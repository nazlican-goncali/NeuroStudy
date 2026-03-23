1. Ürün Özeti
NeuroStudy, 7-26 yaş arası öğrencilerin akademik metinleri okurken yaşadığı "bilişsel yorgunluğu" ve "odak kaybını" yapay zeka (Gemini API) ile çözen web tabanlı bir uygulamadır. Kullanıcı yaşını seçer, metni yapıştırır; AI metni o yaşa uygun analojilerle, parçalara bölünmüş ve etkileşimli bir formatta sunar.

2. Kullanıcı Akışı (User Flow)
Hoş Geldin Ekranı: Kullanıcıdan iki bilgi istenir: Adı ve Yaşı (7-26 aralığı).

Input Paneli: Kullanıcı anlamakta zorlandığı ders notunu veya makaleyi yapıştırır.

Analiz Süreci: "Odaklan" butonuna basılır. AI arka planda metni analiz eder.

Okuma Stüdyosu: Ekran ikiye bölünür. Sol tarafta orijinal metin, sağ tarafta AI'nın "Nöro-Dostu" (parçalanmış, kalınlaştırılmış, basitleştirilmiş) versiyonu.

Check-point: Her 3 paragrafta bir AI durur ve yaşa uygun bir soru sorar.

3. Temel Özellikler (MVP Kapsamı)
Age-Adaptive Engine: * Çocuk (7-12): Masalsı dil, oyun analojileri, çok kısa cümleler.

Genç (13-18): Sınav odaklı, günlük hayat örnekleri, orta uzunlukta cümleler.

Üniversite (19-26): Akademik ama akıcı dil, sektörel/mantıksal analojiler.

Bionic Reading: Kelimelerin ilk harflerinin kalın (bold) yapılması.

Smart Pop-ups: Ağır terimlerin (Termodinamik, Enflasyon vb.) üzerine tıklandığında yaşa uygun "Bunu şöyle düşün..." kutucukları.

Confidence Feedback: Yanlış cevapta bile "Harika bir deneme! Bir de şu açıdan bak..." diyen empatik metinler.

4. Tasarım Gereksinimleri (UI/UX)
Renk Paleti: Göz yormayan "Soft Cream" arka plan (#FFFDF5), koyu gri metinler (#333333).

Font: Okunabilirliği yüksek "Inter" veya "Open Sans".

Sadelik: Karmaşık menüler yok. Sadece metin ve okuma alanı.

5. Teknik Detaylar (Kodsuz Araçlar İçin)
Frontend: React / Tailwind CSS (Lovable üzerinden üretilecek).

AI Integration: Google Gemini 1.5 Flash API (Hızlı ve düşük maliyetli).

Prompt Logic: AI'ya gönderilecek komut şablonu: "Sen uzman bir pedagogsun. Aşağıdaki metni [YAŞ] yaşındaki bir öğrenci için basitleştir, parçalara böl ve [ANALOJİ TÜRÜ] kullanarak açıkla."
