-->
</head>

<body>

  <div id="bodyblur">
    <!-- Wallpaper / Background --><img src="<a href="https://ibb.co/7t5g8np"><img src="https://i.ibb.co/gPF2XhZ/b8fbc39ff32d93a15ce23fe9146e2387.webp"
      id="wallpaper" />
  </div>

  <div class="kumpulanstiker">
    <!-- Stiker untuk Konten -->
    <img src="https://feeldreams.github.io/pusn.gif" id="stiker1" />
    <img src="https://feeldreams.github.io/wortel.gif" id="stiker2" />
    <img src="https://feeldreams.github.io/mndkat.gif" id="stiker3" />
    <img src="https://feeldreams.github.io/ngumpet.gif" id="stiker4" />

    <div id='Content'>

      <div id="suratin" onClick="memulai();audio.play();">
        <!-- Surat --><img src="https://rayyscoding.github.io/envelope.png" />
      </div>
      <p id="ket">Klik Suratnya!</p>

      <div>
        <!-- Foto Akhir -->
        <img src="https://feeldreams.github.io/pandapukpuk.gif" id="fotoakhir" />
        <img src="https://feeldreams.github.io/gumush.gif" id="fotoakhir2" />
      </div>
      <div>
        <blockquote id='bq'>
          <p id="kalimat"></p>
          <p id="kalimatc"></p>
        </blockquote>
      </div>

      <!-- Tombol Kirim Pesan -->
      <div id="Tombol">
        <a onClick="sjawab()">
          <b>💌 Balas</b>
        </a>
      </div>

    </div>

    <script src="https://htmlku.com/akuakan/play/script.js"></script>

    <script type="text/javascript">
      async function pertama() {
        audio = new Audio('https://audio.jukehost.co.uk/5VfcVfr1D3fIU8m27X85m5HVkPyRIhQr'); showDiv();
      } pertama();


      async function pesan() {
        await swalst.fire({
          title: 'Hii Sayangg',
          imageUrl: '' + stiker1.src,
        });

        await swalst.fire({
          title: 'Sorry baby buat sayang sakit hati <br>Buat sayang nangis sorang ii buat sayang ovt🫠',
          imageUrl: '' + stiker2.src,
        });

        await swalst.fire({
          title: 'Sorry takk jaga hati sayang dengan baik  🫠',
          imageUrl: '' + stiker3.src,
        });

        await swalst.fire({
          title: 'Babyy just nak cakap ',
          imageUrl: '' + stiker4.src,
        });

        katangetik = "<b class='putih merah fontalt'>Sorry</b> Maafkan lelaki ini sayang, baby bukanlah lelaki sempurna  tapii jauh dari kata sempurna,<br><br>maaf kalau perangai baby banyak membuat sayang terasa,<br><br>maaf jugak tak dapat menjadi lelaki yang memahami setiap situasi sayang, baby ni hanyalah lelaki biasa,<br><br>but.... percayalah setiap saat i try untuk jadi lelaki versi terbaik untuk sayangg, tapi maaf kalau selalu gagal.";
        katangetik2 = "<i>I Love uuu sooo much sayang</i> 💐🫣🩷";

        setTimeout(kpemb, 200);
      }
    </script>
</body>

</html>
