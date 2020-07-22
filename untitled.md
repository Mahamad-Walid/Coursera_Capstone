# Battle of Neighbourhoods

#### 1 Introduction/Business Problem
    1.a Discussion of the business problem and the audience who would be interested in this project.

#### 2 Data Section
    2-a What data is used?
    2-b Importing Libraries
    2-c Credentials and Core location
    2-d Search for hotel within 1 KM
    2-e Location of Hotels (without the closest hotel to the red dot)

#### 3 methodology
    just doing some data analysis to compare the hotels and the distances between them anc calculate the average distance between them

#### 4 Results Section
    The final map with everything thing in the last map except it will offers you the closest hotel

#### 5 Discussion section

#### 6 Conclusion section



# 1. Introduction/Business Problem
### Discussion of the business problem and the audience who would be interested in this project.
#### Something about the tourist place-Mahamad walid
    I am from Cairo,the capital of Egypt and I had an idea of travelling to sharm el sheikh, but I have never been there and I also don't know what hotel should I stay in, so I thought why do not I use the stuff that I learned from that course to make a map of sharm el sheikh that has all the hotels in it with almost all the details needed.

#### Expected / Interested Audience
    sharm el sheikh is a well known city for being a nice place to stay in and have a nice holiday and lots of tourists go there as they find lots of fun stuff there and have a chance to go to its amazing beaches and its clear sea and do safaris, etc.

# 2.Data section
#### 2.a What data is used?
    We will be completely working on Foursquare data to explore and try to locate our new hotel where more venues beach, memorials that are present nearby
#### How will we be solving using this data?
    We will look for midpoint area of venues to locate our hotel.Before that our major focus will be on all venues present in and around the core place of sharm el sheikh.

    Just a heads up on how many hotels are distributed now around sharm el sheikh.We will perform some EDA on hotels & restaurants present in the tourist spot.On furthur notebook we will use Foursquare data to determine other venues as well.
#### 2.b Importing Libraries
    this part has been already done in the notbook so no need to type the coding here
#### 2.c Credentials and Core location
    this part has been already done in the notbook so no need to type the coding here
    but the output will be put here:
    "sharm el sheikh location : 27.8669082,34.3014551"
#### 2.d Search for hotel within 1 KM
    this part has been already done in the notbook so no need to type the coding here
#### Send the GET Request of hotel and examine the results
    this part has been already done in the notbook so no need to type the coding here
#### Get relevant part of JSON and transform it into a pandas dataframe
    this part has been already done in the notbook so no need to type the coding here
    but the output will be put here:
    "There are 22 hotels at sharm el sheikh"
#### Define information of interest and filter dataframe
    this part has been already done in the notbook so no need to type the coding here
    but the output will be put here:
![Capture](https://user-images.githubusercontent.com/62917455/88228802-fc9ff900-cc6f-11ea-9614-b3039167dbb2.PNG)
#### 2.e Location of Hotels without the selecting the closest hotel to the red dot
    this part has been already done in the notbook so no need to type the coding here
    but the output will be put here:
![map0](https://user-images.githubusercontent.com/62917455/88080129-ecf4b780-cb7e-11ea-8cb3-c1ab7d2ba9cf.png)
## 3.Methodology section
    In this sections we will perform some data analysis
    to know which is the closest hotel to our red point (which is center of sharm el sheikh) 
    and also the average distance between hotels and core location
    this part has been already done in the notbook so no need to type the coding here
    but the output will be put here:
![digram1](https://user-images.githubusercontent.com/62917455/88229224-aed7c080-cc70-11ea-8127-33195c8e3f77.png)
## 4.Results Section
    this part has been already done in the notbook so no need to type the coding here
    it prints the valve of the latitude and langitude of the closest hotel to the red point
    but the output will be put here:
    "27.864835221577067"
    "34.30136007465381"
    then it prints the final map with the closest hotel to the red point
    and the photo of the map is here
![map4](https://user-images.githubusercontent.com/62917455/88229229-b0a18400-cc70-11ea-9960-95edb3d218a6.png)
## 5. Discussion section
    From this finall map we find that pool at aida hotel is the closest hotel from your spot and finally you cna stay for the night.
    Well that app would be super helpful if you were in a rush and didn't know anyplace to stay in for the night.
    I used so basic code but it helped to solve a problem that faced me in my life, so i am proud of myself.
## 6. Conclusion section
    There are about 9,000 English tourists are in Sharm on any given day so for sure at least 500 of them would need to find
    a hotel asap to stay in at night at least for one day so i think that app will be helpfull for them 
    and there soem egyptians like who have never been there that will need that app for sure to find a place to stay in.
    Shortly this app gives a temper hotel to stay as it doesn't give you the ratings or any recommendations, it just tells where is the closest hotel.
# Thanks for taking a look on my project and also reading this, have a nice day!