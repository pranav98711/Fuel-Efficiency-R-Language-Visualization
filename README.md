# 🚗 How Far Can You Go With 1 Gallon of Gas?

I made this little animated race using EPA data to see which car brands are the most fuel-efficient on the highway. It's a fun way to visualize just how far you could go on a single gallon of gas, and spoiler: **some brands really go the distance**.

The animation shows the top 20 most efficient brands based on median MPG and MPGe since 1984 — think of it like a racetrack where cars move forward based on their fuel efficiency.

![2019_42_BigCars_Highway](https://github.com/user-attachments/assets/6ed154db-28b1-4821-ae84-8ac5ea3ece57)


## 💡 Why I Built This

I came across this dataset from the [#TidyTuesday](https://github.com/rfordatascience/tidytuesday) project (week 42, 2019) and thought: “This needs an animation.” The idea was to mix something useful (comparing fuel efficiency) with something visually fun (a countdown and car icons driving off).

I also added a second chart that looks at **how much money you could save** driving electric — based on the average 5-year savings compared to a regular gas car.



## 🔧 How It Works

This is an R project using:

- `gganimate` for the animation  
- `ggimage` to drop in a car icon  
- `emo` to add a bit of fun with emojis  
- `tidyverse` for data wrangling  
- A custom `tidy_grey` ggplot2 theme for a clean, dark aesthetic  

The animation runs on a timeline (like a race), and I used the `transition_reveal()` function to animate the cars as they move across the screen.



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


