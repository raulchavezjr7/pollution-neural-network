# Air Pollution Neural Network

This project uses a linear component analysis called PCA and an artificial neural network called autoencoder to create a model that finds deep relationships with pollutants and a second factor. PCA works by trying to shrink the dimensions of the data as small as possible while still maintaining a certain relationship between the data. Autoencoding works by also shrinking the data, but then trying to rebuild it back up. If the relationship the neural network creates during the shrinking is strong enough it will rebuild the data to an almost perfect copy of the original just using that relationship. Then it can use that shrunken data to find relationships with new data. 

This model gathers weather pollutant data from OpenWeather air pollution api. The data includes 6 polluting gasses and 2 particulate matters that are considered harmful at high levels. We gathered around six months of data from around 18,000 cities in the USA. This project was built on a Jupyter Notebook using Python. Libraries used were numpy, pandas, matplotlib, tensorflow, scikit-learn. 

The model was successful at capturing relationships using population as the second factor. This is a model where the second factor can be replaced in order to see if a relationship exists. We used population because it is a proven relationship with the amount of pollution. 

![autoencoder-poster](https://github.com/user-attachments/assets/eb2699b5-0a1e-4172-8b99-fecdbd8bf98d)

This was a NSF REU research project done with three other students. This project was continued by Nicolas Shannon and Vandana Nunna Lakshmi at https://github.com/nshan651/Pollution-Autoencoders where they cleaned up code for reusability and wrote a research paper on the topic. This code is as is when I left the project at the end of the REU. Follow Nicolas Shannos github shown above for the cleaned code.
