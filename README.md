<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portföyüm</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px auto;
            background: #fff;
            max-width: 800px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Caner Nişancı</h1>
        <nav>
            <ul>
                <li><a href="#hakkimda">Hakkımda</a></li>
                <li><a href="#yetenekler">Yetenekler</a></li>
                <li><a href="#deneyimlerim">Deneyimlerim</a></li>
                <li><a href="#projelerim">Projelerim</a></li>
                <li><a href="#egitim">Eğitim</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="hakkimda">
        <h2>Hakkımda</h2>
        <p>Merhaba! Ben Caner Nişancı, web geliştirme alanında tutkulu bir öğrenciyim. MIS eğitimi aldıktan sonra, kullanıcı deneyimini ön planda tutarak çeşitli projelerde çalıştım. HTML, CSS ve JavaScript gibi teknolojilerle dinamik ve etkileşimli web siteleri oluşturma konusunda deneyimim var.</p>
        <p>Teknolojiye olan ilgim, sürekli öğrenme ve kendimi geliştirme motivasyonumla birleşiyor. Problem çözme becerilerim ve detaylara verdiğim önem sayesinde, projelerde etkili sonuçlar elde ediyorum. Hedefim, kullanıcıların ihtiyaçlarını anlayarak, onlara en iyi deneyimi sunan çözümler geliştirmektir.</p>
        <p>Boş zamanlarımda yeni teknolojileri takip etmek, açık kaynak projelerine katkıda bulunmak ve doğa yürüyüşleri yapmak gibi hobilerim var. Sizinle tanışmayı ve projelerimde birlikte çalışmayı dört gözle bekliyorum!</p>
    </section>

    <section id="yetenekler">
        <h2>Yetenekler</h2>
        <ul>
            <li>JavaScript</li>
            <li>CSS</li>
            <li>SQL</li>
            <li>C++</li>
        </ul>
    </section>

    <section id="deneyimlerim">
        <h2>Deneyimlerim</h2>
        <ul>
            <li>
                <strong>Şirket Adı</strong> - Pozisyon (Tarih Aralığı)
                <p>Kısa bir açıklama.</p>
            </li>
            <li>
                <strong>Şirket Adı</strong> - Pozisyon (Tarih Aralığı)
                <p>Kısa bir açıklama.</p>
            </li>
            <!-- Daha fazla deneyim ekleyebilirsiniz -->
        </ul>
    </section>

    <section id="projelerim">
        <h2>Projelerim</h2>
        <div class="proje">
            <h3>Proje 1</h3>
            <p>Proje hakkında kısa bir açıklama.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
        <div class="proje">
            <h3>Proje 2</h3>
            <p>Proje hakkında kısa bir açıklama.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
        <!-- Daha fazla proje ekleyebilirsiniz -->
    </section>

    <section id="egitim">
        <h2>Eğitim</h2>
        <ul>
            <li>
                <strong>Işık Üniversitesi</strong> - MIS (2022-2025)
                
            </li>
            <li>
                <strong>Okul Adı</strong> - Bölüm (Yıl - Yıl)
                <p>Kısa bir açıklama.</p>
            </li>
            <!-- Daha fazla eğitim ekleyebilirsiniz -->
        </ul>
    </section>

    <section id="iletisim">
        <h2>İletişim Bilgileri</h2>
        <form>
            <label for="isim">İsim:</label>
            <input type="text" id="isim" name="isim" required>
            
            <label for="email">E-posta:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mesaj">Mesaj:</label>
            <textarea id="mesaj" name="mesaj" required></textarea>
            
            <button type="submit">Gönder</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Adınız Soyadınız</p>
    </footer>
</body>
</html>

