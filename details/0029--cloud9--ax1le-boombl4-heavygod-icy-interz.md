### Roster Details<br />
Team Name: Cloud9<br />
Roster: Ax1Le, Boombl4, HeavyGod, ICY, interz<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.2<br />
<br />
Final Rank Value (1155.2) = Starting Rank Value (934.8) + Head To Head Adjustments (220.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.498[<sup>1</sup>](#table2)
- Bounty Collected: 0.414[<sup>2</sup>](#table1)
- Opponent Network: 0.193[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.8
- 400 + ( ( 0.276 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 934.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       23 | 2024-09-07 | Zero Tenacity     | W   | 1.000      | 0.384        | 0.163 (0.063)    | 1.000 (0.384)    | 0 (0.000) |    12.01 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           20 |       49 | 2024-09-06 | BetBoom           | W   | 1.000      | 0.384        | 0.229 (0.088)    | 0.535 (0.206)    | 0 (0.000) |    20.95 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           19 |       96 | 2024-09-05 | ALTERNATE aTTaX   | W   | 1.000      | 0.384        | 0.102 (0.039)    | 0.837 (0.322)    | 0 (0.000) |     8.84 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           18 |      185 | 2024-09-02 | GamerLegion       | W   | 1.000      | 0.384        | 0.162 (0.062)    | 0.601 (0.231)    | 0 (0.000) |    14.39 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           17 |      266 | 2024-08-29 | Insilio           | W   | 1.000      | 0.384        | -                | 0.654 (0.251)    | 0 (0.000) |     7.86 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           16 |      382 | 2024-08-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.20 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           15 |      445 | 2024-08-26 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -0.87 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           14 |      460 | 2024-08-26 | HEROIC            | W   | 1.000      | 0.143        | 0.205 (0.029)    | -                | 0 (0.000) |    25.99 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           13 |      552 | 2024-08-23 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.91 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           12 |      586 | 2024-08-22 | 9 Pandas          | W   | 1.000      | 0.143        | -                | 0.732 (0.105)    | 0 (0.000) |    17.80 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           11 |      637 | 2024-08-21 | Passion UA        | W   | 1.000      | 0.143        | 0.164 (0.023)    | 1.000 (0.143)    | 0 (0.000) |    17.27 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|           10 |      669 | 2024-08-21 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.102 (0.015)    | 0.956 (0.137)    | 0 (0.000) |    18.65 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            9 |      707 | 2024-08-19 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.13 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            8 |      711 | 2024-08-19 | Ninjas in Pyjamas | W   | 1.000      | 0.143        | 0.232 (0.033)    | -                | -         |    28.71 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            7 |      718 | 2024-08-19 | BLEED             | W   | 1.000      | 0.143        | 0.101 (0.014)    | 0.541 (0.077)    | -         |    21.12 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            6 |     1202 | 2024-08-03 | Johnny Speeds     | L   | 0.961      | -            | -                | -                | -         |    -8.04 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            5 |     1228 | 2024-08-02 | BLEED             | W   | 0.955      | 0.143        | -                | 0.541 (0.074)    | -         |    23.91 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            4 |     1269 | 2024-08-01 | AMKAL             | W   | 0.948      | 0.143        | 0.123 (0.017)    | -                | -         |    22.13 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            3 |     1282 | 2024-08-01 | Ninjas in Pyjamas | L   | 0.947      | -            | -                | -                | -         |    -1.88 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            2 |     1315 | 2024-07-31 | 3DMAX             | L   | 0.942      | -            | -                | -                | -         |    -1.14 | Ax1Le, Boombl4, HeavyGod, ICY, interz |
|            1 |     1338 | 2024-07-31 | FaZe              | L   | 0.939      | -            | -                | -                | -         |    -0.32 | Ax1Le, Boombl4, HeavyGod, ICY, interz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,835.53)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-07 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-08-25 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-04 |      0.967 | $5,000.00      | $4,835.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
