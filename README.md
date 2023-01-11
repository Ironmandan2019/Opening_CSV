# Opening_CSV
This is a shortcut way to copy and paste functions needed for opening a CSV File

from csv import reader

opened_file = open('') ## add CSV string here
read_file = reader(opened_file)
apps_data = list(read_file)
