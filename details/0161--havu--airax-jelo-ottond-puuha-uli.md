### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  678.3<br />
<br />
Final Rank Value (678.3) = Starting Rank Value (706.2) + Head To Head Adjustments (-28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.235[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.012[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.2
- 400 + ( ( 0.149 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 706.2


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
|           35 |        4 | 2024-08-06 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -0.94 | Airax, Jelo, ottoNd, puuha, uli  |
|           34 |       23 | 2024-08-05 | Space             | L   | 1.000      | -            | -                | -                | -         |    -9.13 | Airax, Jelo, ottoNd, puuha, uli  |
|           33 |      109 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.12 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      282 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -6.96 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      407 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.35 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      728 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1277 | 2024-06-09 | Zero Tenacity     | L   | 0.813      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1380 | 2024-06-07 | GUN5              | L   | 0.801      | -            | -                | -                | -         |    -4.63 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1469 | 2024-06-06 | Sampi             | L   | 0.793      | -            | -                | -                | -         |    -6.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1589 | 2024-06-03 | RUBY              | W   | 0.774      | 0.435        | 0.095 (0.032)    | 0.480 (0.161)    | 0 (0.000) |    19.21 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1600 | 2024-06-02 | UHKA              | W   | 0.768      | 0.143        | 0.000 (0.000)    | 0.029 (0.003)    | 0 (0.000) |     3.79 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1614 | 2024-06-02 | Heimo             | W   | 0.766      | 0.143        | 0.006 (0.001)    | 0.103 (0.011)    | 0 (0.000) |    11.29 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2389 | 2024-05-05 | RUBY              | L   | 0.580      | -            | -                | -                | -         |    -4.07 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2401 | 2024-05-04 | RUSH B            | L   | 0.574      | -            | -                | -                | -         |    -5.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2439 | 2024-05-02 | Gaimin Gladiators | L   | 0.561      | -            | -                | -                | -         |    -2.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2452 | 2024-05-02 | Zero Tenacity     | L   | 0.559      | -            | -                | -                | -         |    -2.05 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2493 | 2024-04-30 | EYEBALLERS        | W   | 0.547      | 0.384        | 0.005 (0.001)    | 0.488 (0.102)    | 0 (0.000) |    12.87 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2512 | 2024-04-29 | Insilio           | W   | 0.540      | 0.435        | 0.023 (0.005)    | 0.539 (0.127)    | 0 (0.000) |    13.56 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2603 | 2024-04-25 | EYEBALLERS        | L   | 0.515      | -            | -                | -                | -         |    -4.01 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2615 | 2024-04-25 | kONO              | L   | 0.512      | -            | -                | -                | -         |    -5.58 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2646 | 2024-04-23 | 1WIN              | L   | 0.500      | -            | -                | -                | -         |    -3.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2666 | 2024-04-22 | SINNERS           | L   | 0.493      | -            | -                | -                | -         |    -1.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2761 | 2024-04-19 | B8                | L   | 0.473      | -            | -                | -                | -         |    -1.93 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2813 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.467      | 0.384        | 0.031 (0.006)    | 0.537 (0.096)    | 0 (0.000) |    12.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2838 | 2024-04-17 | PARIVISION        | L   | 0.462      | -            | -                | -                | -         |    -1.54 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2899 | 2024-04-15 | Alliance          | L   | 0.447      | -            | -                | -                | -         |    -4.11 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3073 | 2024-04-09 | BLEED             | L   | 0.407      | -            | -                | -                | -         |    -2.19 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3100 | 2024-04-08 | Permitta          | L   | 0.400      | -            | -                | -                | -         |    -2.34 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3205 | 2024-04-04 | Passion UA        | L   | 0.374      | -            | -                | -                | -         |    -1.54 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3933 | 2024-03-02 | Sangal            | L   | 0.153      | -            | -                | -                | -         |    -0.35 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3956 | 2024-02-29 | KOI               | L   | 0.141      | -            | -                | -                | -         |    -0.47 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3961 | 2024-02-29 | Aurora            | L   | 0.139      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3968 | 2024-02-28 | Spirit Academy    | L   | 0.134      | -            | -                | -                | -         |    -2.99 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4056 | 2024-02-24 | ENCE Academy      | L   | 0.109      | -            | -                | -                | -         |    -1.69 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4062 | 2024-02-24 | Rounds            | W   | 0.108      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.108) |     0.52 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($174.76)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
