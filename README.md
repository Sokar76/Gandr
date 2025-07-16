# Gandr
Gandr
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>شحن ألعاب الكازينو | فودافون كاش فقط</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
    }
  </style>
</head>
<body class="bg-gray-950 text-gray-100 scroll-smooth">
  <!-- باقي الموقع كما هو -->

  <!-- Notice Section -->
  <section class="py-12 bg-red-900 text-center">
    <div class="container mx-auto px-6 max-w-3xl">
      <h2 class="text-2xl md:text-3xl font-extrabold mb-4 text-yellow-400">تنبيه هام</h2>
      <p class="text-lg md:text-xl font-bold text-white">
        الحد الأدنى للشحن هو <span class="text-yellow-300">100 جنيه</span> والحد الأقصى هو <span class="text-yellow-300">10000 جنيه</span> في العملية الواحدة.
      </p>
      <p class="text-sm text-gray-300 mt-2">أي تحويل أقل من 100 جنيه لن يتم اعتماده.</p>
    </div>
  </section>

  <!-- متابعة باقي المحتوى -->

  <script>
    document.querySelectorAll('.purchase-btn').forEach(btn => {
      btn.addEventListener('click', () => {
        const packageName = btn.dataset.package;
        alert(`يرجى تحويل مبلغ باقة ${packageName} إلى رقم فودافون كاش، مع التأكد أن المبلغ بين 100 جنيه و 10000 جنيه. ثم أرسل إيصال التحويل لنا على واتساب أو تيليجرام. سيتم إضافة الرصيد خلال دقائق.`);
      });
    });
  </script>
</body>
</html>
