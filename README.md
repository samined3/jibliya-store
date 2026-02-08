<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>JIBLIYA STORE | مضوي محمول</title>
  <style>
    :root{
      --bg:#0b1220; --card:#111a2e; --text:#eaf0ff; --muted:#b8c3e6;
      --accent:#ffb703; --accent2:#fb8500; --line:#22305a;
      --ok:#2dd4bf; --danger:#fb7185;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial; background:linear-gradient(180deg,#070b14, #0b1220); color:var(--text)}
    a{color:inherit}
    .wrap{max-width:980px;margin:auto;padding:18px}
    .topbar{display:flex;gap:12px;align-items:center;justify-content:space-between;margin-bottom:14px}
    .brand{display:flex;gap:10px;align-items:center}
    .logo{width:44px;height:44px;border-radius:14px;background:linear-gradient(135deg,var(--accent),var(--accent2));display:grid;place-items:center;font-weight:800;color:#1b1200}
    .brand h1{margin:0;font-size:18px}
    .badge{font-size:12px;color:#1b1200;background:rgba(255,183,3,.95);padding:6px 10px;border-radius:999px;font-weight:700}
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:14px}
    @media(max-width:860px){.hero{grid-template-columns:1fr}}
    .card{background:rgba(17,26,46,.92);border:1px solid var(--line);border-radius:18px;padding:16px;box-shadow:0 10px 30px rgba(0,0,0,.25)}
    .title{margin:0 0 6px;font-size:26px}
    .subtitle{margin:0 0 14px;color:var(--muted);line-height:1.7}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:10px}
    @media(max-width:860px){.grid{grid-template-columns:1fr}}
    .feat{border:1px solid var(--line);border-radius:16px;padding:12px;background:rgba(7,11,20,.55)}
    .feat b{display:block;margin-bottom:6px}
    .pricebox{display:flex;gap:10px;flex-wrap:wrap;align-items:center;justify-content:space-between;margin-top:10px}
    .price{font-size:26px;font-weight:900}
    .old{color:var(--muted);text-decoration:line-through;font-size:14px}
    .pill{border:1px solid var(--line);border-radius:999px;padding:7px 10px;color:var(--muted);font-size:12px}
    .btns{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .btn{border:0;border-radius:14px;padding:12px 14px;font-weight:800;cursor:pointer}
    .btn.primary{background:linear-gradient(135deg,var(--accent),var(--accent2));color:#1b1200}
    .btn.ghost{background:transparent;border:1px solid var(--line);color:var(--text)}
    .imgbox{display:grid;place-items:center;min-height:260px;background:radial-gradient(60% 60% at 50% 30%, rgba(255,183,3,.22), transparent), rgba(7,11,20,.55);border:1px dashed var(--line);border-radius:18px}
    .imgbox small{color:var(--muted)}
    .section{margin-top:14px}
    label{display:block;font-weight:700;margin:10px 0 6px}
    input,textarea{
      width:100%;padding:12px 12px;border-radius:14px;border:1px solid var(--line);
      background:#0a1020;color:var(--text);outline:none
    }
    input:focus,textarea:focus{border-color:rgba(255,183,3,.6)}
    .note{margin-top:10px;color:var(--muted);font-size:12px;line-height:1.7}
    .ok{color:var(--ok);font-weight:800}
    .danger{color:var(--danger);font-weight:800}
    .footer{margin:18px 0;color:var(--muted);font-size:12px;text-align:center}
  </style>
</head>

<body>
  <div class="wrap">
    <div class="topbar">
      <div class="brand">
        <div class="logo">JS</div>
        <div>
          <h1>JIBLIYA STORE</h1>
          <div style="color:var(--muted);font-size:12px">بيع منتجات متنوعة • توصيل داخل المغرب</div>
        </div>
      </div>
      <div class="badge">طلب سريع</div>
    </div>

    <div class="hero">
      <div class="card">
        <h2 class="title">مضوي محمول قوي 🔥</h2>
        <p class="subtitle">
          مضوي عملي للحمل: فالدار، فالخدمة، فالسيارة، وحتى فالخروج.  
          كيخدم مزيان فالليل وكيعاونك وقت الحاجة.
        </p>

        <div class="grid">
          <div class="feat"><b>✅ إضاءة قوية</b><span style="color:var(--muted)">كيضوي مزيان فالظلام</span></div>
          <div class="feat"><b>✅ خفيف ومحمول</b><span style="color:var(--muted)">ساهل يتشد ويتنقل</span></div>
          <div class="feat"><b>✅ مناسب فالطوارئ</b><span style="color:var(--muted)">كيعاونك فالانقطاع ديال الضو</span></div>
        </div>

        <div class="pricebox">
          <div>
            <div class="old">الثمن القديم: 99 درهم</div>
            <div class="price">الثمن دابا: <span style="color:var(--accent)">80 درهم</span></div>
          </div>
          <div class="pill">الدفع عند الاستلام</div>
          <div class="pill">توصيل سريع</div>
        </div>

        <div class="btns">
          <a class="btn primary" href="#order">✅ طلب دابا</a>
          <a class="btn ghost" href="tel:0660828109">📞 اتصال: 0660828109</a>
          <a class="btn ghost" href="https://wa.me/212660828109" target="_blank" rel="noopener">💬 واتساب</a>
        </div>

        <p class="note">
          <span class="ok">ملاحظة:</span> هاد الثمن (80 درهم) اقتراح مزيان حيث شريتيه بـ 50 درهم:
          كيبقى ليك هامش ربح وكتقدر تخلّص التوصيل/الإشهار.  
          إلا بغيتي تربح أكثر، جرّب 89 درهم وراقب الطلبات.
        </p>
      </div>

      <div class="card">
        <div class="imgbox">
          <div style="text-align:center">
            <div style="font-size:46px">💡</div>
            <div style="font-weight:900;font-size:18px;margin-top:6px">صورة المنتج</div>
            <small>إلى عندك صورة ديال المضوي صيفطها ليا ونحطّها هنا</small>
          </div>
        </div>

        <div class="section" id="order">
          <h3 style="margin:0 0 6px">عمّر بياناتك باش نعيطو ليك</h3>
          <div style="color:var(--muted);font-size:13px;line-height:1.6">
            كتب الاسم ورقم الهاتف والمدينة، وغادي نتاصلوا بك لتأكيد الطلب.
          </div>

          <!--
            مهم: هاد الفورم دابا كيبقى غير محلي (ما كيسجلش فشي بلاصة).
            فالأجوبة اللي جاية غادي نعطيك طريقة مجانية باش يتسجلو فالـ Google Sheets.
          -->
          <form onsubmit="return fakeSubmit(event)">
            <label>الاسم الكامل</label>
            <input required name="name" placeholder="مثال: محمد ..." />

            <label>رقم الهاتف</label>
            <input required name="phone" placeholder="مثال: 06xxxxxxxx" />

            <label>المدينة</label>
            <input required name="city" placeholder="مثال: الدار البيضاء" />

            <label>ملاحظات (اختياري)</label>
            <textarea name="note" rows="3" placeholder="مثال: لون معين / وقت التوصيل..."></textarea>

            <div class="btns" style="margin-top:12px">
              <button class="btn primary" type="submit">✅ تأكيد الطلب</button>
              <button class="btn ghost" type="reset">مسح</button>
            </div>

            <div id="msg" class="note"></div>
          </form>

          <p class="note">
            <span class="danger">مهم:</span> باش تعرف شكون دخل البيانات، خاصنا نربط الفورم بـ Google Sheets (مجانا).
            غادي نديروه فالخطوة الجاية.
          </p>
        </div>
      </div>
    </div>

    <div class="footer">
      © JIBLIYA STORE — جميع الحقوق محفوظة
    </div>
  </div>

<script>
  function fakeSubmit(e){
    e.preventDefault();
    const msg = document.getElementById('msg');
    msg.innerHTML = "✅ توصلنا بطلبك! (دابا غير تجربة) — فالخطوة الجاية غادي نخليها كتسجل فالـ Google Sheets.";
    return false;
  }
</script>

</body>
</html>

صفحة مبيعات احترافية لعرض و بيع منتجات متنوعة و التواصل مع الزبناء
