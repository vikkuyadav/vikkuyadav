- 👋 Hi, I’m @vikku

green="\033[3;32m"
neon="\033[3;36m"
nc="\033[00m"
red="\033[3;31m"
purple="\033[3;34m"
yellow="\033[3;33m"
voilet="\033[3;35m"

def hero():
    def load():
        # for i in tqdm(range(10)):
        #     sleep(0.1)
        with alive_bar(100, force_tty=True) as bar:
            for i in range(100):
                time.sleep(0.7)
                bar()


if (i==0):
                 load()
                 print("Period: 1           Colour  Green")
                 #system(Commands)
                 time.sleep(30)
             if (i==1):
                 load()
                 print("Period: 2           Colour  Green")
                 #system(Commands1)
             if (i==2):
                 load()
                 print("Period: 3           Colour  RED")
                 #system(Commands2)
             if (i==3):
                 load()
                 print("Period: 4          Colour  RED ")
                 #system(Commands3)
             if (i==4):
                 load()
                 print("Period:  5          Colour  GREEN ")
                 #system(Commands4)
             if (i==5):
                 load()
                 print("Period: 6           Colour  GREEN ")
                 #system(Commands5)
             if (i==6):
                 load()
                 print("Period:  7          Colour  Red ")
                 #system(Commands6)
             if (i==7):
                 load()
                 print("Period:   8         Colour Red ")
                 #system(Commands7)
             if (i==8):
                 clear()
                 load()
                 print("Period:  9          Colour Red") 
                 #system(Commands8)
             if (i==9):
                 clear()
                 load()
                 print("Period:  10          Colour Green ")
                 #system(Commands9)
             if (i==10):
                 clear()
                 load()
                 print("Period:            Colour Green ")
                 #system(Commands10)
             if (i==11):
                 clear()
                 load()
                 print("Period:            Colour Green")
                 #system(Commands11)



#  #n = random.randint(1,30)
            #  #  if(n%2==0):
            #  #      c=f"{red}🔴  Red"
            #  #  else:
            #  #      c=f"{green}🟢  Green"
            #  #  print(f"{red}  Period          ", f"{neon}"    ,   load(),     f"{green}     Colour")
            #  #  print(f"{yellow}",newperiod,"            ",c)
            #  print(f"{red}   Period       ", system(Commands))
             newperiod+=1   
             i+=1    
             numbers.append(newperiod)
             y=input("Do you want to play : Press 1 and 0 to exit \n")
             if(y==0):
                 y=False
             if (len(numbers)>12):
                 clear()
                 system('figlet Thank you!!')
                 print("enter next period!!")

