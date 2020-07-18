---
layout: post
title:  "Whats App budy - Ralph"
date:   2020-05-03 
categories: [projects]
tags: twilio whatsapp ruby gems nasa chatbot bot
published: true
---
I have always wanted to make a chatbot and luckily I found a helpful guide on using Twilio with WhatsApp and getting the weather forecast by sending a location.  After some initial struggles setting up the ruby environment and installing all the required gems for the project on my windows machine, I was ready to start.  

Thanks to the tutorial I found online, I was able to get the ruby program running with only little syntax modifications and my little bot was connected to twillio and responding to messages. However, I shortly discovered the API used to fetch the weather data was no longer offered for free so I substituted it with a weather API provided by openweathermap.org, and with it, I was able to get a nice weather response as well as the sky condition. 

![using shared location](/assets/images/location.JPEG# standard)

Being the easily distracted person I am, during the process of looking for a new weather API I discovered a few other fascinating API. One such is the A Photo A Day project by NASA. This free API provided by NASA when called returns the photo of the day of outer space and a description of it. I was fascinated by these wonderful photos so I added it in as sort of an easter egg. 

![with keyword nasa](/assets/images/nasa.JPEG# standard)

See the project <a href="https://github.com/TheTh1rd/ruby-whatsapp-bots">here.</a>
