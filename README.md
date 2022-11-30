# AI Gahaku & Racial Bias in Facial Recognition Algorithms

## Introduction

## Literature review

## Methodology

Evaluating the biases of an AI art generator - AI Gahaku which generates painting in different styles based on a picture.

Our aim is to identify whether the AI underperforms when creating images based on pictures of non-Caucasian people. The first stage of our research consisted in gathering a dataset of faces from different ethnicities. To do so, we relied on the work of Kärkkäinen and Joo (2021) who constructed a dataset aiming at solving the biases that other public face image datasets had toward Caucasian faces. They argue that most datasets tend to significantly underrepresent non-Caucasian faces and created an inclusive dataset to mitigate the race bias problem (Kärkkäinen and Joo, 2021, p. 1548). They defined the following seven race groups: Black, East Asian, Indian, Latino, Middle Eastern, Southeast Asian and White. We created 3 groups out of these seven categories, two treatment groups: Black and East Asian and a control group: White. As an overwhelming majority of Northern Renaissance Paintings feature white people, we assume that their representation will be the most accurate. We picked two groups that are typically underrepresented in this style to help us to assess whether a bias does indeed exist, and if yes whether it is similar for both groups or not. 
We selected a total of 45 pictures (15 per groups) and generated portraits using the AI-Gahaku mobile application. Furthermore, to evaluate whether the biases where only limited to one specific type of painting, we di


## Findings & Analysis
<p align="justify">
Before delving into the mismatches in the quality of the generations that could have been generated by a bias in the AI model, we need to address some aspects affecting all generations. It can notably be noticed that the shapes of the faces tend to be distorted or to present some artefacts (e.g.: #50, #2061, #4228). This is most likely due to formatting of the pictures in the fairface dataset, which crops pictures to only leave faces on the picture. As AI Gahaku generates portraits, it expands some cropped image to try and generate a full face, sometimes deforming faces. As our research focuses on biases in the faces of individuals, it will not be problematic for our analysis. Furthermore, the model produces subpar results for people with an open mouth, which occurred for some portraits, but it does not indicate a bias of the model. Another difficulty introduced by the fairface dataset is that the pictures are relatively small as the minimum size of a detected face can start at 50 by 50 pixels However, as mentioned by Kärkkäinen & Joo (2021, p. 1551), attributes are still recognizable so generations are still accurate enough to assess the presence of biases or not.
We will first assess the presence of biases on the Early Renaissance generations and followingly examine whether Contemporary Realism generations were less biased. As predicted by our initial hypothesis, the generated paintings show a certain degree of biases. The first group examined; Black people shows the most obvious bias which is linked to the skin tones of the generations. As can be seen on the figure XXX, all generations feature rather similar skin colours, which were used in Early Italian Renaissance by painters such as Antonello de Messina to depict white people. The gap is less striking on the generations that were made based on the East Asian group as their skin tones are less contrasted with the generated tone. However, after looking more in-depth at our generations, we can see that different undertones tend to be erased and the three group are uniformly depicted with white skin tones.
</p>

<p align="center">
![image](https://user-images.githubusercontent.com/116351321/204894138-d695034a-3a96-48bc-920b-97f8ca897686.png)
  </p>
<p align="justify">
Original pictures and generations Early Renaissance, references of the images (link to right and top to bottom): #412, #1019, #4433, #1719

Besides the complete change of complexion, we observed that the model reproduces the face shape and most facial characteristics of the people rather accurately. To observe whether significant changes occurred, we juxtaposed original pictures with the AI generated images and observed which areas were misrepresented. We noted that eye shapes tend to not be represented accurately, especially for some members of the East Asian group. For instance, the epicanthal folds on the portraits #3718, #3623, #3974 and #4251 are replaced by rounder, greener eyes on the generated painting.  
![image](https://user-images.githubusercontent.com/116351321/204894325-7d90ec91-94b0-4430-9006-180302246805.png)  ![image](https://user-images.githubusercontent.com/116351321/204894346-a17fbd2f-1650-47d2-9c17-791ab245ffeb.png)

Portrait #3718 & #3623 and juxtaposition of the real picture (black frame) on the generated portrait) 

Such modifications seem to be less prevalent when looking at our control group (white people) even though some individuals present artefacts around their eyes. A similar issue occurs for some portraits of the first group. 

![image](https://user-images.githubusercontent.com/116351321/204894487-36f17c35-891a-41b7-8f43-46b1d2532be9.png) ![image](https://user-images.githubusercontent.com/116351321/204894503-dc7beb2d-4b5c-4ab0-95eb-4845e063a035.png)
Portrait #119 & #5933 and juxtaposition of the real picture (black frame) on the generated portrait)

The issues abovementioned contribute to show that the portraits of white people tend to be more accurately represented than the other groups or at least that the respective generated pictures are closer to the original models. As the canonical aesthetic of Early Italian Renaissance is almost entirely based on the depiction of white people, this is unsurprising. 
![image](https://user-images.githubusercontent.com/116351321/204894619-9afc1aa3-442c-4972-b783-b84063b3e6cb.png)
![image](https://user-images.githubusercontent.com/116351321/204894632-081f48a2-8584-4f3d-b124-938652e0e3c5.png)
  
Original pictures and generations, references of the images (link to right and top to bottom): #654, #623, #37, #3870

The paintings used by AI Gahaku to train the model are most likely based on Antonello da Messina’s work, as one of his paintings is used illustrate the style of images that will be produced when selecting the style. After checking his work through the art database Wikiart (2022) , we did not find a single painting representing a non-white person. This could potentially explain the shortcomings of the models to generate pictures representing people from different ethnicities. 
As mentioned in our methodological part, to see whether those issues would be mitigated by applying an art style that potentially used more inclusive dataset for training, we subsequently generated portraits using the Contemporary Realism style. Amongst the options offered by AI Gahaku, we hypothesized that it could potentially produce less biased results than Early Renaissance. 
The results are, however, practically identical. This is notably visible when looking at the skin complexions of the second round of generations. The complexions are similar to the sample image provided for Contemporary Realism but disregards the skin colour of the pictures selected to produce a white complexion. 
![image](https://user-images.githubusercontent.com/116351321/204894727-a9b21dde-ffb5-4c5f-9427-a9b92efbe544.png)
Original pictures and generations Contemporary Realism, references of the images (link to right and top to bottom): #120, #1370, #4605, #6765
  </p>




## Limitations 

## Annex 

## References
