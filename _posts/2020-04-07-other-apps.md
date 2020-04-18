---
layout: post
title:  "Other efforts across the world"
date:   2020-04-09 00:50:13
excerpt_separator: <!--more-->
---

<!-- 
##### BLubble, a wordplay between BLE and bubble, conveys very succinctly what we intend to achieve. Basically, we want to utilize Bluetooth Low Energy (BLE) beacons in order to classify the 6ft safe bubble you should be in, to maximize your social distancing effectiveness until the COVID-19 pandemic subsides. To this end, we are utilizing crowd-sourced data collection via various data collection apps we have developed. Please checkout our [Data Collection](./categories) page to help us out by contributing to the project. The below figure visually illustrates our technical approach. -->

Many governments and researchers around the world have been tackling the complicated problem of contact tracing in an effort to curb the spread of COVID-19. <a href="https://www.tracetogether.gov.sg/">TraceTogether</a> and <a href="https://www.mygov.in/aarogya-setu-app/">Aarogya Setu</a> have deployed their applications across Singapore and India respectively. These apps have broadly been adopted but have raised many questions about privacy, universal applicability, as well as the accuracy of bluetooth based proximity sensing.<!--more--> Within the United States, there have been many university led efforts to improve upon each of these aspects. However, these efforts are mainly targeting the privacy end, leaving the universal applicability and the bluetooth proximity sensing parts untouched. BluBLE aims to build upon the works of these efforts, and focus on the bluetooth proximity end of things. Furthermore, BluBLE is participating in symposiums like, <a href="https://sites.google.com/tamu.edu/nets-covid/second-call-to-arms-workshop">NSF Call to Arms workshop</a>, hosted by Nets community to create and utilize a collaborative research atmosphere.

<!-- ##### We are members of the [WCSNG Lab](https://wcsng.ucsd.edu) (Wireless Communications Networks and Sensing), UCSD. The Lab is headed by [Prof. Dinesh Bharadia](http://web.eng.ucsd.edu/~dineshb/). We work very extensively in the field of wireless localization, which forms the very heart of this problem of contact tracing via bluetooth connections.  -->

<!-- ##### Recent publications from the lab in the field of wireless localization have been BLoc, LocAP, DLoc and more. Notably, algorithms framed by BLoc have also been adopted in the Bluetooth standards in order to obtain fine-grained localization. Feel free to browse our [lab webpage]((https://wcsng.ucsd.edu)) to know more about our lab. 
 -->
<div class="divider"></div>

<h4> Notabale related projects: </h4>

<div class="sp" >
<div class="left50">
<img src="{{site.baseurl}}/assets/res/traceTog.png" class="center"/>
</div>
<div class="right50">
<h4> <a href="https://www.tracetogether.gov.sg/">TraceTogether</a></h4>
<p>TraceTogether is the first project to have a nationwide release (in Singapore). They have also open-sourced their code for the research communities benefit, and our the closest app to BluBLE. TraceTogether utilizes manual experiments to be done in controlled environments (anechoic chambers which give vacuum like propoagation of wireless signals) to infer distance from bluetooth signals. At BluBLE, we are trying to automate this process by doing crowdsourced data collection.  </p>
</div>
</div>

<div class="divider"></div>

<div class="sp" >
<div class="left50">
<img src="{{site.baseurl}}/assets/res/appG.png" class="center"/>
</div>
<div class="right50">
<h4> <a href="https://www.apple.com/covid19/contacttracing"> Apple+Google's upcoming project</a> </h4>
<p>Apple and Google have started working on building an API which supports and eases the development of such apps, and they are not making an app of their own. This is very good news for BluBLE, since this allows us to utilize the existing codebase and API calls given by Apple and Google to use them for accurate risk and distance classification.</p>
</div>
</div>

<div class="divider"></div>

<div class="sp" >
<div class="left50">
<img src="{{site.baseurl}}/assets/res/safepath.png" class="center"/>
</div>
<div class="right50">
<h4> <a href="https://safepaths.mit.edu/">MIT SafePaths</a></h4>
<p>MIT Safepaths have been leading the efforts on the GPS front, instead of focussing on Bluetooth technology to determine proximity. They have come up with awesome algorithms which keep your location data private and inaccessible, at the same time allowing authorized healthcare bodies to use this to infer the spread of the disease.</p>
</div>
</div>

<div class="divider"></div>

<div class="sp" >
<div class="left50">
<img src="{{site.baseurl}}/assets/res/cwatch.png" class="center"/>
</div>
<div class="right50">
<h4> <a href="https://www.covid-watch.org/">COVID-watch</a> </h4>
<p>COVID-watch is an initiative by Stanford, and they have designed protocols to keep the exchanges happening between bluetooth devices private and secure. Theire algorithms and protocols, have been proposed to be utilized by Apple+Google in their upcoming projects as well.</p>
</div>
</div>


<div class="divider"></div>


<style>

@media screen and (min-width: 601px) {
  h4 {
    font-size:22px;
    font-family: Ariel, sans-serif;
  }
  p {
    font-size:18px;
    font-family: Roboto, sans-serif;
  }
  li {
    font-size:18px;
    font-family: Roboto, sans-serif;
  }
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
.sp{
width: 100%; clear:both;  display: flex; align-items: center; padding-bottom: 20px;
}
.sp .left50{
width: 20%; float:left;
}
.sp .right50{
width: 80%; float:right;
}
.sp .left50 img{
  max-width:1648px; max-height:2136px; width:auto; height:120px;
}
/*.cw{
width: 100%; clear:both;  display: flex; align-items: center; padding-bottom: 20px;
}
.cw .left50{
width: 20%; float:left;
}
.cw .right50{
width: 80%; float:right;
}
.cw .left50 img{
  max-width:1648px; max-height:2136px; width:auto; height:150px;
}
.tt{
width: 100%; clear:both;  display: flex; align-items: center; padding-bottom: 20px;
}
.tt .left50{
width: 20%; float:left;
}
.tt .right50{
width: 80%; float:right;
}
.tt .left50 img{
  max-width:1648px; max-height:2136px; width:auto; height:150px;
}*/


  h5 {
  font-size:20px;
  font-family: Ariel, sans-serif;
  }
}
/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  h4 {
    font-size:6vw;
    font-family: Roboto, sans-serif;
  }
  p {
    font-size:3.5vw;
    font-family: Roboto, sans-serif;
  }
  li {
    font-size:3.5vw;
    font-family: Roboto, sans-serif;
  }
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;
  }
  h5 {
  font-size:5vw;
  font-family: Roboto, sans-serif;
  }

.sp{
width: 100%; clear:both;  display: flex; align-items: center; padding-bottom: 20px;
}
.sp .left50{
width: 50%; float:left;
}
.sp .right50{
width: 50%; float:right;
}


}

</style>