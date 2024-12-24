# Ehliyet Alabilme Durumu Kontrolü

Bu Python programı, kullanıcıların yaş ve eğitim seviyesi bilgilerini alarak, ehliyet alıp alamayacaklarını kontrol eder. Program, kullanıcının yaşının 18 ve üzerinde olup olmadığını ve eğitim seviyesinin belirli bir düzeyde olup olmadığını değerlendirir.

## Kullanım Adımları

1. **Adınızı Girin**: Program, kullanıcıdan adını isteyecektir.
2. **Yaşınızı Girin**: Yaşınızı girmelisiniz. Eğer yaşınız 18'den küçükse, ehliyet almak için yeterli olamayacağınız belirtilir.
3. **Eğitim Seviyenizi Girin**: Program, eğitim seviyenizi (İlköğretim, Ortaöğretim, Lise, Lisans, Ön Lisans, Yüksek Lisans, Doktora) girmenizi isteyecektir. Eğer girdiğiniz eğitim seviyesi "Lise", "Lisans", "Yüksek Lisans", "Doktora" veya "Ön Lisans" ise, ehliyet alabileceğiniz belirtilir. Aksi takdirde, eğitim seviyenizin yeterli olmadığı bildirilir.

## Örnek Çıktılar

- **Yaşınız 18'den küçükse**:
  ```
  Üzgünüm, yaşınız ehliyet almak için yeterli değil.
  ```

- **Yaşınız 18 veya daha büyükse ve eğitim seviyeniz yeterliyse**:
  ```
  Tebrikler! Ehliyet alabilirsiniz.
  ```

- **Eğitim seviyeniz yeterli değilse**:
  ```
  Üzgünüm, eğitim seviyeniz ehliyet almak için yeterli değil.
  ```

## Geliştirme Fikirleri

- Eğitim seviyesi kontrolünü daha fazla seçenekle genişletebilirsiniz.
- Yaş kontrolü, 18'den küçük olanlar için doğrudan "ehliyet almak için yeterli değil" mesajı vermek yerine, kullanıcıya belirli bir yaşa kadar geçerli olan farklı seçenekler sunulabilir.
