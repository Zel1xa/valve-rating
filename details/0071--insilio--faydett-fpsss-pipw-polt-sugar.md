### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.7<br />
<br />
Final Rank Value (954.7) = Starting Rank Value (894.7) + Head To Head Adjustments (60.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 894.7
- 400 + ( ( 0.240 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 894.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |        8 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |       54 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |       94 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      159 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      285 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -9.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      356 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -14.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      423 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    14.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      463 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -15.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      507 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |    10.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      629 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -15.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      712 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.801 (0.297)    | 0 (0.000) |    15.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      775 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      797 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      816 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1064 | 2024-06-10 | ARCRED            | W   | 0.853      | 0.372        | 0.038 (0.012)    | -                | 0 (0.000) |    10.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1111 | 2024-06-09 | RUBY              | W   | 0.846      | 0.372        | 0.097 (0.030)    | 0.544 (0.171)    | 0 (0.000) |    11.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1169 | 2024-06-08 | Zero Tenacity     | W   | 0.840      | 0.372        | 0.139 (0.043)    | 1.000 (0.313)    | 0 (0.000) |    16.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1242 | 2024-06-07 | Aurora Young Blud | W   | 0.833      | 0.372        | -                | 0.449 (0.139)    | 0 (0.000) |     9.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1450 | 2024-06-03 | RUBY              | L   | 0.807      | -            | -                | -                | -         |   -12.53 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1508 | 2024-06-01 | 1WIN              | W   | 0.792      | 0.372        | 0.027 (0.008)    | 0.629 (0.186)    | -         |    14.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1561 | 2024-05-30 | VP.Prodigy        | W   | 0.780      | 0.372        | 0.026 (0.008)    | -                | -         |    12.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2256 | 2024-05-07 | RUBY              | L   | 0.626      | -            | -                | -                | -         |    -9.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2275 | 2024-05-06 | Zero Tenacity     | L   | 0.619      | -            | -                | -                | -         |    -7.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2279 | 2024-05-06 | BLEED             | L   | 0.618      | -            | -                | -                | -         |    -6.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2324 | 2024-05-03 | Permitta          | W   | 0.599      | 0.435        | -                | 0.801 (0.209)    | -         |     8.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2336 | 2024-05-03 | BetBoom           | L   | 0.597      | -            | -                | -                | -         |    -1.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2373 | 2024-05-01 | OG                | W   | 0.586      | 0.435        | 0.143 (0.036)    | -                | -         |    12.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2382 | 2024-05-01 | Nexus             | W   | 0.585      | -            | -                | -                | -         |     6.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2425 | 2024-04-29 | HAVU              | L   | 0.572      | -            | -                | -                | -         |   -14.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2461 | 2024-04-27 | ex-Guild Eagles   | W   | 0.560      | -            | -                | -                | -         |     7.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2471 | 2024-04-27 | Permitta          | W   | 0.559      | 0.396        | -                | 0.801 (0.177)    | -         |     9.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2490 | 2024-04-26 | ARCRED            | L   | 0.552      | -            | -                | -                | -         |   -10.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2494 | 2024-04-26 | Enterprise        | W   | 0.552      | 0.396        | 0.040 (0.009)    | 0.622 (0.136)    | -         |     8.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2530 | 2024-04-25 | MOUZ NXT          | W   | 0.544      | 0.435        | 0.141 (0.033)    | 1.000 (0.236)    | -         |    11.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2556 | 2024-04-23 | EYEBALLERS        | W   | 0.533      | -            | -                | -                | -         |     7.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2608 | 2024-04-21 | Permitta          | L   | 0.517      | -            | -                | -                | -         |    -7.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3154 | 2024-04-03 | AMKAL             | L   | 0.400      | -            | -                | -                | -         |    -2.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3201 | 2024-04-02 | ex-Guild Eagles   | W   | 0.393      | -            | -                | -                | -         |     4.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3216 | 2024-04-02 | PARIVISION        | W   | 0.392      | -            | -                | -                | -         |     9.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3448 | 2024-03-18 | Sashi             | L   | 0.292      | -            | -                | -                | -         |    -1.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3507 | 2024-03-15 | CYBERSHOKE        | W   | 0.273      | -            | -                | -                | -         |     1.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3583 | 2024-03-13 | INGLORIOUS        | W   | 0.259      | -            | -                | -                | -         |     0.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3636 | 2024-03-11 | 1WIN              | W   | 0.246      | -            | -                | -                | -         |     3.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3681 | 2024-03-09 | Fraud5            | W   | 0.233      | -            | -                | -                | -         |     1.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3721 | 2024-03-07 | Sashi             | L   | 0.220      | -            | -                | -                | -         |    -1.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3756 | 2024-03-06 | The Chosen Few    | W   | 0.213      | -            | -                | -                | -         |     1.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3799 | 2024-03-05 | Johnny Speeds     | L   | 0.207      | -            | -                | -                | -         |    -0.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3807 | 2024-03-05 | Betera            | W   | 0.206      | -            | -                | -                | -         |     1.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4364 | 2024-02-09 | Sashi             | L   | 0.039      | -            | -                | -                | -         |    -0.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4373 | 2024-02-08 | ex-Guild Eagles   | W   | 0.033      | -            | -                | -                | -         |     0.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4379 | 2024-02-08 | AMKAL             | L   | 0.032      | -            | -                | -                | -         |    -0.19 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,610.83)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.853 | $7,000.00      | $5,974.31       |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.22       |
| 2024-03-25 |      0.339 | $1,250.00      | $424.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
