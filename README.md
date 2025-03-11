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
