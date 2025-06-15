---
title: "BLEMORE"
weight: 0
description: "The Workshop and Competition on Multimodal Blended Emotion Recognition"

# 1. To ensure Netlify triggers a build on our exampleSite instance, we need to change a file in the exampleSite directory.
theme_version: '2.8.2'
cascade:
  featured_image: 'images/banner_large.png'
menu:
  main:
    weight: 1
    name: "Home"
---
The BLEMORE workshop and competition on multimodal blended emotion recognition will be held at the 13th International Conference on Affective Computing and Intelligent Interaction (ACII 2025) in Canberra, Australia.
BLEMORE aims to inspire further development on the still under-represented topic of blended emotion recognition. By combining a competition with a workshop format, our hope is that BLEMORE will lead to concrete and measurable technical advances, while also providing a forum for reflection and exchange between researchers working in the field.
The workshop will take place on the 11th of October 2025.


## Mailing list
To stay up-to-date, please sign up to our mailing list here: https://www.dfki.de/mailman/cgi-bin/listinfo/blemore-workshop.\
Please be aware that you need to confirm your list membership via email. We will distribute any news and future developments regarding the workshop (e.g., clarification of the challenge rules if there are any uncertainties) via the mailing list.

# News

## Test Dataset Released (2025-06-15)

We’ve now published the test partition of the BlEmoRe dataset on [Zenodo](https://zenodo.org/records/15668840).
The new Zenodo version includes a set of test videos and a [submission_template.json](/submission_template.json) file.

Participants are invited to submit their predictions in the template format to: Petri Laukka: petri.laukka@psyk.uu.se

We will evaluate them on our server. The evaluation will be based on the two metrics defined in the challenge: `ACC_presence` and `ACC_salience`.

## New Baselines Released (2025-06-09)

New baselines for the BLEMORE Challenge are now available.

The baselines include models using features extracted from pre-trained video and image encoders:
- **CLIP**
- **ImageBind**
- **VideoMAEv2**
- **Video Swin Transformer**

Features are either aggregated into video-level representations or subsampled from short clips. Lightweight feedforward models (Linear, MLP) are trained to predict emotion presence and salience following the challenge evaluation protocol.

Code and instructions are available in the updated [GitHub repository](https://github.com/BlEmoRe/blemore-common).


## Paper Submission (2025-06-09)
Submissions to the BLEMORE Workshop are now open!  
Please use the following link to submit your paper:

[Submit via EasyChair](https://easychair.org/conferences?conf=blemoreworkshopacii2)

**1. General Track:** We invite submissions concerned with the general problem of blended emotion recognition.

**2. Challenge Track:** In this track, we invite submissions which utilize the challenge dataset and pre-defined evaluation metrics. 

See the [Call for Papers](https://blemore.github.io/workshop/call-for-papers/) for more details.

## Basic Code for Baselines released (2025-04-08)
Available on [GitHub](https://github.com/BlEmoRe/blemore-common).

## Call for Papers released (2025-04-08)
The call for papers for the BLEMORE workshop and competition is now available: [Call for Papers](https://blemore.github.io/workshop/call-for-papers/)

## Training dataset released (2025-03-27)
The training dataset for the BLEMORE  workshop and competition is now available on [Zenodo](https://zenodo.org/records/15096942). 
Please feel free to contact us in case of any question concerning the dataset: petri.laukka@psyk.uu.se


[//]: # (#### Acknowledgements)

[//]: # (The EmoRec EEG workshop is organized by the Horizon Europe  project GAIN funded by the European Union &#40;GA no.101078950&#41;.)

[//]: # ()
[//]: # ([![Alt text]&#40;https://i.postimg.cc/TP4PPzcN/EU-flag-Horizon-Europe-2.jpg&#41;]&#40;https://research-and-innovation.ec.europa.eu/funding/funding-opportunities/funding-programmes-and-open-calls/horizon-europe_en&#41;)

[//]: # ([![Alt text]&#40;https://i.postimg.cc/J0V8SM1J/gain-logo-4.png&#41;]&#40;https://micm.edu.ge/en/&#41;)
