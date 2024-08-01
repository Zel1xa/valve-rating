### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.0<br />
<br />
Final Rank Value (706.0) = Starting Rank Value (715.7) + Head To Head Adjustments (-9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.016[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.7
- 400 + ( ( 0.153 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 715.7


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
|           33 |      130 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Airax, Jelo, ottoNd, puuha, uli  |
|           32 |      254 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -4.52 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      583 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.52 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |     1133 | 2024-06-09 | Zero Tenacity     | L   | 0.845      | -            | -                | -                | -         |    -4.39 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1245 | 2024-06-07 | GUN5              | L   | 0.833      | -            | -                | -                | -         |    -4.50 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1337 | 2024-06-06 | Sampi             | L   | 0.825      | -            | -                | -                | -         |    -6.93 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1459 | 2024-06-03 | RUBY              | W   | 0.806      | 0.435        | 0.097 (0.034)    | 0.544 (0.190)    | 0 (0.000) |    19.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1471 | 2024-06-02 | UHKA              | W   | 0.800      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     3.84 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1485 | 2024-06-02 | Heimo             | W   | 0.798      | 0.143        | 0.006 (0.001)    | 0.086 (0.010)    | 0 (0.000) |    11.67 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     2299 | 2024-05-05 | RUBY              | L   | 0.612      | -            | -                | -                | -         |    -4.23 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2311 | 2024-05-04 | RUSH B            | L   | 0.606      | -            | -                | -                | -         |    -5.87 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2350 | 2024-05-02 | Gaimin Gladiators | L   | 0.593      | -            | -                | -                | -         |    -3.00 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2363 | 2024-05-02 | Zero Tenacity     | L   | 0.591      | -            | -                | -                | -         |    -2.36 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2406 | 2024-04-30 | EYEBALLERS        | W   | 0.578      | 0.384        | 0.006 (0.001)    | 0.512 (0.114)    | 0 (0.000) |    13.53 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2425 | 2024-04-29 | Insilio           | W   | 0.572      | 0.435        | 0.023 (0.006)    | 0.554 (0.138)    | 0 (0.000) |    14.28 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2516 | 2024-04-25 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |    -4.33 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2528 | 2024-04-25 | kONO              | L   | 0.544      | -            | -                | -                | -         |    -5.74 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2561 | 2024-04-23 | 1WIN              | L   | 0.532      | -            | -                | -                | -         |    -3.87 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2582 | 2024-04-22 | SINNERS           | L   | 0.525      | -            | -                | -                | -         |    -2.02 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2681 | 2024-04-19 | B8                | L   | 0.505      | -            | -                | -                | -         |    -2.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2734 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.498      | 0.384        | 0.032 (0.006)    | 0.563 (0.108)    | 0 (0.000) |    12.78 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2760 | 2024-04-17 | PARIVISION        | L   | 0.493      | -            | -                | -                | -         |    -1.76 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2822 | 2024-04-15 | Alliance          | L   | 0.479      | -            | -                | -                | -         |    -4.47 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2997 | 2024-04-09 | BLEED             | L   | 0.438      | -            | -                | -                | -         |    -2.33 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     3024 | 2024-04-08 | Permitta          | L   | 0.432      | -            | -                | -                | -         |    -2.91 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     3130 | 2024-04-04 | Passion UA        | L   | 0.405      | -            | -                | -                | -         |    -1.78 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3881 | 2024-03-02 | Sangal            | L   | 0.184      | -            | -                | -                | -         |    -0.47 | Airax, Banjo, ottoNd, puuha, uli |
|            6 |     3905 | 2024-02-29 | KOI               | L   | 0.172      | -            | -                | -                | -         |    -1.19 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3910 | 2024-02-29 | Aurora            | L   | 0.171      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3916 | 2024-02-28 | Croatia           | W   | 0.167      | 0.143        | 0.000 (0.000)    | 0.051 (0.001)    | 0 (0.000) |     1.21 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3918 | 2024-02-28 | Spirit Academy    | L   | 0.166      | -            | -                | -                | -         |    -3.73 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     4008 | 2024-02-24 | ENCE Academy      | L   | 0.141      | -            | -                | -                | -         |    -2.12 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     4014 | 2024-02-24 | Rounds            | W   | 0.139      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.139) |     0.64 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($225.77)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
