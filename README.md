# 🕌 AlZafar Shopping

AlZafar is a beautifully designed, secure, and scalable cross-platform e-commerce Flutter app with full support for Arabic (RTL) and English. Inspired by the grandeur of Arabian castles, the app is built with clean architecture, modular BLoC state management, and secure best practices.

## 🚀 Features

- 📱 Flutter-based cross-platform (iOS & Android)
- 🧠 BLoC for scalable state management
- 🌍 English & Arabic support (RTL)
- 🎨 Dark mode by default + light mode toggle
- 🏰 Arabian UI elements (domes, arches, filigree)
- 🔐 JWT-based authentication
- 🛒 Cart, Wishlist, Orders, Profile, Checkout
- 💳 Stripe or HyperPay payment integration
- 🧪 Unit, widget & integration tests
- 🛠️ CI/CD-ready
- 🛍️ Single seller (branded store)

---

## 🧱 Tech Stack

| Layer         | Tech Used                        |
|---------------|----------------------------------|
| **Frontend**  | Flutter, BLoC                    |
| **Languages** | Dart, JSON                       |
| **Backend**   | Node.js or Django                |
| **Payments**  | Stripe or HyperPay               |
| **State Mgmt**| flutter_bloc                     |
| **Testing**   | flutter_test, integration_test   |
| **CI/CD**     | GitHub Actions                   |

---

## 🧩 Project Structure

```
lib/
├── core/
│   ├── config/
│   ├── constants/
│   ├── localization/
│   ├── services/
│   └── utils/
├── data/
├── bloc/
├── presentation/
└── main.dart
```

---

## 🏗️ Build Flavors

```bash
flutter run --flavor android_ar -t lib/main.dart
flutter run --flavor android_en -t lib/main.dart
flutter run --flavor ios_ar -t lib/main.dart
flutter run --flavor ios_en -t lib/main.dart
```

---

## 🌍 Localization

- `assets/lang/en.json`
- `assets/lang/ar.json`
- Uses `easy_localization` for dynamic language switching
- RTL support is automatically enabled for Arabic

---

## 🌗 Themes

- Default: **Dark Theme**
- Toggle to Light Theme
- Arabian color palette: deep indigo, gold, plum
- Fonts: Cairo / Tajawal
- Optional mosque filigree pattern backgrounds

---

## 🤝 Contributing

We welcome contributions from the community!

### ✅ Steps to Contribute

> This follows the **fork-and-PR** model used in open source and at Google-scale projects.

#### 1. Fork the Repository

Go to [https://github.com/YOUR_USERNAME/alzafar_shopping](https://github.com/YOUR_USERNAME/alzafar_shopping) and click `Fork`.

#### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/alzafar_shopping.git
cd alzafar_shopping
```

#### 3. Create a Branch

```bash
git checkout -b feature/your-feature-name
```

#### 4. Make Changes and Commit

```bash
git add .
git commit -m "feat: short description of what you did"
```

#### 5. Push Your Branch

```bash
git push origin feature/your-feature-name
```

#### 6. Create a Pull Request

- Go to your fork on GitHub
- Click "Compare & pull request"
- Fill in title and description following the standards below

---

## 📋 Pull Request Guidelines (Based on Google Engineering Standards)

- ✅ **Title** should use conventional commits:  
  `feat:`, `fix:`, `chore:`, `refactor:`, `test:`, `docs:`

  Example: `feat: add RTL support for cart screen`

- ✅ **Description** should answer:
  - What is the problem you're solving?
  - What changes did you make?
  - Any trade-offs or follow-up tasks?

- ✅ **Tests**: Add tests for any business logic or UI components

- ✅ **Linter**: Ensure your code is formatted (`flutter format .`) and passes analysis

- ✅ **Small commits**: Keep PRs under 300 lines if possible. Split into multiple PRs if needed

- ✅ **Screenshots** (if UI): Include before/after images or GIFs

- ✅ **Review Feedback**: Address comments respectfully, update code, and mark resolved

---

## 🧪 Testing

```bash
flutter test                # Unit & widget tests
flutter test integration_test # E2E
```

Coming Soon:
- GitHub Actions CI for lint + test on PRs

---

## 🔒 Security Best Practices

- Uses HTTPS + secure headers
- Token storage via `flutter_secure_storage`
- Input sanitization & validation
- JWT authentication
- Brute-force protection (backend)
- Future: 2FA support

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 🧠 Credits

Crafted with ❤️ and coffee by Mehdi and Ameer.  
Inspired by Arabian architecture and modern app principles.
