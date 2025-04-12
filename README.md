# 🚗 What Can You Build With R? How About a Car Race! 🚗🏁

I made this animated race using R and EPA data to show which car brands are the most fuel-efficient on the highway. It's a fun way to visualize just how far you could drive on a single gallon of gas — and spoiler: some brands really go the distance.

The animation shows the top 20 most efficient brands based on median MPG and MPGe since 1984. Think of it like a racetrack: the more efficient the brand, the farther it goes!

![2019_42_BigCars_Highway](https://github.com/user-attachments/assets/6ed154db-28b1-4821-ae84-8ac5ea3ece57)


## 💡 Why I Built This

I found this dataset from the #TidyTuesday project (week 42, 2019) and immediately thought: “This would look great as an animation.”

I wanted to make something that mixes useful info (fuel efficiency) with visual storytelling — like a countdown and little cars racing forward based on real numbers.

I also added a chart showing how much money you could save by switching to electric, using average 5-year savings from EPA data.



## 🔧 Built With R

This is an R project using:

- `gganimate` for the animation  
- `ggimage` to drop in a car icon  
- `emo` to add a bit of fun with emojis  
- `tidyverse` for data wrangling  
- A custom `tidy_grey` ggplot2 theme for a clean, dark aesthetic  

The race animation uses transition_reveal() to animate each brand over time, based on their median highway MPG. I also included a countdown at the start to make it feel more like an actual race. 🏁



## 📊 Data Source

All data comes from the [EPA’s fuel economy dataset](https://www.fueleconomy.gov/feg/download.shtml), which has vehicle data going back to 1984.


## 📁 Project Structure

![image](https://github.com/user-attachments/assets/bf9b5cad-aaaf-4ee2-84e7-bac4eae4438f)



## 🔋 Bonus: Going Electric Saves 💸

Here's a static plot I added that shows how much you can save by going electric. It’s based on average estimated 5-year savings from the EPA data:

![2019_42_BigCars_Savings](https://github.com/user-attachments/assets/f677cfa5-0bdf-476c-8066-023bb1eb9f78)



## 📝 Notes

- Car icon is from [mynamepong on Flaticon](https://www.flaticon.com/authors/mynamepong)  
- Inspired by the amazing work of Cédric S



If you’re into data viz and R, hope you enjoy playing with this as much as I did building it. 🚀  
Feel free to fork, tweak, or suggest ideas!


