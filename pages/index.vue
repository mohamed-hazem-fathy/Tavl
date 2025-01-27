<template>
  <div class="landing">
    <v-img v-if="showLogo" class="img1" src="/public/imges/n-1.png" alt="Logo" />
    <v-img class="img" src="/public/imges/logo-desk.png" alt="Logo" />
    <div class="allBoxes">
      <h1 class="mt-2 mb-2 text-center" style="color: #dc979c">Boxes</h1>
      <v-container>
        <v-row class="products-row">
          <!--  product 1 -->
          <v-col class="box" cols="12" md="4">
            <div class="product-card">
              <v-card>
                <v-img
                  style="height: 290px; width: 100%"
                  src="/public/imges/Untitled-7.png"
                ></v-img>
              </v-card>
              <div class="product-info">
                <h3 style="font-size: 25px" class="product-title">Tavl Box</h3>
                <p style="font-size: 25px" class="product-price">
                  1500<span>EGB</span>
                </p>
              </div>
            </div>
          </v-col>

          <!--  product 2 -->
          <v-col cols="12" md="4">
            <div class="product-card">
              <v-card>
                <v-img
                  style="height: 290px"
                  src="/public/imges/box500.png"
                ></v-img>
              </v-card>
              <div class="product-info">
                <h3 style="font-size: 25px" class="product-title">
                  Anthor Box
                </h3>
                <p style="font-size: 25px" class="product-price">
                  500<span>EGB</span>
                </p>
              </div>
            </div>
          </v-col>
          <!--  product 3 -->
          <v-col cols="12" md="4">
            <div class="product-card">
              <v-card>
                <v-img
                  style="height: 290px"
                  cover
                  src="/public/imges//Untitled-3.png"
                ></v-img>
              </v-card>
              <div class="product-info">
                <h3 style="font-size: 25px" class="product-title">Third Box</h3>
                <p style="font-size: 25px" class="product-price">
                  Coming<span>Soon</span>
                </p>
              </div>
            </div>
          </v-col>
        </v-row>
      </v-container>
      <h1 class="mt-2 mb-2 text-center" style="color: #dc979c">Products</h1>
      <v-container>
        <v-row>
          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/WhatsApp Image 2025-01-26 at 21.38.04_4b397014.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Moist -1 Body Milk</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/sun cream.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Farm Stay Aloe Vera Perfect Sun Cream</span>
          </div>
          </v-col>





          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/moroccon.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Moroccan Soap</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/WhatsApp Image 2025-01-26 at 21.37.58_5a3facae.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">alice rose oil exception 2blades</span>
          </div>
          </v-col>




          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/creams.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Farm stay oil-free uv defence sun
            </span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/Soothing Gel.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Shaan Soothing Gel 200 gm & 60gm</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/oil .jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Moroccan Oil</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/shaan.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Shaan Rejuvenation cream 120 gm</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/geljpg.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">LEYLAK Moisturizing Gel 100 Ml</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/bobal.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Bobai sunscreen extra lightening gel spf 50</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/star ville.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Starville Anti-Bacterial Oil Gel Facial Wash</span>
          </div>
          </v-col>

          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/star white.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Whitening Cleanser 200 ML</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/vaselinejpg.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Vaseline Color & Care Strawberry Chapstick 4.5 g</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/smail candy.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Candy Balls Exfoliating Sugar Scrub For Sensitive Areas. Pink 300grams</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/wh.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Roll On Whitening 60 ML</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/soap.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Whitening Care Soap With Collagen, Vitamin E&C 90gm</span>
          </div>
          </v-col>
          <v-col cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/coc.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Bodylicious Coconut Breeze Roll On 50Ml - Set 2 Pcs</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/vio.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Violet Patchouli Antiperspirant Deodorant 50ML</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/pr.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">eva morning blossom body mist senses 240ml</span>
          </div>
          </v-col>
          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/phr.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Bodylicious Coconut Breeze Body Spray - 217 Ml</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/go.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">augenbrauen former for face</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/falmango.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Original flamingo razor blades</span>
          </div>
          </v-col>




          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/kol.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">KOLAGRA Whitening Roll On 2X1- Elder Rose 60ML White</span>
          </div>
          </v-col>




          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/hopo.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Hydrocolloid spots for acne and cold sores Skin Tone Pill Sticker</span>
          </div>
          </v-col>




          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/clary.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Clary Leave In Cream</span>
          </div>
          </v-col>




          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/ry.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Clary Fresh Scalp 300 ml</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/sham.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Clary Shampoo</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/mask.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Clary hair mask 300 ml</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/qtn.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Qualita Cotton Pads Silver 100 Pcs</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/remover.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Starville Micellar Water 100 ml</span>
          </div>
          </v-col>



          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/sta.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Star Ville TEA-TREE OIL&VITAMIN E FACE MASK 1SHEET</span>
          </div>
          </v-col>


          <v-col class="boxProduct" cols="6" sm="6" md="4" lg="3">
            <v-img
            style="height: 290px"
            cover
            src="/public/imges/gg.jpg"
          ></v-img>
          <div>
            <span style="color: #dc979c;font-weight: bold">Thermal Winter Gloves</span>
          </div>
          </v-col>






        </v-row>
        <row>
          <v-col cols="12">
            <div class="text-center" style="display: flex;align-items: center">
              <h1>  <v-icon>mdi-cart</v-icon></h1>
              <p>We are working on adding the rest of the products and working on adding an update to the site😊😊</p>
            </div>
            <div>
              <h1>  <v-icon>mdi-instgram</v-icon></h1>
            </div>
          </v-col>
        </row>
      </v-container>
    </div>
  </div>
</template>

<style>
.products-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.product-card {
  width: 100%;
  max-width: 350px;
  margin: 0 auto;
  border-radius: 10px;
}

.product-info {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.product-title {
  text-align: start;
  color: #dc979c;
  font-size: 20px;
}

.product-price {
  font-size: 18px;
  color: #dc979c;
}

.product-card:hover {
  transform: scale(1.05);
  transition: 1.5s;
}

.product-info {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.product-title {
  text-align: start;
  color: #dc979c;
  font-size: 20px;
}

.product-price {
  font-size: 18px;
  color: #dc979c;
}
.boxProduct {
  cursor: pointer;
}
.boxProduct:hover {
  transform: scale(1.05);
  transition: 1.5s;
}
.img {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  border-bottom-left-radius:4px;
  border-bottom-right-radius:4px;
}
.img1 {
  visibility: hidden;
}


@media (max-width: 768px) {
  .products-row {
    flex-direction: column;
  }
  .img1 {
    visibility: visible;
  }
}

@media (max-width: 768px) {
  .products-row {
    flex-direction: column;
  }
}
</style>

<script>
export default {
  data() {
    return {
      showLogo: true,
    };
  },
  mounted() {
    setTimeout(() => {
      this.showLogo = false;
    }, 1000);
  },
};
</script>
