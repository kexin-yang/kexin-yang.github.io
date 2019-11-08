---
title: "Educational Game for Early Literacy -Sprinkle" 
excerpt: "**# Independent Game Development**, **# Natural Language Processing**,<br> **# Speech Recognition**, **# Python Programming**

<br><br>This is an educational game I developed, aiming at improving kids' early literacy, with gamified activities including pronouncing words and sorting sentences.<br/><img src='https://kexin-yang.github.io/images/Sprinkle/1.png?raw=true' alt='Photo' style='width: 650px;'/>"  
collection: portfolio  
--- 
\#Independent Game Development, \#Natural Language Processing<br> 
\#Speech Recognition, \#Python Programming


**Duration**: 4 weeks, Apr. 15th, 2019 - May.15th, 2019 <br>
**Designer and Developer**: Kexin Yang


## Video demo of Sprinkle

[![SPRINKLE](https://kexin-yang.github.io/images/Sprinkle/1playVideo.png?raw=true)](https://youtu.be/MnF4v5ZgdwY "CameraMaster")


##Overview


## Speak Game

When a kid correctly pronounce the word in the bubble, the bubble will disappear and the kid will gain 3 points.
 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/2.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>

## Sort Game

### Level 1
Level 1 assesses the simplest sentence structure: Subject+Object+Verb. <br>
When a kid correctly sort a sentence into grammatical order, the kid will gain 5 points.

 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/3.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>


### Level 2
Level 1 assesses more complex sentence structure: Subject+Object+Verb+Prepositional Phrases (PP).
When a kid correctly sort a sentence into grammatical order, the kid will gain 10 points.
 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/4.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>


## Development Process

### Natural Language Toolkit and Grammar Writing
To add on to the algorithmic complexity, instead of using existing NLTK grammar, I defined my own grammar that can handle the two sentence structures mentioned<br>
(1) Subject+Object+Verb (SVO), <br>
(2) Subject+Object+Verb + Prepositional Phrases(SVO + PP).  

I made use of the recursive parser in the NLTK to recursively parse the sentence structure, and return True or False, depending on whether the sentence entered is in accordance with the grammar I defined.


### Animation and User-Interface 
The interface design was coded using the Python module tkinter, with some external package including PIL to insert background image.  

### Speech Recognition Function
I made use of the speech_recognition library in Python to hear words spoken and transcribe that into text, then I programmed a function to check if the word heard is the same as the word currently exist. 


## Limitation
For the time constraint, there are a lot of room for improvement in the game design from perspective of learning sciences and educational game design. (For example, while the disappearance of bubbles serve as correctness feedback, the sorting game still lacks immediate corrective feedback). It was developed more as a practice for object-oriented programming.

### Python Libraries Used:
Tkinter (Graphic module)
Speech_recognition  
Natural Language Toolkit (NLTK)  
numpy  
PIL(ImageTk, Image)  
playsound  

<p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/end4.png?raw=true" alt="Photo" style="width: 250px;"/>  
</p>

  




