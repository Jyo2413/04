input=str(input('Enter a string of digits: '))
List=['1','2','3','4','5','6','7','8','9','0']
for dig in List:
count=0
for character in input:
if dig==character:
count+=1
print('Number of ',dig, ': ' ,count)
