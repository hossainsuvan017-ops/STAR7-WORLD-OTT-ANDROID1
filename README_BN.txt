STAR 7 WORLD OTT — Android project source (not a compiled APK)

এই প্রজেক্টে আপনার সর্বশেষ Subscription Expiry & Renew HTML ফাইলটি app/src/main/assets/index.html হিসেবে অপরিবর্তিত রাখা হয়েছে।

Android Studio বা Android SDK-সহ Gradle build পরিবেশে খুলে APK build করা যাবে।
প্রয়োজন: Android SDK 35, JDK 17, Android Gradle Plugin 8.7.3 এবং Gradle 8.9।
এই ZIP-এ Gradle wrapper বা compiled APK নেই।

সীমাবদ্ধতা:
- WebView wrapper, production-ready streaming service নয়।
- Google Play Billing বা নিরাপদ backend এখনো সংযুক্ত নয়।
- অ্যাকাউন্ট ও owner controls কেবল local HTML storage-ভিত্তিক।
- অ্যাপ আনইনস্টল বা data clear করলে locally saved media হারাতে পারে।
- file:// WebView-তে কিছু IndexedDB বা media ফিচার ডিভাইসভেদে সীমাবদ্ধ হতে পারে।
- Android 15 / target SDK 35 edge-to-edge UI testing প্রয়োজন।
- বাস্তব APK ও ফোনে পরীক্ষিত নয়।

প্রোডাকশনে HTTPS-hosted backend, server-side authorization, DRM/offline licensing, Play Billing verification এবং নিরাপদ content storage প্রয়োজন।
