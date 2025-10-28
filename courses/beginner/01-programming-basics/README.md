# 📚 1.1 أساسيات البرمجة - المتغيرات وأنواع البيانات


## 🎯 ما ستتعلمه في هذا الدرس

- ما هي المتغيرات ولماذا نستخدمها
- أنواع البيانات الأساسية في JavaScript
- كيفية تعريف واستخدام المتغيرات
- العمليات الأساسية على البيانات

## 📖 الشق النظري

### ما هي المتغيرات؟
المتغيرات مثل **صناديق تخزين** في ذاكرة الكمبيوتر نضع فيها البيانات. لكل متغير:
- **اسم** - للتعريف عليه
- **قيمة** - البيانات المخزنة
- **نوع** - نوع البيانات المخزنة

### أنواع البيانات الأساسية

#### 1. 🆎 النصوص (String)
```javascript
let name = "أحمد";
let message = 'مرحبا بالعالم!';
2. 🔢 الأرقام (Number)
javascript
let age = 25;
let price = 99.99;
3. ✅ القيم المنطقية (Boolean)
javascript
let isActive = true;
let isCompleted = false;
4. 🔄 القيم غير المعرفة
javascript
let undefinedVar = undefined;
let emptyValue = null;
💻 الشق العملي
مثال 1: تعريف المتغيرات
javascript
// تعريف متغيرات مختلفة
let userName = "محمد";
let userAge = 30;
let isOnline = true;
let salary = 1500.50;

// طباعة القيم
console.log("الاسم:", userName);
console.log("العمر:", userAge);
console.log("متصل:", isOnline);
console.log("الراتب:", salary);
مثال 2: العمليات على المتغيرات
javascript
// عمليات على النصوص
let firstName = "أحمد";
let lastName = "علي";
let fullName = firstName + " " + lastName;
console.log("الاسم الكامل:", fullName);

// عمليات على الأرقام
let x = 10;
let y = 5;
let sum = x + y;
let product = x * y;
console.log("المجموع:", sum);
console.log("الضرب:", product);
🧪 تمارين عملية
التمرين 1: تعريف المتغيرات
عرف متغيرات لتخزين المعلومات التالية:

اسمك

عمرك

مدينتك

هل أنت طالب؟ (نعم/لا)

التمرين 2: العمليات الحسابية
اكتب برنامجاً يحسب:

محيط دائرة نصف قطرها 5

مساحة مستطيل طوله 8 وعرضه 6

التمرين 3: دمج النصوص
أنشئ رسالة ترحيب باستخدام دمج النصوص:
"مرحبا [الاسم]، أنت من [المدينة] وعمرك [العمر]"

🔍 نصائح مهمة
استخدم أسماء واضحة للمتغيرات

استخدم let للمتغيرات التي تتغير

استخدم const للقيم الثابتة

تجنب استخدام الكلمات المحجوزة

🚀 المشروع المصغر
آلة حاسبة بسيطة
javascript
// مشروع: آلة حاسبة
let num1 = 15;
let num2 = 3;

// قم بحساب
let addition = num1 + num2;
let subtraction = num1 - num2;
let multiplication = num1 * num2;
let division = num1 / num2;

// اطبع النتائج
console.log("الجمع:", addition);
console.log("الطرح:", subtraction);
console.log("الضرب:", multiplication);
console.log("القسمة:", division);
📚 ما التالي؟
في الدرس القادم سنتعلم هياكل التحكم والشروط وكيفية اتخاذ القرارات في البرمجة.

💡 تذكر: الممارسة المستمرة هي سر الإتقان!