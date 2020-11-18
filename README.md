# Editable mushroom identifier

Final project for the Building AI course
<br />
<img src="https://github.com/annatao/Building-AI/blob/main/IMG_4704.jpg" width="300">
<img src="https://github.com/annatao/Building-AI/blob/main/IMG_4706.jpg" width="300">
<br />

## Summary

This project is to create an AI that can identify whether a mushroom is edible. It is to help people to enjoy the fun of picking mushrooms in nature while avoid eating poisonous ones. 

## Background

The idea is trying to solve:
* people died because of eating poisonous mushroom by mistake
* mushrooms look similar, and it is easy to mistake one from another
* knowledge about mushroom is very comprehensive

It is not uncommon that people die because of eating poisonous mushrooms by mistake, especially during fall, which is the mushroom harvesting season.
I personally like picking mushrooms and think that it is a good way to interact with nature. It will be beneficial, or even life-saving, to have an AI helping to identify edible mushrooms.


## How is it used?

To use the solution, photos, location or other properties of mushrooms has to be input. Image processing can be used to identify mushrooms from photos. Location can be used to narrow the range of species of mushroom to those available in that region. Other properties can include different appearance factors, such as whether the mushroom contains gills or pores, color and width of cap. 

Please note that sufficient amounts of input is needed for identification. A blurred image or just a broad location will not work. The solution should be able to instruct users about how to provide enough input, the following are examples. 

Example 1
<br />
<img src="https://github.com/annatao/Building-AI/blob/main/IMG_4712%20(2).jpg" width="300">
<br />
* overall appearance is well-recognised
* checking on cap's bottom is beneficial for identification
* instruction from solution can be "take a closer photo on the cap's bottom"

Example 2
<br />
<img src="https://github.com/annatao/Building-AI/blob/main/IMG_4710.jpg" width="300">
<br />
* gills are well-recognized
* checking on mushroom's width is beneficial for identification
* instruction from solution can be "enter estimated width of mushroom"

Users can be any individual that is interested in picking mushrooms and with a smartphone that can install mobile apps. They should be able to take multiple photos of the mushroom, to know where they are situated, and to be able to follow the solution's instruction to provide enough input for identification.

## Data sources and AI methods

Data can be collected via website with comprehensive mushroom knowledge such as
[MushroomExpert](https://www.mushroomexpert.com/)

k-nearest neighbor can be used as a brief identification, while deep learning can be used for more precise identification.

## Challenges

This project does not involve the responsibility of eating the mushrooms identified. It should be considered as a guide to confirm mushrooms, but not a golden rule for consumption.

## What next?

This project can grow to a mushroom species identifier, with comprehensive knowledge from fungi experts.


## Acknowledgments

* https://www.mushroomexpert.com/
* recent mushroom picking experience with friends
