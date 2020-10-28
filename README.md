# Drone Analysis using Machine Learning Techniques

## A dataset (16 features)- delivery of packages using drones, performed both graphical and non-graphical EDA to understand the data and find correlation between the features. Also, finding and fixing the data issues using mathematical techniques and machine learning model. Finally, predicting the Delivery fare using various machine learning models such as Multiple Linear Regression, Support Vector Regression, Random Forest Regression and Decision Tree Regression. Also, both Origin and Destination regions are fixed, using  KNN Classifier.

## Given information about the dataset- The dataset is about delivering packages using drones in Victoria, Australia. The description of each data column is shown below:

### 1) Id: Unique Id for each drone.
### 2) Drone type: A categorical attribute for the type of the drone. Each type of drone has three phases of flight ( namely takeOff , onRoute , and Landing ). The drone may have different speeds at different phases. takeOff and Landing phases only take five minutes.
### 3) Post type : A categorical attribute for the type of delivery (0:normal, 1:express).
### 4) Package weight : The weight of the package.
### 5) Origin region : A categorical attribute representing the region for the origin of the delivery.
### 6) Destination region : A categorical attribute representing the region for the destination of the delivery.
### 7) Origin latitude : Latitude of the origin.
### 8) Origin longitude : Longitude of the origin.
### 9) Destination latitude : Latitude of the destination.
### 10) Destination longitude : Longitude of the destination.
### 11) Distance : Distance of the journey.
### 12) Departure date: Date of the departure.
### 13) Departure time : Time of the departure. The delivery company has a specific rule to define morning (6:00:00 - 11:59:59), afternoon (12:00:00 - 20:59:59), and night (21:00 - 5:59:59).
### 14) Travel time: Travel time (i.e., duration) of the journey.
### 15) Delivery time: The time of the delivery.
### 16) Delivery price: Delivery fare. We know that the fare has a linear relation with some of the attributes of the dataset.

### Each feature has atleast 1 issues. Please view the code for indetail analysis of the same.
