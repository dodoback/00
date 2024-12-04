@charset "utf-8" ;
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
li {
    list-style: none;
}
a {
    text-decoration: none;
    color: inherit;
}

body {
    background-color: #F0E7DB;
}

.header {
    width: calc(100% - 180px);
    height: 100px;
    position: fixed;
    top: 20px;
    left: 50%;
    transform: translate(-50%);
    background-color: #fff;
    z-index: 99;
    font-size: 14px;
}
.header .inner {
    display: flex;
    height: 100%;
    text-align: center;
    max-width: 1640px;
    width: calc(100% - 32px);
    margin: 0 auto;
    justify-content: space-between;
    align-items: center;
    
    
}
.header .inner .gnb {
    display: flex;
    gap: 15px;
    margin-right: 450px;

}




.header .inner .nav .gnb .depth02_wrap  {
    background-color: #fff;
    max-width: 1740px;
    width: 100%;
    height: 488px;
    position: absolute;
    top: 100px;
    left: 50%;
    transform: translate(-50%,0);
    display: none;
}


.header .inner .depth02_wrap .depth02_inner {
    max-width: 1190px;
    width: calc(100% - 32px);
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    
}

.header .inner .depth02_wrap .depth02_inner .depth02 li a {
    font-size: 20px;
    font-weight: bold;
}

.header .inner .depth02_wrap .depth02_inner .depth02 .depth03 li a {
    font-size: 14px;
    font-weight: 400;
    margin: 10px 0;
    display: inline-block;
    
}

.header .inner .depth02_wrap .depth02_inner .depth_image img {
    width: 919px;
    height: 465px;
    object-fit: cover;
    
}

.header .inner .util {
    display: flex;
    gap: 10px;
}

.header .inner .util .lang {
    position: relative;
}

.header .inner .util .lang ul {
    background-color: #fff;
    max-width: 1740px;
    width: 100%;
    position: absolute;
    top: 60px;
    left: 50%;
    transform: translate(-50%,0);
    display: none;
}

.header .inner .util .lang ul li {
    padding: 10px;
    border: 1px solid #333;
    font-size: 20px;
    /* display: none; */
    
}

.header .inner .util .lang ul li a {
    /* display: none; */
}

.header .inner .util .top_menu {
    display: flex;
    gap: 10px;
}

.header .inner .image1 {
    width: 1920px;   
}
.header .inner .image1 img {
    width: 100%;
}


.main-link {
margin-top: 45px;
}

.main-link .wid-wrap {
    display: flex;
    width: 100%;
    justify-content: center;
}

.main-link .wid-wrap .wid3 a {
    display: table;
    width: 100%;
    background-color: #fff;
    padding: 45px 30px;
    text-align: center;
    border: 1px solid #999;
}
.main-link .wid-wrap .wid3 a p {
    margin: 0px 0px 10px;
    padding: 0px 0px 10px;
    
}
.main-link .wid-wrap .wid3 a p:nth-child(1){
    font-size: 22px;
    font-weight: bold;
    color: 53513d;
}
.main-link .wid-wrap .wid3 a p:nth-child(2){
    color: #53513d;
}

.main-choice {
    margin: 130px 130px;
}
.main-choice .sub-title {
    font-size: 34px;
    text-align: center;
    margin: 0 0 15px;
}
.main-choice .editor-tabcont {
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
}

.main-choice .editor-tabwr .editor-tabtit {
    display: flex;   
    justify-content: center;
}
.main-choice .editor-tabwr .editor-tabtit span {
    display: flex;
    align-items: center;
    color: rgba(83, 81, 61, 0.6);
}

.main-choice .editor-tabwr .editor-tabtit li:nth-child(1) {
    color: #333;
    font-weight: bold;
    border-bottom: 2px solid #333;
    
}
.main-choice .editor-tabwr .editor-tabtit li {
    font-size: 16px;
    color: rgba(83, 81, 61, 0.6);
    padding: 8px 25px;
}

.main-choice .editor-tabcont .image_1 .image_all  {
   position: relative;
}
.main-choice .editor-tabcont .image_1 .image_all img {
    display: block;
}
.main-choice .editor-tabcont .image_1 .item_icon_box {
    position: absolute;
    top: 0;
    left: 0;
    padding: 10px 0 0 10px;
}
.main-choice .item_info_cont .item_tit_box .item_name b {
    font-size: 13px;
    color: #716f5e;
    
}
.main-choice .item_info_cont .item_tit_box .item_name p {
    font-size: 15px;
    color: black;
    font-weight: 400;
}

.main-choice .item_info_cont .item_money_box {
    padding: 10px 0 0;
}
.main-choice .item_info_cont .item_money_box span:nth-child(2){
    font-weight: bold;
}

.main-choice .item_info_cont {
    width: 308px;
    padding: 25px;
    
    background-color: #fff;
}

.main-choice .editor-tabwr ul li a {
    padding: 15px;
    background-color: #53513d;
    margin: 60px auto;
    justify-content: center;
    display: flex;
    width: 195px;
    color: #fff;
}

.main-event .sub-title {
    color: #53513d;
    text-align: center;
    font-size: 34px;
    margin: 0 0 15px;
    
}


.main-review p{
    font-size: 34px;
    margin-top: 140px;
    margin-bottom: 15px;
    text-align: center;
}
.main-review .review_wr  {
    display: flex;
    width: 1156px;
    margin: 0 auto;
    justify-content: space-between;

}
.main-review .review_wr .slick-list img {
    width: 366px;
    height: 254px;
    object-fit: cover;
    display: block;
    
}
.main-review .review_wr .slick-list .reviewInfo {
    width: 366px;
    height: 156px;
    background-color: #fff;
    padding: 25px 25px 15px;
    font-size: 14px;
    position: relative;
    flex-direction: column;
    justify-content: center;
    
    display: flex;
    
    
}

.main-review .review_wr .slick-list .reviewInfo a {
    border-bottom: 1px solid rgba(83, 81, 61, 0.7);
    padding: 0 0 10px;
}

.main-review .review_wr .slick-list .reviewInfo .star-wr {
    justify-content: space-between;
    padding: 10px 0 0;
    display: flex;
}
.main-review .review_wr .slick-list .reviewInfo .star-wr span  {
    display: flex;
    align-items: center;
}
.main-review .review_wr .slick-list .reviewInfo span img{
   width: 70px;
   height: 10px;
}


.main-insta {
    margin: 140px auto 130px;
    text-align: center;
    
}

.main-insta .sub-title{
    font-size: 34px;
    color: #53513d;
    margin: 0 0 15px;
}

.main-insta .insta_wr {
    display: flex;
    justify-content: space-between;
    margin: 50px auto;
    width: 1605px;

}

.main-insta .insta_wr img {
    width: 250px;
    height: 250px;
    object-fit: cover;
    
}

.foot_top {
    width: 100%;
    max-width: 1160px;
    margin: 0 auto;
    
}

.foot_top .item1 {
    position: relative;
    top: 25px;
    width: 754px;
    display: flex;
    justify-content: space-between;
}

.foot_top .item1  span:nth-child(1) {
   font-size: 18px;
   color: #3c3c3c;
   width: 150px;
}
.foot_top .item1  span:nth-child(2) {
   font-size: 15px;
   position: relative;
   right: 150px;
}
.foot_top .item1  span:nth-child(3) {
  
}

.foot_top .foot_wr {
    justify-content: space-between;
    align-items: center;
}

.foot_top .foot_wr .foot_sv  {
    width: 754px;
    height: 153px;
    display: flex;
    align-items: center;
    
}


.foot_top .foot_wr {
   display: flex;
   
}

.foot_top .foot_right img {
    width: 406px;
    height: 246px;
    object-fit: cover;
    padding: 0 0 0 60px;
}



.foot_top .foot_wr .foot_sv .info_box {
    display: table-cell;
    width: 50%;
    vertical-align: top;
}

.foot_top .foot_wr .foot_sv .info_box .cs_box p:nth-child(1){
    font-size: 18px;
    color: #3c3c3c;
}
.foot_top .foot_wr .foot_sv .info_box .cs_box p:nth-child(2){
    font-size: 40px;
    font-weight: bold;
    color: #53513d;
}
.foot_top .foot_wr .foot_sv .info_box .cs_box p:nth-child(3){
    font-size: 15px;
    color: #757575;
}
.foot_top .foot_wr .foot_sv .info_box .cs_box p:nth-child(4){
    font-size: 15px;
    color: #757575;
}


.foot_top .foot_wr .foot_sv .ac_box {
    display: table-cell;
    width: 50%;
    vertical-align: top;
    margin: 0 0 0 40px;
}

.foot_top .foot_wr .foot_sv .ac_box .cd_box p:nth-child(1){
    font-size: 18px;
} 
.foot_top .foot_wr .foot_sv .ac_box .cd_box p:nth-child(2){
    font-size: 23px;
} 
.foot_top .foot_wr .foot_sv .ac_box .cd_box p:nth-child(3){
    font-size: 15px;
} 
.foot_top .foot_wr .foot_sv .ac_box .cd_box .btn_cs {
    display: flex;
    
}

.foot_top .foot_wr .foot_sv .ac_box .cd_box .btn_cs a {
    display: block;
    width: 165px;
    height: 44px;
    font-size: 15px; 
    padding: 10px 15px;

} 
.foot_top .foot_wr .foot_sv .ac_box .cd_box .btn_cs a:nth-child(1) {
    background-color: #e7c35d ;
}
.foot_top .foot_wr .foot_sv .ac_box .cd_box .btn_cs a:nth-child(2) {
    background-color: #53513d ;
}
