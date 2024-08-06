### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.3<br />
<br />
Final Rank Value (945.3) = Starting Rank Value (893.2) + Head To Head Adjustments (52.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.2
- 400 + ( ( 0.240 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 893.2


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
|           54 |       44 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       83 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |      112 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -14.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |      151 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      196 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      236 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.07 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      301 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      427 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.46 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      497 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      562 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      600 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      640 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |    10.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      760 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |   -10.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      837 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.901 (0.334)    | 0 (0.000) |    15.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      900 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      922 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      941 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1198 | 2024-06-10 | ARCRED            | W   | 0.825      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    11.98 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1245 | 2024-06-09 | RUBY              | W   | 0.818      | 0.372        | 0.095 (0.029)    | 0.491 (0.150)    | 0 (0.000) |    10.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1301 | 2024-06-08 | Zero Tenacity     | W   | 0.812      | 0.372        | 0.143 (0.043)    | 1.000 (0.302)    | 0 (0.000) |    17.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1367 | 2024-06-07 | Aurora Young Blud | W   | 0.805      | 0.372        | -                | 0.532 (0.159)    | -         |    10.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1570 | 2024-06-03 | RUBY              | L   | 0.778      | -            | -                | -                | -         |   -12.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1627 | 2024-06-01 | 1WIN              | W   | 0.764      | 0.372        | 0.033 (0.009)    | 0.696 (0.198)    | -         |    14.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1680 | 2024-05-30 | VP.Prodigy        | W   | 0.751      | 0.372        | 0.025 (0.007)    | -                | -         |    11.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2336 | 2024-05-07 | RUBY              | L   | 0.598      | -            | -                | -                | -         |    -9.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2355 | 2024-05-06 | Zero Tenacity     | L   | 0.591      | -            | -                | -                | -         |    -6.52 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2359 | 2024-05-06 | BLEED             | L   | 0.589      | -            | -                | -                | -         |    -6.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2404 | 2024-05-03 | Permitta          | W   | 0.571      | 0.435        | -                | 0.901 (0.223)    | -         |     8.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2416 | 2024-05-03 | BetBoom           | L   | 0.569      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2451 | 2024-05-01 | OG                | W   | 0.558      | 0.435        | 0.137 (0.033)    | -                | -         |    11.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2460 | 2024-05-01 | Nexus             | W   | 0.556      | -            | -                | -                | -         |     6.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2502 | 2024-04-29 | HAVU              | L   | 0.543      | -            | -                | -                | -         |   -13.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2538 | 2024-04-27 | ex-Guild Eagles   | W   | 0.531      | -            | -                | -                | -         |     6.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2547 | 2024-04-27 | Permitta          | W   | 0.530      | 0.396        | -                | 0.901 (0.189)    | -         |     9.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2566 | 2024-04-26 | ARCRED            | L   | 0.524      | -            | -                | -                | -         |    -8.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2571 | 2024-04-26 | Enterprise        | W   | 0.523      | 0.396        | 0.039 (0.008)    | 0.616 (0.128)    | -         |     7.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2607 | 2024-04-25 | MOUZ NXT          | W   | 0.515      | 0.435        | 0.139 (0.031)    | 0.986 (0.221)    | -         |    10.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2632 | 2024-04-23 | EYEBALLERS        | W   | 0.504      | -            | -                | -                | -         |     7.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2681 | 2024-04-21 | Permitta          | L   | 0.489      | -            | -                | -                | -         |    -6.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3218 | 2024-04-03 | AMKAL             | L   | 0.372      | -            | -                | -                | -         |    -2.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3259 | 2024-04-02 | ex-Guild Eagles   | W   | 0.365      | -            | -                | -                | -         |     4.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3274 | 2024-04-02 | PARIVISION        | W   | 0.363      | -            | -                | -                | -         |     8.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3501 | 2024-03-18 | Sashi             | L   | 0.264      | -            | -                | -                | -         |    -1.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3560 | 2024-03-15 | CYBERSHOKE        | W   | 0.245      | -            | -                | -                | -         |     1.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3632 | 2024-03-13 | INGLORIOUS        | W   | 0.231      | -            | -                | -                | -         |     0.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3684 | 2024-03-11 | 1WIN              | W   | 0.217      | -            | -                | -                | -         |     3.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3728 | 2024-03-09 | Fraud5            | W   | 0.204      | -            | -                | -                | -         |     1.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3768 | 2024-03-07 | Sashi             | L   | 0.192      | -            | -                | -                | -         |    -1.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3803 | 2024-03-06 | The Chosen Few    | W   | 0.185      | -            | -                | -                | -         |     1.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3842 | 2024-03-05 | Johnny Speeds     | L   | 0.178      | -            | -                | -                | -         |    -0.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3849 | 2024-03-05 | Betera            | W   | 0.178      | -            | -                | -                | -         |     1.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4386 | 2024-02-09 | Sashi             | L   | 0.010      | -            | -                | -                | -         |    -0.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4395 | 2024-02-08 | ex-Guild Eagles   | W   | 0.005      | -            | -                | -                | -         |     0.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4401 | 2024-02-08 | AMKAL             | L   | 0.004      | -            | -                | -                | -         |    -0.02 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,317.57)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.825 | $7,000.00      | $5,774.03       |
| 2024-05-04 |      0.578 | $2,000.00      | $1,155.00       |
| 2024-03-25 |      0.311 | $1,250.00      | $388.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
