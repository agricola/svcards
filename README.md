# svcards
Shadowverse card search

Import svcards and run search_cards(search_term, callback, json_data) where callback is a function that will receive the results such as print or bot.say in sopel and where json_data is an optional argument of type dict (if left blank it will do a get request for the data of all cards)

OR

Run svcards.py in your command line with your search term as your first argument and the second being the optional json_data as described above