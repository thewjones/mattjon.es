---
date: 2020-04-22T13:00:00Z
tags:
- Community
- Health
- Neighbourliness
resources:
- name: moon
  src: crescent-shaped-earth-and-moon.jpg
- name: minimoog
  src: minimoog.jpg
- name: freeway
  src: US-freeway-pollution.jpg
title: Link Notes 22 April 2020
---

{{< imgproc
    name="moon"
    command="Fill"
    options="800x1000"
    imageCaption="A crescent-shaped Earth and Moon recorded by Voyager 1 in 1977 - the first photo of its kind ever taken by a spacecraft"
    imageAttrib="NASA"
    imageLicense="CCO"
    imageURL="https://images.nasa.gov/details-PIA01967"
    licenseURL="https://creativecommons.org/share-your-work/public-domain/cc0/">}}

## Today's links

Today is [Earth Day](https://en.wikipedia.org/wiki/Earth_Day) 2020, so today's links have an environmental theme. Also&hellip; synthesisers. 

<!-- * [Using a 1930 Teletype as a Linux Terminal](/blog/links/2020/04/21#using-a-1930-teletype-as-a-linux-terminal): Using 1930s tech to operate a modern computer. -->

<!--more-->

---

### Rising CO2 causes more than a climate crisis — it may directly harm our ability to think

https://phys.org/news/2020-04-co2-climate-crisisit-ability.html

This is an aspect of rising atmospheric CO2 that rarely gets talked about compared to the impact of global temperature rise. 

Before the [Industrial Revolution](https://en.wikipedia.org/wiki/Industrial_Revolution), the global average CO2 concentration in the atmosphere was around 280 ppm. Scientists consider 400 and 1000 ppm a normal levels for indoor concentration of CO2, with the higher levels of this indoor range being the point at which we may start to feel the need to go outside for fresh air.

The current global average CO2 concentration is over 400 ppm, with the projection - if we do nothing to lower CO2 emissions - of over 900 ppm by 2100. This could make average indoor CO2 level pretty uncomfortable and affect our ability to think in indoor spaces with poor air flow.

---

{{< imgproc
    name="freeway"
    command="Fill"
    options="800x600"
    imageAttrib="The U.S. National Archives"
    imageLicense="CCO"
    imageURL="https://picryl.com/media/environmental-images-water-treatment-plant-vegetables-sculptures-air-pollution-1b721e"
    licenseURL="https://creativecommons.org/share-your-work/public-domain/cc0/">}}


### Air pollution may be ‘key contributor’ to Covid-19 deaths – study

https://www.theguardian.com/environment/2020/apr/20/air-pollution-may-be-key-contributor-to-covid-19-deaths-study

Since the Chinese government has eased lockdown restrictions, the country has seen a drop in the use of public transport and a rise in the use of private cars (comparative to before the outbreak). In the UK, with pressure to restart the economy, major cities are postponing plans to introduce [Clean Air Zones](https://en.wikipedia.org/wiki/Clean_Air_Zone) and congestion charges with the view that people will be avoiding public transport and instead use cars to travel into the city-centres.

Given the nature of this respiratory disease and its impact on the global population, when the lockdown restrictions start easing up in the UK it seems entirely inappropriate for everyone to go back to their diesel and petrol powered cars for urban transport.

Transport isn't a binary choice between public transport and the private car. Cycling and walking are viable transport and travel solutions for people living in towns and cities, and this includes disabled people who use bicycles and adapted cycles as mobility aids. There needs to be massive UK wide investment in enabling this.

---

### How you can help plot the future of UK walking – from a standstill

https://www.nationalgeographic.co.uk/environment-and-conservation/2020/04/how-you-can-help-plot-future-of-uk-walking-standstill

[Slow Ways](https://ravenellison.com/portfolio/slow-ways/) is a project to plot over 4000 walking routes linking every UK village, town and city. 

The road network we have developed mainly for car travel distorts our perception of distance between places. In the same way the [tube map](https://en.wikipedia.org/wiki/Tube_map) can exaggerate the distance between places in London (it's usually quicker to walk between two stations on the same line), settlements in the UK are often closer together than we think they are.

I spend time mandating cycling and campaigning for better cycle routes, but this seems like a quick win in terms of routes for walking, given the footpaths already exist.

---


### Sidewalk Widths NYC

http://www.sidewalkwidths.nyc/

This is a data visualisation of pavement widths in New York City which is an important tool for New Yorkers' and the authorities there to understand where people can and can't walk and still follow social distancing rules.

The first thing that struck me about this is that it's an impressive authority that a) has the data on pavement width and b) releases it into the public domain.

---

### Helm software synthesizer

{{< imgproc
    name="minimoog"
    command="Resize"
    options="1200x"
    imageCaption="Minimoog synthesizer from the early 1970s"
    imageAttrib="Wikimedia Commons"
    imageLicense="CCO"
    imageURL="https://commons.wikimedia.org/wiki/File:Minimoog.JPG"
    licenseURL="https://creativecommons.org/share-your-work/public-domain/cc0/">}}

https://tytel.org/helm

I've recently starting to produce and perform electronic music mainly using software written under the GNU Free Software license. My setup uses a number of pieces of software working together, a combination of step sequencers and arpeggiators to trigger notes together with synth software that is generating the sounds. One of my favourite pieces of sound-generating software is [Helm](https://tytel.org/helm/), written by Matt Tytel. 

The theory of sound synthesis has always been a bit baffling to me. If you've ever seen an early [Moog synthesiser](https://en.wikipedia.org/wiki/Moog_synthesizer) you'll notice they have a complex set of control knobs, switches and patch cables above the keyboard, making the prospect of learning how to play them seem daunting.

As I've learned, behind this apparent complexity lies a relative simplicty in terms of what these controllers are doing. Sound is a wave, so there are controllers for changing the shape of the wave. A sound happens over a period of time and may change during this time; this is an 'envelope', and there are controller for changing its parameters, known as attack, decay, sustain and release. The keyboard keys change the pitch of the envelope, and other controllers apply effects and filters to this envelope to change the sound further.

I've learned all this pretty much just using Helm, and this is because it doesn't employ a [skeuomorphic interface](https://en.wikipedia.org/wiki/Skeuomorph). In other words, it doesn't try and mimic a real synthesiser's control knobs. Instead it provides a graphical representation of what the controllers do, which makes much more sense when translating the actions of physical controllers to a two-dimensional user interface, and makes learning sound synthesis much easier.
