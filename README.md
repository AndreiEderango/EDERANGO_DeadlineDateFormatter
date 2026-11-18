event_title = str(input("Event title: "))
year = int(input("Year: "))
month = int(input("Month(1 to 12): "))
day = int(input("Day: "))
months = ["January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
print("Event: ", event_title)
print("Year: ",year)
if month == 1:
    print("Month: ",months[0])
if month == 2:
    print("Month: ",months[1])
if month == 3:
    print("Month: ",months[2])
if month == 4:
    print("Month: ",months[3])
if month == 5:
    print("Month: ",months[4])
if month == 6:
    print("Month: ",months[5])
if month == 7:
    print("Month: ",months[6])
if month == 8:
    print("Month: ",months[7])
if month == 9:
    print("Month: ",months[8])
if month == 10:
    print("Month: ",months[9])
if month == 11:
    print("Month: ",months[10])
if month == 12:
    print("Month: ",months[11])
print("Day: ", day)
