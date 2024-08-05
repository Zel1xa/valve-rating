### Roster Details<br />
Team Name: kONO<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  841.0<br />
<br />
Final Rank Value (841.0) = Starting Rank Value (806.2) + Head To Head Adjustments (34.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.088[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.198<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 806.2
- 400 + ( ( 0.198 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 806.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |       18 | 2024-08-05 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.05 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |      197 | 2024-07-31 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           44 |      399 | 2024-07-25 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.458 (0.065)    | 0 (0.000) |    13.97 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |      659 | 2024-07-18 | Lilmix            | L   | 1.000      | -            | -                | -                | -         |   -13.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           42 |      709 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -17.49 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           41 |      767 | 2024-07-16 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -12.98 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |      819 | 2024-07-15 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -11.19 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           39 |      820 | 2024-07-14 | Turkey            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           38 |      822 | 2024-07-14 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.458 (0.065)    | 0 (0.000) |    10.62 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           37 |      825 | 2024-07-14 | Turkey            | L   | 1.000      | -            | -                | -                | -         |   -26.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |      874 | 2024-07-11 | Illuminar         | W   | 1.000      | 0.371        | 0.012 (0.005)    | 0.347 (0.129)    | 0 (0.000) |    17.14 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |      884 | 2024-07-10 | Nexus             | W   | 1.000      | 0.143        | -                | 0.458 (0.065)    | 0 (0.000) |    10.37 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |      914 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |      944 | 2024-07-07 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -17.22 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           32 |      948 | 2024-07-06 | BRUTE             | W   | 0.998      | -            | -                | -                | 0 (0.000) |     2.13 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           31 |      951 | 2024-07-05 | Johnny Speeds     | L   | 0.992      | -            | -                | -                | -         |    -3.20 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |      962 | 2024-06-30 | Lazer Cats        | W   | 0.959      | -            | -                | -                | 0 (0.000) |     3.90 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           29 |     1004 | 2024-06-18 | UNiTY             | W   | 0.877      | 0.333        | 0.025 (0.007)    | 0.300 (0.088)    | -         |    17.88 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |     1009 | 2024-06-17 | K10               | W   | 0.871      | 0.333        | 0.008 (0.002)    | -                | -         |     8.81 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           27 |     1799 | 2024-05-25 | Rebels            | L   | 0.718      | -            | -                | -                | -         |    -6.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     1909 | 2024-05-21 | Serbia            | L   | 0.692      | -            | -                | -                | -         |   -13.54 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     2068 | 2024-05-16 | Monte             | L   | 0.659      | -            | -                | -                | -         |    -6.49 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           24 |     2079 | 2024-05-16 | Zero Tenacity     | L   | 0.657      | -            | -                | -                | -         |    -4.86 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     2134 | 2024-05-15 | Preasy            | W   | 0.651      | 0.333        | -                | 0.221 (0.048)    | -         |     7.82 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     2177 | 2024-05-14 | Alliance          | W   | 0.646      | 0.384        | 0.017 (0.004)    | 0.292 (0.072)    | -         |    10.55 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     2184 | 2024-05-14 | Johnny Speeds     | W   | 0.644      | 0.333        | 0.122 (0.026)    | 1.000 (0.215)    | -         |    18.69 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     2203 | 2024-05-13 | Verdant           | W   | 0.638      | 0.333        | 0.015 (0.003)    | 0.294 (0.063)    | -         |    12.73 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     2500 | 2024-04-29 | Gaimin Gladiators | W   | 0.545      | 0.384        | 0.037 (0.008)    | 0.342 (0.072)    | -         |    12.72 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     2602 | 2024-04-25 | HAVU              | W   | 0.518      | -            | -                | -                | -         |     5.74 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     3066 | 2024-04-09 | ex-Preasy         | L   | 0.411      | -            | -                | -                | -         |    -6.29 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     3560 | 2024-03-15 | Metizport         | W   | 0.246      | -            | -                | -                | -         |     4.45 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     3665 | 2024-03-12 | JANO              | W   | 0.226      | -            | -                | -                | -         |     2.38 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     3676 | 2024-03-11 | CYBERSHOKE        | L   | 0.220      | -            | -                | -                | -         |    -4.75 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     3724 | 2024-03-09 | Enterprise        | W   | 0.206      | 0.372        | 0.039 (0.003)    | -                | -         |     4.18 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           12 |     3770 | 2024-03-07 | Endpoint          | L   | 0.194      | -            | -                | -                | -         |    -2.35 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           11 |     3781 | 2024-03-07 | Permitta          | L   | 0.191      | -            | -                | -                | -         |    -1.83 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     3889 | 2024-03-03 | ex-Preasy         | L   | 0.167      | -            | -                | -                | -         |    -2.85 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            9 |     3913 | 2024-03-02 | MOUZ NXT          | L   | 0.159      | -            | -                | -                | -         |    -1.04 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            8 |     3951 | 2024-02-28 | Aurora            | L   | 0.140      | -            | -                | -                | -         |    -0.04 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            7 |     3956 | 2024-02-28 | KOI               | L   | 0.139      | -            | -                | -                | -         |    -0.77 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            6 |     3971 | 2024-02-27 | DMS               | W   | 0.134      | -            | -                | -                | -         |     2.67 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     3981 | 2024-02-27 | INGLORIOUS        | W   | 0.133      | -            | -                | -                | -         |     0.76 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     3982 | 2024-02-27 | AURA              | W   | 0.132      | -            | -                | -                | -         |     0.63 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     4205 | 2024-02-17 | Aurora            | L   | 0.067      | -            | -                | -                | -         |    -0.02 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     4207 | 2024-02-17 | The Chosen Few    | W   | 0.066      | -            | -                | -                | -         |     0.67 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     4212 | 2024-02-17 | Aurora            | L   | 0.066      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,109.18)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-30 |      0.959 | $1,250.00      | $1,198.35       |
| 2024-06-18 |      0.877 | $6,000.00      | $5,265.00       |
| 2024-05-18 |      0.673 | $1,000.00      | $673.33         |
| 2024-05-16 |      0.657 | $3,000.00      | $1,972.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
