<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geleceğin Liderleri - Eğitim ve Gelişim Platformu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Geleceğin Liderleri</h1>
        <p>Bilim, Teknoloji, Uzay ve İnovasyon Alanında Kendinizi Geliştirin</p>
        <nav>
            <a href="#egitim">Eğitim Modülleri</a>
            <a href="#mentorluk">Mentorluk</a>
            <a href="#ilham">İlham Verici İçerikler</a>
            <a href="#fonlama">Fonlama Destekleri</a>
        </nav>
    </header>

    <section id="egitim">
        <h2>Eğitim Modülleri</h2>
        <p>Bilim, teknoloji, uzay ve inovasyon alanında uzmanlık kazanın.</p>
        <div class="module-container">
            <div class="module">
                <h3>Bilim Modülleri</h3>
                <p>Bilim dünyasında ileri düzeyde bilgi edinin.</p>
                <button onclick="showMoreInfo('Bilim')">Daha Fazla</button>
            </div>
            <div class="module">
                <h3>Teknoloji Modülleri</h3>
                <p>Yapay zeka, veri bilimi ve yazılım mühendisliği.</p>
                <button onclick="showMoreInfo('Teknoloji')">Daha Fazla</button>
            </div>
            <div class="module">
                <h3>Uzay Modülleri</h3>
                <p>Uzay keşifleri ve astrofizik hakkında bilgi.</p>
                <button onclick="showMoreInfo('Uzay')">Daha Fazla</button>
            </div>
        </div>
    </section>

    <section id="mentorluk">
        <h2>Mentorluk</h2>
        <p>Alanında uzman kişilerden rehberlik alın.</p>
        <button onclick="showMentorshipInfo()">Mentorluk Programları</button>
    </section>

    <section id="ilham">
        <h2>İlham Verici İçerikler</h2>
        <p>Başarılı insanların hikayelerinden ilham alın.</p>
        <div class="inspiration-container">
            <div class="inspiration">
                <h3>İnovasyon Hikayeleri</h3>
                <p>Dünyayı değiştiren yenilikler hakkında öğrenin.</p>
            </div>
            <div class="inspiration">
                <h3>Bilimsel Başarılar</h3>
                <p>En yeni bilimsel başarılar ve araştırmalar.</p>
            </div>
        </div>
    </section>

    <section id="fonlama">
        <h2>Fonlama Destekleri</h2>
        <p>Projelerinize destek bulabileceğiniz bir alan.</p>
        <button onclick="showFundingInfo()">Fon Başvurusu Yapın</button>
    </section>

    <footer>
        <p>&copy; 2023 Geleceğin Liderleri - Eğitim ve Gelişim Platformu</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
