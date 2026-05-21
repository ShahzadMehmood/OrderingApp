# 🍔 Food Ordering App — Restaurant Admin Panel

An Android app built for restaurant admins to manage incoming orders in real time, handle order fulfillment, and print receipts via Bluetooth — all from a tablet or phone.

![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)
![Language](https://img.shields.io/badge/Language-Kotlin-purple?logo=kotlin)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-blue)
![Bluetooth](https://img.shields.io/badge/Bluetooth-Printer-orange)
![Min SDK](https://img.shields.io/badge/Min%20SDK-21-red)

---

## ✨ Features

- 📦 Real-time order management — view and handle incoming orders live
- 🔔 Instant notifications for new and updated orders
- ✅ Order status tracking — from pending to completed
- 🖨️ Bluetooth printer integration for on-the-spot receipt printing
- 👥 User management — add staff and manage access rights
- 🗂️ Full order history and fulfillment flow

---

## 📸 Screenshots

<p>
  <img src="https://user-images.githubusercontent.com/74652787/257817828-ea56d122-f3f2-4696-a0be-4a1b83a42711.jpg" width="180"/>
  <img src="https://user-images.githubusercontent.com/74652787/257817884-f0b9e14b-f8bd-493c-95de-31705a8d464d.jpg" width="180"/>
  <img src="https://user-images.githubusercontent.com/74652787/257817913-808031a3-e8cd-41fe-8237-582f5fa02d06.jpg" width="180"/>
  <img src="https://user-images.githubusercontent.com/74652787/257817985-20dfe896-c65f-4630-9aa4-fe25bc3d38a1.jpg" width="180"/>
</p>

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Kotlin, Java |
| Architecture | MVVM |
| Printing | Printooth (Bluetooth Printer Library) |
| Backend | REST API — [freeorder.co.uk](https://portal.freeorder.co.uk/Home/Index) |
| Notifications | Firebase Cloud Messaging |
| UI | XML Layouts, Material Design |
| Build | Gradle |

---

## 🏗️ Architecture

```
app/
├── ui/
│   ├── MainActivity.kt
│   ├── OrderListFragment.kt
│   └── OrderDetailActivity.kt
├── viewmodel/
│   └── OrderViewModel.kt
├── repository/
│   └── OrderRepository.kt
├── model/
│   └── Order.kt
└── utils/
    └── PrinterHelper.kt
printooth/              ← Bluetooth printer module
```

---

## 🚀 Getting Started

### Prerequisites
- Android Studio Hedgehog or newer
- Min SDK 21 / Target SDK 34
- A Bluetooth thermal printer for receipt testing

### Setup

1. Clone the repo
```bash
git clone https://github.com/ShahzadMehmood/OrderingApp.git
```
2. Open in Android Studio
3. Sync Gradle
4. Run on a physical device (Bluetooth required for printer features)

---

## 👨‍💻 Author

**Shahzad Mehmood** — Senior Android Developer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/shahzad-mehmood-aa92aa275/)
[![Upwork](https://img.shields.io/badge/Upwork-Top%20Rated-brightgreen?logo=upwork)](https://www.upwork.com/freelancers/~0186d5f4f78c448ee8)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/ShahzadMehmood)

---

## 📄 License

Licensed under the [MIT License](https://opensource.org/licenses/MIT).

<h1>Screenshots</h1>

![IMG-20230802-WA0006](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/ea56d122-f3f2-4696-a0be-4a1b83a42711)
![IMG-20230802-WA0003](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/f0b9e14b-f8bd-493c-95de-31705a8d464d)
![IMG-20230802-WA0002](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/808031a3-e8cd-41fe-8237-582f5fa02d06)
![IMG-20230802-WA0005](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/20dfe896-c65f-4630-9aa4-fe25bc3d38a1)
![IMG-20230802-WA0007](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/f963622c-d483-433b-a283-4ee5def5f2cb)
![IMG-20230802-WA0004](https://github.com/ShahzadMehmood/OrderingApp/assets/74652787/9520e9b1-c15c-42ad-8583-82a71a9cc5b2)

Getting Started
Follow these instructions to set up the Food Ordering App for Admin on your local development environment:

Install dependencies: cd food-ordering-app and npm install
Configure the Backend: Refer to the backend/README.md for setting up the backend server.
Run the App: npm start to launch the development server and access the app at (https://portal.freeorder.co.uk/Home/Index)
Contributing
We welcome contributions to improve the Food Ordering App for Admin. To contribute, follow these steps:

Fork the repository
Create your feature branch: git checkout -b feature/YourFeature
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/YourFeature
Submit a pull request to the main branch.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Support
For any questions or issues, feel free to contact us at shahzadmehmood1246@gmail.com

Acknowledgments
We would like to express our gratitude to the open-source community for the tools and libraries that made this project possible.

Feel free to modify the template according to your specific project details. Make sure to add your project's logo, relevant screenshots, and modify the links accordingly. The README should be concise, yet informative, to attract potential contributors and users to your Food Ordering App for Admin.




