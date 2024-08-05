### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.7<br />
<br />
Final Rank Value (945.7) = Starting Rank Value (893.4) + Head To Head Adjustments (52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.216[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.4
- 400 + ( ( 0.241 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 893.4


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
|           54 |       42 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       81 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      110 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      149 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      194 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      234 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      299 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      425 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      495 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      560 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      598 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      638 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |    10.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      758 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      835 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.902 (0.334)    | 0 (0.000) |    15.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      898 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      920 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      939 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1196 | 2024-06-10 | ARCRED            | W   | 0.827      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1243 | 2024-06-09 | RUBY              | W   | 0.819      | 0.372        | 0.095 (0.029)    | 0.492 (0.150)    | 0 (0.000) |    10.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1299 | 2024-06-08 | Zero Tenacity     | W   | 0.813      | 0.372        | 0.143 (0.043)    | 1.000 (0.303)    | 0 (0.000) |    17.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1365 | 2024-06-07 | Aurora Young Blud | W   | 0.806      | 0.372        | -                | 0.532 (0.160)    | -         |    10.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1568 | 2024-06-03 | RUBY              | L   | 0.780      | -            | -                | -                | -         |   -12.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1625 | 2024-06-01 | 1WIN              | W   | 0.766      | 0.372        | 0.033 (0.009)    | 0.696 (0.198)    | -         |    14.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1678 | 2024-05-30 | VP.Prodigy        | W   | 0.753      | 0.372        | 0.025 (0.007)    | -                | -         |    11.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2334 | 2024-05-07 | RUBY              | L   | 0.599      | -            | -                | -                | -         |    -9.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2353 | 2024-05-06 | Zero Tenacity     | L   | 0.593      | -            | -                | -                | -         |    -6.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2357 | 2024-05-06 | BLEED             | L   | 0.591      | -            | -                | -                | -         |    -6.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2402 | 2024-05-03 | Permitta          | W   | 0.572      | 0.435        | -                | 0.902 (0.224)    | -         |     8.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2414 | 2024-05-03 | BetBoom           | L   | 0.570      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2449 | 2024-05-01 | OG                | W   | 0.560      | 0.435        | 0.138 (0.033)    | -                | -         |    11.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2458 | 2024-05-01 | Nexus             | W   | 0.558      | -            | -                | -                | -         |     6.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2500 | 2024-04-29 | HAVU              | L   | 0.545      | -            | -                | -                | -         |   -13.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2536 | 2024-04-27 | ex-Guild Eagles   | W   | 0.533      | -            | -                | -                | -         |     6.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2545 | 2024-04-27 | Permitta          | W   | 0.532      | 0.396        | -                | 0.902 (0.190)    | -         |     9.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2564 | 2024-04-26 | ARCRED            | L   | 0.526      | -            | -                | -                | -         |    -8.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2569 | 2024-04-26 | Enterprise        | W   | 0.525      | 0.396        | 0.039 (0.008)    | 0.616 (0.128)    | -         |     7.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2605 | 2024-04-25 | MOUZ NXT          | W   | 0.517      | 0.435        | 0.139 (0.031)    | 0.987 (0.222)    | -         |    10.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2630 | 2024-04-23 | EYEBALLERS        | W   | 0.506      | -            | -                | -                | -         |     7.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2679 | 2024-04-21 | Permitta          | L   | 0.490      | -            | -                | -                | -         |    -6.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3216 | 2024-04-03 | AMKAL             | L   | 0.373      | -            | -                | -                | -         |    -2.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3257 | 2024-04-02 | ex-Guild Eagles   | W   | 0.367      | -            | -                | -                | -         |     4.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3272 | 2024-04-02 | PARIVISION        | W   | 0.365      | -            | -                | -                | -         |     8.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3499 | 2024-03-18 | Sashi             | L   | 0.265      | -            | -                | -                | -         |    -1.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3558 | 2024-03-15 | CYBERSHOKE        | W   | 0.247      | -            | -                | -                | -         |     1.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3630 | 2024-03-13 | INGLORIOUS        | W   | 0.233      | -            | -                | -                | -         |     0.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3682 | 2024-03-11 | 1WIN              | W   | 0.219      | -            | -                | -                | -         |     3.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3726 | 2024-03-09 | Fraud5            | W   | 0.206      | -            | -                | -                | -         |     1.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3766 | 2024-03-07 | Sashi             | L   | 0.194      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3801 | 2024-03-06 | The Chosen Few    | W   | 0.187      | -            | -                | -                | -         |     1.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3840 | 2024-03-05 | Johnny Speeds     | L   | 0.180      | -            | -                | -                | -         |    -0.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3847 | 2024-03-05 | Betera            | W   | 0.180      | -            | -                | -                | -         |     1.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4384 | 2024-02-09 | Sashi             | L   | 0.012      | -            | -                | -                | -         |    -0.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4393 | 2024-02-08 | ex-Guild Eagles   | W   | 0.007      | -            | -                | -                | -         |     0.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4399 | 2024-02-08 | AMKAL             | L   | 0.006      | -            | -                | -                | -         |    -0.03 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,336.08)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.827 | $7,000.00      | $5,786.67       |
| 2024-05-04 |      0.579 | $2,000.00      | $1,158.61       |
| 2024-03-25 |      0.313 | $1,250.00      | $390.80         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
