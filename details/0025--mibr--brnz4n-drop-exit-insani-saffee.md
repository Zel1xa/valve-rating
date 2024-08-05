### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1315.5<br />
<br />
Final Rank Value (1315.5) = Starting Rank Value (1417.5) + Head To Head Adjustments (-102.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.486[<sup>2</sup>](#table1)
- Opponent Network: 0.302[<sup>2</sup>](#table1)
- LAN Wins: 0.603[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1417.5
- 400 + ( ( 0.496 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1417.5


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
|           81 |       85 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.98 | brnz4n, drop, exit, insani, saffee |
|           80 |       87 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.98 | brnz4n, drop, exit, insani, saffee |
|           79 |      101 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.716 (0.265)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      128 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.822 (0.305)    | -         |     5.00 | brnz4n, drop, exit, insani, saffee |
|           77 |      175 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           76 |      178 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.47 | brnz4n, drop, exit, insani, saffee |
|           75 |      184 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.76 | brnz4n, drop, exit, insani, saffee |
|           74 |      214 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.04 | brnz4n, drop, exit, insani, saffee |
|           73 |      217 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.26 | brnz4n, drop, exit, insani, saffee |
|           72 |      223 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      259 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.66 | brnz4n, drop, exit, insani, saffee |
|           70 |      284 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      290 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      380 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      381 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.24 | brnz4n, drop, exit, insani, saffee |
|           66 |      644 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.18 | brnz4n, drop, exit, insani, saffee |
|           65 |      696 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.43 | brnz4n, drop, exit, insani, saffee |
|           64 |     1066 | 2024-06-15 | Complexity     | L   | 0.858      | -            | -                | -                | -         |    -6.58 | brnz4n, drop, exit, insani, saffee |
|           63 |     1092 | 2024-06-14 | Alliance       | W   | 0.853      | -            | -                | -                | 1 (0.853) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1105 | 2024-06-14 | ENCE           | L   | 0.852      | -            | -                | -                | -         |   -15.48 | brnz4n, drop, exit, insani, saffee |
|           61 |     1347 | 2024-06-07 | Bounty Hunters | L   | 0.808      | -            | -                | -                | -         |   -24.17 | brnz4n, drop, exit, insani, saffee |
|           60 |     1408 | 2024-06-06 | 9z             | L   | 0.801      | -            | -                | -                | -         |   -11.95 | brnz4n, drop, exit, insani, saffee |
|           59 |     1476 | 2024-06-05 | BESTIA         | W   | 0.794      | 0.450        | -                | 0.792 (0.283)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1530 | 2024-06-04 | Galorys        | W   | 0.788      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1854 | 2024-05-22 | paiN           | W   | 0.700      | 0.450        | 0.325 (0.102)    | 0.856 (0.270)    | -         |     8.41 | brnz4n, drop, exit, insani, saffee |
|           56 |     1858 | 2024-05-22 | paiN           | W   | 0.700      | 0.450        | 0.325 (0.102)    | 0.856 (0.270)    | -         |     8.93 | brnz4n, drop, exit, insani, saffee |
|           55 |     1932 | 2024-05-20 | BetBoom        | L   | 0.687      | -            | -                | -                | -         |   -12.71 | brnz4n, drop, exit, insani, saffee |
|           54 |     1943 | 2024-05-20 | BIG            | W   | 0.685      | 0.769        | 0.154 (0.081)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1952 | 2024-05-20 | BetBoom        | L   | 0.684      | -            | -                | -                | -         |   -13.15 | brnz4n, drop, exit, insani, saffee |
|           52 |     2029 | 2024-05-17 | HEROIC         | L   | 0.666      | -            | -                | -                | -         |    -7.55 | brnz4n, drop, exit, insani, saffee |
|           51 |     2062 | 2024-05-16 | Aurora         | W   | 0.660      | 0.769        | 0.422 (0.214)    | 0.778 (0.395)    | 1 (0.660) |    13.57 | brnz4n, drop, exit, insani, saffee |
|           50 |     2120 | 2024-05-15 | HEROIC         | L   | 0.652      | -            | -                | -                | -         |    -7.36 | brnz4n, drop, exit, insani, saffee |
|           49 |     2526 | 2024-04-28 | Aurora         | W   | 0.537      | 0.500        | 0.422 (0.113)    | -                | 1 (0.537) |    12.26 | brnz4n, drop, exit, insani, saffee |
|           48 |     2529 | 2024-04-27 | Apeks          | W   | 0.536      | -            | -                | -                | 1 (0.536) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2555 | 2024-04-26 | Rooster        | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2578 | 2024-04-26 | Rebels         | L   | 0.524      | -            | -                | -                | -         |   -15.29 | brnz4n, drop, exit, insani, saffee |
|           45 |     2581 | 2024-04-25 | KZG            | W   | 0.522      | -            | -                | -                | 1 (0.522) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2691 | 2024-04-20 | paiN           | L   | 0.486      | -            | -                | -                | -         |    -8.94 | brnz4n, drop, exit, insani, saffee |
|           43 |     2700 | 2024-04-20 | OG             | W   | 0.485      | -            | -                | -                | 1 (0.485) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           42 |     2713 | 2024-04-19 | paiN           | W   | 0.482      | -            | -                | -                | -         |     6.69 | brnz4n, drop, exit, insani, saffee |
|           41 |     2720 | 2024-04-19 | FURIA          | W   | 0.481      | 0.589        | 0.284 (0.080)    | -                | 1 (0.481) |    11.85 | brnz4n, drop, exit, insani, saffee |
|           40 |     2739 | 2024-04-19 | paiN           | L   | 0.480      | -            | -                | -                | -         |    -8.52 | brnz4n, drop, exit, insani, saffee |
|           39 |     2761 | 2024-04-18 | Imperial       | W   | 0.475      | -            | -                | -                | -         |     4.60 | brnz4n, drop, exit, insani, saffee |
|           38 |     2766 | 2024-04-18 | paiN           | W   | 0.474      | -            | -                | -                | -         |     6.70 | brnz4n, drop, exit, insani, saffee |
|           37 |     2770 | 2024-04-18 | OG             | W   | 0.474      | -            | -                | -                | 1 (0.474) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           36 |     2815 | 2024-04-17 | RED Canids     | W   | 0.468      | -            | -                | -                | -         |     1.90 | brnz4n, drop, exit, insani, saffee |
|           35 |     2821 | 2024-04-17 | Case           | W   | 0.467      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2860 | 2024-04-16 | Bounty Hunters | W   | 0.461      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2881 | 2024-04-15 | Imperial       | W   | 0.454      | 0.435        | 0.234 (0.046)    | -                | -         |     4.45 | brnz4n, drop, exit, insani, saffee |
|           32 |     2895 | 2024-04-14 | Galorys        | W   | 0.447      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2909 | 2024-04-13 | Case           | W   | 0.440      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2940 | 2024-04-11 | paiN           | W   | 0.428      | -            | -                | -                | -         |     6.63 | brnz4n, drop, exit, insani, saffee |
|           29 |     2978 | 2024-04-10 | Galorys        | W   | 0.421      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2982 | 2024-04-10 | Galorys        | W   | 0.421      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     2999 | 2024-04-10 | Imperial       | W   | 0.419      | -            | -                | -                | -         |     4.38 | brnz4n, drop, exit, insani, saffee |
|           26 |     3030 | 2024-04-09 | adalYamigos    | W   | 0.415      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3035 | 2024-04-09 | adalYamigos    | W   | 0.414      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3042 | 2024-04-09 | RED Canids     | W   | 0.413      | -            | -                | -                | -         |     1.83 | brnz4n, drop, exit, insani, saffee |
|           23 |     3072 | 2024-04-08 | W7M            | W   | 0.408      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3106 | 2024-04-07 | paiN           | W   | 0.402      | -            | -                | -                | -         |     6.61 | brnz4n, drop, exit, insani, saffee |
|           21 |     3123 | 2024-04-06 | Bounty Hunters | W   | 0.395      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3140 | 2024-04-05 | Fluxo          | W   | 0.388      | -            | -                | -                | -         |     1.59 | brnz4n, drop, exit, insani, saffee |
|           19 |     3141 | 2024-04-05 | Fluxo          | L   | 0.388      | -            | -                | -                | -         |   -10.75 | brnz4n, drop, exit, insani, saffee |
|           18 |     3144 | 2024-04-05 | ODDIK          | W   | 0.387      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3165 | 2024-04-04 | Solid          | W   | 0.381      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3171 | 2024-04-04 | Solid          | W   | 0.381      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3204 | 2024-04-03 | Fluxo          | W   | 0.375      | -            | -                | -                | -         |     1.45 | brnz4n, drop, exit, insani, saffee |
|           14 |     3252 | 2024-04-02 | Fluxo          | W   | 0.368      | -            | -                | -                | -         |     1.41 | brnz4n, drop, exit, insani, saffee |
|           13 |     3255 | 2024-04-02 | Sharks         | W   | 0.367      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3341 | 2024-03-27 | Case           | W   | 0.328      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3347 | 2024-03-27 | Case           | W   | 0.328      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3387 | 2024-03-26 | ODDIK          | W   | 0.322      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3389 | 2024-03-26 | ODDIK          | W   | 0.321      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            8 |     3581 | 2024-03-14 | Sharks         | W   | 0.242      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            7 |     3583 | 2024-03-14 | Sharks         | W   | 0.241      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            6 |     3655 | 2024-03-12 | Fluxo          | L   | 0.227      | -            | -                | -                | -         |    -6.30 | brnz4n, drop, exit, insani, saffee |
|            5 |     3694 | 2024-03-10 | Galorys        | W   | 0.214      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3742 | 2024-03-08 | LA RUGONETA    | W   | 0.200      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3873 | 2024-03-03 | Legacy         | L   | 0.167      | -            | -                | -                | -         |    -4.77 | brnz4n, drop, exit, insani, saffee |
|            2 |     3905 | 2024-03-02 | NRG            | W   | 0.160      | -            | -                | -                | 1 (0.160) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3927 | 2024-03-01 | BOSS           | L   | 0.154      | -            | -                | -                | -         |    -4.69 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,017.55)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.865 | $3,000.00      | $2,596.25       |
| 2024-06-09 |      0.821 | $3,000.00      | $2,461.81       |
| 2024-04-28 |      0.537 | $50,000.00     | $26,870.37      |
| 2024-04-20 |      0.487 | $20,000.00     | $9,745.37       |
| 2024-04-15 |      0.454 | $25,000.00     | $11,343.75      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
