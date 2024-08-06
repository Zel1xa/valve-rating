### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1313.4<br />
<br />
Final Rank Value (1313.4) = Starting Rank Value (1413.9) + Head To Head Adjustments (-100.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.598[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1413.9
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1413.9


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
|           81 |      105 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           80 |      107 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      121 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.701 (0.260)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      148 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.805 (0.298)    | -         |     5.02 | brnz4n, drop, exit, insani, saffee |
|           77 |      195 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      198 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           75 |      204 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      234 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      237 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      243 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|           71 |      279 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.67 | brnz4n, drop, exit, insani, saffee |
|           70 |      304 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      310 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      400 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      401 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      664 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.14 | brnz4n, drop, exit, insani, saffee |
|           65 |      716 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.42 | brnz4n, drop, exit, insani, saffee |
|           64 |     1086 | 2024-06-15 | Complexity     | L   | 0.852      | -            | -                | -                | -         |    -6.50 | brnz4n, drop, exit, insani, saffee |
|           63 |     1112 | 2024-06-14 | Alliance       | W   | 0.847      | -            | -                | -                | 1 (0.847) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           62 |     1125 | 2024-06-14 | ENCE           | L   | 0.846      | -            | -                | -                | -         |   -15.22 | brnz4n, drop, exit, insani, saffee |
|           61 |     1367 | 2024-06-07 | Bounty Hunters | L   | 0.802      | -            | -                | -                | -         |   -23.99 | brnz4n, drop, exit, insani, saffee |
|           60 |     1428 | 2024-06-06 | 9z             | L   | 0.795      | -            | -                | -                | -         |   -11.81 | brnz4n, drop, exit, insani, saffee |
|           59 |     1496 | 2024-06-05 | BESTIA         | W   | 0.789      | 0.450        | -                | 0.776 (0.275)    | -         |     2.54 | brnz4n, drop, exit, insani, saffee |
|           58 |     1550 | 2024-06-04 | Galorys        | W   | 0.782      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1874 | 2024-05-22 | paiN           | W   | 0.694      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.35 | brnz4n, drop, exit, insani, saffee |
|           56 |     1878 | 2024-05-22 | paiN           | W   | 0.694      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.85 | brnz4n, drop, exit, insani, saffee |
|           55 |     1952 | 2024-05-20 | BetBoom        | L   | 0.681      | -            | -                | -                | -         |   -12.54 | brnz4n, drop, exit, insani, saffee |
|           54 |     1963 | 2024-05-20 | BIG            | W   | 0.679      | 0.769        | 0.154 (0.080)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1972 | 2024-05-20 | BetBoom        | L   | 0.678      | -            | -                | -                | -         |   -12.97 | brnz4n, drop, exit, insani, saffee |
|           52 |     2049 | 2024-05-17 | HEROIC         | L   | 0.660      | -            | -                | -                | -         |    -7.47 | brnz4n, drop, exit, insani, saffee |
|           51 |     2082 | 2024-05-16 | Aurora         | W   | 0.654      | 0.769        | 0.420 (0.211)    | 0.758 (0.381)    | 1 (0.654) |    13.66 | brnz4n, drop, exit, insani, saffee |
|           50 |     2140 | 2024-05-15 | HEROIC         | L   | 0.646      | -            | -                | -                | -         |    -7.28 | brnz4n, drop, exit, insani, saffee |
|           49 |     2546 | 2024-04-28 | Aurora         | W   | 0.532      | 0.500        | 0.420 (0.112)    | -                | 1 (0.532) |    12.28 | brnz4n, drop, exit, insani, saffee |
|           48 |     2549 | 2024-04-27 | Apeks          | W   | 0.530      | -            | -                | -                | 1 (0.530) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2575 | 2024-04-26 | Rooster        | W   | 0.524      | -            | -                | -                | 1 (0.524) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2598 | 2024-04-26 | Rebels         | L   | 0.518      | -            | -                | -                | -         |   -15.10 | brnz4n, drop, exit, insani, saffee |
|           45 |     2601 | 2024-04-25 | KZG            | W   | 0.517      | -            | -                | -                | 1 (0.517) |     0.22 | brnz4n, drop, exit, insani, saffee |
|           44 |     2711 | 2024-04-20 | paiN           | L   | 0.481      | -            | -                | -                | -         |    -8.84 | brnz4n, drop, exit, insani, saffee |
|           43 |     2720 | 2024-04-20 | OG             | W   | 0.480      | -            | -                | -                | 1 (0.480) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2733 | 2024-04-19 | paiN           | W   | 0.476      | -            | -                | -                | -         |     6.60 | brnz4n, drop, exit, insani, saffee |
|           41 |     2740 | 2024-04-19 | FURIA          | W   | 0.475      | 0.589        | 0.284 (0.079)    | -                | 1 (0.475) |    11.75 | brnz4n, drop, exit, insani, saffee |
|           40 |     2759 | 2024-04-19 | paiN           | L   | 0.474      | -            | -                | -                | -         |    -8.42 | brnz4n, drop, exit, insani, saffee |
|           39 |     2781 | 2024-04-18 | Imperial       | W   | 0.470      | -            | -                | -                | -         |     4.54 | brnz4n, drop, exit, insani, saffee |
|           38 |     2786 | 2024-04-18 | paiN           | W   | 0.469      | -            | -                | -                | -         |     6.60 | brnz4n, drop, exit, insani, saffee |
|           37 |     2790 | 2024-04-18 | OG             | W   | 0.468      | -            | -                | -                | 1 (0.468) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2835 | 2024-04-17 | RED Canids     | W   | 0.462      | -            | -                | -                | -         |     1.88 | brnz4n, drop, exit, insani, saffee |
|           35 |     2841 | 2024-04-17 | Case           | W   | 0.462      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2880 | 2024-04-16 | Bounty Hunters | W   | 0.456      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2901 | 2024-04-15 | Imperial       | W   | 0.448      | 0.435        | 0.233 (0.045)    | -                | -         |     4.38 | brnz4n, drop, exit, insani, saffee |
|           32 |     2915 | 2024-04-14 | Galorys        | W   | 0.441      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2929 | 2024-04-13 | Case           | W   | 0.434      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2960 | 2024-04-11 | paiN           | W   | 0.422      | -            | -                | -                | -         |     6.53 | brnz4n, drop, exit, insani, saffee |
|           29 |     2998 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     3002 | 2024-04-10 | Galorys        | W   | 0.415      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3019 | 2024-04-10 | Imperial       | W   | 0.413      | -            | -                | -                | -         |     4.30 | brnz4n, drop, exit, insani, saffee |
|           26 |     3050 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3055 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3062 | 2024-04-09 | RED Canids     | W   | 0.408      | -            | -                | -                | -         |     1.81 | brnz4n, drop, exit, insani, saffee |
|           23 |     3092 | 2024-04-08 | W7M            | W   | 0.402      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3126 | 2024-04-07 | paiN           | W   | 0.396      | -            | -                | -                | -         |     6.49 | brnz4n, drop, exit, insani, saffee |
|           21 |     3143 | 2024-04-06 | Bounty Hunters | W   | 0.389      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3160 | 2024-04-05 | Fluxo          | W   | 0.383      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3161 | 2024-04-05 | Fluxo          | L   | 0.382      | -            | -                | -                | -         |   -10.59 | brnz4n, drop, exit, insani, saffee |
|           18 |     3164 | 2024-04-05 | ODDIK          | W   | 0.381      | -            | -                | -                | -         |     0.97 | brnz4n, drop, exit, insani, saffee |
|           17 |     3185 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3191 | 2024-04-04 | Solid          | W   | 0.375      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3224 | 2024-04-03 | Fluxo          | W   | 0.369      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3272 | 2024-04-02 | Fluxo          | W   | 0.362      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3275 | 2024-04-02 | Sharks         | W   | 0.361      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3361 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3367 | 2024-03-27 | Case           | W   | 0.322      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3407 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.89 | brnz4n, drop, exit, insani, saffee |
|            9 |     3409 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3601 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|            7 |     3603 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3675 | 2024-03-12 | Fluxo          | L   | 0.221      | -            | -                | -                | -         |    -6.14 | brnz4n, drop, exit, insani, saffee |
|            5 |     3714 | 2024-03-10 | Galorys        | W   | 0.208      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3762 | 2024-03-08 | LA RUGONETA    | W   | 0.195      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3893 | 2024-03-03 | Legacy         | L   | 0.162      | -            | -                | -                | -         |    -4.61 | brnz4n, drop, exit, insani, saffee |
|            2 |     3925 | 2024-03-02 | NRG            | W   | 0.154      | -            | -                | -                | 1 (0.154) |     0.20 | brnz4n, drop, exit, insani, saffee |
|            1 |     3947 | 2024-03-01 | BOSS           | L   | 0.148      | -            | -                | -                | -         |    -4.51 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,442.41)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.860 | $3,000.00      | $2,579.17       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,444.72       |
| 2024-04-28 |      0.532 | $50,000.00     | $26,585.65      |
| 2024-04-20 |      0.482 | $20,000.00     | $9,631.48       |
| 2024-04-15 |      0.448 | $25,000.00     | $11,201.39      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
