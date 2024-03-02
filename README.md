total_minutes = input ("please type the  number of  minutes \n")
int_minutes = int(total_minutes)
hour = int_minutes // 60
minutes = int_minutes % 60
print("this coures is: " + str(hour) + "houres and " + str(minutes) + "minutes long")
