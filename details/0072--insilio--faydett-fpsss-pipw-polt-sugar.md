### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.4<br />
<br />
Final Rank Value (949.4) = Starting Rank Value (895.2) + Head To Head Adjustments (54.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.2
- 400 + ( ( 0.240 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 895.2


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
|           50 |       19 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |       59 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      124 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      250 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      320 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      385 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    14.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      423 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      463 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.257)    | 0 (0.000) |    10.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      583 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |    -9.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      660 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.799 (0.296)    | 0 (0.000) |    15.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      723 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      745 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      764 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1021 | 2024-06-10 | ARCRED            | W   | 0.859      | 0.372        | 0.038 (0.012)    | -                | 0 (0.000) |    10.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1068 | 2024-06-09 | RUBY              | W   | 0.852      | 0.372        | 0.096 (0.030)    | 0.506 (0.161)    | 0 (0.000) |    10.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1124 | 2024-06-08 | Zero Tenacity     | W   | 0.846      | 0.372        | 0.138 (0.043)    | 1.000 (0.315)    | 0 (0.000) |    18.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1190 | 2024-06-07 | Aurora Young Blud | W   | 0.839      | 0.372        | -                | 0.416 (0.130)    | 0 (0.000) |     9.17 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1393 | 2024-06-03 | RUBY              | L   | 0.813      | -            | -                | -                | -         |   -12.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1450 | 2024-06-01 | 1WIN              | W   | 0.799      | 0.372        | 0.027 (0.008)    | 0.630 (0.187)    | 0 (0.000) |    14.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1503 | 2024-05-30 | VP.Prodigy        | W   | 0.786      | 0.372        | 0.026 (0.008)    | -                | -         |    12.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2159 | 2024-05-07 | RUBY              | L   | 0.632      | -            | -                | -                | -         |   -10.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2178 | 2024-05-06 | Zero Tenacity     | L   | 0.625      | -            | -                | -                | -         |    -7.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2182 | 2024-05-06 | BLEED             | L   | 0.624      | -            | -                | -                | -         |    -6.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2227 | 2024-05-03 | Permitta          | W   | 0.605      | 0.435        | -                | 0.799 (0.210)    | -         |     8.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2239 | 2024-05-03 | BetBoom           | L   | 0.603      | -            | -                | -                | -         |    -1.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2274 | 2024-05-01 | OG                | W   | 0.592      | 0.435        | 0.143 (0.037)    | -                | -         |    12.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2283 | 2024-05-01 | Nexus             | W   | 0.591      | -            | -                | -                | -         |     6.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2325 | 2024-04-29 | HAVU              | L   | 0.578      | -            | -                | -                | -         |   -14.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2361 | 2024-04-27 | ex-Guild Eagles   | W   | 0.566      | -            | -                | -                | -         |     7.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2370 | 2024-04-27 | Permitta          | W   | 0.565      | 0.396        | -                | 0.799 (0.179)    | -         |     9.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2389 | 2024-04-26 | ARCRED            | L   | 0.559      | -            | -                | -                | -         |   -10.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2394 | 2024-04-26 | Enterprise        | W   | 0.558      | 0.396        | 0.040 (0.009)    | 0.622 (0.137)    | -         |     8.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2430 | 2024-04-25 | MOUZ NXT          | W   | 0.550      | 0.435        | 0.140 (0.033)    | 1.000 (0.239)    | -         |    11.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2455 | 2024-04-23 | EYEBALLERS        | W   | 0.539      | -            | -                | -                | -         |     7.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2504 | 2024-04-21 | Permitta          | L   | 0.523      | -            | -                | -                | -         |    -7.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3041 | 2024-04-03 | AMKAL             | L   | 0.406      | -            | -                | -                | -         |    -2.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3082 | 2024-04-02 | ex-Guild Eagles   | W   | 0.399      | -            | -                | -                | -         |     4.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3097 | 2024-04-02 | PARIVISION        | W   | 0.398      | -            | -                | -                | -         |     9.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3324 | 2024-03-18 | Sashi             | L   | 0.298      | -            | -                | -                | -         |    -2.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3383 | 2024-03-15 | CYBERSHOKE        | W   | 0.279      | -            | -                | -                | -         |     1.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3455 | 2024-03-13 | INGLORIOUS        | W   | 0.265      | -            | -                | -                | -         |     0.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3507 | 2024-03-11 | 1WIN              | W   | 0.252      | -            | -                | -                | -         |     3.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3551 | 2024-03-09 | Fraud5            | W   | 0.239      | -            | -                | -                | -         |     1.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3591 | 2024-03-07 | Sashi             | L   | 0.226      | -            | -                | -                | -         |    -1.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3626 | 2024-03-06 | The Chosen Few    | W   | 0.219      | -            | -                | -                | -         |     1.58 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3665 | 2024-03-05 | Johnny Speeds     | L   | 0.213      | -            | -                | -                | -         |    -0.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3672 | 2024-03-05 | Betera            | W   | 0.212      | -            | -                | -                | -         |     1.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4209 | 2024-02-09 | Sashi             | L   | 0.045      | -            | -                | -                | -         |    -0.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4218 | 2024-02-08 | ex-Guild Eagles   | W   | 0.039      | -            | -                | -                | -         |     0.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4224 | 2024-02-08 | AMKAL             | L   | 0.038      | -            | -                | -                | -         |    -0.23 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,672.38)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.859 | $7,000.00      | $6,016.34       |
| 2024-05-04 |      0.612 | $2,000.00      | $1,224.23       |
| 2024-03-25 |      0.345 | $1,250.00      | $431.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
