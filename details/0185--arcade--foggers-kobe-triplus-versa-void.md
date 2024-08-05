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
Final Rank Value (621.3) = Starting Rank Value (676.7) + Head To Head Adjustments (-55.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.7
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 676.7


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
|           33 |      449 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.53 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      453 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.40 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      474 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.53 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      476 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.111 (0.037)    | 0 (0.000) |    16.00 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      629 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.67 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      633 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.017 (0.006)    | 0.226 (0.075)    | 0 (0.000) |    21.26 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2105 | 2024-05-15 | Bad News Kangaroos | L   | 0.656      | -            | -                | -                | -         |    -5.77 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2110 | 2024-05-15 | Bad News Kangaroos | L   | 0.656      | -            | -                | -                | -         |    -6.05 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2300 | 2024-05-08 | Mindfreak          | L   | 0.609      | -            | -                | -                | -         |    -7.65 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2303 | 2024-05-08 | Mindfreak          | L   | 0.609      | -            | -                | -                | -         |    -8.06 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2318 | 2024-05-07 | DXA                | L   | 0.603      | -            | -                | -                | -         |    -9.79 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2321 | 2024-05-07 | DXA                | W   | 0.603      | 0.333        | 0.002 (0.000)    | 0.226 (0.045)    | 0 (0.000) |     9.39 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2813 | 2024-04-17 | Rooster            | L   | 0.469      | -            | -                | -                | -         |    -4.79 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2823 | 2024-04-17 | Vantage            | W   | 0.469      | 0.143        | 0.002 (0.000)    | 0.069 (0.005)    | 0 (0.000) |     7.79 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     2987 | 2024-04-10 | Vantage            | L   | 0.422      | -            | -                | -                | -         |    -6.42 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     2991 | 2024-04-10 | Vantage            | L   | 0.422      | -            | -                | -                | -         |    -6.66 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3220 | 2024-04-03 | FlyQuest           | L   | 0.376      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3225 | 2024-04-03 | FlyQuest           | L   | 0.376      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3346 | 2024-03-27 | Rooster            | L   | 0.329      | -            | -                | -                | -         |    -3.58 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3351 | 2024-03-27 | Rooster            | L   | 0.329      | -            | -                | -                | -         |    -3.67 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3396 | 2024-03-23 | KZG                | L   | 0.302      | -            | -                | -                | -         |    -4.71 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3398 | 2024-03-23 | Bad News Kangaroos | L   | 0.302      | -            | -                | -                | -         |    -3.52 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3792 | 2024-03-06 | KZG                | W   | 0.189      | 0.333        | 0.005 (0.000)    | 0.111 (0.007)    | 0 (0.000) |     3.09 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3798 | 2024-03-06 | KZG                | W   | 0.189      | 0.333        | 0.005 (0.000)    | 0.111 (0.007)    | 0 (0.000) |     3.14 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3966 | 2024-02-27 | Canon Event        | W   | 0.136      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.20 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3969 | 2024-02-27 | Canon Event        | W   | 0.136      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.21 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4104 | 2024-02-20 | Vantage            | L   | 0.095      | -            | -                | -                | -         |    -1.61 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4125 | 2024-02-20 | Cringexe           | W   | 0.089      | 0.143        | -                | 0.004 (0.000)    | 0 (0.000) |     0.71 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4127 | 2024-02-20 | gfg123321          | W   | 0.089      | -            | -                | -                | 0 (0.000) |     0.48 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4171 | 2024-02-18 | FlyQuest           | L   | 0.076      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4173 | 2024-02-18 | KZG                | W   | 0.075      | 0.143        | 0.005 (0.000)    | 0.111 (0.001)    | -         |     1.29 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4176 | 2024-02-17 | FlyQuest           | L   | 0.073      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4199 | 2024-02-16 | LYG                | W   | 0.067      | 0.303        | 0.003 (0.000)    | 0.033 (0.001)    | -         |     1.15 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($784.62)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.821 | $600.00        | $492.83         |
| 2024-03-23 |      0.302 | $662.00        | $200.12         |
| 2024-02-17 |      0.073 | $1,250.00      | $91.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
