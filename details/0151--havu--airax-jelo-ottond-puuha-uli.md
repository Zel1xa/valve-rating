### Roster Details<br />
Team Name: HAVU<br />
Roster: Airax, Jelo, ottoNd, puuha, uli<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.7<br />
<br />
Final Rank Value (706.7) = Starting Rank Value (716.8) + Head To Head Adjustments (-10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.241[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.8
- 400 + ( ( 0.154 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 716.8


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
|           32 |       95 | 2024-07-29 | Permitta          | L   | 1.000      | -            | -                | -                | -         |    -7.55 | Airax, Jelo, ottoNd, puuha, uli  |
|           31 |      220 | 2024-07-25 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -4.49 | Airax, Jelo, ottoNd, puuha, uli  |
|           30 |      541 | 2024-07-17 | Rhyno             | L   | 1.000      | -            | -                | -                | -         |    -5.53 | Airax, Jelo, ottoNd, puuha, uli  |
|           29 |     1090 | 2024-06-09 | Zero Tenacity     | L   | 0.851      | -            | -                | -                | -         |    -3.24 | Airax, Jelo, ottoNd, puuha, uli  |
|           28 |     1193 | 2024-06-07 | GUN5              | L   | 0.839      | -            | -                | -                | -         |    -5.03 | Airax, Jelo, ottoNd, puuha, uli  |
|           27 |     1282 | 2024-06-06 | Sampi             | L   | 0.831      | -            | -                | -                | -         |    -6.85 | Airax, Jelo, ottoNd, puuha, uli  |
|           26 |     1402 | 2024-06-03 | RUBY              | W   | 0.812      | 0.435        | 0.096 (0.034)    | 0.506 (0.179)    | 0 (0.000) |    20.11 | Airax, Jelo, ottoNd, puuha, uli  |
|           25 |     1413 | 2024-06-02 | UHKA              | W   | 0.806      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     3.87 | Airax, Jelo, ottoNd, puuha, uli  |
|           24 |     1427 | 2024-06-02 | Heimo             | W   | 0.804      | 0.143        | 0.006 (0.001)    | 0.086 (0.010)    | 0 (0.000) |    11.79 | Airax, Jelo, ottoNd, puuha, uli  |
|           23 |     2202 | 2024-05-05 | RUBY              | L   | 0.618      | -            | -                | -                | -         |    -4.35 | Airax, Jelo, ottoNd, puuha, uli  |
|           22 |     2214 | 2024-05-04 | RUSH B            | L   | 0.612      | -            | -                | -                | -         |    -5.89 | Airax, Jelo, ottoNd, puuha, uli  |
|           21 |     2252 | 2024-05-02 | Gaimin Gladiators | L   | 0.599      | -            | -                | -                | -         |    -2.98 | Airax, Jelo, ottoNd, puuha, uli  |
|           20 |     2265 | 2024-05-02 | Zero Tenacity     | L   | 0.597      | -            | -                | -                | -         |    -2.32 | Airax, Jelo, ottoNd, puuha, uli  |
|           19 |     2306 | 2024-04-30 | EYEBALLERS        | W   | 0.584      | 0.384        | 0.006 (0.001)    | 0.513 (0.115)    | 0 (0.000) |    13.71 | Airax, Jelo, ottoNd, puuha, uli  |
|           18 |     2325 | 2024-04-29 | Insilio           | W   | 0.578      | 0.435        | 0.023 (0.006)    | 0.554 (0.139)    | 0 (0.000) |    14.45 | Airax, Jelo, ottoNd, puuha, uli  |
|           17 |     2416 | 2024-04-25 | EYEBALLERS        | L   | 0.553      | -            | -                | -                | -         |    -4.34 | Airax, Jelo, ottoNd, puuha, uli  |
|           16 |     2428 | 2024-04-25 | kONO              | L   | 0.550      | -            | -                | -                | -         |    -6.10 | Airax, Jelo, ottoNd, puuha, uli  |
|           15 |     2459 | 2024-04-23 | 1WIN              | L   | 0.538      | -            | -                | -                | -         |    -3.93 | Airax, Jelo, ottoNd, puuha, uli  |
|           14 |     2479 | 2024-04-22 | SINNERS           | L   | 0.531      | -            | -                | -                | -         |    -2.13 | Airax, Jelo, ottoNd, puuha, uli  |
|           13 |     2574 | 2024-04-19 | B8                | L   | 0.511      | -            | -                | -                | -         |    -2.11 | Airax, Jelo, ottoNd, puuha, uli  |
|           12 |     2626 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.504      | 0.384        | 0.032 (0.006)    | 0.564 (0.109)    | 0 (0.000) |    12.99 | Airax, Jelo, ottoNd, puuha, uli  |
|           11 |     2651 | 2024-04-17 | PARIVISION        | L   | 0.499      | -            | -                | -                | -         |    -1.88 | Airax, Jelo, ottoNd, puuha, uli  |
|           10 |     2712 | 2024-04-15 | Alliance          | L   | 0.485      | -            | -                | -                | -         |    -4.57 | Airax, Jelo, ottoNd, puuha, uli  |
|            9 |     2886 | 2024-04-09 | BLEED             | L   | 0.444      | -            | -                | -                | -         |    -2.31 | Airax, Jelo, ottoNd, puuha, uli  |
|            8 |     2913 | 2024-04-08 | Permitta          | L   | 0.438      | -            | -                | -                | -         |    -2.99 | Airax, Jelo, ottoNd, puuha, uli  |
|            7 |     3018 | 2024-04-04 | Passion UA        | L   | 0.411      | -            | -                | -                | -         |    -1.88 | Airax, Jelo, ottoNd, puuha, uli  |
|            6 |     3746 | 2024-03-02 | Sangal            | L   | 0.190      | -            | -                | -                | -         |    -0.49 | Airax, Banjo, ottoNd, puuha, uli |
|            5 |     3769 | 2024-02-29 | KOI               | L   | 0.178      | -            | -                | -                | -         |    -0.56 | Airax, Banjo, ottoNd, puuha, uli |
|            4 |     3774 | 2024-02-29 | Aurora            | L   | 0.177      | -            | -                | -                | -         |    -0.02 | Airax, Banjo, ottoNd, puuha, uli |
|            3 |     3781 | 2024-02-28 | Spirit Academy    | L   | 0.172      | -            | -                | -                | -         |    -3.86 | Airax, Banjo, ottoNd, puuha, uli |
|            2 |     3869 | 2024-02-24 | ENCE Academy      | L   | 0.147      | -            | -                | -                | -         |    -2.21 | Airax, Banjo, ottoNd, puuha, uli |
|            1 |     3875 | 2024-02-24 | Rounds            | W   | 0.145      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.145) |     0.66 | Airax, Banjo, ottoNd, puuha, uli |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($235.41)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
