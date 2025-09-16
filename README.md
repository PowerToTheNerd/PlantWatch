# PlantWatch

## 🌱 Plant Tracker – TODO

- [ ] Figure out formula to scale soil moisture values (≈7000–21000) into 0–100%.

 - [ ] Make a file reader to quickly load and parse the saved CSV data.

 - [ ] Prepare data format (CSV/JSON) for use in C++ capstone project.

 - [ ] Add calibration values (dry/wet averages) into the program.

 - [ ] Optional: add humidity and temperature sensor, or pull local weather data.

 - [ ] Optional: basic graphing to visualize light and moisture trends.

---

## 🌱 Project : Nerd Inc Plant Tracker (WIP)

Right now, my Nerd Inc Plant Tracker is still a work in progress, but I’ve built the foundation by focusing on data collection. The program runs on a Pi 5, it automatically logs readings from a BH1750 lux sensor (for light intensity) and a capacitive soil moisture sensor (through an ADS1115 ADC), along with the date and time, into daily CSV files.

I’ve already done my own calibration testing — I recorded multiple samples with the soil sensor completely dry (in air) and fully wet (submerged in water), then calculated the averages for absolute dry and wet conditions. I saved those values in my “Important Info” file and plan to use them in future updates to translate raw sensor readings into a 0–100% soil moisture scale.

So far, it’s mainly collecting data, but my next steps will include applying my calibration data, visualizing the results, and eventually expanding into more environmental tracking (like temperature and humidity).
