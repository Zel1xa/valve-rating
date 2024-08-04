### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [188](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
<br />
Final Rank Value:  601.9<br />
<br />
Final Rank Value (601.9) = Starting Rank Value (666.1) + Head To Head Adjustments (-64.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.1
- 400 + ( ( 0.130 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 666.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      413 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.16 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      418 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.99 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      438 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.01 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      441 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.112 (0.037)    | 0 (0.000) |    16.56 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      593 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -13.67 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      598 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.146 (0.049)    | 0 (0.000) |    18.03 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2069 | 2024-05-15 | Bad News Kangaroos | L   | 0.660      | -            | -                | -                | -         |    -8.57 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2074 | 2024-05-15 | Bad News Kangaroos | L   | 0.660      | -            | -                | -                | -         |    -9.07 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2264 | 2024-05-08 | Mindfreak          | L   | 0.613      | -            | -                | -                | -         |    -7.66 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2267 | 2024-05-08 | Mindfreak          | L   | 0.613      | -            | -                | -                | -         |    -8.07 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2282 | 2024-05-07 | DXA                | L   | 0.607      | -            | -                | -                | -         |    -9.84 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2285 | 2024-05-07 | DXA                | W   | 0.607      | 0.333        | 0.002 (0.000)    | 0.227 (0.046)    | 0 (0.000) |     9.47 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2777 | 2024-04-17 | Rooster            | L   | 0.474      | -            | -                | -                | -         |    -4.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2787 | 2024-04-17 | Vantage            | W   | 0.473      | 0.143        | 0.002 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     8.05 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     2951 | 2024-04-10 | Vantage            | L   | 0.427      | -            | -                | -                | -         |    -6.30 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     2955 | 2024-04-10 | Vantage            | L   | 0.426      | -            | -                | -                | -         |    -6.54 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3184 | 2024-04-03 | FlyQuest           | L   | 0.380      | -            | -                | -                | -         |    -0.69 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3189 | 2024-04-03 | FlyQuest           | L   | 0.380      | -            | -                | -                | -         |    -0.69 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3310 | 2024-03-27 | Rooster            | L   | 0.334      | -            | -                | -                | -         |    -3.53 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3315 | 2024-03-27 | Rooster            | L   | 0.333      | -            | -                | -                | -         |    -3.62 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3360 | 2024-03-23 | KZG                | L   | 0.306      | -            | -                | -                | -         |    -4.65 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3362 | 2024-03-23 | Bad News Kangaroos | L   | 0.306      | -            | -                | -                | -         |    -3.65 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3756 | 2024-03-06 | KZG                | W   | 0.194      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.24 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3762 | 2024-03-06 | KZG                | W   | 0.193      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.29 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3930 | 2024-02-27 | Canon Event        | W   | 0.140      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.29 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3933 | 2024-02-27 | Canon Event        | W   | 0.140      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.30 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4068 | 2024-02-20 | Vantage            | L   | 0.099      | -            | -                | -                | -         |    -1.63 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4089 | 2024-02-20 | Cringexe           | W   | 0.093      | 0.143        | -                | 0.004 (0.000)    | 0 (0.000) |     0.78 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4091 | 2024-02-20 | gfg123321          | W   | 0.093      | -            | -                | -                | 0 (0.000) |     0.53 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4135 | 2024-02-18 | FlyQuest           | L   | 0.080      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4137 | 2024-02-18 | KZG                | W   | 0.080      | 0.143        | 0.005 (0.000)    | 0.112 (0.001)    | -         |     1.40 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4140 | 2024-02-17 | FlyQuest           | L   | 0.077      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4163 | 2024-02-16 | LYG                | W   | 0.071      | 0.303        | 0.003 (0.000)    | 0.034 (0.001)    | -         |     1.25 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($795.08)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.826 | $600.00        | $495.33         |
| 2024-03-23 |      0.306 | $662.00        | $202.88         |
| 2024-02-17 |      0.077 | $1,250.00      | $96.88          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
