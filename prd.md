Mükemmel bir PRD akışı oldu Nazlıcan. Mevcut çalışan uygulamadaki Dark Mode (Karanlık Mod) ve Bilişsel Ergonomi detaylarını da teknik gereksinimlere profesyonel bir dille ekledim. Bu doküman, 31 Mart jürisine projenin teknik ve mantıksal olarak ne kadar sağlam temellere oturduğunu kanıtlayacak.

İşte en güncel ve kapsamlı prd.md içeriğin:

📄 NeuroStudy - Product Requirements Document (PRD) v2.1
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

Adaptive Theme (Dark Mode): Gündüz kullanımı için "Soft Cream" (#FFFDF5), gece kullanımı ve uzun süreli okumalar için göz yorgunluğunu önleyen tam uyumlu Dark Mode desteği.

Smart Pop-ups: Metin içindeki ağır terimlerin üzerine tıklandığında, yaş grubuna özel "Bunu şöyle düşün..." açıklamaları.

Empatik Geri Bildirim (Confidence AI): Yanlış cevaplarda bile öğrencinin çabasını ödüllendiren, "Harika bir deneme!" gibi motivasyonel ve yönlendirici geri bildirimler.

4. Tasarım Gereksinimleri (UI/UX)
Renk Paleti: Bilişsel ergonomi odaklı, kontrastı dengelenmiş Gündüz/Gece modları.

Tipografi: Okunabilirliği maksimize eden "Inter" veya "Open Sans" font ailesi.

Sadelik (Clean-UI): Karmaşık menülerden arındırılmış, sadece metne ve öğrenmeye odaklanan minimal arayüz.

5. Teknik Altyapı ve AI Mantığı
Frontend: React / Tailwind CSS (Lovable altyapısı ile optimize edilmiş).

AI Engine: Google Gemini 1.5 Flash API (Hızlı yanıt süresi ve düşük token maliyeti).

Prompt Logic: AI'ya gönderilecek sistem talimatı: "Sen uzman bir pedagog ve bilişsel antrenörsün. Aşağıdaki metni [YAŞ] yaşındaki bir öğrenci için basitleştir, parçalara böl ve [ANALOJİ TÜRÜ] kullanarak açıkla. Metnin ruhunu bozma ama dilini tamamen adapte et."
AI Integration: Google Gemini 1.5 Flash API (Hızlı ve düşük maliyetli).

Prompt Logic: AI'ya gönderilecek komut şablonu: "Sen uzman bir pedagogsun. Aşağıdaki metni [YAŞ] yaşındaki bir öğrenci için basitleştir, parçalara böl ve [ANALOJİ TÜRÜ] kullanarak açıkla."
