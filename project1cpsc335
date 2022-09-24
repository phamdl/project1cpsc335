def diskSort(disk):
    count = 0
    for i in range(len(disk)):
	#take each dot and compare them
	for j in range(0, len(disk) - i - 1):
            #take the dot and dot to the right and compare them
            if disk[j] < disk[j + 1]:
                #the position of the dot are swapped
                temp = disk[j]
                disk[j] = disk[j+1]
                disk[j+1] = temp
                count+=1
    print(count)
           
 
 
 
#black disk are 1, white are 0
#the integer n is inputted
n = int(input("Input a positive integer: "))
#n is multiplied by 2
DiskNum = 2 * n
#creates an empty list with 0 
data= [0]

for k in range(DiskNum-1):
    #given the disk number, sort the list in a black and white pattern
    if data[k] == 0:
        data.append(1)
    if data[k] == 1:
        data.append(0)

print('Number sorted: ')

diskSort(data)

print('Final list: ')
print(data)
