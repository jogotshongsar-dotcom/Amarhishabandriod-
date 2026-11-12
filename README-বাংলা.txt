আমার হিসাব — Android APK প্রজেক্ট

এই ZIP-এ আপনার দেওয়া HTML হিসাব অ্যাপটি Android WebView অ্যাপের মধ্যে চালানোর জন্য সাজানো হয়েছে।
অ্যাপের তথ্য এই ফোনের অ্যাপ-স্টোরেজে (WebView localStorage) থাকবে। অ্যাপের ডেটা মুছে ফেললে হিসাবও মুছে যেতে পারে।

APK বানানোর নিয়ম:
১. কম্পিউটারে Android Studio ইনস্টল করুন।
২. Android Studio থেকে এই ZIP extract করা AmarHisab ফোল্ডারটি Open করুন।
৩. Gradle sync শেষ হতে দিন। Android SDK Platform 35 ইনস্টল করতে বললে ইনস্টল করুন।
৪. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
৫. APK তৈরি হলে Android Studio-র notification থেকে Locate চাপুন।
৬. APK ফোনে পাঠিয়ে ইনস্টল করুন। ফোনে “Install unknown apps” অনুমতি চাইলে শুধু নিজের তৈরি APK-র জন্য অনুমতি দিন।

নোট:
- এই পরিবেশে Android SDK/Gradle build tool নেই, তাই এখানে সরাসরি APK compile করা সম্ভব হয়নি।
- HTML-এ Google Fonts লোডের জন্য ইন্টারনেট লাগতে পারে; মূল হিসাবের কাজ অফলাইনে চলে।
