### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  953.6<br />
<br />
Final Rank Value (953.6) = Starting Rank Value (893.8) + Head To Head Adjustments (59.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.8
- 400 + ( ( 0.240 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 893.8


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
|           54 |       52 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       91 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      120 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      159 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      204 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.98 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      244 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      309 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      435 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      505 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      570 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    15.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      608 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      648 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |    10.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      768 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      845 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.919 (0.340)    | 0 (0.000) |    15.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      908 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      930 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      949 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1206 | 2024-06-10 | ARCRED            | W   | 0.822      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1253 | 2024-06-09 | RUBY              | W   | 0.815      | 0.372        | 0.095 (0.029)    | 0.480 (0.145)    | 0 (0.000) |    10.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1309 | 2024-06-08 | Zero Tenacity     | W   | 0.809      | 0.372        | 0.143 (0.043)    | 1.000 (0.301)    | 0 (0.000) |    17.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1375 | 2024-06-07 | Aurora Young Blud | W   | 0.802      | 0.372        | -                | 0.521 (0.156)    | -         |    10.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1578 | 2024-06-03 | RUBY              | L   | 0.775      | -            | -                | -                | -         |   -12.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1635 | 2024-06-01 | 1WIN              | W   | 0.761      | 0.372        | 0.033 (0.009)    | 0.680 (0.193)    | -         |    14.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1688 | 2024-05-30 | VP.Prodigy        | W   | 0.749      | 0.372        | 0.025 (0.007)    | -                | -         |    11.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2344 | 2024-05-07 | RUBY              | L   | 0.595      | -            | -                | -                | -         |    -9.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2363 | 2024-05-06 | Zero Tenacity     | L   | 0.588      | -            | -                | -                | -         |    -6.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2367 | 2024-05-06 | BLEED             | L   | 0.587      | -            | -                | -                | -         |    -6.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2412 | 2024-05-03 | Permitta          | W   | 0.568      | 0.435        | -                | 0.919 (0.227)    | -         |     8.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2424 | 2024-05-03 | BetBoom           | L   | 0.566      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2459 | 2024-05-01 | OG                | W   | 0.555      | 0.435        | 0.137 (0.033)    | -                | -         |    11.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2468 | 2024-05-01 | Nexus             | W   | 0.554      | -            | -                | -                | -         |     6.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2510 | 2024-04-29 | HAVU              | L   | 0.540      | -            | -                | -                | -         |   -13.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2546 | 2024-04-27 | ex-Guild Eagles   | W   | 0.528      | -            | -                | -                | -         |     6.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2555 | 2024-04-27 | Permitta          | W   | 0.527      | 0.396        | -                | 0.919 (0.192)    | -         |     9.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2574 | 2024-04-26 | ARCRED            | L   | 0.521      | -            | -                | -                | -         |    -8.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2579 | 2024-04-26 | Enterprise        | W   | 0.520      | 0.396        | 0.039 (0.008)    | 0.641 (0.132)    | -         |     7.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2615 | 2024-04-25 | MOUZ NXT          | W   | 0.512      | 0.435        | 0.139 (0.031)    | 0.962 (0.214)    | -         |    10.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2640 | 2024-04-23 | EYEBALLERS        | W   | 0.502      | -            | -                | -                | -         |     7.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2689 | 2024-04-21 | Permitta          | L   | 0.486      | -            | -                | -                | -         |    -6.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3226 | 2024-04-03 | AMKAL             | L   | 0.369      | -            | -                | -                | -         |    -2.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3267 | 2024-04-02 | ex-Guild Eagles   | W   | 0.362      | -            | -                | -                | -         |     4.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3282 | 2024-04-02 | PARIVISION        | W   | 0.361      | -            | -                | -                | -         |     8.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3509 | 2024-03-18 | Sashi             | L   | 0.261      | -            | -                | -                | -         |    -1.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3568 | 2024-03-15 | CYBERSHOKE        | W   | 0.242      | -            | -                | -                | -         |     1.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3640 | 2024-03-13 | INGLORIOUS        | W   | 0.228      | -            | -                | -                | -         |     0.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3692 | 2024-03-11 | 1WIN              | W   | 0.215      | -            | -                | -                | -         |     3.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3736 | 2024-03-09 | Fraud5            | W   | 0.201      | -            | -                | -                | -         |     1.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3776 | 2024-03-07 | Sashi             | L   | 0.189      | -            | -                | -                | -         |    -1.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3811 | 2024-03-06 | The Chosen Few    | W   | 0.182      | -            | -                | -                | -         |     1.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3850 | 2024-03-05 | Johnny Speeds     | L   | 0.175      | -            | -                | -                | -         |    -0.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3857 | 2024-03-05 | Betera            | W   | 0.175      | -            | -                | -                | -         |     1.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4394 | 2024-02-09 | Sashi             | L   | 0.008      | -            | -                | -                | -         |    -0.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4403 | 2024-02-08 | ex-Guild Eagles   | W   | 0.002      | -            | -                | -                | -         |     0.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4409 | 2024-02-08 | AMKAL             | L   | 0.001      | -            | -                | -                | -         |    -0.01 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,289.10)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.822 | $7,000.00      | $5,754.58       |
| 2024-05-04 |      0.575 | $2,000.00      | $1,149.44       |
| 2024-03-25 |      0.308 | $1,250.00      | $385.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
