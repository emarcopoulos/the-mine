# The Mine
## An ASCII based mining game coded in Java
##### Developed by Elias Marcopoulos and Christa Spieth

### Stuff to Do
#### Brainstorm ideas
- [x] Decide type of game
  - [ ] Exploring game
  - [x] Mining game
- [ ] Decide on game mechanics
  - [x] Concept
    - [x] who is mining?
      - [ ] a human
        - [ ] pickaxe and mining tools
        - [ ] a machine powered directly by a human
        - [ ] a machine powered remotely by a human
      - [x] a machine powered autonomously
      - [ ] an alien
      - [ ] other
    - [x] where is the mine?
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
      - [x] a made up celestial body
    - [x] why mine?
      - [ ] profit
        - [ ] lowly worker
        - [ ] rich manager
      - [x] research
        - [ ] to help humanity!
        - [x] to destroy humanity (^.^)
      - [ ] survival
        - [ ] escape!
        - [ ] stranded here
      - [ ] boredom
      - [ ] forced labor
        - [ ] old slave society
        - [ ] imprisonment punishment
      - [x] personal ambition
        - [ ] save a loved one
        - [x] prove worth to a loved one
          - [ ] gain enough wealth
          - [ ] find some special gem
          - [x] loved one is of a species that exists underground
            - [ ] you strive to fit in with people
            - [ ] you take loved one from people
              - [ ] selfish abduction
              - [ ] saving from people
            - [x] broken machine found underground
  - [x] Movement
    - [x] keys
      - [x] wasd
      - [x] arrow
      - [ ] user programmable
      - [ ] other
    - [x] mining
      - [x] left, right, down
      - [ ] only down
      - [ ] all four directions
      - [ ] start only down, then allow in game upgrades
    - [x] going back up
      - [x] flying
      - [ ] wall climbing
      - [ ] laddering
      - [x] teleportation
  - [x] Map
    - [x] rendering
      - [x] what to render
        - [x] randomly generated [different game every play]
          - [x] store on continue
          - [ ] re-generate on continue
        - [ ] pattern based [same game for everyone]
      - [x] when to render
        - [ ] render whole map at once
        - [x] render when within some distance of unrendered map
          - [ ] user render options for small, medium, large
          - [x] some constant distance we choose
    - [x] dimensions [row X col]
      - [ ] finite X finite
        - [ ] horizontal wrapping
        - [ ] natural constraints
        - [ ] simply limited mapping
      - [x] infinite X finite [dig very deep]
        - [x] horizontal wrapping
        - [x] no ceiling
        - [ ] ceiling
      - [ ] finite X infinite 
        - [ ] stop at planet center
        - [ ] stop at planet core
        - [ ] planet has hard impermeable part
        - [ ] too hot, instant death
      - [ ] infinite X infinite
    - [x] contents
      - [x] valuables
        - [x] our own created minerals
        - [ ] based on celestial body chosen
      - [x] obstacles
        - [x] too hard to mine
        - [x] too hot to mine
        - [x] other
      - [x] enemies
        - [ ] competing miners
        - [ ] underground creatures
        - [x] a supernatural power
          - [x] god
          - [x] devil
          - [x] your conscious
          - [x] your conscience
      - [x] generic
        - [x] ground
        - [x] sky
        - [x] water
      - [x] shops
        - [x] trade post
        - [x] gas
        - [x] stocks/bank
        - [x] mining upgrades
        - [x] extra utilities
        - [x] fun stuff
          - [x] color
          - [x] font
          - [x] your character
    - [x] display
      - [x] some constant we decide will be showed to user
      - [ ] user decidable
  - [ ] Machine
    - [ ] health type
    - [ ] weaknesses
    - [ ] character
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
- [x] Decide on Implementation
  - [x] Language
    - [x] Java
    - [x] javaScript
    - [x] HTML
    - [ ] C++
  - [x] location of display
    - [x] Browser [game will require exportable game state in JSON and importable user commands]
    - [ ] Terminal [game will simply print to terminal]