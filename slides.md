---
colorSchema: light
layout: cover
routerMode: hash
title: Water's Sonic Signatures
theme: neversink
addons:
  - slidev-addon-citations
biblio:
  filename:
    - tarkovsky.bib
    - ig2022.json
  # footnotes: true 
  template: chicago
csl_template_file: style.json
---

# Water's Sonic Signatures

Computational Sound Studies and Ecological Awareness in Tarkovsky's Films 

**Tate Carson**, **Dakota State University**

<!--
Andrei Tarkovsky's films frequently employ water as a powerful sonic and visual element, evoking profound ecological and emotional resonance. This project applies computational and qualitative analysis to explore how water's sounds in *Solaris*, *Stalker*, and *Nostalghia* shape narrative ecological consciousness.
-->


---
layout: image
image: /images/stalker-rain.png
---

<!--
## Why Water and Tarkovsky?

and in Sculpting in Time about rain Tarkovsky wrote: 
"Rain, fire, water, snow, dew, the driving ground wind—all are part of the material setting in which we dwell; I would even say of the truth of our lives. I am therefore puzzled when I am told that people cannot simply enjoy watching nature, when it is lovingly reproduced on the screen, but have to look for some hidden meaning. Of course rain can just be seen as bad weather, whereas I use it to create a particular aesthetic setting in which to steep the action of the film. But that is not at all the same thing as bringing nature into my films as a symbol of something else—Heaven forbid!"
-->

---
layout: intro
---

# Motivation & Research Question

- This project explores how water sounds in Tarkovsky’s *Solaris*, *Stalker*, and *Nostalghia* operate as more than atmospheric effects or mere symbols.
- I ask:  
  > *How do these sonic treatments of water contribute to ecological awareness?*

<!-- 
- The inspiration for this project came from my initial viewing of Tarkovsky's *Stalker* about a year ago. The film had a profound impact on me, unlike any other film I'd seen before—its unique cinematic language and portrayal of nature felt both unique, but at the same time deeply resonant.
- Tarkovsky’s treatment of nature captivated me, specifically his use of natural elements, not merely as symbolic imagery, but as tangible experiences encountered by his characters.
- When I learned of the conference theme, the connection seemed clear. Tarkovsky extensively features water in his works, particularly in the three films I've chosen for analysis, Solaris, Stalker, and Nostalghia.
- This project aims to investigate how Tarkovsky employs water sonically, using qualitative and quantitative methods to determine whether his films can indeed enhance viewers' ecological awareness or consciousness.
 -->



---
layout: section
color: navy
---

# Theoretical Context
<hr>
Cinema as ecological world-making; Materializing Sound Indices;  Ecoacoustics 


---
layout: side-title
color: emerald-light
titlewidth: is-3
align: rm-lm
---

:: title ::

# Cinema as Ecological World-Making

:: content ::

- Cinema creates worlds that are not separate from reality, but continuous with it <Cite bref="adrianj.ivakhivEcologiesMovingImage2013"/>.
- Films can reshape how we perceive social and ecological relations.
- Through spectacle, narrative, and meaning, cinema draws us into relational ecologies — where perception and world are intertwined.
- Some films, like Tarkovsky’s, foster ecological awareness by revealing the world’s materiality, vitality, and openness to becoming.
- Audiovisual ecology suggests that sound and image together shape ecological perception [@jordanSchizophonicImaginationAudiovisual].

<!-- 
- Source: Adrian J. Ivakhiv (2013), *Ecologies of the Moving Image: Cinema, Affect, Nature*.
- Cinema is a "process-relational" art: it depicts and participates in the world's constant becoming.
- Moving images don't just reflect the world; they *move* us, connecting perception and environment.
- Tarkovsky's water imagery, slow takes, and material textures are ecological gestures, grounding us in shared existence with the more-than-human world.
- Films can help viewers re-attune to material and ecological realities, resisting disconnection and abstraction.
-->


---
layout: side-title
color: sky-light
titlewidth: is-3
align: rm-lm
---

:: title ::

# Materializing Sound Indices (MSIs) 

:: content ::

- **MSIs** are sonic details that make us *feel* the physical, material qualities of a sound source [@Chion_Gorbman_2018].
- Sounds rich in MSIs make scenes feel tangible and grounded.
- Sparse MSIs make sounds feel ethereal or abstract.
- Water in Tarkovsky's films often acts as a high-MSI material, immersing viewers in a concrete, ecological reality.

<!-- 
- MSIs highlight how sound conveys material texture: friction, impact, oscillation.
- Real acoustic reverbs materialize sounds; synthetic reverbs can dematerialize them.
- In Tarkovsky’s films, water often carries heavy materializing detail (e.g., dripping, splashing), rooting the audience in the "here-and-now."
-->

---
layout: side-title
color: teal-light
titlewidth: is-3
align: rm-lm
---

:: title ::

# Ecoacoustics and Perception

:: content ::

| **Index**                                                         | **What it measures (in a nutshell)**              | **High value sounds like…**    | **Typical perception**                                   |
| ----------------------------------------------------------------- | ------------------------------------------------- | ------------------------------ | -------------------------------------------------------- |
| Acoustic Evenness (**AEI**)                                       | How evenly energy fills the spectrum (Gini-style) | Balanced rain, gentle surf     | Calm, pleasant                                           |
| Acoustic Richness (**AR**)                                        | Loud _and_ dynamically varied                     | Traffic + machinery mix        | Busy, stressful                                          |
| Median Amplitude (**M**) [@lawrenceLinkingEcoacousticIndices2023] | Overall loudness vs. quiet gaps                   | Constant roar/back- ground hum | Chaotic, annoying [@kjaerExploringImpactsSoundscape2025] |
| Number of Peaks (**NP**)                                          | Count of sudden transients across bands           | Drips, insects, bird calls     | Detailed, lively, “natural”                              |

<!-- 
- Lawrence et al. (2023) linked acoustic indices to psychoacoustic perception outcomes.
- Definitions
  - Median Amplitude (M) - Median amplitude divided by maximum amplitude of the whole clip. Closer to 1 → overall loud; closer 0 → mostly quiet with occasional peaks.
  - Acoustic Richness (AR) - Combines M and Ht ranks. High AR means a clip is both loud and dynamically varied—often used as a quick “soundscape richness” surrogate.
  - Number of Peaks (NP) - Counts sudden boosts in power in each frequency bin across the clip. More peaks → more transient detail (e.g., insect stridulation, drips). Zero means a perfectly flat spectrum.
  - Acoustic Evenness Index (AEI) - Uses the Gini coefficient (In ecoacoustics it gauges how evenly energy is spread across frequency bands.): 0 = every bin equally loud (even); 1 = all energy crammed into a few bins (uneven).
- Higher acoustic richness and median amplitude correlated with perceptions of annoyance and traffic.
- Higher acoustic evenness and number of peaks correlated with perceptions of calmness and naturalness.
- These perceptions can influence environmental attitudes and behaviors.
-->

---
layout: side-title
color: cyan-light
titlewidth: is-3
align: rm-lm
---

:: title ::

# Ecoacoustics in Film Sound Studies

:: content ::

- Applying ecoacoustic indices to film soundtracks could:
  - Reveal sonic environments that cultivate ecological awareness.
  - Differentiate scenes dominated by natural vs. anthropogenic sounds.
  - Analyze how soundscapes influence viewer emotion, attention, and sense of place.
- A step toward computational ecocinema analysis.

<!-- 
- Films already use sound to create worlds; analyzing them with ecoacoustic indices could quantify how soundscapes shape ecological or anti-ecological impressions.
- A natural, richly textured soundscape could enhance ecological immersion.
- Anthropogenic noise could intentionally create alienation or critique human impacts.
- Opens new possibilities for integrating ecoacoustics with film sound analysis and environmental media studies.
-->



---
layout: image-left
image: /images/nostalghia-dog.png
---

# Films & Method

- **Studied**: *Solaris* (1972), *Stalker* (1979), *Nostalghia* (1983)  
- **Approach**: Scene-by-scene tagging of water events  


<!-- 
**Solaris (1972):**
Solaris follows psychologist Kris Kelvin as he is dispatched to a space station orbiting the enigmatic planet Solaris, whose vast, oceanic surface mysteriously materializes the deepest memories of its occupants. Kelvin’s encounter with Hari—a physical manifestation of his deceased wife—forces him to confront unresolved grief and the fluid boundaries between reality and memory. Through long takes and immersive soundscapes, the film invites viewers to question the nature of human experience and the interplay of love, loss, and imagination.

**Stalker (1979):**
Stalker follows a mysterious guide known as the Stalker, who leads two men—a writer and a professor—into the forbidden Zone, a surreal landscape where a Room is rumored to grant one’s deepest wishes. As the trio journeys through an environment that shifts in tune with their inner fears and desires, they grapple with existential uncertainty and the transformative power of their own aspirations. The film’s deliberate pacing, meditative camera work, and atmospheric sound design create a dynamic interplay between the tangible world and the metaphysical realm.

**Nostalghia (1983):**
Nostalghia centers on the Russian poet Andrei Gorchakov as he travels to Italy in search of artistic and personal meaning, only to become enveloped in a profound sense of longing and alienation. His journey is marked by nostalgic reveries and encounters that blur the boundaries between memory, ritual, and present reality. Through haunting imagery, slow-paced sequences, and persistent water motifs, the film meditates on loss, cultural dislocation, and the bittersweet nature of home.
-->

---
layout: image
image: /images/spreadsheet.png
---

<!--
- **Water Type**: flowing, dripping, still  
- **Sonic Features**: reverberant, layered, low-frequency  
- **Chionian Function**: rendering, symbolic, reproduction  
- **Ecological Connection**: water as memory, habitat, contamination  
- **MSI Level**: Material–Social–Imaginal axis
 -->

---
layout: default
---

![](/figures/fig_water_type_bar.svg)

<!-- 
- This bar chart shows the **number of scenes** associated with each water type across *Stalker*, *Solaris*, and *Nostalghia*.
- We can see that *Stalker* dominates in **Pond Stillness** (Quiet, motionless water; represents contemplation or spiritual calm.) and **Splashing**, reflecting its marshy, still environment.
- *Solaris* shows a strong concentration in **Submersion** (Underwater perspective; conveys immersion, distortion, or dream states.), matching its focus on psychological immersion and interior memory spaces.
- *Nostalghia* spreads its water types more evenly, with notable usage of **Flowing**, **Gurgling**, and **Rain**.
- This quantitative view emphasizes how **scene counts** differ, not just presence—showing Tarkovsky's evolving soundscape strategies across films.

-->



---
layout: default
---

<img src="/figures/rain_calmness_heatmap.svg" style="max-height: 500px;">

<!--
Overview:
- This figure shows Tarkovsky’s Rain scenes ordered by an ecoacoustic calmness score.
  - Calmness is defined as: (+ NP + AEI) – (M + AR)
  - where:
    - NP = Number of Peaks (higher = calming, more natural detail)
    - AEI = Acoustic Evenness Index (higher = even, less masked spectrum)
    - M = Median Amplitude (lower = quieter)
    - AR = Acoustic Richness (lower = less monotonous, less mechanical noise)

Color Interpretation:
  - Dark blue = lower value for that index
  - Yellow = mid-range
  - Red = high value
  - NP and AEI are positive indicators — higher values are more calming
  - M and AR are negative indicators — lower values are more calming

Scene Order:
  - Top scenes (e.g., Nostalghia Scene16, Nostalghia Scene05)
    → have high NP and AEI, low M and AR
    → correspond to calm environments: dripping rain, distant reverberation, ritual moments.
  - Bottom scenes (e.g., Solaris Scene16, Solaris Scene15)
  → have lower NP and AEI, or higher M and AR
  → denser water movement sounds, final narrative intensities.

Narrative Connection:
  - The calmest scenes align with moments of memory, ritual, and thresholds in Tarkovsky’s films.
  - Sonic calmness reinforces slow, contemplative narrative structures.
  - Scenes of higher density correspond to narrative climaxes or emotional confrontations.
-->

---
layout: default
---

# Nostalghia: Hotel Room

<video controls style="max-width: 100%; height: auto; display: block; margin: auto;">
  <source src="/video/Nostalghia_Scene05_HotelRoomRain.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>

---
layout: side-title
color: emerald-light
titlewidth: is-3
align: rm-lm
---

:: title ::

# Contributions & Implications

:: content ::

- Proposed framework: **sonic-ecological agency**  
- Bridges **film sound studies** and **ecoacoustics**  
- Demonstrates value of **computational methods** in ecocinema analysis  
- Future work: other water types, more computational descriptors
  
<!--
This project introduces *sonic-ecological agency*—a framework for understanding how water sounds in film actively shape ecological perception by mediating relationships between characters, environments, and viewers. Drawing on Jordan’s theory of audiovisual ecology and Ivakhiv’s process-relational model of cinema, the framework views sound as an agent in world-making—not just representational, but affective and ecological.

My computational study focused on rain scenes, using ecoacoustic indices associated with calmness and naturalness. These indices helped identify how Tarkovsky’s sonic environments might cultivate an attunement to place, reinforcing Ivakhiv’s claim that cinema reshapes perceptual ecologies.

Future work will extend to other water types (e.g., dripping, splashing) to compare acoustic textures, narrative roles, and Chionian functions. These sonic categories—when aligned with narrative and perceptual structure—may help reveal broader patterns of ecological meaning.

While this study used established ecoacoustic indices, I plan to integrate more refined computational descriptors and develop a perception study to better link sonic features with embodied and affective responses.
-->




---
layout: biblio
biblio:
  item_per_page: 5
---


---
layout: section
color: navy
---

## Contact 

Tate Carson | 
tatecarson.com |
tatecarson@pm.me

<!-- This is a **note** -->
