# 🔥 ActionDispatcher

A flexible command dispatch framework for Android, Kotlin, and server-side JVM applications.  
It enables you to map string actions to handlers, support dynamic registration, middlewares, execution queues, and priority scheduling.

---

## ✨ Features
✅ Command Pattern based action dispatch  
✅ Dynamic action registration  
✅ Middleware chain (logging, permissions, etc.)  
✅ Synchronous/Asynchronous queue execution  
✅ Priority action queue  
✅ Extensible parser for protocols like JSON, Protobuf  
✅ Ready-to-use demo

---

## 🚀 Quick Start

1️⃣ Register actions:
```kotlin
ActionCenter.register("OPEN_REST_MODE") { intent -> println("Rest mode opened") }
