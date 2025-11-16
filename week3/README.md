# 📘 Week 3 — Navigation, Lists, Async Data & Architecture

This week you will learn how to build multi-screen apps, manage lists efficiently, and fetch async data from APIs using SwiftUI + MVVM.

---

## 🎯 Goals
- Use NavigationStack and NavigationLink
- Understand List, ForEach, and Identifiable
- Load data using async/await
- Build API-driven features
- Apply architecture patterns to real projects

---

## 📅 Daily Topics

### **Day 1 — NavigationStack**
- Push navigation
- Passing data to destination views
- NavigationPath for programmatic routing

### **Day 2 — List & ForEach**
- Identifiable models
- Lazy rendering
- Custom row components

### **Day 3 — Async/Await + task{}**
- Load data automatically on appear
- Handle retry and cancellation

### **Day 4 — API Integration in ViewModel**
- Structuring API services
- Decoding JSON
- Error handling

### **Day 5 — Loading & Error UI**
- ProgressView
- Error views
- State enums (loading/success/failure)

### **Day 6 — Practice**
- Complete multi-screen demo app

### **Day 7 — Review**
- Code review & architecture validation

---

## 📝 Assignment — GitHub Repository Browser

### **Requirements**
- TextField to enter GitHub username  
- Fetch user repositories using async/await  
- Display repo list in `List`  
- Tap item → open detail screen  
- NavigationStack for routing  
- MVVM setup with APIService  

### **Endpoints Example**

`https://api.github.com/users/{username}/repos`

---

## 🔧 Suggested Structure
```
GitHubBrowser/
├─ Models/
├─ ViewModels/
├─ Views/
├─ Services/ (API)
└─ Resources/
```

---

## ✅ Review Checklist
- Navigation is clean and consistent  
- Row views extracted into components  
- API errors handled gracefully  
- No networking code inside Views  
- ViewModels are testable  

---

## 📤 Submission
Push your Week 3 project into `week3/` and share it for review.
