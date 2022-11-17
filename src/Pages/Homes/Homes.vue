<template>
    <div>
        <div class="container" style="height: 700px">
            <div
                class="container"
                style="
                    position: relative;
                    height: 60%;
                    opacity: 0.9;
                    background-image: url('https://images.pexels.com/photos/3209045/pexels-photo-3209045.jpeg');
                    background-position: center;
                    background-size: cover;
                "
            >
                <h1
                    style="
                        position: absolute;
                        top: 45%;
                        left: 17%;
                        font-weight: 900;
                        color: black;
                        font-size: 5vh;
                    "
                >
                    지금 바로 아파트 매매 정보를 확인해 보세요!
                </h1>
                <div
                    style="position: absolute; top: 61%; left: 37%; width: 20%"
                >
                    <b-button
                        block
                        class="mr-2 mb-2"
                        variant="primary"
                        size="lg"
                        style="
                            background-color: #336633;
                            border: 1px solid #336633;
                        "
                    >
                        실거래가 조회
                    </b-button>
                </div>
            </div>
            <b-row class="mt-5" style="height: 40%">
                <b-col>
                    <div
                        class="border-bottom border-primary"
                        style="padding-right: 20px"
                    >
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
                    <b-table
                        striped
                        hover
                        :items="items"
                        thead-class="d-none"
                    ></b-table>
                </b-col>
                <b-col>
                    <div
                        class="border-bottom border-primary"
                        style="padding-right: 20px"
                    >
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
                    <b-table
                        striped
                        hover
                        :items="items"
                        thead-class="d-none"
                    ></b-table>
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
    name: "Homes",

    data() {
        return {
            items: [
                // 제목, 작성자만 보여주기
                {
                    title: "메인 화면 만들었어용",
                    user_id: "싸피",
                },
                {
                    title: "메인 화면 만들었어용",
                    user_id: "싸피",
                },
                {
                    title: "메인 화면 만들었어용",
                    user_id: "싸피",
                },
            ],
        };
    },

    mounted() {},

    methods: {},
};
</script>

<style lang="css" scoped>
div {
    /* border: 3px solid;
    border-color: red !important; */
}
</style>
