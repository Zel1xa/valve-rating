### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [76](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.6<br />
<br />
Final Rank Value (944.6) = Starting Rank Value (891.8) + Head To Head Adjustments (52.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.8
- 400 + ( ( 0.240 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 891.8


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
|           54 |       41 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       80 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      109 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      148 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      193 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      233 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      298 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      424 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      494 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      559 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      597 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      637 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |    10.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      757 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      834 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.863 (0.320)    | 0 (0.000) |    15.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      897 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      919 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      938 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1195 | 2024-06-10 | ARCRED            | W   | 0.827      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    12.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1242 | 2024-06-09 | RUBY              | W   | 0.820      | 0.372        | 0.095 (0.029)    | 0.492 (0.150)    | 0 (0.000) |    10.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1298 | 2024-06-08 | Zero Tenacity     | W   | 0.814      | 0.372        | 0.143 (0.043)    | 1.000 (0.303)    | 0 (0.000) |    17.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1364 | 2024-06-07 | Aurora Young Blud | W   | 0.807      | 0.372        | -                | 0.532 (0.160)    | -         |    10.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1567 | 2024-06-03 | RUBY              | L   | 0.780      | -            | -                | -                | -         |   -12.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1624 | 2024-06-01 | 1WIN              | W   | 0.766      | 0.372        | 0.033 (0.009)    | 0.696 (0.199)    | -         |    14.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1677 | 2024-05-30 | VP.Prodigy        | W   | 0.754      | 0.372        | 0.025 (0.007)    | -                | -         |    11.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2333 | 2024-05-07 | RUBY              | L   | 0.600      | -            | -                | -                | -         |    -9.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2352 | 2024-05-06 | Zero Tenacity     | L   | 0.593      | -            | -                | -                | -         |    -6.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2356 | 2024-05-06 | BLEED             | L   | 0.592      | -            | -                | -                | -         |    -6.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2401 | 2024-05-03 | Permitta          | W   | 0.573      | 0.435        | -                | 0.863 (0.215)    | -         |     8.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2413 | 2024-05-03 | BetBoom           | L   | 0.571      | -            | -                | -                | -         |    -1.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2448 | 2024-05-01 | OG                | W   | 0.560      | 0.435        | 0.138 (0.034)    | -                | -         |    11.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2457 | 2024-05-01 | Nexus             | W   | 0.559      | -            | -                | -                | -         |     6.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2499 | 2024-04-29 | HAVU              | L   | 0.545      | -            | -                | -                | -         |   -13.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2535 | 2024-04-27 | ex-Guild Eagles   | W   | 0.533      | -            | -                | -                | -         |     6.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2544 | 2024-04-27 | Permitta          | W   | 0.532      | 0.396        | -                | 0.863 (0.182)    | -         |     9.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2563 | 2024-04-26 | ARCRED            | L   | 0.526      | -            | -                | -                | -         |    -8.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2568 | 2024-04-26 | Enterprise        | W   | 0.525      | 0.396        | 0.039 (0.008)    | 0.616 (0.128)    | -         |     7.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2604 | 2024-04-25 | MOUZ NXT          | W   | 0.517      | 0.435        | 0.139 (0.031)    | 0.987 (0.222)    | -         |    10.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2629 | 2024-04-23 | EYEBALLERS        | W   | 0.507      | -            | -                | -                | -         |     7.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2678 | 2024-04-21 | Permitta          | L   | 0.491      | -            | -                | -                | -         |    -6.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3215 | 2024-04-03 | AMKAL             | L   | 0.374      | -            | -                | -                | -         |    -2.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3256 | 2024-04-02 | ex-Guild Eagles   | W   | 0.367      | -            | -                | -                | -         |     4.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3271 | 2024-04-02 | PARIVISION        | W   | 0.366      | -            | -                | -                | -         |     8.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3498 | 2024-03-18 | Sashi             | L   | 0.266      | -            | -                | -                | -         |    -1.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3557 | 2024-03-15 | CYBERSHOKE        | W   | 0.247      | -            | -                | -                | -         |     1.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3629 | 2024-03-13 | INGLORIOUS        | W   | 0.233      | -            | -                | -                | -         |     0.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3681 | 2024-03-11 | 1WIN              | W   | 0.220      | -            | -                | -                | -         |     3.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3725 | 2024-03-09 | Fraud5            | W   | 0.206      | -            | -                | -                | -         |     1.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3765 | 2024-03-07 | Sashi             | L   | 0.194      | -            | -                | -                | -         |    -1.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3800 | 2024-03-06 | The Chosen Few    | W   | 0.187      | -            | -                | -                | -         |     1.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3839 | 2024-03-05 | Johnny Speeds     | L   | 0.180      | -            | -                | -                | -         |    -0.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3846 | 2024-03-05 | Betera            | W   | 0.180      | -            | -                | -                | -         |     1.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4383 | 2024-02-09 | Sashi             | L   | 0.013      | -            | -                | -                | -         |    -0.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4392 | 2024-02-08 | ex-Guild Eagles   | W   | 0.007      | -            | -                | -                | -         |     0.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4398 | 2024-02-08 | AMKAL             | L   | 0.006      | -            | -                | -                | -         |    -0.04 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,340.35)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.827 | $7,000.00      | $5,789.58       |
| 2024-05-04 |      0.580 | $2,000.00      | $1,159.44       |
| 2024-03-25 |      0.313 | $1,250.00      | $391.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
