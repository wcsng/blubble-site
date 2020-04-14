---
layout: post
title:  "What sets us apart?"
date:   2020-04-08 00:50:13
excerpt_separator: <!--more-->
---
<p>We are currently developing a robust and environment-agnostic algorithm to quantify the effectiveness of social distancing. Our aim is to automate the tedious process of contact tracing to help combat COVID-19, which involves tracking the activities of a diagnosed patient and generating a network of interaction of this patient with others. But here, we do things <b>a bit differently</b> --  <!--more--> 
instead of assigning a binary value to each interaction as a potential contact or not, we develop a spectrum of risk score to characterize each interaction. </p>

<p>We do this risk profiling by inferring the distance between two persons, by harnessing myriad of wireless signals like Bluetooth, Wi-Fi etc. Our research group is uniquely positioned to develop this system. We have built <a href="https://wcsng.ucsd.edu/localization.html">world-class algorithms</a> and are leading the development for wireless based localization and proximity detection.</p> 

<p>COVID-19 has been a rapidly evolving pandemic and owing to its two week incubation period and high communicability, it has infected over 1.5 million people in a matter of 4 months. Various international health agencies have touted the merits of social distancing, and in states like California and New York, strict quarantine measures have resulted in a decline of new cases. Yet, experts argue that this social distancing is not nearly enough. To again open up our streets and public spaces, we need to be able to have:</p>
<ul>
<li>A <em>ubiquitous</em> system that alerts you if someone accidentally comes closer than 6 ft to you or warns about specific indoor spaces which have a higher likelihood of COVID-19 </li>
<li>A <em>dynamic system</em> which can inform specific vulnerable individuals to self-quarantine; </li>
<li>A <em>private and voluntary</em> system which will effectively anonymize contact tracking. </li>
<li>A system to <em>understand</em> how this disease spreads;</li>
</ul>

<p>Using the wireless signals broadcasted by your smartphone (Bluetooth/WiFi signals broadcasted from your phone), we classify the distance to others in your surroundings and build a graph of connections. This <em>dynamic</em> graph will be updated every time you come close to another person and warns you if necessary, and also can effectively track the spread of the disease.  We will utilize unique and anonymous identifiers to track each person within our ecosystem. In other words, we <b>do not collect</b> any personal information about you. We only know you as an unique individual in our ecosystem characterized by an arbitrary identifier, but we do not know who you are, hence providing <em>privacy</em>. Furthermore, this system is <em>voluntary</em>, and you will not be tracked if you do not install our application. Finally, we have developed our platform to work on both Android and iOS devices, so that it can be deployed <em>ubiquitously</em>. </p>

<p>Please checkout our <a href="{{site.baseurl}}/categories.html">Data Collection page</a> to help us in making our project a great success</p>

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
  h5 {
  font-size:20px;
  font-family: Ariel, sans-serif;
  }
}

/* If the screen size is 600px wide or less, set the font-size of <div> to 30px */
@media screen and (max-width: 600px) {
  h4 {
    font-size:6vw;
    font-family: Ariel, sans-serif;
  }
  p {
    font-size:4vw;
    font-family: Roboto, sans-serif;
  }
  li {
    font-size:4vw;
    font-family: Roboto, sans-serif;
  }
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;
  }

  /*h5 {
  font-size:4vw;
  font-family: Ariel, sans-serif;
  }*/
}

</style>