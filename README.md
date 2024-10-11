# Vocab Tester
This is a very simple vocab tester for japanese.

You're shown a random japanese word from a .csv file you provide and you're prompted to type it in.  
After pressing enter, the word will turn green if you typed it in correctly.  
Furigana will be revealed to show the reading, as well as the meaning of the word.

<img width="600" src="Images\\start.png"/>

I made this so I can easily practice new vocabs repeatedly and whenever I want, without having to make a new Anki deck/custom study to do it.
When selecting a random word, the program will go through each vocab in the .csv file at least once before repeating words.
</br></br>
## Usage ##
1. Download the ``index.html`` file (and if you want the ``vocabs.csv``)  
2. Open the index.html file in a browser of your choice  
3. At the bottom of the page there will be an Open File prompt. Navigate and open a .csv file containing your vocabs
</br></br>
## Setting your own vocabs ##
An example .csv file (vocabs.csv) is available.  

Each line in the file is a vocab, every line should contain two columns, delimited/separated by ``;``  
Example: ``もらう;to receive``

<img width="600" src="Images\\receive.png"/>  

You can also set furigana by using the japanese quotes ``「`` and ``」`` after a kanji (or multiple kanji)  
Example: ``家「か」族「ぞく」;family`` or ``日本「にほん」語「ご」;Japanese (language)``

<img width="600" src="Images\\family.png"/>  

The furigana will be applied to all symbols that came before it, stopping at the previous furigana if there is one.  
If you want to apply the furigana only to specific characters, just place a space before it.  
Example: ``お 願「ねが」いします;please`` (there is a space between ``お`` and ``願``)

<img width="600" src="Images\\please.png"/>
