# WordCloud
![Output Image](https://github.com/Umair-Yaqub/WordCloud/blob/cb7bd89b1bae8ee8a1e3412728b7d55ef64e38bc/Word_Cloud_Output.png)
<br><br>
This project, creates a "word cloud" from a text by writing a script.  This script needs to process the text, remove punctuation, ignore case and words that do not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words.  A dictionary is the output of the `calculate_frequencies` function.  The `wordcloud` module will then generate the image from dictionary.
For the input text of script, you will need to provide a file that contains text only(I have included that file in the repository "Word_Cloud_Text.txt").
<br><br>
You will need to upload your input file here so that script will be able to process it.  To do the upload, you will need an uploader widget.  Run the following cell to perform all the installs and imports for word cloud script and uploader widget.  It may take a minute for all of this to run and there will be a lot of output messages. But, be patient. Once you get the following final line of output, the code is done executing. Then you can continue on with the rest of this notebook.
<br><br>
To upload your text file, run the following cell that contains all the code for a custom uploader widget. Once you run this cell, a "Browse" button should appear below it. Click this button and navigate the window to locate your saved text file.
The uploader widget saved the contents of your uploaded file into a string object named *file_contents* that word cloud script can process.
A function in the cell below iterates through the words in *file_contents*, removes punctuation, and counts the frequency of each word, ignore word case, words that do not contain all alphabets and boring words like "and" or "the".  Then used the `generate_from_frequencies` function to generate word cloud!
<br><br>
Storing the results of your iteration in a dictionary before passing them into wordcloud via the `generate_from_frequencies` function.
