TeamFortressMatchHistoryAnalyzer
================================

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Introduction
------------

Since the EU GDPR changes you can view your personal data on Steam. This includes information related to TF2, this information also includes the Match History of all Matches you played in Casual or Competitive. This is a fork of the tool which allows you to analyze this data by giving you a organized .csv file to use **after you download it as HTML page (yourself, a helper script is included on the page, just scroll to the bottom.)**. You can use the original site and get the script to load your match history [here](https://netroscript.github.io/TeamFortressMatchHistoryAnalyzer/) if you want to get a .csv you need to download it


How it works
------------

You can upload a (html) file, and the JavaScript accesses it and parses it (assuming it is from the Match History page). It then creates 2 lists, one with all casual games and one with all competitive games.

Usage
-----

Just download this as a folder, and open index.html in your browser.  




Credits
-------

Following Libraries are included and used:

* [Chart.js](https://www.chartjs.org/) - Licensed under the MIT License
* [chartjs-plugin-datalabels](https://chartjs-plugin-datalabels.netlify.com/) - Licensed under the MIT License

Additionally the TF2 icon from [http://www.teamfortress.com/](http://www.teamfortress.com/) was used as favicon.

All trademarks belong to their respective owners.
