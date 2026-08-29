# Roster Pay — GitHub Pages

Bu klasör doğrudan GitHub Pages için hazırlanmıştır.

## Kurulum

1. GitHub'da yeni bir repository oluşturun. Örn: `roster-pay`
2. Bu ZIP'in içindeki **dosyaları repository'nin kök dizinine** yükleyin.
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `.nojekyll`
3. GitHub repository içinde:
   - **Settings**
   - **Pages**
   - **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
   - **Save**
4. Birkaç dakika sonra GitHub size şu biçimde bir adres verir:
   `https://KULLANICI-ADI.github.io/roster-pay/`
5. Bu adresi iPhone'da **Safari** ile açın.
6. Safari: **Paylaş > Ana Ekrana Ekle**

## Notlar

- Uygulama SunExpress roster PDF formatına göre hazırlanmış beta sürümdür.
- Vergi iadesi ve kişisel sigorta/vergi düzeltmeleri maaş tahminine dahil değildir.
- Yatı tam/yarım sayıları bu sürümde manuel kontrol edilebilir.
- TRI eğitim günleri virgülle yazılır: `1,2,6,7`
- İlk kullanımda PDF.js internetten yüklenir.
