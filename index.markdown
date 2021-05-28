---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Nami
---

![Sara and Nami](/assets/images/sara_nami_trumpet.jpeg)

### Nami is a custom built glove interface designed for cross-cultural musical exploration and performance.

<div class="words-and-video">
<p>
Nami is outfitted on the performer's (user) left hand leaving the right hand available for playing an instrument (trumpet). In real-time the performer can manage multiple controls exploring, expanding, and amplifying the trumpet sound in the left hand. 
<br>
<br>
The Japanese word “nami” means “wave.” In the musical and social context it can be interpreted as an embodiment of life experiences expressed in each musical beat that is free flowing and unrestricted by bar lines. As a designer, I want Nami to be flexible and adaptable, and for various iterations of Nami to exist that embrace a variety of cultural bodies (embodied experiences) and their respective cross-cultural gestural vocabularies.
</p>
<div style="padding:0 0 0 0;position:relative;width:100%;"><iframe src="https://player.vimeo.com/video/555581211?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Nami Demo"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
</div>

## Background
I used the Poieto Cultural AI Design Tool to ideate multiple design iterations of Nami from various socio-cultural perspectives. Poieto consists of the following 5 phases: 

### Sketching &#10142; Concept &#10142; Critical Thinking &#10142; Reflections &#10142; Implementation
{:style="text-align:center;margin: 30px 0;"}

For more details about the Cultural AI Design Tool and the design of Nami, please refer to my paper, ["Exploring Identity Through Design: A Focus on the Cultural Body Via Nami"](https://www.nime.org/proceedings/2020/nime2020_paper109.pdf) published in the proceedings of the _International Conference on New Interfaces for Musical Expression (NIME), 21-25 July 2020_.


## Sketching
During the Sketching Phase, my main focus was on the purpose of the musical interface. So why am I doing this?

### Challenge

- As a trumpet player, using guitar pedals and trumpet mutes (physical filters) are often awkward to use during a live performance and can detract from the music-making experience and only provide limited control over effects
- Many commercially available musical interfaces, DAWs, and musical notation software are culture specific in which the purpose, intent, and material reflect and privilege a particular cultural framework (i.e. Sibelius privileges the Western notation system) limiting artists outside of these culture-specific frameworks from being able to freely express themselves
- Custom interfaces, musical gear and technology can often be cost prohibitive 

### Key Goal

I wanted to develop a new interface for trumpet that allows the user to freely explore their own identity by utilizing their personal cultural body (embodied experiences and gestures) as the basis of visual (movement-based) storytelling and sound exploration in-real time.

<div class="iteration-imgs">
  <img src="/assets/images/Nami_iteration_1.JPG"/>
  <img src="/assets/images/Nami_iteration_2.5.JPG"/>
</div>

### User Profile
At first, Nami was created for myself as a trumpet player and as an interface in which I could manipulate my acoustic trumpet sound in-real time. The gestures I used would not only trigger, synthesize or otherwise control sound, but they would also tell a story. This storytelling would draw from my cultural body (embodied experiences) which are not limited to the following identity descriptors: performer, trumpet player, composer, improviser, and Nikkei (Japanese American)

### Gestures
Existing augmented trumpet interfaces have largely depended upon traditional effective gestures including valve pressing in the right hand, extending the first or third valves slides or utilizing various mutes and their accompanying gestures with the left hand. Nami is unique in that it privileges the exploration of accompanist and figurative gesture while allowing the performer access to multiple simultaneous controls. 

### Form
This is a glove interface that uses sensor technology to capture gestural data such as finger flexing and finger pressure to offer extended control and expressivity to performers through manipulation of acoustic and/or electronic sounds (for example, through signal processing or spatialization.) The output is MIDI data that can be mapped to any parameter within Ableton Live or any other DAW.

## Concept
![Poieto Concept Phase](/assets/images/poieto_concept.png)
During the Concept phase, I focused on _interaction design_ - setting up a relationship between my input and the rules, whether it was an algorithm, model or mappings. 

### Types of Mappings
I used Embodied Design Improvisation as the basis for exploring and creating a set of gestural vocabulary. This is a generative and evaluative approach to use tacit knowledge about embodied experiences. 
1. Establish various physical scenario guidelines to explore (i.e. "The user can only move in x and y directions")
2. Iterate multiple movement possibilities (i.e. What gestures can I create within these restrictions? )
3. Develop initial set of requirements to improve design (i.e. Are these the right sensors/materials to accomplish this gesture?)

## Critical Thinking: Cultural Lenses

During the Critical Thinking, I continued to iterate and developed versions of Nami through specific community and cultural lenses: 
- Little Tokyo artist community in Downtown Los Angeles through _Festival of Shadows_ utilizing movement from butoh and somatic movement practice
- Local Pasadena, Los Angeles maker community for the SupplyFrame Design Lab and CalArts AI.Culture.Creativity event and week

![Poieto Cultural Lens](/assets/images/Poieto_cultural_lense.png)

<div class="iteration-imgs">
  <img src="/assets/images/Festival_of_Shadows_1.jpg"/>
  <img src="/assets/images/supplyframe1.jpg"/>
</div>


## Reflections
Through this design process, these were some key initial questions I focused on addressing:
- Who can access it? Who can wear it? 
    - How can I create a glove that is flexible and can fit or adjust to multiple hand sizes but also be form fitting?
- Is it intuitive to use in live performance?
    - How to play with one hand? What kinds of sounds can you make utilizing one hand?
- How does this affect the body? 
    - Does this cause balance issues or tension? 
- How can the materials embody the technology?
- How does this design adapt to a variety of musicians/instrumentalists? 
- How can I make my instrument/interface relevant to other communities to give it a better chance at a longer life?

## Iterations

Various iterations tailored to user's preferences (hand size, stretch, material, etc). Each iteration has different types of sensors including hall effect sensors, force-sensitive-resistors (FSRs), flex sensors, buttons, photoresistors, and an IMU. Total cost for sensors and materials were approximately $150-200, significantly less than most commercially available musical gestural/glove controllers.

<div class="iteration-imgs-3">
  <img src="/assets/images/Nami_Iteration_2.JPG"/>
  <img src="/assets/images/Nami_Iteration_4.JPG"/>
  <img src="/assets/images/Nami_Iteration_5.JPG"/>
</div>

## Results/Implementation
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/339804376?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Nami Short Demo"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/529220765?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="An Exploration of 3 Japanese Stories"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>


## Acknowledgements
Initial iterations of Nami were created and developed during my time at CalArts in Interface Design Class led by Ajay Kapur and TA’d by Andrew Piepenbrink. Many thanks to Christine Meinders and the AI.Culture.Creativity class for their help in the development of Nami specifically with feedback and integration with Wekinator. Big thanks also to Sarah Reid, David Rosenboom, and Tim Feeney on both the creative and technical aspects of Nami. 