# A-guide-to-creating-attractive-and-interactive-data-visualizations...-even-for-NLP
A guide to creating attractive and interactive data visualizations… even for NLP

Currently, in my work as a physics professor, I showed some visualizations of EM waves in class. I explained how the parameters in the solution of the equation modify the wave shape, my students got interested and asked me to change the settings and run the code to see different waves. I thought that it would be great if I could modify the graph interactively without running the code. After some Google search, I found some libraries that do pretty cool interactive plots:

- Altair
- Ipywidgets

It was very easy to plot the wave equation with Altair and ipywidgets (link). I use the features of these libraries to modify parameters such as amplitude, wavelength and wave frequency interactively. Currently, one of my main interests is digital marketing, so for a more exciting demonstration of the power of Altair and Ipywidgets, I decided to use a data set containing information about Instagram posts, and got visualizations for:

Trends on the likes and comments.
Word clouds to visualize the most used words in captions and hashtags (I also used NLTK for this part).

In this post, you will learn how to:
- Use Altair to make a plot where you interact with the mouse to select data points, retrieve information of these points, and zoom in regions of the graph.
- Implement ipywidgets to make interactive pie charts, clean text data, and word clouds in one line.


## Note: The notebook is too heavy and it doesnt display well in github. Download the repository and run it to see the viz in your computer. Or check the gifs in this link https://medium.com/@thalia181189/want-to-create-fully-interactive-plots-with-python-d54ab28760d9 to have a better idea of how the plots look.
