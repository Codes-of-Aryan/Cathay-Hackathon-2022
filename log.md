# Cathay-Hackathon
Training a Machine Leaning Model to get accurate Carbon Emissions per passenger per flight. <br> 
Since I'm the only coder in the team, I'm gonna be using the README as a way to think out loud.
Think of this as a progress log, as I descend into madness. This is more for future me to look 
into my mistakes and analyze my methods than anything. 

## Pipeline Steps
Let's get the dats first: <br>
    1. Look into Cathay's api and see if the data is relevant <br> 
    2. Look Online how calculator's work <br> 
    3. Look at the online flight data available <br> 
    4. Clean and combine useful data <br> 
    5. Train model <br> 
    6. Check Accuracy with test data <br> 
    7. Compare with traditional calculator formula <br> 
    8. Then present this data <br>  
    
Main Blockers - Getting actual flight data might be difficult, will look into it....

I need like flight data, mp like fdr of a lot of like real life flights 
1. factors such as avg. pressure, avg. temp, weather (like more features from that mit paper) 
2. hopefully these fdr's have total flight fuel consumption, now if we have that we can train 
3. a regression model to this data. 

kaggle so far has been a dead end, no useful data on there. not for this task anyway. So either 
FDR or maybe it might be worth looking into the datasets used by a lot of the research papers
that I'm planning to cite. <br> <br>

Ok another dead end. I can't seem to find any FDR online. I've spent about 3-4 hours now at this point 
trying to find out datasets and nothing seems to be a match for what I'm trying to achieve.
Only option I now have is to find a way to create a dummy set that somewhat achieves the objectives of 
the dataset I wanted to find. I'll state my assumptions and just let the judges know how I could've 
improved this data if I had access to FDR. 


Origin Destination (have it in the dataset, but don't really 
use this to predict anything) 
just use time, avg. load factor, aircraft type and build the 
most clean and readable code ever

HOLY SHIT!!!! 
The us is god-sent. thank god for the us bureau of stats. The only website, that 
somewhat has the data that might be usable here. And there's tonnes of data as well. 
This is good, this is really really good. Thank fuck. That's relief. There's still 10
hours left in the hackathon, I should be able to use some assumptions, clean/preprocess
data, build a model, and visualise that data as well. This is the hope, I needed. 
