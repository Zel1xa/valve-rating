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
Final Rank Value (954.7) = Starting Rank Value (894.7) + Head To Head Adjustments (59.9)<br />

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
|           51 |        4 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |       49 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |       91 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      157 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      283 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -9.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      354 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -14.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      421 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    14.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      461 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -15.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      503 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |    10.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      625 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -15.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      710 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.801 (0.297)    | 0 (0.000) |    15.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      773 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      795 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      814 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1062 | 2024-06-10 | ARCRED            | W   | 0.854      | 0.372        | 0.038 (0.012)    | -                | 0 (0.000) |    10.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1109 | 2024-06-09 | RUBY              | W   | 0.846      | 0.372        | 0.097 (0.030)    | 0.544 (0.171)    | 0 (0.000) |    11.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1167 | 2024-06-08 | Zero Tenacity     | W   | 0.840      | 0.372        | 0.139 (0.043)    | 1.000 (0.313)    | 0 (0.000) |    16.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1240 | 2024-06-07 | Aurora Young Blud | W   | 0.833      | 0.372        | -                | 0.449 (0.139)    | 0 (0.000) |     9.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1448 | 2024-06-03 | RUBY              | L   | 0.807      | -            | -                | -                | -         |   -12.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1506 | 2024-06-01 | 1WIN              | W   | 0.793      | 0.372        | 0.027 (0.008)    | 0.629 (0.186)    | -         |    14.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1559 | 2024-05-30 | VP.Prodigy        | W   | 0.780      | 0.372        | 0.026 (0.008)    | -                | -         |    12.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2254 | 2024-05-07 | RUBY              | L   | 0.626      | -            | -                | -                | -         |    -9.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2273 | 2024-05-06 | Zero Tenacity     | L   | 0.620      | -            | -                | -                | -         |    -7.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2277 | 2024-05-06 | BLEED             | L   | 0.618      | -            | -                | -                | -         |    -6.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2322 | 2024-05-03 | Permitta          | W   | 0.599      | 0.435        | -                | 0.801 (0.209)    | -         |     8.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2334 | 2024-05-03 | BetBoom           | L   | 0.598      | -            | -                | -                | -         |    -1.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2371 | 2024-05-01 | OG                | W   | 0.587      | 0.435        | 0.143 (0.037)    | -                | -         |    12.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2380 | 2024-05-01 | Nexus             | W   | 0.585      | -            | -                | -                | -         |     6.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2423 | 2024-04-29 | HAVU              | L   | 0.572      | -            | -                | -                | -         |   -14.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2459 | 2024-04-27 | ex-Guild Eagles   | W   | 0.560      | -            | -                | -                | -         |     7.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2469 | 2024-04-27 | Permitta          | W   | 0.559      | 0.396        | -                | 0.801 (0.177)    | -         |     9.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2488 | 2024-04-26 | ARCRED            | L   | 0.553      | -            | -                | -                | -         |   -10.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2492 | 2024-04-26 | Enterprise        | W   | 0.552      | 0.396        | 0.040 (0.009)    | 0.622 (0.136)    | -         |     8.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2528 | 2024-04-25 | MOUZ NXT          | W   | 0.544      | 0.435        | 0.141 (0.033)    | 1.000 (0.236)    | -         |    11.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2554 | 2024-04-23 | EYEBALLERS        | W   | 0.533      | -            | -                | -                | -         |     7.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2606 | 2024-04-21 | Permitta          | L   | 0.517      | -            | -                | -                | -         |    -7.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3152 | 2024-04-03 | AMKAL             | L   | 0.400      | -            | -                | -                | -         |    -2.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3199 | 2024-04-02 | ex-Guild Eagles   | W   | 0.394      | -            | -                | -                | -         |     4.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3214 | 2024-04-02 | PARIVISION        | W   | 0.392      | -            | -                | -                | -         |     9.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3446 | 2024-03-18 | Sashi             | L   | 0.292      | -            | -                | -                | -         |    -2.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3505 | 2024-03-15 | CYBERSHOKE        | W   | 0.274      | -            | -                | -                | -         |     1.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3581 | 2024-03-13 | INGLORIOUS        | W   | 0.260      | -            | -                | -                | -         |     0.97 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3634 | 2024-03-11 | 1WIN              | W   | 0.246      | -            | -                | -                | -         |     3.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3679 | 2024-03-09 | Fraud5            | W   | 0.233      | -            | -                | -                | -         |     1.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3719 | 2024-03-07 | Sashi             | L   | 0.221      | -            | -                | -                | -         |    -1.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3754 | 2024-03-06 | The Chosen Few    | W   | 0.214      | -            | -                | -                | -         |     1.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3797 | 2024-03-05 | Johnny Speeds     | L   | 0.207      | -            | -                | -                | -         |    -0.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3805 | 2024-03-05 | Betera            | W   | 0.207      | -            | -                | -                | -         |     1.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4362 | 2024-02-09 | Sashi             | L   | 0.039      | -            | -                | -                | -         |    -0.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4371 | 2024-02-08 | ex-Guild Eagles   | W   | 0.034      | -            | -                | -                | -         |     0.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4377 | 2024-02-08 | AMKAL             | L   | 0.033      | -            | -                | -                | -         |    -0.20 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,613.68)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.854 | $7,000.00      | $5,976.25       |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.78       |
| 2024-03-25 |      0.340 | $1,250.00      | $424.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
