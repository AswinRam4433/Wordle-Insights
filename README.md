# Wordle-Insights
Strategy for solving the Wordle of The Day


### What is Wordle?
Wordle is an online 5-letter word game. Each day a new word is released and players have six attempts to guess what the word of the day is. 

### How does Wordle work?
During the guesses, tiles will change colour to help players get the word. A grey letter means it isn’t in today’s word, whilst a yellow letter signals it is in the word but in the wrong position. Then there’s the green letter which means it’s in the word and in the right place.

### Why this project?
A fury of coloured tiles flooded the Whatsapp groups I was part of. At first, they made very little sense but after a quick Google search, I stumbled upon Wordle. The minimalistic design of the game and very simple rules of play appealed to me. So I decided to give Wordle a try. After a few days, I was hooked. I would countdown the amount of time I had left before the next Wordle would unlock. One such day, I was struggling to get the Wordle Of The Day. That's when I had the idea for this project.

![image](https://user-images.githubusercontent.com/75494275/160246858-9efe87ff-b15b-43e1-a0b2-34fb27d78fdc.png)



### Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- NLP using NLTK library

![Heatmap of Letters across Positions](https://user-images.githubusercontent.com/75494275/160242986-ef93b480-740e-44b3-9ca9-b68d0197197c.png)


### What did I do in this project?
I made use of the in-built corpora of the NLTK library of Python and picked out all the 5 letter words. Then I filtered out all the Wordle-legal words and began to look through them for interesting patterns to make tangible insights. Along the way, I used matlplotlib to depict information graphically. After looking at the heatmap showing the occurrence of each letter at each position and after using online word unscramblers, I was able to arrive at the conclusion that RAINS, BLUEY and CHOMP are the three best words to start off with. I also arrived at the conclusion that a letter can repeat almost one-third of the time.

### What did I learn in this project?
- I learnt how to make use of the NLTK library in real-world scenarios. 
- I have gotten more confident in my data visualisation capabilites. 

### Contact
[Aswin Ramanathan](https://www.linkedin.com/feed/)

Mail ID - aswinarv55[at][Gmail][dot][com]

### License
Licensed under MIT License. [Click here](https://github.com/AswinRam4433/Wordle-Insights/blob/main/LICENSE) to know more.
