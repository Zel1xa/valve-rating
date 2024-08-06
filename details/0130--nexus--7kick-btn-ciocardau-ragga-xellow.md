### Roster Details<br />
Team Name: Nexus<br />
Roster: 7kick, BTN, Ciocardau, ragga, XELLOW<br />
Global Rank: [130](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
<br />
Final Rank Value:  786.9<br />
<br />
Final Rank Value (786.9) = Starting Rank Value (837.1) + Head To Head Adjustments (-50.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.354[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 837.1
- 400 + ( ( 0.213 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 837.1


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
|           61 |      207 | 2024-07-31 | EYEBALLERS        | W   | 1.000      | 0.143        | -                | 0.500 (0.071)    | 0 (0.000) |    15.76 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           60 |      269 | 2024-07-29 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -4.66 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           59 |      402 | 2024-07-25 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -14.00 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           58 |      546 | 2024-07-20 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |    -2.99 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           57 |      589 | 2024-07-19 | PERA              | W   | 1.000      | 0.333        | 0.048 (0.016)    | 0.445 (0.148)    | 0 (0.000) |    23.79 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           56 |      632 | 2024-07-18 | TSM               | W   | 1.000      | 0.333        | 0.040 (0.013)    | 0.431 (0.144)    | 0 (0.000) |    26.27 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           55 |      648 | 2024-07-18 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -6.31 | 7kick, BTN, Ciocardau, Ed1m, ragga   |
|           54 |      726 | 2024-07-17 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -11.01 | 7kick, BTN, Ed1m, ragga, XELLOW      |
|           53 |      752 | 2024-07-16 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -0.29 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           52 |      817 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.333        | 0.037 (0.012)    | 0.808 (0.269)    | 0 (0.000) |    25.64 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           51 |      825 | 2024-07-14 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.65 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           50 |      844 | 2024-07-13 | Serbia            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.00 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           49 |      887 | 2024-07-10 | kONO              | L   | 1.000      | -            | -                | -                | -         |   -10.41 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           48 |      918 | 2024-07-09 | Belarus           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.13 | 7kick, BTN, Ciocardau, ragga, XELLOW |
|           47 |     1159 | 2024-06-12 | Permitta          | L   | 0.838      | -            | -                | -                | -         |    -6.50 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           46 |     1182 | 2024-06-11 | FAVBET            | L   | 0.831      | -            | -                | -                | -         |   -10.59 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           45 |     1278 | 2024-06-09 | EYEBALLERS        | L   | 0.816      | -            | -                | -                | -         |    -7.49 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           44 |     1303 | 2024-06-08 | Enterprise        | L   | 0.811      | -            | -                | -                | -         |    -7.96 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           43 |     1378 | 2024-06-07 | Astralis Talent   | W   | 0.804      | -            | -                | -                | 0 (0.000) |    12.84 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           42 |     1390 | 2024-06-07 | 9INE              | L   | 0.803      | -            | -                | -                | -         |    -8.07 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           41 |     1416 | 2024-06-06 | 3DMAX             | L   | 0.799      | -            | -                | -                | -         |    -0.40 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           40 |     1512 | 2024-06-05 | BLEED             | L   | 0.790      | -            | -                | -                | -         |    -0.74 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           39 |     1752 | 2024-05-27 | The Prodigies     | L   | 0.731      | -            | -                | -                | -         |   -18.12 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           38 |     1760 | 2024-05-27 | MOUZ NXT          | L   | 0.729      | -            | -                | -                | -         |    -3.93 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           37 |     1795 | 2024-05-25 | Permitta          | L   | 0.716      | -            | -                | -                | -         |    -7.75 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           36 |     1822 | 2024-05-23 | RUBY              | L   | 0.704      | -            | -                | -                | -         |    -6.55 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           35 |     1937 | 2024-05-20 | ALTERNATE aTTaX   | W   | 0.685      | 0.435        | 0.031 (0.009)    | 0.550 (0.164)    | 0 (0.000) |    14.67 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           34 |     1942 | 2024-05-20 | PERA              | L   | 0.684      | -            | -                | -                | -         |    -6.53 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           33 |     2039 | 2024-05-17 | Passion UA        | L   | 0.663      | -            | -                | -                | -         |    -4.33 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           32 |     2136 | 2024-05-15 | Space             | L   | 0.649      | -            | -                | -                | -         |    -9.11 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           31 |     2205 | 2024-05-13 | Sampi             | L   | 0.636      | -            | -                | -                | -         |    -6.93 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           30 |     2415 | 2024-05-03 | ENCE Academy      | L   | 0.569      | -            | -                | -                | -         |   -11.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     2460 | 2024-05-01 | Insilio           | L   | 0.556      | -            | -                | -                | -         |    -6.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     2492 | 2024-04-30 | fnatic            | L   | 0.549      | -            | -                | -                | -         |    -0.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     2496 | 2024-04-29 | Endpoint          | L   | 0.544      | -            | -                | -                | -         |    -7.11 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     2501 | 2024-04-29 | VP.Prodigy        | L   | 0.543      | -            | -                | -                | -         |    -8.00 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     2506 | 2024-04-29 | LEON              | W   | 0.543      | -            | -                | -                | 0 (0.000) |     5.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     2511 | 2024-04-29 | Enterprise        | W   | 0.542      | 0.384        | 0.039 (0.008)    | 0.616 (0.128)    | 0 (0.000) |     9.89 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     2527 | 2024-04-28 | brazylijski luz   | L   | 0.536      | -            | -                | -                | -         |    -8.61 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     2595 | 2024-04-25 | Metizport         | W   | 0.518      | 0.384        | 0.032 (0.006)    | -                | -         |     9.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     2603 | 2024-04-25 | Grannys Knockers  | L   | 0.516      | -            | -                | -                | -         |   -10.09 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     2624 | 2024-04-24 | AMKAL             | L   | 0.509      | -            | -                | -                | -         |    -2.60 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     2642 | 2024-04-23 | Illuminar         | L   | 0.503      | -            | -                | -                | -         |   -13.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     2655 | 2024-04-22 | Zero Tenacity     | L   | 0.496      | -            | -                | -                | -         |    -3.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     2666 | 2024-04-21 | Young Ninjas      | W   | 0.491      | -            | -                | -                | -         |     5.95 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     2670 | 2024-04-21 | PARIVISION        | L   | 0.490      | -            | -                | -                | -         |    -3.81 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     2706 | 2024-04-20 | Permitta          | W   | 0.483      | 0.500        | -                | 0.901 (0.218)    | -         |    10.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           14 |     2776 | 2024-04-18 | Young Ninjas      | L   | 0.471      | -            | -                | -                | -         |    -9.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     2807 | 2024-04-18 | Enterprise        | L   | 0.469      | -            | -                | -                | -         |    -6.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           12 |     3005 | 2024-04-10 | B8                | W   | 0.417      | 0.384        | 0.164 (0.026)    | 0.934 (0.150)    | -         |     9.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           11 |     3149 | 2024-04-05 | SINNERS           | L   | 0.384      | -            | -                | -                | -         |    -1.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           10 |     3291 | 2024-04-01 | Sashi             | W   | 0.356      | 0.384        | 0.184 (0.025)    | 0.982 (0.134)    | -         |     9.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            9 |     3400 | 2024-03-25 | Sashi             | L   | 0.311      | -            | -                | -                | -         |    -1.57 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            8 |     3661 | 2024-03-12 | Nemiga            | W   | 0.225      | 0.372        | 0.315 (0.026)    | 0.721 (0.060)    | -         |     6.13 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            7 |     3683 | 2024-03-11 | RUBY              | W   | 0.218      | 0.372        | 0.095 (0.008)    | -                | -         |     4.29 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            6 |     3723 | 2024-03-09 | INGLORIOUS        | W   | 0.204      | -            | -                | -                | -         |     1.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            5 |     3747 | 2024-03-08 | FAVBET            | W   | 0.198      | -            | -                | -                | -         |     2.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            4 |     3893 | 2024-03-03 | TSM               | L   | 0.164      | -            | -                | -                | -         |    -3.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            3 |     4141 | 2024-02-20 | ex-Guild Eagles   | L   | 0.083      | -            | -                | -                | -         |    -1.41 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            2 |     4162 | 2024-02-19 | Monte             | L   | 0.078      | -            | -                | -                | -         |    -0.73 | BTN, ERSIN, ragga, s0und, XELLOW     |
|            1 |     4168 | 2024-02-19 | Astralis          | L   | 0.077      | -            | -                | -                | -         |    -0.02 | BTN, ERSIN, ragga, s0und, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,400.75)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-05-02 |      0.564 | $1,000.00      | $564.17         |
| 2024-03-25 |      0.311 | $4,300.00      | $1,336.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
