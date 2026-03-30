1. Ürün Özeti (Executive Summary)
NeuroStudy, 7-26 yaş arası öğrencilerin akademik metinleri okurken yaşadığı "bilişsel yorgunluğu" ve "odak kaybını" yapay zeka (Gemini API) ile çözen, kişiselleştirilmiş bir bilişsel okuma asistanıdır. Statik ve tek tip metinleri; kullanıcının yaşına uygun analojilerle yeniden yapılandırır, parçalara böler ve interaktif bir öğrenme yolculuğuna dönüştürür.

2. Kullanıcı Akışı (User Flow)
Giriş Paneli: Kullanıcıdan isim ve yaş grubu (7-12, 13-18, 19-26) bilgisi alınır. Bu seçim, arka plandaki AI "Prompt Logic"ini tetikler.

Input Alanı: Kullanıcı anlamakta zorlandığı akademik makale, ders notu veya karmaşık metni yapıştırır.

Bilişsel Analiz Süreci: "Odaklan" butonu ile Gemini API devreye girer. Metin sadece özetlenmez; kullanıcının yaş grubuna göre semantik olarak yeniden inşa edilir.

Okuma Stüdyosu:

Sol Panel: Orijinal metin (referans için).

Sağ Panel: AI tarafından üretilen "Nöro-Dostu" (basitleştirilmiş, analojilerle zenginleştirilmiş) versiyon.

Check-point Sistemi: Okuma akışını bozmadan, her 3-4 paragrafta bir AI durur ve bağlamsal, yaşa uygun bir sorgulama sorusu sorar.

3. Temel Özellikler (Key Features)
Age-Adaptive Engine:

Çocuk (7-12): Masalsı dil, oyun/oyuncak analojileri, kısa ve somut cümleler.

Genç (13-18): Sınav odaklı (LGS/YKS), günlük hayat örnekleri, motivasyonel dil.

Üniversite (19-26): Akademik derinliği koruyan ama akıcı, sektörel ve mantıksal analojiler içeren profesyonel ton.

Bionic Reading Entegrasyonu: Kelimelerin ilk harflerinin kalın (bold) yapılmasıyla gözün metin üzerinde daha hızlı ve odaklı kaymasını sağlayan görsel mod.

Smart Pop-ups: Metin içindeki ağır terimlerin üzerine tıklandığında, yaş grubuna özel "Bunu şöyle düşün..." açıklamaları.

Empatik Geri Bildirim (Confidence AI): Yanlış cevaplarda bile öğrencinin çabasını ödüllendiren, "Harika bir deneme!" gibi motivasyonel ve yönlendirici geri bildirimler.

4. Tasarım Gereksinimleri (UI/UX)
Renk Paleti: Göz yorgunluğunu minimize eden "Soft Cream" arka plan (#FFFDF5) ve yüksek kontrastlı koyu gri metinler (#333333).

Tipografi: Okunabilirliği maksimize eden "Inter" veya "Open Sans" font ailesi.

Minimalizm: Karmaşık menülerden arındırılmış, sadece metne ve öğrenmeye odaklanan "Clean-UI" felsefesi.

5. Teknik Altyapı
Frontend: React / Tailwind CSS (Lovable altyapısı ile optimize edilmiş).

AI Engine: Google Gemini 1.5 Flash (Düşük gecikme süresi ve yüksek anlama kapasitesi).

Prompt Stratejisi: "Sen uzman bir pedagog ve bilişsel antrenörsün. [YAŞ] yaşındaki bir öğrenci için metni [ANALOJİ] kullanarak, parçalara bölünmüş şekilde yeniden kurgula."

AI Integration: Google Gemini 1.5 Flash API (Hızlı ve düşük maliyetli).

Prompt Logic: AI'ya gönderilecek komut şablonu: "Sen uzman bir pedagogsun. Aşağıdaki metni [YAŞ] yaşındaki bir öğrenci için basitleştir, parçalara böl ve [ANALOJİ TÜRÜ] kullanarak açıkla."
