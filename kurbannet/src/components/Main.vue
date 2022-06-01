<template>
  <div class="container">
    <v-dialog
      v-model="dialog"
      transition="dialog-bottom-transition"
      width="500px"
    >
      <img src="@/assets/afis.jpg" alt="" />
      <v-btn color="grey" @click="dialog = !dialog">Kapat</v-btn>
    </v-dialog>
    <div class="card">
      <div class="row p-3">
        <h1 class="display-1" style="text-align: center">
          Kurbanın Yedi Mühim Faydası
        </h1>
        <v-subheader class="mb-5">
          Maddi ve Manevi Olmak Üzere Kurbanın Yedi Mühim Faydası Vardır;
        </v-subheader>
        <div class="col-sm-6">
          <v-card elevation="0">
            <p>- Gadab-ı İlahi'yi söndürür.</p>
            <p>- Çok kurban kesilen memlekette harp olmaz</p>

            <p>- Kurban bayramında umumi affı ilahi tecelli eder</p>
            <p>
              - Eğer bir insan vakti hali musait olup da kurban kesmezse, ya
              kendisinden, ya çocuğundan ya da servetinden ve varlığından
              mutlaka kan çıkar. Kurbana riayet eden cemiyetler bu felaketlerden
              muhafaza olunurlar. -S.H.T.
            </p>
          </v-card>
        </div>
        <div class="col-sm-6">
          <v-card elevation="0">
            <p>- Rıza-i ilahi'yi celp eder.</p>
            <p>
              - Kurbanda çocuklar ve fakirler için umumi bir maslahat ve mutlak
              menfaat vardır.
            </p>
            <p>
              - Kurbana inanmayan ateistlerin gayesi, neticesi ve sonu
              intihardır. Maddi ya da manevi cihetten kendi kendilerini
              katlederek ebedi cehenneme yuvalanırlar.
            </p>
            <p>
              Ey Habibim sana kevseri verdik. Öyleyse Rabbine kulluk et ve
              kurban kes. Asıl ebter yani soyu kesik olan şüphesiz sana hınç
              besleyendir.
              <br />
              el-Kevser, 108/1-3
            </p>
          </v-card>
        </div>
      </div>
    </div>
    <div class="mt-5 mb-5" style="text-align: center">
      <b>Muhterem Efendim</b>
      <p>
        Vacip, Adak, Akika, Şifa, Nafile kurbanlarınızı "Fi Sebilillah" Hz.
        Allah (c.c) Yolundaki, Tahsil Çağındaki Talebelerimize bağış
        yapabilirsiniz.
      </p>
    </div>

    <div class="navbar mt-5 mb-5">
      <v-btn
        class="p-5"
        width="45%"
        color="teal"
        @click="snackbar = true"
        href="tel://05056057307"
      >
        <div style="color: white">Kurban için Bize ulaşın</div>
      </v-btn>
      <v-btn
        class="p-5"
        width="45%"
        color="indigo"
        @click="snackbar = true"
        href="tel://05375922559"
      >
        <div style="color: white">Kurban için Bize ulaşın</div>
      </v-btn>
    </div>
    <div class="mb-5">
      <div class="row">
        <div class="col-sm-6">
          <h1 class="mb-5">GRUPLARIMIZ;</h1>
          <h2>1.Grup: 5000₺ - 5500₺</h2>
          <h2>2.Grup: 5500₺ - 6000₺</h2>
          <h2>3.Grup: 6000₺ - 6500₺</h2>
          <h2>4.Grup: 6500₺ - 7500₺</h2>
        </div>
        <div class="col-sm-6">
          <div>
            <img width="100%" src="@/assets/kurban5.jpg" alt="" />
          </div>
        </div>
      </div>

      <v-divider />
      <b>Barbaros Kurban Organizasyonu</b>
    </div>
    <div style="text-align: center">
      Cenab-ı Hak cümlemize kurban kesmeyi nasip eylesin.
    </div>
    <div class="row p-3">
      <h1 class="display-1">Akika Kurbanı</h1>
      <div class="col-sm-6">
        <v-card elevation="0">
          <p>
            Bir çocuğun dünyaya gelmesi, nefes alması, ilk kalp atışı,ilk "Anne"
            "Baba" demesi, her insan için dünyada karşılığı hiçbir şey ile
            kıyaslanamayacak kadar değerlidir.
          </p>
          <p>
            Cenab-ı Hakk'ın kullarına meccanen bahşettiği (Evlat) niğmetine
            şükür için kesilen kurbana 'Akika Kurbanı' denir.
          </p>

          <p>
            Akika kurbanı kesmek müstehaptır. Çocuk doğduğu günden itibaren her
            zaman kesilebilir.
          </p>
        </v-card>
      </div>
      <div class="col-sm-6" style="display: table-cell">
        <div>
          <img width="100%" src="@/assets/kurban1.jpg" alt="" />
        </div>
      </div>
    </div>
    <v-divider />
    <div class="row p-3">
      <h1 class="display-1">Adak Kurbanı</h1>
      <div class="col-sm-6" style="display: table-cell">
        <div>
          <img width="100%" src="@/assets/kurban2.jpg" alt="" />
        </div>
      </div>
      <div class="col-sm-6">
        <v-card elevation="0">
          <p>
            Hayatımız sürekli bir hedef peşinde bir şeyleri elde etmekle
            geçiyor. Hayırlı olacağına inandığımız bir sürü hayalimizin gerçek
            olmasını isteriz.
          </p>
          <p>
            Bazen de korkularımız olur ki bundan da emin olmak isteriz işte bu
            anlar kulun acizliğini fark etmesine imkan sağlayan çok önemli
            anlardır.
          </p>

          <p>
            <b>İşte o zaman bir kul olarak istediklerimizin</b> hayırlısıyla
            olmasını korktuklarımızdan güvende olmayı
            <b>Cenab-ı Haktan istemek en doğrusu olacaktır.</b>
          </p>
          <p>
            <b>
              Bu istediklerimizin gerçekleşmesi, bir problemin çözülmesi, bir
              belanın def edilmesi için bir (Kurban keserim) diye niyet etmek.
            </b>
            Durumun hayırlısıyla netice bulmasına sebep olabilir.işte bu durumda
            <b>Adak kurbanı</b> keseriz.
          </p>
        </v-card>
      </div>
    </div>
    <v-divider />
    <div class="row p-3">
      <h1 class="display-1">Nafile Kurban</h1>

      <div class="col-sm-6">
        <v-card elevation="0">
          <p>
            Kurban bayramı dışındaki zamanlarda sırd Allah'a yakınlık için
            kesilen kurbana <b>'Nafile Kurban'</b> denir.
          </p>
          <p>
            <b>Kurban kesmek Allah'a yakınlaştıran bir ibadettir.</b> Arapçada
            <b>kurb</b>
            kelimesi de <b>yakınlık</b> demektir. Nafile ibadetlerin temelinde
            de zaten Allah'a yakınlaşma vardır. Bunun için zaman zaman imkan
            nispetinde Nafile ibadet niyetiyle kurban kesilmelidir.
          </p>

          <p>
            <b>İşte o zaman bir kul olarak istediklerimizin</b> hayırlısıyla
            olmasını korktuklarımızdan güvende olmayı
            <b>Cenab-ı Haktan istemek en doğrusu olacaktır.</b>
          </p>
          <p>
            <b>
              Bu istediklerimizin gerçekleşmesi, bir problemin çözülmesi, bir
              belanın def edilmesi için bir (Kurban keserim) diye niyet etmek.
            </b>
            Durumun hayırlısıyla netice bulmasına sebep olabilir.işte bu durumda
            <b>Adak kurbanı</b> keseriz.
          </p>
        </v-card>
      </div>
      <div class="col-sm-6" style="display: table-cell">
        <div>
          <img width="100%" src="@/assets/kurban3.jpg" alt="" />
        </div>
      </div>
    </div>
    <v-divider />
    <div class="row p-3">
      <h1 class="display-1">Şifa Kurbanı</h1>
      <div class="col-sm-6" style="display: table-cell">
        <div>
          <img width="100%" src="@/assets/kurban4.jpg" alt="" />
        </div>
      </div>
      <div class="col-sm-6">
        <v-card elevation="0">
          <p>
            Sağlık sorunlarıyla karşı karşıya kaldığımızda veya bir yakınımız
            hastalandığında ise Cenab-ı Hakk'a dua etmek, maddi çareler bularak,
            hastamızın derdine deva bulmaya çalışırken, şifasını Cenab-ı
            Hakk'tan da istemek gerekir.
          </p>
          <p>
            Bunun için hatimler okumak, dua etmek ve bu niyetle kurban kesmek
            güzeldir. Tabi, Allah'a tevekkül, maddi ve manevi her türlü vazifeyi
            yerine getirdikten sonra neticeyi beklemeye denir. Bizlere düşen,
            maddi ve manevi her türlü adımı atmaktır.
          </p>
        </v-card>
      </div>
    </div>
    <v-divider />

    <v-snackbar style="margin: auto" v-model="snackbar" timeout="2000">
      <div>Yönlendiriliyorsunuz</div>
    </v-snackbar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      snackbar: false,
      dialog: true,
    };
  },
};
</script>

<style></style>
