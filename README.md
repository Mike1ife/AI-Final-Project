# AI-Final-Project
Generative AI

### requirements.txt
All the package you need to run our project

### Data
Contain [midi files](http://www.piano-midi.de/midi_files.htm) from each musician

### Note.csv
Contain notes of each file extracted from [Data](https://github.com/Mike1ife/AI-Final-Project/tree/main/Data)

### Argument
<pre>
-h                    show this help message and exit
--readcsv             read notes from csv file
--train               train your own model
</pre>

### preprocess.py
Contain functions to load midi files as well as notes preprocess

### model.py
Contain functions to train, evaluation and generate music

### test_output.mid
Our generated music
