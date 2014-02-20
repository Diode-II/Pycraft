import random
import time
import os
def spawn():
    global sandwich
    sandwich = 0
    mobhealth = 0
    global coal
    coal = 0
    global iron
    iron = 0
    global gold
    gold = 0
    global diamond
    diamond = 0
    global silver
    silver = 0
    global tin
    tin = 0
    global copper
    copper = 0
    global ironore
    ironore = 0
    global goldore
    goldore = 0
    global silverore
    silverore = 0
    global tinore
    tinore = 0
    global copperore
    copperore = 0
    global redstone
    redstone = 0
    global lapis
    lapis = 0
    global quartz
    quartz = 0
    global nikolite
    nikolite = 0
    global torch
    torch = 0
    global arrows
    arrows = 0
    global planks
    planks = 0
    global wood
    wood = 0
    global gunpowder
    gunpowder = 0
    global bones
    bones = 0
    global flesh
    flesh = 0
    global armourhealth
    armourhealth = 0
    global sword
    sword ='Empty'
    global swordhealth
    swordhealth = 0
    global dagger
    dagger = 'Empty'
    global daggerhealth
    daggerhealth = 0
    global bowhealth
    bowhealth = 0
    global axe
    axe ='Empty'
    global axehealth
    axehealth = 0
    global hoe
    hoe ='Empty'
    global hoehealth
    hoehealth = 0
    global pick
    pick ='Empty'
    global pickhealth
    pickhealth = 0
    global incave
    incave = False
    global food
    food = 0
    global fcave
    fcave = False
    global deepcave
    deepcave = False
    global ravine
    ravine = False
    global shaft
    shaft = False
    global lavacave
    lavacave = False
    global health
    health = 20
    clear()
    print('hello. Welcome to pycraft')
    n()
    Pause()
    clear()
    print('starting new game....')
    #time.sleep(3.2)
    n()
    print("Generating world...")
    #time.sleep(3.9)
    n()
    print("Generating chunks...")
    #time.sleep(2.3)
    n()
    print("Loading world...")
    #time.sleep(3.4)
    n()
    print("Spawning...")
    n()
    #time.sleep(.3)
    Pause()
    clear()
    print('hi, steve')
    n()
    Sbiome = get_random_biome_op()
    #time.sleep(2.3)
    print("You spawned in the " + Sbiome + " biome.")
    n()
    print("setting up inventory...")
    n()
    Pause()
    clear()
    Cbiome = Sbiome.lower()
    materialt = random.randrange(2)
    testt = random.randrange(2)
    if testt == 1:
        if materialt == 0:
            print("You got a wooden sword.")
            sword = 'wood'
            swordhealth = 60
        if materialt == 1:
            print("You got a stone sword.")
            sword = 'stone'
            swordhealth = 132
    materialt = random.randrange(2)
    testt = random.randrange(2)
    if testt == 1:
        if materialt == 0:
            print("You got a wooden axe.")
            axe = 'wood'
            axehealth = 60
        if materialt == 1:
            print("You got a stone axe.")
            axe = 'stone'
            axehealth = 132
    materialt = random.randrange(2)
    testt = random.randrange(2)
    if testt == 1:
        if materialt == 0:
            print("You got a wooden hoe.")
            hoe = 'wood'
            hoehealth = 60
        if materialt == 1:
            print("You got a stone hoe.")
            hoe = 'stone'
            hoehealth = 132
    materialt = random.randrange(2)
    testt = random.randrange(2)
    if testt == 1:
        if materialt == 0:
            print("You got a wooden pick.")
            pick = 'wood'
            pickhealth = 60
        if materialt == 1:
            print("You got a stone pick.")
            pick = 'stone'
            pickhealth = 132
    testt = random.randint(2,20)
    print("You got " + str(testt) + " planks.")
    planks += int(testt)
    testt = random.randint(2,20)
    print("You got " + str(testt) + " wood.")
    wood += int(testt)
    testt = random.randint(2,75)
    print("You got %d torches") % (testt)
    global torch
    torch += testt
    n()
    Pause()
    n()
    MenuText()
def n():
    print("")
def d():
    n()
    n()
def clear():
    os.system('cls' if os.name == 'nt' else 'clear')
def Pause():
    yolohashtagsuperswaggerswag = raw_input("Press enter to continue")
def SPause():
    yolohashtagsuperswaggerswag = raw_input("")

def Help():
    clear()
    print("---- HELP ----")
    d()
    print("press 'E' to open inventory,")
    n()
    print("press 'M' for main menu.")
    n()
    TTE = raw_input("press return to exit, or press L for a list of commands.")
    if TTE == 'L':
        print("---- LIST OF COMMANDS ----")
        d()
        print("Pick,Hoe,Axe,Shovel,Bow,dagger")
        n()
        print("Gets the Pick,Hoe,Axe,Shovel,Bow,dagger")
        n()
        print("'torches'")
        n()
        print("Gets the number of torches")
        n()
        print("'Pick'")
        n()
        print("Gets the pick")
        n()
        print("'Pick'")
        n()
        print("Gets the pick")
        n()
        print("'Pick'")
        n()
        print("Gets the pick")
        n()
    else:
        Help()
def MenuText():
    clear()
    print("---- MENU ----")
    d()
    print("Back to game")
    print(" (BTG)")
    n()
    print("Help")
    n()
    print("Mods")
    d()
    Menubutton = raw_input("Type here:  ").lower()
    if Menubutton == "help":
        Help()
        MenuText()
    elif Menubutton == "mods":
        clear()
        print("You have ALL the mods!")
        n()
        SPause()
        MenuText()
    elif Menubutton == "btg" or Menubutton == "":
        clear()
        testkey()
    else:
        clear()
        print('"' + str(Menubutton) + '"' " isn't an option.")
        time.sleep(1)
        print("3")
        time.sleep(1)
        print("2")
        time.sleep(1)
        print("1")
        time.sleep(1)
        print("BACK TO MENU")
        time.sleep(1)
        MenuText()
def get_random_biome_op():
    spawni = random.randrange(26)
    if spawni == 0:
        return "grassland"
    elif spawni == 1:
        return "tropics"
    elif spawni == 2:
        return "alps"
    elif spawni == 3:
        return "bamboo forest"
    elif spawni == 4:
        return "forest"
    elif spawni == 5:
        return "desert"
    elif spawni == 6:
        return "jungle"
    elif spawni == 7:
        return "swamp"
    elif spawni == 8:
        return "canyon"
    elif spawni == 9:
        return "crag"
    elif spawni == 10:
        return "dead forest"
    elif spawni == 11:
        return "dunes"
    elif spawni == 12:
        return "glacier"
    elif spawni == 13:
        return "hot springs"
    elif spawni == 14:
        return "lush desert"
    elif spawni == 15:
        return "lush swamp"
    elif spawni == 16:
        return "mangrove"
    elif spawni == 17:
        return "mountain"
    elif spawni == 18:
        return "mystic grove"
    elif spawni == 19:
        return "ominous woods"
    elif spawni == 20:
        return "rainforest"
    elif spawni == 21:
        return "sacred springs"
    elif spawni == 22:
        return "tundra"
    elif spawni == 23:
        return "frost forest"
    elif spawni == 24:
        return "tempertate rainforest"
    elif spawni == 25:
        return "tropical rainforest"
def inaorona(incav):
    if incave == True:
        return "in a cave"
    elif incave == False:
        return "on land"
def youare():
    testcave = inaorona(incave)
    if Cbiome != "texas":
        return "You are in the " + str(Cbiome) + " biome, and you are " + str(testcave) + "."
    else:
        return "You are in texas, and you are " + str(testcave) + "."

Scav = 2
caverare = 8
def respawn():
    print("Do you want to respawn?").lower()
    r = raw_input("")
    if r == "no":
        print("alright, then.")
        time.sleep(3)
        print(Death)
    elif r == "yes":
        print("Ok.")
        spawn()
    else:
        print("Interpereting vauge answer as 'yes'.")
        spawn()
def bicave():
    if (Cbiome == "glacier") or (Cbiome == "mangrove"):
        return 50
    elif (Cbiome == "mystic grove") or (Cbiome == "ominous woods") or (Cbiome == "tundra") or (Cbiome == "desert"):
        return 40
    elif (Cbiome == "tempertate rainforest") or (Cbiome == "tropical rainforest") or (Cbiome == "mountain") or (Cbiome == "lush swamp") or (Cbiome == "lush swamp"):
        return 30
    elif (Cbiome == "hot springs") or (Cbiome == "dunes") or (Cbiome == "swamp") or (Cbiome == "forest"):
        return 30
    elif (Cbiome == "frost forest") or (Cbiome == "rainforest") or (Cbiome == "dead forest") or (Cbiome == "lush desert"):
        return 20
    elif (Cbiome == "bamboo forest") or (Cbiome == "jungle") or (Cbiome == "tropics") or (Cbiome == "canyon"):
        return 20
    elif (Cbiome == "sacred springs") or (Cbiome == "crag") or (Cbiome == "alps"):
        return 15
    elif Cbiome == "grassland":
        return 10
    elif Cbiome == "texas":
        return 8
counterd = 0
def looptime(hl):
    counterd = 0
    while counterd < hl:
        time.sleep(1)
        global counterd
        counterd += 1
def ascavetrue(cmac):
    cmac = True
    incave = True
    return True
def sfcave(rarity):
    Scav = random.randrange(rarity)
    time.sleep(1)
    while Scav != 7:
        Scav = random.randrange(rarity)
        time.sleep(.5)
        n()
        print("searching")
    if Scav == 7:
        n()
        print("Cave found!")
        n()
        Pause()
        findnewcave()
    else:
        print("someth'in went trrble wrng.")
    findnewcave()

def testkey():
    WkEy = raw_input("Type here: ").lower()
    n()
    if WkEy == "sword":
        if sword != 'Empty':
            print("Your sword is " + str(sword)) + "."
            n()
            print("It's health is " + str(swordhealth))
        else:
            print("You dont have a sword.")
        resetkey()
    elif WkEy == "pick":
        if pick != 'Empty':
            print("Your pick is " + str(pick)) + "."
            n()
            print("It's health is " + str(pickhealth))
        else:
            print("You don't have a pick.")
        resetkey()
    elif WkEy == "axe":
        if axe != 'Empty':
            print("Your axe is " + str(axe)) + "."
            n()
            print("It's health is " + str(axehealth))
        else:
            print("you don't have an axe.")
        resetkey()
    elif WkEy == "hoe":
        if hoe != 'Empty':
            print("Your hoe is " + str(hoe)) + "."
            n()
            print("It's health is " + str(hoehealth))
        else:
            print("you don't have a hoe.")
        resetkey()
    elif WkEy == "dagger":
        if dagger != 'Empty':
            print("Your dagger is " + str(dagger)) + "."
            n()
            print("It's health is " + str(daggerhealth))
        else:
            print("you don't have a dagger.")
        resetkey()
    elif WkEy == "bow":
        if bow != 'Empty':
            print("Your bow is " + str(bow)) + "."
            n()
            print("It's health is " + str(bowhealth))
            d()
            if arrows == 0:
                print("you don't have any arrows.")
            elif arrows == 1:
                print("you have 1 arrow.")
            else:
                print("you also have " + str(arrows) + " arrows")
        else:
            print("you don't have a bow.")
        resetkey()
    elif (WkEy == "arrows") or (WkEy == "arrow"):
        if arrows == 0:
            print("you don't have any arrows.")
        elif arrows == 1:
            print("you have 1 arrow.")
        else:
            print("you also have " + str(arrows) + " arrows")
        resetkey()
    elif (WkEy == "torches") or (WkEy == "torch"):
        if torch != 0:
            print("You have " + str(torch) + " torches")
        else:
            print("You don't have any torches.")
        resetkey()
    elif WkEy == "gunpowder":
        n()
        print("You have " + str(gunpowder) + " gunpowder.")
    elif (WkEy == "bones") or (WkEy == "bone"):
        if bones == 0:
            print("You don't have any bones.")
        elif bones == 1:
            print("You have 1 bone.")
        else:
            print("You have " + str(bones) + " bones.")
    elif WkEy == "biome":
        if Cbiome != "texas":
            print("You are in the " + Cbiome + " biome.")
        else:
            print("You are in texas.")
    elif (WkEy == "diamond") or (WkEy == "diamonds"):
        if diamond == 0:
            print("You don't have any diamonds")
        elif diamond == 1:
            print("You have 1 diamond.")
        else:
            print("You have " + str(diamond) + " diamonds")
        resetkey()
    elif (WkEy == "nikolite"):
        if nikolite == 0:
            print("You don't have any nikolite")
        elif nikolite == 1:
            print("You have 1 piece of nikolite.")
        else:
            print("You have " + str(nikolite) + "pieces of nikolite")
        resetkey()
    elif (WkEy == "lapis") or (WkEy == "lapis lazuli"):
        if lapis == 0:
            print("You don't have any lapis")
        elif lapis == 1:
            print("You have 1 piece of lapis.")
        else:
            print("You have " + str(lapis) + " pieces of lapis")
        resetkey()
    elif (WkEy == "redstone") or (WkEy == "red stone"):
        if redstone == 0:
            print("You don't have any redstone")
        elif redstone == 1:
            print("You have 1 piece of redstone.")
        else:
            print("You have " + str(redstone) + " pieces of redstone")
        resetkey()
    elif (WkEy == "coal"):
        if coal == 0:
            print("You don't have any coal")
        elif coal == 1:
            print("You have 1 chunk of coal.")
        else:
            print("You have " + str(coal) + " chunks of coal")
        resetkey()
    elif (WkEy == "iron"):
        if iron == 0:
            if ironore != 0:
                print("You don't have any iron, but you have " + str(ironore) + " iron ore")
                n()
                print("Smelt them")
            else:
                print("You don't have any iron")
        elif iron == 1:
            print("You have 1 iron ingot")
        else:
            print("You have " + str(iron) +  " iron ingots")
        resetkey()
    elif (WkEy == "ironore") or (WkEy == "iron ore"):
        if ironore == 0:
            print("You don't have any iron ore")
        elif ironore == 1:
            print("You have 1 block of iron ore")
        else:
            print("You have " + str(ironore) + " blocks of iron ore.")
        resetkey()
    elif (WkEy == "tin"):
        if tin == 0:
            if tinore != 0:
                print("You don't have any tin, but you have " + str(tinore) + " tin ore")
                n()
                print("Smelt them")
            else:
                print("You don't have any tin")
        elif tin == 1:
            print("You have 1 tin ingot")
        else:
            print("You have " + str(iron) + " tin ingots")
        resetkey()
    elif (WkEy == "tinore") or (WkEy == "tin ore"):
        if tinore == 0:
            print("You don't have any tin ore")
        elif tinore == 1:
            print("You have 1 block of tin ore")
        else:
            print("You have " + str(tinore) + " blocks of tin ore.")
        resetkey()
    elif (WkEy == "silver"):
        if silver == 0:
            if silverore != 0:
                print("You don't have any silver, but you have " + str(silverore) + " silver ore")
                n()
                print("Smelt them")
            else:
                print("You don't have any silver")
        elif silver == 1:
            print("You have 1 silver ingot")
        else:
            print("You have " + str(silver) + " silver ingots")
        resetkey()
    elif (WkEy == "silverore") or (WkEy == "silver ore"):
        if silverore == 0:
            print("You don't have any silver ore")
        elif silverore == 1:
            print("You have 1 block of silver ore")
        else:
            print("You have " + str(silverore) + " blocks of silver ore.")
    elif (WkEy == "gold"):
        if gold == 0:
            if goldore != 0:
                print("You don't have any gold, but you have " + str(goldore) + " gold ore")
                n()
                print("Smelt them")
            else:
                print("You don't have any gold")
        elif gold == 1:
            print("You have 1 gold ingot")
        else:
            print("You have " + str(gold) + " gold ingots")
        resetkey()
    elif (WkEy == "goldore") or (WkEy == "gold ore"):
        if goldore == 0:
            print("You don't have any gold ore")
        elif goldore == 1:
            print("You have 1 block of gold ore")
        else:
            print("You have " + str(goldore) + " blocks of gold ore.")
        resetkey()
    elif (WkEy == "copper"):
        if copper == 0:
            if copperore != 0:
                print("You don't have any copper, but you have " + str(copperore) + " copper ore")
                n()
                print("Smelt them")
            else:
                print("You don't have any copper")
        elif copper == 1:
            print("You have 1 copper ingot")
        else:
            print("You have " + str(gold) + " copper ingots")
        resetkey()
    elif (WkEy == "copperore") or (WkEy == "copper ore"):
        if copperore == 0:
            print("You don't have any copper ore")
        elif copperore == 1:
            print("You have 1 block of copper ore")
        else:
            print("You have " + str(copperore) + " blocks of copper ore.")
        resetkey()
    elif WkEy == "health":
        print("You have " + str(health) + " health.")
    elif (WkEy == "heal") or (WkEy == "eat"):
        gethealth()
    elif WkEy == "":
        print("You didn't enter anything!")
        resetkey()
    elif (WkEy == "find a cave") or (WkEy == "find cave") or (WkEy == "get cave") or (WkEy == "get a cave") or (WkEy == "look for cave"):
        n()
        sfcave(bicave())
        n()
        print("your cave status is: " + str(incave) + ".")
        resetkey()
    elif WkEy == "end":
        n()
        clear()
    elif WkEy == "cave":
        clear()
        global incave
        if incave == True:
            print("WHAT?!?!?!?   YOU ARE IN A CAVE!!!!!!")
        elif incave == False:
            clear()
            print("you need to find a cave. use 'find cave'")
        resetkey()
    elif (WkEy == "explore") or (WkEy =="walk") or (WkEy =="hike"):
        if incave == True:
            print("Try 'mine'. Unless you just want to hike around this cave.")
        elif incave == False:
            tth = random.randrange(31)
            print("Walking...")
            time.sleep(int(tth))
            if int(tth) < 8:
                n()
                print("Still walking...")
                time.sleep(1.5 * int(tth))
            clear()
            global Cbiome
            Cbiome = get_random_biome_op()
            print("You hiked to the " + str(Cbiome) + " biome.")
    elif (WkEy == "leave cave") or (WkEy == "exit cave") or (WkEy == "walk out of cave") or (WkEy == "go out of cave") or (WkEy == "get out of cave"):
        if incave == True:
            if deepcave == True:
                print("do you really want to leave?")
                n()
                really = raw_input("").lower()
                if (really == "yes") or (really == "y"):
                    leaving_cave()
                    resetkey()
                else:
                    print("ok")
                    Pause()
                    resetkey()
            else:
                if lavacave == True:
                    print("do you really want to leave?")
                    n()
                    really = raw_input("").lower()
                    if (really == "yes") or (really == "y"):
                        leaving_cave()
                        resetkey()
                    else:
                        print("ok")
                        Pause()
                        resetkey()
                else:
                    if ravine == True:
                        print("do you really want to leave?")
                        n()
                        really = raw_input("").lower()
                        if (really == "yes") or (really == "y"):
                            leaving_cave()
                            resetkey()
                        else:
                            print("ok")
                            Pause()
                            resetkey()
                    else:
                        clear()
                        print("do you really want to leave?")
                        n()
                        really = raw_input("").lower()
                        if (really == "yes") or (really == "y"):
                            leaving_cave()
                            resetkey()
                        else:
                            print("ok")
                            Pause()
                            resetkey()
        else:
            print("You are'nt even in a cave!")
    elif (WkEy == "go up in cave") or (WkEy == "go higher in cave") or (WkEy == "go up") or (WkEy == "go higher") or (WkEy == "walk up"):
        if incave == True:
            if deepcave == True:
                deepcode
            elif lavacave == True:
                lavacode 
        else:
            print("You are'nt even in a cave")
    elif WkEy == "mine":
        if pick != "Empty":
            if incave == True:
                if deepcave == True:
                    deepchoice = raw_input("Do you want to mine here, or try to go even deeper? type: ").lower()
                    if (deepchoice == "mine") or (deepchoice == "stay") or (deepchoice == "mine here") or (deepchoice == "here"):
                        print("normal mining")
                        resetkey()
                    elif (deepchoice == "deeper") or (deepchoice == "deep") or (deepchoice == "go deeper"):
                        deeptest = random.randrange(16)
                        n()
                        tth = random.randrange(31)
                        print("searching...")
                        time.sleep(int(tth))
                        if deeptest < 6:
                            n()
                            print("you found a cave to go deeper!")
                            n()
                            evendeeper()
                            resetkey()
                        else:
                            n()
                            print("awww... no deeeper cave")
                            resetkey()
                else:
                    if lavacave == True:
                        print("lava caving")
                    else:
                        if shaft == True:
                            print("Shafting here")
                        else:
                            if ravine == True:
                                print("ravine here")
                            else:
                                n()
                                deepchoice = raw_input("Do you want to mine up here, or try to go deeper? type: ").lower()
                                if (deepchoice == "mine") or (deepchoice == "stay") or (deepchoice == "mine here"):
                                    mineit("cave")
                                    resetkey()
                                elif (deepchoice == "deeper") or (deepchoice == "deep") or (deepchoice == "go deeper"):
                                    deeptest = random.randrange(10)
                                    n()
                                    tth = random.randrange(21)
                                    print("searching...")
                                    time.sleep(int(tth))
                                    if deeptest < 6:
                                        n()
                                        print("you found a cave to go deeper!")
                                        n()
                                        godeeper()
                                        resetkey()
                                    else:
                                        n()
                                        print("awww.. no deeper caves here.")
                                        resetkey()
                                else:
                                    n()
                                    print("What?")
                                    time.sleep(3)
                                    resetkey()
            else:
                n()
                print("You aren't in a cave. use 'find cave'.")
                resetkey()
        else:
            n()
            print("You don't have a pick!")
            resetkey()
    elif WkEy == "gpick":
        global pick
        pick = "stone"
        global pickhealth
        pickhealth = 6
        print("Done")
    elif WkEy == "alpha":
        battle("spider")
    elif (WkEy == "make me a sandwich") or (WkEy == "make me a sandwich."):
        print("What? Make it yourself.")
    elif (WkEy == "sudo make me a sandwich") or (WkEy == "sudo make me a sandwich."):
        print("Okay.")
        global sandwich
        sandwich += 1
    elif (WkEy == "sandwich") or (WkEy == "sandwiches"):
        if sandwich == 0:
            print("You don't have any sandwiches")
        elif sandwich == 1:
            print("You have 1 sandwich")
        else:
            print("You have " + str(sandwich) + " sandwiches")
    elif WkEy == "texas":
        if sandwich > 2:
            print("You ate your to texas.")
            global Cbiome
            Cbiome = "texas"
            global sandwich
            sandwich = sandwich - 3
        else:
            print("You don't have enough sandwiches to go to texas.")
    elif (WkEy == "chop trees") or (WkEy == "cut down trees") or (WkEy == "cut down some trees") or (WkEy == "get wood") or (WkEy == "cut trees") or (WkEy == "punch trees"):
        if incave == True:
            print("You are in a cave.")
            print("There are no trees in caves.")
            n()
            Pause()
            resetkey()
        else:
            if axehealth != 0:
                if (Cbiome == "desert") or (Cbiome == "crag") or (Cbiome == "glacier"):
                    print("There are no trees in the " + Cbiome + " biome.")
                else:
                    treehigh = random.randint(5,10)
                    print("You found a tree that is " + str(treehigh) + " blocks tall.")
                    n()
                    print("Chop it down?")
                    chop = raw_input("").lower()
                    if (chop == "no") or (chop == "n"):
                        n()
                        print("ok")
                        Pause()
                        resetkey()
                    elif (chop == "yes") or (chop == "y"):
                        clear()
                        bl = int(treehigh)
                        while bl != 0:
                            if axehealth != 0:
                                print("chopping...")
                                time.sleep(1)
                                bl = bl - 1
                                global axehealth
                                axehealth = axehealth - 1
                                time.sleep(.2)
                                print("+ 1 wood")
                            else:
                                print("You are out of axe")
                    else:
                        print("Interpreting vague answer as 'yes'.")
                        Pause()
                        clear()
                        bl = int(treehigh)
                        while bl != 0:
                            if axehealth != 0:
                                print("chopping...")
                                time.sleep(2)
                                bl = bl - 1
                                global axehealth
                                axehealth = axehealth - 1
                                time.sleep(.2)
                                print("+ 1 wood")
                            else:
                                print("You are out of axe")
            else:
                print("Goodbye fists....")
                if (Cbiome == "desert") or (Cbiome == "crag") or (Cbiome == "glacier"):
                    print("Thank heavens. There are no trees in the " + Cbiome + " biome.")
                else:
                    treehigh = random.randint(5,10)
                    print("You found a tree that is " + str(treehigh) + " blocks tall.")
                    n()
                    print("Punch it down?")
                    chop = raw_input("").lower()
                    if (chop == "no") or (chop == "n"):
                        n()
                        print("Your fists thank you.")
                        Pause()
                        resetkey()
                    elif (chop == "yes") or (chop == "y"):
                        clear()
                        bl = int(treehigh)
                        while bl != 0:
                            time.sleep(4)
                            print("punching...")
                            bl = bl - 1
                            time.sleep(1)
                            print("+ 1 wood")
                    else:
                        print("Interpreting vague answer as 'yes'.")
                        Pause()
                        clear()
                        bl = int(treehigh)
                        while bl != 0:
                            time.sleep(4)
                            print("punching...")
                            bl = bl - 1
                            time.sleep(1)
                            print("+ 1 wood")
            print("you now have " + str(wood) + " wood")  
    elif WkEy == "gsword":
        global sword
        sword = "diamond"
        global swordhealth
        swordhealth = 5000
    elif WkEy == "gfood":
        global food
        food += 7
    else:
        print("WHAT?")
        resetkey()
    resetkey()

def leaving_cave():
    if torch != 0:
        iftorch = raw_input("Do you want to use torches? type: ").lower()
        if (iftorch == "y") or (iftorch == "yes"):
            iftorch = True
        else:
            iftorch = False
    else:
        iftorch = False
    if iftorch == True:
        n()
        print("you will be safe.")
        time.sleep(3)
        clear()
        if deepcave == True:
            torchuse = random.randint(3,6)
        elif lavacave == True:
            torchuse = random.randint(7,13)
        elif ravine == True:
            torchuse = random.randint(3,13)
        elif shaft == True: 
            torchuse = random.randint(1,9)
        if torchuse <= torch:
            print("You used " + str(torchuse) + "torches")
            global torch
            torch = torch - int(torchuse)
            leavecave()
        else:
            print("You don't have enough torches. try again, or don't use them.")
    elif iftorch == False:
        n()
        print("You will not be safe.")
        time.sleep(3)
        clear()
        if deepcave == True:
            mobrate = random.randint(0,2)
        elif lavacave == True:
            mobrate = random.randint(2,4)
        elif ravine == True:
            mobrate = random.randint(2,5)
        elif shaft == True: 
            mobrate = random.randint(1,3)
        else:
            mobrate = 0
        if mobrate == 0:
            print("You are safe anyway.")
            leavecave()
            resetkey()
        else:
            mobsleft = int(mobrate)
            while mobsleft != 0:
                print("walking..")
                time.sleep(random.randint(7,17))
                mobsleft = mobsleft - 1           
def resetkey():
    n()
    Pause()
    clear()
    testkey()
def findnewcave():
    global incave
    incave = True
def godeeper():
    global deepcave
    deepcave = True
def goup():
    global deepcave
    deepcave = False
def leavecave():
    global ravine
    ravine = False
    global shaft
    shaft = False
    global incave
    incave = False
    global deepcave
    deepcave = False
def evendeeper():
    global deepcave
    deepcave = False
    global lavacave
    lavacave = True
def gtncave():
    global deepcave
    deepcave = True
    global lavacave
    lavacave = False

def ad1or(ore):
    if ore == "coal":
        global coal
        coal += 1
    elif ore == "iron":
        global ironore
        ironore += 1
    elif ore == "gold":
        global goldore
        goldore += 1
    elif ore == "tin":
        global tinore
        tinore += 1
    elif ore == "diamond":
        global diamond
        diamond += 1
    elif ore == "copper":
        global copperore
        copperore += 1
    elif ore == "redstone":
        global redstone
        redstone += 1
    elif ore == "gem":
        global gem
        gem += 1
    elif ore == "quartz":
        global quartz
        quartz += 1
    elif ore == "nikolite":
        global nikolite
        nikolite += 1
def getoretime(ore):
    if ore == "coal":
        if pick == "wood":
            time.sleep(2)
        elif pick == "stone":
            time.sleep(1.7)
        elif pick == "iron":
            time.sleep(1.3)
        elif pick == "gold":
            time.sleep(.8)
        elif pick == "diamond":
            time.sleep(1)
    elif ore == "iron":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(5)
        elif pick == "iron":
            time.sleep(2.3)
        elif pick == "gold":
            time.sleep(1.7)
        elif pick == "diamond":
            time.sleep(1.9)
    elif ore == "copper":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(3)
        elif pick == "iron":
            time.sleep(2.4)
        elif pick == "gold":
            time.sleep(1.8)
        elif pick == "diamond":
            time.sleep(2)
    elif ore == "gold":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(20)
        elif pick == "iron":
            time.sleep(4)
        elif pick == "gold":
            time.sleep(1)
        elif pick == "diamond":
            time.sleep(2.1)
    elif ore == "redstone":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(20)
        elif pick == "iron":
            time.sleep(4)
        elif pick == "gold":
            time.sleep(2)
        elif pick == "diamond":
            time.sleep(3)
    elif ore == "lapis":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(20)
        elif pick == "iron":
            time.sleep(2.4)
        elif pick == "gold":
            time.sleep(1.8)
        elif pick == "diamond":
            time.sleep(2)
    elif ore == "diamond":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(20)
        elif pick == "iron":
            time.sleep(7)
        elif pick == "gold":
            time.sleep(9)
        elif pick == "diamond":
            time.sleep(4)
    elif ore == "gem":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(10)
        elif pick == "iron":
            time.sleep(4)
        elif pick == "gold":
            time.sleep(3)
        elif pick == "diamond":
            time.sleep(2)
    elif ore == "quartz":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(4)
        elif pick == "iron":
            time.sleep(3)
        elif pick == "gold":
            time.sleep(2)
        elif pick == "diamond":
            time.sleep(2)
    elif ore == "tin":
        if pick == "wood":
            time.sleep(6)
        elif pick == "stone":
            time.sleep(5)
        elif pick == "iron":
            time.sleep(3)
        elif pick == "gold":
            time.sleep(2)
        elif pick == "diamond":
            time.sleep(2.5)
    elif ore == "silver":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(4)
        elif pick == "iron":
            time.sleep(3.5)
        elif pick == "gold":
            time.sleep(2)
        elif pick == "diamond":
            time.sleep(2.8)
    elif ore == "copper":
        if pick == "wood":
            time.sleep(14)
        elif pick == "stone":
            time.sleep(3)
        elif pick == "iron":
            time.sleep(2.4)
        elif pick == "gold":
            time.sleep(1.8)
        elif pick == "diamond":
            time.sleep(2)
    elif ore == "nikolite":
        if pick == "wood":
            time.sleep(20)
        elif pick == "stone":
            time.sleep(15)
        elif pick == "iron":
            time.sleep(5)
        elif pick == "gold":
            time.sleep(3)
        elif pick == "diamond":
            time.sleep(2)
    else:
        print("you are ugly.")
def pickdetect():
    if pick ==  "Empty":
        return False
    else:
        if pickhealth == 0:
            global pick
            pick == "Empty"
            pickdetect()
        else:
            return True
def mineit(place):
    ttw = random.randrange(15)
    if place == "lavacave":
        print("lavacavecode")
    elif place == "shaft":
        print("shaftcode")
    elif place == "deepcave":
        print("deepcode")
    elif place == "cave":
        print("searching...")
        Placaw = random.randrange(11)
        counter = 0
        while counter < Placaw:
            time.sleep(2)
            print("exploring...")
            n()
            if torch != 0:
                print("-1 torch")
                global torch
                torch = torch - 1
                counter += 1
            else:
                n()
                print("You are out of torches!")
                resetkey()
            
        clear()
        print("You had enough torches.")
        n()
        randore = random.randrange(6)
        if (randore == 0) or (randore == 1) or (randore == 2):
            minore = "coal"
            manyore = random.randint(6,20)
        elif (randore == 3) or (randore == 4):
            minore = "iron"
            manyore = random.randint(3,5)
        elif (randore == 5):
            minore = "tin"
            manyore = random.randint(2,3)
        elif randore == 6:
            minore = "copper"
        print("You found a cluster of " + str(manyore) + " " + str(minore) + ".")
        n()
        print("Do you want to mine the cluster?")
        dywtmi = raw_input("").lower()
        if (dywtmi == "yes") or (dywtmi == "yes"):
            minetime(minore,manyore)
        elif (dywtmi == "no") or (dywtmi == "n"):
            n()
            time.sleep(3)
            resetkey()
        else:
            n()
            print("Interpreting vague answer as 'yes'.")
            time.sleep(3)
            minetime(minore,manyore)
def minetime(orez,clusterz):
    clear()
    countert = 0
    while countert < clusterz:
        if pickhealth != 0:
            print("mining...")
            getoretime(orez)
            n()
            ad1or(orez)
            print("+ 1 " + str(orez) + ". For a total of " + str(getorevar(orez)) + " " + str(orez))
            n()
            global pickhealth
            pickhealth = pickhealth - 1
            countert += 1
        else:
            n()
            print("You ran out of pick")
            global pick
            pick = "Empty"
            resetkey()          
def getorevar(ore):
    if ore == "coal":
        return coal
    elif ore == "tin":
        return tinore
    elif ore == "copper":
        return copperore
    elif ore == "iron":
        return ironore
    elif ore == "diamond":
        return diamond
    elif ore == "silver":
        return silverore
    elif ore == "nikolite":
        return nikolite
    elif ore == "gold":
        return goldore
    elif ore == "quartz":
        return quartz
    elif ore == "gem":
        return gem
    elif ore == "lapis":
        return lapis
def getrandmob():
    wm = random.randint(0,29)
    if (wm == 0) or (wm == 29) or (wm == 28):
        return "creeper"
    elif (wm == 1) or (wm == 25) or (wm == 26) or (wm == 27):
        return "skeleton"
    elif (wm == 2) or (wm == 15) or (wm == 21) or (wm == 22) or (wm == 23) or (wm == 24):
        return "zombie"
    elif (wm == 3) or (wm == 17) or (wm == 18) or (wm == 19) or (wm == 20):
        return "spider"
    elif (wm == 4) or (wm == 10) or (wm == 11):
        return "fire ogre"
    elif (wm == 5) or (wm == 12) or (wm == 13) or (wm == 14):
        return "enderman"
    elif (wm == 6) or (wm == 16):
        return "slime"
    elif (wm == 7):
        return "cave ogre"
    elif (wm == 8) or (wm == 9):
        return "fire ogre"
    else:
        return "slime"
def getshaftmob():
    wm = random.randint(0,40)
    if (wm == 0) or (wm == 29) or (wm == 30) or (wm == 31) or (wm == 32):
        return "creeper"
    elif (wm == 1) or (wm == 25) or (wm == 26) or (wm == 27) or (wm == 28):
        return "skeleton"
    elif (wm == 2) or (wm == 15) or (wm == 21) or (wm == 22) or (wm == 23) or (wm == 24):
        return "zombie"
    elif (wm == 3) or (wm == 17) or (wm == 18) or (wm == 19) or (wm == 20):
        return "spider"
    elif (wm == 4) or (wm == 10) or (wm == 11):
        return "fire ogre"
    elif (wm == 5) or (wm == 12) or (wm == 13) or (wm == 14):
        return "enderman"
    elif (wm == 6) or (wm == 16):
        return "slime"
    elif (wm == 7):
        return "cave ogre"
    elif (wm == 8) or (wm == 9):
        return "fire ogre"
    else:
        return "cave spider"
def mobstats(mob, close, health):
    n()
    print("The " + str(mob) + " is " + str(close) + " blocks away")
    print("It has " + str(health) + " health left.") 
def wepenchusr(far):
    print("What weapon do you want to use to attack?")
    atas = raw_input("").lower()
    if (atas == "bow") or (atas == "shoot") or (atas == "shoot it") or (atas == "use bow") or (atas == "use the bow"):
        if bowhealth == 0:
            n()
            print("You don't have a bow!")
        else:
            if arrows != 0:
                global bowhealth
                bowhealth = bowhealth - 1
                global arrows
                arrows = arrows - 1
                damage = random.randint(4,9)
                return int(damage)
            else:
                print("You don't have any arrows!")
                return wepenchusr(far)
    elif (atas == "sword"):
        if swordhealth == 0:
            n()
            print("You don't have a sword!")
            Pause()
            clear()
            return wepenchusr(far)
        else:
            if far < 10:
                global swordhealth
                swordhealth = swordhealth - 1
                if sword == "wood":
                    return 4
                elif sword == "stone":
                    return 5
                elif sword == "iron":
                    return 6
                elif sword == "gold":
                    return 4
                elif sword == "diamond":
                    return 7
            else:
                print("Out of range.")
                Pause()
                clear()
                return wepenchusr(far)
    elif (atas == "dagger"):
        if daggerhealth == 0:
            n()
            print("You don't have a dagger!")
            Pause()
            clear()
            return wepenchusr(far)
        else:
            if far < 5:
                global daggerhealth
                daggerhealth = daggerhealth - 1
                if dagger == "wood":
                    return 3
                elif dagger == "stone":
                    return 4
                elif dagger == "iron":
                    return 5
                elif dagger == "gold":
                    return 3
                elif dagger == "diamond":
                    return 6
            else:
                n()
                print("out of range. throw the dagger?")
                thrown = raw_input("").lower()
                if (thrown == "yes") or (thrown == "y"):
                    if dagger == "wood":
                        return 2
                    elif dagger == "stone":
                        return 3
                    elif dagger == "iron":
                        return 4
                    elif dagger == "gold":
                        return 3
                    elif dagger == "diamond":
                        return 5
                    else:
                        print("too bad.")
                        Pause()
                        clear()
                        return wepenchusr(far)
    elif (atas == "hoe"):
        if hoehealth == 0:
            n()
            print("You don't have a hoe!")
            return wepenchusr(far)
        else:
            if far < 8:
                global hoehealth
                hoehealth = hoehealth - 1
                if hoe == "wood":
                    return 2
                elif hoe == "stone":
                    return 3
                elif hoe == "iron":
                    return 4
                elif hoe == "gold":
                    return 2
                elif hoe == "diamond":
                    return 5
            else:
                print("out of range.")
                Pause()
                clear()
                return wepenchusr(far)
    elif (atas == "axe"):
        if axehealth == 0:
            n()
            print("You don't have an axe!")
            Pause()
            clear()
            return wepenchusr(far)
        else:
            if far < 8:
                global axehealth
                axehealth = axehealth - 1
                if axe == "wood":
                    return 3
                elif axe == "stone":
                    return 4
                elif axe == "iron":
                    return 5
                elif axe == "gold":
                    return 4
                elif axe == "diamond":
                    return 6
            else:   
                print("out of range.")
                Pause()
                clear()
                return wepenchusr(far)
    elif (atas == "pick"):
        if pickhealth == 0:
            n()
            print("You don't have a pick!")
            n()
            Pause()
            clear()
            return wepenchusr(far)
        else:
            if far < 9:
                global pickhealth
                pickhealth = pickhealth - 1
                if pick == "wood":
                    return 2
                elif pick == "stone":
                    return 3
                elif pick == "iron":
                    return 4
                elif pick == "gold":
                    return 2
                elif pick == "diamond":
                    return 5
            else:
                print("out of range.")
                Pause()
                clear()
                return wepenchusr(far)
    elif (atas == "fist") or (atas == "fists"):
        if far < 4:
            return 1
        else:
            print("Out of range.")
            n()
            return wepenchusr(far)
    elif (atas == "wait") or (atas == "nothing") or (atas == "no"):
        return 0
    elif (atas == "retreat") or (atas == "run away"):
        return 42
    elif (atas == "charge") or (atas == "charge!") or (atas == "charge!!") or (atas == "charge!!!") or (atas == "charge!!!!"):
        return 43
    else:
        print("you were not understood.")
        Pause()
        clear()
        return wepenchusr(far)
def mattack(mob,far):
    if mob == "creeper":
        if far > 40:
            print("The creeper hisses, but you can't hear it.")
        if far > 20:
            print("The creeper hisses, but you can barely hear it.")
        elif far > 3:
            print("The creeper hisses silently")
        else:
            print("The creeper slowly turns white.")
            time.sleep(1)
            clear()
            print("The creeper slowly turns white..")
            time.sleep(1)
            clear()
            print("The creeper slowly turns white...")
            time.sleep(3)
            clear()
            print("BOOOOMM!!!!!!!!")
            bh = random.randint(10,25)
            losehealth(bh)
            
    elif mob == "skeleton":
        if far < 4:
            hit = random.randint(0,1)
        elif far < 10:
            hit = random.randint(0,2)
        elif far < 20:
            hit = random.randint(0,4)
        elif far < 30:
            hit = random.randint(0,6)
        elif far < 40:
            hit = random.randint(0,7)
        if hit == 0:
            print("You have been hit!")
            losehealth(4)
        else:
            print("The skeleton missed you.")
    elif mob == "zombie":
        if far == 0:
            print("The zombie starts to eat your brain.")
            be = random.randint(4,6)
            losehealth(be)
        elif far < 2:
            print("The zombie claws at you terribly.")
            be = random.randint(3,5)
            losehealth(be)
        elif far < 3:
            print("The zombie claws at you.")
            be = random.randint(2,4)
            losehealth(be)
        elif far < 13:
            print("The zombie groans.")
        elif far < 30:
            print("The zombie groans faintly.")
        elif far < 50:
            print("The zombie groans, but you can only see it's mouth move.")
    elif mob == "spider":
        if far == 0:
            print("The spider bites you.")
            losehealth(4)
        elif far < 3:
            print("The spider slashes at you with it's foot.")
            hit = random.randint(0,7)
            if hit == 7:
                print("It missed you!")
            else:
                print("You've been hit.")
                losehealth(3)
        elif far <= 25:
            print("The spider hisses at you.")
        else:
            print("The spider hisses at you faintly.")
    elif mob == "fire ogre":
        pass
    elif mob == "enderman":
        pass
    elif mob == "slime":
        pass
    elif mob == "cave ogre":
        pass
    elif mob == "cave spider":
        pass
    elif mob == "ghast":
        pass
    elif mob == "blaze":
        pass
    elif mob == "wither skeleton":
        pass
def battle(mob):
    clear()
    print("you are battling a " + mob + "!")
    if mob == "creeper":
        global mobhealth
        mobhealth = 20
        far = random.randint(12,25)
    elif mob == "skeleton":
        global mobhealth
        mobhealth = 20
        far = random.randint(15,30)
    elif mob == "zombie":
        global mobhealth
        mobhealth = 20
        far = random.randint(13,27)
    elif mob == "spider":
        global mobhealth
        mobhealth = 16
        far = random.randint(16,20)
    elif mob == "fire ogre":
        global mobhealth
        mobhealth = 30
        far = random.randint(10,20)
    elif mob == "enderman":
        global mobhealth
        mobhealth = 40
        far = random.randint(10,30)
    elif mob == "slime":
        global mobhealth
        mobhealth = 16
        far = random.randint(10,20)
    elif mob == "cave ogre":
        global mobhealth
        mobhealth = 45
        far = random.randint(10,27)
    elif mob == "cave spider":
        global mobhealth
        mobhealth = 12
        far = random.randint(10,23)
    elif mob == "ghast":
        global mobhealth
        mobhealth = 12
        far = random.randint(20,50)
    elif mob == "blaze":
        global mobhealth
        mobhealth = 20
        far = random.randint(5,26)
    elif mob == "wither skeleton":
        global mobhealth
        mobhealth = 20
        far = random.randint(12,20)
    while True:
        mobstats(mob,far,mobhealth)
        strength = 0
        strength = pattack(far)
        n()
        if strength == 42:
            print("Your retreating!")
            time.sleep(5)
            dist = random.randint(5,15)
            clear()
            print("You retreated " + str(dist) + " blocks!")
            far += dist
        elif strength == 43:
            if far != 0:
                print("Your CHARGING!!!!!")
                time.sleep(5)
                dist = random.randint(5,15)
                clear()
                print("You ran " + str(dist) + " blocks!")
                if far - dist < 0:
                    far = 0
                far = far - dist
            else:
                print("You can't charge, you are already touching the " + mob + "!")
                n()
                print("too bad you already wasted your turn.")
        elif strength != 0:
            print("You attacked, and the " + mob + " lost " + str(strength) + " health.")
            mobhealth = mobhealth - strength
        else:
            print("You didn't attack.")
        n()
        if (strength != 0) and (strength != 42):
            if (mobhealth > 0):
                kb = random.randint(0,2)
                if kb != 0:
                    print("You knocked the " + mob + " back " + str(kb) + " blocks.")
                n()
                print("Now the " + mob + " has " + str(mobhealth) + " health.")
            else:
                clear()
                print("You did it! you got the " + mob + "!")
                win = True
                break
        else:
            print("The " + mob + " still has " + str(mobhealth) + " health.")
        n()
        Pause()
        clear()
        if far > 0:
            if mob == "creeper":
                if far < 10:
                    advance = random.randint(1,2)
                else:
                    advance = random.randint(2,4)
            elif mob == "zombie":
                advance = random.randint(2,3)
            elif mob == "spider":
                advance = random.randint(2,3)
            else:
                advance = random.randint(2,5)
        elif far <= 0:
            far = 0
            advance = 0
        far = far - advance
        if far < 0:
            far = 0
        if far > 50:
            clear()
            print("You ran away!")
            win = False
            break
        if far > 0:
            if mob == "zombie":
                print("the " + str(mob) + " shambled " + str(advance) + " blocks toward you!")
            elif (mob == "spider") or (mob == "cave spider"):
                print("the " + str(mob) + " crawled " + str(advance) + " blocks toward you!")
            else:
                print("the " + str(mob) + " walked " + str(advance) + " blocks toward you!")
            n()
            mattack(mob,far)
        else:
            n()
            mattack(mob,far)
        Pause()
        clear()
    if win == True:
        if mob == "creeper":
            gunloot = random.randint(1,3)
            global gunpowder
            gunpowder = gunpowder + gunloot
            print("you got " + str(gunloot) + " gunpowder.")
        elif mob == "skeleton":
            boneloot = random.randint(1,3)
            global bones
            bones = bones + boneloot
            if boneloot == 1:
                print("You got 1 bone")
            else:
                print("you got " + str(boneloot) + " bones.")
            n()
            getbow = random.randint(1,10)
            if getbow == 7:
                print("You got a new bow!")
                global bowhealth
                bowhealth = 100
                n()
            getarro = random.randint(2,5)
            print("you got " + str(getarro) + " arrows.")
            global arrows
            arrows = arrows + getarro
        elif mob == "zombie":
            fleshloot = random.randint(2,4)
            n()
            print("You got " + str(fleshloot) + " rotten flesh.")
            if sword != "diamond":
                getsword = random.randint(1,10)
                if getsword == 7:
                    print("Do you want a new iron sword?")
                    want = raw_input("")
                    if want == "no":
                        print("ok....")
                    else:
                        n()
                        print("Ok. here you go.")
                        global sword
                        sword = "iron"
                        global swordhealth
                        swordhealth = 100
    else:
        n()
        Pause()
def losehealth(lh):
    if armourhealth != 0:
        if armourhealth > lh:
            global armourhealth
            armourhealth = armourhealth - lh
            print("Your armour lost " + str(lh) + " health,")
            n()
            print("but you still have " + str(armourhealth) + " left.")
        elif armourhealth == lh:
            global armourhealth
            armourhealth = 0
            print("You lost all your armour, it didn't harm your health.")
        elif armourhealth < lh:
            if armourhealth + health > lh:
                global health
                health = (armourhealth + health) - lh
                global armourhealth
                armourhealth = 0
                print("You lost all you armour,")
                n()
                print("and you lost " + str((armourhealth + health) - lh) + " health.")
                n()
                global health
                health = (armourhealth + health) - lh
                global armourhealth
                armourhealth = 0
                print("You have " + str(health) + " health left.")
            else:
                print("You lost all your health.")
                n()
                Pause()
                respawn()
    else:
        if health > lh:
            print("You lost " + str(lh) + " health,")
            n()
            global health
            health = health - lh
            print("but you still have " + str(health))
        else:   
            print("You lost all your health.")
            n()
            Pause()
            respawn()
def gethealth():
    if health == 20:
        print("You health is already full.")
    else:
        if food != 0:
            print("You have " + str(food) + " points of food.")
            n()
            print("You have " + str(health) + " health.")
            n()
            print("How much would you like to eat? (numbers only)")
            n()
            eat = raw_input("")
            if eat > health:
                eat = 20 - health
            if eat > food:
                eat = food
            clear()
            print("You ate " + str(eat) + " points worth of food.")
            global health
            health = health + eat
            global food
            food = food - eat
def pattack(far):
    n()
    strength = wepenchusr(far)
    return strength
def tloin():
    print("going to the land of infinate numbers...")
    time.sleep(3)
    num = 0
    while True:
        print(str(num))
        num += 1

spawn()
'''
infinite mining solved
space solved
zero solved
loop "out of pick" 
'''
