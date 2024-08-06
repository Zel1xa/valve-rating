### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  621.3<br />
<br />
Final Rank Value (621.3) = Starting Rank Value (676.7) + Head To Head Adjustments (-55.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.7
- 400 + ( ( 0.135 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 676.7


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
|           33 |      477 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.57 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      481 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.45 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      502 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.51 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      504 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.109 (0.036)    | 0 (0.000) |    16.02 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      657 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.72 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      661 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.016 (0.005)    | 0.222 (0.074)    | 0 (0.000) |    21.20 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2133 | 2024-05-15 | Bad News Kangaroos | L   | 0.647      | -            | -                | -                | -         |    -5.74 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2138 | 2024-05-15 | Bad News Kangaroos | L   | 0.646      | -            | -                | -                | -         |    -6.01 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2328 | 2024-05-08 | Mindfreak          | L   | 0.600      | -            | -                | -                | -         |    -7.56 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2331 | 2024-05-08 | Mindfreak          | L   | 0.600      | -            | -                | -                | -         |    -7.96 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2346 | 2024-05-07 | DXA                | L   | 0.594      | -            | -                | -                | -         |    -9.61 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2349 | 2024-05-07 | DXA                | W   | 0.593      | 0.333        | 0.002 (0.000)    | 0.222 (0.044)    | 0 (0.000) |     9.27 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2841 | 2024-04-17 | Rooster            | L   | 0.460      | -            | -                | -                | -         |    -4.71 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2851 | 2024-04-17 | Vantage            | W   | 0.460      | 0.143        | 0.002 (0.000)    | 0.066 (0.004)    | 0 (0.000) |     7.63 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     3015 | 2024-04-10 | Vantage            | L   | 0.413      | -            | -                | -                | -         |    -6.28 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     3019 | 2024-04-10 | Vantage            | L   | 0.413      | -            | -                | -                | -         |    -6.51 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3248 | 2024-04-03 | FlyQuest           | L   | 0.367      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3253 | 2024-04-03 | FlyQuest           | L   | 0.366      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3374 | 2024-03-27 | Rooster            | L   | 0.320      | -            | -                | -                | -         |    -3.49 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3379 | 2024-03-27 | Rooster            | L   | 0.320      | -            | -                | -                | -         |    -3.58 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3424 | 2024-03-23 | KZG                | L   | 0.293      | -            | -                | -                | -         |    -4.55 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3426 | 2024-03-23 | Bad News Kangaroos | L   | 0.292      | -            | -                | -                | -         |    -3.42 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3820 | 2024-03-06 | KZG                | W   | 0.180      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     2.95 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3826 | 2024-03-06 | KZG                | W   | 0.180      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     2.99 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3994 | 2024-02-27 | Canon Event        | W   | 0.127      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.12 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3997 | 2024-02-27 | Canon Event        | W   | 0.126      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.13 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4132 | 2024-02-20 | Vantage            | L   | 0.086      | -            | -                | -                | -         |    -1.45 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4153 | 2024-02-20 | Cringexe           | W   | 0.080      | 0.143        | -                | 0.003 (0.000)    | 0 (0.000) |     0.64 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4155 | 2024-02-20 | gfg123321          | W   | 0.080      | -            | -                | -                | 0 (0.000) |     0.44 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4199 | 2024-02-18 | FlyQuest           | L   | 0.067      | -            | -                | -                | -         |    -0.14 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4201 | 2024-02-18 | KZG                | W   | 0.066      | 0.143        | 0.005 (0.000)    | 0.109 (0.001)    | -         |     1.13 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4204 | 2024-02-17 | FlyQuest           | L   | 0.064      | -            | -                | -                | -         |    -0.13 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4227 | 2024-02-16 | LYG                | W   | 0.058      | 0.303        | 0.003 (0.000)    | 0.032 (0.001)    | -         |     0.99 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($761.59)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $600.00        | $487.33         |
| 2024-03-23 |      0.293 | $662.00        | $194.05         |
| 2024-02-17 |      0.064 | $1,250.00      | $80.21          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
