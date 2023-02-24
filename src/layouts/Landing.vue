<script setup>
    import MyButton from "../components/Button.vue";
</script>

<template>
  <div class="navbar-container">
        <img class="logo" alt="Vue logo" src="../img/logo.png" />
        
        <div class="navbar-menu-container">
            <div class="navbar-menu f-row f-center">
                <div class="nav-item font16 font-dark-blue fontbold"> Products </div>
                <div class="nav-item font16 font-dark-blue fontbold"> Code </div>
                <div class="nav-item font16 font-dark-blue fontbold"> Ecosystem </div>
                <div class="nav-item font16 font-dark-blue fontbold"> Team </div>
                <div class="nav-item font16 font-dark-blue fontbold"> Resources </div>
                <MyButton class="join-btn font-dark-blue font16 fontbold" value="Join"/>
            </div>
        </div>  
  </div>
  <div class="company-show-container">
     <div class="show-background">
        <div class="show-caption f-col">
            <div class="font80 font-light-blue fontbold">HUMAN Token</div>
            <div class="font80 font-dark-blue fontbold">(HMT)</div>
            <div class="font18 mt40">Fuelling the HUMAN ecosystem</div>
            <MyButton class="leave-btn mt40 font16 font-dark-blue fontbold" value="Leave more"/>
        </div>
        <div class="big-logo">
            <img alt="Vue logo" src="../img/advpng.png" />
        </div>
     </div>
  </div>
  <div class="layout1-container f-row f-center">
    <img class="layout1-image" src="../img/pic1.png" />
    <div class="layout1-content font48 font-dark-blue">HMT funds the processing of digitized work, and rewards workers for their contributions.</div>
  </div>
  <div class="layout2-container mt40 f-row f-center">
        <div class="f-col">
            <div class="font60 font-dark-blue fontbold">Token Details</div>
            <div class="layout2-token-detail f-row f-center">
                <div class="f-col f-center w25 h100 mr10">
                    <div class="f-col  w100 h50">
                        <div class="font18 font-dark-blue f-al">Ticker</div>
                        <div class="font32 font-dark-blue f-ar">HMT</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class="f-col w100 h50 mt15">
                        <div class="font18 font-dark-blue f-al">Token Price</div>
                        <div class="">
                            <div class="font32 font-dark-blue d-in-l">USD</div>
                            <div class="font32 font-dark-blue d-in-r">7.6</div>
                        </div>
                    </div>
                </div>
                <div class="brr h100"></div>
                <div class="f-col f-center w75 ml20">
                    <div class="w100 h33 f-row f-center">
                        <div class="font18 font-dark-blue w50 f-al">Circulating Supply</div>
                        <div class="font32 font-dark-blue w50 f-ar">120,000,000</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class="w100 h33 f-row f-center">
                        <div class="font18 font-dark-blue w50 f-al">Total Supply</div>
                        <div class="font32 font-dark-blue w50 f-ar">1.000.000.000</div>
                    </div>
                    <div class="w100 brt mt5"></div>
                    <div class=" w100 h33  f-row f-center">
                        <div class="font18 font-dark-blue w50 f-al">Market Cap</div>
                        <div class="font32 font-dark-blue w50 f-ar">1.000.000.000</div>
                    </div>
                </div>
            </div>
            <div class=" mt20">
                <div class="token-type-container d-in-l">
                    <div class="font18 ma d-in-l"><span class=" f-row f-center" style="height:45px; padding-left:20px">Token Type</span></div>
                    <div class="font32 font-dark-blue d-in-r mr10">ERC-20</div>
                </div>
                <div class="contact-address-container d-in-r">
                    <div>
                        <div class="font18 ma d-in-l font-dark-blue d-in-l"><span class=" f-row f-center" style="height:45px; padding-left:20px">Contact Address</span></div>
                        <div class="d-in-r"><button class="link-btn font18 font-dark-blue ml30">Ethereum</button></div>
                        <div class="d-in-r"><button class="link-btn font18 font-dark-blue ml40 mr10">Polygon</button></div>
                    </div>
                </div>
                <div class="f-row f-center mt40">
                    <div class="audit-item w50 f-row f-center">
                        <div class="font18 mta mr40"><span>Smart Contract Audit</span></div>
                        <div class="font32 mta"><span>Loremipsum</span></div>
                    </div>
                    <div class="audit-item w50 f-row ml40 f-center">
                        <div class="font18 mta mr40"><span>Escrow Factory</span></div>
                        <div class="font32 mta mr40"><span>Loremipsum</span></div>
                    </div>
                </div>
            </div>
            <div class="mt40">
              <img src="../img/Group 1284.png">
            </div>
        </div>
  </div>
  <div class="layout3-container f-col mt40 f-center">
    <div class="font60 font-dark-blue fontbold">HUMAN in the media</div>
    <img src="../img/Group 1294.png">
  </div>
  <div class="normal-container f-col mt40 f-center">
    <img src="../img/Group 1300.png">
  </div>
  <div class="normal-container f-col mt40 f-center">
    <img src="../img/Group 1298.png">
  </div>
  <div class="layout2-container f-col mt40 w75 f-center">
    <div class="font60 font-dark-blue fontbold">How do I get HMT?</div>
    <div class="f-row ml20 mr20 mt40 f-center w75">
      <div class="picture-box1 ma f-show f-center">
        <img src="../img/Group 1309.png">
      </div>
      <div class="picture-box1 ma f-show f-center">
        <img src="../img/Group 1310.png">
      </div>
      <div class="picture-box1 ma f-show f-center">
        <img src="../img/Group 1311.png">
      </div>
      <div class="picture-box1 ma f-show f-center">
        <img src="../img/Group 1312.png">
      </div>
      <div class="picture-box1 ma f-show f-center">
        <img src="../img/Group 1313.png">
      </div>
    </div>
  </div>
  <div class="human-container f-row f-center">
    <div class="human-content">
        <div class="font60 font-dark-blue w100 f-ac fontbold" style="padding:101px 143px 0px 143px">Utility of the HUMAN Token</div>
        <div class="human-list   f-center">
            <div class="picture-box2 f-col f-center">
                <img src="../img/Group 439.png" style="width:auto"/>
                <div class="font18 font-dark-blue fontbold mt40">Complete Jobs</div>
            </div>
            <div class="picture-box2 f-col f-center">
                <img src="../img/Group 1320.png" style="width:auto"/>
                <div class="font18 font-dark-blue fontbold mt40">Grants Program</div>
            </div>
            <div class="picture-box2 f-col f-center">
                <img src="../img/Group 610.png" style="width:auto"/>
                <div class="font18 font-dark-blue fontbold mt40">Ambassador Program</div>
            </div>
        </div>
    </div>
  </div>
  <div class="disclaim-container f-col f-al ma">
    <div class="font60 font-dark-blue f-al">Disclaimer</div>
    <div class="font18 fontline30 font-dark-blue f-al mt40">The HUMAN Protocol Foundation makes no representation, warranty, or undertaking, express or implied, as to the accuracy, reliability, completeness, or reasonableness of the Information. Any assumptions, opinions, and estimates expressed in the information on this page constitutes the HUMAN Protocol Foundation’s judgment as of 18/11/21 and are subject to change without notice. The HUMAN Protocol Foundation does not accept any liability for any direct, consequential or other loss arising from reliance on the contents of the information in this graphic.</div>
  </div>
  <div class="layout8-container f-col f-center">
    <div class="w100" style="padding:0px 225px">
        <div class="font60 font-dark-blue d-in-l fontbold">Recent Entries</div>
        <button class="go-blog-btn font16 font-dark-blue d-in-r">Go Blog</button>
    </div>
    <div class="layout8-content mt40">
       <div class="layout8-view-content ">
            <div class="layout8-view f-row">
                <div class="card-list-item" style="margin-left: 225px;">
                    <img src="../img/Screen1.png" style="z-index: 5;position:relative"/>
                    <div class="selected-area"></div>
                    <div class="f-col card-list-detail" style="z-index: 5;">
                        <div class="f-row f-ccenter mt20">
                            <div class="font18 font-dark-blue">Mar 31  2022</div>
                            <button class="guest-post-btn ml40">Guest Post</button>
                        </div>
                        <div class="font32 font-dark-blue fontbold mt20">
                            Interview with Andreas Schemm, Head of Ecosystem Development & Operations at HUMAN Protocol
                        </div> 
                        <button class="community-btn mt40 font16 font-dark-blue">Community</button>
                    </div>
                </div>
                <div class="card-list-item f-col ml40">
                    <img src="../img/Screen2.png"/>
                    <div class="f-col card-list-detail">
                        <div class="f-row f-ccenter mt20">
                            <div class="font18 font-dark-blue">Mar 31  2022</div>
                            <button class="guest-post-btn ml40">Guest Post</button>
                        </div>
                        <div class="font32 font-dark-blue fontbold mt20">
                            Interview with Andreas Schemm, Head of Ecosystem Development & Operations at HUMAN Protocol
                        </div> 
                        <button class="community-btn mt40 font16 font-dark-blue">Community</button>
                    </div>
                </div>
                <div class="card-list-item f-col ml40">
                    <img src="../img/Screen3.png"/>
                    <div class="f-col card-list-detail">
                        <div class="f-row f-ccenter mt20">
                            <div class="font18 font-dark-blue">Mar 31  2022</div>
                            <button class="guest-post-btn ml40">Guest Post</button>
                        </div>
                        <div class="font32 font-dark-blue fontbold mt20">
                            Interview with Andreas Schemm, Head of Ecosystem Development & Operations at HUMAN Protocol
                        </div> 
                        <button class="community-btn mt40 font16 font-dark-blue">Community</button>
                    </div>
                </div>
            </div>
       </div>
    </div>
    <div class="arrow-container">
        <button class="arrow-btn font18 f-ac d-in-r ml40 mr10 font-dark-blue">{{ ">" }}</button>
        <button class="arrow-btn font18 f-ac d-in-r ml40 font-dark-blue">{{ "<" }}<ArrowBackIcon/></button>
    </div>
  </div>
  <div class="last-container f-row">
    <div class="last-content ma">
      <div class="font32 fontbold font-dark-blue mt20">Get HUMAN news and updates</div>
      <div class="f-row mt20 f-left">
        <div class="input-email font18 font-dark-blue w60 f-al">your@email.com</div>
        <div class="submit-email font18 font-white ma w30 f-ac">Subscribe</div>
      </div>
      <div class="font18 font-dark-blue mt20">Get HUMAN news and updates</div>
    </div>
    <div class="last-content ma w20 f-row">
      <div class="font32 font-dark-blue ma"><img src="../img/icon1.png"></div>
      <div class="font32 font-dark-blue ma"><img src="../img/icon2.png"></div>
      <div class="font32 font-dark-blue ma"><img src="../img/icon3.png"></div>
      <div class="font32 font-dark-blue ma"><img src="../img/icon4.png"></div>
      <div class="font32 font-dark-blue ma"><img src="../img/icon5.png"></div>
    </div>
  </div>
  <div class="footer f-row ma">
    <div class="f-col mpa  f-al">
      <div class="font18 font-dark-blue fontbold">Products</div>
      <div class="font18 font-dark-blue mt30">HUMAN App</div>
      <div class="font18 font-dark-blue mt30">Proof of HUMANity</div>
      <div class="font18 font-dark-blue mt30">IMOO</div>
    </div>
    <div class="f-col mpa f-al">
      <div class="font18 font-dark-blue fontbold">Discover</div>
      <div class="font18 font-dark-blue mt30">Token</div>
      <div class="font18 font-dark-blue mt30">Routing Layer</div>
      <div class="font18 font-dark-blue mt30">Team</div>
      <div class="font18 font-dark-blue mt30">Careers</div>
    </div>
    <div class="f-col mpa  f-al">
      <div class="font18 font-dark-blue fontbold">Build</div>
      <div class="font18 font-dark-blue mt30">Developers</div>
      <div class="font18 font-dark-blue mt30">Technology</div>
      <div class="font18 font-dark-blue mt30">DevBounty Program</div>
      <div class="font18 font-dark-blue mt30">BugBounty Program</div>
      <div class="font18 font-dark-blue mt30">Github</div>
      <div class="font18 font-dark-blue mt30">Grants Program</div>
    </div>
    <div class="f-col mpa  f-al">
      <div class="font18 font-dark-blue fontbold">Community</div>
      <div class="font18 font-dark-blue mt30">Grants Program</div>
      <div class="font18 font-dark-blue mt30">Elite Ops Program</div>
      <div class="font18 font-dark-blue mt30">Events</div>
    </div>
    <div class="f-col mpa f-al">
      <div class="font18 font-dark-blue fontbold">Resources</div>
      <div class="font18 font-dark-blue mt30">Documents Hub</div>
      <div class="font18 font-dark-blue mt30">Lifepaper</div>
      <div class="font18 font-dark-blue mt30">Technical Whitepaper</div>
      <div class="font18 font-dark-blue mt30">AI Whitepaper</div>
      <div class="font18 font-dark-blue mt30">System Status</div>
      <div class="font18 font-dark-blue mt30">In The News</div>
      <div class="font18 font-dark-blue mt30">One Pagers Archive</div>
      <div class="font18 font-dark-blue mt30">Brand Assets</div>
    </div>
    <div class="f-col mpa  f-al">
      <div class="font18 font-dark-blue fontbold">Impact Projects</div>
      <div class="font18 font-dark-blue fontbold mt30">Blog</div>
      <div class="font18 font-dark-blue fontbold mt30">Explorer</div>
    </div>
  </div>
  <div class="contact-container f-col ma">
    <div class="f-al font18 font-dark-blue fontbold">Third-party communities</div>
    <div class="f-row contact-content">
      <div class="send-box f-row mra w60 mt40">
        <img src="../img/Tele.png">
        <div class="f-al font18 font-dark-blue fontbold ml30">Telegram</div>
      </div>
      <div class="send-box f-row mla w30 mt40">
        <img src="../img/Mixin.png">
        <div class="f-al font18 font-dark-blue fontbold ml30">Mixin</div>
      </div>
    </div>
  </div>
</template> 

<style scoped>

.layout8-container{
        padding: 0px 0px 100px 0px;
    }
    .layout8-content{
        overflow:hidden;
        width:100vw;
        height:780px;
    }
    .arrow-container{
        width:100%;
        padding:40px 227px 0px 0px;
    }
    .arrow-btn{
        width:80px;
        height:80px;
        background: linear-gradient(145.2deg, #F0F2FC -4.32%, #FFFFFF 61.97%);
        box-shadow: 0px 12px 16px rgba(12, 32, 213, 0.07);
        backdrop-filter: blur(4.07742px);
        border:solid 5px white;
        border-radius: 50%;
    }
    .layout8-view-content{
        overflow-y: hidden;
        overflow-x: auto;
        height:820px;
    }
    .layout8-view{
        width:2500px;
    }
    .card-list-item
    {
        position:relative;
        width:712px;
        height:758px;
        z-index: 5;
    }
    .selected-area
    {
        z-index: 1;
        position:absolute;
        width:760px;
        height:720px;
        left:-24px;
        top:0px;
        background: #FFFFFF;
        border-radius: 40px;
        box-shadow: 4px 4px 10px #F2F2FA;
    }
    .card-list-item>img{
        z-index: 5;
        padding:50px;
        width:100%;
        height:50%;
    }
    .go-blog-btn{
        border: 2px solid #320A8D;
        border-radius: 10px;
        width:184px;
        height:56px;
    }
    .guest-post-btn{
        width:133px;
        height:32px;
        background: #FFFFFF;
        /* Blue/400 */
        border: 1px solid #320A8D;
        border-radius: 10px;
    }
    .community-btn{
        width:133px;
        height:40px;
        border: none;
        background: #F2F2FA;
        border-radius: 20px;
    }
    .card-list-detail{
        position: relative;
        width:100%;
        height:50%;
        padding:0px 76px 0px 76px;
    }
.send-box{
  width:auto;
  padding:30px 0px 30px 0px;
  border-bottom:1px solid #320A8D;
}
.contact-content{
  display: flex;
  flex: 60% 30%;
}
.contact-container{
  background: #E9EBFA;
  padding:150px 5% 150px 5%;
}
.footer{
  background: #F2F2FA;
  padding:150px 5% 150px 5%;
}
.submit-email{
  padding-top:10px;
  padding-bottom: 10px;
  background:#320A8D;
  border-radius: 10px;
}
.input-email{
  padding-top:10px;
  padding-bottom: 10px;
  padding-left: 4%;
  background:#FFFFFF;
  border-radius: 10px;
  border:2px solid #320A8D;
}
.last-container{
  background: #FBFBFD;
}
.last-content{
  padding:150px 0px 150px 0px;
}

.entry-content{
  padding-left: 20%;
  width:auto;
}

.entry-container{
}
.fontline30{
  line-height: 30px;
}
.disclaim-container{
    padding: 200px 0px 200px 0px;
    width: 60%; 
}
.human-container{
    padding: 200px 0px 200px 0px;
    width: 100%;
}
.human-content{
    width:1472px;
    height:454px;
    background: #F2F2FA;
    border-radius: 40px;
}
.human-list {
    margin-top:120px;
    padding:0px 100px 100px 100px;
    display: flex;
    flex-wrap:wrap;
}
.picture-box2{
    margin:0px 50px;
    width:300px;
    height:300px;
    background: #FFFFFF;
    border-radius: 10px;
    box-shadow: 4px 4px 10px #F0F2FC;
}
.picture-box2>img{
    width:50%;
    height:20%;
}
.picture-box1{
  background:#FFFFFF;
  border-radius: 20px;
  width:200px;
  height:200px;
  box-shadow:0px 5px 5px #F2F2FA
}
  .layout3-container{
    padding-top:143px;
    width: 100%;
    border-radius: 30px;
background: #F2F2FA;
  }
/*Flex*/

.f-show{
  display: flex;
}
.f-row{
  display: flex;
  flex-direction: row;
}

.f-col{
  display: flex;
  flex-direction: column;
}

.f-center{
  justify-content: center;
  align-items: center;
}

.f-rcenter{
  justify-content: center;
}
.f-ccenter{
  align-items: center;
}
.f-left{
  align-items: start;
}
/*Font*/

.font80{
  font-size: 80px;
}
.font60{
  font-size: 60px;
}
.font48{
  font-size: 48px;
}
.font32{
  font-size: 32px;
}
.font18{
  font-size: 18px;
}
.font16{
  font-size: 16px;
}

.font-dark-blue{
  color:#320A8D;
}
.font-light-blue{
  color:#6309FF;;
}

.font-white{
  color:#FFFFFF;;
}

.fontbold{
  font-weight: 700;
}


.f-al{
  text-align: left;
}
.f-ac{
  text-align: center;
}
.f-ar{
  text-align: right;
}
/*margin*/

.mt5{
  margin-top: 5px;
}
.mt10{
  margin-top: 10px;
}
.mt15{
  margin-top: 15px;
}
.mt20{
  margin-top: 20px;
}
.mt30{
  margin-top: 30px;
}
.mt40{
  margin-top: 40px;
}

.ml5{
  margin-left: 5px;
}
.ml10{
  margin-left: 10px;
}
.ml15{
  margin-left: 15px;
}
.ml20{
  margin-left: 20px;
}
.ml30{
  margin-left: 30px;
}
.ml40{
  margin-left: 40px;
}

.mr10{
  margin-right: 10px;
}
.mr30{
  margin-right: 30px;
}
.mr40{
  margin-right: 40px;
}
.mb30{
  margin-bottom: 30px;
}
.mb40{
  margin-bottom: 40px;
}
.mb100{
  margin-bottom: 100px;
}

.ma{
  margin:auto;
}

.mta{
    margin-top:auto;
    margin-bottom: auto;
}
.mpa{
    margin-left:auto;
    margin-right: auto;
}
.mla{
    margin-left:auto;
}
.mra{
    margin-right: auto;
}

.pdr10{
  padding-right: 10px;
}
.pd10{
  padding: 10px;
}
.pda{
  padding: auto;
}

.w100{
  width:100%;
}
.w75{
  width:75%;
}
.w60{
  width:60%;
}
.w50{
  width:50%;
}
.w30{
  width:30%;
}
.w20{
  width:20%;
}
.w25{
  width:176px;
}

.h100{
  height:168px;
}

.h50{
  height:84px;
}

.h33{
  height:56px;
}

.d-in-r{
  display: inline-block;
  float:right;
}

.d-in-l{
  display: inline-block;
  float:l;
}

.brt{
  border-top:solid 2px lightgrey;
}

.brr{
  border-right:solid 2px lightgrey;
}
.layout2-container{
        padding-top:143px;
        width: 100%;
        background: linear-gradient(167.14deg, #F0F2FC 9.58%, #FFFFFF 93.46%)!important;
    }
    .layout2-token-detail{
        margin-top: 60px;
        width:1088px;
        height:248px;
        padding:80px 38px 40px 38px;
        background: #FFFFFF;
        border-radius: 30px;
    }
    .token-type-container{
        padding:14px;
        width:357px;
        height:79px;
        background: #FFFFFF;
        border-radius: 30px;
    }
    .contact-address-container{
        padding:14px;
        width:auto;
        height:79px;
        background: #FFFFFF;
/* Blue/400 */
        border: 2px solid #320A8D;
        border-radius: 40px;
    }
    .audit-item{
        height:80px;
        background: #320A8D;
        border-radius: 25px;
        color:white;
    }
    .link-btn{
        width:200px;
        height:75px;
        background: #FFFFFF;
        border-radius: 10px;
    }
    .company-show-container{
        padding: 0px 72px;
    }
    .show-background{
        position: relative;
        width:100%;
        height:680px;
        background: linear-gradient(167.14deg, #F0F2FC 9.58%, #FFFFFF 93.46%);
        background: #F2F2FA;
        border-radius: 40px;
    }
    .show-caption{
        z-index: 5;
        position: relative;
        padding:167px 100px;
    }

    .big-logo{
        z-index: 0;
        position:absolute;
        width:704px;
        height:592px;
        right:95px;
        top:87px;
    }
    .big-logo>img{
        width:100%;
        height: 100%;
    }
    .leave-btn{
        width:127px;
        height:56px;
    }
    .layout1-container{
        padding: 193px 0px;
        width: 100%;
    }
    .layout1-image{
        width:608px;
        height:608px;
    }
    .layout1-content{
        width:608px;
    }
    .navbar-container{
        padding:62px 75px;
    }
    .logo{
        width:134.23px;
        height:32px;
        display: inline-block;
    }
    .navbar-menu-container{
        display: inline-block;
        float: right;
    }
    .nav-item {
        margin-left: 65px;
    }
    .join-btn{
        display: inline-block;
        float: right;
        width:144px;
        height:56px;
        margin-left: 68px;
    }
</style>
