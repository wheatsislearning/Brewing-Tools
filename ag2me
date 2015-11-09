#total pounds of base malt
#extract efficiency (70 to 75%)
#multiply the pounds of base malt by 37PPG (point per pound per gallon, this is typical PPG for base grain)
#ex. 10lbs base malt * 37PPG is 370points (370 * .70 = 259)
#DME = 44PPG and LME = 37PPG



print("THIS IS A PROGRAM TO CONVERT ALLGRAIN TO EXTRACT")
print("\n")
#collecting data about the recipe
basemalt=input("What is the amount of total base malt grain in pounds?")
eff=input("what is your mash efficiency?")
batchsize=input("what is the batch size in gallons?")
print("\n")
print("\n")
print(".........Please wait one second while I analyze your recipe................")
import time 
time.sleep(1)
print("\n")
print("\n")
print("-----------------------------Results:--------------------------------------")
print("\n")
print("\n")
basepoints= float(basemalt) * 37
print("The basepoints (PpPpG) equal.......")
print (basepoints)
actualpoints= float(basepoints) * float(eff)
OG= float(actualpoints) / float(batchsize)
print("\n")
print("the Actual PPG is  ")
print(actualpoints)
print("\n")
print("the expected original gravity is")
print ("1.0" + str(int(OG)))

print("\n")

DME= float(actualpoints) / 44
LME = float(actualpoints) / 37

print("the total amount of Liquid Malt Extract to use is... ")
print(str(LME) + str(" pounds"))
print("\n")
print("OR the total amount of Dry Malt Extract to use is...") 
print(str(DME) + str(" pounds"))
print("\n")

#I would like to calculate LME and DME together in a percentage relative to eachother
howmuchLME=input("how many pounds of LME would you like to use in this recipe?")

math1=  LME - float(howmuchLME)                  #CALC REMAINING POINTS
math2= float(math1) *  37                        #REMAINING POINTS FOR DME
math3= float(math2) / 44                         #amount of DME to use now


print (str(math3) + "  pounds of DME when using " + str(howmuchLME) + " pounds of LME")
print("\n")
print("\n")
OGfromabove = input("what was the OG from above?")
FG = input("what is your anticipated final gravity?")

abv = (float(OGfromabove) - float(FG)) * 131
print ("Your ABV will be " + str(float(abv)) + " percent")
print("\n")
print("CHEERS!." )
