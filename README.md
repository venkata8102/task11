tallies = {'I': 1,'V': 5,'X': 10,'L': 50,'C': 100,'D': 500,'M': 1000}
def romanNumberaltoDecimal(romanNumberal):
sum=0
for i in range(len(romanNumberal)-1):
left = romanNumberal[i]
right = romanNumberal[i+1]
if tallise[left] < tallies[right]:
sum -= tallies[left]
else:
sum += tallies[left]
sum += tallies[romanNumberal[-1]]
return sum 
roman=input("enter roman number :")
ROMANNUMBERALTODecimal(roman)
