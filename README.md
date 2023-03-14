# AN ALTERNATIVE TO A RESTRICTIVE PAIN CHART

## PROJECT DESCRIPTION 
This project was prompted by the studies and experiences that show that people of colour, especially dark-skinned people, pain and symptomps are likely to not be taken seriously in medical institutions*
When I researched for this project, I found that there's tons and tons of guides to how to talk to your doctor in a way where you pain will be believed, but I am interested in seeing how people actually describe their pain and what this does to our way of percieving pain and illness. 
I also stumbled upon the pain chart - a chart of 10 drawn faces that are supposed to depict levels of pain. A chart that I've never heard of before, but that is apparently used in a lot of US medical institutions, which I find to be a rather restrictive way to determine a patients level of pain and to prescribe diagnosis and medication. 

This project interrogates how we are expected to talk about our pain versus how we actually talk about it. What does this do to our understanding and percievement of pain, and it is possible to create a better, more relateable pain chart. 


## DISTILGPT2 & STABLE DIFFUSION 

To generate the images for the new pain chart I have been using a stable diffusion model, that takes a text input and based on that generates an image. I thought of finetuning this model, but ended up fine tuning a text generation model instead, because I don't want to assume or put any of my own ideas of descriptions of pain into the model.   
In order to get real life descriptions of peoples pain I have scraped from a variety of subreddits revolving pain and treatments, some of them are specifically of backpain or kneepain, some of them are for people living with migraines or chronic pain in any form. 
On this data I have trained the text generation model, distilgpt2 to generate prompts to use in a stable diffusion model. 


## THE DATASET 

OBS: The data is cleaned, but it needs to be viewed on an JSON viewer to format properly. 





*https://www.npr.org/templates/story/story.php?storyId=201128359
