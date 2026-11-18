event_title = str(input("Event title: "))
year = int(input("Year: "))
month = int(input("Month(1 to 12): "))
day = int(input("Day: "))
months = ["January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]
weekday = [days[((day) % 7) - 1]]
def date(year, month, day):
    print("Date: ",months[month], day, year)
print("Formatted output: ")
print("Event: ", event_title.upper())
date(year, month - 1, day)
print("Year: ",year)
print("Month: ",months[month - 1])
print("Day: ",day)
print("Weekday: ", days[((day) % 7) - 1])
