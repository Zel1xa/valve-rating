### Roster Details<br />
Team Name: kONO<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
<br />
Final Rank Value:  863.1<br />
<br />
Final Rank Value (863.1) = Starting Rank Value (810.9) + Head To Head Adjustments (52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.313[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 810.9
- 400 + ( ( 0.200 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 810.9


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
|           47 |       22 | 2024-08-06 | Illuminar         | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.340 (0.113)    | 0 (0.000) |    18.70 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           46 |       43 | 2024-08-05 | INFINITE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.04 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           45 |      223 | 2024-07-31 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.30 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           44 |      425 | 2024-07-25 | Nexus             | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.447 (0.064)    | 0 (0.000) |    14.05 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           43 |      685 | 2024-07-18 | Lilmix            | L   | 1.000      | -            | -                | -                | -         |   -13.47 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           42 |      735 | 2024-07-17 | Preasy            | L   | 1.000      | -            | -                | -                | -         |   -17.56 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           41 |      793 | 2024-07-16 | Illuminar         | L   | 1.000      | -            | -                | -                | -         |   -12.93 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           40 |      845 | 2024-07-15 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -11.30 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           39 |      846 | 2024-07-14 | Turkey            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           38 |      848 | 2024-07-14 | Nexus             | W   | 1.000      | 0.143        | -                | 0.447 (0.064)    | 0 (0.000) |    10.70 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           37 |      851 | 2024-07-14 | Turkey            | L   | 1.000      | -            | -                | -                | -         |   -26.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           36 |      900 | 2024-07-11 | Illuminar         | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.340 (0.126)    | 0 (0.000) |    17.19 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           35 |      910 | 2024-07-10 | Nexus             | W   | 1.000      | 0.143        | -                | 0.447 (0.064)    | 0 (0.000) |    10.46 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           34 |      940 | 2024-07-09 | 500               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.36 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           33 |      970 | 2024-07-07 | Revenant          | L   | 0.998      | -            | -                | -                | -         |   -17.29 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           32 |      974 | 2024-07-06 | BRUTE             | W   | 0.991      | -            | -                | -                | 0 (0.000) |     2.08 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           31 |      977 | 2024-07-05 | Johnny Speeds     | L   | 0.985      | -            | -                | -                | -         |    -3.17 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           30 |      988 | 2024-06-30 | Lazer Cats        | W   | 0.952      | -            | -                | -                | -         |     3.81 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           29 |     1030 | 2024-06-18 | UNiTY             | W   | 0.871      | 0.333        | 0.024 (0.007)    | 0.331 (0.096)    | -         |    17.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |     1035 | 2024-06-17 | K10               | W   | 0.864      | 0.333        | 0.008 (0.002)    | -                | -         |     8.63 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           27 |     1825 | 2024-05-25 | Rebels            | L   | 0.711      | -            | -                | -                | -         |    -6.67 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |     1935 | 2024-05-21 | Serbia            | L   | 0.685      | -            | -                | -                | -         |   -13.41 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |     2094 | 2024-05-16 | Monte             | L   | 0.652      | -            | -                | -                | -         |    -6.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           24 |     2105 | 2024-05-16 | Zero Tenacity     | L   | 0.651      | -            | -                | -                | -         |    -4.82 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     2160 | 2024-05-15 | Preasy            | W   | 0.644      | -            | -                | -                | -         |     7.65 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     2203 | 2024-05-14 | Alliance          | W   | 0.639      | 0.384        | 0.017 (0.004)    | 0.282 (0.069)    | -         |    10.38 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     2210 | 2024-05-14 | Johnny Speeds     | W   | 0.638      | 0.333        | 0.122 (0.026)    | 1.000 (0.213)    | -         |    18.50 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     2229 | 2024-05-13 | Verdant           | W   | 0.632      | 0.333        | 0.015 (0.003)    | 0.287 (0.060)    | -         |    12.64 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     2526 | 2024-04-29 | Gaimin Gladiators | W   | 0.539      | 0.384        | 0.037 (0.008)    | 0.331 (0.068)    | -         |    12.44 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     2628 | 2024-04-25 | HAVU              | W   | 0.511      | -            | -                | -                | -         |     5.56 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     3092 | 2024-04-09 | ex-Preasy         | L   | 0.405      | -            | -                | -                | -         |    -6.31 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           16 |     3586 | 2024-03-15 | Metizport         | W   | 0.240      | -            | -                | -                | -         |     4.96 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           15 |     3691 | 2024-03-12 | JANO              | W   | 0.219      | -            | -                | -                | -         |     2.27 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     3702 | 2024-03-11 | CYBERSHOKE        | L   | 0.214      | -            | -                | -                | -         |    -4.65 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     3750 | 2024-03-09 | Enterprise        | W   | 0.200      | 0.372        | 0.039 (0.003)    | -                | -         |     4.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           12 |     3796 | 2024-03-07 | Endpoint          | L   | 0.187      | -            | -                | -                | -         |    -2.27 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           11 |     3807 | 2024-03-07 | Permitta          | L   | 0.185      | -            | -                | -                | -         |    -1.57 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     3915 | 2024-03-03 | ex-Preasy         | L   | 0.160      | -            | -                | -                | -         |    -2.77 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            9 |     3939 | 2024-03-02 | MOUZ NXT          | L   | 0.152      | -            | -                | -                | -         |    -1.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            8 |     3977 | 2024-02-28 | Aurora            | L   | 0.134      | -            | -                | -                | -         |    -0.03 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            7 |     3982 | 2024-02-28 | KOI               | L   | 0.133      | -            | -                | -                | -         |    -0.76 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            6 |     3997 | 2024-02-27 | DMS               | W   | 0.127      | -            | -                | -                | -         |     2.52 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     4007 | 2024-02-27 | INGLORIOUS        | W   | 0.127      | -            | -                | -                | -         |     0.70 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     4008 | 2024-02-27 | AURA              | W   | 0.126      | -            | -                | -                | -         |     0.57 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     4231 | 2024-02-17 | Aurora            | L   | 0.060      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     4233 | 2024-02-17 | The Chosen Few    | W   | 0.060      | -            | -                | -                | -         |     0.59 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     4238 | 2024-02-17 | Aurora            | L   | 0.059      | -            | -                | -                | -         |    -0.01 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,035.75)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-30 |      0.952 | $1,250.00      | $1,190.19       |
| 2024-06-18 |      0.871 | $6,000.00      | $5,225.83       |
| 2024-05-18 |      0.667 | $1,000.00      | $666.81         |
| 2024-05-16 |      0.651 | $3,000.00      | $1,952.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
