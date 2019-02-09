# Sketches2Life

Ashwin Sankaralingam, Manish Shambu, Kodur Krishna Chaitanya


#### Problem Statement:
 To convert drawings (strokes) into images that contains the context of the drawing.

#### Motivation
This is a very interesting idea with respect to quick prototyping. 
- Film makers can use this kind of prototyping 
- Artists sculptors
- Police evidence pictures

It kind tells how much information strokes can be converted in 3 channel output. 

- Why is this an important and interesting problem? What triggered the idea?

#### Data / Data Plan

We are planning on using couple of datasets 

- Art Dataset : 
    -   Train : stroke version of the real drawing
    -   Generate : real drawing
- Doodle+ImageNet dataset:
    - Train : Doodle -> Image Net after class matching
    (* similarity score of the images also count wrt to doodle and real image)

#### Planned Approach

- We are planning on building the data set from art dataset and try to analyse data.
- Preprocess the data
- Apply either convolutionalAE or GANs to see the latent image generation.
- Validate and find a better model.
- Try to use google doodle dataset+ Imagenet to do the same. 
- Using colab (google) for training on TPUs and colaboration on notebooks.