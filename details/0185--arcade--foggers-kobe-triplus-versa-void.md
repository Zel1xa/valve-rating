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
|           33 |      473 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.56 | foggers, Kobe, TRIPLUS, versa, void      |
|           32 |      477 | 2024-07-23 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -11.44 | foggers, Kobe, TRIPLUS, versa, void      |
|           31 |      498 | 2024-07-22 | KZG                | L   | 1.000      | -            | -                | -                | -         |   -15.51 | foggers, Kobe, TRIPLUS, versa, void      |
|           30 |      500 | 2024-07-22 | KZG                | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.109 (0.036)    | 0 (0.000) |    16.01 | foggers, Kobe, TRIPLUS, versa, void      |
|           29 |      653 | 2024-07-18 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |   -10.71 | foggers, kibstar, TRIPLUS, versa, void   |
|           28 |      657 | 2024-07-18 | Bad News Kangaroos | W   | 1.000      | 0.333        | 0.016 (0.005)    | 0.222 (0.074)    | 0 (0.000) |    21.22 | foggers, kibstar, TRIPLUS, versa, void   |
|           27 |     2129 | 2024-05-15 | Bad News Kangaroos | L   | 0.649      | -            | -                | -                | -         |    -5.75 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           26 |     2134 | 2024-05-15 | Bad News Kangaroos | L   | 0.649      | -            | -                | -                | -         |    -6.03 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           25 |     2324 | 2024-05-08 | Mindfreak          | L   | 0.602      | -            | -                | -                | -         |    -7.58 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           24 |     2327 | 2024-05-08 | Mindfreak          | L   | 0.602      | -            | -                | -                | -         |    -7.99 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           23 |     2342 | 2024-05-07 | DXA                | L   | 0.596      | -            | -                | -                | -         |    -9.66 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           22 |     2345 | 2024-05-07 | DXA                | W   | 0.596      | 0.333        | 0.002 (0.000)    | 0.222 (0.044)    | 0 (0.000) |     9.30 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           21 |     2837 | 2024-04-17 | Rooster            | L   | 0.463      | -            | -                | -                | -         |    -4.74 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           20 |     2847 | 2024-04-17 | Vantage            | W   | 0.463      | 0.143        | 0.002 (0.000)    | 0.067 (0.004)    | 0 (0.000) |     7.67 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           19 |     3011 | 2024-04-10 | Vantage            | L   | 0.416      | -            | -                | -                | -         |    -6.32 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           18 |     3015 | 2024-04-10 | Vantage            | L   | 0.416      | -            | -                | -                | -         |    -6.55 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           17 |     3244 | 2024-04-03 | FlyQuest           | L   | 0.369      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           16 |     3249 | 2024-04-03 | FlyQuest           | L   | 0.369      | -            | -                | -                | -         |    -0.72 | apocdud, foggers, Kobe, TRIPLUS, void    |
|           15 |     3370 | 2024-03-27 | Rooster            | L   | 0.323      | -            | -                | -                | -         |    -3.52 | apocdud, foggers, kibstar, Kobe, void    |
|           14 |     3375 | 2024-03-27 | Rooster            | L   | 0.323      | -            | -                | -                | -         |    -3.60 | apocdud, foggers, kibstar, Kobe, void    |
|           13 |     3420 | 2024-03-23 | KZG                | L   | 0.296      | -            | -                | -                | -         |    -4.60 | apocdud, foggers, Kobe, rekonz, void     |
|           12 |     3422 | 2024-03-23 | Bad News Kangaroos | L   | 0.295      | -            | -                | -                | -         |    -3.45 | apocdud, foggers, Kobe, rekonz, void     |
|           11 |     3816 | 2024-03-06 | KZG                | W   | 0.183      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     2.98 | apocdud, foggers, Kobe, void, yourwombat |
|           10 |     3822 | 2024-03-06 | KZG                | W   | 0.182      | 0.333        | 0.005 (0.000)    | 0.109 (0.007)    | 0 (0.000) |     3.03 | apocdud, foggers, Kobe, void, yourwombat |
|            9 |     3990 | 2024-02-27 | Canon Event        | W   | 0.129      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.14 | apocdud, damyo, foggers, Kobe, void      |
|            8 |     3993 | 2024-02-27 | Canon Event        | W   | 0.129      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     1.15 | apocdud, damyo, foggers, Kobe, void      |
|            7 |     4128 | 2024-02-20 | Vantage            | L   | 0.088      | -            | -                | -                | -         |    -1.49 | apocdud, damyo, foggers, Kobe, void      |
|            6 |     4149 | 2024-02-20 | Cringexe           | W   | 0.083      | 0.143        | -                | 0.003 (0.000)    | 0 (0.000) |     0.66 | apocdud, damyo, foggers, Kobe, void      |
|            5 |     4151 | 2024-02-20 | gfg123321          | W   | 0.082      | -            | -                | -                | 0 (0.000) |     0.45 | apocdud, damyo, foggers, Kobe, void      |
|            4 |     4195 | 2024-02-18 | FlyQuest           | L   | 0.069      | -            | -                | -                | -         |    -0.14 | apocdud, damyo, foggers, Kobe, void      |
|            3 |     4197 | 2024-02-18 | KZG                | W   | 0.069      | 0.143        | 0.005 (0.000)    | 0.109 (0.001)    | -         |     1.17 | apocdud, damyo, foggers, Kobe, void      |
|            2 |     4200 | 2024-02-17 | FlyQuest           | L   | 0.067      | -            | -                | -                | -         |    -0.14 | apocdud, damyo, foggers, Kobe, void      |
|            1 |     4223 | 2024-02-16 | LYG                | W   | 0.061      | 0.303        | 0.003 (0.000)    | 0.032 (0.001)    | -         |     1.03 | apocdud, damyo, foggers, Kobe, void      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($767.87)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.815 | $600.00        | $488.83         |
| 2024-03-23 |      0.296 | $662.00        | $195.70         |
| 2024-02-17 |      0.067 | $1,250.00      | $83.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
