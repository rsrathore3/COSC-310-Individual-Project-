
# COSC 310 Individual Assignment 
![Cute lil robot!](https://upload.wikimedia.org/wikipedia/commons/7/75/Kawaii_robot_power_clipart.svg)

<sub><sup>**IMAGE CREDIT**</sub></sup><br>
<sub><sup>"File:Kawaii robot power clipart.svg" by Mvolz is marked under CC0 1.0.</sub></sup>

**CHATBOT PROGRAM**

This program is meant to be a simple chatbot capable of 30 rounds of semi-natural speech. This was initally done via simple phrase recognition but has been upgraded to use python's natural language toolkit. Implemented features include:

- Misspelling handling via Porter Stemmer.
> Program stems user input and checks against stemmed sentences on the backend, allowing the system to handle minor gramatical errors.

- Part of Speech recognition.
> In order to make sure the user is giving a valid name or food item, the system checks for a noun when asking for user input for stored values.

- Named entity recognition.
> Similar to the POS recognition, the program uses NER to isolate the name of an organization from a string when the user inputs a response to a question like 'What is your favorite hockey team?"

- A simple GUI via Python's Tkinter functionality.
> The title explains it pretty well, this allows the user to input conversation in a more standard setting. This also allows the user to look back through chat history.

- More varried responses when the agent doesn't understand.
> In order to make the program a bit more dynamic, it can now randomly pick from one of five error sentences instead of just the one.


![POS](https://github.com/COSC-310-Group-24/Assignment-2/blob/main/Images/pos.png?raw=true "Demonstration of POS tagging")
POS Tagging
![NER](https://github.com/COSC-310-Group-24/Assignment-2/blob/main/Images/ner.png?raw=true "Demonstration of Named Entity Recognition")
Named Entity Recognition
![STEM](https://github.com/COSC-310-Group-24/Assignment-2/blob/main/Images/stem.png?raw=true "Demonstration of Porter Stemmer")
Stemming
![GUI](https://github.com/COSC-310-Group-24/Assignment-2/blob/main/Images/gui.png?raw=true "Demonstration of GUI")
GUI
![RANDOM](https://github.com/COSC-310-Group-24/Assignment-2/blob/main/Images/random.png?raw=true "Demonstration of Responses")
More varried responses (some not shown, bad RNG)

- Use of Public APIs 

   <img width="400" alt="COSC_310_screenshot" src="https://user-images.githubusercontent.com/79660865/115100374-c91da100-9f59-11eb-849c-0351fab72065.png">
  
 -Wikipedia API
  >Robot Robert uses the Wikipedia API (https://pypi.org/project/wikipedia/) which makes it easy to access and parse data from Wikipedia. Having this Wikipedia feature in 
  >Robot Robert makes it more informative and increases curiosity amongst the users. Robot Robert is also focused on giving the maximum amount of information in the specified
  > number of sentences. Also having such an API makes the conversation longer and meaningful for the user to continue asking intrguing questions from Robot Robert. Overall, 
  > usage of Wikipedia API has made Robot Robert as efficient as ever. 
  

 -GoogleTranslate API 
  >Robot Robert uses the Google Translate API (https://pypi.org/project/googletrans2/) that implemented Google Translate API and converts English to Japanese. This feature
  >from the public API makes Robot Robert highly inclusive and multi lingual. As a developer, I chose Japanese as the language because I personally want to learn Japanese and 
  >starting out with my own chatbot doesn't seem to be a bad idea. I would be interested in further developing this feature of Robot Robert, it would be interesting to have 
  >Robot Robert speak more than languages than just English and Japanese. 
