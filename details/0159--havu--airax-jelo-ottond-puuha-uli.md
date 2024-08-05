### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [159](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  688.1<br />
<br />
Final Rank Value (688.1) = Starting Rank Value (708.0) + Head To Head Adjustments (-19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.0
- 400 + ( ( 0.151 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 708.0


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
|           33 |       75 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.18 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      248 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.27 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      373 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.40 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      694 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.64 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1243 | 2024-06-09 | Zero Tenacity     | L   | 0.823      | -            | -                | -                | -         |    -3.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1346 | 2024-06-07 | GUN5              | L   | 0.811      | -            | -                | -                | -         |    -4.70 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1435 | 2024-06-06 | Sampi             | L   | 0.803      | -            | -                | -                | -         |    -6.40 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1555 | 2024-06-03 | RUBY              | W   | 0.784      | 0.435        | 0.095 (0.032)    | 0.501 (0.171)    | 0 (0.000) |    19.32 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1566 | 2024-06-02 | UHKA              | W   | 0.778      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     3.83 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1580 | 2024-06-02 | Heimo             | W   | 0.776      | 0.143        | 0.006 (0.001)    | 0.107 (0.012)    | 0 (0.000) |    11.39 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2355 | 2024-05-05 | RUBY              | L   | 0.590      | -            | -                | -                | -         |    -4.26 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2367 | 2024-05-04 | RUSH B            | L   | 0.584      | -            | -                | -                | -         |    -5.26 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2405 | 2024-05-02 | Gaimin Gladiators | L   | 0.571      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2418 | 2024-05-02 | Zero Tenacity     | L   | 0.569      | -            | -                | -                | -         |    -2.12 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2459 | 2024-04-30 | EYEBALLERS        | W   | 0.556      | 0.384        | 0.005 (0.001)    | 0.509 (0.109)    | 0 (0.000) |    13.04 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2478 | 2024-04-29 | Insilio           | W   | 0.550      | 0.435        | 0.023 (0.005)    | 0.561 (0.134)    | 0 (0.000) |    13.75 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2569 | 2024-04-25 | EYEBALLERS        | L   | 0.525      | -            | -                | -                | -         |    -4.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2581 | 2024-04-25 | kONO              | L   | 0.522      | -            | -                | -                | -         |    -5.79 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2612 | 2024-04-23 | 1WIN              | L   | 0.510      | -            | -                | -                | -         |    -3.29 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2632 | 2024-04-22 | SINNERS           | L   | 0.503      | -            | -                | -                | -         |    -1.29 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2727 | 2024-04-19 | B8                | L   | 0.483      | -            | -                | -                | -         |    -2.01 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2779 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.476      | 0.384        | 0.031 (0.006)    | 0.560 (0.102)    | 0 (0.000) |    12.30 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2804 | 2024-04-17 | PARIVISION        | L   | 0.471      | -            | -                | -                | -         |    -1.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2865 | 2024-04-15 | Alliance          | L   | 0.457      | -            | -                | -                | -         |    -4.21 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3039 | 2024-04-09 | BLEED             | L   | 0.416      | -            | -                | -                | -         |    -2.23 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3066 | 2024-04-08 | Permitta          | L   | 0.410      | -            | -                | -                | -         |    -2.56 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3171 | 2024-04-04 | Passion UA        | L   | 0.383      | -            | -                | -                | -         |    -1.65 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3899 | 2024-03-02 | Sangal            | L   | 0.163      | -            | -                | -                | -         |    -0.38 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3922 | 2024-02-29 | KOI               | L   | 0.150      | -            | -                | -                | -         |    -0.50 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3927 | 2024-02-29 | Aurora            | L   | 0.149      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3934 | 2024-02-28 | Spirit Academy    | L   | 0.144      | -            | -                | -                | -         |    -3.22 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4022 | 2024-02-24 | ENCE Academy      | L   | 0.119      | -            | -                | -                | -         |    -1.84 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4028 | 2024-02-24 | Rounds            | W   | 0.117      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.117) |     0.56 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($190.53)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
