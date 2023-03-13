<template>
    <div class="homeBackground">
        <div class="coverImg">
            <div class="logoPosition">
                <img class="logo" src="../assets/網頁刊頭-LOGO.png" alt="">
                <div class="logoImg">
                    <img class="dMdNone" src="../assets/網頁刊頭-文字.png" alt="">
                    <img class="dXlNone" src="../assets/Group1517.png" alt="">
                </div>

            </div>
        </div>

        <!-- 申請按鈕&輪播圖 -->
        <div class="main maxWidth">
            <div class="col-12 row mainContain">
                <div class="col-xl-6 beCenter mainContainWrap">
                    <div>
                        <img class="beCenter" src="../assets/Group1518.png" alt="">
                        <h5 class="mainContainText">
                            第一次有了孕期反應，第一次聽見心跳
                            <br>
                            第一次感覺到有一個小小生命在身體裡茁壯
                            <br>
                            有了寶寶，更要好好照顧自己
                            <br>
                            讓我們和妳一起愛護寶寶，呵護自己
                        </h5>
                        <div class="mainContainBtn">
                            <button class="mainContainBtnStyle">免費申請試喝</button>
                        </div>
                    </div>
                </div>

                <!-- 產品輪播 -->
                <div class="col-xl-6
                                col-md-8  p-0">
                    <div id="carouselExampleIndicators" class="carousel slide col-xl-11" data-bs-ride="carousel">
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="../assets/雙盒組15_810x535.png" class="d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="../assets/雙盒組15_810x535.png" class="d-block w-100" alt="...">
                            </div>
                            <div class="carousel-item">
                                <img src="../assets/雙盒組15_810x535.png" class="d-block w-100" alt="...">
                            </div>
                        </div>
                        <div class="carousel-indicators">
                            <button type="button"
                                style="border-radius: 50%; width: 15px;height: 15px;background-color: white;"
                                data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
                                aria-current="true" aria-label="Slide 1"></button>
                            <button type="button"
                                style="border-radius: 50%; width: 15px;height: 15px;background-color: white;"
                                data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                                aria-label="Slide 2"></button>
                            <button type="button"
                                style="border-radius: 50%; width: 15px;height: 15px;background-color: white;"
                                data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                                aria-label="Slide 3"></button>
                        </div>
                    </div>


                </div>
            </div>
        </div>

        <!-- 申請辦法 -->
        <div class="bigTitle maxWidth">
            <div style="background-color:#CC6D00;width: 40% ;height: 5px;"></div>
            <h2 class="m-auto" style="color:#CC6D00;font-size:#CC6D00;white-space: nowrap;">申請辦法</h2>
            <div style="background-color:#CC6D00;width: 40% ;height: 5px;"></div>
        </div>

        <!-- <576px 時不顯現這一區的申請辦法-->
        <div class="dSmNone">
            <!-- 1 -->
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="col-6 applyContainText" style="white-space: nowrap;">
                        <p>
                            <span style="color: #BF0505">*</span>
                            <span style="color: #2FAFAE">活動對象</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">懷孕中的孕媽咪</span>
                        </p>
                    </div>
                    <div class="col-6 applyContainText" style="white-space: nowrap;">
                        <p class="applyContainTextRight" style="padding-left: 9px;">
                            <span style="width: 9px;"></span>
                            <span style="color: #2FAFAE ">活動費用</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">免費</span>
                        </p>
                    </div>

                </div>
            </div>
            <!-- 2 -->
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="col-6 applyContainText" style="white-space: nowrap;">
                        <p style="padding-left: 9px;">
                            <span style="color: #2FAFAE">活動名額</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">每月限量30名</span>
                        </p>
                    </div>
                    <div class="col-6">
                        <div class="d-flex applyContainText">
                            <p class="applyContainTextRight" style="white-space: nowrap;">
                                <span style="width: 9px;"></span>
                                <span style="color: #2FAFAE">申請時間</span>
                                <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            </p>

                            <p style="color: #010101">每月1號起-額滿為止，依照填單完成順序安排出貨，申請截止日至當月25日前，或額滿為止。</p>
                        </div>
                    </div>

                </div>
            </div>
            <!-- 3 -->
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="col-12 applyContainText">
                        <p style="white-space: nowrap;">
                            <span style="color: #BF0505">*</span>
                            <span style="color: #2FAFAE">申請辦法</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                        </p>
                        <ul style="color: #010101;list-style-type:decimal;margin-bottom: 0px;
                                                padding-left: 12px;">
                            <li>填寫Google申請表單，提供欲申請的媽咪本人基本資料，同步上傳媽媽手冊封面 (姓名須清楚)，與預產期之照片。</li>
                            <li>待確認資料無誤後，初饌就會盡快寄出「初饌淬魚精常溫體驗包」。</li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>

        <!-- >576px 時出現這一區的申請辦法-->
        <div class="dSmNone dSmYes">
            <!-- 1 -->
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="applyContainText" style="white-space: nowrap;">
                        <p>
                            <span style="color: #BF0505">*</span>
                            <span style="color: #2FAFAE">活動對象</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">懷孕中的孕媽咪</span>
                        </p>
                    </div>
                </div>
            </div>
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="applyContainText" style="white-space: nowrap;">
                        <p style="padding-left: 9px;">
                            <span style="width: 9px;"></span>
                            <span style="color: #2FAFAE ">活動費用</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">免費</span>
                        </p>
                    </div>
                </div>
            </div>
            <!-- 2 -->
            <div class="applyContain maxWidth">
                <div class="col-12 row">
                    <div class="applyContainText" style="white-space: nowrap;">
                        <p style="padding-left: 9px;">
                            <span style="color: #2FAFAE">活動名額</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            <span style="color: #010101">每月限量30名</span>
                        </p>
                    </div>
                </div>
            </div>
            <div class="applyContainNormal maxWidth">
                <div class="col-12 row">
                    <div>
                        <div class="d-flex applyContainText">
                            <p style="white-space: nowrap;">
                                <span style="width: 9px;"></span>
                                <span style="color: #2FAFAE">申請時間</span>
                                <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                            </p>

                            <p style="color: #010101">每月1號起-額滿為止，依照填單完成順序安排出貨，申請截止日至當月25日前，或額滿為止。</p>
                        </div>
                    </div>

                </div>
            </div>
            <!-- 3 -->
            <div class="applyContainBig maxWidth">
                <div class="col-12 row">
                    <div class="col-12 applyContainText">
                        <p style="white-space: nowrap;">
                            <span style="color: #BF0505">*</span>
                            <span style="color: #2FAFAE">申請辦法</span>
                            <span class="h3 mx-2" style="color: #2FAFAE">/</span>
                        </p>
                        <ul style="color: #010101;list-style-type:decimal;margin-bottom: 0px;
                                                padding-left: 12px;">
                            <li>填寫Google申請表單，提供欲申請的媽咪本人基本資料，同步上傳媽媽手冊封面 (姓名須清楚)，與預產期之照片。</li>
                            <li>待確認資料無誤後，初饌就會盡快寄出「初饌淬魚精常溫體驗包」。</li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
        <div class="dSmNone">
            <div class="applyContainPoint maxWidth mx-auto">
                <div style="color: #BF0505;font-weight: bold;font-size: 15px;">*限本人申請，每人限申請乙次乙包。 *試用體驗組為獨立寄送，不可與官網其他訂單合併出貨。
                </div>
            </div>
        </div>
        <div class="dSmNone dSmYes">
            <div class="maxWidth mx-auto px-2">
                <p style="color: #BF0505;font-weight: bold;font-size: 15px;">*限本人申請，每人限申請乙次乙包。</p>
                <p style="color: #BF0505;font-weight: bold;font-size: 15px;">*試用體驗組為獨立寄送，不可與官網其他訂單合併出貨。
                </p>
            </div>
        </div>


        <!-- 產品介紹區 -->

        <div class="maxWidth mx-auto" style="max-height: 657.92px">
            <img class="productImg" src="../assets/Group1521.png" alt="">

            <div class="productLogo">
                <div class="row productLogoPosition">
                    <img class="productLogoImg" src="../assets/Group1520.png" alt="">
                    <img class="productLogoImg" src="../assets/Group1522.png" alt="">
                </div>
            </div>
            <div class="productContainBg">
                <ul class="productContainText">
                    <li>100%無水添加，完整魚淬精華</li>
                    <li>快速補充蛋白質、膠原蛋白、胺基酸…等身體所需</li>
                    <li>孕期關鍵營養補充</li>
                    <li>天然花蓮湧泉養殖，純淨健康好安心</li>
                    <li>營養師推薦！漁業署認證營養豐富魚種淬取</li>
                </ul>
            </div>

        </div>

        <!-- 聯絡我們 -->
        <div class="bigTitle maxWidth contactTitlePosition">
            <div style="background-color:#CC6D00;width: 40% ;height: 5px;"></div>
            <h2 class="m-auto" style="color:#CC6D00;font-size:#CC6D00;white-space: nowrap;">聯絡我們</h2>
            <div style="background-color:#CC6D00;width: 40% ;height: 5px;"></div>
        </div>
        <p class="contactThank">感謝您對百森的支持與鼓勵，請不吝將您的疑問或意見告知，我們將依據您填寫的資料，儘快為您處理。</p>
        <!-- 聯絡表單 -->
        <div class="maxWidth contactForm">
            <form class="col-12 row">
                <div class="col-xl-4 col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">姓名</span>
                    </label>
                    <input placeholder="請輸入姓名" type="text" class="form-control" style="border:1px solid #2FAFAE;" required>
                </div>
                <div class="col-xl-4 col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">電話</span>
                    </label>
                    <input placeholder="請輸入電話" type="tel" pattern="[0-9]{10}" class="form-control" style="border:1px solid #2FAFAE;" required>
                </div>
                <div class="col-xl-4 col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">訂單編號</span>
                    </label>
                    <input placeholder="請輸入訂單編號" type="text" class="form-control" style="border:1px solid #2FAFAE;"
                        required>
                </div>
                <div class="col-xl-6 col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">電子郵件</span>
                    </label>
                    <input placeholder="請輸入電子郵件" type="email" class="form-control" style="border:1px solid #2FAFAE;"
                        required>
                </div>

                <div class="col-xl-6 col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">詢問項目</span>
                    </label>
                    <select class="form-select" style="border:1px solid #2FAFAE;" required>
                        <option value="" selected disabled hidden>請輸入詢問項目</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select>
                </div>
                <div class="col-12">
                    <label class="form-label contactFormLabel">
                        <span style="color: #BF0505">*</span>
                        <span style="color: #2FAFAE">詢問/意見內容</span>
                    </label>
                    <textarea class="form-control" style="height: 100px;border:1px solid #2FAFAE;" required></textarea>
                    <div class="valid-feedback">
                        ok!
                    </div>
                </div>

                <div class="col-12 d-flex justify-content-center" style="margin-top:53px ;">
                    <button class="contactFormBtn" type="submit" style="">確認送出</button>
                </div>
            </form>
        </div>

        <!-- footer -->
        <div class="contactUsBg">
            <div class="col-12 row contactUsContain ">
                <img class="contactUsLogo" src="../assets/網頁刊頭-LOGO.png" alt="">
                <p class="col-8 contactUsLogoText">懷揣純淨初心．淬鍊滋養珍饌</p>
            </div>
            <div class="maxWidth contactUsMethod">
                <div class="contactUsMethodTitle">
                    <img class="contactUsMethodImg" src="../assets/Group101.png" alt="">
                    <p class="contactUsMethodText">新北市板橋區三民路二段37號22樓之1</p>
                </div>
                <div class="d-flex flex-nowrap mx-auto">
                    <div class="col-12 contactUsMethodTitle">
                        <img class="contactUsMethodImg" src="../assets/Group102.png" alt="">
                        <p class="contactUsMethodText">(02)2953-0799</p>
                        <img class="contactUsMethodImg" src="../assets/Group103.png" alt="">
                        <p class="contactUsMethodText">周一至周五 9:30-18:00</p>
                    </div>

                </div>

            </div>
        </div>
        <footer>
            <div class="copyrightBg">
                <p style="color: #AD7B43;">Copyright @ 2021 CHU ZHUAN INC. All Rights Reserved.</p>
            </div>
        </footer>


    </div>
</template>

<script >
export default {
}
</script>


<style scoped>
/* 大量使用 */
p {
    margin-bottom: 0px;
}

.beCenter {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0px auto;
    padding: 0px auto;
}

/* 在sm以前都不會顯示 */
.dSmYes {
    display: none;
}

.maxWidth {
    max-width: 1000px;
}

/* header */
.homeBackground {
    background-image: url("../assets/MaskGroup 20.png");
    background-size: cover;
    max-width: 100%;
    max-height: 100%;
}

.coverImg {
    background-image: url("../assets/網頁刊頭-無字.png");
    background-size: cover;
    background-position: center center;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding-top: 3%;
    width: 100%;
    height: 40vh;
}

.logoPosition {
    display: flex;
    position: relative;
    margin-top: -20px;
    margin-left: -700px;
}

.logo {
    width: 117px;
    height: 29px;
    margin-right: 29px
}

.logoImg {
    display: flex;
    flex-flow: column;
    max-width: 100%;
    align-items: start
}

/* 申請button&輪播圖 */
.main {
    display: flex;
    justify-content: center;
    margin: 0px auto 75px auto;
}

.mainContain {
    display: flex;
    flex-wrap: nowrap;
    align-items: flex-end;
    justify-content: center;
    padding: 100px 0 0 0;
}

.mainContainText {
    font-size: 20px;
    font-weight: bold;
    white-space: nowrap;
    line-height: 1.4;
    text-align: center;
    margin: 7px auto 26px auto;
}

.mainContainBtn {
    display: flex;
    justify-content: center;
}

.mainContainBtnStyle {
    font-size: 1.5rem;
    font-weight: bold;
    color: #FFF7F3;
    background-color: #F88A8A;
    box-shadow: 0px 3px 10px #772405;
    padding: 12px 42px;
    margin: 6px auto 0 auto;
    text-align: center;
    border-radius: 78px;
}

/* 申請辦法 */
.bigTitle {
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 95px auto 47px auto;
    padding: 0px auto;
}

.applyContain {
    display: flex;
    margin: 0 auto 7px auto;
    height: 124px;
    align-items: center;
    background-color: #ffffff;
    border-radius: 20px;
}

.applyContainText {
    max-width: 100%;
    padding-left: 29px;
    display: flex;
    align-items: center;
    font-size: 18px;
    font-weight: bold;
}

.applyContainPoint {
    display: flex;
    justify-content: end;

}

/* 產品介紹 */
.productImg {
    max-width: 538.93px;
    position: relative;
    top: 20px;
    right: 50px;
    z-index: 2;
}

.productLogo {
    display: flex;
    justify-content: end;
    margin-right: 79px;
    margin-bottom: 27.55px;
}

.productLogoPosition {
    display: flex;
    position: relative;
    top: -500px;
    width: 459px;
}

.productContainBg {
    background-image: url("../assets/Group1516.png");
    height: 261.45px;
    position: relative;
    top: -500px;
}

.productContainText {
    color: #FFFFFF;
    text-shadow: 0px 3px 3px #47270680;
    font-weight: bold;
    font-size: 20px;
    float: right;
    margin: 42px 79px;
}

/* 聯絡表單 */
.contactThank {
    color: #747474;
    text-align: center;
    margin-top: 53px
}

.contactForm {
    margin: 0px auto;
    padding-top: 0;
    position: relative;
    top: -200px;
}

.contactFormLabel {
    font-size: 20px;
    font-weight: bold;
    white-space: nowrap;
    margin-top: 32px;
}

.contactFormBtn {
    background-color: #2FAFAE;
    color: #FFFFFF;
    padding: 4px 94px;
}

/* footer */
.contactUsBg {
    background-color: #F8E8D5;
    max-width: 100%;
    height: 200px;
    margin: 0px auto;
    padding-top: 65px;
    display: flex;
    flex-wrap: wrap;
}

.contactUsContain {
    height: 35px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-bottom: 42px;
}

.contactUsLogo {
    width: 131px;
    height: 33px;
    margin-right: 29px;
}

.contactUsLogoText {
    color: #AD7B43;
    font-size: 18px;
    font-weight: bold;
    width: auto;
    padding-top: 5px;
}

.contactUsMethod {
    height: 50px;
    margin: 0px auto;
    display: flex;
    flex-wrap: wrap;
}

.contactUsMethodTitle {
    display: flex;
    flex-wrap: nowrap;
    justify-content: center;
    margin: auto;
}

.contactUsMethodImg {
    width: 16px;
    height: 16px;
    margin: 5px;
}

.contactUsMethodText {
    color: #AD7B43;
    font-size: 16px
}

/* copyright */
.copyrightBg {
    max-width: 100%;
    height: 57px;
    background-color: #EDD2B3;
    display: flex;
    align-items: center;
    justify-content: center;
}




@media screen and (max-width: 1200px) {
    .maxWidth {
        max-width: 750px;
    }

    /* 設定在<1200px時消失 */
    .dXlNone {
        display: none;
    }

    .coverImg {
        background-image: url("../assets/網頁刊頭-無字.png");
        display: flex;
        align-items: center;
        flex-direction: column;
        padding-top: 3%;
        width: 100%;
    }

    .logoPosition {
        display: flex;
        position: relative;
        top: 50px;
        left: 50px;
        flex-direction: column;
    }

    .logo {
        width: 150px;
        height: 45px;
        margin-right: 29px;
        margin-bottom: 10px;
    }

    .logoImg {
        display: flex;
        flex-flow: column;
        max-width: 100%;
        align-items: start
    }

    /* 申請button&輪播圖 */
    .mainContain {
        flex-wrap: wrap;
        padding: 20px 0 0 0;
    }

    .mainContainWrap {
        width: 100%;
        margin-bottom: 30px;
    }

    /* 申請辦法 */
    .bigTitle {
        margin: 0px auto 30px auto;
        width: 90%;
    }

    .applyContain {
        height: 80px;
        border-radius: 10px;
    }

    .applyContainText {
        font-size: 15px;
    }

    .applyContainPoint {
        font-size: 15px;
    }

    /* 產品介紹 */
    .productImg {
        max-width: 380px;
        top: 30px;
        right: 30px;
    }

    .productLogoImg {
        width: 300px;
    }

    .productLogoPosition {
        top: -400px;
        width: 459px;
        display: flex;
        justify-content: center;
    }

    .productContainBg {
        height: 220px;
        top: -400px;
    }

    .productContainText {
        margin: 42px 15px;
    }

    /* 聯絡表單 */
    .contactTitlePosition {
        position: relative;
        top: -300px;
        display: flex;
        justify-content: center;
        width: 750px;
    }

    .contactThank {
        position: relative;
        top: -325px;
        margin: 0 auto;
        width: 90%;
    }

    .contactForm {
        top: -300px;
        margin: 0px auto;
    }

    .contactFormLabel {
        font-size: 20px;
        font-weight: bold;
        white-space: nowrap;
        margin-top: 16px;
    }

    /* footer */
    .contactUsBg {
        position: relative;
        top: -200px;
    }

    .contactUsContain {
        position: relative;
        top: -30px;
    }

    .contactUsMethod {
        position: relative;
        top: -35px;
    }

    /* copyright */
    .copyrightBg {
        margin-top: -200px;
    }
}

@media screen and (max-width: 768px) {
    .maxWidth {
        max-width: 550px;
    }

    .dMdNone {
        display: none;
    }

    .coverImg {
        background-image: url();
        background-color: #EDD2B3;
        display: flex;
        align-items: center;
        flex-direction: column;
        width: 100%;
        height: 20vh;
    }

    .logoPosition {
        position: relative;
        left: 60%;
        top: 25px;
    }

    .logo {
        width: 200px;
        height: 60px;
    }

    /* 申請button&輪播圖 */

    .mainContainText {
        font-size: 1.6rem;
    }

    /* 申請辦法 */


    /* 產品介紹 */
    .productImg {
        max-width: 200px;
        top: -10px;
        left: 0px;
    }

    .productLogoPosition {
        top: -200px;
        width: 459px;
        display: flex;
        justify-content: end;
        z-index: 2;
    }

    .productContainBg {
        height: 200px;
        top: -225px;
    }

    /* 聯絡表單 */
    .contactTitlePosition {
        position: relative;
        top: -200px;
        display: flex;
        justify-content: center;
        width: 90%;
    }

    .contactThank {
        margin: 30px auto;
        position: relative;
        top: -225px;
        width: 70%;
    }

    .contactForm {
        top: -250px;
        margin: 0px auto;
    }

    .contactFormLabel {
        font-size: 20px;
        font-weight: bold;
        white-space: nowrap;
        margin-top: 16px;
    }

    /* footer */
    .contactUsBg {
        position: relative;
        top: -200px;
    }

    .contactUsContain {
        position: relative;
        top: -30px;
    }

    .contactUsMethod {
        position: relative;
        top: -35px;
    }

    /* copyright */
    .copyrightBg {
        margin-top: -200px;
    }
}

@media screen and (max-width: 576px) {
    .maxWidth {
        max-width: 350px;
    }

    .dSmNone {
        display: none;
    }

    .dSmYes {
        display: block
    }

    .logoPosition {
        top: 50px;
        left: 200px;
    }

    .logo {
        margin-left: 200px;
        width: 200px;
        height: 60px;
    }

    /* 申請button&輪播圖 */

    .mainContainText {
        font-size: 1.2rem;
    }

    /* 申請辦法 */

    .applyContainNormal {
        display: flex;
        margin: 0 auto 7px auto;
        align-items: center;
        background-color: #ffffff;
        border-radius: 20px;
        height: 150px;
    }

    .applyContainBig {
        display: flex;
        margin: 0 auto 7px auto;
        align-items: center;
        background-color: #ffffff;
        border-radius: 20px;
        height: 225px;
    }

    /* 產品介紹 */
    .productImg {
        max-width: 200px;
        top: 0px;
        left: 75px;
    }

    .productLogoImg {
        width: 200px;
    }

    .productLogoPosition {
        top: 20px;
        left: 0px;
        width: 90%;
    }

    .productContainBg {
        height: 175px;
        top: 25px;
    }

    .productContainText {
        margin: 10px 10px;
        font-size: 15px;
    }

    /* 聯絡表單 */
    .contactTitlePosition {
        position: relative;
        top: 50px;
        display: flex;
        justify-content: center;
    }

    .contactThank {
        margin: 30px auto;
        position: relative;
        top: 50px;
    }

    .contactForm {
        top: 25px;
        margin: 0px auto;
        display: flex;
        justify-content: center;
    }

    .contactFormLabel {
        font-size: 20px;
        font-weight: bold;
        white-space: nowrap;
        margin-top: 16px;
    }

    /* footer */
    .contactUsBg {
        position: relative;
        top: 100px;
    }

    .contactUsContain {
        position: relative;
        top: -30px;
    }

    .contactUsMethod {
        position: relative;
        top: -35px;
    }

    /* copyright */
    .copyrightBg {
        margin-top: 100px;
        font-size: 12px;
    }
}
</style>


