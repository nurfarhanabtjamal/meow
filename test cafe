# defined function
import time
import sys  # utk function sys.exit()
lives = 5  # Standardized jadi variable "lives"
def loading():
      print()
      print("LOADING [", end="", flush=True)
      for i in range(10):
        time.sleep(0.2)
        print("#", end="", flush=True)
      print("]")

def dot():
      print()
      for i in range(3):
        time.sleep(0.5)
        print(".", end="", flush=True)

def two_space():
    print()
    print()

def th3_space():
    print()
    print()
    print()

# Untuk check if user fill in things other than numbers
def ask_number(question):
    answer = input(question)
    while not answer.isdigit():
        print("Please enter a number.")
        answer = input(question)
    return int(answer)

myName = input("What should I call you?: ")

print("Emergency Exit.")
print()
time.sleep(1)  # fix: tmbh number, tadi time.sleep() kosong so crash
print(f"{myName} rush towards the emergency exit")
print()
time.sleep(1)  # fix: tmbh number, tadi time.sleep() kosong so crash
print(f"{myName}: 'FINALLY! AN EXIT!")
print()
time.sleep(1)
print(f"{myName} grab the door handle")
print()
time.sleep(1)  # fix: tmbh number, tadi time.sleep() kosong so crash
print("*CLICK! *CLICK!")
print()
time.sleep(1)
print("The door won't open.")
print()
time.sleep(1)
print(f"{myName}: 'YOU'VE GOT TO BE KIDDING ME!")
print()
time.sleep(1)
print("Suddenly..")
print()
time.sleep(1)
print("*BANG!  *BANG! *BANG!")
print()
time.sleep(1)
print(f"{myName} hear someone knocking from the other side of the door.")
print("???: 'HELLO?! CAN ANYONE HEAR ME?!!'")
print()
time.sleep(1)
print(f"{myName}: 'YESSS!!! WHO'S THERE????'")
print()
time.sleep(1)
print("???: I'M TRAPPED IN THE EMERGENCY STAIRS!!!! PLEASE HELP ME!!!")
print()
time.sleep(1)
print(f"{myName}: 'Hold on! I- What should I do to get you out?!!")
print()
time.sleep(1)
print("???: 'THE DOOR HAVE SECURITY KEYPAD! I CAN'T OPEN THE DOOR FROM INSIDE!")
print()
time.sleep(1)
print(f"{myName}: 'OKAYYY! I'LL TRY MY BEST!' ")  # fix: myname jadi myName, tadi error
print()
time.sleep(1)
print(f"{myName} try to look for the keypad and found it.")
print()
time.sleep(1)
print("SYSTEM: ACCESS DENIED.")
print()
time.sleep(1)
print("="*40)
print("To unlock the door, solve the following question.")
print("="*40)
print()
time.sleep(1)
print("Security Verification")
print()
time.sleep(1)
print("-"*40)
print("""password = 10

for i in range(3):
    password += 4
print(password)
  """)
print("-"*40)
print()
time.sleep(1)
print("[1] 18")
time.sleep(1)
print("[2] 22")
time.sleep(1)
print("[3] 26")
print()
time.sleep(1)

while True:
  ans = ask_number("Enter your answer (1/2/3): ")  # fix: add error handling
  if ans == 2:
    loading()
    print()
    time.sleep(1)  # fix: tmbh number, tadi time.sleep() kosong so crash
    print("ACCESS GRANTED!")
    print()
    time.sleep(1)
    print("*CLICK!*")
    print()
    time.sleep(1)
    print("The emergency door unlocks.")
    print()
    time.sleep(1)
    print(f"{myName} quickly enter the emergency stair.")
    dot()
    print()
    print("The survivor is nowhere to be seen.")
    time.sleep(1)  # fix: tmbh number, tadi time.sleep() kosong so crash
    print(f"{myName}: 'Hey-- What the.. Hey!! Where are you?!") 
    print()
    time.sleep(1)
    print(f"""{myName} try to search around the stair only to find a handwritten note.""")
    two_space()
    print("-"*40)
    print("Please find me at ///////")
    print("-"*40)
    two_space()
    time.sleep(1)
    print(f"{myName}: What the?- WHERE SHOULD I FIND YOU???")
    time.sleep(2)
    print(f"{myName}: What a troublesome..let's go floor by floor")
    break


  elif ans == 1 or ans == 3:  # fix: and jadi or, sbb ans tk boleh jadi 1 dgn 3 sekali
    loading()
    print()
    time.sleep(1)
    print("ACCESS DENIED!")
    print()
    time.sleep(1)
    print("*BEEP! *BEEP!")
    print()
    time.sleep(1)
    print("WARNING! INCORRECT PASSWORD!")
    print()
    time.sleep(1)
    print("Zombies: huarghghjjjhhhh")
    print()
    time.sleep(1)
    # fix variable name jadi lives + tolak 1 life betul2
    lives -= 1
    print("LIVES:", "<3"*lives)
    if lives == 0:  # game over kalau lives dh habis
        print("GAME OVER! You ran out of lives.")
        sys.exit()
    print()
    time.sleep(1)
    print("Please try again.")
    continue
  else:  # tmbh error handling if user isi other numbers
    print("There are only 3 choices. Enter 1, 2 or 3.")

print("="*6, "EMERGENCY STAIRS", "="*6)
print()
time.sleep(1)
print(f"{myName} are standing on Floor 2")
print()
time.sleep(1)
print("There are three possible directions")
print()
time.sleep(1)
print("[1] Go to upstairs to Floor 3")
time.sleep(1)
print("[2] Go to downstairs to Floor 1")
time.sleep(1)
print("[3] Search the current floor")
print()
time.sleep(1)

while True:
  print()
  time.sleep(1)
  ans = ask_number("Enter your answer (1/2/3): ")  # fix: add error handling
  if ans == 1:
    print()
    time.sleep(1)
    print(f"{myName} are now standing on Floor 3")
    print()
    time.sleep(1)
    print("Suddenly...")
    print()
    time.sleep(1)
    print("*GORAANNNN....*")
    print()
    time.sleep(1)
    print("A zombie is blocking the corridor!")
    print()
    time.sleep(1)
    print(f"{myName} quickly run downstairs.")
    print()
    print("="*40)
    # fix variable name jadi lives + tolak 1 life betul2
    lives -= 1
    print("LIVES:", "<3"*lives)
    if lives == 0:  # game over kalau lives dh habis
        print("GAME OVER! You ran out of lives.")
        sys.exit()
    print("="*40)
    continue
  elif ans == 2:
    print()
    time.sleep(1)
    print(f"{myName} are now standing on Floor 1")
    print()
    time.sleep(1)
    print(f"{myName} slowly walk downstairs.")
    print()
    time.sleep(1)
    print(f"{myName} reach Floor 1")
    print()
    time.sleep(1)
    print(f"{myName} hear someone is calling.")
    time.sleep(1)
    print("???: HELLO?! IS ANYONE THERE?!")
    time.sleep(1)
    print(f"{myName}: YES! I'M HERE!. WHERE ARE YOU?")
    time.sleep(1)
    print("???: COME TO THE EQUIPMENT ROOM!")
    time.sleep(1)
    print(f"{myName}: WHY DO YOU KEEP ON RUNNING!! UGH!!")
    time.sleep(1)
    print()
    print(f"*{myName} slowly approach the locked door* ")
    time.sleep(1)
    two_space()
    print("-- NEW OBJECTIVE: UNLOCK THE EQUIPMENT ROOM.")
    break

  elif ans == 3:
    print()
    time.sleep(1)
    print(f"{myName} are now standing on Floor 2")
    print()
    time.sleep(1)
    print(f"{myName} discover an emergency telephone.") 
    print()
    time.sleep(1)
    print(f"{myName} quickly call the emergency telephone but no one answer.")
    print()
    time.sleep(1)
    print("THUD..THUD..THUD..")
    print()
    time.sleep(1)
    print(f"{myName}: It's no use.. I should go check on the other floor. ")
    print()
    time.sleep(1)
    print(f"{myName} return to the stairs.")
    continue   
  else:
    print()
    time.sleep(1)
    print("There are no floor with that number. Try again.") 
    continue
  
# Equipment room
print("Equipment Room")
print()
time.sleep(1)
print(f"{myName} approach the equipment room.")
print()
time.sleep(1)
print(f"{myName}: Why is the door locked? Hey, how did you come in?")
time.sleep(1)
print("???: You have to break the code given. It's different each time it's locked so I can't lend a hand to you.")
time.sleep(2)
print(f"{myName}: Okay. I'll give it a try.")
print()
time.sleep(1)
print("="*40)
print("""A security monitor displays:
ANSWER THE FOLLOWING QUESTION TO UNLOCK THE EQUIPMENT ROOM.

x = 15
y = 4

print(x % y + y * 2)
""")
print("="*40)
print()
time.sleep(1)

while True:
  ans = ask_number("What is the output?: ")  # fix: add error handling
  if ans == 11:
    loading()
    print()
    print("CORRECT ANSWER!")
    print()
    time.sleep(1)
    print("ACCESS  GRANTED!")
    print()
    time.sleep(1)
    print("*CLICK!*")
    print()
    time.sleep(1)
    print("The door unlocks.")
    print()
    time.sleep(1)
    print(f"{myName} quickly enter the equipment room.")
    print()
    time.sleep(1)
    print("A frightened man is sitting behind a storage cabinet.")
    time.sleep(1)
    print("DR. DANIEL: You finally found me!")
    time.sleep(1)
    print(f"{myName}: Are you okay?! Of course I would find you! My hand has got bitten by a zombie!")
    time.sleep(1)
    print("DR. DANIEL: What? Oh no!. Let me see.")
    print()
    time.sleep(1)
    print(f"{myName}: *show their wrist that has got bitten by a zombie.*")
    print()
    time.sleep(1)  
    print(f"DR. DANIEL: *Proceed to take something out from his pocket and pour it on {myName} wrist*")
    print()
    time.sleep(2)
    print(f"{myName}: Ughhhh, it hurts so much..")
    time.sleep(1)
    print("DR. DANIEL: It's going to be hurt a lil bit but you will be fine after 5 minutes. Thank you for searching me.")
    time.sleep(1)
    print(f"{myName}: Not yet..We still have to get out of here. How to get to the exit from here?")   
    time.sleep(1)
    print("DR. DANIEL: We have to go to the basement parking.")
    time.sleep(1) 
    print(f"{myName}: Alright then. Let's hurry!.")
    print()
    time.sleep(1)
    print(f"{myName} and DR. DANIEL rushes to the basement parking")  # fix: tmbh f so nama player keluar
    break
  else:
    loading()
    print("ACCESS DENIED!")
    print()
    time.sleep(1)
    print("*BEEP! *BEEP!")
    print()
    time.sleep(1)
    print("WARNING! INCORRECT PASSWORD!")
    print()
    time.sleep(1)
    print("Zombies: huarghghjjjhhhh")
    print()
    time.sleep(1)
    lives -= 1
    print("LIVES:", "<3"*lives)
    if lives == 0:  
        print("GAME OVER! You ran out of lives.")
        sys.exit()
    print()
    time.sleep(1)
    print("Please try again.")
    continue

print("Basement Parking.")
print()
time.sleep(1)
print(f"{myName} and DR. DANIEL: *Enter the basement parking*")
print()
time.sleep(1)
print(f"{myName}: Where should we go?")
time.sleep(1)
print("DR. DANIEL: There should be two passages if we go straight ahead and see the sign board.")
time.sleep(1)
print()
print(f"{myName} and DR. DANIEL walks toward the sign board")
time.sleep(1)
print()
print("-"*50)
print("""                 << SIGN BOARD >>
            STAFF PARKING <<            >> VISITOR PARKING""")
print("-"*50)
print()
time.sleep(1)
print(f"{myName}: Staff parking is more likely to be empty but we can't be sure.")
time.sleep(1)

while True:
   choice = input("DR. DANIEL: yeah. so which will it be? (<</>>): ")  # fix: loop non stop
   if choice == ">>":
    print(f"{myName} and DR. DANIEL rushes towards the exit in the visitor parking.")  # fix: tmbh f so nama player keluar
    print()
    time.sleep(1)
    print(f"{myName} and DR. DANIEL reach at the exit but the exit is blocked by a parking gate barrier")  # fix: tmbh f so nama player keluar
    print()
    time.sleep(1)
    print("SYSTEM: EMERGENCY LOCKDOWN ACTIVE.")
    print()
    time.sleep(1)
    print("DR. DANIEL: WE'RE SO CLOSE!")
    time.sleep(1)
    print(f"{myName}: There has to be a way!")
    print()
    time.sleep(1)
    print("="*70)
    print("            EMERGENCY LOCKDOWN CAN BE DEACTIVATED IF FINAL VERIFICATION IS PASSED.     ")
    print("="*70)
    break
   elif choice == "<<":
    print(f"{myName} and DR. DANIEL rushes towards the exit in the staff parking only to find the exit is being swarmed by zombies.")  # fix: tmbh f, and << tu staff parking
    print()
    time.sleep(1)
    print("Zombies: huagrhhhguhrghhh")  # fix: tmbh "" sbb ni text, bukan variable
    print()
    time.sleep(1)
    print(f"{myName}: GET BACK! GET BACKK!!!")
    print()
    time.sleep(1)
    # fix variable name jadi lives + tolak 1 life betul2
    lives -= 1
    print("LIVES:", "<3"*lives)
    if lives == 0:  # game over kalau lives dh habis
        print("GAME OVER! You ran out of lives.")
        sys.exit()
    print()
    time.sleep(1)
    print("Please try again")
    continue
   else:
    print()
    time.sleep(1)
    print("DR. DANIEL: We only have two choices here buddy. << or >>")
    continue

# fix indent
print("====== FINAL VERIFICATION ======")
print()
time.sleep(1)
print("-"*40)
# fix: tmbh ":" yg tertinggal kat def
print("""def unlock(x,y):
    result = x*y
    return result  + 5
print(unlock(3,4))""")
print("-"*40)
print()
time.sleep(1)
print("What's your answer?: ")
print()
time.sleep(1)

while True:
    ans = ask_number("Enter your answer: ")  # fix: add error handling
    if ans == 17:
      print("VERIFICATION PASSED!")
      print()
      time.sleep(1)
      print("*CLICK!*")
      print()
      time.sleep(1)
      print("EMERGENCY LOCKDOWN DISABLED!")
      print()
      time.sleep(1)
      print("The emergency exit slowly opens.")
      print()
      time.sleep(1)
      print("DR. DANIEL: IT'S OPEN!!!")
      time.sleep(1)
      print(f"{myName}: COME ON!! LET'S GO!")
      print()
      time.sleep(1)
      print(f"{myName} and DR. DANIEL rush outside.")  # fix: tmbh f so nama player keluar
      print()
      time.sleep(1)
      print("The emergency exit closes.")
      break

    else:
      print("VERIFICATION FAILED!")
      print()
      time.sleep(1)
      print("!! WARNING !!")
      time.sleep(1)
      print("INCORRECT ANSWER!")  
      print()
      time.sleep(1)
      print("Zombies are approaching")
      print("huarghhhhhagh")
      print()
      time.sleep(1)
      print(f"{myName} and DR. DANIEL: ARGHHHHHH RUNNNN!!!!")
      print()
      time.sleep(1)
      # fix variable name jadi lives + tolak 1 life betul2
      lives -= 1
      print("LIVES:", "<3"*lives)
      if lives == 0:  # game over kalau lives dh habis
          print("GAME OVER! You ran out of lives.")
          sys.exit()
      print()
      time.sleep(1)
      print("TRY AGAIN.")
      continue

print("="*40)
print("GAME OVER.")
print("="*40)
two_space()
print("SURVIVOR RESCUED: YES.")
print("HOSPITAL ESCAPED: YES.")
print()
time.sleep(1)
print(f"DID {myName} AND DR. DANIEL SURVIVED?")
print()
time.sleep(1)
print("YES. -- MISSION COMPLETED. --")