---
layout: page
title: About/Sign up
---

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}

* TOC
{:toc}

To registrer
---------------

To register, sign up on the [facebook event](https://www.facebook.com/events/839646426173282).


Time
------------

For the schedule go [here]({{ site.baseurl }}/{{ page.eventpath }}/schedule.html)


Venue
----------

The event is at EAL campus at seebladsgade 1, 5000 Odense C.

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2265.3951633205165!2d10.377145315917003!3d55.40345798046134!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464cdffce26d61f5%3A0xb3c45d391e70236f!2sSeebladsgade+1%2C+5000+Odense+C!5e0!3m2!1sen!2sdk!4v1476866186128" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

We meet in room B2.48

The door will be open in the daytime, and students will have all-time access using their tokens or student cards. We will arrange for a phone number to call, if the door is locked.

Please note that the windows must be kept closed throughout the weeked. This is an alarm thing, and the guards don't like to be called unneccesarily.


Transportation and parking (!)
------------

{% include transportation.html %}


Food and accomodation
---------------------

There are supermarket in the vicinity, and vending machines for coffe.

Media
---------

We have logos and posters [here]({{ site.baseurl }}/media).
