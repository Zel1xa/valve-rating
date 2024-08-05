### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1351.9<br />
<br />
Final Rank Value (1351.9) = Starting Rank Value (1433.9) + Head To Head Adjustments (-82.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.589[<sup>1</sup>](#table2)
- Bounty Collected: 0.492[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.640[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1433.9
- 400 + ( ( 0.501 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1433.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           78 |        0 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.44 | brnz4n, drop, exit, insani, saffee |
|           77 |        3 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.097 (0.044)    | 0.781 (0.352)    | -         |     5.23 | brnz4n, drop, exit, insani, saffee |
|           76 |        9 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.097 (0.044)    | 0.781 (0.352)    | -         |     5.50 | brnz4n, drop, exit, insani, saffee |
|           75 |       39 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.16 | brnz4n, drop, exit, insani, saffee |
|           74 |       42 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.16 | brnz4n, drop, exit, insani, saffee |
|           73 |       48 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.25 | brnz4n, drop, exit, insani, saffee |
|           72 |       84 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.56 | brnz4n, drop, exit, insani, saffee |
|           71 |      109 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.27 | brnz4n, drop, exit, insani, saffee |
|           70 |      115 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.57 | brnz4n, drop, exit, insani, saffee |
|           69 |      205 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | -         |     1.13 | brnz4n, drop, exit, insani, saffee |
|           68 |      206 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.553 (0.249)    | -         |     1.14 | brnz4n, drop, exit, insani, saffee |
|           67 |      469 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.36 | brnz4n, drop, exit, insani, saffee |
|           66 |      521 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.40 | brnz4n, drop, exit, insani, saffee |
|           65 |      891 | 2024-06-15 | Complexity     | L   | 0.891      | -            | -                | -                | -         |    -7.15 | brnz4n, drop, exit, insani, saffee |
|           64 |      917 | 2024-06-14 | Alliance       | W   | 0.886      | -            | -                | -                | 1 (0.886) |     1.22 | brnz4n, drop, exit, insani, saffee |
|           63 |      930 | 2024-06-14 | ENCE           | L   | 0.884      | -            | -                | -                | -         |   -16.46 | brnz4n, drop, exit, insani, saffee |
|           62 |     1172 | 2024-06-07 | Bounty Hunters | L   | 0.841      | -            | -                | -                | -         |   -25.24 | brnz4n, drop, exit, insani, saffee |
|           61 |     1233 | 2024-06-06 | 9z             | L   | 0.834      | -            | -                | -                | -         |   -12.51 | brnz4n, drop, exit, insani, saffee |
|           60 |     1301 | 2024-06-05 | BESTIA         | W   | 0.827      | 0.450        | -                | 0.731 (0.272)    | -         |     2.52 | brnz4n, drop, exit, insani, saffee |
|           59 |     1355 | 2024-06-04 | Galorys        | W   | 0.821      | 0.450        | -                | 0.553 (0.204)    | -         |     0.95 | brnz4n, drop, exit, insani, saffee |
|           58 |     1679 | 2024-05-22 | paiN           | W   | 0.733      | 0.450        | 0.333 (0.110)    | 0.797 (0.263)    | -         |     8.87 | brnz4n, drop, exit, insani, saffee |
|           57 |     1683 | 2024-05-22 | paiN           | W   | 0.733      | 0.450        | 0.333 (0.110)    | 0.797 (0.263)    | -         |     9.44 | brnz4n, drop, exit, insani, saffee |
|           56 |     1757 | 2024-05-20 | BetBoom        | L   | 0.720      | -            | -                | -                | -         |   -13.19 | brnz4n, drop, exit, insani, saffee |
|           55 |     1768 | 2024-05-20 | BIG            | W   | 0.718      | 0.769        | 0.157 (0.087)    | -                | -         |     5.44 | brnz4n, drop, exit, insani, saffee |
|           54 |     1777 | 2024-05-20 | BetBoom        | L   | 0.717      | -            | -                | -                | -         |   -13.71 | brnz4n, drop, exit, insani, saffee |
|           53 |     1854 | 2024-05-17 | HEROIC         | L   | 0.699      | -            | -                | -                | -         |    -7.76 | brnz4n, drop, exit, insani, saffee |
|           52 |     1887 | 2024-05-16 | Aurora         | W   | 0.693      | 0.769        | 0.429 (0.228)    | 0.800 (0.426)    | 1 (0.693) |    13.87 | brnz4n, drop, exit, insani, saffee |
|           51 |     1945 | 2024-05-15 | HEROIC         | L   | 0.685      | -            | -                | -                | -         |    -7.57 | brnz4n, drop, exit, insani, saffee |
|           50 |     2351 | 2024-04-28 | Aurora         | W   | 0.570      | 0.500        | 0.429 (0.122)    | 0.800 (0.228)    | 1 (0.570) |    12.79 | brnz4n, drop, exit, insani, saffee |
|           49 |     2354 | 2024-04-27 | Apeks          | W   | 0.569      | -            | -                | -                | 1 (0.569) |     1.21 | brnz4n, drop, exit, insani, saffee |
|           48 |     2380 | 2024-04-26 | Rooster        | W   | 0.562      | -            | -                | -                | 1 (0.562) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           47 |     2403 | 2024-04-26 | Rebels         | L   | 0.556      | -            | -                | -                | -         |   -16.30 | brnz4n, drop, exit, insani, saffee |
|           46 |     2406 | 2024-04-25 | KZG            | W   | 0.555      | -            | -                | -                | 1 (0.555) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           45 |     2516 | 2024-04-20 | paiN           | L   | 0.519      | -            | -                | -                | -         |    -9.43 | brnz4n, drop, exit, insani, saffee |
|           44 |     2525 | 2024-04-20 | OG             | W   | 0.518      | 0.589        | 0.143 (0.044)    | -                | 1 (0.518) |     1.70 | brnz4n, drop, exit, insani, saffee |
|           43 |     2538 | 2024-04-19 | paiN           | W   | 0.515      | -            | -                | -                | -         |     7.27 | brnz4n, drop, exit, insani, saffee |
|           42 |     2545 | 2024-04-19 | FURIA          | W   | 0.514      | 0.589        | 0.284 (0.086)    | -                | 1 (0.514) |    12.68 | brnz4n, drop, exit, insani, saffee |
|           41 |     2564 | 2024-04-19 | paiN           | L   | 0.512      | -            | -                | -                | -         |    -8.96 | brnz4n, drop, exit, insani, saffee |
|           40 |     2586 | 2024-04-18 | Imperial       | W   | 0.508      | -            | -                | -                | -         |     5.17 | brnz4n, drop, exit, insani, saffee |
|           39 |     2591 | 2024-04-18 | paiN           | W   | 0.507      | -            | -                | -                | -         |     7.31 | brnz4n, drop, exit, insani, saffee |
|           38 |     2595 | 2024-04-18 | OG             | W   | 0.507      | -            | -                | -                | 1 (0.507) |     1.70 | brnz4n, drop, exit, insani, saffee |
|           37 |     2640 | 2024-04-17 | RED Canids     | W   | 0.501      | -            | -                | -                | -         |     1.98 | brnz4n, drop, exit, insani, saffee |
|           36 |     2646 | 2024-04-17 | Case           | W   | 0.500      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           35 |     2685 | 2024-04-16 | Bounty Hunters | W   | 0.494      | -            | -                | -                | -         |     0.68 | brnz4n, drop, exit, insani, saffee |
|           34 |     2706 | 2024-04-15 | Imperial       | W   | 0.487      | 0.435        | 0.243 (0.051)    | -                | -         |     5.04 | brnz4n, drop, exit, insani, saffee |
|           33 |     2720 | 2024-04-14 | Galorys        | W   | 0.480      | -            | -                | -                | -         |     0.76 | brnz4n, drop, exit, insani, saffee |
|           32 |     2734 | 2024-04-13 | Case           | W   | 0.472      | -            | -                | -                | -         |     0.74 | brnz4n, drop, exit, insani, saffee |
|           31 |     2765 | 2024-04-11 | paiN           | W   | 0.461      | -            | -                | -                | -         |     7.34 | brnz4n, drop, exit, insani, saffee |
|           30 |     2803 | 2024-04-10 | Galorys        | W   | 0.454      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           29 |     2807 | 2024-04-10 | Galorys        | W   | 0.454      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           28 |     2824 | 2024-04-10 | Imperial       | W   | 0.452      | -            | -                | -                | -         |     5.03 | brnz4n, drop, exit, insani, saffee |
|           27 |     2855 | 2024-04-09 | adalYamigos    | W   | 0.448      | -            | -                | -                | -         |     0.17 | brnz4n, drop, exit, insani, saffee |
|           26 |     2860 | 2024-04-09 | adalYamigos    | W   | 0.447      | -            | -                | -                | -         |     0.17 | brnz4n, drop, exit, insani, saffee |
|           25 |     2867 | 2024-04-09 | RED Canids     | W   | 0.446      | -            | -                | -                | -         |     1.95 | brnz4n, drop, exit, insani, saffee |
|           24 |     2897 | 2024-04-08 | W7M            | W   | 0.441      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           23 |     2931 | 2024-04-07 | paiN           | W   | 0.434      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           22 |     2948 | 2024-04-06 | Bounty Hunters | W   | 0.427      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           21 |     2965 | 2024-04-05 | Fluxo          | W   | 0.421      | -            | -                | -                | -         |     1.64 | brnz4n, drop, exit, insani, saffee |
|           20 |     2966 | 2024-04-05 | Fluxo          | L   | 0.421      | -            | -                | -                | -         |   -11.75 | brnz4n, drop, exit, insani, saffee |
|           19 |     2969 | 2024-04-05 | ODDIK          | W   | 0.419      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           18 |     2990 | 2024-04-04 | Solid          | W   | 0.414      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           17 |     2996 | 2024-04-04 | Solid          | W   | 0.414      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           16 |     3029 | 2024-04-03 | Fluxo          | W   | 0.408      | -            | -                | -                | -         |     1.48 | brnz4n, drop, exit, insani, saffee |
|           15 |     3077 | 2024-04-02 | Fluxo          | W   | 0.401      | -            | -                | -                | -         |     1.44 | brnz4n, drop, exit, insani, saffee |
|           14 |     3080 | 2024-04-02 | Sharks         | W   | 0.400      | -            | -                | -                | -         |     0.31 | brnz4n, drop, exit, insani, saffee |
|           13 |     3166 | 2024-03-27 | Case           | W   | 0.361      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           12 |     3172 | 2024-03-27 | Case           | W   | 0.361      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           11 |     3212 | 2024-03-26 | ODDIK          | W   | 0.354      | -            | -                | -                | -         |     0.93 | brnz4n, drop, exit, insani, saffee |
|           10 |     3214 | 2024-03-26 | ODDIK          | W   | 0.354      | -            | -                | -                | -         |     0.94 | brnz4n, drop, exit, insani, saffee |
|            9 |     3406 | 2024-03-14 | Sharks         | W   | 0.274      | -            | -                | -                | -         |     0.68 | brnz4n, drop, exit, insani, saffee |
|            8 |     3408 | 2024-03-14 | Sharks         | W   | 0.274      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|            7 |     3480 | 2024-03-12 | Fluxo          | L   | 0.260      | -            | -                | -                | -         |    -7.27 | brnz4n, drop, exit, insani, saffee |
|            6 |     3519 | 2024-03-10 | Galorys        | W   | 0.247      | -            | -                | -                | -         |     0.38 | brnz4n, drop, exit, insani, saffee |
|            5 |     3567 | 2024-03-08 | LA RUGONETA    | W   | 0.233      | -            | -                | -                | -         |     0.06 | brnz4n, drop, exit, insani, saffee |
|            4 |     3698 | 2024-03-03 | Legacy         | L   | 0.200      | -            | -                | -                | -         |    -5.76 | brnz4n, drop, exit, insani, saffee |
|            3 |     3730 | 2024-03-02 | NRG            | W   | 0.193      | -            | -                | -                | 1 (0.193) |     0.23 | brnz4n, drop, exit, insani, saffee |
|            2 |     3752 | 2024-03-01 | BOSS           | L   | 0.187      | -            | -                | -                | -         |    -5.70 | brnz4n, drop, exit, insani, saffee |
|            1 |     4280 | 2024-02-03 | Imperial       | L   | 0.007      | -            | -                | -                | -         |    -0.15 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,331.38)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.898 | $3,000.00      | $2,694.68       |
| 2024-06-09 |      0.853 | $3,000.00      | $2,560.24       |
| 2024-04-28 |      0.570 | $50,000.00     | $28,510.88      |
| 2024-04-20 |      0.520 | $20,000.00     | $10,401.57      |
| 2024-04-15 |      0.487 | $25,000.00     | $12,164.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
