<!DOCTYPE html>
<html lang="ar">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <title>الاسلام حياة</title>
    <style>
        :root {
            --bg: #eefde1;
            --bg-strong: #d5f5b1;
            --surface: rgba(255, 255, 255, 0.92);
            --text: #1a2b0f;
            --accent: #28723c;
            --accent-soft: #edf7e9;
            --border: rgba(40, 114, 60, 0.2);
        }

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;
            font-family: "Roboto", sans-serif;
            background: radial-gradient(circle at top right, #f8ffe9 0%, #d7ffb8 45%, #b1e884 100%);
            color: var(--text);
            line-height: 1.7;
        }

        .page {
            max-width: 1120px;
            margin: 0 auto;
            padding: 28px 18px 40px;
        }

        .header {
            text-align: center;
            padding: 34px 16px;
        }

        .header h1 {
            margin: 0;
            font-size: clamp(2.4rem, 4vw, 3.6rem);
            letter-spacing: 0.04em;
            color: #1f4f22;
        }

        .header p {
            margin: 18px auto 0;
            max-width: 780px;
            font-size: 1.05rem;
            color: #2e4827;
        }

        .hero {
            display: grid;
            grid-template-columns: minmax(260px, 1fr) minmax(340px, 1.2fr);
            gap: 24px;
            align-items: center;
            margin-top: 24px;
        }

        .card {
            background: var(--surface);
            border: 1px solid var(--border);
            border-radius: 28px;
            padding: 26px;
            box-shadow: 0 18px 40px rgba(15, 44, 15, 0.12);
        }

        .hero img {
            width: 100%;
            display: block;
            border-radius: 26px;
            box-shadow: 0 22px 50px rgba(15, 44, 15, 0.16);
            border: 5px solid rgba(255, 255, 255, 0.9);
            max-width: 520px;
            margin: 0 auto;
        }

        .links-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 12px;
            margin-top: 20px;
        }

        .link {
            display: inline-flex;
            justify-content: center;
            align-items: center;
            padding: 14px 16px;
            border-radius: 14px;
            text-decoration: none;
            color: var(--text);
            background: var(--accent-soft);
            border: 1px solid var(--border);
            font-weight: 600;
            transition: transform 0.2s ease, background 0.2s ease, color 0.2s ease;
        }

        .link:hover {
            transform: translateY(-2px);
            background: #ffffff;
            color: #16411a;
            border-color: rgba(40, 114, 60, 0.35);
        }

        .section-title {
            margin: 0 0 16px;
            font-size: 1.35rem;
            color: #22532b;
        }

        .footer {
            margin-top: 32px;
            text-align: center;
            color: #314a28;
            font-size: 1rem;
        }

        .footer a {
            color: #1c521c;
            text-decoration: none;
            font-weight: 700;
        }

        @media (max-width: 860px) {
            .hero {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 520px) {
            .page {
                padding: 18px 14px 32px;
            }

            .header p,
            .footer {
                font-size: 1rem;
            }
        }
    </style>

</head>

<body>
    <div class="page">
        <header class="header">
            <h1>تفسير جزء عم</h1>
            <p>جزء عم هو الجزء الثلاثون من القرآن الكريم، ويضم سوراً قصيرة ذات معانٍ عظيمة في الإيمان، الأخلاق، والتوحيد.</p>
        </header>

        <section class="hero">
            <div class="card">
                <p>جزء عم يحتوي على سورٍ مثل النبأ، النازعات، عبس، التكوير، والأعلى. هذه السور تدعو المؤمنين إلى التفكر في قدرة الله ونعمته، وتذكرهم بأهمية الأخلاق والتقوى في حياتهم اليومية.</p>
            </div>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQH-gFXISTiXSRVqR2SMwLlxsACYUY7boJc6g&s" alt="تفسير جزء عم">
        </section>

        <section class="card">
            <h2 class="section-title">روابط تفسير السور</h2>
            <div class="links-grid">
                <a class="link" href="https://shamela.ws/book/14536/167">تفسير سورة الناس</a>
                <a class="link" href="https://shamela.ws/book/14536/164">تفسير سورة الفلق</a>
                <a class="link" href="https://shamela.ws/book/14536/162">تفسير سورة الإخلاص</a>
                <a class="link" href="https://shamela.ws/book/14536/160">تفسير سورة المسد</a>
                <a class="link" href="https://shamela.ws/book/14536/158">تفسير سورة النصر</a>
                <a class="link" href="https://shamela.ws/book/14536/156">تفسير سورة الكافرون</a>
                <a class="link" href="https://shamela.ws/book/14536/154">تفسير سورة الكوثر</a>
                <a class="link" href="https://shamela.ws/book/14536/152">تفسير سورة الماعون</a>
                <a class="link" href="https://shamela.ws/book/14536/150">تفسير سورة قريش</a>
                <a class="link" href="https://shamela.ws/book/14536/146">تفسير سورة الفيل</a>
                <a class="link" href="https://shamela.ws/book/14536/145">تفسير سورة الهمزة</a>
                <a class="link" href="https://shamela.ws/book/14536/143">تفسير سورة العصر</a>
                <a class="link" href="https://shamela.ws/book/14536/141">تفسير سورة التكاثر</a>
                <a class="link" href="https://shamela.ws/book/14536/138">تفسير سورة القارعة</a>
                <a class="link" href="https://shamela.ws/book/14536/135">تفسير سورة العاديات</a>
                <a class="link" href="https://shamela.ws/book/14536/133">تفسير سورة الزلزلة</a>
                <a class="link" href="https://shamela.ws/book/14536/128">تفسير سورة البينة</a>
                <a class="link" href="https://shamela.ws/book/14536/126">تفسير سورة القدر</a>
                <a class="link" href="https://shamela.ws/book/14536/119">تفسير سورة التين</a>
                <a class="link" href="https://shamela.ws/book/14536/117">تفسير سورة الشرح</a>
                <a class="link" href="https://shamela.ws/book/14536/113">تفسير سورة الضحى</a>
                <a class="link" href="https://shamela.ws/book/14536/108">تفسير سورة الليل</a>
                <a class="link" href="https://shamela.ws/book/14536/104">تفسير سورة الشمس</a>
                <a class="link" href="https://shamela.ws/book/14536/98">تفسير سورة البلد</a>
                <a class="link" href="https://shamela.ws/book/14536/90">تفسير سورة الفجر</a>
                <a class="link" href="https://shamela.ws/book/14536/84">تفسير سورة الغاشية</a>
                <a class="link" href="https://shamela.ws/book/14536/79">تفسير سورة الأعلى</a>
                <a class="link" href="https://shamela.ws/book/14536/75">تفسير سورة الطارق</a>
                <a class="link" href="https://shamela.ws/book/14536/68">تفسير سورة البروج</a>
                <a class="link" href="https://shamela.ws/book/14536/62">تفسير سورة الانشقاق</a>
                <a class="link" href="https://shamela.ws/book/14536/53">تفسير سورة المطففين</a>
                <a class="link" href="https://shamela.ws/book/14536/48">تفسير سورة الانفطار</a>
                <a class="link" href="https://shamela.ws/book/14536/41">تفسير سورة التكوير</a>
                <a class="link" href="https://shamela.ws/book/14536/32">تفسير سورة عبس</a>
                <a class="link" href="https://shamela.ws/book/14536/22">تفسير سورة النازعات</a>
                <a class="link" href="https://shamela.ws/book/14536/10">تفسير سورة عم</a>
            </div>
        </section>

        <footer class="footer">
            <p> .abushi12 هذا التفسير من كتاب "القرآن الأعظم" بعمل المتعلم الأمن السيبراني </p>
            <p>مشروع جانبي | 2026/6/12</p>
            <p><a href="https://abushi12.github.io/thshish/html5/tast.html">مشاريع أخرى: الجزر</a></p>
        </footer>
    </div>
</body>

</html>
