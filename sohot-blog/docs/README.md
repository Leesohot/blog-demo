---
home: true
heroImage: '/vuepress/topic2.png'
faceImage: '/vuepress/head.png'
heroImageStyle: {
  maxWidth: '800px',
  width: '100%',
  height: '15%',,
  display: block,
  margin: '24% auto -18% auto',
  //border: '1px dashed #000',
  box-shadow: '8px 8px 20px #022',
  borderRadius: '1rem',
  background: 'rgba(0, 0, 0, 0.8) none repeat scroll !important',
}
isShowTitleInHome: true
actionText: 'READ NOW'
actionLink: /views/
features:
- title: 
  details: Software Engineering
- title: 
  details: Front-end
- title: 
  details: HFUT
footer: MIT Licensed | Copyright © 2018-present Evan You
---

<Clock/>

::: tip Introducion:
<font size=5>Bio:<br/></font>
Sohot(LI SONGHAO) is a student at HFUT.<br/>
Proficient in Java, C++, C, etc.<br/>
Having good coding habits and procedure framing abilities<br/> 
Having a good knowledge of version management<br/>
Having experiences of leading teams to program with git+gitlab<br/>

<font size=5>Awards and Honors: </font>
- Individual Scholarship, Hefei University of Technology, 2019<br/>
- Elected as an Excellent league member, Hefei University of Technology, 2019<br/>


<font size=5>Experiences：<br/></font>
Culture exchange in East Asia <br/>
College Students' Innovative Entrepreneurial Training Plan Program <br/>
Search and Mining of Social Information on the Internet based on Elasticsearch <br/>
The System of Receiving and Handing out Homework for the Company Named Chinese Handwriting Classroom <br/>
 

:::


<CanvasNest color='0,23,255' zIndex='-2'></CanvasNest>

<style>
.home .content__default:not(.custom) {
  max-width: 100% !important;
  margin: 0  !important;
  padding: 0 !important;
}
.home .hero h1 {
    display: none;
}
.home img {
   transform: scale(0.8,0.8) !important;
   transition: all 1s!important;
}
.home img:hover {
   transform: scale(1)!important;
   transition:all 2s !important;
}
/* 阻止描述冒泡 */
.home .hero .description{
    pointer-events: none;
    cursor: default;
    opacity: 0.6;
}
.home .feature p {
    color: #476582 !important;
}
.home .hero .description {
    color: #476582 !important;
}
.wrap {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 200px;
    min-height: 10vh;
    background: transparent none repeat scroll!important;
    position: fixed;
    top: -120%;
    left: -1%;
}

@media screen and (max-width: 768px){
  .clock {
    margin-top: -35%
  }
}

@media screen and (max-width: 700px){
  .wrap {
    top:-107%;
    transform: scale(0.68,0.58);
  }
  .home img {    
    margin: 24% auto -6% auto !important;
  }
  .home .feature {
    width: 100%;
    text-align: center;
    color: rgb(71, 101, 130) !important;
    padding: 5px !important;
    margin: -12px;
    margin-left: 0px;
  }
  .clock {
    margin-top: 0%;
    background: rgba(0, 0, 0, 0) none repeat scroll !important;
    background-image: url() !important;
  }
}
.clock {
  transition: all 2s;
}
.wrap {
  transition: all 2s;
}
.clock:hover {
  transform: scale(0.55) !important;
  transition: all 2s;
}
.wrap:hover {
  transform: scale(1.15) !important;
  transition: all 2s;
}

</style>

