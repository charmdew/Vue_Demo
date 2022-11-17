<template>
  <div>   
    <div class="container" style="height:700px; width:1500px">
      <div class="container" style="height:60%; background-size : cover; background-image: url('https://media.architecturaldigest.com/photos/571e97c5741fcddb16b559c9/2:1/w_5127,h_2563,c_limit/modernist-decor-inspiration-01.jpg');" >
        <div class="col" style="opacity:1">
          어떤 집?
        </div>
        <div class="row">
          <div class="col">
            <b-button class="mr-2 mb-2" variant="success">
              실거래가 조회
            </b-button>
          </div>
        </div>
      </div>
      <b-row class="mt-5" style="height:40%">
          <b-col>
            <div class="border-bottom border-primary">
              <b-row>
                <b-col cols="11">
                  <h3>부동산 뉴스</h3>
                </b-col>
                <b-col cols="1">
                  <span class="font-icon-wrapper">
                    <i class="pe-7s-right-arrow"></i>
                  </span>
                </b-col>
              </b-row>
            </div>
            <b-table striped hover :items="items" thead-class="d-none"></b-table>
          </b-col>
          <b-col>
            <div class="border-bottom border-primary">
              <b-row>
                <b-col cols="11">
                  <h3>공지사항</h3>
                </b-col>
                <b-col cols="1">
                  <span class="font-icon-wrapper">
                    <i class="pe-7s-right-arrow"></i>
                  </span>
                </b-col>
              </b-row>
            </div>
            <b-table striped hover :items="items" thead-class="d-none"></b-table>
          </b-col>
        </b-row>
    </div>
        <!-- <div>

          <b-row>
            <b-col cols="5">
              <b-button class="mr-2 mb-2" variant="success">
                실거래가 조회
              </b-button>
            </b-col>
          </b-row>
        </div>         -->

        <!-- <div class="col">
          <div class="row">
            <b-button class="mr-2 mb-2" variant="success">
              실거래가 조회
            </b-button>
          </div>
        </div> -->

        
        
      </div>   
</template>

<script>
export default {
  name: 'Homes',

  data() {
    return {
      items: [
        // 제목, 작성자만 보여주기
        {
          "title": "메인 화면 만들었어용",
          "user_id": "싸피"
        },
        {
          "title": "메인 화면 만들었어용",
          "user_id": "싸피"
        },
        {
          "title": "메인 화면 만들었어용",
          "user_id": "싸피"
        },
      ]
      
    };
  },

  mounted() {
    
  },

  methods: {
    
  },
};
</script>

<style lang="scss" scoped>

</style>