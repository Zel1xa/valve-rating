### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
<br />
Final Rank Value:  679.0<br />
<br />
Final Rank Value (679.0) = Starting Rank Value (707.1) + Head To Head Adjustments (-28.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 707.1
- 400 + ( ( 0.150 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 707.1


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
|           34 |       13 | 2024-08-05 | Space             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | Airax, Jelo, ottoNd, puuha, uli  |
|           33 |       97 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.15 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      270 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      395 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.37 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      716 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1265 | 2024-06-09 | Zero Tenacity     | L   | 0.818      | -            | -                | -                | -         |    -3.06 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1368 | 2024-06-07 | GUN5              | L   | 0.806      | -            | -                | -                | -         |    -4.66 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1457 | 2024-06-06 | Sampi             | L   | 0.798      | -            | -                | -                | -         |    -6.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1577 | 2024-06-03 | RUBY              | W   | 0.779      | 0.435        | 0.095 (0.032)    | 0.492 (0.167)    | 0 (0.000) |    19.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1588 | 2024-06-02 | UHKA              | W   | 0.773      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 0 (0.000) |     3.81 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1602 | 2024-06-02 | Heimo             | W   | 0.771      | 0.143        | 0.006 (0.001)    | 0.106 (0.012)    | 0 (0.000) |    11.34 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2377 | 2024-05-05 | RUBY              | L   | 0.585      | -            | -                | -                | -         |    -4.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2389 | 2024-05-04 | RUSH B            | L   | 0.579      | -            | -                | -                | -         |    -5.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2427 | 2024-05-02 | Gaimin Gladiators | L   | 0.566      | -            | -                | -                | -         |    -2.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2440 | 2024-05-02 | Zero Tenacity     | L   | 0.564      | -            | -                | -                | -         |    -2.08 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2481 | 2024-04-30 | EYEBALLERS        | W   | 0.552      | 0.384        | 0.005 (0.001)    | 0.500 (0.106)    | 0 (0.000) |    12.95 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2500 | 2024-04-29 | Insilio           | W   | 0.545      | 0.435        | 0.023 (0.005)    | 0.552 (0.131)    | 0 (0.000) |    13.68 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2591 | 2024-04-25 | EYEBALLERS        | L   | 0.520      | -            | -                | -                | -         |    -4.08 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2603 | 2024-04-25 | kONO              | L   | 0.517      | -            | -                | -                | -         |    -5.73 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2634 | 2024-04-23 | 1WIN              | L   | 0.505      | -            | -                | -                | -         |    -3.14 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2654 | 2024-04-22 | SINNERS           | L   | 0.498      | -            | -                | -                | -         |    -1.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2749 | 2024-04-19 | B8                | L   | 0.478      | -            | -                | -                | -         |    -1.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2801 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.472      | 0.384        | 0.031 (0.006)    | 0.550 (0.100)    | 0 (0.000) |    12.19 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2826 | 2024-04-17 | PARIVISION        | L   | 0.467      | -            | -                | -                | -         |    -1.59 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2887 | 2024-04-15 | Alliance          | L   | 0.452      | -            | -                | -                | -         |    -4.16 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3061 | 2024-04-09 | BLEED             | L   | 0.412      | -            | -                | -                | -         |    -2.21 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3088 | 2024-04-08 | Permitta          | L   | 0.405      | -            | -                | -                | -         |    -2.37 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3193 | 2024-04-04 | Passion UA        | L   | 0.378      | -            | -                | -                | -         |    -1.58 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3921 | 2024-03-02 | Sangal            | L   | 0.158      | -            | -                | -                | -         |    -0.36 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3944 | 2024-02-29 | KOI               | L   | 0.146      | -            | -                | -                | -         |    -0.48 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3949 | 2024-02-29 | Aurora            | L   | 0.144      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3956 | 2024-02-28 | Spirit Academy    | L   | 0.139      | -            | -                | -                | -         |    -3.11 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4044 | 2024-02-24 | ENCE Academy      | L   | 0.114      | -            | -                | -                | -         |    -1.76 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4050 | 2024-02-24 | Rounds            | W   | 0.112      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.112) |     0.54 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($182.72)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
