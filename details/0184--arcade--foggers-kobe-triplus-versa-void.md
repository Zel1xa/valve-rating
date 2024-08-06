### Roster Details<br />
Team Name: Arcade<br />
Roster: foggers, Kobe, TRIPLUS, versa, void<br />
Global Rank: [184](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
<br />
Final Rank Value:  621.7<br />
<br />
Final Rank Value (621.7) = Starting Rank Value (677.0) + Head To Head Adjustments (-55.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.0
- 400 + ( ( 0.135 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 677.0


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
|           33 |      490 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.58 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      494 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.46 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      515 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.51 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      517 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.106 (0.035)    | 0 (0.000) |    16.02 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      670 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.73 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      674 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.016 (0.005)    | 0.217 (0.072)    | 0 (0.000) |    21.19 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2146 | 2024-05-15 | Bad News Kangaroos | L   | 0.645      | -            | -                | -                | -         |    -5.73 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2151 | 2024-05-15 | Bad News Kangaroos | L   | 0.645      | -            | -                | -                | -         |    -6.01 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2341 | 2024-05-08 | Mindfreak          | L   | 0.599      | -            | -                | -                | -         |    -7.55 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2344 | 2024-05-08 | Mindfreak          | L   | 0.598      | -            | -                | -                | -         |    -7.94 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2359 | 2024-05-07 | DXA                | L   | 0.592      | -            | -                | -                | -         |    -9.59 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2362 | 2024-05-07 | DXA                | W   | 0.592      | 0.333        | 0.002 (0.000)    | 0.217 (0.043)    | 0 (0.000) |     9.26 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2854 | 2024-04-17 | Rooster            | L   | 0.459      | -            | -                | -                | -         |    -4.71 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2864 | 2024-04-17 | Vantage            | W   | 0.459      | 0.143        | 0.002 (0.000)    | 0.064 (0.004)    | 0 (0.000) |     7.61 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     3028 | 2024-04-10 | Vantage            | L   | 0.412      | -            | -                | -                | -         |    -6.26 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     3032 | 2024-04-10 | Vantage            | L   | 0.412      | -            | -                | -                | -         |    -6.49 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3261 | 2024-04-03 | FlyQuest           | L   | 0.365      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3266 | 2024-04-03 | FlyQuest           | L   | 0.365      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3387 | 2024-03-27 | Rooster            | L   | 0.319      | -            | -                | -                | -         |    -3.48 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3392 | 2024-03-27 | Rooster            | L   | 0.319      | -            | -                | -                | -         |    -3.56 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3437 | 2024-03-23 | KZG                | L   | 0.292      | -            | -                | -                | -         |    -4.53 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3439 | 2024-03-23 | Bad News Kangaroos | L   | 0.291      | -            | -                | -                | -         |    -3.40 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3833 | 2024-03-06 | KZG                | W   | 0.179      | 0.333        | 0.005 (0.000)    | 0.106 (0.006)    | 0 (0.000) |     2.92 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3839 | 2024-03-06 | KZG                | W   | 0.179      | 0.333        | 0.005 (0.000)    | 0.106 (0.006)    | 0 (0.000) |     2.97 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     4007 | 2024-02-27 | Canon Event        | W   | 0.125      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.11 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     4010 | 2024-02-27 | Canon Event        | W   | 0.125      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.12 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4145 | 2024-02-20 | Vantage            | L   | 0.084      | -            | -                | -                | -         |    -1.43 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4166 | 2024-02-20 | Cringexe           | W   | 0.079      | 0.143        | -                | 0.003 (0.000)    | 0 (0.000) |     0.62 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4168 | 2024-02-20 | gfg123321          | W   | 0.078      | -            | -                | -                | 0 (0.000) |     0.43 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4212 | 2024-02-18 | FlyQuest           | L   | 0.065      | -            | -                | -                | -         |    -0.14 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4214 | 2024-02-18 | KZG                | W   | 0.065      | 0.143        | 0.005 (0.000)    | 0.106 (0.001)    | -         |     1.10 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4217 | 2024-02-17 | FlyQuest           | L   | 0.063      | -            | -                | -                | -         |    -0.13 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4240 | 2024-02-16 | LYG                | W   | 0.057      | 0.303        | 0.003 (0.000)    | 0.031 (0.001)    | -         |     0.97 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($758.10)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $600.00        | $486.50         |
| 2024-03-23 |      0.292 | $662.00        | $193.13         |
| 2024-02-17 |      0.063 | $1,250.00      | $78.47          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
