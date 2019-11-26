---
layout: page
title: Contact
sidebar_link: true
---

<form action="https://formspree.io/mikenw@hotmail.co.uk" method="POST">
    <input class="left" type="text" name="name" placeholder="Your name..">
    <input class="left" type="email" name="email" placeholder="Your email..">
        <br/>
        <br/>
    <textarea class="left" type="text" name="message" placeholder="Your message.."></textarea>
        <br/>
        <br/>
        <input type="submit" value="Send" class="right">
</form>
<div class="flex-container flex-container-center">
    <a href="https://www.facebook.com/mikeywotton" target="_blank">
        <img src="{{ site.baseurl }}/assets/css/icon/facebook.svg" height="60" width="60" class="center" alt="Facebook Logo">
    </a>
    <a href="https://github.com/mikey-wotton" target="_blank">
        <img src="{{ site.baseurl }}/assets/css/icon/github.svg" height="60" width="60" class="center" alt="github Logo">
    </a>
    <a href="mailto:mikenw@hotmail.co.uk">
        <img src="{{ site.baseurl }}/assets/css/icon/gmail.svg" height="60" width="60" class="center" alt="Email Logo">
    </a>
    <br>
    <a href="https://linkedin.com/in/mikey-wotton" target="_blank">
        <img src="{{ site.baseurl }}/assets/css/icon/linkedin.svg" height="60" width="60" class="center" alt="linkedin Logo">
    </a>
    <a href="https://api.whatsapp.com/send?phone=447943624891&text=Hi%20Mike" target="_blank">
        <img src="{{ site.baseurl }}/assets/css/icon/whatsapp.svg" height="60" width="60" class="center" alt="whatsapp Logo">
    </a>
</div>
<div id="map"></div>
<script>
    var map;
    function initMap() {
        var myLatLng ={lat: 51.458435, lng: -0.971466};
    map = new google.maps.Map(document.getElementById('map'), {
        center: myLatLng,
        zoom: 12
    });
      var marker = new google.maps.Marker({
    position: myLatLng,
    map: map,
    title: 'Mike lives here'
    });
    }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAd-Q7Y19ex5EkzjpaKF7kSNxBip_Scxc8&callback=initMap"
async defer></script>
