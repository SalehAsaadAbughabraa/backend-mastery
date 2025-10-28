# 🏆 المشاريع المصغرة - المستوى الأول


## 🎯 مشروع 1: الآلة الحاسبة البسيطة

### 📝 المتطلبات:
- تقوم بالعمليات الحسابية الأساسية
- تخزن النتائج في متغيرات
- تعرض النتائج بشكل منظم

### 💻 الكود:
```javascript
// الآلة الحاسبة البسيطة
let num1 = 15;
let num2 = 3;

// العمليات الحسابية
let addition = num1 + num2;
let subtraction = num1 - num2;
let multiplication = num1 * num2;
let division = num1 / num2;
let modulus = num1 % num2;

// عرض النتائج
console.log("🧮 الآلة الحاسبة البسيطة");
console.log(num1 + " + " + num2 + " = " + addition);
console.log(num1 + " - " + num2 + " = " + subtraction);
console.log(num1 + " × " + num2 + " = " + multiplication);
console.log(num1 + " ÷ " + num2 + " = " + division);
console.log(num1 + " % " + num2 + " = " + modulus);
🎯 مشروع 2: نظام إدارة الطلاب
📝 المتطلبات:
تخزين بيانات طالب

حساب المعدل التراكمي

تحديد حالة النجاح/الرسوب

💻 الكود:
javascript
// نظام إدارة الطلاب
let studentName = "فاطمة محمد";
let studentGrade = 85;
let maxGrade = 100;
let passingGrade = 50;

// حساب النسبة المئوية
let percentage = (studentGrade / maxGrade) * 100;
let isPassed = studentGrade >= passingGrade;

// تقرير الطالب
console.log("🎓 نظام إدارة الطلاب");
console.log("اسم الطالب:", studentName);
console.log("الدرجة:", studentGrade + "/" + maxGrade);
console.log("النسبة المئوية:", percentage + "%");
console.log("الحالة:", isPassed ? "ناجح 🎉" : "راسب ❌");
🎯 مشروع 3: محول العملات
📝 المتطلبات:
تحويل من ريال سعودي إلى عملات أخرى

عرض جميع التحويلات في وقت واحد

تحديث الأسعار بسهولة

💻 الكود:
javascript
// محول العملات
let sarAmount = 100; // المبلغ بالريال السعودي

// أسعار الصرف
let usdRate = 0.27;  // USD
let eurRate = 0.24;  // EUR
let gbpRate = 0.21;  // GBP
let aedRate = 0.98;  // AED

// التحويلات
let usdAmount = sarAmount * usdRate;
let eurAmount = sarAmount * eurRate;
let gbpAmount = sarAmount * gbpRate;
let aedAmount = sarAmount * aedRate;

// النتائج
console.log("💱 محول العملات");
console.log(sarAmount + " ريال سعودي =");
console.log("💰 " + usdAmount.toFixed(2) + " دولار أمريكي");
console.log("💶 " + eurAmount.toFixed(2) + " يورو");
console.log("💷 " + gbpAmount.toFixed(2) + " جنيه إسترليني");
console.log("🏙️ " + aedAmount.toFixed(2) + " درهم إماراتي");
🎯 مشروع 4: منشئ البطاقات الشخصية
📝 المتطلبات:
إنشاء بطاقة شخصية متكاملة

استخدام كائنات ومصفوفات

تنسيق الإخراج بشكل جميل

💻 الكود:
javascript
// منشئ البطاقات الشخصية
let person = {
    arabicName: "خالد أحمد",
    englishName: "Khaled Ahmed", 
    age: 28,
    job: "مطور برمجيات",
    skills: ["JavaScript", "Python", "SQL", "Git"],
    contact: {
        email: "khaled@example.com",
        phone: "+966500000000"
    }
};

// إنشاء البطاقة
let businessCard = `
=================================
           🪪 البطاقة الشخصية
=================================
الاسم: ${person.arabicName}
Name: ${person.englishName}
العمر: ${person.age}
الوظيفة: ${person.job}
المهارات: ${person.skills.join(" • ")}
---------------------------------
📧 ${person.contact.email}
📞 ${person.contact.phone}
=================================
`;

console.log(businessCard);
🎯 مشروع 5: حاسبة اللياقة البدنية
📝 المتطلبات:
حساب مؤشر كتلة الجسم (BMI)

تحديد الفئة (نحيف، طبيعي، سمين)

تقديم نصائح بناء على النتيجة

💻 الكود:
javascript
// حاسبة اللياقة البدنية
let weight = 70; // كجم
let height = 1.75; // متر

// حساب BMI
let bmi = weight / (height * height);
let category = "";

// تحديد الفئة
if (bmi < 18.5) {
    category = "نحيف";
} else if (bmi < 25) {
    category = "طبيعي";
} else if (bmi < 30) {
    category = "زائد الوزن";
} else {
    category = "سمين";
}

// التقرير
console.log("🏃 حاسبة اللياقة البدنية");
console.log("الوزن:", weight + " كجم");
console.log("الطول:", height + " م");
console.log("مؤشر كتلة الجسم (BMI):", bmi.toFixed(2));
console.log("الفئة:", category);

// نصائح
console.log("💡 النصيحة:", 
    category === "طبيعي" ? "حافظ على وزنك المثالي!" :
    category === "نحيف" ? "احرص على تناول الطعام الصحي!" :
    "جرب ممارسة الرياضة بانتظام!");
🚀 تحدي إضافي: نظام حجز التذاكر
📝 المتطلبات المتقدمة:
إدارة أنواع التذاكر المختلفة

حساب التكلفة الإجمالية

تطبيق الخصومات

javascript
// نظام حجز التذاكر
let eventName = "حفلة موسيقية";
let ticketType = "VIP"; // "عادي", "VIP", "مميز"
let ticketPrice = 0;
let quantity = 2;
let discount = 0.1; // 10% خصم

// تحديد سعر التذكرة
if (ticketType === "عادي") {
    ticketPrice = 100;
} else if (ticketType === "مميز") {
    ticketPrice = 200;
} else if (ticketType === "VIP") {
    ticketPrice = 500;
}

// الحسابات
let totalBeforeDiscount = ticketPrice * quantity;
let discountAmount = totalBeforeDiscount * discount;
let finalTotal = totalBeforeDiscount - discountAmount;

// الفاتورة
console.log("🎫 نظام حجز التذاكر");
console.log("الفعالية:", eventName);
console.log("نوع التذكرة:", ticketType);
console.log("السعر:", ticketPrice + " ريال");
console.log("الكمية:", quantity);
console.log("------------------------");
console.log("الإجمالي قبل الخصم:", totalBeforeDiscount + " ريال");
console.log("الخصم:", (discount * 100) + "%");
console.log("مبلغ الخصم:", discountAmount + " ريال");
console.log("الإجمالي النهائي:", finalTotal + " ريال");