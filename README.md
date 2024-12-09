# meteo473project
## Our Proccess:
---
We collected 2 meter temperature data and 500mb geopotential height data from the ECMWF model, beginning at October 10 2024 and spanning across the following 10 days. We established the verification and initialization models over the continental US at numerous timesteps. Next, we calculated the absolute error of each parameter and graphed it with respect to the KUNV station. Additionally, breaking down the 10 days into short, medium, and long ranges and repeating the absolute error calculation across this more dense range and creating filled contour plots. Finally, calcualting the root mean squared error at each time step and dispalying the results as a line chart. We read in another model run, 12 hours prior and repeated the same process to calculate the root mean squared error and added it to the plot. 

## Our Conclusion & Analysis
---
From our line charts of root mean error squared, it is clear that the accuracy of forecast models declines as it gets further out in time. So to reiterate, the models have a smaller error for a 12 hour prediction than for a 72 hour prediction. This makes physical sense, and is what would be expected, our model just proves it using real data. 

## Plots
---
- **Model Run & Verification Run for 0, 72, 144, & 240 Hours for 2m Temperature Data**
    - 2m Temperature(°F) at Forecast Hour 0
    - 2m Temperature(°F) at Forecast Hour 72
    - 2m Temperature(°F) at Forecast Hour 144
    - 2m Temperature(°F) at Forecast Hour 240
    - 2m Temperature(°F) Verification at Forecast Hour 0
    - 2m Temperature(°F) Verification at Forecast Hour 72
    - 2m Temperature(°F) Verification at Forecast Hour 144
    - 2m Temperature(°F) Verification at Forecast Hour 240
- **The Absolute Difference Between Model Run and Verification for 2m Temperature Data**
    - 2m Temperature(°F) Absolute Difference at Forecast Hour 0
    - 2m Temperature(°F) Absolute Difference at Forecast Hour 72
    - 2m Temperature(°F) Absolute Difference at Forecast Hour 144
    - 2m Temperature(°F) Absolute Difference at Forecast Hour 240
- **Line Chart of Forecast Error (y axis) vs Time Step (x axis) for 2m Temperature Data**
    - Short-Range 2m Temperature Forecast Mean Absolute Error
    - Medium-Range 2m Temperature Forecast Mean Absolute Error
    - Long-Range 2m Temperature Forecast Mean Absolute Error
- **Root Mean Squared Error (RMSE) Over Time of 2m Temperature Data**
- **Root Mean Squared Error (RMSE) Over Time of 2m Temperature Data from 2 model runs**
- **The Absolute Difference Between Model Run and Verification for 500mb Geopotential Height Data**
    - 500mb Geopotential Height Absolute Difference at Forecast Hour 0
    - 500mb Geopotential Height Absolute Difference at Forecast Hour 72
    - 500mb Geopotential Height Absolute Difference at Forecast Hour 144
    - 500mb Geopotential Height Absolute Difference at Forecast Hour 240
- **Line Chart of Forecast Error (y axis) vs Time Step (x axis) for 500mb Geopotential Height Data**
    - Short-Range 500mb Geopotential Height Forecast Mean Absolute Error
    - Medium-Range 500mb Geopotential Height Forecast Mean Absolute Error
    - Long-Range 500mb Geopotential Height Forecast Mean Absolute Error
- **Root Mean Squared Error (RMSE) Over Time of 500mb Geopotential Height Data**
- **Root Mean Squared Error (RMSE) Over Time of 500mb Geopotential Height Data from 2 model runs**
- **Forecast Error Over Time**

## Challenges
---
We faced challenges predominately with storing our data. We certainly learned the value of compartmentalizing our process. By this I mean, we put our imports and data downloads in their own cells and were extremely concious of not rerunning unnecessary cells. Not only is it a poor use of time, but excessive data download sometimes hindered our process by writing over itself until failure sometimes. Overall, we became a lot more detailed in our formating as we progressed in this project. 

## License
---
[MIT](https://choosealicense.com/licenses/mit/)
