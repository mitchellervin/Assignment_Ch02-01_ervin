# Assignment_Ch02-01_ervin
Reads the elapsed time in hours minutes and seconds


seconds = eval(input("Enter elapsed time for an event in seconds: "))


print("hours:", int(seconds//3600))
seconds = seconds % 3600


print("minutes:", int(seconds//60))
seconds = seconds % 60


print("seconds:", int(seconds))
