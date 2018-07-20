07/20/18 notes:
##created initial app and environment. will ad a link to repo here: https://github.com/jaredspecjr/game

created components in game repo, made a visual spot for the home page of the app.

having issues getting routers to work

decided that create react app is not for me and am scrapping the current project. I'll be spending my time setting up my environment. will add pictures and keep old repo to account for work done on that.

##I will also provide a link to the new repo here: https://github.com/jaredspecjr/Capstone-game


still working on getting routing to work. will post pictures of written notes regarding where state may live.

Routing now works and has images for both rooms. 

<!-- VV LAST FRIDAYS WORK VV -->
Spent morning thinking about capstone ideas and I think I am settling with a choose your own adventure game. will spend more time white boarding and sketching up ideas.
will begin writing out capstone proposal idea and add to this readme.


#Project Description

##Proposal

Jared Lutz,

Choose Your Own Adventure,

This Projects goal is to provide a simple game experience that users can enjoy.

Minimum features:

  Player is able to traverse from room to room depending on what direction they choose or user will see a list of options to choose from and will move to new room depending on what option they choose.

  Player is able to fight enemies, dishing out damage and taking damage.
  enemies and monsters will have to be their own components shoved in between rooms.
  for instance the user selects to go into the room to their right. They will encounter an enemy before moving on to the next room or dying and ending the game.

  Player is able to die and reset the game.


Tools being used for this project:

  create react app?

  React-redux

  CSS

  Webpack

  Bulma? (still deciding)

More Features If minimum requirements are met:

  Boss battles

  Add items like potions or weapons to amplify attack


  ability to level up

I wish I had more time to study react before starting a new project from scratch in it. I feel as though this will be a tough challenge but one I hope to see through.





##Notes:
should the movement be based on what arrow you click or should the user see options of which way they are allowed to go? could the user select multiple options in a single room component?

should health reside in app? how does an enemy component damage the user.

user stories

user sees room or text description of what is int he room.
user chooses an action from a list of options.
user selects room2. user traverses to room2.
user begins to move to room two but encounters an enemy.
user selects attack and enemy loses health.
user takes damage from enemy after ending their turn.
user defeats enemy and proceeds to next room.

##State

where should state reside for these components?


users health state should stay in App. or a redux store?

#Component tree

App
-user
  ~manageHealth/damage?
-component container
  ~room1
  ~room2
  ~enemy1
  ~etc..
-buttons/commands
  ~movement
  ~attack/defend
