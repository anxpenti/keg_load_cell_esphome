# keg_load_cell_esphome
<h1 align="center">
  ESPHome KEG scale - E-PAPER
</h1>

KEG Fridge, loadcell, epaper, hx711, Google Trends
<p align="center"><img src="images/view_1.jpg" width=512 alt="Pípa s dislayem"></p>

## Hardware
* ESP32
* 2in9 epaper Waveshare display
* HX711 ADC converter
* 50KG loadcell

<p align="center"><img src="images/view_2.jpg" width=512 alt="Stohování sudů"></p>

## Google Trends
* zobrazení aktuálních trendu vyhledávání na Google.com
* komponenta pro vypsání RSS jako sensor - https://github.com/custom-components/feedparser

<p align="center"><img src="images/google_trends.jpg" width=512 alt="Google Trends"></p>

## Lovelace setting
* nastavení offsetu pro váhu sudu (15,30,50L)
* výběr loga pivovaru k zobrazení na epaper

<p align="center"><img src="images/ha_lovelace_setting.jpg" width=512 alt="Homeassistant Lovelace"></p>

## Score table
* to není třeba vysvětlovat :)
* == stiskem tlačítka se přičte do konkrétního input_number hodnota a podle ní se zobrazí "čárka" na displayi ==

<p align="center"><img src="images/score_table.jpg" width=512 alt="Score table"></p>

* input_text pro jména na Score Table
<p align="center"><img src="images/score_table_ha.jpg" width=512 alt="Score table HA"></p>

## Tenzometry a držáky

<p align="center"><img src="images/keg_holder_tenzo.jpg" width=512 alt="Score table"></p>

