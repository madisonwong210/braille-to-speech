# braille-to-speech
Braille to Speech is a machine learning application whose goal is to bridge the gap between the visually impaired and others by providing support to those who cannot read braille. The program takes in an image contaning braille, then speaks its English translation aloud.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#data-collection">Data Collection</a></li>
    <li><a href="#preprocessing">Preprocessing</a></li>
    <li><a href="#implementation">Implementation</a></li>
  </ol>
</details>

### Data Collection
The dataset contains of photos of braille text. It contains various images from the following texts:

|   | type | sided | pages |
| ----- | :---: | :---: | ---: |
| Frederick | contracted (type 2) | single | 20 |
| Cloudy With a Chance of Meatballs | uncontracted (type 1)| double | 33 |
| Looking for a job? a guide for youth | contracted | double | 80 |

### Preprocessing
Basic image preprocessing can be found in Final_Proj_1.ipynb
Here is a link to the colab: https://colab.research.google.com/drive/1m8Z7Qcfv67zfctvQ3r8iZvvSmUAnDGqS?usp=sharing

### Implementation
The beginning stages of implementing the basic model can also be found in Final_Proj_1.ipynb

<!-- ROADMAP -->
### Roadmap

- [x] Gather data
- [x] Preprocess images
- [ ] Implement and train model

<!-- ### Built With

* [Next.js](https://nextjs.org/) -->
