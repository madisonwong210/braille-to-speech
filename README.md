# braille-to-speech
Braille to Speech is a machine learning application whose goal is to bridge the gap between the visually impaired and others by providing support to those who cannot read braille. The program takes in photos of braille characters, then speaks the English translations aloud.

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
The entire dataset, located in the character_data folder, contains photos of braille characters from the following texts: 

|   | type | sided | total # of images |
| ----- | :---: | :---: | ---: |
| Frederick | contracted (Grade 2) | single | 725 |
| Cloudy With a Chance of Meatballs | contracted (Grade 2)| double | 40 |
| Looking for a job? a guide for youth | contracted (Grade 2)| double | 45 |

However, the name of the images and the corresponding labels that we ended up using can be seen at `braille_data.csv`.
If you'd like to see all data, labels, and how we ended up with our final dataset, please see the sheets here: https://docs.google.com/spreadsheets/d/1xZFTeVZoV0V9dDaK4uzo02x--8YlRg-7uVvZJCTyhtI/edit?usp=sharing.

### Preprocessing, Implementation, and Training
Data preprocessing including loading into dataframe, creating a Dataset class, tranforming images, and feeding it into a Dataloader, as well as model implementation and training procedure are outlined in `braille_classification.ipynb`

<!-- ROADMAP -->
### Roadmap

- [x] Gather data
- [x] Preprocess images
- [x] Label data
- [x] Implement and train model

<!-- ### Built With

* [Next.js](https://nextjs.org/) -->
