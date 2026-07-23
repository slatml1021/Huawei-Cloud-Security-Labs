 Bu Ödevde Ne Öğreneceksiniz

Gerçek bir müşteri, gerçek bir regülasyon ve gerçek bir kelime sınırı altında yazı yazmak, iki oturum boyunca edindiğiniz bilgi ve becerileri pekiştirmenin en etkili yollarından biridir.

Bu görevde sizden, Huawei Cloud güvenlik değerlendirmesi sonrasında bir danışmanın müşterisine teslim edeceği profesyonel bir rapor hazırlamanız beklenmektedir. Rapor; gerçekçi bir mimari tasarım, risk değerlendirmesi ve uygulanabilir öneriler içermelidir.

Görev Tanımı
Kurgusal Müşteri: PayCarry Türkiye

PayCarry, Türkiye'de faaliyet gösteren, küçük işletmeler için günde yaklaşık 15.000 ödeme işlemi gerçekleştiren Series-B yatırım almış bir fintech şirketidir.

Şirket;

PCI DSS Level 1 sertifikasını 18 ay sonra yenileyecektir.
Şu anda farklı bir bulut sağlayıcısını kullanmaktadır.
Huawei Cloud TR-Istanbul bölgesine geçişi ciddi şekilde değerlendirmektedir.

Şirket CEO'sunun cevap aradığı iki temel soru vardır:

Production ortamında Zero-CVE hedefine nasıl ulaşabiliriz?
Denetim kanıtlarını yılda bir kez aceleyle hazırlamak yerine sürekli olarak nasıl üretebiliriz?

CEO teknik bilgiye sahiptir ancak siber güvenlik uzmanı değildir.

Hazırlanacak Rapor

Toplam 1.500–2.000 kelimelik profesyonel bir makale hazırlayın.

Aşağıdaki altı bölüm mutlaka bulunmalıdır.

Bölüm 1 — Yönetici Özeti (~150 kelime)

Üç kısa paragraf yazınız.

PayCarry'nin çözmeye çalıştığı problemi tek cümlede açıklayın.
En önemli mimari veya iş akışı önerinizi belirtin.
Çalışmanın başlamasından 90 gün sonra başarı kriterlerini açıklayın.
Bölüm 2 — Mimari Genel Bakış (~400 kelime)

Huawei Cloud üzerinde önerdiğiniz mimariyi aşağıdaki dört katmanda açıklayın.

Bir mimari diyagramı ekleyin (draw.io, ASCII veya elle çizilmiş olabilir).

Geliştirme Katmanı
CodeArts Repo
CodeArts Inspector
SAST
SCA
IaC Analizi
Pre-commit politikaları
Derleme/Test Katmanı
CodeArts Pipeline güvenlik kapıları
İmzalı artifact'lerin SWHR üzerinde saklanması
Staging ortamında DAST çalıştırılması
Çalışma Zamanı (Runtime) Katmanı
ELB arkasındaki ECS sunucuları
HSS Enterprise koruması
KMS tarafından yönetilen anahtarlar
Ön tarafta WAF
Yönetişim Katmanı
PCI DSS Compliance Pack ile SecMaster
Denetim kayıtları için CTS
Log yönetimi için LTS
Kanıt dışa aktarımı için Compliance Center
Bölüm 3 — Production Ortamında "Zero CVEs" Hedefine Nasıl Ulaşılır? (~400 kelime)

Shift-left yaklaşımı ile runtime defense-in-depth stratejisini açıklayın.

En az aşağıdaki konulara değinin:

CodeArts Inspector'da bulunan bir CVE'nin production ortamında bulunan aynı güvenlik açığına göre neden yaklaşık 100 kat daha düşük maliyetli olduğu.
HSS'in One-click Fix özelliğinin nasıl çalıştığı.
Güncelleme öncesinde alınan snapshot'ın neden önemli olduğu.
"Zero CVEs" ifadesinin bir hedef olduğu, garanti olmadığı.
Log4Shell benzeri kritik güvenlik açıkları ve HSS'in yaklaşık 48 saatlik güncelleme süreci.
Bölüm 4 — Sürekli PCI DSS Kanıtı Nasıl Üretilir? (~400 kelime)

Aşağıdaki konuları açıklayın.

SecMaster üzerindeki PCI DSS Compliance Pack aboneliği
Otomatik tarama sıklığı
Otomatik gerçekleştirilen kontroller
Manuel olarak yapılması gereken kontroller

Ayrıca aşağıdaki gereksinimlerden birini örnek olarak seçin.

PCI DSS Requirement 1 (Firewall)

veya

PCI DSS Requirement 8 (Kimlik Doğrulama)

Huawei Cloud servislerinin ilgili PCI DSS maddelerini nasıl karşıladığını açıklayın.

Compliance Center'ın denetim kanıtlarını nasıl kolayca dışa aktarılabilir hale getirdiğini anlatın.

Bulut sağlayıcılarının otomatikleştiremeyeceği maddeleri de dürüst şekilde belirtin.

Örneğin;

Güvenlik politikaları
Personel eğitimleri
Risk değerlendirmeleri
İç süreçler
Bölüm 5 — Risk Kaydı (~200 kelime + tablo)

Önerilen mimarinin en önemli 5 riskini belirleyin.

Her risk için;

Olasılık (Düşük / Orta / Yüksek)
Etki (Düşük / Orta / Yüksek)
Azaltma yöntemi

bilgilerini tablo halinde sunun.

Örnek riskler:

Türkiye'de Huawei Cloud deneyimli mühendis sayısının az olması
TR-Istanbul bölgesinde bazı servislerin eksik olması
Cloud geçişi ile PCI DSS yenileme takviminin çakışması
İş ortaklarının Huawei Cloud hakkında ek güvenlik değerlendirmesi istemesi
Huawei'ye özel araçlara bağımlılık oluşması
Bölüm 6 — İlk 90 Gün Planı (~150 kelime + kontrol listesi)

Hafta bazında bir geçiş planı hazırlayın.

Hafta 1–2
Huawei Cloud hesabı oluşturulması
IAM yapılandırması
Network Landing Zone kurulumu
Hafta 3–6
Pilot uygulamanın taşınması
HSS'in etkinleştirilmesi
SecMaster baseline kontrollerinin açılması
Hafta 7–10
CodeArts Pipeline kurulumu
CodeArts Inspector entegrasyonu
Güvenlik kapılarının (Security Gates) etkinleştirilmesi
Hafta 11–13
PCI DSS Compliance Pack aboneliği
İlk güvenlik taraması
Eksiklerin giderilmesi
Deneme denetimi (Mock Audit)
Yazım Kuralları
Hedef Kitle: PayCarry CEO'su ve CTO'su
Yazım Dili: Açık, profesyonel ve pazarlama dili içermeyen İngilizce
Kaynak Gösterimi: Makale boyunca en az 6 Huawei Cloud dokümanına atıf yapılmalıdır.
Dürüstlük: En az iki gerçek dezavantaj veya sınırlama belirtilmelidir.
Uzunluk: 1.500–2.000 kelime (mimari diyagram ve risk tablosu hariç)
Teslim Edilecekler
Word veya PDF formatında hazırlanmış makale
Mimari diyagram
5 satırlık Risk Register tablosu
En az 8 farklı kaynak URL'si içeren kaynakça
Bonus (İsteğe Bağlı)

Yaklaşık 5 dakikalık bir sunum videosu hazırlayın ve raporunuzu CEO'ya sunuyormuş gibi anlatın.

Öz Değerlendirme

Ertesi gün raporunuzu tekrar okuyun ve kendinize şu soruyu sorun:

"Eğer ben PayCarry'nin CEO'su olsaydım, bu rapor beni Huawei Cloud'a geçiş sözleşmesini imzalamaya ikna eder miydi?"
