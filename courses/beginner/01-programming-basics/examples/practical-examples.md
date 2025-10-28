 💻 أمثلة عملية حية - المتغيرات وأنواع البيانات



## 🎯 أمثلة من الحياة الواقعية

### مثال 1: نظام تسجيل المستخدمين
```javascript
// بيانات مستخدم جديد
let userName = "سارة أحمد";
let userEmail = "sara@example.com";
let userAge = 28;
let isVerified = false;
let registrationDate = "2024-01-15";

console.log("👉 بيانات المستخدم:");
console.log("الاسم:", userName);
console.log("البريد:", userEmail);
console.log("العمر:", userAge);
console.log("مفعل:", isVerified ? "نعم" : "لا");
console.log("تاريخ التسجيل:", registrationDate);
مثال 2: نظام المتجر الإلكتروني
javascript
// منتج في المتجر
let productName = "iPhone 14";
let productPrice = 3500;
let inStock = true;
let discount = 0.15; // 15%
let finalPrice = productPrice * (1 - discount);

console.log("🛒 تفاصيل المنتج:");
console.log("المنتج:", productName);
console.log("السعر الأصلي:", productPrice + " ريال");
console.log("السعر بعد الخصم:", finalPrice + " ريال");
console.log("متوفر:", inStock ? "نعم" : "لا");
مثال 3: حاسبة القروض
javascript
// حساب قرض سيارة
let loanAmount = 50000;
let interestRate = 0.05; // 5%
let loanTerm = 5; // سنوات

let totalInterest = loanAmount * interestRate * loanTerm;
let totalPayment = loanAmount + totalInterest;
let monthlyPayment = totalPayment / (loanTerm * 12);

console.log("💰 تفاصيل القرض:");
console.log("مبلغ القرض:", loanAmount + " ريال");
console.log("إجمالي الفائدة:", totalInterest + " ريال");
console.log("إجمالي السداد:", totalPayment + " ريال");
console.log("القسط الشهري:", monthlyPayment.toFixed(2) + " ريال");
🔧 أمثلة تفاعلية
مثال 4: محول الوحدات
javascript
// محول من كيلومتر إلى ميل
let kilometers = 100;
let miles = kilometers * 0.621371;

console.log("📏 محول المسافات:");
console.log(kilometers + " كم = " + miles + " ميل");

// محول من درجة مئوية إلى فهرنهايت
let celsius = 25;
let fahrenheit = (celsius * 9/5) + 32;
console.log(celsius + "°C = " + fahrenheit + "°F");
مثال 5: منشئ السيرة الذاتية
javascript
// بيانات شخصية
let person = {
    name: "محمد عبدالله",
    jobTitle: "مطور ويب",
    experience: 3,
    skills: ["JavaScript", "HTML", "CSS", "Node.js"],
    available: true
};

let cv = `
🎯 السيرة الذاتية
الاسم: ${person.name}
المسمى الوظيفي: ${person.jobTitle}
سنوات الخبرة: ${person.experience}
المهارات: ${person.skills.join(" - ")}
الحالة: ${person.available ? "متاح للعمل" : "غير متاح"}
`;

console.log(cv);
🎮 أمثلة الألعاب البسيطة
مثال 6: لعبة تخمين الرقم
javascript
// إعدادات اللعبة
let targetNumber = 42;
let playerGuess = 35;
let attempts = 1;
let maxAttempts = 5;

console.log("🎮 لعبة تخمين الرقم");
console.log("المحاولة:", attempts);
console.log("تخمينك:", playerGuess);

if (playerGuess === targetNumber) {
    console.log("🎉 أحسنت! لقد فزت!");
} else if (playerGuess < targetNumber) {
    console.log("📈 الرقم أكبر من هذا");
} else {
    console.log("📉 الرقم أصغر من هذا");
}
💡 نصائح للتطبيق
جرب تعديل القيم وشاهد كيف يتغير الناتج

أضف متغيرات جديدة تناسب مشاريعك

استخدم console.log لمتابعة القيم

حول الأمثلة إلى دوال قابلة لإعادة الاستخدام

