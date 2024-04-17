# Find_Lost_Dog_TBG

 A TBG (text based game) is a game where text is displayed in the python shell, 
 then the user inputs one of the options available for what they want their next move to be. My TBG will take place in a forest. 
 This is merely the pseudocode for my game as I have not began coding it yet. 


# Installation

 Need at lest python 3.1 in order to play this game.


# Run the Program

```python
python game.py
```


## The Pseudocode for the Game
# TBG Pseudocode - Kaden Whiteside
# Apiril 15, 2024


# This python file is dedicated to a pseudocode for my TBG
# It will be a fully commented rough outline of what my game will look like


# Beginning
    # background information about the setting and what is going on
    # you're with your dog, etc
   
   
# Dog's name
    # ask for the dog's name
    # that name will then be input for every (dog's name) seen in the code
    # it will look kind of like this
    # name = input("What is your dog's name? ")                                         # The whole game will be text based, so the user inputs their answer
    # print(f"Your dog's name is:", name)                                               # I won't put example text for every single function


# Cooking USER ACTION
    # 2 choices that have four outcomes (2 potential outcomes for each code):
    # 1. you go to the bathroom:
        # a. You leave your fire to do your business and when you return your
        # food is cooked perfectly, but that's not all! (Dog's name) is missing!
        # b. You leave your fire to do your business but when you return all your
        # food is burnt, that's not all! (Dog's name) is missing!
    # 1. # You stay at the fire to cook your meal and rishk soiling your pants
        # a. You stay to cook and you manage to hold it off until you're done. You go
        # to the bathroom to do your business but when you return (dog's name) is missing.
        # b.  You stay to cook but you soil yourself, now you must clean it up so you
        # return to your tent, when your return (dog's name) is missing.
    # All outcomes then ask another question with one possible outcome:
    # 1. You eat to fill your stomach and clear your mind, (dog's name) probably
    # just found a squirrel or something. 
    # 2. You don't waste one second you immediately start looking for (dog's name).
   
   
# Pathways USER ACTION
    # This is where the game divergerges into two paths, I'll start with the left option
    # Here is what the user action question asks:
        # USER ACTION: Luckily you've trained (dog's name) well and they know not to leave
        # the trails because this forest has lions, tigers, and bears (oh my). There are two
        # trails to choose from: The trail on the left is pitch black from all the trees
        # blocking the moonlight but it's smooth and not dangerous. The trail on the right
        # is well lit, however it is rocky, steep, and dangerous. Which do you choose?

       
# Left:
    # USER ACTION: You go left. Your flashlight is very helpful here, do you patiently walk
    # through the trail, observing as much as possible, or do you rush through it to try and
    # find (dog's name)? 
    # outcome 1:
        # You run, you must find (dog's name) before it is too late, this is a dangerous forest,
        # your fast action and aimless running are your downfall, you are lost. You now must wait
        # until daybreak to figure out where you are. You have failed to find (dog's name). 
        # This outcome results in the game ending.
    # outcome 2:
        # You venture through the forest with caution, it is easy to get lost at night. After
        # walking through bushy trails for a while, you come to an opening, there are eyes
        # staring at you from across the opening.
   
    # USER ACTION: Do you head back down the trail? Or do you decide to go onward with caution?
    # This has 2 outcomes, they are:
    # outcome 1:
        # Heading back down the trail brings you back to your camp.
        # This returns the user back to the fork in the paths
        # They will once again get the choice between going left and going right
        # from there they carry on the same exact way, nothing new will happen on the second -
        # - go around
        
    # Proceeding with caution you approach the ominous eyes.... It's a tiger! The tiger tells
    # you her name is Marrr. She tells you she will not let you pass. You plead with her,
    # telling her that your dog is lost and you must find it. Marrr says she likes to play games.
    
    # USER ACTION: You offer to play rock paper scissors against Marrr, she tells you beforehand
    # that she always picks rock, do you believe her? She also says that if you tie her, you must
    # turn around and go to the other path, and if you lose then she gets to eat you. Which do you
    # pick: rock, paper, or scissors?
    # Once again the user is given three options:
    # option 1:
        # You pick scissors. This means that you lose and Marrr gets to eat you. You have failed
        # to save (dog's name).
        # This means that the user must restart the game, because they have died
    # option 2:
        # This option has yet another USER ACTION within it, here it is:
        # USER ACTION: You pick rock too, It's a draw, you now must go the other way. Do you
        # continue the other way? Or do you try to go back the same way in hopes that Marrr
        # forgets about you?
        # option 1:
            # This option brings the user back to the beginning of the rock paper scissors game.
        # option 2:
            # You go to the beginning of the right trail.
    # option 3:
        # You pick paper. You win! Marrr lets you pass by, she also tells you that there is a
        # lion named Bungus that is friendly and willing to help you on your journey. He likes
        # to be in bushes. 
        # The storyline then continues from here:
        # The forest  gets darker and thicker. It is nearly impossible to see now without the
        # flashlight, but you hear rustling in the bushes. "Marrr sent me." You exclaim.
        # Bungus appears, he says he knows where your dog went, even without you asking, boy he
        # really is friendly. 
        
        
# Now since the LEFT options are completed and they won't be revisited until the right option -
# - catches up in terms of the chronology of the storyline, lets get into the RIGHT now.


# RIGHT
     # USER ACTION: You go right, you approach the cliff. Do you climb it as it's faster,
     # however more dangerous (25% chance of success)? Or do you go around it to be safe
     # but take more time (100%)? 
     # There are three outcomes, here they are:
     # option 1:
         # You climb the cliff
         # You fall and injure yourself severely, you must make it back to your camp to
         # call for help, you can no longer find (dog's name).
         # This results in the game once angain ending
    # option 2:
        # You climb the cliff
        # You coninue on as normal
    # option 3:
        # This option results in another USER ACTION with two outcomes:
        # USER ACTION: Going around is safe and it still gets you to the top of the cliff,
        # you start to hear murmuring in the bushes. You can't figure out what or who is making
        # that noise. Do you investigate or do you move on?
        # option 1:
            # You continue onward, ignoring the sounds coming from along the path
            # This option reconnects the user with the same chronological pathway as the -
            # - sucessful cliff climb. Here that is:
                # USER ACTION: You get to the top of the cliff. When you reach the top
                # you see (dog's name)! They're eating a big supply of honey. That can only
                # mean one thing, that honey belongs to a bear. You don't know if there is a
                # bear nearby, do you call (dog's name)?'
                # Two options:
                # option 1:
                    # You call (dog's name), both (dog's name) and the bear hear you. The bear
                    # finds you first and your dog runs away, you have failed in finding (dog's
                    # name).
                    # This option results in the user being forced to restart, the game has ended.
                # option 2:
                    # You don't call (dog's name). Instead you try to get closer to see if there is
                    # a bear nearby, there is! Not to worry, the bear is unaware of your presence.
                # USER ACTION: Do you approach the bear and tell him what is going on in hopes
                # that he will understand? Or do you try and sneakily get your dog to notice you
                # without the bear noticing (25% success rate)?
                # There are 3 outcomes based off the two options
                # outcome 1:
                    # You successfully get (dog's name's) attention without the bear noticing!
                    # This means that you have found your dog safe and sound! Yipee!
                    # THis would end the game, however not as a failure, but as a sucess -
                    # - as the user would have completed the goal.
                # outcome 2:
                    # You go to the bear, you tell him everything that has happened over the
                    # coarse of the night. The bear was initially angry, but after you explained
                    # everything he calmed down and came to understand your side of the story.
                    # He lets you and your dog go without any trouble, you thank the bear and head
                    # on your merry way!
                    # THis would end the game, however not as a failure, but as a sucess -
                    # - as the user would have completed the goal.
                # outcome 3:
                    # Sneaking towards (dog's name) has failed! Now the bear has noticed you.
                    # You have enough time to get away so you run for it! While running back to
                    # your camp with (dog's name), you notice that the bear is following you closely.
                    # You and (dog's name) are cornered at your campsite, there is nothing more you
                    # can do! Until....
                    # We are now at the end point, let's go back to option 2 from the sound from the-
                    # - bushes USER ACTION. This will connect all the dots.
        # option 2:
            # This option takes the user on a completely different pathway, here that is:
            # You inch closer to the bushes, it's a lion! But it doesn't attack you, no no.
            # This is a friendly lion. The Friendly Lion tells you his name is Bungus. Bungus
            # tells you that your dog went running up this very trail, but there is a bears den
            # at the top of the cliff that this trail leads to.
            # This next text line is the point where the LEFT and RIGHT trails connect, here it is:
            # You and Bungus head up the trail, you reach the top and the bear is there, so is (dog's
            # name). But the bear has (dog's name) trapped.
            # USER ACTION: Do you have Bungus distract the bear while you grab (dog's name) [25%
            # success rate]? Or do you decide to be honest, and approach the bear to tell him
            # what you did?
            # This has three possible outcomes, two of them result in a sucessful game that ends-
            # - the user comleting the task
            # Here are those two
            # winning outcome 1:
                # Bungus distracts the bear by discussing the local penguin soccer league with him!
                # You manage to escape with your dog back to your camp. It's as though nothing even
                # happend, hooray!
            # winning outcome 2:
                # You go to the bear, you tell him everything that has happened over the coarse of
                # the night. The bear was initially angry, but after you explained everything he
                # calmed down and came to understand your side of the story. He lets you and your dog
                # go without any trouble, you thank the bear and head on your merry way!
                # Yes, this one is the same as the other RIGHT branch.
            # The third outcome continues the TBG
            # outcome 3:
                # Bungus fails to distract the bear and it notices as you try to get your dog away
                # from the honey. You jump on Bungus you all run back to camp, the bear follows. You
                # get cornered at your camp, but the bear smells something.
                # After this everything will be connected
                
              
# THE END
  # USER ACTION: The bear smells more honey from your honey butter. Do you offer it to the bear or do you
  # pretend like you don't know where the smell is coming from?
  # 2 outcomes, here they are:
  # outcome 1:
      # You offer your honey butter to the bear. The bear thanks you and it says that because you gave him
      # honey butter, he will call it even. He lets you and (dog's name) go.
      # This is the winning outcome, therefore the game will end with a "You Win!" being printed
  # outcome 2:
      # You play it off, the bear gets angrier. It tears through your camp looking for the source of the smell!
      # He destroys everything an there is nothing you can do to stop it, then he runs off. This means that
      # your mission to get your dog - while successful - has left you without a safe space to spend the night.
      # This is a loss, therefore the game will end saying "You failed, try again."
