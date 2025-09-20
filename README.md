# SwarnaKhataBook 📱💎

A comprehensive Point of Sale (POS) application designed specifically for jewelry businesses. Built with modern Android development practices using Kotlin, this app helps jewelry shop owners manage their inventory, customers, sales, and business operations efficiently.

[![Download on Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.jewelrypos.swarnakhatabook)

**Download from Google Play Store**: [Swarna Khata Book](https://play.google.com/store/apps/details?id=com.jewelrypos.swarnakhatabook)

## 🌟 Features

### 🏪 Multi-Shop Management
- **Multiple Shop Support**: Manage multiple jewelry shops under a single account
- **Shop Switching**: Easy switching between different shops with isolated data
- **Shop Creation**: Create and configure new shops with business details
- **Data Isolation**: Each shop maintains its own separate data and transactions

### 💰 Sales & Invoicing
- **Invoice Generation**: Create professional invoices with customizable templates
- **PDF Export**: Generate and share invoices as PDF documents
- **Payment Tracking**: Track partial payments and outstanding balances
- **WhatsApp Integration**: Send invoices directly via WhatsApp
- **QR Code Support**: Generate QR codes for easy payment processing

### 📦 Inventory Management
- **Jewelry Items**: Add and manage gold, silver, and other jewelry items
- **Category Management**: Organize items by categories and types
- **Stock Tracking**: Monitor stock levels and values
- **Purity Tracking**: Track gold/silver purity (e.g., 22K, 91.66%)
- **Location Management**: Track item locations within the shop

### 👥 Customer Management
- **Customer Database**: Store customer information and contact details
- **Customer Types**: Support for both retail customers and wholesalers
- **Balance Tracking**: Track customer outstanding balances
- **Purchase History**: View complete customer purchase history
- **GST Support**: Handle GST numbers for business customers

### 📊 Business Analytics
- **Dashboard**: Overview of sales, inventory, and customer metrics
- **Reports**: Generate detailed business reports
- **Charts & Graphs**: Visual representation of business data
- **Sales Analytics**: Track sales performance and trends

### 🔐 Security Features
- **PIN Protection**: Secure app access with 4-digit PIN
- **Biometric Authentication**: Fingerprint/Face unlock support
- **Data Encryption**: Secure storage of sensitive business data
- **Emergency Wipe**: PIN reverse entry to wipe data in emergencies

### 🔔 Notifications & Updates
- **Push Notifications**: Firebase-powered notifications
- **App Updates**: Automatic app update management
- **In-App Review**: Integrated Google Play review system
- **Subscription Management**: Handle premium features and billing

## 🛠️ Technical Stack

- **Language**: Kotlin
- **Architecture**: MVVM with Repository Pattern
- **Database**: 
  - Firebase Firestore (Cloud)
  - Room Database (Local)
- **UI**: Material Design 3
- **Navigation**: Navigation Component
- **State Management**: LiveData, ViewModel
- **Image Loading**: Picasso
- **PDF Generation**: PDFBox
- **Charts**: MPAndroidChart
- **Dependency Injection**: Manual DI
- **Testing**: JUnit, Mockito, Espresso

## 📱 Screenshots

![App Screenshot 1](https://github.com/user-attachments/assets/d4148c61-01cf-4acf-a5f7-0f318fd6a4ed)

![App Screenshot 2](https://github.com/user-attachments/assets/258fce69-f431-4a57-8938-38f771b97143)

![App Screenshot 3](https://github.com/user-attachments/assets/4a7f09f8-89a9-4757-a994-af4298eaef4f)

![App Screenshot 4](https://github.com/user-attachments/assets/b7c33c61-757a-494c-a262-ccf30ad9d3c2)

![App Screenshot 5](https://github.com/user-attachments/assets/c7748e62-ad72-439f-ba5b-f99c191578dd)

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK 26+ (Android 8.0+)
- Kotlin 1.8+
- Firebase project setup

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/SwarnaKhataBook.git
   cd SwarnaKhataBook
   ```

2. **Open in Android Studio**
   - Open Android Studio
   - Select "Open an existing project"
   - Navigate to the cloned directory

3. **Firebase Setup**
   - Create a new Firebase project
   - Add your Android app to the project
   - Download `google-services.json` and place it in the `app/` directory
   - Enable Firestore, Authentication, and Cloud Messaging

4. **Build and Run**
   ```bash
   ./gradlew assembleDebug
   ```

## 📁 Project Structure

```
app/
├── src/main/java/com/jewelrypos/swarnakhatabook/
│   ├── Adapters/              # RecyclerView adapters
│   ├── BottomSheet/           # Bottom sheet components
│   ├── DataClasses/           # Data models and entities
│   ├── Enums/                 # Enumeration classes
│   ├── Events/                # Event handling
│   ├── Factorys/              # ViewModel factories
│   ├── Repository/            # Data repositories
│   ├── Services/              # Background services
│   ├── Utilitys/              # Utility classes
│   ├── ViewModle/             # ViewModels
│   └── MainActivity.kt        # Main activity
├── src/main/res/
│   ├── layout/                # XML layouts
│   ├── values/                # Strings, colors, themes
│   ├── drawable/              # Icons and images
│   └── navigation/            # Navigation graphs
└── build.gradle.kts           # App-level build configuration
```

## 🔧 Configuration

### Firebase Configuration
1. Create a Firebase project
2. Enable Authentication (Phone)
3. Enable Firestore Database
4. Enable Cloud Messaging
5. Add your app's SHA-1 fingerprint

### App Configuration
- Update `google-services.json` with your Firebase configuration
- Configure notification channels in `NotificationChannelManager`
- Set up billing for premium features (if applicable)

## 📋 Key Features Implementation

### Multi-Shop Architecture
- **SessionManager**: Manages active shop context
- **ShopManager**: Handles shop CRUD operations
- **Data Isolation**: Each shop has separate Firestore collections

### Invoice System
- **PDF Generation**: Custom PDF templates for invoices
- **WhatsApp Integration**: Direct sharing via WhatsApp
- **Payment Tracking**: Support for partial and full payments

### Security Implementation
- **PIN Security**: Encrypted PIN storage
- **Biometric Auth**: Android BiometricPrompt integration
- **Data Encryption**: Secure preferences for sensitive data

## 🧪 Testing

The project includes comprehensive testing:
- **Unit Tests**: Repository and ViewModel testing
- **Integration Tests**: End-to-end feature testing
- **UI Tests**: Espresso-based UI testing

Run tests:
```bash
./gradlew test
./gradlew connectedAndroidTest
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support and questions:
- Create an issue in this repository
- Contact: goldinvoice0@gmail.com
- **Download the app**: [Google Play Store](https://play.google.com/store/apps/details?id=com.jewelrypos.swarnakhatabook)

## 🎯 Roadmap

- [ ] Multi-language support
- [ ] Advanced reporting features
- [ ] Barcode scanning for inventory
- [ ] Cloud backup and sync
- [ ] Advanced analytics dashboard
- [ ] Integration with accounting software

## 🙏 Acknowledgments

- Material Design 3 for beautiful UI components
- Firebase for backend services
- MPAndroidChart for data visualization
- PDFBox for PDF generation
- All contributors and testers

---

**SwarnaKhataBook** - Making jewelry business management simple and efficient! 💎✨
