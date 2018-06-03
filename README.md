# infinity
Practice
print "Welcome to my Introvert/Extravert Personality Quiz!"
looping = True
while looping:   
    answer = raw_input("Would you like to begin? Y or N?")
    if answer == "Y":
        print "Great! Let's begin!"
        looping = False
    elif answer == "N":
        print "Please try again. I want you to play this quiz!"
a_count = 0
b_count = 0
print ""

looping_1 = True
while looping_1:
    print "A.) Day at the beach, city, or park enjoying myself"
    print "B.) Hanging out with friends and family doing actitivies"
    print "C.) A & B"
    q1 = raw_input("What does your perfect day look like? ")
    if q1 == "A": 
        looping_1 = False
        a_count += 1
    if q1 == "B":
        looping_1 = False
        b_count += 1
    if q1 == "C":
        looping_1 = False
print ""

looping_2 = True
while looping_2:
    print "A.) Being in my own company of course!"
    print "B.) Socializing!"
    print "C.) Depends on the day and how I'm feeling!"
    q2 = raw_input("Do you feel re-energized by socializing or being in your own company?")
    if q2 == "A": 
        looping_2 = False
        a_count += 1
    if q2 == "B":
        looping_2 = False
        b_count += 1
    if q2 == "C":
        looping_2 = False
print ""

looping_3 = True
while looping_3:
    print "A.) A little drained and will probably stick to myself for the rest of the day"
    print "B.) Great! Going to catchup with some co-workers/friends after work for drinks"
    print "C.) Alright but I would like to sit bymyself for a bit before meeting up with someone"
    q3 = raw_input("You've talked to 37 people today at work! Do you typically feel a little.....")
    if q3 == "A": 
        looping_3 = False
        a_count += 1
    if q3 == "B":
        looping_3 = False
        b_count += 1
    if q3 == "C":
        looping_3 = False
        
print ""
print "Your answer is!"
if a_count >= 2: 
    print "Great! You might be an Introvert that is very introspective and a very deep thinker!"
elif b_count >= 2:  
    print "Great! You might be an Extravert! Now go out there and fly you social butterful you! "
else: 
    print "Awsome You might just be both Introvert and Extravert!! Most people are and you carry the strengths of both!"
    
 

