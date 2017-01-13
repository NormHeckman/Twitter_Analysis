# Twitter_Analysis

These python notebooks create word clouds for twitter tweet collections. neh 2017-01-13

In order to run these juypiter notebooks locally, download the files to your workstation. Place the uncompressed files in a known location. A full installation of Anaconda Python on that workstation is recommended.

Then open an Anaconda bash shell.
You will need to install the wordcloud package with this command:
conda install -c amueller wordcloud=1.2.1

To open the notebooks in the case that the jupyter_notebooks directory is installed at: c:/workspace/Twitter-Analysis/jupyter_notebooks enter the following command:
jupyter notebook --notebook-dir=c:/workspace/Twitter-Analysis/jupyter_notebooks
This will cause a Jupyter Notebook home page to open in your default browser. Click on a notebook to open it. Then you can execute one block at a time by clicking on the ">|" icon. 

Note that the twitter data files read are located in a parallel input directory. For the example in the case above, the input directory would be located at C:/workspace/jupyter/input

Notes:
kaggle_tweets.csv is the original file from the Kaggle example.
tweetsP.csv is from a Mozdeh collection of tweets containing tweets sent by Putin, @PutinRF_Eng
tweets.csv is from a cree.py collection of tweets containing tweets sent by Lewanowski, @CLewandowski_ and Trump, @realDonaldTrump
