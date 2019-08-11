# poppy-wrist

"poppy-wrist" is a library adapted from the [poppy-humanoid library](https://github.com/poppy-project/poppy-humanoid) by Hugo KERMABON, Loan GUILBAUD, Gilles SCHNEIDER and Florian TSCHUDY, students at IMT Atlantique, Brest.
It's been developped during a first-year project and aims to provide a fully-fonctionnal Poppy-with-wrist instance, compatible with a modified Poppy-humanoid.

## Poppy-wrist

Poppy-wrist is a modified Poppy-humanoid. It has two articulated wrists, each one adding 2 degrees of liberty to Poppy's hands. The 3D printable pieces and the servomotors references will be soon available.

## What modifications does this library bring ?

It aims to bring :
- a fully working V-Rep scene of Poppy-wrist
- an updated servomotors configuration (config.json) file with new wrists motors.

## Wow, that seems cool, but how to use it ?

This library will be referenced in the [pypot library](https://github.com/poppy-project/pypot) so you will install poppy-wrist just like you installed poppy-humanoid or anything (like `pip install pypot poppy-wrist`).

Then, for example if you decide to control your Poppy-wrist with Python, the code will look like :

```
import pypot.creatures
poppy = pypot.creatures.PoppyWrist()
```

or if you just wanna use to Poppy-wrist simulated version :

```
import pypot.creatures
poppy = pypot.creatures.PoppyWrist(simulator='vrep')
```

## This readme.md is soooooo not clear right now

Sorry, we're just beginning this deployment.
> More instructions will follow. - Future me
