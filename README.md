Esphome yaml files for home-assistant. 

Using nws to grab temp highs and lows, and openWeatherMap for preciptation history and predictions (api free up to 2000 req/day, which we will never approach, as we update sensors once per hour.) 

devices so far: 
- LOLIN TFT-2.4 running on a D1 mini ESP32
  -   https://www.wemos.cc/en/latest/d1_mini_shield/tft_2_4.html
- Cheap Yellow Display (CYD)
  -   https://www.youtube.com/watch?v=0AVyvwv0agk
- MAX7219 8x8x4 LED matrix
  -   https://esphome.io/components/display/max7219digit.html
