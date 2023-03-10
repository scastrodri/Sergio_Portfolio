Some projects using Python.


#  [Found faces and text in zip files of images](https://github.com/scastrodri/Python_projects/tree/main/Faces_and_text_%20in_zip)
* Take a zip file of scanned images. Detect faces and text to find a specific word in every one of the images in the zip file.
* Print a legend that shows up the amount found of the specific word.
* With the faces detected create a contact sheet to show every one of them.
## A sample image
<img src="./images/a-0.jpg" alt="a-0">

## Faces found in the sample image
<img src="./images/faces_in_a-0.png" alt="faces_in_a-0">


#  [Sentiment Analysis of Climate Change Tweets](https://github.com/scastrodri/Python_projects/tree/main/Sentiment_Analysis_of_Climate_Change_Tweets)
* Getting into the Bayes Theorem through an example of cookies and bowls.
* Going from the cookies example through the tweet classification creating a Bayesian model for tweets as a base parameter.
* 'Smoothing' the model for those words that couldn't be parametrized in the initial model.


# [Image Processing](https://github.com/scastrodri/Python_projects/tree/main/Image_Processing)
Much of the filters here exists are built-in functions that use numpy arrays, but in this case will be use the putpixel method, although it's a little bit slow, it's very easy and intuitive to use.
* Some basic filters as grayscale, black and white, sepia tone, neon filter, negative filter.
* A little bit of rotating, scaling and blending.
* Image Kernel for cleaning up noise (Replace every pixel with the median pixel value of the 8 pixels around it).
## All filters
<img src="./images/all_filters.jpg" alt="all_filters">

## Kernel for cleaning up noise
<img src="./images/noisy_non-noisy.png" alt="noisy_non-noisy">


# [Exploring Common Words and SETI](https://github.com/scastrodri/Python_projects/tree/main/Exploring_Common_Words)
* Graph the frequency of the words on the Y axis against the rank of the words on the X axis. It would should see a pretty dramatic (exponential) curve. Its also not very useful because a few very large values dwarf all of the small # values.
* Graph the frequency of the words on the Y axis against the rank of the words on the X axis. This one will be in a log-log scale.
* Which of the words when spelled forward are also on the list when spelled backward?
* How many new words can be reversed if you you add an ???s??? on the end?
* Finally lets look at the distribution of the different parts of speech in this 5000 word dataset.
## Frequency of the words
<img src="./images/Distribution of the words.png" alt="Frequency of the words">

## Frequency of the words in a log-log scale
<img src="./images/Distribution of the words log.png" alt="Frequency of the words log">
## Distribution of the different parts of speech
<img src="./images/Distribution of the different parts of speech.png" alt="Distribution of the different parts of speech">


# [Graphing data with the Turtle module](https://github.com/scastrodri/Python_projects/tree/main/Graphic_Turtle)
* There are many tools to graph data, but let's 'code' our own graphs from scratch using the turtle module.
* The data used is part of [Kiva](http://kiva.org/) that is an international nonprofit, founded in 2005 and based in San Francisco, with a mission to connect people 
through lending to alleviate poverty.
* The first one will be a bar chart that shows the total amount of loans for country.
* The second one is a scatter plot that prints the loan amount vs the total number of lenders.
* The last one is a histogram (using the bar chart) that is used to display 10 differents 'buckets' that are 'categories' from the loan amount.
## Bar chart
<img src="./images/Bar-chart.png" alt="Bar-chart">

## scatter plot
<img src="./images/Sactterplot.png" alt="Sactterplot">


# [Substitution Cipher](https://github.com/scastrodri/Python_projects/tree/main/Substitution_Cipher)
* A script that will encrypt the string referenced by the variable plaintext using the Caesar cipher with a shift of 13.
* A script that will encrypt the plaintext using a key.
* A script that will decrypt the ciphertext using a key.
* A scrypt that asks the user to enter a key (scrambled alphabet) and a message to encrypt or decrypt.

# [Create and 'guess' passwords](https://github.com/scastrodri/Python_projects/tree/main/Password)
* Creates an 8-letter password by combining characters from three strings (letters, CAPS, numbers).
* Creates a four-word password by combining words from three lists (nouns, verbs, and adjectives).
* Have at least one capital letter and a number in your password.
* How many guesses would it take to guess a 4 letters password? - If you change this to a 5-letter password will increase the amount of time due to the calculations.
