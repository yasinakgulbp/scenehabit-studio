# SceneHabit Studio

Türkçe Assist seçenekleriyle çalışan tek kutulu prompt stüdyosu.

## Çalışma biçimi

- 262 başlangıç: 160 Promptwise hazır içerik metni, kurs bankalarından 100 benzersiz prompt, iki denenmiş fotoğraf uyarlaması.
- Metnini tek kutuya yaz veya hazır promptu aynen aç. Otomatik yeniden yazma, altı adımlı sihirbaz ve karakter yerleştirme bu ekranda yoktur.
- Assist menüsünün dokuz kategorisi ve 440 seçeneği özgün sırada korunur. Bütün seçenekler Türkçe görünür; seçilince özgün İngilizce ifade metnin sonuna eklenir.
- Eklenen etiketler × ile kaldırılır. Uygulama sadece kendi eklediği metin aralığını siler; kaynakta önceden bulunan aynı ifadeyi değiştirmez.
- Model, 10 oran, çözünürlük ve adet ayarları ayrı tutulur. Kopyala yalnız promptun kendisini panoya verir.
- Görsel / Video / Ses sekmeleri ayrı yerel taslaklar tutar. Referanslar yalnız yerel önizlemedir; dış üretim hizmetine ayrıca eklenir.
- Prompt iyileştirme ücretli ve kilitlidir. Kaynak geliştirme paketindeki server/enhance.ts ve enhance-preset.json, yetkilendirme ile AI adaptörü bağlanabilecek hazır altyapıdır. Bu statik GitHub Pages yayını ücret veya AI isteği çalıştırmaz.
- Önceki proje kayıtları ve yedekler korunur. Eski düzenleme ve planlama kaynakları geliştirme paketinde bulunur.

Bu uygulama bir dil modeli veya görsel/video motoru çalıştırmaz. Hazırlanan metinler dış üretim hizmetinde kullanılır. O hizmetin hesap ve ücretleri ayrıdır. Basit stüdyo taslakları tarayıcıda otomatik saklanır. Referans önizlemeleri sayfa kapandığında silinir. Önceki projeler için Yardım & yedek bölümünü kullan.

Statik yayın GitHub Pages üzerinden sunulur. Site ve içerdiği hazır çalışma metinleri herkese açıktır. Özel projeler bu depoya yüklenmez. Kurs PDF arşivi, ücretli kitap, oturum kayıtları ve hesap verileri yayın paketinde bulunmaz.

## Sürüm

3.0.0 · 28 Ekim 2026. React, Dexie ve Zod ile geliştirildi. Derlenmiş uygulama index.html içindedir. N01.jpg / N02.jpg uygulama için üretilmiş AI örnekleridir. Bileşen bildirimleri THIRD-PARTY-NOTICES.txt içindedir.
