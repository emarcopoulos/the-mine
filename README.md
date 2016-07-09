# The Mine
## An ASCII based mining game coded in Java
##### Developed by Elias Marcopoulos and Christa Spieth

### Stuff to Do
#### Brainstorm ideas
- [x] Decide type of game
  - [ ] Exploring game
  - [x] Mining game
- [ ] Decide on game mechanics
  - [ ] Concept
    - [ ] who is mining?
      - [ ] a human
        - [ ] pickaxe and mining tools
        - [ ] a machine powered directly by a human
        - [ ] a machine powered remotely by a human
      - [ ] a machine powered autonomously
      - [ ] an alien
      - [ ] other
    - [ ] where is the mine?
      - [ ] earth
        - [ ] backyard
        - [ ] mining ground
          - [ ] government facility
          - [ ] private facility
      - [ ] a local planet
        - [ ] mercury
        - [ ] venus
        - [ ] mars
        - [ ] jupiter
        - [ ] saturn
        - [ ] neptune
        - [ ] uranus
        - [ ] pluto
      - [ ] a star
      - [ ] an asteroid
      - [ ] a comet
      - [ ] some other celestial body
      - [ ] a made up celestial body
    - [ ] why mine?
      - [ ] profit
        - [ ] lowly worker
        - [ ] rich manager
      - [ ] research
        - [ ] to help humanity!
        - [ ] to destroy humanity (^.^)
      - [ ] survival
        - [ ] escape!
        - [ ] stranded here
      - [ ] boredom
      - [ ] forced labor
        - [ ] old slave society
        - [ ] imprisonment punishment
      - [ ] personal ambition
        - [ ] save a loved one
        - [ ] prove worth to a loved one
          - [ ] gain enough wealth
          - [ ] find some special gem
          - [ ] loved one is of a species that exists unerground
            - [ ] you strive to fit in with people
            - [ ] you take loved one from people
              - [ ] selfish abduction
              - [ ] saving from people
  - [ ] Movement
    - [ ] keys
      - [ ] wasd
      - [ ] arrow
      - [ ] user programmable
      - [ ] other
    - [ ] mining
      - [ ] left, right, down
      - [ ] only down
      - [ ] all four directions
      - [ ] start only down, then allow in game upgrades
    - [ ] going back up
      - [ ] flying
      - [ ] wall climbing
      - [ ] laddering
      - [ ] teleportation
  - [ ] Map
    - [ ] rendering
      - [ ] what to render
        - [ ] randomly generated [different game every play]
        - [ ] pattern based [same game for everyone]
      - [ ] when to render
        - [ ] render whole map at once
        - [ ] render when within some distance of unrendered map
          - [ ] user render options for small, medium, large
          - [ ] some constant distance we choose
    - [ ] dimensions [row X col]
      - [ ] finite X finite
        - [ ] horizontal wrapping
        - [ ] natural constraints
        - [ ] simply limited mapping
      - [ ] infinite X finite [dig very deep]
        - [ ] horizontal wrapping
        - [ ] no ceiling
        - [ ] ceiling
      - [ ] finite X infinite 
        - [ ] stop at planet center
        - [ ] stop at planet core
        - [ ] planet has hard impermeable part
        - [ ] too hot, instant death
      - [ ] infinite X infinite
    - [ ] contents
      - [ ] valuables
        - [ ] our own created minerals
        - [ ] based on celestial body chosen
      - [ ] obstacles
        - [ ] too hard to mine
        - [ ] too hot to mine
        - [ ] other
      - [ ] enemies
        - [ ] competing miners
        - [ ] underground creatures
        - [ ] a supernatural power
          - [ ] god
          - [ ] devil
          - [ ] your conscious
          - [ ] your conscience
      - [ ] generic
        - [ ] ground
        - [ ] sky
        - [ ] water
      - [ ] shops
        - [ ] gas
        - [ ] mining upgrades
        - [ ] extra utilities
        - [ ] fun stuff
          - [ ] color
          - [ ] font
          - [ ] your character
    - [ ] display
      - [ ] some constant we decide will be showed to user
      - [ ] user decidable
  - [ ] Menu
    - [ ] settings
    - [ ] save game
    - [ ] log in
    - [ ] display at start of game
    - [ ] access location
      - [ ] in game map item
      - [ ] press a specific key
  - [ ] Music
    - [ ] create song
    - [ ] royalty free song
- [ ] Decide on Implementation
  - [x] Language
    - [x] Java
    - [ ] javaScript
    - [ ] C++
  - [ ] location of display
    - [ ] Browser [game will require exportable game state in JSON and importable user commands]
    - [ ] Terminal [game will simply print to terminal]