# Creator: Anthony Bordens
import sys
import time

a = 2
b = 0.2
c = 0.08




def intro():
    print()
    print("(It's a bright sunny day)")
    time.sleep(a)
    print("Mom got mad at me for the 4th time this week cause all I do is sleep and play Fortnite.")
    time.sleep(a)
    print("I mean I do get bored not having a job and being home all day but when I go pro i'll be the one laughing.")
    time.sleep(a)
    print("Ehhh maybe I should go speak with a recruiter, I heard the military is fun and you get paid a lot.")
    time.sleep(a)
    print()
    print("Plus I know Jason from my spanish class just bought himself a 2020 Mustang and he\'s in the Marine Corps.")
    print()
    print()
    s = ("1 Hour later")
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)
    print()
    print("Thanks for the ride mom!")
    time.sleep(a)
    print("Alright we have the Army,Navy and the Marine Corps here.")
    time.sleep(a)
    print("I wonder where the Air Force recruiter is at... oh well.")
    time.sleep(a)
    print()
    print("#1 Navy office: Come on in squid, the water is just fine. ")
    time.sleep(a)
    print("#2 Army office: Hey buddy! You don't just look strong you look Army Strong.")
    time.sleep(a)
    print("#3 Marine Corps office: Hey %$^$#@ get over here! You look lost come on in I just baked some fresh Crayons.")
    time.sleep(a)
    print()
    firstPath = input("Which path should I pick? (1/2/3): ")
    if firstPath == '1':
        print()
        path1()
    elif firstPath == '2':
        print()
        path2()
    elif firstPath == '3':
        print()
        path3()


def path1():
    print()
    print('"Do I know squid when I see one or what?"')
    time.sleep(a)
    print('"Have you ever wanted to see the world? The Navy is like being on a cruise,except you get PAID!"')
    time.sleep(a)
    print('"I mean yeah I guess the world is 70% water and I mean yeah I guess that\'s not that exciting BUT,"')
    time.sleep(a)
    print('"at least you \'ll be able to see some dolphins... probably."')
    time.sleep(a)
    print('"We do however offer a enlistment bonus of 2000 its small but at least its more than those"')
    time.sleep(a)
    print('"Marines next door they don\'t ever have money to give."')
    time.sleep(a)
    print()
    print("#1 Hmmm you know what I am down bring in the dolphins!")
    time.sleep(a)
    print("#2 Im going to have to think about it im not the best swimmer and I get sea sick easily.")
    time.sleep(a)
    print()
    fourthPath = input("So what do you say son can I get you committed to joining the worlds greatest Navy? (1/2): ")
    if fourthPath == '1':
        path4_1()

    elif fourthPath == '2':
        path4_2()

def path4_1():
    print()
    print("Congrats on graduating bootcamp in Chicago! You are now officially a sailor!")
    time.sleep(a)
    print("You are now on your way to A-school and you met someone on the plane ride there, she also just graduated.")
    time.sleep(a)
    print("Unfortunately upon completion of A-school you both got stationed on separated parts of the world.")
    time.sleep(a)
    print("As you get to your new unit you quickly find out that they aren\'t a fan of your unique comedic jokes.")
    time.sleep(a)
    print("Eventually you say the wrong joke and one of the motivated officers over heard your joke and reported,")
    time.sleep(a)
    print("up the chain of command and it led to you losing rank and 15 days on restriction.")
    time.sleep(a)
    s = "You decided that it was best to just keep your mouth shut and serve your time honorably. You lose..."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)

def path4_2():
    print()
    s = "You went ahead and left to college....still became a broke college student."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)







def path2():
    print()
    print('"HEY SOLDIER!"')
    time.sleep(a)
    print('"Glad you decided to come here. Oh you thought this was the Air Force? Yeah are they never are in their"')
    time.sleep(a)
    print('"office.You don\'t look like you wanted the easy route anyways. Here in the Army we make sure to make"')
    time.sleep(a)
    print('"things hard for no reason its what we pride ourselves in. Granted I know were not as good as the "')
    time.sleep(a)
    print('"Marines but hey,nothing is wrong with second place. Plus we have way bigger enlistment bonuses."')
    time.sleep(a)
    print()
    print("#1 HECK YEAH SHOW ME THAT CASH!")
    time.sleep(a)
    print("#2 No I think im going to weigh my options first.")
    time.sleep(a)
    print()
    fifthPath = input("Are you ready to be not just strong...but Army strong? (1/2): ")
    if fifthPath == '1':
        path5_1()

    elif fifthPath == '2':
        path5_2()


def path5_1():
    print()
    print("Upon completion of basic training you earned the title of Soldier and it was one of your proudest moments.")
    time.sleep(a)
    print("You completed your MOS School training with ease and even became the honor grad. ")
    time.sleep(a)
    print("You became extremely cocky and arrogant which led you to be over confident in your ability,")
    time.sleep(a)
    print("so one day you didn't double check your work which resulted in costing your unit over a million dollars")
    time.sleep(a)
    print("worth of damage. Thus cementing your reputation and an incompetent worker and never getting promoted.")
    time.sleep(a)
    s = "YOU LOSE TRY AGAIN."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)


def path5_2():
    print()
    s = "You went ahead and left to college....still became a broke college student."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)


def path2_1():
    print()
    print("Congratulations your ship date is 2 months from now.")
    time.sleep(a)
    print("(2 months later you arrive at MCRD San Diego.)")
    time.sleep(a)
    print("After some time on the depot you and your platoon were awarded as they Honor platoon.")
    time.sleep(a)
    print("Congratulations! You have completed bootcamp and now a United States Marine.")
    time.sleep(a)
    print("After months of completing Marine Combat Training and your MOS school you have the choice between,")
    time.sleep(a)
    print("the West Coast or the East Coast for your first duty station. Which one will you choose?")
    time.sleep(a)
    print()
    print("#1 West Coast best coast!")
    time.sleep(a)
    print("#2 East Coast all day!")
    time.sleep(a)
    print()
    thirdPath = input('Where would you like to get stationed? (1/2): ')
    if thirdPath == '1':
        path3_1()
    elif thirdPath == '2':
        path3_2()


def path2_2():
    print()
    s = "You went ahead and left to college....still became a broke college student."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)

def path3():
    print('"I knew you would come in, I can spot a future Devil Dog when I see one."')
    time.sleep(a)
    print('"Do you have a girlfriend? No? just wait til you put these on, you wont know what to do with yourself."')
    time.sleep(a)
    print('"So I know you said you wanted to be Recon and although your 4 pull ups are a amazing start."')
    time.sleep(a)
    print('"I have a spot open in supply! You ever heard bullets don\'t fly without supply?"')
    time.sleep(a)
    print('"You will definitely deploy they see more combat than MARSOC and Grunts combined!"')
    time.sleep(a)
    print('"Oh you asked about a bonus right? Yeah we arent fans of giving out money because we never have any"')
    time.sleep(a)
    print('"Yeah our bootcamp is the longest and most physically demanding and you wont get your phone, so?"')
    time.sleep(a)
    print('"BUT have you seen the uniforms?"')
    time.sleep(a)
    print()
    print("#1 Yeah sure i'll join")
    time.sleep(a)
    print("#2 I don\'t know it seems like it not that cool of a branch to join why would i always want to feel broke?")
    time.sleep(a)
    print()
    secondPath = input("Will you join the Marine Corps? (1/2): ")
    if secondPath == '2':
        path2_2()
    elif secondPath == '1':
        path2_1()

def path3_1():
    print()
    print("Awesome! You just got orders to Oceanside California!")
    time.sleep(a)
    print("You now belong to CLB-5 and now their youngest supply Marine full of motivation!")
    time.sleep(a)
    print("After just a quick 6 months you were promoted to the rank of Lance Corporal.")
    time.sleep(a)
    print("You experienced your first field op and after 4 months of the beautiful 29 palms weather you were")
    time.sleep(a)
    print("acknowledged by your battalion commander who awarded you a Navy Achievement Medal.")
    time.sleep(a)
    s = "YOU WIN...Thanks for playing Lance Cooly keep on the motivation OOOOORAHHHHHH."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)


def path3_2():
    print()
    print("Upon arriving to Camp Lejeune, you met a shady car salesman who sold you your own 2020 Mustang at 31% APR.")
    time.sleep(a)
    print("Because of your newly acquired debt, it has put a financial burden on you. Thus having you seek out help")
    time.sleep(a)
    print("from your chain of command resulting in you getting negative paperwork and being overlooked for promotion.")
    time.sleep(a)
    print("Given the negative paperwork it caused you to lose motivation and just ride out your four year commitment,")
    time.sleep(a)
    print("without getting promoted to the next rank.")
    time.sleep(a)
    print("")
    s = "YOU LOSE....Thanks for playing PFC."
    for character in s:
        sys.stdout.write(character)
        sys.stdout.flush()
        time.sleep(b)
    time.sleep(1)
    time.sleep(a)




print()
print()
print("              #######################################")
print("              #                                     #")
print("              #      Picking a military branch      #")
print("              #                                     #")
print("              #######################################")
print()
print()
time.sleep(a)
print("Awwwww man, I want to join a military branch but I cant decide on which one.")
time.sleep(a)
print("Maybe I should go talk to a recruiter.")
time.sleep(a)
print()
startGame = input("Want to come and talk to the recruiter with me? (Y/N): ")
if startGame == 'n' or startGame == 'N':
    print("You're right... I should just go to college.")
elif startGame == 'y' or startGame == 'Y':
    intro()










