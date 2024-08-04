### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [158](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
<br />
Final Rank Value:  688.0<br />
<br />
Final Rank Value (688.0) = Starting Rank Value (709.3) + Head To Head Adjustments (-21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.238[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.014[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.3
- 400 + ( ( 0.151 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 709.3


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
|           33 |       38 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.19 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      209 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.34 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      333 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.45 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      652 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.64 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1203 | 2024-06-09 | Zero Tenacity     | L   | 0.830      | -            | -                | -                | -         |    -3.15 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1306 | 2024-06-07 | GUN5              | L   | 0.818      | -            | -                | -                | -         |    -4.77 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1395 | 2024-06-06 | Sampi             | L   | 0.810      | -            | -                | -                | -         |    -6.51 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1515 | 2024-06-03 | RUBY              | W   | 0.791      | 0.435        | 0.095 (0.033)    | 0.502 (0.173)    | 0 (0.000) |    19.59 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1526 | 2024-06-02 | UHKA              | W   | 0.785      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     3.87 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1540 | 2024-06-02 | Heimo             | W   | 0.783      | 0.143        | 0.006 (0.001)    | 0.107 (0.012)    | 0 (0.000) |    11.50 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2315 | 2024-05-05 | RUBY              | L   | 0.597      | -            | -                | -                | -         |    -4.22 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2327 | 2024-05-04 | RUSH B            | L   | 0.591      | -            | -                | -                | -         |    -5.58 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2365 | 2024-05-02 | Gaimin Gladiators | L   | 0.578      | -            | -                | -                | -         |    -3.02 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2378 | 2024-05-02 | Zero Tenacity     | L   | 0.576      | -            | -                | -                | -         |    -2.19 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2419 | 2024-04-30 | EYEBALLERS        | W   | 0.564      | 0.384        | 0.006 (0.001)    | 0.510 (0.111)    | 0 (0.000) |    13.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2438 | 2024-04-29 | Insilio           | W   | 0.557      | 0.435        | 0.023 (0.006)    | 0.561 (0.136)    | 0 (0.000) |    13.92 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2528 | 2024-04-25 | EYEBALLERS        | L   | 0.532      | -            | -                | -                | -         |    -4.17 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2540 | 2024-04-25 | kONO              | L   | 0.529      | -            | -                | -                | -         |    -5.86 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2571 | 2024-04-23 | 1WIN              | L   | 0.517      | -            | -                | -                | -         |    -3.75 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2591 | 2024-04-22 | SINNERS           | L   | 0.510      | -            | -                | -                | -         |    -1.67 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2686 | 2024-04-19 | B8                | L   | 0.490      | -            | -                | -                | -         |    -2.04 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2738 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.484      | 0.384        | 0.032 (0.006)    | 0.561 (0.104)    | 0 (0.000) |    12.47 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2763 | 2024-04-17 | PARIVISION        | L   | 0.479      | -            | -                | -                | -         |    -1.70 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2824 | 2024-04-15 | Alliance          | L   | 0.464      | -            | -                | -                | -         |    -4.29 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     2998 | 2024-04-09 | BLEED             | L   | 0.424      | -            | -                | -                | -         |    -2.26 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3025 | 2024-04-08 | Permitta          | L   | 0.417      | -            | -                | -                | -         |    -2.61 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3130 | 2024-04-04 | Passion UA        | L   | 0.391      | -            | -                | -                | -         |    -1.72 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3857 | 2024-03-02 | Sangal            | L   | 0.170      | -            | -                | -                | -         |    -0.41 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3880 | 2024-02-29 | KOI               | L   | 0.158      | -            | -                | -                | -         |    -0.52 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3885 | 2024-02-29 | Aurora            | L   | 0.156      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3892 | 2024-02-28 | Spirit Academy    | L   | 0.151      | -            | -                | -                | -         |    -3.38 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     3980 | 2024-02-24 | ENCE Academy      | L   | 0.126      | -            | -                | -                | -         |    -1.96 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     3986 | 2024-02-24 | Rounds            | W   | 0.125      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.125) |     0.59 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($202.13)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
