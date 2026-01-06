# Fake-News-Headline-Generator
Fake News Headline Generator provide you a funny and joyful activity where you enjoy the fake headline generated with the combinations of random word selection .Enjoy
import random

subjects=[
    "Shahrukh Khan",
    "Virat Kohli",
    "Nirmala Sitaraman",
    "A mumbai cat",
    "A group of Monkey",
    "Prime Minister Modi",
    "Auto Rikshaw Driver from Delhi"
]

actions =[
    "Launches",
    "cancels",
    "dances with",
    "eats",
    "declare war",
    "order",
    "celebration"
]

places_or_things=[
    "at red fort",
    "in mumbai local trains",
    "a plate of samosha",
    "inside parliament",
    "during ipl",
    "india gate"
]

while True:
    subjects=random.choice(subjects)
    actions=random.choice(actions)
    places_or_things=random.choice(places_or_things)

    headline =f" BREAKING NEWS:{subjects} {actions} {places_or_things}"
    print("\n"+headline)

    user_input=input("\nDO You want another Headline ?(yes/no)").strip().lower()
    if user_input=="no":
        break

print("\nThanks for using the fake news Headline Generator.Have a fun day")
