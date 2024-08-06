### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.8<br />
<br />
Final Rank Value (678.8) = Starting Rank Value (706.8) + Head To Head Adjustments (-28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.235[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.8
- 400 + ( ( 0.150 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 706.8


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
|           34 |       15 | 2024-08-05 | Space             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | Airax, Jelo, ottoNd, puuha, uli  |
|           33 |       99 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      272 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      397 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.37 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      718 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1267 | 2024-06-09 | Zero Tenacity     | L   | 0.816      | -            | -                | -                | -         |    -3.05 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1370 | 2024-06-07 | GUN5              | L   | 0.804      | -            | -                | -                | -         |    -4.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1459 | 2024-06-06 | Sampi             | L   | 0.796      | -            | -                | -                | -         |    -6.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1579 | 2024-06-03 | RUBY              | W   | 0.777      | 0.435        | 0.095 (0.032)    | 0.491 (0.166)    | 0 (0.000) |    19.19 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1590 | 2024-06-02 | UHKA              | W   | 0.771      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 0 (0.000) |     3.81 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1604 | 2024-06-02 | Heimo             | W   | 0.769      | 0.143        | 0.006 (0.001)    | 0.106 (0.012)    | 0 (0.000) |    11.32 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2379 | 2024-05-05 | RUBY              | L   | 0.583      | -            | -                | -                | -         |    -4.18 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2391 | 2024-05-04 | RUSH B            | L   | 0.577      | -            | -                | -                | -         |    -5.18 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2429 | 2024-05-02 | Gaimin Gladiators | L   | 0.564      | -            | -                | -                | -         |    -2.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2442 | 2024-05-02 | Zero Tenacity     | L   | 0.562      | -            | -                | -                | -         |    -2.07 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2483 | 2024-04-30 | EYEBALLERS        | W   | 0.550      | 0.384        | 0.005 (0.001)    | 0.500 (0.106)    | 0 (0.000) |    12.91 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2502 | 2024-04-29 | Insilio           | W   | 0.543      | 0.435        | 0.023 (0.005)    | 0.552 (0.130)    | 0 (0.000) |    13.63 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2593 | 2024-04-25 | EYEBALLERS        | L   | 0.518      | -            | -                | -                | -         |    -4.07 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2605 | 2024-04-25 | kONO              | L   | 0.516      | -            | -                | -                | -         |    -5.71 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2636 | 2024-04-23 | 1WIN              | L   | 0.504      | -            | -                | -                | -         |    -3.13 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2656 | 2024-04-22 | SINNERS           | L   | 0.496      | -            | -                | -                | -         |    -1.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2751 | 2024-04-19 | B8                | L   | 0.477      | -            | -                | -                | -         |    -1.97 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2803 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.470      | 0.384        | 0.031 (0.006)    | 0.550 (0.099)    | 0 (0.000) |    12.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2828 | 2024-04-17 | PARIVISION        | L   | 0.465      | -            | -                | -                | -         |    -1.58 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2889 | 2024-04-15 | Alliance          | L   | 0.450      | -            | -                | -                | -         |    -4.14 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3063 | 2024-04-09 | BLEED             | L   | 0.410      | -            | -                | -                | -         |    -2.20 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3090 | 2024-04-08 | Permitta          | L   | 0.403      | -            | -                | -                | -         |    -2.36 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3195 | 2024-04-04 | Passion UA        | L   | 0.377      | -            | -                | -                | -         |    -1.57 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3923 | 2024-03-02 | Sangal            | L   | 0.156      | -            | -                | -                | -         |    -0.36 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3946 | 2024-02-29 | KOI               | L   | 0.144      | -            | -                | -                | -         |    -0.48 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3951 | 2024-02-29 | Aurora            | L   | 0.142      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3958 | 2024-02-28 | Spirit Academy    | L   | 0.137      | -            | -                | -                | -         |    -3.06 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4046 | 2024-02-24 | ENCE Academy      | L   | 0.112      | -            | -                | -                | -         |    -1.74 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4052 | 2024-02-24 | Rounds            | W   | 0.111      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.111) |     0.53 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($179.82)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
