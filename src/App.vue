<template>
<!--  <iframe width="1" height="1" src="https://www.youtube.com/embed/L4_1WtqPPpE?autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
  <audio src="https://s3.ap-northeast-2.amazonaws.com/yoursnow.online/merry.mp3"></audio>
</template>
<script>

import 'particles.js/particles';
const particlesJS = window.particlesJS;
export default {
  name: 'App',
  created() {
    particlesJS("particles-js", {
      "particles": {
        "number": {
          "value": 200,
          "density": {
            "enable": true,
            "value_area": 800
          }
        },
        "color": {
          "value": "#ffffff"
        },
        "shape": {
          "type": "circle",
          "stroke": {
            "width": 0,
            "color": "#fff"
          },
          "polygon": {
            "nb_sides": 5
          },
          "image": {
            "src": "http://www.dynamicdigital.us/wp-content/uploads/2013/02/starburst_white_300_drop_2.png",
            "width": 100,
            "height": 100
          }
        },
        "opacity": {
          "value": 0.5,
          "random": true,
          "anim": {
            "enable": false,
            "speed": 1,
            "opacity_min": 0.1,
            "sync": false
          }
        },
        "size": {
          "value": 12,
          "random": true,
          "anim": {
            "enable": false,
            "speed": 20,
            "size_min": 0.1,
            "sync": false
          }
        },
        "line_linked": {
          "enable": false,
          "distance": 50,
          "color": "#ffffff",
          "opacity": 0.6,
          "width": 1
        },
        "move": {
          "enable": true,
          "speed": 2,
          "direction": "bottom",
          "random": true,
          "straight": false,
          "out_mode": "out",
          "bounce": false,
          "attract": {
            "enable": true,
            "rotateX": 600,
            "rotateY": 1200
          }
        }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": {
          "onhover": {
            "enable": true,
            "mode":  "bubble"
          },
          "onclick": {
            "enable": true,
            "mode": "repulse"
          },
          "resize": true
        },
        "modes": {
          "grab": {
            "distance": 150,
            "line_linked": {
              "opacity": 1
            }
          },
          "bubble": {
            "distance": 200,
            "size": 7,
            "duration": 2,
            "opacity": 8,
            "speed": 3
          },
          "repulse": {
            "distance": 250,
            "duration": 0.2
          },
          "push": {
            "particles_nb": 4
          },
          "remove": {
            "particles_nb": 2
          }
        }
      },
      "retina_detect": true
    });
  }
}
</script>

<style>
#particles-js {
  /*position: absolute;*/
  /*width: 100%;*/
  /*height: 50%;*/
  height: 100vh;
  /*background: linear-gradient(to bottom, rgba(117, 114, 113, 0.8) 10%, rgba(40, 49, 77, 0.8) 30%, rgba(29, 35, 71, 0.8) 50%, rgba(19, 25, 28, 0.8) 80%, rgba(15, 14, 14, .8) 100%), url(https://yoursnowbucket2.s3.ap-northeast-2.amazonaws.com/card.PNG);*/
  background: url(https://s3.ap-northeast-2.amazonaws.com/yoursnow.online/whatIfSnowFinal.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  /*background-position: 50% 50%;*/
}
</style>
