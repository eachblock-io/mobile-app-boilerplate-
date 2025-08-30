# 📱 EachBlock Mobile App Boilerplate  
````markdown
 

A production-ready **React Native + TypeScript** boilerplate maintained by **EachBlock** for building scalable, secure, and high-quality mobile apps.  

This boilerplate includes everything we believe every mobile app should start with — from authentication to performance optimizations, notifications, analytics, and CI/CD setup. It ensures consistency, saves development time, and guarantees all projects meet our internal quality standards.  

---

## ✨ Features Included  
- 🚀 Latest **React Native** with **TypeScript**  
- 🗂️ Clean **feature-based folder structure**  
- 🛠️ Pre-configured **Redux Toolkit** & **React Query**  
- 🔑 Authentication (email, social logins, Firebase/JWT ready)  
- 🖼️ Onboarding + reusable **UI components (design system)**  
- 🔔 Push notifications (FCM/OneSignal ready)  
- 📊 Analytics integration (Firebase/Amplitude)  
- ⚡ Performance optimizations (lazy loading, caching, offline support)  
- 🔐 Secure token storage (Keychain/Keystore)  
- 🆕 **App Update Modal** (force & optional updates)  
- 🧪 Testing setup (Jest + React Native Testing Library)  
- 🔄 CI/CD ready (Fastlane / GitHub Actions)  
- 📖 Documentation boilerplate (README, Changelog, API docs)  

---

## 📦 Getting Started  

```bash
# Clone the repo
git clone https://github.com/eachblock/mobile-app-boilerplate.git

# Install dependencies
yarn install

# Run on iOS
yarn ios

# Run on Android
yarn android
````

---

## 📋 Project Structure

```
src/
 ├─ components/     → reusable UI components
 ├─ features/       → feature-based modules (auth, profile, etc.)
 ├─ hooks/          → custom hooks
 ├─ navigation/     → stack + tab navigation setup
 ├─ services/       → API clients, Firebase, storage
 ├─ store/          → Redux Toolkit slices
 ├─ utils/          → helpers (validation, formatting)
```

---

## 🛡️ Why This Boilerplate?

At **EachBlock**, we believe every app should start from a strong foundation. This boilerplate ensures:

* Faster delivery 🚀
* Consistent code quality ✅
* Built-in best practices 🔒
* Reduced bugs & technical debt ⚡

---

## 👥 Contribution Guidelines

We welcome improvements to the boilerplate! Please follow these guidelines when contributing:

### 🔹 Branching Strategy

* `main` → always stable, production-ready.
* `develop` → active development branch.
* `feature/*` → for new features or modules.
* `fix/*` → for bug fixes.

### 🔹 Commit Convention

Follow [Conventional Commits](https://www.conventionalcommits.org/):

* `feat:` → for new features
* `fix:` → for bug fixes
* `docs:` → documentation changes
* `chore:` → tooling/config updates
* `refactor:` → code refactors (no feature change)
* `test:` → adding or updating tests

Example:

```
feat(auth): add Google login support
fix(api): handle token refresh on 401
```

### 🔹 Pull Requests

1. Fork or branch from `develop`.
2. Ensure your branch is up to date with `develop`.
3. Run `yarn lint` & `yarn test` before submitting.
4. Provide a clear PR description (what was changed, why, screenshots if UI).
5. At least one reviewer must approve before merging.

### 🔹 Code Style

* Prettier & ESLint are enforced.
* Use TypeScript for all files.
* Keep components small, reusable, and feature-based.

---

## 👥 Maintainers

Maintained by **EachBlock Engineering Team**.
