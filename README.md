[index.html.html](https://github.com/user-attachments/files/25184726/index.html.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>M38 FC</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-red-700 text-white font-sans transition-all duration-500">

  <!-- Language Button -->
  <div class="flex justify-end p-4">
    <button onclick="toggleLang()" class="bg-black px-4 py-2 rounded-xl shadow-lg hover:scale-105 transition" id="langBtn">
      English
    </button>
  </div>

  <!-- Hero Section -->
  <section class="text-center py-16 px-6">
    <div class="flex justify-center mb-8">
      <img src="m38-logo.jpg" alt="M38 FC Logo" class="w-48 h-48 object-contain rounded-full shadow-2xl border-4 border-black">
    </div>
    <h1 class="text-5xl font-extrabold tracking-wide" id="heroTitle">M38 FC</h1>
    <p class="mt-4 text-xl font-light" id="heroSubtitle">الهيمنة على طور البروكلوب منذ 2020</p>
    <p class="mt-6 max-w-2xl mx-auto text-lg opacity-95" id="heroText">
      تأسس نادي M38 FC عام 2020 كمشروع تنافسي في طور البروكلوب داخل FIFA. خلال سنوات قليلة أصبح الفريق قوة ضاربة حصدت أكثر من 20 بطولة رسمية وألقاب تايتل متعددة على مستوى المنافسات.
    </p>
  </section>

  <!-- About -->
  <section class="bg-red-800 py-16 px-6">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-6" id="aboutTitle">من نحن</h2>
      <p class="text-lg leading-8 opacity-95" id="aboutText">
        M38 FC كيان تنافسي منظم يعتمد على الانضباط التكتيكي واللعب الجماعي السريع. هوية الفريق هجومية بضغط عالٍ وتحولات ذكية، مع دفاع صلب في المباريات الحاسمة.
      </p>
    </div>
  </section>

  <!-- Achievements -->
  <section class="py-16 px-6">
    <div class="max-w-5xl mx-auto">
      <h2 class="text-3xl font-bold mb-8" id="achievementsTitle">الإنجازات</h2>
      <ul class="grid md:grid-cols-2 gap-6 text-lg">
        <li>🏆 8 League Titles</li>
        <li>🏆 5 Domestic Cups</li>
        <li>🏆 4 Regional Championships</li>
        <li>🏆 3 Elite Invitational Trophies</li>
        <li>⭐ 300+ Official Wins</li>
        <li>⭐ 27-Game Unbeaten Streak</li>
      </ul>
    </div>
  </section>

  <!-- Vision -->
  <section class="bg-red-800 py-16 px-6 text-center">
    <h2 class="text-3xl font-bold mb-6" id="visionTitle">رؤيتنا</h2>
    <p class="max-w-3xl mx-auto text-lg opacity-95 leading-8" id="visionText">
      نهدف إلى أن نكون من أقوى أندية البروكلوب في المنطقة والمنافسة على أعلى المستويات العالمية، عبر تطوير التكتيك واستقطاب المواهب وصناعة هوية لا تُهزم.
    </p>
  </section>

  <!-- Footer -->
  <footer class="bg-black py-8 text-center text-sm">
    <p>© 2026 M38 FC - All Rights Reserved</p>
    <p class="mt-2 opacity-70" id="established">تأسس عام 2020</p>
  </footer>

<script>
let currentLang = "ar";

function toggleLang() {
  if (currentLang === "ar") {
    document.documentElement.lang = "en";
    document.documentElement.dir = "ltr";
    document.getElementById("langBtn").innerText = "العربية";
    document.getElementById("heroSubtitle").innerText = "Dominating Pro Clubs Since 2020";
    document.getElementById("heroText").innerText = "Founded in 2020, M38 FC quickly became a competitive powerhouse in FIFA Pro Clubs. With over 20 major titles and multiple championship wins, the club established itself as a dominant force.";
    document.getElementById("aboutTitle").innerText = "About Us";
    document.getElementById("aboutText").innerText = "M38 FC is a structured competitive club built on tactical discipline and fast team play. The identity is aggressive pressing, intelligent transitions, and a rock-solid defense in big matches.";
    document.getElementById("achievementsTitle").innerText = "Achievements";
    document.getElementById("visionTitle").innerText = "Our Vision";
    document.getElementById("visionText").innerText = "Our goal is to become one of the strongest Pro Clubs teams in the region and compete at the highest global level by refining tactics, recruiting talent, and building an unstoppable identity.";
    document.getElementById("established").innerText = "Established in 2020";
    currentLang = "en";
  } else {
    document.documentElement.lang = "ar";
    document.documentElement.dir = "rtl";
    document.getElementById("langBtn").innerText = "English";
    document.getElementById("heroSubtitle").innerText = "الهيمنة على طور البروكلوب منذ 2020";
    document.getElementById("heroText").innerText = "تأسس نادي M38 FC عام 2020 كمشروع تنافسي في طور البروكلوب داخل FIFA. خلال سنوات قليلة أصبح الفريق قوة ضاربة حصدت أكثر من 20 بطولة رسمية وألقاب تايتل متعددة على مستوى المنافسات.";
    document.getElementById("aboutTitle").innerText = "من نحن";
    document.getElementById("aboutText").innerText = "M38 FC كيان تنافسي منظم يعتمد على الانضباط التكتيكي واللعب الجماعي السريع. هوية الفريق هجومية بضغط عالٍ وتحولات ذكية، مع دفاع صلب في المباريات الحاسمة.";
    document.getElementById("achievementsTitle").innerText = "الإنجازات";
    document.getElementById("visionTitle").innerText = "رؤيتنا";
    document.getElementById("visionText").innerText = "نهدف إلى أن نكون من أقوى أندية البروكلوب في المنطقة والمنافسة على أعلى المستويات العالمية، عبر تطوير التكتيك واستقطاب المواهب وصناعة هوية لا تُهزم.";
    document.getElementById("established").innerText = "تأسس عام 2020";
    currentLang = "ar";
  }
}
</script>

</body>
</html>
