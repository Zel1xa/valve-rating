### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1088.6<br />
<br />
Final Rank Value (1088.6) = Starting Rank Value (1091.8) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.566[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1091.8
- 400 + ( ( 0.335 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1091.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           91 |       57 | 2024-07-30 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           90 |       92 | 2024-07-29 | Nexus             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           89 |      104 | 2024-07-29 | Into the Breach   | L   | 1.000      | -            | -                | -                | -         |   -28.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           88 |      146 | 2024-07-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -12.25 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           87 |      168 | 2024-07-26 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           86 |      187 | 2024-07-26 | Astralis Talent   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           85 |      208 | 2024-07-25 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -26.56 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           84 |      226 | 2024-07-25 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           83 |      291 | 2024-07-23 | 9INE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           82 |      313 | 2024-07-22 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -4.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           81 |      319 | 2024-07-22 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           80 |      339 | 2024-07-21 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.138 (0.069)    | 1.000 (0.500)    | 0 (0.000) |    17.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           79 |      374 | 2024-07-20 | Ninjas in Pyjamas | W   | 1.000      | 0.500        | 0.256 (0.128)    | 0.477 (0.239)    | 0 (0.000) |    29.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           78 |      387 | 2024-07-20 | RUBY              | W   | 1.000      | 0.435        | 0.096 (0.042)    | -                | 0 (0.000) |     9.02 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           77 |      416 | 2024-07-19 | Nemiga            | W   | 1.000      | 0.500        | 0.322 (0.161)    | 0.698 (0.349)    | -         |    21.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           76 |      473 | 2024-07-18 | Johnny Speeds     | W   | 1.000      | 0.371        | 0.123 (0.045)    | 0.817 (0.303)    | -         |    23.68 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           75 |      484 | 2024-07-18 | CPH Wolves        | L   | 1.000      | -            | -                | -                | -         |   -23.34 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           74 |      540 | 2024-07-17 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | -         |     9.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           73 |      601 | 2024-07-16 | Permitta          | W   | 1.000      | 0.371        | -                | 0.799 (0.296)    | -         |    11.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           72 |      623 | 2024-07-15 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -9.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           71 |      643 | 2024-07-15 | WOPA              | W   | 1.000      | -            | -                | -                | -         |     1.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           70 |      661 | 2024-07-14 | Preasy            | W   | 1.000      | -            | -                | -                | -         |     6.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           69 |      725 | 2024-07-10 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -18.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           68 |      743 | 2024-07-09 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           67 |      745 | 2024-07-09 | Insilio           | W   | 1.000      | -            | -                | -                | -         |    11.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           66 |      765 | 2024-07-08 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -18.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           65 |      939 | 2024-06-14 | 3DMAX             | L   | 0.883      | -            | -                | -                | -         |    -3.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           64 |     1031 | 2024-06-10 | Space             | W   | 0.858      | -            | -                | -                | -         |     7.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           63 |     1143 | 2024-06-08 | Zero Tenacity     | L   | 0.845      | -            | -                | -                | -         |   -11.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           62 |     1205 | 2024-06-07 | Rare Atom         | W   | 0.838      | -            | -                | -                | -         |     2.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           61 |     1218 | 2024-06-07 | Aurora Young Blud | W   | 0.837      | -            | -                | -                | -         |     5.92 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           60 |     1289 | 2024-06-06 | Serbia            | W   | 0.830      | -            | -                | -                | -         |     5.59 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           59 |     1341 | 2024-06-05 | EYEBALLERS        | L   | 0.824      | -            | -                | -                | -         |   -19.50 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           58 |     1371 | 2024-06-04 | Illuminar         | W   | 0.818      | -            | -                | -                | -         |     5.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           57 |     1380 | 2024-06-04 | Serbia            | W   | 0.818      | -            | -                | -                | -         |     5.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           56 |     1429 | 2024-06-02 | UNiTY             | W   | 0.803      | -            | -                | -                | -         |     9.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           55 |     1490 | 2024-05-31 | Zero Tenacity     | L   | 0.791      | -            | -                | -                | -         |   -10.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           54 |     1511 | 2024-05-30 | Zero Tenacity     | W   | 0.785      | 0.371        | 0.138 (0.040)    | 1.000 (0.291)    | -         |    14.40 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           53 |     1540 | 2024-05-29 | Illuminar         | W   | 0.777      | -            | -                | -                | -         |     6.18 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           52 |     1611 | 2024-05-25 | Sampi             | W   | 0.752      | 0.435        | -                | 1.000 (0.327)    | -         |     7.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           51 |     1632 | 2024-05-24 | FURIA             | L   | 0.745      | -            | -                | -                | -         |    -0.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           50 |     1638 | 2024-05-24 | ECSTATIC          | W   | 0.743      | -            | -                | -                | -         |     0.64 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           49 |     1652 | 2024-05-23 | SINNERS           | W   | 0.737      | 0.435        | -                | 0.721 (0.231)    | -         |    11.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           48 |     1776 | 2024-05-20 | Permitta          | W   | 0.717      | 0.435        | -                | 0.799 (0.249)    | -         |     6.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           47 |     1788 | 2024-05-19 | Sashi             | L   | 0.712      | -            | -                | -                | -         |    -5.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           46 |     1799 | 2024-05-19 | ALTERNATE aTTaX   | W   | 0.710      | -            | -                | -                | -         |     8.57 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           45 |     1819 | 2024-05-18 | 9 Pandas          | L   | 0.705      | -            | -                | -                | -         |   -10.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           44 |     1862 | 2024-05-17 | Nexus             | W   | 0.697      | -            | -                | -                | -         |     4.79 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           43 |     1903 | 2024-05-16 | Sashi             | W   | 0.690      | 0.500        | 0.185 (0.064)    | 0.973 (0.336)    | -         |    16.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           42 |     1942 | 2024-05-15 | Endpoint          | L   | 0.685      | -            | -                | -                | -         |   -13.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           41 |     1996 | 2024-05-14 | SINNERS           | L   | 0.679      | -            | -                | -                | -         |   -11.33 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           40 |     2089 | 2024-05-11 | Preasy            | W   | 0.657      | -            | -                | -                | -         |     4.07 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           39 |     2253 | 2024-05-02 | Nemiga            | L   | 0.599      | -            | -                | -                | -         |    -5.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           38 |     2276 | 2024-05-01 | PARIVISION        | W   | 0.592      | -            | -                | -                | -         |    10.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           37 |     2313 | 2024-04-30 | 9 Pandas          | W   | 0.584      | -            | -                | -                | -         |     8.20 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           36 |     2340 | 2024-04-28 | ALTERNATE aTTaX   | L   | 0.572      | -            | -                | -                | -         |   -10.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           35 |     2390 | 2024-04-26 | 9 Pandas          | W   | 0.559      | -            | -                | -                | -         |     8.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           34 |     2391 | 2024-04-26 | 9 Pandas          | W   | 0.559      | -            | -                | -                | -         |     7.72 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           33 |     2427 | 2024-04-25 | Sashi             | L   | 0.551      | -            | -                | -                | -         |    -4.93 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           32 |     2442 | 2024-04-24 | Permitta          | L   | 0.545      | -            | -                | -                | -         |   -10.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           31 |     2471 | 2024-04-22 | B8                | L   | 0.533      | -            | -                | -                | -         |    -7.97 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           30 |     2512 | 2024-04-20 | Young Ninjas      | W   | 0.519      | -            | -                | -                | -         |     3.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           29 |     2534 | 2024-04-20 | Permitta          | L   | 0.517      | -            | -                | -                | -         |   -10.09 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           28 |     2568 | 2024-04-19 | ALTERNATE aTTaX   | L   | 0.512      | -            | -                | -                | -         |   -10.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           27 |     2625 | 2024-04-18 | Permitta          | W   | 0.504      | -            | -                | -                | -         |     5.90 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           26 |     2655 | 2024-04-17 | Sashi             | W   | 0.498      | 0.371        | 0.185 (0.034)    | -                | -         |     9.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           25 |     2689 | 2024-04-16 | 500               | L   | 0.492      | -            | -                | -                | -         |   -12.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           24 |     2728 | 2024-04-14 | SINNERS           | L   | 0.477      | -            | -                | -                | -         |    -6.78 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           23 |     2783 | 2024-04-11 | 3DMAX             | W   | 0.458      | 0.384        | 0.499 (0.088)    | -                | -         |    13.96 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           22 |     2831 | 2024-04-10 | Sashi             | W   | 0.451      | 0.371        | 0.185 (0.031)    | -                | -         |     9.17 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           21 |     3018 | 2024-04-04 | HAVU              | W   | 0.411      | -            | -                | -                | -         |     1.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           20 |     3089 | 2024-04-02 | BLEED             | L   | 0.399      | -            | -                | -                | -         |    -7.08 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           19 |     3118 | 2024-03-31 | FAVBET            | L   | 0.385      | -            | -                | -                | -         |    -9.88 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           18 |     3125 | 2024-03-30 | Lazer Cats        | W   | 0.377      | -            | -                | -                | -         |     0.67 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           17 |     3133 | 2024-03-29 | NAVI Junior       | L   | 0.371      | -            | -                | -                | -         |   -10.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           16 |     3152 | 2024-03-28 | GL Academy        | L   | 0.364      | -            | -                | -                | -         |    -9.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           15 |     3362 | 2024-03-17 | Sampi             | L   | 0.290      | -            | -                | -                | -         |    -6.49 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           14 |     3371 | 2024-03-16 | ex-Preasy         | L   | 0.285      | -            | -                | -                | -         |    -7.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           13 |     3424 | 2024-03-14 | Sampi             | W   | 0.271      | -            | -                | -                | -         |     2.37 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           12 |     3492 | 2024-03-12 | Alliance          | W   | 0.258      | -            | -                | -                | -         |     1.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           11 |     3514 | 2024-03-11 | MOUZ NXT          | L   | 0.251      | -            | -                | -                | -         |    -4.24 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|           10 |     3534 | 2024-03-10 | MOUZ NXT          | W   | 0.245      | -            | -                | -                | -         |     3.63 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            9 |     3549 | 2024-03-09 | The Chosen Few    | L   | 0.239      | -            | -                | -                | -         |    -6.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            8 |     3574 | 2024-03-08 | Spirit Academy    | L   | 0.232      | -            | -                | -                | -         |    -6.95 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            7 |     3579 | 2024-03-08 | Entropiq          | W   | 0.231      | -            | -                | -                | -         |     0.36 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            6 |     3598 | 2024-03-07 | AURA              | W   | 0.226      | -            | -                | -                | -         |     0.26 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            5 |     3634 | 2024-03-06 | Permitta          | L   | 0.218      | -            | -                | -                | -         |    -4.83 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            4 |     3638 | 2024-03-06 | Fraud5            | W   | 0.217      | -            | -                | -                | -         |     0.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            3 |     3663 | 2024-03-05 | B8                | L   | 0.213      | -            | -                | -                | -         |    -3.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            2 |     3692 | 2024-03-04 | ALTERNATE aTTaX   | W   | 0.204      | -            | -                | -                | -         |     2.30 | fear, jackasmo, jambo, s-chilla, zeRRoFIX     |
|            1 |     4225 | 2024-02-08 | BLEED             | L   | 0.037      | -            | -                | -                | -         |    -0.79 | jackasmo, jambo, marat2k, s-chilla, Zinchenko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($56,590.95)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-25 |      1.000 | $11,000.00     | $11,000.00      |
| 2024-07-22 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-06 |      0.830 | $11,000.00     | $9,128.83       |
| 2024-05-03 |      0.605 | $12,500.00     | $7,564.64       |
| 2024-03-31 |      0.385 | $657.00        | $252.78         |
| 2024-03-30 |      0.378 | $1,000.00      | $377.67         |
| 2024-03-18 |      0.297 | $3,000.00      | $890.51         |
| 2024-03-11 |      0.251 | $1,500.00      | $376.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
