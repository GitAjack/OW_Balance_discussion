# OW_Balance_discussion
OW_Balance_discussion
__My suggestions__
Goal: make early/mid game weapons viable, delay late game techs a bit without making matches too long:__

__Technology research time:__

Partial invisibility: 100->50
Double laser: 120->60
Siberite implosion: 300->250
Hack: 100->50
Gatling gun: 30->15
Explosives: 70->50
Stimulation drugs: 130->80
Materialization prediction (RU): 30->15
Siberite localisation: 30->15
Targeted teleportation: 90->60

__Upgrades:__

     {Solar Engine Discharging}
     UPGRADE 2
       LEVEL  0  9 
       LEVEL  1  6
      +LEVEL  3  4
//make solar engine actually usable, higher build cost to balance, see below.

     {Teleport recharge time}
     UPGRADE 41
       LEVEL  0  4 
      +LEVEL  1  3
       LEVEL  3  2->1.5

     {Apeman driver skill}
     UPGRADE 43
       LEVEL  0  2->3 
      +LEVEL  1  5
       LEVEL  2  6->7 
       LEVEL  3  10 

__Vehicles:__

      ENGINE_TYPE  2 
        NAME "E(Solar)C(solární motor)"
        CANS 10->15
        TIME 20->10

      WEAPON_TYPE  3 
        NAME "E(Light gun)C(lehké dìlo)"
        NATION American
        CANS 25->20
        ATTACK
          FREQUENCY  1  30->27

      WEAPON_TYPE  23 
        NAME "E(Light gun)C(lehké dìlo)"
        NATION Arabian
        CANS 25->20
        ATTACK
          FREQUENCY  1  30->27

      WEAPON_TYPE  27 
        NAME "E(Gun)C(dìlo)"
        NATION Arabian
        ATTACK
          EFF 20 40 30 
       -> EFF 20 50 30 
//stronger against vehicles to have a chance in late game. No need to buff building DMG since you have rockets, flamethrowers, self-propelled bombs.

      WEAPON_TYPE  4 + 44 
        NAME "E(Gun)C(dìlo)"
        NATION American + Russian
        CANS 40->35

      WEAPON_TYPE  4 + 25 + 43
        NAME "E(Gatling gun)C(rotaèní kulomet)"
        NATION American + Arabian + Russian
        TIME 40->20

      WEAPON_TYPE  6 + 46
        NAME "E(Heavy gun)C(tìžké dìlo)"
        NATION American + Russian
        CANS 45->50
        TIME 30->60
//there needs to be price/build time separation between early guns and HG since they're so much stronger.

      WEAPON_TYPE  9 
        NAME "E(Laser)C(laser)"
        NATION American
        CANS 25->40
        TIME 90->70
//why is it so cheap? :D

      WEAPON_TYPE  10 
        NAME "E(Double laser)C(dvojitý laser)"
        NATION American
        SIBERIUM 10
        CANS 20->30

      CHASSIS_TYPE  5 
        NAME "E(Morphling)C(kolopásový podvozek)"
        NATION American
        CANS 40->50
        TIME 80->50
        DEFEND 45->50
//currently morph is useless, so a buff is in order, but its hard to balance.
//Am. heavy tracked perhaps deserves small armor or speed reduction to be fair Vs. Russian HT, but Russians have time-lapsers so IDK.

      CHASSIS_TYPE  21 
        NAME "E(Medium wheeled)C(støední kolový podvozek)"
        NATION Russian
        CANS 20->15
        TIME 25->15
//to help russians deal with early American/Arab rushes

      CHASSIS_TYPE  25 
        NAME "E(Behemoth)C(Behemot)"
        NATION Russian
        SIBERIUM 50->30
        CANS 250->220
        TIME 100->75
        SPEED 4->6

      CHASSIS_TYPE  26 
        NAME "E(BehemothComponent)C(BehemothComponent)"
        NATION Russian
        SIBERIUM 50->30
        CANS 250->220
        TIME 100->75
        SPEED 4->6
//not sure whats the difference between Behemoth and BehemothComponent :Shrug:
