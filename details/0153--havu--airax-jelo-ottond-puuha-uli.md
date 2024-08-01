### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.7<br />
<br />
Final Rank Value (706.7) = Starting Rank Value (716.4) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.241[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.016[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.4
- 400 + ( ( 0.154 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 716.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      124 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.53 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      248 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -4.51 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      577 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.52 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |     1127 | 2024-06-09 | Zero Tenacity     | L   | 0.847      | -            | -                | -                | -         |    -4.41 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1239 | 2024-06-07 | GUN5              | L   | 0.835      | -            | -                | -                | -         |    -4.50 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1331 | 2024-06-06 | Sampi             | L   | 0.826      | -            | -                | -                | -         |    -6.93 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1453 | 2024-06-03 | RUBY              | W   | 0.807      | 0.435        | 0.097 (0.034)    | 0.544 (0.191)    | 0 (0.000) |    20.04 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1465 | 2024-06-02 | UHKA              | W   | 0.801      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     3.83 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1479 | 2024-06-02 | Heimo             | W   | 0.799      | 0.143        | 0.006 (0.001)    | 0.086 (0.010)    | 0 (0.000) |    11.69 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     2293 | 2024-05-05 | RUBY              | L   | 0.614      | -            | -                | -                | -         |    -4.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2305 | 2024-05-04 | RUSH B            | L   | 0.608      | -            | -                | -                | -         |    -5.89 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2344 | 2024-05-02 | Gaimin Gladiators | L   | 0.594      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2357 | 2024-05-02 | Zero Tenacity     | L   | 0.593      | -            | -                | -                | -         |    -2.37 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2400 | 2024-04-30 | EYEBALLERS        | W   | 0.580      | 0.384        | 0.006 (0.001)    | 0.513 (0.114)    | 0 (0.000) |    13.57 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2419 | 2024-04-29 | Insilio           | W   | 0.573      | 0.435        | 0.023 (0.006)    | 0.554 (0.138)    | 0 (0.000) |    14.33 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2510 | 2024-04-25 | EYEBALLERS        | L   | 0.548      | -            | -                | -                | -         |    -4.34 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2522 | 2024-04-25 | kONO              | L   | 0.546      | -            | -                | -                | -         |    -5.76 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2555 | 2024-04-23 | 1WIN              | L   | 0.534      | -            | -                | -                | -         |    -3.90 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2576 | 2024-04-22 | SINNERS           | L   | 0.526      | -            | -                | -                | -         |    -2.02 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2675 | 2024-04-19 | B8                | L   | 0.507      | -            | -                | -                | -         |    -2.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2728 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.500      | 0.384        | 0.032 (0.006)    | 0.564 (0.108)    | 0 (0.000) |    12.83 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2754 | 2024-04-17 | PARIVISION        | L   | 0.495      | -            | -                | -                | -         |    -1.83 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2816 | 2024-04-15 | Alliance          | L   | 0.480      | -            | -                | -                | -         |    -4.48 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2991 | 2024-04-09 | BLEED             | L   | 0.440      | -            | -                | -                | -         |    -2.33 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3018 | 2024-04-08 | Permitta          | L   | 0.434      | -            | -                | -                | -         |    -2.88 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3124 | 2024-04-04 | Passion UA        | L   | 0.407      | -            | -                | -                | -         |    -1.78 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3875 | 2024-03-02 | Sangal            | L   | 0.186      | -            | -                | -                | -         |    -0.48 | Airax, Banjo, ottoNd, puuha, uli |
|            6 |     3899 | 2024-02-29 | KOI               | L   | 0.174      | -            | -                | -                | -         |    -1.20 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3904 | 2024-02-29 | Aurora            | L   | 0.173      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3910 | 2024-02-28 | Croatia           | W   | 0.168      | 0.143        | 0.000 (0.000)    | 0.051 (0.001)    | 0 (0.000) |     1.22 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3912 | 2024-02-28 | Spirit Academy    | L   | 0.167      | -            | -                | -                | -         |    -3.76 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4002 | 2024-02-24 | ENCE Academy      | L   | 0.142      | -            | -                | -                | -         |    -2.14 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4008 | 2024-02-24 | Rounds            | W   | 0.141      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.141) |     0.65 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($228.45)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
