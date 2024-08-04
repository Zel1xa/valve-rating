### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [183](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  621.3<br />
<br />
Final Rank Value (621.3) = Starting Rank Value (676.8) + Head To Head Adjustments (-55.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.8
- 400 + ( ( 0.135 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 676.8


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
|           33 |      421 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.51 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      426 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.39 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      446 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.53 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      449 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.112 (0.037)    | 0 (0.000) |    15.99 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      601 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.65 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      606 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.017 (0.006)    | 0.226 (0.075)    | 0 (0.000) |    21.29 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2077 | 2024-05-15 | Bad News Kangaroos | L   | 0.659      | -            | -                | -                | -         |    -5.79 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2082 | 2024-05-15 | Bad News Kangaroos | L   | 0.659      | -            | -                | -                | -         |    -6.07 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2272 | 2024-05-08 | Mindfreak          | L   | 0.613      | -            | -                | -                | -         |    -7.69 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2275 | 2024-05-08 | Mindfreak          | L   | 0.612      | -            | -                | -                | -         |    -8.10 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2290 | 2024-05-07 | DXA                | L   | 0.606      | -            | -                | -                | -         |    -9.85 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2293 | 2024-05-07 | DXA                | W   | 0.606      | 0.333        | 0.002 (0.000)    | 0.226 (0.046)    | 0 (0.000) |     9.43 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2785 | 2024-04-17 | Rooster            | L   | 0.473      | -            | -                | -                | -         |    -4.82 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2795 | 2024-04-17 | Vantage            | W   | 0.473      | 0.143        | 0.002 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     7.84 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     2959 | 2024-04-10 | Vantage            | L   | 0.426      | -            | -                | -                | -         |    -6.47 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     2963 | 2024-04-10 | Vantage            | L   | 0.426      | -            | -                | -                | -         |    -6.71 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3192 | 2024-04-03 | FlyQuest           | L   | 0.379      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3197 | 2024-04-03 | FlyQuest           | L   | 0.379      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3318 | 2024-03-27 | Rooster            | L   | 0.333      | -            | -                | -                | -         |    -3.62 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3323 | 2024-03-27 | Rooster            | L   | 0.333      | -            | -                | -                | -         |    -3.71 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3368 | 2024-03-23 | KZG                | L   | 0.306      | -            | -                | -                | -         |    -4.77 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3370 | 2024-03-23 | Bad News Kangaroos | L   | 0.305      | -            | -                | -                | -         |    -3.55 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3764 | 2024-03-06 | KZG                | W   | 0.193      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.14 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3770 | 2024-03-06 | KZG                | W   | 0.193      | 0.333        | 0.005 (0.000)    | 0.112 (0.007)    | 0 (0.000) |     3.19 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3938 | 2024-02-27 | Canon Event        | W   | 0.139      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.23 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3941 | 2024-02-27 | Canon Event        | W   | 0.139      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.24 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4076 | 2024-02-20 | Vantage            | L   | 0.098      | -            | -                | -                | -         |    -1.67 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4097 | 2024-02-20 | Cringexe           | W   | 0.093      | 0.143        | -                | 0.004 (0.000)    | 0 (0.000) |     0.74 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4099 | 2024-02-20 | gfg123321          | W   | 0.092      | -            | -                | -                | 0 (0.000) |     0.50 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4143 | 2024-02-18 | FlyQuest           | L   | 0.079      | -            | -                | -                | -         |    -0.16 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4145 | 2024-02-18 | KZG                | W   | 0.079      | 0.143        | 0.005 (0.000)    | 0.112 (0.001)    | -         |     1.34 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4148 | 2024-02-17 | FlyQuest           | L   | 0.077      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4171 | 2024-02-16 | LYG                | W   | 0.071      | 0.303        | 0.003 (0.000)    | 0.034 (0.001)    | -         |     1.20 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($793.28)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.825 | $600.00        | $494.90         |
| 2024-03-23 |      0.306 | $662.00        | $202.40         |
| 2024-02-17 |      0.077 | $1,250.00      | $95.98          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
