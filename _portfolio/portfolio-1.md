---
title: "Educational Game for Early Literacy -Sprinkle" 
excerpt: "**#Independent Game Development**, **#Natural Language Processing**,<br> **#Speech Recognition**, **#Python Programming**

<br><br>This is an educational game I developed myself, aiming at improving kids' early literacy, with gamified activities including pronouncing words and sorting sentences.<br/><img src='https://kexin-yang.github.io/images/Sprinkle/1.png?raw=true' alt='Photo' style='width: 650px;'/>"  
collection: portfolio  
--- 

**Duration**: 4 weeks, Apr. 15th, 2019 - May.15th, 2019 
**Designer and Developer**: Kexin Yang


## Video demo of Sprinkle

[![SPRINKLE](https://kexin-yang.github.io/images/Sprinkle/1playVideo.png?raw=true)](https://youtu.be/rKN3eWOOxNw "CameraMaster")



## Speak Game

When a kid correctly pronounce the word in the bubble, the bubble will disappear and the kid will gain 3 points.
 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/2.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>

## Sort Game

### Level 1
Level 1 assesses the simplest sentence structure: Subject+Object+Verb
When a kid correctly sort a sentence into grammatical order, the kid will gain 5 points.

 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/3.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>


### Level 2
Level 1 assesses the harder sentence structure: Subject+Object+Verb+Prepositional Phrases (PP)
When a kid correctly sort a sentence into grammatical order, the kid will gain 10 points.
 <p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/4.png?raw=true" alt="Photo" style="width: 650px;"/>  
</p>



## Development Process

### Natural Language Toolkit and Grammar Writing
To add on to the algorithmic complexity, instead of using existing NLTK grammar, I defined my own grammar that can handle two sentence structures (1) Subject+Object+Verb, (2) Subject+Object+Verb + Proeositional Phrases.  
I made use of the recursive parser in the NLTK to recursively parse the sentence, which will return True or False, depending on whether the sentence entered is in accordance with the grammar I defined.


### Animation and User-Interface 
The interface design was coded using the Python module tkinter, with some external package including PIL to insert background image.  

### Speech Recognition Function
I made use of the speech_recognition library in Python to hear words spoken and transcribe that into text, then I programmed a function to check if the word heard is the same as the word currently exist. 


## Modules and Libraries Used
### Graphic module:
Tkinter
### Python Libraries:
Speech_recognition  
Natural Language Toolkit (NLTK)  
numpy  
PIL(ImageTk, Image)  
playsound  
random

<p align="center">
 <img src="https://kexin-yang.github.io/images/Sprinkle/end1.jpeg?raw=true" alt="Photo" style="width: 150px;"/>  
</p>

  




