# Classifiying-gaussian-quantiles

Simple machine Learning based classification of 200 randomly generated gaussian points into two classes. Aim was to reflect the effectiveness of neural networks over regression model to classify non-linear distribution of data. Distribution of points is shown in gaussian_distribution.PNG. 

Initial attempt was to classify the plot using logistic regression. But the model resulted into an accuracy of only 53%, thereby not making a clear distinction between the two classes. The classification was greatly improved on fitting the plots using single hidden layer neural network. On running the model for around 9000 epochs, staggering accuarcy of 92% was achieved with just 4 hidden units in hidden layer.
Decision boundary was plotted which clearly classified non-linear distribution. 

The model was compared with different number of hidden units in hidden layer. 100% accuracy was observed when hidden units were increased to 30, which showed clear signs of over-fitting. 
