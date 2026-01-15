

# 📱 How to Use This Android Project (XML + Java)

This repository contains an Android application built using **Java** and **XML layouts**.
Follow the steps below to run and understand the project in **Android Studio**.

---

## 🔧 Prerequisites

Before starting, make sure you have:

* Android Studio installed (latest version recommended)
* Basic knowledge of Java & XML
* JDK (comes bundled with Android Studio)

---

## 🚀 Step 1: Create a New Android Project

1. Open **Android Studio**
2. Click **New Project**
3. Select **Empty Views Activity**
4. Click **Next**
5. Fill the project details:

   * **Name**: (Any name, e.g., `MyAndroidApp`)
   * **Language**: `Java`
   * **Minimum SDK**: As mentioned in the repo (or choose API 21+)
6. Click **Finish**
7. Wait for Gradle build to complete

---

## 📂 Step 2: Understand the Project Structure

Important folders you’ll use:

```
app/
 ├── java/
 │    └── com.yourpackage.name/
 │         └── MainActivity.java
 │
 └── res/
      ├── layout/
      │     └── activity_main.xml
      └── values/
```

---

## 📄 Step 3: Add Java Code

1. Go to:

   ```
   app > java > com.yourpackage.name
   ```
2. Open `MainActivity.java`
3. Replace the existing code with the **Java code from this repository**
4. Make sure:

   * `package name` matches your project
   * `setContentView()` uses the correct XML file

Example:

```java
setContentView(R.layout.activity_main);
```

---

## 🎨 Step 4: Add XML Layout Files

1. Go to:

   ```
   app > res > layout
   ```
2. Open `activity_main.xml`
3. Replace its content with the **XML code from this repository**
4. Save the file

---

## 🔁 Step 5: Check IDs & Imports

* Ensure all `id`s used in Java exist in XML
* Example:

```xml
<Button
    android:id="@+id/btnClick" />
```

```java
Button btn = findViewById(R.id.btnClick);
```

---

## ▶️ Step 6: Run the App

1. Click **Run ▶️**
2. Choose:

   * Emulator **OR**
   * Physical Android device (USB debugging enabled)
3. App will launch successfully 🎉

---

## 🛠 Common Issues & Fixes

### ❌ Package Name Error

✔ Update package name in Java files to match your project

### ❌ R file not found

✔ Sync Gradle
✔ Check XML syntax errors

### ❌ App crashes

✔ Check **Logcat** for error messages
✔ Verify IDs and imports

---

## 📌 Tech Stack Used

* Language: **Java**
* UI: **XML**
* IDE: **Android Studio**

---

## ⭐ Support

If you find this project helpful:

* ⭐ Star the repository
* 🍴 Fork it
* 🐞 Raise an issue for bugs or suggestions

---
