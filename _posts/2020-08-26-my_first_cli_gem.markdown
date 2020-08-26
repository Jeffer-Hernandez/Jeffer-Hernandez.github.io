---
layout: post
title:      "My First CLI Gem"
date:       2020-08-26 13:10:25 -0400
permalink:  my_first_cli_gem
---

This project has been one of the most challenging yet satisfying parts of my coding journey. I've never written any code that wasn't to pass a "test", or some specific feature that was being checked for. This is the first time that the purpose, design, and implentation was all my idea. I set up my own environment and created my own directories. I felt like *real* software engineer.

This assignment absolutely came with its own challenges that needed to be overcome. I needed to decided whether I was scraping data from a website, or requesting data from an API. That decision alone was so exciting. I would be working with actual data from the real world! I ultimately chose to work with an API, as there were many exciting API's that offered data about Crypto Currency, which is a field that I am interested in. 

The project was designed to request data about 10 currencies. Then, depending on the currency chosen from the menu, you would receive the Bitcoin exchange rate for the currency. This would be useful for those looking to trade Bitcoin, or for those looking for arbitrage opportunities between different exchanges.

The gem takes the parsed data from the API in JSON format and saves key/value pairs in class atttributes to be used for each instance of a currency. Each currency is delivered to my currency class one at time and is instantiated with these attributes, then saved in a class variable. That way they can be accessed in my CLI class for selection purposes on a menu, or to show the user actual data. This project was a blast to work on! I tore some hair out, but ultimately learned alot, and I can't wait to get started on the next one. 
