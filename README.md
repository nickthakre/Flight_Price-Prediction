# Demo
[Demo link](https://predict-flight-price-api.herokuapp.com/)

<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/2a67ab4fac816bdedc7b5b38f7e1d7ecc51ea1c7/Plots/home.PNG" />



# Flight_Price-Prediction

Here we Predict flight price base on following inputs or Features.<br>
1. Where from user take a flight i.e Source of traval
2. To Where he want to go ie. Destination of Traval.
3. Day And Time of Departure
4. Day And Time to Arrival
5. Stopage i.e To traval from Source To Destination how many Stop user wants or that flight takes.
6. Airline company. I.e From which Airline company user want to travel.

From above Features we Generate another featurs like,
1. Journey_day
2. Journey_month
3. Dep_hour
4. Dep_min
5. Arrival_hour
6. Arrival_min
7. Duration_hours
8. Duration_mins

And Convert all Categorical Features into Numerical using One-Hot Encoding.

### ALL Airlines
<img src="Plots/airline.png" />

### ALL Source
<img src="Plots/source.png" />

### ALL Destinations
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Destination%20count%20plot.png" />

### ALL Routes
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Route%20count%20plot.png" />

### ALL Total_stops
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Total_stop%20count%20plot.png" />

### Price Over days in Months
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/day_price%20line%20plot.png" />

### Dep_Houre
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Dep_houre%20lineplot.png"/>

### Arrivel Houre
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Arrivel_houre%20lineplot.png" />

### Duration Hours Count
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/e7a83c65c3b8d82085e0fefb668ecd467ed73665/Plots/Duration_houre%20countplot.png" />

### Duration Hours
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/duration_houre%20lineplot.png" />

### Heat Map
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/heatmap.png" />

### Top 20 Features
<img src="https://github.com/nickthakre/Flight_Price-Prediction/blob/8e00fdd784889ea90edb53c69358dd1204678040/Plots/Top%20features.png" />


Like this type of inputs or features we predict flight price.
And Deploy it on severs.

