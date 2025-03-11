# Act-3-4-5
def check_number(num):
    if num % 2 == 0:
        print(f"{num} Even number yan bossing.")
    else:
        print(f"{num} Odd number yan bossing.")


print("Check natin yan kung Odd or Even number!")

try:
    chan = int(input("pili ka kahit anong number boss: "))
    check_number(chan)  
except ValueError:
    print("Mali yan boss number lang dapat.")

def ilang_taon(age):
    
    if age < 0:
        print("Invalid age! wag mag enter ng negative age.")
    
    elif age <= 10:
        print("ATABS, CHILD.")
    elif age <= 18:
        print("TUMATANDA KANA, TEEN.")
    elif age <= 65:
        print("MEDYO MATANDA KANA, ADULT.")
    else:
        print("TANDA KANA, SENIOR.")


print("Welcome sa age classifier na kung saan malalaman mo dito kung anong uri kana ng pagkatao")

while True:
    try:
        
        chan = input("Ilang taon kana erp? : ")
        
        ilang_taon(int(chan))
    except ValueError:
        print("Hindi pwede yang may decimal point boss!.")

def chan(score):
    if score < 0:
        print("Invalid score! Please enter a value between 0 and 100.")
         
    elif score <= 60:
        print("You got an F!")        
    elif score <= 69:
        print("You got an D!")        
    elif score <= 79:
        print("You got an C!")        
    elif score <= 89:
        print("You got an B!")        
    elif score <= 100:
        print("You got an A!")
    else: 
        print("Failed.")
       
print("Assigning Grades")

while True:
    try:
        itchan = input("State you Grade: ")
        chan(int(itchan))        
    except ValueError:
        print("Invalid score! Please enter a value between 0 and 100!")
        break

https://youtube.com/shorts/ShOXBMVWlr0?si=giEKwH-75t-wUeBo
