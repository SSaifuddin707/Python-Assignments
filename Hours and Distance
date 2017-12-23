import sys, os
def res():
	restart = input("Would you like to restart? [Y/N]\n")
	if (restart == "Y") or (restart == "y"):
		os.system("cls")
		distance()
	elif (restart == "N") or (restart == "n") or (restart ==""):
		sys.exit()

def distance():
	speed = input("How fast was the vehicle going in miles per hour?\n")
	hours = input("How many hours has the vehicle traveled?\n")

	print("Hours   Distance Traveled")
	print("-----------------------------")

	for hours in range(1, int(hours)+1):
	    distance = int(speed) * int(hours)
	    print(hours,"           ",distance)
	res()

distance()


