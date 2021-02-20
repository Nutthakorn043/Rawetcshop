<template>

  <div class="container">
     <button class="btn btn-dark btn-lg float-right" type="submit">{{nut1+nut2+nut3+nut4+nut5+nut6+nut7+nut8+nut9+nut10+nut11+nut12}}<b-icon icon="cart3"></b-icon></button> 
     <!-- {{nut1.nut2.nut3.nut4.nut5.nut6.nut7.nut8.nut9.nut10.nut11.nut12}} -->
    
    <h1>NEW ARRIVALS</h1> 
<hr />
    <b-card-group deck>
      
       <b-card
          id:1
          title="Nike Heritage86"
          img-src="https://shorturl.asia/JIq5e"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
            ฿550
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI1">
                Add<b-badge variant="light"
                  >{{ nut1}}
                  <span class="sr-only">unread messges</span></b-badge
>
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem1">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
            <b-card
          id:2
          title="Nike Liverpool86"
          img-src="https://shorturl.asia/ZivLC"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
            ฿950
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI2">
                Add<b-badge variant="light"
                  >{{ nut2}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem2">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
          <b-card
          id:3
          title="Paris Saint-7"
          img-src="https://shorturl.asia/8U9jr"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
            ฿850
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI3">
                Add<b-badge variant="light"
                  >{{ nut3}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem3">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
         <b-card
          id:4
          title="Jordan Jumpman"
          img-src="https://shorturl.asia/FJZMt"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
            ฿1850
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI4">
                Add<b-badge variant="light"
                  >{{ nut4}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem4">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
        
    </b-card-group>
    <h1></h1>
    <hr />
    <h1>SHOP ALL</h1>
    <hr />
    <b-card-group deck>
          <b-card
          id:5
          title="Jordan Dri-FIT"
          img-src="https://shorturl.asia/fpx6U"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
           ฿690
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI5">
                Add<b-badge variant="light"
                  >{{ nut5}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem5">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
         <b-card
          id:6
          title="Nike Swoosh"
          img-src="https://shorturl.asia/0iTN7"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
           ฿590
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI6">
                Add<b-badge variant="light"
                  >{{ nut6}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem6">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
        
      
        <b-card
          id:7
          title="Nike Advantage"
          img-src="https://shorturl.asia/UWLIF"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
          ฿850
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI7">
                Add<b-badge variant="light"
                  >{{ nut7}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem7">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
     
          <b-card
          id:8
          title="Nike ACG"
          img-src="https://shorturl.asia/ovj1k"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
           ฿990
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI8">
                Add<b-badge variant="light"
                  >{{ nut8}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem8">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
    
    </b-card-group>
<hr />
    <b-card-group deck>
    <b-card
          id:9
          title="NikeCourt"
          img-src="https://shorturl.asia/fpx6U"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
           ฿900
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI9">
                Add<b-badge variant="light"
                  >{{ nut9}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem9">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>

          <b-card
          id:10
          title="Nike Heritage86"
          img-src="https://shorturl.asia/zHykl"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
           ฿896
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI10">
                Add<b-badge variant="light"
                  >{{ nut10}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem10">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>

          <b-card
          id:11
          title="Nike Tailwind Fast"
          img-src="https://shorturl.asia/MbG3U"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
            ฿850
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI11">
                Add<b-badge variant="light"
                  >{{ nut11}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem11">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>

      <b-card
          id:12
          title="Nike Pro Rayguns"
          img-src="https://shorturl.asia/3Okcv"
          img-alt="Image"
          style="max-width: 15rem;"
          img-top
        >
          <b-card-text>
          ฿959
          </b-card-text>
          <template #footer>
            <small class="text-muted">
              <b-button variant="outline-dark" @click="nutI12">
                Add<b-badge variant="light"
                  >{{ nut12}}<span class="sr-only">unread messges</span></b-badge
                >
              </b-button>
              <span class="sr-only">unread messges</span></b-badge
                >
              <b-button variant="outline-dark" @click="CancelItem12">
                Cancel
              </b-button></small
            >
          </template>
        </b-card>
    </b-card-group>
    <div>
    
    <hr />
  <b-button variant="outline-dark" id="show-btn" @click="$bvModal.show('bv-modal-example')">กดยืนยันการสั่งซื้อ</b-button>

  <b-modal  size="lg" id="bv-modal-example" hide-footer>
    <template #modal-title>
       Rawetc Shop14
    </template>
    <div class="d-block text-center">
       <h4>รายการสินค้า
      <hr />
      <header class="d-flex flex-column flex-md-row align-items-mide p-3 px-md-4 mb-3 bg-body border-bottom shadow-sm">
        <div v-if="nut1 >= 1">
    <img src="https://shorturl.asia/JIq5e" width="60"  height=“60”>
    <p1> x{{ nut1 }} </p1>
  </div>
          <div v-if="nut2 >= 1">
    <img src="https://shorturl.asia/ZivLC" width="60"  height=“60”>
    <p1> x{{ nut2 }} </p1>
  </div>
         <div v-if="nut3 >= 1">
    <img src="https://shorturl.asia/8U9jr" width="60"  height=“60”>
    <p1> x{{ nut3 }} </p1>
  </div>
         <div v-if="nut4 >= 1">
    <img src="https://shorturl.asia/FJZMt" width="60"  height=“60”>
    <p1> x{{ nut4 }} </p1>
  </div>
         <div v-if="nut5 >= 1">
    <img src="https://shorturl.asia/fpx6U" width="60"  height=“60”>
    <p1> x{{nut5 }} </p1>
  </div>
         <div v-if="nut6 >= 1">
    <img src="https://shorturl.asia/0iTN7" width="60"  height=“60”>
    <p1> x{{ nut6 }} </p1>
  </div>
         <div v-if="nut7 >= 1">
    <img src="https://shorturl.asia/UWLIF" width="60"  height=“60”>
    <p1> x{{ nut7 }} </p1>
  </div>
         <div v-if="buy8 >= 1">
    <img src="https://shorturl.asia/ovj1k" width="60"  height=“60”>
    <p1> x{{ buy8 }} </p1>
  </div>
         <div v-if="nut9 >= 1">
    <img src="https://shorturl.asia/fpx6U" width="60"  height=“60”>
    <p1> x{{ nut9 }} </p1>
  </div>
         <div v-if="nut10 >= 1">
    <img src="https://shorturl.asia/zHykl" width="60"  height=“60”>
    <p1> x{{ nut10 }} </p1>
  </div>
         <div v-if="nut11 >= 1">
    <img src="https://shorturl.asia/MbG3U" width="60"  height=“60”>
    <p1> x{{ nut11 }} </p1>
  </div>
         <div v-if="nut12 >= 1">
    <img src="https://shorturl.asia/3Okcv" width="60"  height=“60”>
    <p1> x{{ nut12 }} </p1>
  </div>
  </header>
    </h4>
    <h1>ราคารวม = {{ nut13 }} บาท</h1>

    <b-button variant="outline-success" @click="CancelAllItem" v-on:click="say">ชำระเงิน</b-button>

    <b-button variant="outline-danger" @click="CancelAllItem">
      ยกเลิกการสั่งซื้อ
    </b-button>
    </div>
    
  </b-modal>
 <hr />
</div>
       
    <div>
     </div>
  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  data() {
    return {
      nut1: 0,
      nut2: 0,
      nut3: 0,
      nut4: 0,
      nut5: 0,
      nut6: 0,
      nut7: 0,
      nut8: 0,
      nut9: 0,
      nut10: 0,
      nut11: 0,
      nut12: 0,
      nut13: 0
    };
  },
  methods: {
    say: function() {
      alert(
        "ท่านได้ชำระเงินรายการสินค้านี้แล้ว ขอบคุณที่ใช้บริการ"
      );
    },
    nutI1() {
      this.nut1++;
      this.nut13 += 550;
    },
    nutI2() {
      this.nut2++;
      this.nut13 += 950;
    },
    nutI3() {
      this.nut3++;
      this.nut13 += 850;
    },
    nutI4() {
      this.nut4++;
      this.nut13 += 1850;
    },
   nutI5() {
      this.nut5++;
      this.but13 += 690;
    },
    nutI6() {
      this.nut6++;
      this.nut13 += 590;
    },
      nutI7() {
      this.nut7++;
      this.nut13 += 850;
    },
      nutI8() {
      this.nut8++;
      this.nut13 += 990;
    },
      nutI9() {
      this.nut9++;
      this.nut13 += 900;
    },
      nutI10() {
      this.nut10++;
      this.nut13 += 896;
    },
      nutI11() {
      this.nut11++;
      this.nut13 += 850;
    },
      nutI12() {
      this.nut12++;
      this.nut13 += 950;
    },
    CancelItem1() {
      if (this.nut1 > 0) {
        this.nut1--;
        this.nut13 -= 550;
      }
    },
    CancelItem2() {
      if (this.nut2 > 0) {
        this.nut2--;
        this.nut13 -= 950;
      }
    },
    CancelItem3() {
      if (this.nut3 > 0) {
        this.nut3--;
        this.nut13 -= 850;
      }
    },
    CancelItem4() {
      if (this.nut4 > 0) {
        this.nut4--;
        this.nut13 -= 1850;
      }
    },
    CancelItem5() {
      if (this.nut5 > 0) {
        this.nut5--;
        this.nut13 -= 690;
      }
    },
    CancelItem6() {
      if (this.nut6 > 0) {
        this.nut6--;
        this.nut13 -= 590;
      }
    },
        CancelItem7() {
      if (this.nut7 > 0) {
        this.nut7--;
        this.nut13 -= 850;
      }
    },
        CancelItem8() {
      if (this.nut8 > 0) {
        this.nut8--;
        this.nut13 -= 990;
      }
    },
        CancelItem9() {
      if (this.nut9 > 0) {
        this.nut9--;
        this.nut13 -= 900;
      }
    },
        CancelItem10() {
      if (this.nut10 > 0) {
        this.nut10--;
        this.nut13 -= 896;
      }
    },
        CancelItem11() {
      if (this.nut11 > 0) {
        this.nut11--;
        this.nut13 -= 850;
      }
    },
        CancelItem12() {
      if (this.nut12 > 0) {
        this.nut12--;
        this.nut13 -= 959;
      }
    },

    CancelAllItem() {
      if (this.nut13 > 0) {
        (this.nut1 = 0),
          (this.nut2 = 0),
          (this.nut3 = 0),
          (this.nut4 = 0),
          (this.nut5 = 0),
          (this.nut6 = 0),
          (this.nut7 = 0);
          (this.nut8 = 0);
          (this.nut9 = 0);
          (this.nut10 = 0);
          (this.nut11 = 0);
          (this.nut12 = 0);
          (this.nut13 = 0);
      }
    }
  }
};
</script>
