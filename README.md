# geographystatista
I have developed the geography package for statista.
Sometimes, when manager collect the geographical data of clients. They will either miss the city, state, or write the country wrong. When analyst received the dataset, it always just show part of the geographical data. And excel is lack of functions to fix the missing columns.
For fixing the problem and automate the process of combining dataset, I have written one dictionary for dealing with missing geography data. It is devided into two parts.
1) How to write the a excel spreadsheet with data of city and state into a python dictionary.
2) The automation codes- Upload the dataset, and refresh. Then you will have one dataset with city, state and the larger city which has the airport. 
