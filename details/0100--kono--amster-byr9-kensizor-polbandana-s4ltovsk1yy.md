### Roster Details<br />
Team Name: kONO<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.7<br />
<br />
Final Rank Value (861.7) = Starting Rank Value (810.3) + Head To Head Adjustments (51.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 810.3
- 400 + ( ( 0.200 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 810.3


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
|           47 |        3 | 2024-08-06 | Illuminar         | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.347 (0.116)    | 0 (0.000) |    18.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |       25 | 2024-08-05 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.01 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |      204 | 2024-07-31 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.32 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           44 |      406 | 2024-07-25 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.457 (0.065)    | 0 (0.000) |    13.99 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |      666 | 2024-07-18 | Lilmix            | L   | 1.000      | -            | -                | -                | -         |   -13.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           42 |      716 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -17.58 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           41 |      774 | 2024-07-16 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -13.06 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |      826 | 2024-07-15 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -11.29 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           39 |      827 | 2024-07-14 | Turkey            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.41 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           38 |      829 | 2024-07-14 | Nexus             | W   | 1.000      | 0.143        | -                | 0.457 (0.065)    | 0 (0.000) |    10.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           37 |      832 | 2024-07-14 | Turkey            | L   | 1.000      | -            | -                | -                | -         |   -26.37 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |      881 | 2024-07-11 | Illuminar         | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.347 (0.129)    | 0 (0.000) |    17.04 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |      891 | 2024-07-10 | Nexus             | W   | 1.000      | 0.143        | -                | 0.457 (0.065)    | 0 (0.000) |    10.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |      921 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.37 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |      951 | 2024-07-07 | Revenant          | L   | 1.000      | -            | -                | -                | -         |   -17.32 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           32 |      955 | 2024-07-06 | BRUTE             | W   | 0.993      | -            | -                | -                | 0 (0.000) |     2.09 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           31 |      958 | 2024-07-05 | Johnny Speeds     | L   | 0.987      | -            | -                | -                | -         |    -3.21 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |      969 | 2024-06-30 | Lazer Cats        | W   | 0.954      | -            | -                | -                | -         |     3.83 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           29 |     1011 | 2024-06-18 | UNiTY             | W   | 0.873      | 0.333        | 0.024 (0.007)    | 0.300 (0.087)    | -         |    17.68 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |     1016 | 2024-06-17 | K10               | W   | 0.866      | 0.333        | 0.008 (0.002)    | -                | -         |     8.66 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           27 |     1806 | 2024-05-25 | Rebels            | L   | 0.713      | -            | -                | -                | -         |    -6.71 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     1916 | 2024-05-21 | Serbia            | L   | 0.687      | -            | -                | -                | -         |   -13.52 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     2075 | 2024-05-16 | Monte             | L   | 0.654      | -            | -                | -                | -         |    -6.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           24 |     2086 | 2024-05-16 | Zero Tenacity     | L   | 0.653      | -            | -                | -                | -         |    -4.87 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     2141 | 2024-05-15 | Preasy            | W   | 0.646      | -            | -                | -                | -         |     7.68 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     2184 | 2024-05-14 | Alliance          | W   | 0.641      | 0.384        | 0.017 (0.004)    | 0.289 (0.071)    | -         |    10.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     2191 | 2024-05-14 | Johnny Speeds     | W   | 0.640      | 0.333        | 0.122 (0.026)    | 1.000 (0.213)    | -         |    18.53 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     2210 | 2024-05-13 | Verdant           | W   | 0.633      | 0.333        | 0.015 (0.003)    | 0.294 (0.062)    | -         |    12.55 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     2507 | 2024-04-29 | Gaimin Gladiators | W   | 0.541      | 0.384        | 0.037 (0.008)    | 0.339 (0.070)    | -         |    12.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     2609 | 2024-04-25 | HAVU              | W   | 0.513      | -            | -                | -                | -         |     5.59 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     3073 | 2024-04-09 | ex-Preasy         | L   | 0.406      | -            | -                | -                | -         |    -6.32 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     3567 | 2024-03-15 | Metizport         | W   | 0.242      | -            | -                | -                | -         |     4.96 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     3672 | 2024-03-12 | JANO              | W   | 0.221      | -            | -                | -                | -         |     2.29 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     3683 | 2024-03-11 | CYBERSHOKE        | L   | 0.216      | -            | -                | -                | -         |    -4.68 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     3731 | 2024-03-09 | Enterprise        | W   | 0.201      | 0.372        | 0.039 (0.003)    | -                | -         |     4.07 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           12 |     3777 | 2024-03-07 | Endpoint          | L   | 0.189      | -            | -                | -                | -         |    -2.31 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           11 |     3788 | 2024-03-07 | Permitta          | L   | 0.187      | -            | -                | -                | -         |    -1.71 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     3896 | 2024-03-03 | ex-Preasy         | L   | 0.162      | -            | -                | -                | -         |    -2.80 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            9 |     3920 | 2024-03-02 | MOUZ NXT          | L   | 0.154      | -            | -                | -                | -         |    -1.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            8 |     3958 | 2024-02-28 | Aurora            | L   | 0.136      | -            | -                | -                | -         |    -0.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            7 |     3963 | 2024-02-28 | KOI               | L   | 0.135      | -            | -                | -                | -         |    -0.76 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            6 |     3978 | 2024-02-27 | DMS               | W   | 0.129      | -            | -                | -                | -         |     2.55 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     3988 | 2024-02-27 | INGLORIOUS        | W   | 0.129      | -            | -                | -                | -         |     0.72 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     3989 | 2024-02-27 | AURA              | W   | 0.128      | -            | -                | -                | -         |     0.58 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     4212 | 2024-02-17 | Aurora            | L   | 0.062      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     4214 | 2024-02-17 | The Chosen Few    | W   | 0.062      | -            | -                | -                | -         |     0.61 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     4219 | 2024-02-17 | Aurora            | L   | 0.061      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,056.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-30 |      0.954 | $1,250.00      | $1,192.45       |
| 2024-06-18 |      0.873 | $6,000.00      | $5,236.67       |
| 2024-05-18 |      0.669 | $1,000.00      | $668.61         |
| 2024-05-16 |      0.653 | $3,000.00      | $1,958.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
