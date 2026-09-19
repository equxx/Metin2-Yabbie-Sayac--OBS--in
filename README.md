# Yabbie Death Counter (Slot Animasyonlu OBS Ölüm Sayacı)

Bu proje, yayıncıların canlı yayınlarında (OBS Studio) kullanabileceği, **DCSB (Deathcounter and Soundboard)** programı ile anlık entegre çalışan ve **slot makinesi (odometre) tarzı dikey kayma animasyonuna** sahip modern bir ölüm sayacı arayüzüdür.

## Özellikler
- 🔄 Yerel `olumler.txt` dosyasını CORS engellerine takılmadan anlık (300ms) sorgular.
- 🎰 Rakam geçişlerinde pürüzsüz yukarı/aşağı kayma animasyonu sunar.
- 🎨 Şık, 3 bölmeli mekanik çerçeve tasarımı içerir.

## Kurulum ve Kullanım

1. Bu depodaki `index.html` dosyasını bilgisayarınıza indirin.
2. DCSB programınızın sayıları yazdığı `.txt` dosyasının adını `olumler.txt` yapın.
3. `index.html` ile `olumler.txt` dosyalarını **aynı klasörün içine yan yana** koyun.
4. OBS Studio'yu açın ve sahnenize yeni bir **Tarayıcı (Browser Source)** kaynağı ekleyin.
5. **Yerel Dosya (Local File)** kutucuğunu işaretleyip `index.html` dosyasını hedef gösterin.
6. Genişlik (Width): **500**, Yükseklik (Height): **150** olarak ayarlayın.
7. **"Yerel dosyalara erişime izin ver" (Allow access to local files)** seçeneğini mutlaka işaretleyin.
8. Özel CSS (Custom CSS) kutusunu tamamen boşaltın ve kaydedin.
