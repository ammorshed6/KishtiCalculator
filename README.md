# 📊 কিস্তি ক্যালকুলেটর

বাংলাদেশের জন্য সম্পূর্ণ বাংলা ভাষায় ঋণের কিস্তি হিসাবের Android অ্যাপ।

## ✨ ফিচার

- **সমান হার (Flat Rate)** — মাসিক কিস্তি হিসাব
- **ক্রমহ্রাসমান ব্যালেন্স (Reducing Balance)** — ধীরে কমা কিস্তি
- **সমান মাসিক কিস্তি (EMI)** — সমান কিস্তির বিস্তারিত বিভাজন
- **বুলেট পেমেন্ট (Bullet Payment)** — শুধু সুদ + শেষে আসল
- **তুলনা চার্ট** — চারটি পদ্ধতির একসাথে তুলনা
- **সম্পূর্ণ শিডিউল** — প্রতি মাসের আসল, সুদ, বাকি ঋণ
- **রিপোর্ট শেয়ার** — WhatsApp/SMS-এ পাঠান

## 🚀 GitHub Actions দিয়ে APK বিল্ড

1. এই repository-তে push করুন
2. **Actions** ট্যাবে যান
3. **Build APK** workflow চলবে স্বয়ংক্রিয়ভাবে
4. সম্পন্ন হলে **Artifacts** থেকে APK ডাউনলোড করুন

## 📁 প্রজেক্ট স্ট্রাকচার

```
KistiCalculator/
├── app/src/main/
│   ├── assets/index.html      ← পুরো অ্যাপ (HTML/CSS/JS)
│   ├── java/.../MainActivity  ← Android WebView wrapper
│   └── res/                   ← আইকন ও লেআউট
├── .github/workflows/build.yml ← স্বয়ংক্রিয় APK বিল্ড
└── build.gradle
```

## 📱 ইন্সটল

APK ডাউনলোড করে ফোনে ইন্সটল করুন।  
প্রথমবার: Settings → Unknown sources → Allow

---
বিজ্ঞাপনমুক্ত | অফলাইনে কাজ করে | সম্পূর্ণ বাংলা
