
<p align="center"><a href="https://Drasthi&Jay.netlify.app/"><img src="./assets/wedding.gif" width="150px" height="150px"/></a></p>
<h1 align="center"><a href="https://Drasthi&Jay.netlify.app/">Wedding Invitation</a> :ring: <br> <br> SAVE THE DATE: NOV 21, 2021 <br> <a href="https://Drasthi&Jay.netlify.app/">Drasthi&Jay.netlify.app</a></h1>

 [![GitHub license](https://img.shields.io/github/license/vinitshahdeo/Wedding-Invitation?logo=github)](https://github.com/vinitshahdeo/Wedding-Invitation)

## Wedding Invitation :ring:

<details>
  <summary><strong>View Invitation</strong></summary>
  <a href="https://Drasthi&Jay.netlify.app/"><img src="./assets/img/Drasthi&Jay.jpeg" /></a>
</details>

With the divine grace of the almighty,
inviting you and your family to Jay & Drasthi wedding to be held on **21st November at [Nokha](https://goo.gl/maps/5z5xX2hTYzU8VGEJ9) from 7:00 PM** onwards.

- [Download](https://github.com/vinitshahdeo/vinitshahdeo/raw/master/docs/Sonali%20%26%20Gagan.pdf) the Invitation card

- Find [venue](https://goo.gl/maps/5z5xX2hTYzU8VGEJ9) on Google map

- Visit the [website](https://sonali.netlify.app/) for more details

```js

const newCouple = 'Drasthi & Jay';

// Nov 29, 2020
const weddingDate = new Date(2021, 11, 21);

// Wedding venue: https://goo.gl/maps/5z5xX2hTYzU8VGEJ9
const weddingVenue = new Location('Nokha');

(function() {
    newCouple.willTieKnot(weddingDate);

    // your presence is requested
    (new Wedding()).acceptInvitation(
        window.open('https://sonali.netlify.app/')
    );
})();


```

## Are you or your loved ones a *bride-to-be* or *groom-to-be*? 
> Feel free to use this template to build your wedding website!

To reuse this, follow the steps:

- *Replace the date in [script.js](https://github.com/vinitshahdeo/Wedding-Invitation/blob/master/js/script.js#L29) to have a timer running for your big day!*

```js
// Set the date we're counting down to
var countDownDate = new Date("Nov 21, 2021 00:00:00").getTime();
```

- *If you wish to change the track which plays on click, edit the `src` in [index.html](https://github.com/vinitshahdeo/Wedding-Invitation/blob/760c4aa437115fc365f5cb86a4b428b0e292b5ba/index.html#L69)*

```html
<div class="music">
   <audio src="./assets/mp3/song.mp3" id="my_audio" loop="loop"></audio> 
</div>
```

> <sup>Despite so many new Bollywood and English song options, I prefered to use two-decade-old song, **[Din Shagna Da](https://youtu.be/X0MDALpV29s)**! Ever attended a North Indian Wedding? As soon as the DJ plays [Din Shagna Da](https://youtu.be/Mj4eK5YViCs) song, it means that the much-awaited moment is here and the bride is all set to put her first foot forward to the wedding venue under a breathtaking phoolon ki chaadar. Let's keep the sky-high status of this song untouched! When the website is backed up with a soul-stirring track, the feeling becomes absolutely surreal. **Choose a heart-touching track!** :musical_note: :heart: </sup>



