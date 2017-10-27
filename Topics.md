**You have a topic?**

If you have an idea for a topic you want to pitch and work on at the BaselHack 2017, you can add it here. It is optional to publish them beforehand, you can also just pitch them on Saturday morning. By publishing it here, you give other participants the possibility to already get familiar with it.

To give you an idea on how such a topic could look like, we prepared one: [nearest-free-BS-parking-space](#template-for-a-topic-description-nearest-free-bs-parking-space)

Just add your topic to the end of this page.

**Need some inspiration?**

* Local Data for Local Applications:
  *  **https://github.com/BaselHack/BaselHack2017/tree/master/data**


_**Disclaimer**_: if you have trouble editing this site, please send your proposal to info@baselhack.ch

***

### template for a topic description "nearest-free-BS-parking-space"
**Problem:**
The search for available parking space frequently wastes time and resources, if required to enter densely constructed areas by car.

**Data resources:**
The city of Basel provides real-time information on the occupation of the majority of the public and private parking buildings via [RSS-feeds](http://www.parkleitsystem-basel.ch/rss_feed.php).
    
**proposed hack topic:**
We propose to incorporate this information into a mobile routing app (eg https://developers.google.com/maps/documentation/directions/intro?hl=en) to guide users to the closest available parking space, including information on parking fees, and permitted duration of occupation. An additional innovative aspect is a proof-of-concept inclusion of open space parking. The topic includes the ad-hoc monitoring of selected parking spots with IoT-enabled smart parking sensor (eg https://www.pnicorp.com/placepod/ ) and their integration into a LoRaWAN network.

***

## Time-based prevoyance as the fourth pillar of old-age provision

### Pitch
Over the next 30 years, Switzerland will face up to 50% more pensioners [1]. The institutions and funds for old-age provision (AVH, BVG, 3rd pillar) and the healthcare sector are increasingly under financial stress. To counter this trend, several associations have been established in Switzerland to offer a voluntary, time-based 4th pillar [2]: retirees can collect time credits in the "younger" years during which they take care of elderly retirees (e.g. go shopping, take them for a walk, etc.). Later, once they themselves are dependent on help, they can redeem the collected time credits at local associations. This time-based prevoyance provides financial relief for old-aged provision, promotes intergenerational justice, and helps elderly staying in their homes longer.

### Goal at the BaselHack
Develop a system to make time-keeping efficient, and allow the participating associations to easily manage time credits. We aim to deliver a proof-of-concept solution for creating, managing, and redeeming time credits. To avoid fraud, important pieces of metadata relating to the time credits will be stored in a blockchain / wallet.

### References
1. Federal Office for Statistics. Scenarios for the population development of the cantons of Switzerland 2015-2045. http://bit.ly/2xyWCkn
2. Association KISS Switzerland. Time prevoyance as a supplement to pension funds. http://bit.ly/2xyQuZG

***
## For safety and more efficient traffic in Basel
**Problem:**
In Basel, the traffic situation is getting worse and worse every year. By means of a targeted evaluation of the traffic data, the traffic flow of the city can be optimized.

**Data resources:**
The city of Basel provides Radar data from more than 300 Streets. How many cars and other vehicles passed in which speed. How high is the transgression rate of each street? In which streets is the tendency to drive too fast? Which are the busiest and most dangerous streets in the City?

**proposed hack topic:**
There are different approaches. On one hand it is interesting to show the traffic situation graphically (for example categorisation of streets) and enable the inhabitants to choose a better route (kind of self-regulation). On the other hand, it is possible to improve the cantonal processes with software so that traffic can be better distributed through the city. More information at saturday :)

## BaselStat - An Open Data Search Engine
 
Nowadays, an enormous amount of data is generated every day. Unfortunately, this data is mostly available on different sources and stored in different file formats.
 
 
We would like to create our own open data search engine with all available statistical data from the Kanton Basel Stadt.
Thus, the exploration of these records should become easy and intuitive, as if one would be googeling any topic.
 
 
The public API would allow other developers to create their own applications. Of course our frontend also retrieves its data from the public API.
 
 
Additionally to our Web Application we would like to create a visualisation by using the Microsoft HoloLens.
 

Team:
* Denise Bauman
* Fabrizio Parrillo
* Quentin Garnier
* ... you?  Join our team and clone the [repo](https://github.com/FUUbi/BaselStat).
***

### They Live AR
**Problem:**
“The System” is turning our brains to mush with an overload of branding, advertisements and information in the public space. Can technology save us?
https://www.youtube.com/watch?v=JI8AMRbqY6w

**Proposed hack topic:**
An ad-blocker for the real world. Create a mobile AR app or webpage which detects “information” such as text or branding and blocks it out.
(Or replace the information with alternative messages or art.)

**Tech resources:**
* Android vision API: https://developers.google.com/vision/text-overview
* Chrome text API: https://paul.kinlan.me/detecting-text-in-an-image/
* Tesseract: http://tesseract.projectnaptha.com/
* Browser OCR: https://kdzwinel.github.io/JS-OCR-demo/
* Browser based tracking: https://trackingjs.com/

**Prior art:**
* https://www.wired.com/2015/01/adblock-real-life-adblock-real-life/
* https://creators.vice.com/en_us/article/3d5bg3/this-augmented-reality-app-blocks-advertisements-with-digital-art

***

### Chat Visualiser
**Problem:**
Chat is utterly useless without a visualiser.

;)

  
**Proposed hack topic:**
An “online chat” web application that creates a realtime visual experience based on the contents of the chat. The app retrieves (hopefully) relevant images, videos, webpages, maps, emoticons, icons, or other content and displays them in a “visualiser panel” adjacent to the chat space.
(Maybe the core of the system could be used in other contexts than chat, such as live performance.)

**Data resources:**
Any Content API, such as...
* OpenGLAM: https://opendata.swiss/de/organization/openglam?res_format=HTML
* https://www.flickr.com/services/api/explore/flickr.photos.search
* https://developers.google.com/youtube/v3/docs/search/list#try-it
* https://unsplash.com/developers
* https://www.pexels.com/api/
* https://www.pond5.com/free
  

***
-> complement with YOUR ideas: ...