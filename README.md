~~~
  _   _                              _   _                                     
 | \ | |                            | \ | |                                    
 |  \| | ___ _   _ _ __ ___  _ __   |  \| | ___  _ __  ___  ___ _ __  ___  ___ 
 | . ` |/ _ \ | | | '__/ _ \| '_ \  | . ` |/ _ \| '_ \/ __|/ _ \ '_ \/ __|/ _ \
 | |\  |  __/ |_| | | | (_) | | | | | |\  | (_) | | | \__ \  __/ | | \__ \  __/
 |_| \_|\___|\__,_|_|  \___/|_| |_| |_| \_|\___/|_| |_|___/\___|_| |_|___/\___|
~~~                                                                              
                                                                               
# Welcome to Neuron Nonsense, the first ever Neural Net Auto-Battler. 

## In this game you will compete to create the most effecient neural net.

## *** Nodes ***

### Generation:
  generation nodes are the life of your net and produce power based on some factor,
  like time or damage recieved. after enough time has passed or damage is taken, the
  node will activate sending a pulse of power to all the connected nodes. this power
  is what activation nodes use to deal, heal, and block damage.

### Bridge:
  bridge nodes are the best way to scale your neural nets build. bridges offer a way
  to increase (or split) the power flowing through your network. bridges offer a lot 
  of power, but they usually come with the limitation of how many connections they
  can have, so plan ahead!

### Activation:
  activation nodes are what give your net offensive/defensive capabilities. when an
  activation node has reached its activation charge it will activate dealing its 
  damage/buff to the respective player. things like kinetic, fire, and poison will
  hurt your oppenent while heal, miners and shield will apply to yourself.


## *** Gameplay ***

You start with a simple neural net of just 1 generation node, and 1 activation node.
You will have to battle your way to the top, expanding and upgrading as you go.

Every round consists of a battle, shop, and edit phase.

 ### Edit:
  you will have time to move around your network's nodes, and add or delete 
  connections between them. you can also spend your gold upgrading or purchasing
  new nodes in the shop.
    
 ### Shop:
  the shop will currently offer 2 random nodes, and 3 skills (WIP) to be purchased.
  you can only buy 1 copy of everything in the shop, but the shop will refresh 
  after each battle.
    
 ### Battle:
  after you have finished editing your network you can pit it against an enemy net.
  this will test your build and reward you with gold, every battle you will be put
  against another net with the same number of wins as you. For the demo these are 
  pre-build and hand crafted nets BUT in the future will be other player's nets.

## *** Node Index ***

### Generation:

  Timer:
    timer neurons are the base generation neuron. every time interval they will 
    activate, sending a charge to each connection.
    
  Reactive:
    reactive neurons only activate after taking a hit.

### Bridge:

  Splitter:
    splitter neurons are essentially a blank neuron, they don't change the overall
    incoming charge vs. outcoming charge. they simply split the input equally with
    all connected outputs.
    
  Addition:
    addition neurons simply add a set value to every charge passing through it.
    
  Multiply:
    multiply neurons multiply the input before splitting evenly between outputs.

### Activation:

  Kinetic:
    the most basic of activations, deals raw damage.
    
  Fire:
    deals damage over time, does many ticks of damage per second.
    
  Poison:
    deals damage over time, ignores shields, and does larger chunks of damage.
    
  Heal:
    heals the net for a set value.
    
  Heal Buff:
    has a high activation threshold, but buffs all healing done for a short time.
    
  Miner:
    turns in battle energy into out-of-battle gold to spend in the shop.
    
  Shield:
    applys a shild to the net that can block most types of damages.

