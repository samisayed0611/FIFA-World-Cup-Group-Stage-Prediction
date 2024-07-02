# 2018 FIFA World Cup Russia™ Prediction Project

## Table of Contents

- [Description](#description)
- [Tools & Dependencies](#tools--dependencies)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

### Description

This project aims to predict the 2018 FIFA World Cup Russia™ group stage outcomes by collecting and analyzing data from previous World Cups (1994-2014). Data was gathered using a web scraper due to the lack of an API.

We collected group statistics for the following FIFA World Cups:
- 2014 Brazil™
- 2010 South Africa™
- 2006 Germany™
- 2002 Korea/Japan™
- 1998 France™
- 1994 USA™

For each World Cup, the following statistics were collected:
- Group name
- Team names
- Matches played, won, drawn, and lost
- Goals for and against
- Goal difference
- Points

Detailed steps for building the web scraper are in the [Medium article](https://medium.com/ub-women-data-scholars/let-the-robot-do-your-work-web-scraping-with-python-9c147fb7690f).

## Tools & Dependencies

The data is publicly accessible on the [FIFA website](https://www.fifa.com/fifa-tournaments/statistics-and-records/worldcup/index.html). According to the `robots.txt`, data scraping is allowed [as of June 10, 2018].

Analysis was performed using Jupyter Notebook with Python 3.x and the following libraries:
- [Requests](http://docs.python-requests.org/en/master/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)

## Installation

To run this project:

1. Create and activate a virtual environment:
   ```shell
   virtualenv -p python3 my_virtualenv
   source my_virtualenv/bin/activate
   ```

2. Clone this repository:
   ```shell
   git clone https://github.com/BarbaraStempien/DA--World-Cup-Data.git
   ```

3. Install project dependencies:
   ```shell
   pip install -r DA--World-Cup-Data/requirements.txt
   ```

4. Open Jupyter Notebook to run the project or open `web_scraping.py` in your code editor.

## Contributing

Contributions are welcome. For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

---

FIFA World Cup Group Stage Prediction | Python, Web Scraping, Data Analysis, BeautifulSoup, Pandas
Developed a prediction model for the 2018 FIFA World Cup Russia™ group stage by scraping historical data from 1994 to 2014 using Python, BeautifulSoup, and Requests, followed by comprehensive data analysis with Pandas.