# Claude-Code-in-Action

---

## 01 🔵 Coding Assistant কী করে?

<img width="736" height="400" alt="image" src="https://github.com/user-attachments/assets/f6e88640-f081-49c4-add8-3fa142ece58e" />

- Language model ব্যবহার করে complex programming tasks handle করে — শুধু code লেখে না, পুরো problem solve করে।
- একজন human developer-এর মতো **3টা ধাপে** কাজ করে:

**🔍 Context বোঝো → 🧠 Plan করো → ⚡ Action নাও**

- **Important:** প্রথম ও শেষ ধাপে "outside world"-এর সাথে interact করতে হয় — files পড়া, commands চালানো ইত্যাদি।

---

## 02 🟡 Tool Use — আসল রহস্য 🔑

- **Problem:** Language model শুধু text in → text out করতে পারে। নিজে থেকে file পড়তে বা command চালাতে পারে না।
- **Solution:** "Tool Use" — model-কে শেখানো হয় কীভাবে action request করতে হয়।

**Tool Use-এর পুরো flow:**

তুমি প্রশ্ন করো → Tool instructions add হয় → Model বলে "ReadFile: x" → Assistant file পড়ে → Content model-কে দেয় → ✅ Final answer পাও

- মানে model আসলে file "পড়ে" না — সে শুধু **carefully formatted text response** তৈরি করে। Assistant বাকি কাজ করে।

---

## 03 🟢 Claude কেন Special? 🌟

সব models tool use-এ সমান না — **Claude (Opus, Sonnet, Haiku)** বিশেষভাবে ভালো।

| সুবিধা | মানে কী |
|---|---|
| 🎯 কঠিন কাজ | Multiple tools combine করে complex tasks handle করে |
| 🔌 Extensible | নতুন tools add করলে Claude নিজেই adapt করে |
| 🔒 Security | Codebase index না করেই কাজ করে — পুরো code বাইরে যায় না |
| ♾️ Longevity | তোমার workflow বদলালেও Claude সাথে থাকবে |

---

## 04 🔴 মনে রাখার 4টা কথা 🧠

① Coding assistants = Language model + Smart tools
② Real-world কাজের জন্য tools ছাড়া model অসহায়
③ সব models tool use-এ equally skilled না
④ Claude-এর strong tool use = better security + customization + longevity

---
