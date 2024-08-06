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
Final Rank Value (841.0) = Starting Rank Value (806.2) + Head To Head Adjustments (34.9)<br />

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
|           46 |       21 | 2024-08-05 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.06 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |      200 | 2024-07-31 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           44 |      402 | 2024-07-25 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.457 (0.065)    | 0 (0.000) |    14.00 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |      662 | 2024-07-18 | Lilmix            | L   | 1.000      | -            | -                | -                | -         |   -13.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           42 |      712 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -17.48 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           41 |      770 | 2024-07-16 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -12.97 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |      822 | 2024-07-15 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -11.19 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           39 |      823 | 2024-07-14 | Turkey            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           38 |      825 | 2024-07-14 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.457 (0.065)    | 0 (0.000) |    10.65 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           37 |      828 | 2024-07-14 | Turkey            | L   | 1.000      | -            | -                | -                | -         |   -26.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |      877 | 2024-07-11 | Illuminar         | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.347 (0.129)    | 0 (0.000) |    17.14 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |      887 | 2024-07-10 | Nexus             | W   | 1.000      | 0.143        | -                | 0.457 (0.065)    | 0 (0.000) |    10.41 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |      917 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |      947 | 2024-07-07 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -17.20 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           32 |      951 | 2024-07-06 | BRUTE             | W   | 0.995      | -            | -                | -                | 0 (0.000) |     2.13 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           31 |      954 | 2024-07-05 | Johnny Speeds     | L   | 0.990      | -            | -                | -                | -         |    -3.18 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |      965 | 2024-06-30 | Lazer Cats        | W   | 0.956      | -            | -                | -                | 0 (0.000) |     3.89 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           29 |     1007 | 2024-06-18 | UNiTY             | W   | 0.875      | 0.333        | 0.025 (0.007)    | 0.300 (0.088)    | -         |    17.84 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |     1012 | 2024-06-17 | K10               | W   | 0.869      | 0.333        | 0.008 (0.002)    | -                | -         |     8.79 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           27 |     1802 | 2024-05-25 | Rebels            | L   | 0.715      | -            | -                | -                | -         |    -6.66 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     1912 | 2024-05-21 | Serbia            | L   | 0.689      | -            | -                | -                | -         |   -13.48 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     2071 | 2024-05-16 | Monte             | L   | 0.657      | -            | -                | -                | -         |    -6.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           24 |     2082 | 2024-05-16 | Zero Tenacity     | L   | 0.655      | -            | -                | -                | -         |    -4.84 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     2137 | 2024-05-15 | Preasy            | W   | 0.649      | 0.333        | -                | 0.221 (0.048)    | -         |     7.80 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     2180 | 2024-05-14 | Alliance          | W   | 0.643      | 0.384        | 0.017 (0.004)    | 0.291 (0.072)    | -         |    10.51 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     2187 | 2024-05-14 | Johnny Speeds     | W   | 0.642      | 0.333        | 0.122 (0.026)    | 1.000 (0.214)    | -         |    18.63 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     2206 | 2024-05-13 | Verdant           | W   | 0.636      | 0.333        | 0.015 (0.003)    | 0.294 (0.062)    | -         |    12.70 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     2503 | 2024-04-29 | Gaimin Gladiators | W   | 0.543      | 0.384        | 0.037 (0.008)    | 0.340 (0.071)    | -         |    12.65 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     2605 | 2024-04-25 | HAVU              | W   | 0.516      | -            | -                | -                | -         |     5.71 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     3069 | 2024-04-09 | ex-Preasy         | L   | 0.409      | -            | -                | -                | -         |    -6.27 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     3563 | 2024-03-15 | Metizport         | W   | 0.244      | -            | -                | -                | -         |     4.40 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     3668 | 2024-03-12 | JANO              | W   | 0.224      | -            | -                | -                | -         |     2.35 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     3679 | 2024-03-11 | CYBERSHOKE        | L   | 0.218      | -            | -                | -                | -         |    -4.70 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     3727 | 2024-03-09 | Enterprise        | W   | 0.204      | 0.372        | 0.039 (0.003)    | -                | -         |     4.14 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           12 |     3773 | 2024-03-07 | Endpoint          | L   | 0.191      | -            | -                | -                | -         |    -2.31 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           11 |     3784 | 2024-03-07 | Permitta          | L   | 0.189      | -            | -                | -                | -         |    -1.71 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     3892 | 2024-03-03 | ex-Preasy         | L   | 0.164      | -            | -                | -                | -         |    -2.81 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            9 |     3916 | 2024-03-02 | MOUZ NXT          | L   | 0.157      | -            | -                | -                | -         |    -1.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            8 |     3954 | 2024-02-28 | Aurora            | L   | 0.138      | -            | -                | -                | -         |    -0.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            7 |     3959 | 2024-02-28 | KOI               | L   | 0.137      | -            | -                | -                | -         |    -0.76 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            6 |     3974 | 2024-02-27 | DMS               | W   | 0.131      | -            | -                | -                | -         |     2.62 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     3984 | 2024-02-27 | INGLORIOUS        | W   | 0.131      | -            | -                | -                | -         |     0.74 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     3985 | 2024-02-27 | AURA              | W   | 0.130      | -            | -                | -                | -         |     0.61 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     4208 | 2024-02-17 | Aurora            | L   | 0.065      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     4210 | 2024-02-17 | The Chosen Few    | W   | 0.064      | -            | -                | -                | -         |     0.64 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     4215 | 2024-02-17 | Aurora            | L   | 0.064      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,084.18)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-30 |      0.956 | $1,250.00      | $1,195.57       |
| 2024-06-18 |      0.875 | $6,000.00      | $5,251.67       |
| 2024-05-18 |      0.671 | $1,000.00      | $671.11         |
| 2024-05-16 |      0.655 | $3,000.00      | $1,965.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
