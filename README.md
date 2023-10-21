# css-flexbox

CSS FLEXBOX

Flexbox (Flexible Box) adalah sebuah metode tata letak (layout) dalam CSS yang dirancang untuk merancang dan mengatur elemen-elemen HTML di dalam kontainer dengan cara yang responsif dan mudah diatur. Flexbox sangat berguna untuk mengatur elemen-elemen dalam satu dimensi, biasanya baris atau kolom, sehingga mereka dapat menyesuaikan ruang dengan lebih baik.

Berikut adalah beberapa properti yang sering digunakan dalam CSS Flexbox beserta nilai-nilai yang relevan:

1. `display`:
   - Nilai: `flex`, `inline-flex`
   - Properti `display` digunakan untuk mengubah elemen menjadi wadah flexbox. Nilai `flex` akan membuat elemen menjadi blok-level, sementara `inline-flex` akan membuatnya menjadi inline-level.

2. `flex-direction`:
   - Nilai: `row`, `row-reverse`, `column`, `column-reverse`
   - Properti ini mengatur arah utama dari flex container. Nilai `row` membuat elemen-elemen berada dalam satu baris, `column` membuatnya dalam satu kolom, dan nilai dengan `-reverse` akan membalik arahnya.

3. `flex-wrap`:
   - Nilai: `nowrap`, `wrap`, `wrap-reverse`
   - Properti ini mengatur apakah elemen-elemen flexbox harus melanjutkan ke baris/kolom berikutnya ketika mereka tidak muat dalam satu baris/kolom. `nowrap` berarti elemen-elemen tetap dalam satu baris/kolom, `wrap` akan membuat mereka melanjutkan ke baris/kolom berikutnya jika perlu, dan `wrap-reverse` akan membalik arahnya.

4. `justify-content`:
   - Nilai: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`
   - Properti ini mengatur cara elemen-elemen flexbox sejajar dengan arah utama. Misalnya, `flex-start` akan menjaga elemen-elemen di sisi awal kontainer, sementara `space-between` akan meratakan elemen-elemen dengan ruang di antara mereka.

5. `align-items`:
   - Nilai: `flex-start`, `flex-end`, `center`, `baseline`, `stretch`
   - Properti ini mengatur cara elemen-elemen flexbox sejajar dengan arah silang (cross-axis). `stretch` akan mengisi seluruh ketinggian (jika dalam arah kolom) atau lebar (jika dalam arah baris) kontainer.

6. `align-content`:
   - Nilai: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `stretch`
   - Properti ini mengatur cara kontainer flexbox menyesuaikan elemen-elemen jika mereka ada dalam lebih dari satu baris atau kolom.

7. `flex-grow`:
   - Nilai: Angka
   - Properti ini mengatur bagaimana elemen-elemen flexbox harus berbagi ruang tambahan jika ada. Semakin besar nilai `flex-grow`, semakin banyak ruang ekstra yang akan mereka ambil.

8. `flex-shrink`:
   - Nilai: Angka
   - Properti ini mengatur bagaimana elemen-elemen flexbox harus menyusut jika tidak cukup ruang. Semakin besar nilai `flex-shrink`, semakin banyak elemen akan menyusut.

9. `flex-basis`:
   - Nilai: Panjang (px, %, rem, dll.)
   - Properti ini menentukan ukuran awal elemen sebelum pertimbangan `flex-grow` dan `flex-shrink`.

10. `order`:
    - Nilai: Angka
    - Properti ini mengatur urutan elemen-elemen flexbox dalam kontainer. Elemen dengan nilai `order` yang lebih kecil akan datang lebih awal.

Ini hanyalah beberapa properti utama dalam CSS Flexbox. Gabungan dari properti-properti ini memungkinkan Anda untuk mengatur tata letak elemen-elemen HTML dengan lebih fleksibel dan responsif dalam satu dimensi. Anda dapat menggabungkan properti-properti ini dalam berbagai cara untuk mencapai hasil yang diinginkan dalam desain web Anda.
