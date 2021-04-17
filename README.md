# overwatch
Data about 200+ CS:GO overwatch cases I did in 2021. All cases were reviewed manually.


# Columns

- `map` (string): the map a given overwatch case was played on
- `vision` (boolean): whether the suspect was guilty of using vision assisting cheats (e.g. wallhacks)
- `aim` (boolean): whether the suspect was guilty of using aim assisting cheats (e.g. triggerbot, aimbot)
- `bhop` (boolean): whether the suspect was using a bhop script
- `griefing` (boolean): whether the suspect was guilty of anti-social behavior (e.g. killing teammates, blocking runways, team-flashing)
- `anti aim` (boolean): whether the suspect used any kind of anti aim or spinbot
- `tries to hide` (boolean, can be N/A): Empty if the suspect was clean. (e.g. checking angles even though they have wallhacks, holding sites they know noone is attacking, silent aim). caution: this value is highly subjective
- `hvh` (boolean): whether an enemy player is clearly cheating (indicators are, not limited to: killing the suspect that is rage-hacking multiple times, anti aim visible through xray, extremely high scores)
- `gamemode` (either "mm" or "wm"): wingman or normal 5v5 competetive

Data is licensed under the MIT License
