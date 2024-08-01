### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  955.4<br />
<br />
Final Rank Value (955.4) = Starting Rank Value (895.5) + Head To Head Adjustments (59.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.241<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.5
- 400 + ( ( 0.241 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 895.5


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
|           51 |        0 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |       45 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |       87 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.89 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      153 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      279 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -9.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      350 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -14.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      417 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    14.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      457 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -15.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      499 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.256)    | 0 (0.000) |    10.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      621 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -15.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      706 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.801 (0.297)    | 0 (0.000) |    15.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      769 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      791 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -12.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      810 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1058 | 2024-06-10 | ARCRED            | W   | 0.855      | 0.372        | 0.039 (0.012)    | -                | 0 (0.000) |    10.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1105 | 2024-06-09 | RUBY              | W   | 0.848      | 0.372        | 0.097 (0.030)    | 0.544 (0.172)    | 0 (0.000) |    11.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1163 | 2024-06-08 | Zero Tenacity     | W   | 0.842      | 0.372        | 0.139 (0.043)    | 1.000 (0.313)    | 0 (0.000) |    16.62 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1236 | 2024-06-07 | Aurora Young Blud | W   | 0.835      | 0.372        | -                | 0.449 (0.139)    | 0 (0.000) |     9.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1444 | 2024-06-03 | RUBY              | L   | 0.808      | -            | -                | -                | -         |   -12.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1502 | 2024-06-01 | 1WIN              | W   | 0.794      | 0.372        | 0.027 (0.008)    | 0.630 (0.186)    | -         |    14.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1555 | 2024-05-30 | VP.Prodigy        | W   | 0.782      | 0.372        | 0.026 (0.008)    | -                | -         |    12.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2250 | 2024-05-07 | RUBY              | L   | 0.628      | -            | -                | -                | -         |    -9.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2269 | 2024-05-06 | Zero Tenacity     | L   | 0.621      | -            | -                | -                | -         |    -7.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2273 | 2024-05-06 | BLEED             | L   | 0.620      | -            | -                | -                | -         |    -6.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2318 | 2024-05-03 | Permitta          | W   | 0.601      | 0.435        | -                | 0.801 (0.209)    | -         |     8.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2330 | 2024-05-03 | BetBoom           | L   | 0.599      | -            | -                | -                | -         |    -1.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2367 | 2024-05-01 | OG                | W   | 0.588      | 0.435        | 0.143 (0.037)    | -                | -         |    12.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2376 | 2024-05-01 | Nexus             | W   | 0.587      | -            | -                | -                | -         |     6.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2419 | 2024-04-29 | HAVU              | L   | 0.573      | -            | -                | -                | -         |   -14.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2455 | 2024-04-27 | ex-Guild Eagles   | W   | 0.561      | -            | -                | -                | -         |     7.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2465 | 2024-04-27 | Permitta          | W   | 0.560      | 0.396        | -                | 0.801 (0.178)    | -         |     9.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2484 | 2024-04-26 | ARCRED            | L   | 0.554      | -            | -                | -                | -         |   -10.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2488 | 2024-04-26 | Enterprise        | W   | 0.554      | 0.396        | 0.040 (0.009)    | 0.622 (0.137)    | -         |     8.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2524 | 2024-04-25 | MOUZ NXT          | W   | 0.546      | 0.435        | 0.141 (0.033)    | 1.000 (0.237)    | -         |    11.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2550 | 2024-04-23 | EYEBALLERS        | W   | 0.535      | -            | -                | -                | -         |     7.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2602 | 2024-04-21 | Permitta          | L   | 0.519      | -            | -                | -                | -         |    -7.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3148 | 2024-04-03 | AMKAL             | L   | 0.402      | -            | -                | -                | -         |    -2.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3195 | 2024-04-02 | ex-Guild Eagles   | W   | 0.395      | -            | -                | -                | -         |     4.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3210 | 2024-04-02 | PARIVISION        | W   | 0.394      | -            | -                | -                | -         |     9.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3442 | 2024-03-18 | Sashi             | L   | 0.294      | -            | -                | -                | -         |    -2.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3501 | 2024-03-15 | CYBERSHOKE        | W   | 0.275      | -            | -                | -                | -         |     1.93 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3577 | 2024-03-13 | INGLORIOUS        | W   | 0.261      | -            | -                | -                | -         |     0.97 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3630 | 2024-03-11 | 1WIN              | W   | 0.248      | -            | -                | -                | -         |     3.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3675 | 2024-03-09 | Fraud5            | W   | 0.234      | -            | -                | -                | -         |     1.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3715 | 2024-03-07 | Sashi             | L   | 0.222      | -            | -                | -                | -         |    -1.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3750 | 2024-03-06 | The Chosen Few    | W   | 0.215      | -            | -                | -                | -         |     1.53 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3793 | 2024-03-05 | Johnny Speeds     | L   | 0.208      | -            | -                | -                | -         |    -0.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3801 | 2024-03-05 | Betera            | W   | 0.208      | -            | -                | -                | -         |     1.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4358 | 2024-02-09 | Sashi             | L   | 0.041      | -            | -                | -                | -         |    -0.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4367 | 2024-02-08 | ex-Guild Eagles   | W   | 0.035      | -            | -                | -                | -         |     0.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4373 | 2024-02-08 | AMKAL             | L   | 0.034      | -            | -                | -                | -         |    -0.20 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,627.92)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.855 | $7,000.00      | $5,985.97       |
| 2024-05-04 |      0.608 | $2,000.00      | $1,215.56       |
| 2024-03-25 |      0.341 | $1,250.00      | $426.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
