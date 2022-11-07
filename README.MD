# Lasso regression model for YouTube show ["Разгоны"](https://www.youtube.com/watch?v=vv7rCc2yeU0&list=PLcQngyvNgfmK0mOFKfVdi2RNiaJTfuL5e)  

   
Views prediction based on video duration, days from release date, cast, number of male and female participants.  
Total amount of available data is 86 records. Train set was 61 chronologically first records, validation set - 25 last records.  
Every record has a feature for every participant who ever took a part at this show making dataframe pretty sparse.  
Lasso linear model showed best results amongst others (Linear, Ridge, Random Forest) with mean absolute error - 127000 and mean absolute percentage error - 17 %