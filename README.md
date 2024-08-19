-->
</head>

<body>

  <div id="bodyblur">
    <!-- Wallpaper / Background --><img src="https://i.ibb.co/gPF2XhZ/b8fbc39ff32d93a15ce23fe9146e2387.webp"
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
          title: 'Hii Sayanggkuu! 😍',
          imageUrl: '' + stiker1.src,
        });

        await swalst.fire({
          title: 'Sorry tau kalau orang<br>Selalu buat sayang sakit hati🫠',
          imageUrl: '' + stiker2.src,
        });

        await swalst.fire({
          title: 'Dan Buat Sayangg Marah²  🫠',
          imageUrl: '' + stiker3.src,
        });

        await swalst.fire({
          title: 'Orang Just Nak Cakap.. 🫶',
          imageUrl: '' + stiker4.src,
        });

        katangetik = "<b class='putih merah fontalt'>Sorry</b> Orang belum boleh jadi<br>yang terbaik buat sayang,<br><br>Orang pun belum boleh nakk memahami sayang dengan baikk dan cara yang sayang ingin kann,<br><br>Orang terlalu banyak kekurangan untuk orang sespesial sayangg,<br><br>Tapi... Orang akan berusaha yang terbaik buat sayang 🥰";
        katangetik2 = "<i>I Love uuu more</i> 💐🫣🩷";

        setTimeout(kpemb, 200);
      }
    </script>
</body>

</html>
