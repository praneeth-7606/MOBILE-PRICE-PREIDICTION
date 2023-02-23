# Mobile price prediction
## Problem Definition:
Ravi has started his own mobile company. He wants to give tough fight to big companies like Apple, Samsung etc. He does not know how to estimate the price of mobiles his company creates. In this competitive mobile phone market, you cannot simply assume things. To solve this problem, he collects sales data of mobile phones of various companies. Ravi wants to find out some relation between features of a mobile phone (eg:- RAM, Internal Memory etc.) and its selling price. But he is not so good at Machine Learning. So, he needs your help to solve this problem. In this problem you do not have to predict the actual prices of the mobiles, but you have to predict the price range of the mobiles.

## Datasets:
In this project total we are using 3 different datasets of mobiles each dataset has different features. All the columns in the data set describe various features in the mobile phone which decides its price.amoung  the 3 datasets 2 are used in  regression and 1 dataset is used in classification.

## Features in Data Set 1:
- mobile name: Name of the mobile likeRealme Narz, Realme 5 Pro, Realme X2, Realme X2 Pro etc. 
- Mobile price: We have to check the price according to the features of the phone. 
- Mobile colour: Colour is important for the mobile weather it is white,blue,sparkling blue etc. 
- Dual Sim: dual sim or not
- disp size: Measured diagonally of left corner to right corner. 
- 0S:Weather it is FAndroid 10, Android Pie etc.
- num cores:Octacore
- mp speed:2 GHz,2.3GHz,1.95GHz etc. 
- int memory:inbuilt memory with 32GB,64GB,128GB it is different for all phones. 
- RAM:4GB is minimum RAM in memory. 
- P cam: Check the suitable MP for P cam
- f Cam: Check the suitable MP for f cam
- Network:4G VOLTE or 3G VOLTE.
- Bluetooth: Had Bluetooth or not. 
- Battery:4000 MAH is better for a smart phone. 
- mob width: Width of the mobile.
- mob depth: depth of the mobile.
- mob weight: weight of the mobile

- *In dataset 1 target variable values (price_range) are in the form of 0,1,2,3 which indicates the price ranges of the mobile and after using different ml models the
predicted values are also in the same.

  - 0 value indicates price range of the mobile is between 0-10,999
  - 1 value indicates price range of the mobile is between 11000-29,999
  - 2 value indicates price range of the mobile is between 30,000-49,999
  - 3 value indicates price range of the mobile is between 50,00-79,999
  
## Features in Data Set 2:
- Brand me: It denotes the name of the brand and name of the mobile.
- Ratings: This feature denotes the number of the ratings gave by the consumers for each mobile.
- RAM: It has RAM the size of the phone. 
- ROM: It has ROM size of the phone. 
- Mobile Size: It represents how many inches of the particular mobile.
- Primary Cam: It denotes no of pixels of the primary camera (Back Camera).
- Selfie_Cam: It denotes no of pixels of Selfie camera (Front Camera).
- Battery Power: It donates amount of the battery power in each mobile in mAh. 
- Price: It is a dependent feature of the data set. It just denotes the price of eachmobile.

## Features in Data 3:
- It is important to check the price of the mobile.
- Sale: Enhances the potential of mobile based on sales. Weight: weight of cellphone.
- Resolution: an important factor in measuring the visual quality of digital images, photos, and videos.
- PPI: Measure price change from the perspective of the seller. CPU core: It is a Processer in phone. 
- CPU frequency: A good processor speed is between 3.50 to 4.2 GHz. 
- Internal memory: The internal memory is the one where you can store all of your personal content.
- RAM: at least 4GB RAM should be there. 
- Rear cam:16 to 128megapixals
- Front camera:6 megapixel is sufficient for a normal.
- Battery: A customer should definitely check the battery 4000mah is good.
- Thickness: The average thickness of a smart phone is 0.35 inches.

## Python Packages:

- NumPy: a library for numerical computation and manipulation of large arrays and matrices of data. 
- Pandas: a library for data manipulation and analysis, including data cleaning and preparation, as well as data visualization.
- Matplotlib: a library for data visualization, including 2D and 3D plots. 
- Scikit-learn: a library for machine learning, including supervised and unsupervised learning algorithms. 
- Seaborn: It is a data visualization library for Python. It is built on top of Matplotlib and provides a high-level interface for creating attractive and informative
statistical graphics.

## ALGORITHIMS USED :
- DECISION TREE
- RANDOM FOREST
- SVM (SUPPORT VECTOR MACHINE)
- KNN (K NEAREST NEIGHBOUR)



