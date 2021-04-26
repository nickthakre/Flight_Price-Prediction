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

- There are total 12 Unique Airlines. which is ['IndiGo', 'Air India', 'Jet Airways', 'SpiceJet', 'Multiple carriers', 'GoAir', 'Vistara', 'Air Asia', 'Vistara Premium economy', 'Jet Airways Business', 'Multiple carriers Premium economy', 'Trujet']
- Most used flight by user are Jet Airways, IndiGo, Air India.
- And most expensive flight is Vistara Premium Economy.

### ALL Source
<img src="Plots/source.png" />

- There are total 5 Unique Source of travel. which is ['Banglore', 'Kolkata', 'Delhi', 'Chennai', 'Mumbai']
- Most user travel from Delhi, Kolkata, Banglore.
- And Delhi, Kolkata, Banglore Source have a high price as compare to others. 

### ALL Destinations
<img src="Plots/destination.png" />

- There are total 6 Unique Destination of travel. which is ['New Delhi', 'Banglore', 'Cochin', 'Kolkata', 'Delhi', 'Hyderabad']
- most of the user Travel To Cochin, Banglore, Delhi.
- And New Delhi, Cochin, Banglore Destination have a high price as compare to others.

### ALL Routes
<img src="Plots/route.png" />

- There are total 128 Unique Route paths.
- Most of the Airline Route path is DEL-BOM-COK, BLR → DEL, CCU → BOM → BLR

### ALL Total_stops
<img src="Plots/total_stop.png" />

- There are total 5 types Unique Stops during Travel. which is ['non-stop', '2 stops', '1 stop', '3 stops', 'missing', '4 stops'].
- Most of the Airline take at least one stop during travel.
- And as Stops Increase Flight Price will also Increases.

### Price Over days in Months
<img src="Plots/journey_day.png" />

- All Journey year are 2019.
- Fight Price high in March Month till 13 March in 2019.
- In whole April month Fight Price is low as Compare to other Months.

### Dep_Houre
<img src="Plots/dep_hour.png"/>

- In mid night Flight Price is less as compare to day.
- From 1 Am to 4-5 Am Flight Price is low.

### Arrivel Houre
<img src="Plots/arrival_hour.png" />

### Duration Hours Count
<img src="Plots/duration_hours.png" />

### Duration Hours
<img src="Plots/duration_hours_lineplot.png" />

- From above plots we say that 22.5% Travel duration Takes 2 Hours.
- And 50.0% Travel duration takes 8 Hours.
- There are very few flights which take more than 32 hours.
- And As Travel duration increase Flight Price also increases.

### Heat Map
<img src="Plots/heatmap.png" />

### Top 20 Features
<img src="Plots/Top features.png" />


Like this type of inputs or features we train a model and predict flight price.
And Deploy it on server.

