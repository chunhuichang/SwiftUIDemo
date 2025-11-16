# 📘 Week 2 — SwiftUI Data Flow & MVVM

This week focuses on understanding how data moves through SwiftUI.  
You will master State, Binding, ObservableObject, ViewModel patterns, and the Environment system.

---

## 🎯 Goals
- Learn how SwiftUI updates UI in response to data changes
- Understand the roles of:
  - `@State`
  - `@Binding`
  - `@ObservedObject`
  - `@ObservableObject`
  - `@Published`
  - `@EnvironmentObject`
- Build SwiftUI screens using MVVM architecture
- Use async/await or Combine inside ViewModel

---

## 📅 Daily Topics

### **Day 1 — State & Binding Deep Dive**
- Difference between `@State` vs `@Binding`
- Best practices: state ownership, lifting state up

### **Day 2 — ObservableObject & @Published**
- Creating ViewModels
- Observable change notifications
- Structuring data models

### **Day 3 — Environment & EnvironmentObject**
- Passing shared state across many views
- Avoiding “prop-drilling”
- Testing EnvironmentObject

### **Day 4 — MVVM in SwiftUI**
- How Views depend on ViewModels
- Inputs / Outputs
- Clean state separation

### **Day 5 — Networking in SwiftUI**
- Using async/await in ViewModels
- Handling loading + error states

### **Day 6 — Practice App**
- Small multi-screen project
- Use full data flow patterns

### **Day 7 — Review & Cleanup**
- Code review checklist
- Architecture improvements

---

## 📝 Assignment — To-Do List App

### **Requirements**
- Add new tasks
- Mark tasks as completed
- Delete tasks
- Display tasks in a List
- Use a ViewModel with `@Published`
- Share state via `@EnvironmentObject`

### **Suggested File Structure**

```
ToDoApp/
├─ Models/
├─ ViewModels/
├─ Views/
└─ Resources/
```

---

## ✅ Review Checklist
- ViewModel owns all business logic
- UI has no logic except rendering
- Property wrappers used correctly
- Data flow is predictable and stable

---

## 📤 Submission
Push your Week 2 project to GitHub under `week2/` and share the link for review.
