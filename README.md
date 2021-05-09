# sleegalAI
Let us assume that everyday staff rearrange the bikes and for each bike station, the total number of bikes approximately equals the capacity of the station at the beginning of each day.

I used the Q4 dataset to analyze. Assume that there may be broken bikes, so people may not ride all the bikes at each station, every station may have one or two bikes left and people won't take them. By analyzing whether the number of bikes starting from the station is larger than the capacity plus the number of bikes arriving at the station for each day, I got seven stations, the stations ids are 47, 49, 76, 191, 195, 264, 286.

Then I set 7 - 10 a.m. and 5 - 8 p.m. as busy times, and checked whether there are some stations that need more bike docks. Based on the result, the stations that need to install more bike docks are 28, 36, 50, 56, 58, 66, 74, 75, 76, 77, 91, 111, 143, 164, 174, 175, 176, 191, 192, 195, 197, 255, 264, 301, 309, 320.

So the stations that need to install more bike docks are 28, 36, 47, 49,50, 56, 58, 66, 74, 75, 76, 77, 91, 111, 143, 164, 174, 175, 176, 191, 192, 195, 197, 255, 264, 286, 301, 309, 320.
