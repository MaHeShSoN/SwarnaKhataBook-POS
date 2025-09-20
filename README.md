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
- **UI**: Material Design 3, Constraint Layout, ViewPager2, Animated Bottom Bar
- **Navigation**: Navigation Component
- **State Management**: LiveData, ViewModel
- **Image Loading**: Picasso, Coil
- **PDF Generation**: PDFBox, Android PDF Viewer
- **Charts**: MPAndroidChart
- **Networking**: OkHttp
- **Async Programming**: Kotlin Coroutines
- **Security**: Biometric Authentication, Security Crypto
- **QR Code**: ZXing Core
- **Signature**: Signature Pad
- **Document Processing**: Apache POI
- **Google Services**: Firebase Suite, Play Billing, App Updates
- **Testing**: JUnit, Mockito, Espresso, Robolectric
- **Dependency Injection**: Manual DI

## 📱 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/d4148c61-01cf-4acf-a5f7-0f318fd6a4ed" width="200"/>
  <img src="https://github.com/user-attachments/assets/258fce69-f431-4a57-8938-38f771b97143" width="200"/>
  <img src="https://github.com/user-attachments/assets/4a7f09f8-89a9-4757-a994-af4298eaef4f" width="200"/>
  <img src="https://github.com/user-attachments/assets/b7c33c61-757a-494c-a262-ccf30ad9d3c2" width="200"/>
  <img src="https://github.com/user-attachments/assets/c7748e62-ad72-439f-ba5b-f99c191578dd" width="200"/>
</p>

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
**SwarnaKhataBook** - Making jewelry business management simple and efficient! 💎✨
