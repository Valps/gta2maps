Map: de_dust2
Version: 0.1.0
Author: Valps

- No cars;
- No NPCs;
- Two teams, T: terrorists, CT: counter-terrorists

(Things that can be changed later, feedback are welcome)
- Only weapons available: (silenced) machine guns, pistols, grenades and molotovs;
- Timing of (dis)arm the bomb and the countdown to explosion.
- Bomb respawn locations
- Defuse kit respawn

Rules:
- To pick a team, walk into the CT or T painted on ground.
- Once all players already chosen their team, one terrorist will pick the bomb and one CT will pick the defuse kit (displayed as briefcase).
- Players carrying the bomb or defuse kit will have an arrow pointing to them, standing out from the others.
- The bomb can be placed in two locations, Site A or Site B.

- If the CT holding a defuse kit dies, a new kit spawn in their base.
- If the T holding the bomb dies, the bomb is dropped depending of his location. If he dies close to the Site B, the bomb will respawn at a specific location in Site B. If he dies in Site A, the bomb will respawn at north or south of Site A, depending of his position.
- If the T holding the bomb dies outside any Site A or B, the bomb will respawn at the Terrorist Base.

Timing:

- Arm the bomb: 5 seconds
- Disarm the bomb: 7 seconds
- Time to explode: 35 seconds

Win condition:

- Terrorists will win if all CT are dead or if the bomb was planted and explodes. A message of "Job Failed" will show to everyone.
- Counter-terrorists will win if the bomb was disarmed or if all terrorist are dead and the bomb wasn't planted. A message of "Job Complete" will show to everyone.

- After one of the wins conditions was reached, the game will close automatically.

Known issues:

- The disarm timer and the bomb timer may sometimes desync a bit in multiplayer. It may be related to the change of number of cycles the game executes within a time.

I need feedback:
- Bugs on gameplay (script issues) or in the map.
- The need of armor to the players.
- Weapons that can be chosen, or the weapon-give method.