<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>اختبار مستوى اللغة العربية</title>
  <style>
    body { font-family: sans-serif; padding: 20px; background: #f2f2f2; }
    h1 { color: #333; }
    .question { background: #fff; padding: 15px; margin: 10px 0; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    label { display: block; margin: 5px 0; }
    input[type="text"], textarea { width: 100%; padding: 8px; margin-top: 5px; border-radius: 5px; border: 1px solid #ccc; }
    button { margin-top: 20px; padding: 10px 20px; background: #3498db; color: white; border: none; border-radius: 5px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>اختبار مستوى اللغة العربية</h1>

  <div class="question">
    <p>1. ما هذه الحرف؟</p>
    <img src="https://via.placeholder.com/50x50?text=%D8%A8%D9%8E" alt="ba">
    <label><input type="radio" name="q1"> با</label>
    <label><input type="radio" name="q1"> تا</label>
    <label><input type="radio" name="q1"> ثا</label>
    <label><input type="radio" name="q1"> دال</label>
  </div>

  <div class="question">
    <p>2. اكتب اسم هذا الحرف: ت</p>
    <input type="text" placeholder="اكتب هنا">
  </div>

  <div class="question">
    <p>3. اقرأ هذه الكلمة: <strong>البَابُ</strong></p>
    <button onclick="alert('تسجيل صوتي غير مفعل بعد')">اضغط للتسجيل</button>
  </div>

  <div class="question">
    <p>4. أي كلمة تحتوي على الضمة؟</p>
    <label><input type="radio" name="q4"> كُتُبْ</label>
    <label><input type="radio" name="q4"> كَتَبَ</label>
    <label><input type="radio" name="q4"> كِتَابْ</label>
  </div>

  <div class="question">
    <p>5. اقرأ هذه المقاطع: بَـا، بِـي، بُـو</p>
    <button onclick="alert('تسجيل صوتي غير مفعل بعد')">اضغط للتسجيل</button>
  </div>

  <div class="question">
    <p>6. اكتب حرف "ر" في أول وآخر الكلمة</p>
    <input type="text" placeholder="مثال: ـر، ر">
  </div>

  <div class="question">
    <p>7. اقرأ واكتب: خُبْزٌ</p>
    <input type="text" placeholder="اكتب هنا">
  </div>

  <div class="question">
    <p>8. 🎧 ما اسمك؟</p>
    <button onclick="alert('تسجيل صوتي غير مفعل بعد')">اضغط للتسجيل</button>
  </div>

  <div class="question">
    <p>9. اختر الصورة التي تمثل كلمة "قِطَّةٌ"</p>
    <label><input type="radio" name="q9"> 🐈</label>
    <label><input type="radio" name="q9"> 🐕</label>
    <label><input type="radio" name="q9"> 🐦</label>
    <label><input type="radio" name="q9"> 🐟</label>
  </div>

  <div class="question">
    <p>10. ما معنى كلمة "بَيْتٌ"؟</p>
    <label><input type="radio" name="q10"> 🏠 منزل</label>
    <label><input type="radio" name="q10"> 🏫 مدرسة</label>
    <label><input type="radio" name="q10"> 🚘 سيارة</label>
    <label><input type="radio" name="q10"> 🌲 شجرة</label>
  </div>

  <div class="question">
    <p>11. قدم عائلتك بجمل بسيطة</p>
    <button onclick="alert('تسجيل صوتي غير مفعل بعد')">اضغط للتسجيل</button>
  </div>

  <div class="question">
    <p>12. قل "السلام عليكم" واسأل عن الحال</p>
    <button onclick="alert('تسجيل صوتي غير مفعل بعد')">اضغط للتسجيل</button>
  </div>

  <div class="question">
    <p>13. ما الضمير الذي يعني "أنا"؟</p>
    <label><input type="radio" name="q13"> أَنَا</label>
    <label><input type="radio" name="q13"> أَنْتَ</label>
    <label><input type="radio" name="q13"> هُوَ</label>
    <label><input type="radio" name="q13"> هِيَ</label>
  </div>

  <div class="question">
    <p>14. صرّف الفعل "كَتَبَ" للمفرد المذكر في المضارع</p>
    <input type="text" placeholder="اكتب هنا">
  </div>

  <div class="question">
    <p>15. ما جمع كلمة "كِتَابٌ"؟</p>
    <label><input type="radio" name="q15"> كُتُبٌ</label>
    <label><input type="radio" name="q15"> كِتَابَاتٌ</label>
    <label><input type="radio" name="q15"> كَاتِبُونَ</label>
    <label><input type="radio" name="q15"> كُتُبِي</label>
  </div>

  <button onclick="alert('Merci pour votre participation !')">Envoyer</button>
</body>
</html>
