---
layout: page
title: About
subtitle: Not a Cult
permalink: /about/
comments: false
author_footer: false
---
Experimenters and dabblers: The Colin Collective taps unusual inspiration and explores new realms. Born across the globe, eight diverse and unique individuals were summoned together by pheromones and mystical forces to become Colin. We excel in experimenting with original formats and dare to play big. Based out of Kansas City, The Colin Collective has been performing long form improvisation and being generally silly since 2015.

Members of The Colin Collective have a wide spectrum of backgrounds, from acting to computer science to juggling to transportation logistics. Most are involved in additional improv groups, including Comedy City, Kansas City Improv Company, Babies, and That’s No Movie. The Colin Collective can be seen regularly at the Kick Comedy theater and has made appearances at the Kansas City Improv Festival, the Denver Improv Festival, and the New York City Improv Festival.

Interested in having us perform? Would you like to be coached by up to eight people? Do you want to just say hello and send pictures of your cat? Contact us at [thecolincollective@gmail.com](mailto:thecolincollective@gmail.com).

{% capture images %}
    {% for photo in site.data.photos %}
    /assets/img/{{ photo.path }}
    {% endfor %}
{% endcapture %}
{% include gallery images=images caption="Kansas City Improv Festival 2016" cols=3 %}
