### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  785.7<br />
<br />
Final Rank Value (785.7) = Starting Rank Value (837.0) + Head To Head Adjustments (-51.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.355[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 837.0
- 400 + ( ( 0.213 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 837.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      195 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.507 (0.072)    | 0 (0.000) |    15.71 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      258 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.64 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      391 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -13.97 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      535 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.97 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      578 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.451 (0.150)    | 0 (0.000) |    23.84 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      621 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.435 (0.145)    | 0 (0.000) |    26.27 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      637 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.26 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      715 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.00 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      741 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.28 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      806 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.794 (0.265)    | 0 (0.000) |    25.60 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      814 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.61 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      833 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.04 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      876 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.36 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      907 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.16 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1148 | 2024-06-12 | Permitta          | L   | 0.841      | -            | -                | -                | -         |    -6.63 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1171 | 2024-06-11 | FAVBET            | L   | 0.834      | -            | -                | -                | -         |   -10.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1267 | 2024-06-09 | EYEBALLERS        | L   | 0.819      | -            | -                | -                | -         |    -7.52 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1292 | 2024-06-08 | Enterprise        | L   | 0.815      | -            | -                | -                | -         |    -8.08 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1367 | 2024-06-07 | Astralis Talent   | W   | 0.807      | -            | -                | -                | 0 (0.000) |    13.00 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1379 | 2024-06-07 | 9INE              | L   | 0.806      | -            | -                | -                | -         |    -8.09 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1405 | 2024-06-06 | 3DMAX             | L   | 0.802      | -            | -                | -                | -         |    -0.41 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1501 | 2024-06-05 | BLEED             | L   | 0.793      | -            | -                | -                | -         |    -0.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1741 | 2024-05-27 | The Prodigies     | L   | 0.735      | -            | -                | -                | -         |   -18.17 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1749 | 2024-05-27 | MOUZ NXT          | L   | 0.732      | -            | -                | -                | -         |    -3.93 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1784 | 2024-05-25 | Permitta          | L   | 0.720      | -            | -                | -                | -         |    -7.98 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1811 | 2024-05-23 | RUBY              | L   | 0.707      | -            | -                | -                | -         |    -6.59 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1926 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.688      | 0.435        | 0.031 (0.009)    | 0.557 (0.167)    | 0 (0.000) |    14.73 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1931 | 2024-05-20 | PERA              | L   | 0.687      | -            | -                | -                | -         |    -6.52 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2028 | 2024-05-17 | Passion UA        | L   | 0.666      | -            | -                | -                | -         |    -4.39 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2125 | 2024-05-15 | Space             | L   | 0.652      | -            | -                | -                | -         |    -9.13 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2194 | 2024-05-13 | Sampi             | L   | 0.639      | -            | -                | -                | -         |    -6.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2404 | 2024-05-03 | ENCE Academy      | L   | 0.572      | -            | -                | -                | -         |   -11.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2449 | 2024-05-01 | Insilio           | L   | 0.560      | -            | -                | -                | -         |    -6.49 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2481 | 2024-04-30 | fnatic            | L   | 0.552      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2485 | 2024-04-29 | Endpoint          | L   | 0.548      | -            | -                | -                | -         |    -7.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2490 | 2024-04-29 | VP.Prodigy        | L   | 0.547      | -            | -                | -                | -         |    -8.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2495 | 2024-04-29 | LEON              | W   | 0.546      | -            | -                | -                | 0 (0.000) |     5.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2500 | 2024-04-29 | Enterprise        | W   | 0.545      | 0.384        | 0.039 (0.008)    | 0.624 (0.131)    | 0 (0.000) |     9.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2516 | 2024-04-28 | brazylijski luz   | L   | 0.539      | -            | -                | -                | -         |    -8.64 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2584 | 2024-04-25 | Metizport         | W   | 0.521      | 0.384        | 0.033 (0.007)    | -                | -         |     9.51 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2592 | 2024-04-25 | Grannys Knockers  | L   | 0.520      | -            | -                | -                | -         |   -10.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2613 | 2024-04-24 | AMKAL             | L   | 0.512      | -            | -                | -                | -         |    -2.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2631 | 2024-04-23 | Illuminar         | L   | 0.506      | -            | -                | -                | -         |   -13.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2644 | 2024-04-22 | Zero Tenacity     | L   | 0.500      | -            | -                | -                | -         |    -3.62 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2655 | 2024-04-21 | Young Ninjas      | W   | 0.495      | -            | -                | -                | -         |     5.90 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2659 | 2024-04-21 | PARIVISION        | L   | 0.494      | -            | -                | -                | -         |    -3.88 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2695 | 2024-04-20 | Permitta          | W   | 0.486      | 0.500        | -                | 0.873 (0.212)    | -         |    10.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2765 | 2024-04-18 | Young Ninjas      | L   | 0.475      | -            | -                | -                | -         |    -9.34 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2796 | 2024-04-18 | Enterprise        | L   | 0.472      | -            | -                | -                | -         |    -6.22 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     2994 | 2024-04-10 | B8                | W   | 0.420      | 0.384        | 0.165 (0.027)    | 0.947 (0.153)    | -         |    10.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3138 | 2024-04-05 | SINNERS           | L   | 0.387      | -            | -                | -                | -         |    -2.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3280 | 2024-04-01 | Sashi             | W   | 0.359      | 0.384        | 0.184 (0.025)    | 0.996 (0.137)    | -         |     9.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3389 | 2024-03-25 | Sashi             | L   | 0.314      | -            | -                | -                | -         |    -1.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3650 | 2024-03-12 | Nemiga            | W   | 0.228      | 0.372        | 0.316 (0.027)    | 0.731 (0.062)    | -         |     6.22 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3672 | 2024-03-11 | RUBY              | W   | 0.221      | 0.372        | 0.095 (0.008)    | -                | -         |     4.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3712 | 2024-03-09 | INGLORIOUS        | W   | 0.208      | -            | -                | -                | -         |     1.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3736 | 2024-03-08 | FAVBET            | W   | 0.201      | -            | -                | -                | -         |     2.53 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3882 | 2024-03-03 | TSM               | L   | 0.168      | -            | -                | -                | -         |    -3.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4130 | 2024-02-20 | ex-Guild Eagles   | L   | 0.087      | -            | -                | -                | -         |    -1.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4151 | 2024-02-19 | Monte             | L   | 0.081      | -            | -                | -                | -         |    -0.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4157 | 2024-02-19 | Astralis          | L   | 0.080      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,418.42)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.568 | $1,000.00      | $567.50         |
| 2024-03-25 |      0.314 | $4,300.00      | $1,350.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
