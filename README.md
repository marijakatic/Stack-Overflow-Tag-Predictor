  
  <h1 align="center">Tag Prediction from Stack Overflow Questions </h1>

  <p align="center">
    Student project on course Machine Learning, Master Degree Studies, University of Belgrade, Faculty of Mathematics
    <br>
   
 <!-- ABOUT THE PROJECT -->
## About The Project
The project is inspired by [CS229](http://cs229.stanford.edu/) Student Final Project:

> Tag Prediction from Stack Overflow Questions - Jalal Buckley, Kevin Fuhs, Reid M. Whitaker ([poster](http://cs229.stanford.edu/proj2019spr/poster/78.pdf), [report](http://cs229.stanford.edu/proj2019spr/report/78.pdf))

The task and the data are given in Kaggle competition: [Facebook Recruiting III - Keyword Extraction](https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/overview).

**Task description** (<a href="https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/overview">Description from competition overview</a>):

*The task is to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title.
The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions.*

**Data description** (<a href="https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data">Description from competition overview</a>):

*All of the data is in 2 files: Train and Test.*
*Train.csv contains 4 columns: Id,Title,Body,Tags*
* *Id - Unique identifier for each question*
* *Title - The question's title*
* *Body - The body of the question*
* *Tags - The tags associated with the question (all lowercase, should not c contain tabs '\t' or ampersands '&')*
* *Test.csv contains the same columns but without the Tags, which you are to predict.*

*The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).*


<!-- LANGUAGES AND TECHNOLOGIES USED -->
## Languages and technologies used

* Implementation is in [Python 3.7](https://www.python.org/).
* Code was written using [Google colab](https://colab.research.google.com/notebooks/intro.ipynb), [Anaconda](https://www.anaconda.com/), [The Jupyter Notebook](https://jupyter.org/).
* [scikit-multilearn](http://scikit.ml/) library for Multi-label Classification was used.
* Other packages and libraries used: [Matplotlib](https://matplotlib.org/), [NumPy](https://numpy.org/), [pandas](https://pandas.pydata.org/), [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/), [NLTK](https://www.nltk.org/), [SciPy](https://www.scipy.org/), [scikit-learn](https://scikit-learn.org/stable/), [Keras](https://keras.io/).
* Markdown editor for README: [StackEdit](https://stackedit.io/)

<!-- NOTES -->
## Notes

* We used an unacceptably small subset of data due to a lack of hardware capabilities. In the future, models should be trained on a larger dataset and the results compared.
* In the future, we can try with some more complex NLP word embeddings and models.
* The Heuristic, since it turned out to be very good, will continue to be used in the future. There are relations between tags for one question, so when you have some tags, it is easier to predict more of them. So The Heuristic could be the starting point,  upgraded with some ML.


<!-- REFERENCES -->
## References

* Inspiration for the project: "Tag Prediction from Stack Overflow Questions" - Jalal Buckley, Kevin Fuhs, Reid M. Whitaker ([poster](http://cs229.stanford.edu/proj2019spr/poster/78.pdf), [report](http://cs229.stanford.edu/proj2019spr/report/78.pdf))
* Dataset: [Facebook Recruiting III - Keyword Extraction](https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/overview)


<!-- CONTACT -->
## Contact

* Marija Katić | katic.marija.97@gmail.com, mr16032@alas.matf.bg.ac.rs | https://github.com/marijakatic