<style>
   .esu-hp-content {
    overflow-x: auto;
    overflow-y: auto;
    background-color: rgb(255,240,240);
    border-top-left-radius: 5px 5px;
    border-top-right-radius: 5px 5px;
    border-bottom-right-radius: 5px 5px;
    border-bottom-left-radius: 5px 5px;
    border-radius: 5px;
    border-width: 1px;
    border-style: solid;
    padding: 10px;
    border-color:rgba(255, 120 , 178, 0.1);
    -webkit-box-flex: 1;
        -ms-flex: 1;
            flex: 1;
  }

  .esu-overflow-visible {
    overflow: visible !important;
  }
  .esu-hp-text-center {
    text-align: center;
  }

  .esu-hp-huge-text {
    font-size: 500%;
  }

  .esu-hp-title {
    color: black;
    background-image: none;
    background-color: transparent;
    font-weight: normal;
    overflow-x: hidden;
    overflow-y: hidden;
    line-height: 1.3;
    font-size: 1.5em;
    text-align: left;
    border-width: medium;
    border-style: none none hidden;
    margin: 1px;
    padding: 1px;
    padding-bottom: 4px;
    -webkit-box-flex: 0;
        -ms-flex: 0 0 auto;
            flex: 0 0 auto;
  }

  .esu-hp-title .floatleft {
    margin: 0;
  }

  .esu-hp-row {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
        -ms-flex-direction: row;
            flex-direction: row;
    -ms-flex-pack: distribute;
        justify-content: space-around;
    -webkit-box-align: stretch;
        -ms-flex-align: stretch;
            align-items: stretch;
    -ms-flex-wrap: wrap;
        flex-wrap: wrap;
  } 

  .esu-hp-item {
    max-width: 100%;
    min-width: 320px;
    vertical-align: top;
    background-color: rgba(250, 120, 178, 0.5);
    border-color: rgba(255, 120 , 178, 0.1);
    border-width: 1px;
    border-style: solid;
    margin: 5px 1px;
    border-radius: 5px;
    -webkit-box-flex: 1;
        -ms-flex: 1 1 0px;
            flex: 1 1 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column;
  }

  .esu-hp-left {
    justify-self: flex-start;
  }

  .esu-hp-right {
    justify-self: flex-end;
  }
  
  .esu-hp-zxr-container {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: space-evenly;
        -ms-flex-pack: space-evenly;
            justify-content: space-evenly;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
        -ms-flex-direction: row;
            flex-direction: row;
  }

  @media( max-width: 1024px ){
    .esu-hp-zxr-container  {
      -webkit-box-orient: vertical;
      -webkit-box-direction: normal;
          -ms-flex-direction: column;
              flex-direction: column;
    }
  }
  .esu-hp-zxr-text {
    color: rgba(255, 0, 0, 0.546875);
    font-family: 微软雅黑;
    white-space: nowrap;
    text-shadow: rgb(255, 255, 255) 0px 0px 5px, rgb(255, 255, 255) 0px 0px 10px, rgb(255, 255, 255) 0px 0px 15px, rgba(255, 0, 0, 0.746094) 0px 0px 40px, rgba(255, 0, 0, 0.796875) 0px 0px 70px;
    border-width: 0;
    border-style: solid;
  }

  #esu-topbanner {
    background-color: rgba(247, 117, 175,0.8);
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    border-radius: 5px;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    padding: 0.5em 0;
  }
  #esu-topbanner .left{
    text-align: center;
    max-width: 280px;
    -webkit-box-flex: 1;
        -ms-flex: 1;
            flex: 1;
  }
  #esu-topbanner .primary-title{
    font-size:1.5em;
    margin:0;
    line-height:1.5;
    text-shadow: rgb(255, 255, 255) 0px 0px 5px, rgb(255, 255, 255) 0px 0px 10px, rgb(255, 255, 255) 0px 0px 15px, rgba(225, 100, 150, 0.3) 0px 0px 40px, rgba(225, 100, 150, 0.3) 0px 0px 70px;
  }

  #esu-topbanner .secondary-title{
    font-size: 0.9em;
  }

  #esu-topbanner .right{
     padding: 0 0.5em;
  }

  #esu-topbanner .right p{
     margin: 0;
  }

  #fallback-banner {
    text-align:center;
    background-color:rgb(247, 117, 175);
    display: none;
  }
 
  @media all and (-ms-high-contrast: none), (-ms-high-contrast: active) {
     .esu-hp-item{ display:block; }
  }

  .skin-minerva .esu-hp-content > table > tbody > tr > td:nth-child(1) {
    display: block;
  }

  .skin-minerva .esu-hp-content > table > tbody > tr > td:nth-child(2) {
    display: block;
  }
  .skin-minerva .esu-hp-content > table {
    margin: 0;
  }
</style>
<div id="fallback-banner">
  <h3>
    你的浏览器都旧得生[[蛆]]了，如无法正常黑屁请立刻[https://www.mozilla.org/ 升级大脑]
  </h3>
</div>
<div id="esu-topbanner">
  <div class="left">
    <div class="primary-title">硝神百科</div>
    <div class="secondary-title">揭露事实真相的百科全书<br>
      共有[[Special:Statistics|{{NUMBEROFARTICLES}}]]个条目</div>
  </div>
  <div class="right">
[[file:Esu_icon_2018.png|64px|]]
  </div>
</div>

<div class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:Announce.png|left|25px]]公告
    </div>
    <div class="esu-hp-content esu-hp-text-center">
{{公告}}
    </div>
  </div>
</div>
<div class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:good.png|left|25px]]国际巨星
    </div>
    <div class="esu-hp-content">
      {{国际巨星}}
    </div>
  </div>
</div>

<div class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:good.png|left|25px]]Ｃ位出道
    </div>
    <div class="esu-hp-content">
      {{C位出道}}
    </div>
  </div>
</div>
<div class="esu-hp-row">
  <div class="esu-hp-item esu-hp-left">
    <div class="esu-hp-title">
      [[File:good.png|left|25px]]超级巨星
    </div>
    <div class="esu-hp-content">
      {{超级巨星}}
    </div>
  </div>
  <div class="esu-hp-item esu-hp-right">
    <div class="esu-hp-title">
      [[File:Unknown.png|left|25px]]年度硬汉
    </div>
    <div class="esu-hp-content">
      {{年度硬汉}}
    </div>
  </div>
</div>
<div id="ASSPC" class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:Announce.png|left|25px]]招聘请示
    </div>
    <div class="esu-hp-content esu-text-center esu-overflow-visible">
      <center> <div class="esu-hp-content esu-hp-text-center esu-hp-huge-text esu-hp-zxr-container" style="background-color:pink">
        <div class="desktop-inline esu-hp-zxr-text">[[File:Ad.jpg|500px|link=https://m.tb.cn/h.41xdBjF]]</div>
      </div></center>
    </div>
  </div>
</div>

<div class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:picture.png|left|25px]]高雅画廊
    </div>
    <div class="esu-hp-content">
      {{画廊}}
    </div>
  </div>
</div>

<div class="esu-hp-row">
  <div class="esu-hp-item esu-hp-left">
    <div class="esu-hp-title">
      [[File:artical.png|left|25px]]高雅美文
    </div>
    <div class="esu-hp-content">
      {{高雅美文}}
    </div>
  </div>
  <div class="esu-hp-item esu-hp-right">
    <div class="esu-hp-title">
      [[File:know.png|left|25px]]你知道吗
    </div>
    <div class="esu-hp-content">
      {{你知道吗}}
    </div>
  </div>
</div>
<div class="esu-hp-row">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:worlds.png|left|25px]]名言警句
    </div>
    <div class="esu-hp-content esu-text-center">
      {{名言警句}}
    </div>
  </div>
</div>

<div class="esu-hp-row mobile-block">
  <div class="esu-hp-item">
    <div class="esu-hp-title">
      [[File:know.png|left|25px]]手机版导航
    </div>
    <div class="esu-hp-content esu-text-center">
      {{手机版导航}}
    </div>
  </div>
</div>
