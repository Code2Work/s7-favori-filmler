# Favori Filmler

Favori filmlerini listelemek için bir web uygulaması yapmaya karar verdin. Her zamanki gibi küçük ölçekte componentları oluşturarak ve statik verilerle çalışarak başladın.

## Amaç

- Birden çok route ile çalışmak, url parametreleri ile dinamik routeları kullanmak.
- Uygulama bir dosyadan import ettiği filmleri listelemeli, detay sayfalarını görüntülemeli ve "kaydet" butonuna basıldığında o filmi "Kaydedilen Filmler" listesine eklemeli. [Demo videosunda](http://player.vimeo.com/video/1095757548) detayları bulabilirsin.
- [react-router](https://v5.reactrouter.com/web/guides/quick-start) kütüphanesini (v5) kullanman bekleniyor.
- Projeyi ve testleri çalıştırma komutlarından önce paketi kurduğundan emin ol. Kurulum adımları üstteki linkte mevcut.
- Çalışma dosyaların: `src/main.jsx`, `src/App.jsx`, `src/components/MovieDetails.jsx`, `src/components/MovieBox.jsx`. Detaylı yönergeler bu dosyalarda.
- Projeyi mutlaka çalıştır ve browserdan örnek video ile karşılaştırarak ilerle.
- Unutma, takıldığın yerlerde terminaldeki test mesajlarında ipuçları bulabilirsin.

## 🔧 VS Code Hazırlığı

### ESLint Eklentisi (Zorunlu)

ESLint, JavaScript ve JSX dosyalarınızda kod kalitesini artırmak için hataları ve stil tutarsızlıklarını otomatik olarak tespit eder. Prettier ile birlikte kullanıldığında otomatik olarak düzeltme imkanı sunar.

**Kurulum:**

1. VS Code'da sol paneldeki **Extensions** (📦) simgesine tıklayın
2. Arama kutusuna `ESLint` yazın
3. **Microsoft** tarafından sunulan eklentiyi bulun
4. **Install** butonuna tıklayın

**Kullanım:**

- Bir `.js`, `.jsx`, `.ts` veya `.tsx` dosyası açtığınızda ESLint otomatik olarak çalışır
- Hatalar ve uyarılar satır üzerinde kırmızı veya sarı renkle gösterilir
- Sağ alttaki **Problems** sekmesinden tüm dosyadaki sorunları görebilirsiniz
- Otomatik düzeltme yapmak için alttaki **Prettier** eklentisi kurulum adımlarını tamamlayın

> **Geleceğe Not:** Bir projede bu işlemlerin olabilmesi için `eslint` paketi ve bir konfigürasyon dosyası (`.eslint.config.js`) bulunmalıdır. Yoksa VS Code eklentisi çalışmaz. (Projede bu paket ve ayar dosyaları var, o yüzden ekstra bir şey yapmanız gerekmiyor.)

### Prettier Eklentisi (Zorunlu)

Kodunuzu otomatik olarak düzenler ve formatlar.

**Kurulum:**

1. Extensions bölümünde `Prettier` arayın
2. **"Prettier - Code formatter"** eklentisini kurun
3. **Ayarlar** → **"Format On Save"** seçeneğini aktif edin

## 🚀 Projeye Başlama

### Adım 1: Projeyi Kendi Hesabınıza Kopyalayın

1. Bu sayfanın sağ üst köşesindeki **Fork** butonuna tıklayın
2. Kendi GitHub hesabınızda proje kopyası oluşacak

### Adım 2: Projeyi Bilgisayarınıza İndirin

Görseldeki adımları takip edin ya da terminali kullanabilirsiniz.

```bash
git clone [buraya-kendi-fork-linkinizi-yazın]
cd [proje-klasor-adi]
```

### Adım 3: Gerekli Kurulumları Yapın

Terminal açın ve sırasıyla şu komutları çalıştırın:

```bash
npm install
npm run c2w
```

> **💡 İpucu:** Bu komutlar gerekli paketleri yükler ve test sistemini başlatır.

### Adım 4: Projeyi Çalıştırın ve Browserda Görüntüleyin

Yeni bir terminal tabı açın ve şu komutu çalıştırın:

```bash
npm run dev
```

Bu komut projeyi çalıştıracak ve bir link verecek. Bu linki browserda açın ve yazdıklarınızın çıktısını gözlemleyin.

## 📝 Geliştirme Süreci

### 0. Öğrenci numaranızı `student_id.txt` dosyasına yazın 

### 1. Testleri Takip Edin

- Testlerin çalıştığı trminali açık tutun ve test çıktılarını izleyin
- Başarılı testler ✅, başarısız testler ❌ ile gösterilir

### 2. Adım Adım İlerleyin

- Her küçük ilerleme sonrası değişiklikleri kaydedin
- Testlerin durumunu kontrol edin
- Bir özelliği tamamen bitirdikten sonra commit yapın

### 3. Düzenli Commit Yapın

GitHub Desktop uygulamasını kullanarak ilerlemenizi sıklıkla GitHub'a gönderin.
Ya da terminali kullanabilirsiniz:

```bash
git add .
git commit -m "Anlamlı bir commit mesajı"
git push origin main
```

## 🧪 Otomatik Değerlendirme Sistemi

Bu proje otomatik test sistemi ile gelir. Test sonuçları terminal penceresinde görünür. Kırmızı (❌) testleri yeşile (✅) çevirmeye odaklanın.

## 🆘 Sorun Giderme

### Yaygın Sorunlar:

- **npm komutları çalışmıyor:** Node.js kurulu olduğundan emin olun
- **Testler çalışmıyor:** Terminal penceresini kapatıp `npm run c2w` komutunu tekrar çalıştırın

### Yardım İçin:

1. Terminal hatasını tam olarak okuyun
2. Dosya yollarının doğru olduğunu kontrol edin
3. Değişiklikleri kaydettiğinizden emin olun

## 📋 Çalışma Akışı Özeti

1. ✅ Projeyi fork edin ve clone edin
2. ✅ `npm install` ve `npm run c2w` çalıştırın
3. ✅ `npm run dev` ile projeyi çalıştırın ve size verdiği linki açarak yaptıklarınızı takip edin
4. ✅ Terminal'den test sonuçlarını takip edin
5. ✅ Düzenli olarak commit yapın
6. ✅ İlerleyişinizi GitHub'a push edin

**İyi çalışmalar! 🎨✨**
