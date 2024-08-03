### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  702.8<br />
<br />
Final Rank Value (702.8) = Starting Rank Value (710.9) + Head To Head Adjustments (-8.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.238[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.014[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.9
- 400 + ( ( 0.152 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 710.9


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
|           32 |      186 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.84 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      310 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -3.44 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      628 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.65 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1148 | 2024-06-09 | Zero Tenacity     | L   | 0.832      | -            | -                | -                | -         |    -3.28 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1246 | 2024-06-07 | GUN5              | L   | 0.820      | -            | -                | -                | -         |    -4.74 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1335 | 2024-06-06 | Sampi             | L   | 0.812      | -            | -                | -                | -         |    -6.50 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1454 | 2024-06-03 | RUBY              | W   | 0.793      | 0.435        | 0.095 (0.033)    | 0.520 (0.179)    | 0 (0.000) |    19.64 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1464 | 2024-06-02 | UHKA              | W   | 0.787      | 0.143        | 0.000 (0.000)    | 0.032 (0.004)    | 0 (0.000) |     3.86 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1478 | 2024-06-02 | Heimo             | W   | 0.785      | 0.143        | 0.006 (0.001)    | 0.089 (0.010)    | 0 (0.000) |    11.55 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2249 | 2024-05-05 | RUBY              | L   | 0.599      | -            | -                | -                | -         |    -4.20 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2261 | 2024-05-04 | RUSH B            | L   | 0.593      | -            | -                | -                | -         |    -5.60 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2299 | 2024-05-02 | Gaimin Gladiators | L   | 0.580      | -            | -                | -                | -         |    -3.01 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2312 | 2024-05-02 | Zero Tenacity     | L   | 0.578      | -            | -                | -                | -         |    -2.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2353 | 2024-04-30 | EYEBALLERS        | W   | 0.565      | 0.384        | 0.006 (0.001)    | 0.528 (0.115)    | 0 (0.000) |    13.25 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2372 | 2024-04-29 | Insilio           | W   | 0.559      | 0.435        | 0.023 (0.006)    | 0.581 (0.141)    | 0 (0.000) |    13.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2462 | 2024-04-25 | EYEBALLERS        | L   | 0.534      | -            | -                | -                | -         |    -4.21 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2474 | 2024-04-25 | kONO              | L   | 0.531      | -            | -                | -                | -         |    -5.90 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2505 | 2024-04-23 | 1WIN              | L   | 0.519      | -            | -                | -                | -         |    -3.73 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2525 | 2024-04-22 | SINNERS           | L   | 0.512      | -            | -                | -                | -         |    -1.66 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2620 | 2024-04-19 | B8                | L   | 0.492      | -            | -                | -                | -         |    -2.05 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2672 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.485      | 0.384        | 0.032 (0.006)    | 0.580 (0.108)    | 0 (0.000) |    12.51 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2697 | 2024-04-17 | PARIVISION        | L   | 0.480      | -            | -                | -                | -         |    -1.69 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2758 | 2024-04-15 | Alliance          | L   | 0.466      | -            | -                | -                | -         |    -4.29 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     2932 | 2024-04-09 | BLEED             | L   | 0.425      | -            | -                | -                | -         |    -2.26 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     2959 | 2024-04-08 | Permitta          | L   | 0.419      | -            | -                | -                | -         |    -2.63 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3064 | 2024-04-04 | Passion UA        | L   | 0.392      | -            | -                | -                | -         |    -1.73 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3784 | 2024-03-02 | Sangal            | L   | 0.171      | -            | -                | -                | -         |    -0.41 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3807 | 2024-02-29 | KOI               | L   | 0.159      | -            | -                | -                | -         |    -1.10 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3812 | 2024-02-29 | Aurora            | L   | 0.158      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3819 | 2024-02-28 | Spirit Academy    | L   | 0.153      | -            | -                | -                | -         |    -3.42 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     3907 | 2024-02-24 | ENCE Academy      | L   | 0.128      | -            | -                | -                | -         |    -1.93 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     3913 | 2024-02-24 | Rounds            | W   | 0.126      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.126) |     0.59 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($204.88)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
