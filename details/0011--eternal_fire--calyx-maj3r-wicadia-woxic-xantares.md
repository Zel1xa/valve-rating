### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.3<br />
<br />
Final Rank Value (1621.3) = Starting Rank Value (1695.8) + Head To Head Adjustments (-74.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.884[<sup>1</sup>](#table2)
- Bounty Collected: 0.559[<sup>2</sup>](#table1)
- Opponent Network: 0.306[<sup>2</sup>](#table1)
- LAN Wins: 0.771[<sup>2</sup>](#table1)

The average of these factors is 0.630<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.8
- 400 + ( ( 0.630 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1695.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      333 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      369 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.510 (0.332)    | 1.000 (0.650)    | 1 (1.000) |     6.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      414 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.452 (0.294)    | 1 (1.000) |     2.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      445 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.428 (0.278)    | 1 (1.000) |     0.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      454 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.259 (0.168)    | 1 (1.000) |     0.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1455 | 2024-06-06 | BetBoom           | L   | 0.794      | -            | -                | -                | -         |   -19.50 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1476 | 2024-06-06 | BIG               | W   | 0.792      | 0.715        | 0.154 (0.087)    | -                | 1 (0.792) |     3.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1485 | 2024-06-06 | FURIA             | L   | 0.792      | -            | -                | -                | -         |   -15.15 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1508 | 2024-06-05 | fnatic            | L   | 0.787      | -            | -                | -                | -         |   -19.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1535 | 2024-06-05 | Complexity        | L   | 0.785      | -            | -                | -                | -         |   -13.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1841 | 2024-05-23 | Liquid            | W   | 0.700      | 0.769        | 0.383 (0.206)    | 0.437 (0.235)    | -         |     8.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1882 | 2024-05-22 | GamerLegion       | W   | 0.693      | 0.769        | 0.173 (0.092)    | -                | -         |     1.26 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1922 | 2024-05-21 | BetBoom           | W   | 0.687      | 0.769        | 0.248 (0.131)    | 0.513 (0.271)    | -         |     3.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2079 | 2024-05-16 | SAW               | W   | 0.654      | 0.769        | -                | 0.516 (0.260)    | -         |     1.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2088 | 2024-05-16 | PARIVISION        | W   | 0.653      | 0.769        | -                | 0.590 (0.296)    | -         |     0.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2552 | 2024-04-27 | SAW               | L   | 0.528      | -            | -                | -                | -         |   -15.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2581 | 2024-04-26 | FaZe              | L   | 0.520      | -            | -                | -                | -         |    -7.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2608 | 2024-04-25 | fnatic            | W   | 0.514      | 0.889        | 0.371 (0.169)    | 0.680 (0.311)    | 1 (0.514) |     4.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2628 | 2024-04-24 | Imperial          | W   | 0.508      | 0.889        | 0.233 (0.105)    | 0.658 (0.297)    | 1 (0.508) |     1.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2649 | 2024-04-23 | Astralis          | L   | 0.500      | -            | -                | -                | -         |    -7.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2710 | 2024-04-20 | Sashi             | L   | 0.481      | -            | -                | -                | -         |   -14.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2756 | 2024-04-19 | Sashi             | W   | 0.474      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2766 | 2024-04-19 | BetBoom           | W   | 0.473      | -            | -                | -                | -         |     2.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3324 | 2024-03-29 | Natus Vincere     | L   | 0.334      | -            | -                | -                | -         |    -2.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3432 | 2024-03-23 | Virtus.pro        | W   | 0.293      | 1.000        | 0.498 (0.146)    | -                | 1 (0.293) |     4.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3447 | 2024-03-22 | FaZe              | W   | 0.286      | 1.000        | 0.625 (0.179)    | -                | 1 (0.286) |     4.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3464 | 2024-03-21 | MOUZ              | L   | 0.281      | -            | -                | -                | -         |    -2.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3472 | 2024-03-21 | Vitality          | W   | 0.280      | 1.000        | 0.647 (0.181)    | -                | 1 (0.280) |     6.16 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3511 | 2024-03-19 | GamerLegion       | W   | 0.266      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3519 | 2024-03-18 | HEROIC            | L   | 0.260      | -            | -                | -                | -         |    -5.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3541 | 2024-03-17 | paiN              | W   | 0.254      | -            | -                | -                | -         |     1.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3553 | 2024-03-17 | The MongolZ       | W   | 0.253      | -            | -                | -                | -         |     6.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4227 | 2024-02-17 | BetBoom           | W   | 0.061      | -            | -                | -                | -         |     0.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4261 | 2024-02-16 | FaZe              | L   | 0.053      | -            | -                | -                | -         |    -0.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4291 | 2024-02-15 | Falcons           | W   | 0.046      | -            | -                | -                | -         |     0.25 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4317 | 2024-02-14 | G2                | L   | 0.041      | -            | -                | -                | -         |    -0.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4328 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.040      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($236,484.07)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.814 | $8,000.00      | $6,508.15       |
| 2024-05-23 |      0.700 | $250,000.00    | $174,942.13     |
| 2024-05-12 |      0.627 | $7,000.00      | $4,387.96       |
| 2024-03-31 |      0.348 | $45,000.00     | $15,645.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
