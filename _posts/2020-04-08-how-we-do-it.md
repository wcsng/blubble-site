---
layout: post
title:  "What sets us apart?"
date:   2020-04-08 00:50:13
---
<p> At heart of our approach, lies the algorithm which classifies how far you are by observing the signal strength of the bluetooth signal. On an intuitive level, this works similar to what you experience with Wi-Fi, as you move closer to the AP, the Wi-Fi signal strength increases, and you see more bars in the Wi-Fi logo. Similarly, if two bluetooth devices are close, they will have a higher signal strength, which slowly decreases as you go far apart. However, this is distance classification is easier said than done. </p>

<p>
The problem with mapping signal strength to distance is that this mapping depends on a number of factors, like exact phone model of TX-RX, the environment itself, and even if you have placed the phone in your pocket or it is in your hand. To account for these factors, our approach is to gather crowdsourced data and build novel classification algorithms on top of this to very precisely classify if someone is within 6 ft to you, by observing the signal strength. Please checkout our <a href="https://wcsng.github.io/blubble-site/categories">Data Collection</a> page to help us out by contributing to the project.
</p>

<style>

@media screen and (min-width: 601px) {
  h4 {
    font-size:1.3vw;
    font-family: Ariel, sans-serif;
  }
  p {
    font-size:0.95vw;
    font-family: Roboto, sans-serif;
  }
  li {
    font-size:0.95vw;
    font-family: Roboto, sans-serif;
  }
  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
/*  h5 {
  font-size:0.95vw;
  font-family: Ariel, sans-serif;
  }*/

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