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
Final Rank Value (678.8) = Starting Rank Value (707.2) + Head To Head Adjustments (-28.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 707.2
- 400 + ( ( 0.150 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 707.2


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
|           34 |       12 | 2024-08-05 | Space             | L   | 1.000      | -            | -                | -                | -         |    -9.30 | Airax, Jelo, ottoNd, puuha, uli  |
|           33 |       96 | 2024-08-02 | ENCE Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.15 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      269 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.22 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      394 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.38 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      715 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.64 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1264 | 2024-06-09 | Zero Tenacity     | L   | 0.819      | -            | -                | -                | -         |    -3.06 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1367 | 2024-06-07 | GUN5              | L   | 0.807      | -            | -                | -                | -         |    -4.67 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1456 | 2024-06-06 | Sampi             | L   | 0.798      | -            | -                | -                | -         |    -6.26 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1576 | 2024-06-03 | RUBY              | W   | 0.779      | 0.435        | 0.095 (0.032)    | 0.492 (0.167)    | 0 (0.000) |    19.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1587 | 2024-06-02 | UHKA              | W   | 0.773      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 0 (0.000) |     3.81 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1601 | 2024-06-02 | Heimo             | W   | 0.771      | 0.143        | 0.006 (0.001)    | 0.106 (0.012)    | 0 (0.000) |    11.35 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2376 | 2024-05-05 | RUBY              | L   | 0.586      | -            | -                | -                | -         |    -4.21 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2388 | 2024-05-04 | RUSH B            | L   | 0.579      | -            | -                | -                | -         |    -5.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2426 | 2024-05-02 | Gaimin Gladiators | L   | 0.566      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2439 | 2024-05-02 | Zero Tenacity     | L   | 0.564      | -            | -                | -                | -         |    -2.08 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2480 | 2024-04-30 | EYEBALLERS        | W   | 0.552      | 0.384        | 0.005 (0.001)    | 0.500 (0.106)    | 0 (0.000) |    12.95 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2499 | 2024-04-29 | Insilio           | W   | 0.545      | 0.435        | 0.023 (0.005)    | 0.553 (0.131)    | 0 (0.000) |    13.66 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2590 | 2024-04-25 | EYEBALLERS        | L   | 0.520      | -            | -                | -                | -         |    -4.09 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2602 | 2024-04-25 | kONO              | L   | 0.518      | -            | -                | -                | -         |    -5.74 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2633 | 2024-04-23 | 1WIN              | L   | 0.506      | -            | -                | -                | -         |    -3.15 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2653 | 2024-04-22 | SINNERS           | L   | 0.498      | -            | -                | -                | -         |    -1.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2748 | 2024-04-19 | B8                | L   | 0.479      | -            | -                | -                | -         |    -1.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2800 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.472      | 0.384        | 0.031 (0.006)    | 0.550 (0.100)    | 0 (0.000) |    12.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2825 | 2024-04-17 | PARIVISION        | L   | 0.467      | -            | -                | -                | -         |    -1.59 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2886 | 2024-04-15 | Alliance          | L   | 0.452      | -            | -                | -                | -         |    -4.16 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3060 | 2024-04-09 | BLEED             | L   | 0.412      | -            | -                | -                | -         |    -2.21 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3087 | 2024-04-08 | Permitta          | L   | 0.406      | -            | -                | -                | -         |    -2.52 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3192 | 2024-04-04 | Passion UA        | L   | 0.379      | -            | -                | -                | -         |    -1.59 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3920 | 2024-03-02 | Sangal            | L   | 0.158      | -            | -                | -                | -         |    -0.37 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3943 | 2024-02-29 | KOI               | L   | 0.146      | -            | -                | -                | -         |    -0.48 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3948 | 2024-02-29 | Aurora            | L   | 0.145      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3955 | 2024-02-28 | Spirit Academy    | L   | 0.139      | -            | -                | -                | -         |    -3.12 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4043 | 2024-02-24 | ENCE Academy      | L   | 0.114      | -            | -                | -                | -         |    -1.77 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4049 | 2024-02-24 | Rounds            | W   | 0.113      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.113) |     0.54 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($183.39)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
