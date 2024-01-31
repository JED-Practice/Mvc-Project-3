# Hotel Project

## Proyekt haqqında

Bu proyektdə bir hotel web saytını hazırlamalıyıq. Saytda istifadəçilər hotel otaqlarına baxa bilməli, sayta abunə ola bilməli, otaqlara comment yaza bilməli və otağı rezerv edəbilməlidir. Həmçinin bir admin panelimiz olmalıdır ki, bu məlumatlar orada əlavə olunsun, yenilənsin, silinsin və.s proseslər görülsün.

## Əsas özəlliklər

1. Login/Register:

   - İstifadəçilərin rahatlığı üçün login və register məntiqi yazın
   - Rollar istifadə edərək admin və ya sadəcə user olduğunu müəyyən edin

2. Hotel otağı yaradarkən:

   - Model düzgün qurulmalıdır və bütün özəllikləri nəzərə alınmalıdır.

3. Partial View məntiqi:

   - Proyektdə təkrarlanan hissələri partial view-da yazmaq lazımdır.

4. Axtarış:

   - İstifadəçilər hotel adına, kategoriyasına uyğun axtarış edə bilməlidir.

5. İstifadəçi profili:
   - Istifadəçilər istəsələr, profil şəkli əlavə edə bilərlər və ya istməsələr belə default bir şəkil olmalıdır.
   - İstədikləri zaman məlumatlarını dəyişə bilməlidirlər.
   - Öz kommentlərini görə bilməlidirlər.
6. Hotel otağı admin tərəfdən:

   - Adminlər istənilən bir məlumatı silə bilməlidir
   - Silmək isə iki cür olmalıdır ilk növbədə sadəcə deaktiv olmalı sonra isə tamamilə silinməlidir
   - Adminlər hazırda saytda olan otaqların sayını görə bilməlidir
   - Adminlər hotel otaqları üçün kateqoriya yarada bilməli və onları idarə edə bilməlidir
     -Adminlər hotel otaqlarını yarada, silə və ya yeniləyə bilməlidir
   - Adminlər yazılan bütün kommentləri qəbul edə və ya ləğv edə bilməlidir.
   - Qəbul edilmiş kommentləri isə ayrıca görə bilməlidirlər

7. Təhlükəsizlik:
   - Yuxarıda da qeyd edildiyi kimi rol əsaslı avtorizasiya olmalıdır.
   - Eləcə də qonaq(guest) modu olmalıdır ki, hesabı olmayan istifadəçilər otaqları görə bilsin lakin komment yaza bilməsin
   - Register-dən sonra istifadəçinin daxil etdiyi mailə təsdiq linki göndərilməlidir təsdiq edildikdən sonra artıq Login mümkün olmalıdır

### Challange (optional)

Bu hisə sizin seçiminizdən asılıdır ki, istəsəz yaza bilərsiz.

- filterlərləmə yaza bilərsiz ki, otağın kateqoriyasına, qiymətinə görə istifadəçi axtarış edə bilsin.
