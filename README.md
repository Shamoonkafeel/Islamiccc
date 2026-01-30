# اسلامی ویب سائٹ - Islamic Website

## خصوصیات / Features

### ✨ نئی خصوصیات / New Features

1. **تقریبات کا صفحہ / Events Page**
   - 10 اسلامی تقریبات
   - ہر صفحے پر 6 تقریبات
   - خوبصورت pagination
   - تاریخ، مقام اور تفصیل کے ساتھ

2. **10 ممالک کی زبانیں / 10 Muslim Countries Languages**
   - اردو (Urdu) - پاکستان
   - العربية (Arabic) - سعودی عرب
   - Bahasa Indonesia - انڈونیشیا
   - Türkçe (Turkish) - ترکی
   - فارسی (Persian) - ایران
   - বাংলা (Bengali) - بنگلہ دیش
   - Bahasa Melayu - ملائیشیا
   - Soomaali (Somali) - صومالیہ
   - پښتو (Pashto) - افغانستان
   - Hausa - نائیجیریا

3. **12 تھیم رنگ / 12 Theme Colors**
   - Green (سبز) - ڈیفالٹ
   - Blue (نیلا)
   - Purple (جامنی)
   - Teal (فیروزی)
   - Orange (نارنجی)
   - Red (سرخ)
   - Brown (بھورا)
   - Indigo (گہرا نیلا)
   - Pink (گلابی)
   - Cyan (آسمانی)
   - Lime (لائم)
   - Amber (کہربا)

4. **ہر صفحے پر ڈراپ ڈاؤن / Dropdowns on Every Page**
   - زبان کا انتخاب header میں
   - تھیم کا انتخاب header میں
   - تمام صفحات پر دستیاب

## فائلوں کی تفصیل / File Structure

```
islamic-website/
├── index.html              # مرکزی صفحہ
├── events.html            # تقریبات کا صفحہ (نیا)
├── prayer-times.html      # نماز کے اوقات
├── pillars.html           # ارکان اسلام
├── quran.html             # قرآن مجید
├── information.html       # اسلامی معلومات
├── registration.html      # رجسٹریشن
├── prayers/
│   ├── fajr.html         # فجر کی نماز
│   ├── zuhr.html         # ظہر کی نماز
│   ├── asr.html          # عصر کی نماز
│   ├── maghrib.html      # مغرب کی نماز
│   └── isha.html         # عشاء کی نماز
├── css/
│   └── styles.css        # تمام اسٹائلز (12 تھیمز کے ساتھ)
└── js/
    └── main.js           # JavaScript (زبانیں، تھیمز، pagination)
```

## استعمال کی ہدایات / Usage Instructions

### زبان تبدیل کرنا / Changing Language
1. Header کے اوپری دائیں کونے میں "زبان" پر کلک کریں
2. اپنی پسند کی زبان منتخب کریں
3. پوری ویب سائٹ اس زبان میں تبدیل ہو جائے گی
4. آپ کی پسند خودکار محفوظ ہو جائے گی

### تھیم تبدیل کرنا / Changing Theme
1. Header میں "تھیم" پر کلک کریں
2. 12 رنگوں میں سے اپنی پسند کا رنگ منتخب کریں
3. پوری ویب سائٹ کا رنگ فوری طور پر تبدیل ہو جائے گا
4. آپ کی پسند خودکار محفوظ ہو جائے گی

### تقریبات دیکھنا / Viewing Events
1. Navigation menu میں "تقریبات" پر کلک کریں
2. ہر صفحے پر 6 تقریبات نظر آئیں گی
3. مزید تقریبات دیکھنے کے لیے "اگلا" بٹن استعمال کریں
4. واپس جانے کے لیے "پچھلا" بٹن استعمال کریں

## تکنیکی تفصیلات / Technical Details

### زبان کی تبدیلی / Language Switching
- **localStorage** میں محفوظ ہوتی ہے
- **RTL/LTR** خودکار طور پر تبدیل ہوتا ہے
- تمام صفحات پر کام کرتا ہے

### تھیم سسٹم / Theme System
- **CSS Variables** استعمال کرتا ہے
- **localStorage** میں محفوظ ہوتا ہے
- 12 مختلف رنگ سکیمز
- ہموار transitions

### Events Pagination
- **JavaScript** سے چلتا ہے
- 6 events فی صفحہ
- کل 10 events (2 صفحات)
- Smooth scrolling

## برائوزر سپورٹ / Browser Support
- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Opera ✅

## مزید بہتریاں / Future Enhancements
- [ ] Backend integration کے لیے API
- [ ] Event registration functionality
- [ ] Social media sharing
- [ ] Print-friendly layouts
- [ ] Dark mode option
- [ ] More languages

## Developer Notes

### Adding New Languages
1. Open `js/main.js`
2. Add new language object to `translations` object
3. Include all required translation keys
4. Update language dropdown in HTML files

### Adding New Theme Colors
1. Open `css/styles.css`
2. Add new theme class (e.g., `.theme-yourcolor`)
3. Define CSS variables for the theme
4. Update theme dropdown in HTML files
5. Add to `themeColors` object in `js/main.js`

### Adding New Events
1. Open `js/main.js`
2. Add event object to `allEvents` array
3. Include: title, date, description, location
4. Events will automatically paginate

## کاپی رائٹ / Copyright
© 2026 Islamic Knowledge Center
تمام حقوق محفوظ ہیں / All rights reserved

---

اللہ تعالیٰ ہمیں دین کی سمجھ عطا فرمائے - آمین
May Allah grant us understanding of the religion - Ameen
