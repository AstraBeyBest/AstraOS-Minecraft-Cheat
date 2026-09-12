# 🌌 **AstraOS Client v2 Wurst Sürüm v7.54.1 — Güncelleme Notları & Kurulum Rehberi**

AstraOS Client projemizdeki tüm bu büyük tasarım, performans ve işlevsellik yenilikleriyle oyun deneyiminizi zirveye taşıyoruz! 🚀
( Yeni Versiyon Release Kısmında )
---

## 🌟 **Yapılan Temel İyileştirmeler ve Yenilikler**

### 1. 🪟 **Modernleştirilmiş ClickGUI & Navigator Menü**

* **Arka Plan Karartması (Backdrop Dim):** Menüler açıldığında arkasındaki oyun dünyası şık bir koyu akrilik tonla hafifçe karartılır, pencereler ön plana çıkar.
* **Koyu Obsidyen Cam Tasarım:** Pencerelerin tamamına derin obsidyen arka plan, yumuşak gölgelendirme ve gökkuşağı neon ayırıcı şeritler eklendi.
* **Yenilenen Butonlar:** Kapalı modüller için koyu karo görünümleri, aktif modüller için canlı Zümrüt Yeşili - Astra Mavisi dikey gradyanları ve neon sol şeritler uygulandı.
* **Modern Arama Kapsülü:** Navigator ekranındaki eski arama çubuğu, 🔍 ikonlu ve odaklanıldığında parıldayan modern bir yapıya kavuşturuldu. Minimalist scrollbar eklendi.

### 2. 🎨 **Görsel HUD, AstraOS Markalaması & Ana Menü**

* **Özel Ana Menü (TitleScreen):**
* Derin mor gradyan gökyüzü ve LCG algoritmasıyla yerleştirilmiş 140 parlak yıldız.
* Midpoint displacement ile oluşturulan katmanlı dağ silüetleri.
* Animasyonlu mor-violet rainbow renkli, glow halolu **"AstraOS Client"** başlığı ve **"by astrabey_best"** imzası.
* Vanilya Minecraft Logosu ve sarı splash text'ler tamamen kaldırılarak yerine modern AstraOS tasarımı getirildi.


* **WurstLogo:** Genişletilmiş Wide Latin tipografi, gökkuşağı parıltılı kenarlık ve sol gradyan arka plan.
* **HackListHUD:** Sıkışık görünüm giderildi (`itemHeight: 14`, dikey ortalanmış metinler). Kategori simgeleri ve sol dikey durum çubuğu eklendi.
* **TabGui:** Satır vurgu arka planları ve aktif özellikler için `✦` göstergesi eklendi.

### 3. 📊 **Yeni Eklenen HUD Modülleri**

* **AstraHUD:** Sağ altta anlık yumuşatılmış FPS, Ping (ms) ve X/Y/Z koordinat paneli.
* **SpeedIndicatorHUD:** Sol altta m/s cinsinden şık hız göstergesi.
* **AstraNotificationHUD:** Sağ alttaki FPS panelinin hemen üzerinden başlayarak yukarıya doğru kayan, hack açılıp kapandığında bilgi veren şık toast bildirim sistemi (HackList ile çakışma sorunu tamamen çözüldü).

### 4. 💎 **Gelişmiş Mod Özellikleri ve Anti-XRay Koruması**

* **OreGlow (Bypass Anti-XRay):** Sunuculardaki sahte maden tuzaklarını (Engine Mode 2) filtreleyen 6 yönlü komşu tarama algoritması eklendi; sadece gerçek madenler parlatılır.
* **Criticals & BunnyHop Güncellemeleri:** Silah barı kontrolü (`Only when charged`), otomatik depara kalkma (`Auto Sprint`) ve hassas ivmelenme çarpanları eklendi.

---

# 🌌 **AstraOS Client — Fabric Kurulum Rehberi**

> **AstraOS Client** modumuzu tercih ettiğin için teşekkürler! Modun Fabric altyapısında sorunsuz çalışabilmesi için aşağıdaki adımları sırasıyla takip etmen yeterlidir. 🚀

---

### 📦 **Gereksinimler**

Kuruluma geçmeden önce bilgisayarında ve oyununda aşağıdakilerin olduğundan emin ol:

* ☕ **Java** (Oynadığın Minecraft sürümüne uygun sürüm)
* ⚙️ **Fabric Loader** ve uyumlu **Fabric API**

---

### 🛠️ **Adım Adım Kurulum Rehberi**

1. **Fabric API'yi İndirme:**
* Modumuz Fabric tabanlı olduğu için çalışabilmesi adına önce **Fabric API** modunu indirip hazırlaman gerekir.


2. **Mods Klasörünü Açma:**
* Klavyenden **`Windows + R`** tuşlarına aynı anda bas.
* Açılan çalıştır penceresine **`%appdata%\.minecraft`** yaz ve **Enter** tuşuna bas.
* Karşına çıkan klasörlerin arasından **`mods`** klasörünü bul ve içine gir (Eğer yoksa kendin yeni bir klasör açıp adını `mods` yapabilirsin).


3. **Dosyaları Atma:**
* İndirdiğin **AstraOS Client** dosyasını (`.jar`) ve **Fabric API** `.jar` dosyasını kopyala.
* İki dosyayı da doğrudan bu **`mods`** klasörünün içine yapıştır. *(Not: Dosyaları Rar/Zip'ten çıkarmadan, doğrudan `.jar` olarak atman gerekir.)*


4. **Oyunu Başlatma:**
* Minecraft Launcher'ı aç.
* Profil kısmından **Fabric** sürümünü seç ve **Oyuna Başla (Play)** de! 🎮



---

### ⚠️ **Önemli İpuçları & Hata Çözümleri**

* ❌ *Mod oyun içinde görünmüyor mu veya çökme yaşanıyor mu?* Doğru sürümde bir **Fabric Loader** kullandığından ve **Fabric API**'nin de mods klasöründe olduğundan emin ol.
* 🛡️ *Antivirüs uyarısı alırsan:* Bazı client dosyaları güvenli olmasına rağmen yanlış alarm verebilir. İçin rahat olsun, tamamen güvenlidir.

> *Keyifli oyunlar dileriz! Takıldığın bir yer olursa bizimle iletişime geçmekten çekinme.* ✨
