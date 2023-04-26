# COMP90054-P2-PDDL
# VX: csprojhelp 备注: github

The Domain - Bubble Tea robot

Your task is to model a robot that makes bubble tea. The owner of the company has just a few hard-coded recipes, but would prefer that customers are able to flexibly specify their own bubble teas.

The robot is able to do three things: (1) add ingredients to a cup; (2) mix the ingredients that are in the cup; and (3) heat the ingredients that are in the cup.

There are four main types of ingredients: (1) tapioca balls; (2) syrup; (3) ice; and (4) the tea itself. The model can add any of these to the cup at any point. Syrup and tapioca balls can be flavoured.

Customers can specify whether they would like their drink mixed or not (modelling as a PDDL predicate in a goal). If the tea and syrup are mixed, the drink is considered to be "mixed". However, if the tapioca balls are mixed, the mixer blends them into a syrup, so there are no longer tapioca balls in the drink.

When ice is added to the cup, the drink is considered to be iced. Otherwise, it is not iced (modelled as a PDDL goal).

The cup can be heated in a microwave. Typically, customers like heated tapioca balls (modelled as a PDDL goal), otherwise the tapioca balls are too hard. If the ice is heated, it melts so the drink is no longer iced. Customers can also specify that they would like the tea or the syrup iced as well (modelled as a PDDL goal).

The robot can make just one bubble tea at a time.
