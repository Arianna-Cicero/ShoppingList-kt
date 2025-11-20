# 🛒 ShoppingList (Kotlin + Android + Firebase)

A modern Android application built with **Kotlin**, **Jetpack Compose**,
**MVVM**, and **Firebase**, designed to manage shopping lists, products,
and carts in a clean and intuitive way.

This project was created as part of a learning and development exercise
focusing on **Compose UI**, **modular architecture**, and **real-time
Firebase integration**.

## 🚀 Features

-   🔐 **Firebase Authentication** (Login)
-   🧺 **Cart management**
    -   Add products to cart\
    -   Remove items\
    -   View total items\
-   📦 **Product management**
    -   Create and view product entries\
    -   Product screens built with Jetpack Compose\
-   📱 **Modern UI**
    -   Jetpack Compose\
    -   Navigation\
    -   Custom theme\
-   🗂️ **Clean Architecture**
    -   Models\
    -   Repositories\
    -   UI Screens

## 🛠️ Tech Stack

### **Frontend / Android**

-   **Kotlin**
-   **Jetpack Compose**
-   **Material 3**
-   **Android ViewModel**
-   **Navigation Compose**
-   **Dependency Injection (AppModule.kt)**

### **Backend**

-   **Firebase Authentication**
-   **Firebase Cloud Firestore**
-   **Firebase Storage (optional)**

## 🔧 Setup Instructions

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/Arianna-Cicero/ShoppingList-kt.git
cd ShoppingList-kt
```

### 2️⃣ Open the project

Open the project in **Android Studio (latest version recommended)**.

### 3️⃣ Configure Firebase

Place your **google-services.json** file under:

    app/google-services.json

⚠️ Do **NOT** reuse the existing file in the repository if you fork this
project.

### 4️⃣ Build & Run

Click **Run ▶️** in Android Studio.

## 📚 Architecture Overview

### **Model Layer**

-   Data classes such as `Product.kt` and `Cart.kt`

### **Repository Layer**

-   Firebase communication\
-   `LoginRepository.kt`, `CartRepository.kt`, etc.

### **UI Layer**

-   Jetpack Compose screens\
-   Modules for login, product management, carts, theme, etc.

## 🔌 Firebase Integration

✔️ Authentication\
✔️ Firestore storage\
✔️ Centralized configuration

## 🧪 Future Improvements

-   Add user registration\
-   Product categories\
-   Offline Room database\
-   UI animations\
-   Unit testing

## 🤝 Contributing

PRs and suggestions are welcome!

## 📄 License

This project is under the MIT License.
