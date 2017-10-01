---
layout: page
title: About
subtitle: Not a Cult
permalink: /about/
comments: false
author_footer: false
---
Born across the globe, seven diverse and unique individuals were summoned together by pheromones and mystical forces to become Colin.
The Colin Collective has a wide spectrum of backgrounds, from acting to computer science to juggling to transportation logistics. 
Members are involved in additional improv groups, including Comedy City, Kansas City Improv Company, Babies, and That’s No Movie.

Based out of Kansas City, The Colin Collective has been performing long form improvisation and being generally silly since 2015.
The Colin Collective can be seen regularly at the Kick Comedy theater and America's Improv Test Kitchen.
They have performed at the Kansas City, Denver, New York City, and Omaha Improv Festivals, as well as the Del Close Marathon.

Interested in having us perform? Would you like to be coached by up to seven people? Do you want to just say hello and send pictures of your cat? Contact us at [thecolincollective@gmail.com](mailto:thecolincollective@gmail.com).

{% capture images %}
    {% for photo in site.data.photos %}
    /assets/img/{{ photo.path }}
    {% endfor %}
{% endcapture %}
{% include gallery images=images caption="Kansas City Improv Festival 2016" cols=3 %}
