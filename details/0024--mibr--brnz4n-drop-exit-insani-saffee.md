### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1316.3<br />
<br />
Final Rank Value (1316.3) = Starting Rank Value (1418.7) + Head To Head Adjustments (-102.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.486[<sup>2</sup>](#table1)
- Opponent Network: 0.305[<sup>2</sup>](#table1)
- LAN Wins: 0.604[<sup>2</sup>](#table1)

The average of these factors is 0.498<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1418.7
- 400 + ( ( 0.498 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1418.7


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
|           81 |       76 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.98 | brnz4n, drop, exit, insani, saffee |
|           80 |       78 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.98 | brnz4n, drop, exit, insani, saffee |
|           79 |       92 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.724 (0.268)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      119 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.832 (0.308)    | -         |     5.00 | brnz4n, drop, exit, insani, saffee |
|           77 |      166 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           76 |      169 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |     5.47 | brnz4n, drop, exit, insani, saffee |
|           75 |      175 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |     5.76 | brnz4n, drop, exit, insani, saffee |
|           74 |      205 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.05 | brnz4n, drop, exit, insani, saffee |
|           73 |      208 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.26 | brnz4n, drop, exit, insani, saffee |
|           72 |      214 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      250 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.65 | brnz4n, drop, exit, insani, saffee |
|           70 |      275 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      281 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.67 | brnz4n, drop, exit, insani, saffee |
|           68 |      371 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.550 (0.247)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      372 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.550 (0.247)    | -         |     1.24 | brnz4n, drop, exit, insani, saffee |
|           66 |      635 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.19 | brnz4n, drop, exit, insani, saffee |
|           65 |      687 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.44 | brnz4n, drop, exit, insani, saffee |
|           64 |     1057 | 2024-06-15 | Complexity     | L   | 0.859      | -            | -                | -                | -         |    -6.61 | brnz4n, drop, exit, insani, saffee |
|           63 |     1083 | 2024-06-14 | Alliance       | W   | 0.854      | -            | -                | -                | 1 (0.854) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1096 | 2024-06-14 | ENCE           | L   | 0.853      | -            | -                | -                | -         |   -15.63 | brnz4n, drop, exit, insani, saffee |
|           61 |     1338 | 2024-06-07 | Bounty Hunters | L   | 0.810      | -            | -                | -                | -         |   -24.21 | brnz4n, drop, exit, insani, saffee |
|           60 |     1399 | 2024-06-06 | 9z             | L   | 0.802      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           59 |     1467 | 2024-06-05 | BESTIA         | W   | 0.796      | 0.450        | -                | 0.801 (0.287)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1521 | 2024-06-04 | Galorys        | W   | 0.789      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1845 | 2024-05-22 | paiN           | W   | 0.702      | 0.450        | 0.325 (0.103)    | 0.867 (0.274)    | -         |     8.44 | brnz4n, drop, exit, insani, saffee |
|           56 |     1849 | 2024-05-22 | paiN           | W   | 0.701      | 0.450        | 0.325 (0.103)    | 0.867 (0.274)    | -         |     8.95 | brnz4n, drop, exit, insani, saffee |
|           55 |     1923 | 2024-05-20 | BetBoom        | L   | 0.688      | -            | -                | -                | -         |   -12.75 | brnz4n, drop, exit, insani, saffee |
|           54 |     1934 | 2024-05-20 | BIG            | W   | 0.687      | 0.769        | 0.155 (0.082)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1943 | 2024-05-20 | BetBoom        | L   | 0.686      | -            | -                | -                | -         |   -13.19 | brnz4n, drop, exit, insani, saffee |
|           52 |     2020 | 2024-05-17 | HEROIC         | L   | 0.667      | -            | -                | -                | -         |    -7.58 | brnz4n, drop, exit, insani, saffee |
|           51 |     2053 | 2024-05-16 | Aurora         | W   | 0.661      | 0.769        | 0.422 (0.214)    | 0.788 (0.401)    | 1 (0.661) |    13.49 | brnz4n, drop, exit, insani, saffee |
|           50 |     2111 | 2024-05-15 | HEROIC         | L   | 0.653      | -            | -                | -                | -         |    -7.39 | brnz4n, drop, exit, insani, saffee |
|           49 |     2517 | 2024-04-28 | Aurora         | W   | 0.539      | 0.500        | 0.422 (0.114)    | -                | 1 (0.539) |    12.21 | brnz4n, drop, exit, insani, saffee |
|           48 |     2520 | 2024-04-27 | Apeks          | W   | 0.537      | -            | -                | -                | 1 (0.537) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2546 | 2024-04-26 | Rooster        | W   | 0.531      | -            | -                | -                | 1 (0.531) |     0.45 | brnz4n, drop, exit, insani, saffee |
|           46 |     2569 | 2024-04-26 | Rebels         | L   | 0.525      | -            | -                | -                | -         |   -15.35 | brnz4n, drop, exit, insani, saffee |
|           45 |     2572 | 2024-04-25 | KZG            | W   | 0.524      | -            | -                | -                | 1 (0.524) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2682 | 2024-04-20 | paiN           | L   | 0.488      | -            | -                | -                | -         |    -8.96 | brnz4n, drop, exit, insani, saffee |
|           43 |     2691 | 2024-04-20 | OG             | W   | 0.487      | -            | -                | -                | 1 (0.487) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2704 | 2024-04-19 | paiN           | W   | 0.484      | -            | -                | -                | -         |     6.71 | brnz4n, drop, exit, insani, saffee |
|           41 |     2711 | 2024-04-19 | FURIA          | W   | 0.483      | 0.589        | 0.284 (0.081)    | -                | 1 (0.483) |    11.87 | brnz4n, drop, exit, insani, saffee |
|           40 |     2730 | 2024-04-19 | paiN           | L   | 0.481      | -            | -                | -                | -         |    -8.54 | brnz4n, drop, exit, insani, saffee |
|           39 |     2752 | 2024-04-18 | Imperial       | W   | 0.477      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           38 |     2757 | 2024-04-18 | paiN           | W   | 0.476      | -            | -                | -                | -         |     6.72 | brnz4n, drop, exit, insani, saffee |
|           37 |     2761 | 2024-04-18 | OG             | W   | 0.475      | -            | -                | -                | 1 (0.475) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           36 |     2806 | 2024-04-17 | RED Canids     | W   | 0.469      | -            | -                | -                | -         |     1.90 | brnz4n, drop, exit, insani, saffee |
|           35 |     2812 | 2024-04-17 | Case           | W   | 0.469      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2851 | 2024-04-16 | Bounty Hunters | W   | 0.463      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2872 | 2024-04-15 | Imperial       | W   | 0.455      | 0.435        | 0.235 (0.046)    | -                | -         |     4.47 | brnz4n, drop, exit, insani, saffee |
|           32 |     2886 | 2024-04-14 | Galorys        | W   | 0.449      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2900 | 2024-04-13 | Case           | W   | 0.441      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2931 | 2024-04-11 | paiN           | W   | 0.430      | -            | -                | -                | -         |     6.66 | brnz4n, drop, exit, insani, saffee |
|           29 |     2969 | 2024-04-10 | Galorys        | W   | 0.423      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2973 | 2024-04-10 | Galorys        | W   | 0.422      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2990 | 2024-04-10 | Imperial       | W   | 0.421      | -            | -                | -                | -         |     4.40 | brnz4n, drop, exit, insani, saffee |
|           26 |     3021 | 2024-04-09 | adalYamigos    | W   | 0.416      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3026 | 2024-04-09 | adalYamigos    | W   | 0.416      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3033 | 2024-04-09 | RED Canids     | W   | 0.415      | -            | -                | -                | -         |     1.84 | brnz4n, drop, exit, insani, saffee |
|           23 |     3063 | 2024-04-08 | W7M            | W   | 0.409      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3097 | 2024-04-07 | paiN           | W   | 0.403      | -            | -                | -                | -         |     6.64 | brnz4n, drop, exit, insani, saffee |
|           21 |     3114 | 2024-04-06 | Bounty Hunters | W   | 0.396      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3131 | 2024-04-05 | Fluxo          | W   | 0.390      | -            | -                | -                | -         |     1.60 | brnz4n, drop, exit, insani, saffee |
|           19 |     3132 | 2024-04-05 | Fluxo          | L   | 0.389      | -            | -                | -                | -         |   -10.79 | brnz4n, drop, exit, insani, saffee |
|           18 |     3135 | 2024-04-05 | ODDIK          | W   | 0.388      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3156 | 2024-04-04 | Solid          | W   | 0.383      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3162 | 2024-04-04 | Solid          | W   | 0.383      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3195 | 2024-04-03 | Fluxo          | W   | 0.376      | -            | -                | -                | -         |     1.45 | brnz4n, drop, exit, insani, saffee |
|           14 |     3243 | 2024-04-02 | Fluxo          | W   | 0.370      | -            | -                | -                | -         |     1.41 | brnz4n, drop, exit, insani, saffee |
|           13 |     3246 | 2024-04-02 | Sharks         | W   | 0.368      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3332 | 2024-03-27 | Case           | W   | 0.330      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3338 | 2024-03-27 | Case           | W   | 0.329      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3378 | 2024-03-26 | ODDIK          | W   | 0.323      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            9 |     3380 | 2024-03-26 | ODDIK          | W   | 0.323      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            8 |     3572 | 2024-03-14 | Sharks         | W   | 0.243      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            7 |     3574 | 2024-03-14 | Sharks         | W   | 0.243      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            6 |     3646 | 2024-03-12 | Fluxo          | L   | 0.229      | -            | -                | -                | -         |    -6.34 | brnz4n, drop, exit, insani, saffee |
|            5 |     3685 | 2024-03-10 | Galorys        | W   | 0.216      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3733 | 2024-03-08 | LA RUGONETA    | W   | 0.202      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3864 | 2024-03-03 | Legacy         | L   | 0.169      | -            | -                | -                | -         |    -4.82 | brnz4n, drop, exit, insani, saffee |
|            2 |     3896 | 2024-03-02 | NRG            | W   | 0.161      | -            | -                | -                | 1 (0.161) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3918 | 2024-03-01 | BOSS           | L   | 0.155      | -            | -                | -                | -         |    -4.74 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,171.85)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.867 | $3,000.00      | $2,600.83       |
| 2024-06-09 |      0.822 | $3,000.00      | $2,466.39       |
| 2024-04-28 |      0.539 | $50,000.00     | $26,946.76      |
| 2024-04-20 |      0.489 | $20,000.00     | $9,775.93       |
| 2024-04-15 |      0.455 | $25,000.00     | $11,381.94      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
