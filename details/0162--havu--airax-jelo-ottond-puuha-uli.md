### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.6<br />
<br />
Final Rank Value (678.6) = Starting Rank Value (707.4) + Head To Head Adjustments (-28.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 707.4
- 400 + ( ( 0.150 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 707.4


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
|           34 |        3 | 2024-08-05 | Space             | L   | 1.000      | -            | -                | -                | -         |    -9.30 | Airax, Jelo, ottoNd, puuha, uli  |
|           33 |       88 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.16 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      261 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      386 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.39 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      707 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.64 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1256 | 2024-06-09 | Zero Tenacity     | L   | 0.820      | -            | -                | -                | -         |    -3.07 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1359 | 2024-06-07 | GUN5              | L   | 0.808      | -            | -                | -                | -         |    -4.68 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1448 | 2024-06-06 | Sampi             | L   | 0.799      | -            | -                | -                | -         |    -6.27 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1568 | 2024-06-03 | RUBY              | W   | 0.780      | 0.435        | 0.095 (0.032)    | 0.499 (0.169)    | 0 (0.000) |    19.25 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1579 | 2024-06-02 | UHKA              | W   | 0.774      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     3.82 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1593 | 2024-06-02 | Heimo             | W   | 0.772      | 0.143        | 0.006 (0.001)    | 0.107 (0.012)    | 0 (0.000) |    11.36 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2368 | 2024-05-05 | RUBY              | L   | 0.587      | -            | -                | -                | -         |    -4.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2380 | 2024-05-04 | RUSH B            | L   | 0.581      | -            | -                | -                | -         |    -5.22 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2418 | 2024-05-02 | Gaimin Gladiators | L   | 0.567      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2431 | 2024-05-02 | Zero Tenacity     | L   | 0.566      | -            | -                | -                | -         |    -2.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2472 | 2024-04-30 | EYEBALLERS        | W   | 0.553      | 0.384        | 0.005 (0.001)    | 0.507 (0.108)    | 0 (0.000) |    12.97 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2491 | 2024-04-29 | Insilio           | W   | 0.546      | 0.435        | 0.023 (0.005)    | 0.559 (0.133)    | 0 (0.000) |    13.67 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2582 | 2024-04-25 | EYEBALLERS        | L   | 0.521      | -            | -                | -                | -         |    -4.11 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2594 | 2024-04-25 | kONO              | L   | 0.519      | -            | -                | -                | -         |    -5.76 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2625 | 2024-04-23 | 1WIN              | L   | 0.507      | -            | -                | -                | -         |    -3.16 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2645 | 2024-04-22 | SINNERS           | L   | 0.499      | -            | -                | -                | -         |    -1.28 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2740 | 2024-04-19 | B8                | L   | 0.480      | -            | -                | -                | -         |    -1.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2792 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.473      | 0.384        | 0.031 (0.006)    | 0.557 (0.101)    | 0 (0.000) |    12.22 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2817 | 2024-04-17 | PARIVISION        | L   | 0.468      | -            | -                | -                | -         |    -1.62 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2878 | 2024-04-15 | Alliance          | L   | 0.453      | -            | -                | -                | -         |    -4.18 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3052 | 2024-04-09 | BLEED             | L   | 0.413      | -            | -                | -                | -         |    -2.22 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3079 | 2024-04-08 | Permitta          | L   | 0.407      | -            | -                | -                | -         |    -2.53 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3184 | 2024-04-04 | Passion UA        | L   | 0.380      | -            | -                | -                | -         |    -1.62 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3912 | 2024-03-02 | Sangal            | L   | 0.159      | -            | -                | -                | -         |    -0.37 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3935 | 2024-02-29 | KOI               | L   | 0.147      | -            | -                | -                | -         |    -0.49 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3940 | 2024-02-29 | Aurora            | L   | 0.146      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3947 | 2024-02-28 | Spirit Academy    | L   | 0.140      | -            | -                | -                | -         |    -3.14 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4035 | 2024-02-24 | ENCE Academy      | L   | 0.115      | -            | -                | -                | -         |    -1.79 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4041 | 2024-02-24 | Rounds            | W   | 0.114      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.114) |     0.55 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($185.17)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
