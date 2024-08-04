### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1317.4<br />
<br />
Final Rank Value (1317.4) = Starting Rank Value (1421.2) + Head To Head Adjustments (-103.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.608[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.2
- 400 + ( ( 0.499 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1421.2


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
|           81 |       59 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.97 | brnz4n, drop, exit, insani, saffee |
|           80 |       61 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.99 | brnz4n, drop, exit, insani, saffee |
|           79 |       75 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.724 (0.268)    | -         |     7.83 | brnz4n, drop, exit, insani, saffee |
|           78 |      102 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.832 (0.308)    | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           77 |      149 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.61 | brnz4n, drop, exit, insani, saffee |
|           76 |      152 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |     5.45 | brnz4n, drop, exit, insani, saffee |
|           75 |      158 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |     5.74 | brnz4n, drop, exit, insani, saffee |
|           74 |      188 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.06 | brnz4n, drop, exit, insani, saffee |
|           73 |      191 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           72 |      197 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      233 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.64 | brnz4n, drop, exit, insani, saffee |
|           70 |      258 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      264 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.65 | brnz4n, drop, exit, insani, saffee |
|           68 |      354 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      355 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           66 |      618 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.25 | brnz4n, drop, exit, insani, saffee |
|           65 |      670 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.44 | brnz4n, drop, exit, insani, saffee |
|           64 |     1040 | 2024-06-15 | Complexity     | L   | 0.865      | -            | -                | -                | -         |    -6.67 | brnz4n, drop, exit, insani, saffee |
|           63 |     1066 | 2024-06-14 | Alliance       | W   | 0.860      | -            | -                | -                | 1 (0.860) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1079 | 2024-06-14 | ENCE           | L   | 0.859      | -            | -                | -                | -         |   -15.98 | brnz4n, drop, exit, insani, saffee |
|           61 |     1321 | 2024-06-07 | Bounty Hunters | L   | 0.815      | -            | -                | -                | -         |   -24.40 | brnz4n, drop, exit, insani, saffee |
|           60 |     1382 | 2024-06-06 | 9z             | L   | 0.808      | -            | -                | -                | -         |   -12.12 | brnz4n, drop, exit, insani, saffee |
|           59 |     1450 | 2024-06-05 | BESTIA         | W   | 0.802      | 0.450        | -                | 0.801 (0.289)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1504 | 2024-06-04 | Galorys        | W   | 0.795      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1828 | 2024-05-22 | paiN           | W   | 0.707      | 0.450        | 0.327 (0.104)    | 0.867 (0.276)    | -         |     8.51 | brnz4n, drop, exit, insani, saffee |
|           56 |     1832 | 2024-05-22 | paiN           | W   | 0.707      | 0.450        | 0.327 (0.104)    | 0.867 (0.276)    | -         |     9.03 | brnz4n, drop, exit, insani, saffee |
|           55 |     1906 | 2024-05-20 | BetBoom        | L   | 0.694      | -            | -                | -                | -         |   -12.88 | brnz4n, drop, exit, insani, saffee |
|           54 |     1917 | 2024-05-20 | BIG            | W   | 0.692      | 0.769        | 0.155 (0.082)    | -                | -         |     6.78 | brnz4n, drop, exit, insani, saffee |
|           53 |     1926 | 2024-05-20 | BetBoom        | L   | 0.691      | -            | -                | -                | -         |   -13.33 | brnz4n, drop, exit, insani, saffee |
|           52 |     2003 | 2024-05-17 | HEROIC         | L   | 0.673      | -            | -                | -                | -         |    -7.67 | brnz4n, drop, exit, insani, saffee |
|           51 |     2036 | 2024-05-16 | Aurora         | W   | 0.667      | 0.769        | 0.423 (0.217)    | 0.793 (0.406)    | 1 (0.667) |    13.48 | brnz4n, drop, exit, insani, saffee |
|           50 |     2094 | 2024-05-15 | HEROIC         | L   | 0.659      | -            | -                | -                | -         |    -7.49 | brnz4n, drop, exit, insani, saffee |
|           49 |     2500 | 2024-04-28 | Aurora         | W   | 0.545      | 0.500        | 0.423 (0.115)    | -                | 1 (0.545) |    12.26 | brnz4n, drop, exit, insani, saffee |
|           48 |     2503 | 2024-04-27 | Apeks          | W   | 0.543      | -            | -                | -                | 1 (0.543) |     1.10 | brnz4n, drop, exit, insani, saffee |
|           47 |     2529 | 2024-04-26 | Rooster        | W   | 0.537      | -            | -                | -                | 1 (0.537) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2552 | 2024-04-26 | Rebels         | L   | 0.531      | -            | -                | -                | -         |   -15.52 | brnz4n, drop, exit, insani, saffee |
|           45 |     2555 | 2024-04-25 | KZG            | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2665 | 2024-04-20 | paiN           | L   | 0.494      | -            | -                | -                | -         |    -9.06 | brnz4n, drop, exit, insani, saffee |
|           43 |     2674 | 2024-04-20 | OG             | W   | 0.492      | -            | -                | -                | 1 (0.492) |     1.57 | brnz4n, drop, exit, insani, saffee |
|           42 |     2687 | 2024-04-19 | paiN           | W   | 0.489      | -            | -                | -                | -         |     6.80 | brnz4n, drop, exit, insani, saffee |
|           41 |     2694 | 2024-04-19 | FURIA          | W   | 0.488      | 0.589        | 0.284 (0.082)    | -                | 1 (0.488) |    11.94 | brnz4n, drop, exit, insani, saffee |
|           40 |     2713 | 2024-04-19 | paiN           | L   | 0.487      | -            | -                | -                | -         |    -8.63 | brnz4n, drop, exit, insani, saffee |
|           39 |     2735 | 2024-04-18 | Imperial       | W   | 0.483      | -            | -                | -                | -         |     4.69 | brnz4n, drop, exit, insani, saffee |
|           38 |     2740 | 2024-04-18 | paiN           | W   | 0.482      | -            | -                | -                | -         |     6.81 | brnz4n, drop, exit, insani, saffee |
|           37 |     2744 | 2024-04-18 | OG             | W   | 0.481      | -            | -                | -                | 1 (0.481) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           36 |     2789 | 2024-04-17 | RED Canids     | W   | 0.475      | -            | -                | -                | -         |     1.91 | brnz4n, drop, exit, insani, saffee |
|           35 |     2795 | 2024-04-17 | Case           | W   | 0.475      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2834 | 2024-04-16 | Bounty Hunters | W   | 0.469      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2855 | 2024-04-15 | Imperial       | W   | 0.461      | 0.435        | 0.236 (0.047)    | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           32 |     2869 | 2024-04-14 | Galorys        | W   | 0.454      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2883 | 2024-04-13 | Case           | W   | 0.447      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2914 | 2024-04-11 | paiN           | W   | 0.435      | -            | -                | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           29 |     2952 | 2024-04-10 | Galorys        | W   | 0.429      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2956 | 2024-04-10 | Galorys        | W   | 0.428      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2973 | 2024-04-10 | Imperial       | W   | 0.426      | -            | -                | -                | -         |     4.48 | brnz4n, drop, exit, insani, saffee |
|           26 |     3004 | 2024-04-09 | adalYamigos    | W   | 0.422      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3009 | 2024-04-09 | adalYamigos    | W   | 0.422      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3016 | 2024-04-09 | RED Canids     | W   | 0.421      | -            | -                | -                | -         |     1.85 | brnz4n, drop, exit, insani, saffee |
|           23 |     3046 | 2024-04-08 | W7M            | W   | 0.415      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3080 | 2024-04-07 | paiN           | W   | 0.409      | -            | -                | -                | -         |     6.75 | brnz4n, drop, exit, insani, saffee |
|           21 |     3097 | 2024-04-06 | Bounty Hunters | W   | 0.402      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           20 |     3114 | 2024-04-05 | Fluxo          | W   | 0.395      | -            | -                | -                | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           19 |     3115 | 2024-04-05 | Fluxo          | L   | 0.395      | -            | -                | -                | -         |   -10.96 | brnz4n, drop, exit, insani, saffee |
|           18 |     3118 | 2024-04-05 | ODDIK          | W   | 0.394      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           17 |     3139 | 2024-04-04 | Solid          | W   | 0.389      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3145 | 2024-04-04 | Solid          | W   | 0.388      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           15 |     3178 | 2024-04-03 | Fluxo          | W   | 0.382      | -            | -                | -                | -         |     1.46 | brnz4n, drop, exit, insani, saffee |
|           14 |     3226 | 2024-04-02 | Fluxo          | W   | 0.375      | -            | -                | -                | -         |     1.42 | brnz4n, drop, exit, insani, saffee |
|           13 |     3229 | 2024-04-02 | Sharks         | W   | 0.374      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3315 | 2024-03-27 | Case           | W   | 0.335      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3321 | 2024-03-27 | Case           | W   | 0.335      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           10 |     3361 | 2024-03-26 | ODDIK          | W   | 0.329      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            9 |     3363 | 2024-03-26 | ODDIK          | W   | 0.328      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            8 |     3555 | 2024-03-14 | Sharks         | W   | 0.249      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            7 |     3557 | 2024-03-14 | Sharks         | W   | 0.249      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|            6 |     3629 | 2024-03-12 | Fluxo          | L   | 0.234      | -            | -                | -                | -         |    -6.50 | brnz4n, drop, exit, insani, saffee |
|            5 |     3668 | 2024-03-10 | Galorys        | W   | 0.221      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|            4 |     3716 | 2024-03-08 | LA RUGONETA    | W   | 0.208      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3847 | 2024-03-03 | Legacy         | L   | 0.175      | -            | -                | -                | -         |    -4.98 | brnz4n, drop, exit, insani, saffee |
|            2 |     3879 | 2024-03-02 | NRG            | W   | 0.167      | -            | -                | -                | 1 (0.167) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3901 | 2024-03-01 | BOSS           | L   | 0.161      | -            | -                | -                | -         |    -4.91 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,749.33)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.873 | $3,000.00      | $2,617.99       |
| 2024-06-09 |      0.828 | $3,000.00      | $2,483.54       |
| 2024-04-28 |      0.545 | $50,000.00     | $27,232.64      |
| 2024-04-20 |      0.495 | $20,000.00     | $9,890.28       |
| 2024-04-15 |      0.461 | $25,000.00     | $11,524.88      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
