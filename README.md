# GA-DnD-analysis
Exploratory analysis of a large data set of Dungeons and Dragons characters.
This exercise was done as a wrap up project for the General Assembly python bootcamp in February 2021.

## About the Data Source
 Github user [oganm](https://github.com/oganm), as part of the the project [dnddata](https://github.com/oganm/dnddata), shared a large data set of Dungeons and dragons characters. They run a website that prints character sheets and they've published these as a result of that process.
 
 A backup of the .tsv data source is included.
 
## Components
 This project was made with Google Collab as the host for the jupyter notebook. Its written in python 3 and uses:
 - numpy
 - pandas
 - matplotlib.pyplot and seaborn for visualization

## Analysis 
The goal of this project is to sudy which class and subclass choices lead to survivability. Exploring the data, we can see which choices are more common for long-lived characters, demonstrating better usefulness across a broad range of situations.

- The number of level one characters is much higher than expected, showing that many characters made see little to no play.
- The characters that survive to high level play have a very different class distribution than the entire set. So we can conclude that there are aspects of the class choice that improve survivability.
- By considering the overrepresentation of some choices in the long living set, we can see that they offer better benefits for character survivability.

Thank you for reviewing my project.
