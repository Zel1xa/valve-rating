### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [188](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
<br />
Final Rank Value:  601.8<br />
<br />
Final Rank Value (601.8) = Starting Rank Value (666.2) + Head To Head Adjustments (-64.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.2
- 400 + ( ( 0.130 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 666.2


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
|           33 |      410 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.18 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      415 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.01 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      435 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.02 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      438 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.112 (0.037)    | 0 (0.000) |    16.55 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      590 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -13.66 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      595 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.145 (0.048)    | 0 (0.000) |    18.03 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2065 | 2024-05-15 | Bad News Kangaroos | L   | 0.663      | -            | -                | -                | -         |    -8.61 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2070 | 2024-05-15 | Bad News Kangaroos | L   | 0.663      | -            | -                | -                | -         |    -9.11 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2260 | 2024-05-08 | Mindfreak          | L   | 0.616      | -            | -                | -                | -         |    -7.71 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2263 | 2024-05-08 | Mindfreak          | L   | 0.616      | -            | -                | -                | -         |    -8.13 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2278 | 2024-05-07 | DXA                | L   | 0.610      | -            | -                | -                | -         |    -9.90 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2281 | 2024-05-07 | DXA                | W   | 0.610      | 0.333        | 0.002 (0.000)    | 0.227 (0.046)    | 0 (0.000) |     9.50 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2772 | 2024-04-17 | Rooster            | L   | 0.477      | -            | -                | -                | -         |    -4.75 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2782 | 2024-04-17 | Vantage            | W   | 0.476      | 0.143        | 0.002 (0.000)    | 0.071 (0.005)    | 0 (0.000) |     8.12 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     2946 | 2024-04-10 | Vantage            | L   | 0.430      | -            | -                | -                | -         |    -6.33 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     2950 | 2024-04-10 | Vantage            | L   | 0.429      | -            | -                | -                | -         |    -6.57 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3179 | 2024-04-03 | FlyQuest           | L   | 0.383      | -            | -                | -                | -         |    -0.69 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3184 | 2024-04-03 | FlyQuest           | L   | 0.383      | -            | -                | -                | -         |    -0.69 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3305 | 2024-03-27 | Rooster            | L   | 0.337      | -            | -                | -                | -         |    -3.56 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3310 | 2024-03-27 | Rooster            | L   | 0.336      | -            | -                | -                | -         |    -3.66 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3355 | 2024-03-23 | KZG                | L   | 0.310      | -            | -                | -                | -         |    -4.70 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3357 | 2024-03-23 | Bad News Kangaroos | L   | 0.309      | -            | -                | -                | -         |    -3.68 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3750 | 2024-03-06 | KZG                | W   | 0.197      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.29 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3756 | 2024-03-06 | KZG                | W   | 0.196      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.34 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3924 | 2024-02-27 | Canon Event        | W   | 0.143      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.31 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3927 | 2024-02-27 | Canon Event        | W   | 0.143      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.32 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4062 | 2024-02-20 | Vantage            | L   | 0.102      | -            | -                | -                | -         |    -1.68 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4083 | 2024-02-20 | Cringexe           | W   | 0.096      | 0.143        | -                | 0.004 (0.000)    | 0 (0.000) |     0.80 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4085 | 2024-02-20 | gfg123321          | W   | 0.096      | -            | -                | -                | 0 (0.000) |     0.55 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4128 | 2024-02-18 | FlyQuest           | L   | 0.083      | -            | -                | -                | -         |    -0.16 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4130 | 2024-02-18 | KZG                | W   | 0.083      | 0.143        | 0.005 (0.000)    | 0.112 (0.001)    | -         |     1.45 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4133 | 2024-02-17 | FlyQuest           | L   | 0.081      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4156 | 2024-02-16 | LYG                | W   | 0.074      | 0.303        | 0.003 (0.000)    | 0.034 (0.001)    | -         |     1.30 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($802.76)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.829 | $600.00        | $497.17         |
| 2024-03-23 |      0.310 | $662.00        | $204.90         |
| 2024-02-17 |      0.081 | $1,250.00      | $100.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
