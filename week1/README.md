# 📘 Week 1 — SwiftUI Fundamentals & Layout

**One-Month SwiftUI Learning Plan｜Week 1**

---

## 🎯 Goals for This Week

Develop a solid understanding of SwiftUI fundamentals, including:

- Declarative UI mindset (vs UIKit’s imperative approach)    
- VStack / HStack / ZStack    
- `frame`, `padding`, `background`, `cornerRadius`, `shadow`    
- Text / Image / Button basics    
- Understanding `@State` and `@Binding`    
- Building a simple, complete SwiftUI screen

---

## 📅 Weekly Schedule (One Topic per Day)

### **Day 1 — Declarative Thinking in SwiftUI**

- Views are value types (struct) instead of classes    
- `body` describes UI instead of directly manipulating it    
- Rendering is data-driven (no `reloadData` / `setNeedsLayout`)

---

### **Day 2 — VStack / HStack / ZStack + Frame & Alignment**

- VStack / HStack as SwiftUI equivalents of UIStackView    
- ZStack for overlays and layered layouts    
- Understanding `.frame(width:height:alignment:)`    
- Alignment and spacing behavior

---

### **Day 3 — Modifiers (padding, background, cornerRadius, shadow)**

- Modifiers create **new** views, not mutate existing ones    
- Importance of modifier order    
- Optional: build a simple card-style view

---

### **Day 4 — Common Views: Text / Image / Button**

- Text: font, weight, multiline behavior    
- Image: resizable, scaledToFit/Fill    
- Button modern syntax with action + label

---

### **Day 5 — State Management: `@State` & `@Binding`**

- `@State` for local view state    
- `@Binding` for parent → child state sharing    
- Build a toggle show/hide small practice

---

### **Day 6 — Integration Practice**

Combine everything from this week into a small UI:

- One screen    
- Layout + basic interactive state    
- Simple styling with modifiers

---

### **Day 7 — Self Review (or submit to ChatGPT for review)**

Check your work for:

- Clean modifier order    
- Correct state placement    
- Stable layout behavior    
- View structure clarity

---

## 📝 **Week 1 Assignment: Personal Profile Card**

Build a simple SwiftUI “Profile Card” screen containing:

- A profile photo (Image)    
- Your name (Text)
- A short introduction (Text)
- A `Show More` button
- Pressing the button uses `@State` to reveal extra details  
    (e.g., hobbies, skills, contact info)


### Suggested Structure

```
ProfileView
 ├─ VStack
 │   ├─ Image("your_photo")
 │   ├─ Text("Your Name")
 │   ├─ Text("Short intro")
 │   ├─ Button("Show More")
 │   └─ if showMore { Text("More details…") }
```

### Review Checklist

- Modifier order is clean and intentional    
- Layout is stable across devices    
- `@State` is in the correct place    
- Complex view parts extracted into smaller components

---

## ✔ Next Week Preview (Week 2)

- `@ObservableObject`    
- `@Published`    
- `@EnvironmentObject`    
- SwiftUI data flow deep dive    
- MVVM structure in SwiftUI

---

## 📤 Submission Workflow

1. Create a GitHub repo for the 1-month learning plan    
2. Put this file as:  
    `week1/README.md`    
3. Add your assignment in the same folder    
4. Share the repo link    
5. I will review your Week 1 project with detailed feedback