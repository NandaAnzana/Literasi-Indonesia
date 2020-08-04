<h1>NLP untuk menirukan struktur bahasa sastrawan Indonesia</h1>

![Sastrawan Indonesia](/gambar/Sastrawan-Indonesia.png)

<p>Indonesia mempunyai banyak sastrawan besar. Baru-baru ini, Indonesia kehilangan salah satu sastrawan besarnya, yaitu Alm. Bapak Sapardi Djoko Damono. Bapak Sapardi meninggalkan karya-karya yang sangat besar bagi perkembangan sastra Indonesia. Salah satu puisinya yang masih menjadi favorit saya sampai hari ini yang berjudul aku ingin. <br>
<br>
<em>Aku ingin mencintaimu dengan sederhana<br>
dengan kata yang tak sempat diucapkan<br>
kayu kepada api yang menjadikannya abu<br>
<br>
Aku ingin mencintaimu dengan sederhana<br>
dengan isyarat yang tak sempat disampaikan<br>
awan kepada hujan yang menjadikannya tiada</em><br>
<br>
Ada keindahan dan kesedihan yang terangkai dalam puisi tersebut. Sebelum Alm. Bapak Sapardi Djoko Damono, banyak sastrawan Indonesia lain yang sudah berpulang lebih dulu dan kita tidak sempat merasakan karya-karya baru mereka. Untuk mengenang para sastrawan ini, saya memutuskan untuk membuat salah satu A.I. yang nantinya mempelajari struktur dari karya sastra berbahasa Indonesia. Tapi agar A.I. ini bisa belajar dengan baik, data yang dibutuhkan sangat besar, setidaknya mengandung <strong>1 juta karakter</strong> atau <strong>200 ribu kata</strong> dan sepertinya di Indonesia belum ada data open source yang seperti itu. Untuk itu, saya mengajak teman-teman untuk bersama-sama mengumpulkan data berupa puisi, novel, cerpen, atau karya sastra lainnya dari para sastrawan di Indonesia dan mengubahnya dalam bentuk file txt agar lebih mudah dianalisis oleh A.I.
</p>

<h4>Sampai kapanpun A.I. tidak akan pernah bisa menggantikan para sastrawan yang sudah tiada. Karena menulis sastra bukan hanya soal keindahan struktur bahasa, tapi juga perasaan-perasaan yang terkandung di karyanya.</h4>
<h4>Data ini harus digunakan untuk kepentingan penelitian saja.</h4>

<h1>Arsitektur Model</h1>

<p>Model ini sangat sederhana (yang mana nanti bisa berubah menjadi lebih kompleks) dengan menggunakan framework Tensorflow 2 dan menggunakan Sequantial API dari Keras. Karena perkembangan yang pesat dari NLP, bukan tidak mungkin ke depannya model pada repository ini akan menggunakan Transformers dengan beberapa perubahan tentunya. Model akan terdiri dari 4 layer, dimana layer pertama berupa input, lalu ada layer embedding, dan 2 layer full connected. Berikut adalah gambar arsitekturnya.</p>