# <img src="https://i.ibb.co/vBDDNpd/earthquake.png" width="37px" /> KD QUAKE

 | 🧋To access the bot [click here](http://t.me/KDQUAKEBOT).                                                     |
|------------------------------------------------------------|
| **Thanks for the support!**.|


<p align="center">
  <a href="https://www.python.org/downloads/"><img src="https://img.shields.io/badge/Python-3.8%2B-blue.svg" alt="Python Version"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-brightgreen.svg" alt="License"></a>
  <a href="https://pypi.org/project/pyTelegramBotAPI/"><img src="https://img.shields.io/badge/pyTelegramBotAPI-4.16.1-ff69b4.svg" alt="pyTelegramBotAPI Version"></a>
  <a href="https://pypi.org/project/requests/"><img src="https://img.shields.io/badge/Requests-2.31.0-orange.svg" alt="Requests Version"></a>
  <a href="https://pypi.org/project/beautifulsoup4/"><img src="https://img.shields.io/badge/BeautifulSoup4-4.12.3-yellow.svg" alt="BeautifulSoup4 Version"></a>
</p>




## Features

- **Earthquake Data Display:**
  - The `/start` command shows a main menu with options to view earthquake data.
  - Options include displaying all recorded earthquakes, the latest earthquake, and the most intense earthquake recorded.

- **Callback Handling:**
  - KD-QUAKE manages inline button callbacks to display the geographical location of earthquakes.
  - The location is shown on the map directly in the chat.

- **Earthquake Data Parsing:**
  - Utilizes the BeautifulSoup library to extract data such as date, location, magnitude, depth, and geographic coordinates from INGV's HTML data.

- **User Interaction:**
  - Provides a welcome message with a link to the "KDTOOLS" channel for support.
  - Uses inline keyboards to allow users to select their desired options.

- **Menu State Logic:**
  - Maintains a menu state for each user, allowing them to resume interactions where they left off.

## Usage

To use KD-QUAKE, follow these steps:

1. Start the bot by sending the `/start` command.
2. Choose from the available options in the main menu to explore earthquake data.


## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
```
```
