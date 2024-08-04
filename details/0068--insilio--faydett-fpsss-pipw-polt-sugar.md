### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.9<br />
<br />
Final Rank Value (957.9) = Starting Rank Value (890.3) + Head To Head Adjustments (67.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.3
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 890.3


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
|           53 |       22 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |       51 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |       88 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.93 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      131 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.95 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      173 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      238 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      364 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      434 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      499 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      537 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      575 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |    10.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      695 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |    -9.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      774 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.876 (0.325)    | 0 (0.000) |    15.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      836 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      858 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      877 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1134 | 2024-06-10 | ARCRED            | W   | 0.839      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    10.98 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1181 | 2024-06-09 | RUBY              | W   | 0.831      | 0.372        | 0.095 (0.029)    | 0.502 (0.156)    | 0 (0.000) |    10.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1237 | 2024-06-08 | Zero Tenacity     | W   | 0.825      | 0.372        | 0.137 (0.042)    | 1.000 (0.307)    | 0 (0.000) |    17.95 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1303 | 2024-06-07 | Aurora Young Blud | W   | 0.818      | 0.372        | -                | 0.419 (0.128)    | -         |     9.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1506 | 2024-06-03 | RUBY              | L   | 0.792      | -            | -                | -                | -         |   -12.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1563 | 2024-06-01 | 1WIN              | W   | 0.778      | 0.372        | 0.027 (0.008)    | 0.629 (0.182)    | -         |    14.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1616 | 2024-05-30 | VP.Prodigy        | W   | 0.765      | 0.372        | 0.026 (0.007)    | -                | -         |    11.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2272 | 2024-05-07 | RUBY              | L   | 0.611      | -            | -                | -                | -         |    -9.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2291 | 2024-05-06 | Zero Tenacity     | L   | 0.605      | -            | -                | -                | -         |    -6.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2295 | 2024-05-06 | BLEED             | L   | 0.603      | -            | -                | -                | -         |    -6.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2340 | 2024-05-03 | Permitta          | W   | 0.584      | 0.435        | -                | 0.876 (0.223)    | -         |     8.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2352 | 2024-05-03 | BetBoom           | L   | 0.583      | -            | -                | -                | -         |    -1.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2387 | 2024-05-01 | OG                | W   | 0.572      | 0.435        | 0.140 (0.035)    | -                | -         |    12.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2396 | 2024-05-01 | Nexus             | W   | 0.570      | -            | -                | -                | -         |     6.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2438 | 2024-04-29 | HAVU              | L   | 0.557      | -            | -                | -                | -         |   -13.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2474 | 2024-04-27 | ex-Guild Eagles   | W   | 0.545      | -            | -                | -                | -         |     6.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2483 | 2024-04-27 | Permitta          | W   | 0.544      | 0.396        | -                | 0.876 (0.189)    | -         |     9.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2502 | 2024-04-26 | ARCRED            | L   | 0.538      | -            | -                | -                | -         |    -9.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2506 | 2024-04-26 | Enterprise        | W   | 0.537      | 0.396        | 0.039 (0.008)    | 0.624 (0.133)    | -         |     8.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2542 | 2024-04-25 | MOUZ NXT          | W   | 0.529      | 0.435        | 0.139 (0.032)    | 1.000 (0.230)    | -         |    11.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2567 | 2024-04-23 | EYEBALLERS        | W   | 0.518      | -            | -                | -                | -         |     7.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2616 | 2024-04-21 | Permitta          | L   | 0.502      | -            | -                | -                | -         |    -6.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3153 | 2024-04-03 | AMKAL             | L   | 0.385      | -            | -                | -                | -         |    -2.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3194 | 2024-04-02 | ex-Guild Eagles   | W   | 0.379      | -            | -                | -                | -         |     4.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3209 | 2024-04-02 | PARIVISION        | W   | 0.377      | -            | -                | -                | -         |     9.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3436 | 2024-03-18 | Sashi             | L   | 0.278      | -            | -                | -                | -         |    -1.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3495 | 2024-03-15 | CYBERSHOKE        | W   | 0.259      | -            | -                | -                | -         |     1.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3566 | 2024-03-13 | INGLORIOUS        | W   | 0.245      | -            | -                | -                | -         |     0.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3618 | 2024-03-11 | 1WIN              | W   | 0.231      | -            | -                | -                | -         |     3.61 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3662 | 2024-03-09 | Fraud5            | W   | 0.218      | -            | -                | -                | -         |     1.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3702 | 2024-03-07 | Sashi             | L   | 0.206      | -            | -                | -                | -         |    -1.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3737 | 2024-03-06 | The Chosen Few    | W   | 0.199      | -            | -                | -                | -         |     1.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3776 | 2024-03-05 | Johnny Speeds     | L   | 0.192      | -            | -                | -                | -         |    -0.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3783 | 2024-03-05 | Betera            | W   | 0.192      | -            | -                | -                | -         |     1.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4319 | 2024-02-09 | Sashi             | L   | 0.024      | -            | -                | -                | -         |    -0.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4328 | 2024-02-08 | ex-Guild Eagles   | W   | 0.019      | -            | -                | -                | -         |     0.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4334 | 2024-02-08 | AMKAL             | L   | 0.018      | -            | -                | -                | -         |    -0.11 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,459.93)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.839 | $7,000.00      | $5,871.25       |
| 2024-05-04 |      0.591 | $2,000.00      | $1,182.78       |
| 2024-03-25 |      0.325 | $1,250.00      | $405.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
