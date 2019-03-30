# Smart-keyboard
A smart keyboard that predicts next word and also spell checks based on user's conversation history<br />

#### Predicting Next word
![alt text](https://github.com/pranavjadhav001/Smart-keyboard/blob/master/readmeimages/Capture2.PNG)

#### Spellchecking
![alt text](https://github.com/pranavjadhav001/Smart-keyboard/blob/master/readmeimages/Capture3.PNG)

#### How to run
python smart_keyboard.py -m path_to_model -f path_to_dict

#### Commands
- Tab: fetches the left hand side and best result and puts it in text filed
- Enter : Clears the text field and dumps the text in text file
- Space : predicts next keyword 
- Any key : It shows the best possible spelling in your dictionary

#### Prerequisites
- Tensorflow - 1.12.0
- Tkinter 
- keras - 2.2.4
- Python - 3.6.1
- Numpy 
- Json
