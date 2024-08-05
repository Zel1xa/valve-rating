### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  621.4<br />
<br />
Final Rank Value (621.4) = Starting Rank Value (676.8) + Head To Head Adjustments (-55.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.8
- 400 + ( ( 0.135 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 676.8


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
|           33 |      471 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.55 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      475 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.43 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      496 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.52 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      498 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.109 (0.036)    | 0 (0.000) |    16.01 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      651 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.70 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      655 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.017 (0.006)    | 0.222 (0.074)    | 0 (0.000) |    21.23 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2127 | 2024-05-15 | Bad News Kangaroos | L   | 0.651      | -            | -                | -                | -         |    -5.75 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2132 | 2024-05-15 | Bad News Kangaroos | L   | 0.651      | -            | -                | -                | -         |    -6.03 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2322 | 2024-05-08 | Mindfreak          | L   | 0.604      | -            | -                | -                | -         |    -7.60 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2325 | 2024-05-08 | Mindfreak          | L   | 0.604      | -            | -                | -                | -         |    -8.01 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2340 | 2024-05-07 | DXA                | L   | 0.598      | -            | -                | -                | -         |    -9.70 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2343 | 2024-05-07 | DXA                | W   | 0.598      | 0.333        | 0.002 (0.000)    | 0.222 (0.044)    | 0 (0.000) |     9.33 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2835 | 2024-04-17 | Rooster            | L   | 0.465      | -            | -                | -                | -         |    -4.75 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2845 | 2024-04-17 | Vantage            | W   | 0.464      | 0.143        | 0.002 (0.000)    | 0.067 (0.004)    | 0 (0.000) |     7.70 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     3009 | 2024-04-10 | Vantage            | L   | 0.418      | -            | -                | -                | -         |    -6.34 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     3013 | 2024-04-10 | Vantage            | L   | 0.417      | -            | -                | -                | -         |    -6.58 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3242 | 2024-04-03 | FlyQuest           | L   | 0.371      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3247 | 2024-04-03 | FlyQuest           | L   | 0.371      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3368 | 2024-03-27 | Rooster            | L   | 0.325      | -            | -                | -                | -         |    -3.53 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3373 | 2024-03-27 | Rooster            | L   | 0.324      | -            | -                | -                | -         |    -3.63 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3418 | 2024-03-23 | KZG                | L   | 0.297      | -            | -                | -                | -         |    -4.63 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3420 | 2024-03-23 | Bad News Kangaroos | L   | 0.297      | -            | -                | -                | -         |    -3.46 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3814 | 2024-03-06 | KZG                | W   | 0.185      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     3.01 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3820 | 2024-03-06 | KZG                | W   | 0.184      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     3.06 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3988 | 2024-02-27 | Canon Event        | W   | 0.131      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.16 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3991 | 2024-02-27 | Canon Event        | W   | 0.131      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.17 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4126 | 2024-02-20 | Vantage            | L   | 0.090      | -            | -                | -                | -         |    -1.52 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4147 | 2024-02-20 | Cringexe           | W   | 0.084      | 0.143        | -                | 0.003 (0.000)    | 0 (0.000) |     0.67 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4149 | 2024-02-20 | gfg123321          | W   | 0.084      | -            | -                | -                | 0 (0.000) |     0.46 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4193 | 2024-02-18 | FlyQuest           | L   | 0.071      | -            | -                | -                | -         |    -0.15 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4195 | 2024-02-18 | KZG                | W   | 0.071      | 0.143        | 0.005 (0.000)    | 0.109 (0.001)    | -         |     1.20 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4198 | 2024-02-17 | FlyQuest           | L   | 0.068      | -            | -                | -                | -         |    -0.14 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4221 | 2024-02-16 | LYG                | W   | 0.062      | 0.303        | 0.003 (0.000)    | 0.032 (0.001)    | -         |     1.06 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($772.41)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $600.00        | $489.92         |
| 2024-03-23 |      0.297 | $662.00        | $196.90         |
| 2024-02-17 |      0.068 | $1,250.00      | $85.59          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
