### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, KENSI, Lack1, Norwi, r3salt<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1395.2<br />
<br />
Final Rank Value (1395.2) = Starting Rank Value (1685.9) + Head To Head Adjustments (-290.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.726[<sup>1</sup>](#table2)
- Bounty Collected: 0.503[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.978[<sup>2</sup>](#table1)

The average of these factors is 0.625<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1685.9
- 400 + ( ( 0.625 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1685.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           87 |       26 | 2024-08-05 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |   -28.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           86 |       58 | 2024-08-04 | Nemiga             | L   | 1.000      | -            | -                | -                | -         |   -26.43 | deko, KENSI, Lack1, Norwi, r3salt     |
|           85 |      336 | 2024-07-28 | 3DMAX              | L   | 1.000      | -            | -                | -                | -         |   -18.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           84 |      384 | 2024-07-26 | The MongolZ        | L   | 1.000      | -            | -                | -                | -         |    -6.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           83 |      389 | 2024-07-26 | BLEED              | W   | 1.000      | 0.650        | 0.125 (0.082)    | 0.538 (0.350)    | 1 (1.000) |     9.89 | deko, KENSI, Lack1, Norwi, r3salt     |
|           82 |      415 | 2024-07-25 | True Rippers       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           81 |      427 | 2024-07-25 | ENCE               | W   | 1.000      | 0.650        | 0.173 (0.112)    | 0.422 (0.274)    | 1 (1.000) |    12.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           80 |      462 | 2024-07-24 | PARIVISION         | W   | 1.000      | 0.650        | -                | 0.590 (0.384)    | 1 (1.000) |     3.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           79 |      651 | 2024-07-18 | B8                 | W   | 1.000      | 0.500        | 0.170 (0.085)    | 0.912 (0.456)    | -         |     5.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           78 |      779 | 2024-07-16 | PERA               | W   | 1.000      | 0.500        | -                | 0.435 (0.218)    | -         |     2.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           77 |     1061 | 2024-06-16 | Complexity         | L   | 0.858      | -            | -                | -                | -         |    -7.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           76 |     1127 | 2024-06-14 | The MongolZ        | W   | 0.846      | 0.500        | 1.000 (0.423)    | 0.694 (0.293)    | 1 (0.846) |    24.72 | deko, KENSI, Lack1, Norwi, r3salt     |
|           75 |     1137 | 2024-06-14 | Falcons            | W   | 0.845      | 0.500        | 0.219 (0.093)    | -                | 1 (0.845) |    13.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1237 | 2024-06-10 | 9 Pandas           | W   | 0.819      | -            | -                | -                | -         |     3.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1242 | 2024-06-10 | Monte              | W   | 0.819      | -            | -                | -                | -         |     2.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1246 | 2024-06-10 | SAW                | L   | 0.818      | -            | -                | -                | -         |   -20.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1271 | 2024-06-09 | Monte              | L   | 0.813      | -            | -                | -                | -         |   -23.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1278 | 2024-06-09 | PARIVISION         | W   | 0.813      | -            | -                | -                | -         |     3.58 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1286 | 2024-06-09 | RUSH B             | L   | 0.812      | -            | -                | -                | -         |   -24.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1294 | 2024-06-09 | 3DMAX              | L   | 0.812      | -            | -                | -                | -         |   -12.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1302 | 2024-06-09 | SINNERS            | L   | 0.812      | -            | -                | -                | -         |   -23.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1389 | 2024-06-07 | Sangal             | L   | 0.800      | -            | -                | -                | -         |   -21.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1404 | 2024-06-07 | Verdant            | W   | 0.799      | -            | -                | -                | -         |     0.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1408 | 2024-06-07 | PERA               | W   | 0.799      | -            | -                | -                | -         |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     1455 | 2024-06-06 | RUSH B             | W   | 0.793      | -            | -                | -                | -         |     0.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     1517 | 2024-06-05 | PARIVISION         | W   | 0.787      | 0.500        | -                | 0.590 (0.232)    | -         |     2.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     1565 | 2024-06-04 | 3DMAX              | L   | 0.780      | -            | -                | -                | -         |   -12.03 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     1630 | 2024-06-01 | BLEED              | L   | 0.763      | -            | -                | -                | -         |   -17.33 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     1655 | 2024-06-01 | Lynn Vision        | W   | 0.759      | 0.500        | 0.086 (0.033)    | -                | 1 (0.759) |     1.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     1664 | 2024-05-31 | Chinggis Warriors  | W   | 0.757      | -            | -                | -                | 1 (0.757) |     1.01 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     1739 | 2024-05-29 | The MongolZ        | L   | 0.738      | -            | -                | -                | -         |    -3.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     1762 | 2024-05-28 | Lynn Vision        | W   | 0.731      | -            | -                | -                | 1 (0.731) |     1.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     1933 | 2024-05-21 | Astralis           | L   | 0.686      | -            | -                | -                | -         |    -5.48 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2064 | 2024-05-17 | SAW                | W   | 0.658      | 0.769        | 0.104 (0.053)    | 0.516 (0.261)    | -         |     2.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2079 | 2024-05-16 | PARIVISION         | W   | 0.654      | 0.769        | -                | 0.590 (0.297)    | -         |     1.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2087 | 2024-05-16 | MIBR               | L   | 0.654      | -            | -                | -                | -         |   -13.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2101 | 2024-05-16 | SAW                | L   | 0.651      | -            | -                | -                | -         |   -18.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2151 | 2024-05-15 | Spirit             | L   | 0.645      | -            | -                | -                | -         |    -2.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2294 | 2024-05-10 | MOUZ NXT           | L   | 0.614      | -            | -                | -                | -         |   -18.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2551 | 2024-04-28 | MIBR               | L   | 0.531      | -            | -                | -                | -         |   -12.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2553 | 2024-04-27 | Rebels             | W   | 0.531      | 0.500        | -                | 0.578 (0.153)    | 1 (0.531) |     0.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2579 | 2024-04-27 | Party Astronauts   | W   | 0.524      | -            | -                | -                | -         |     0.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2604 | 2024-04-25 | Apeks              | L   | 0.517      | -            | -                | -                | -         |   -15.95 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2608 | 2024-04-25 | Party Astronauts   | W   | 0.516      | -            | -                | -                | -         |     0.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2812 | 2024-04-18 | RUBY               | L   | 0.467      | -            | -                | -                | -         |   -14.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2924 | 2024-04-14 | OG                 | W   | 0.439      | 0.684        | 0.137 (0.041)    | -                | -         |     0.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     2937 | 2024-04-13 | BetBoom            | W   | 0.433      | 0.684        | 0.248 (0.073)    | -                | -         |     2.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     2949 | 2024-04-12 | AMKAL              | W   | 0.427      | -            | -                | -                | -         |     0.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     2972 | 2024-04-11 | BetBoom            | W   | 0.421      | -            | -                | -                | -         |     2.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     2979 | 2024-04-11 | Apeks              | W   | 0.420      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     2984 | 2024-04-11 | FORZE              | W   | 0.419      | -            | -                | -                | -         |     0.25 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3013 | 2024-04-10 | PARIVISION         | W   | 0.414      | -            | -                | -                | -         |     0.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3025 | 2024-04-10 | BetBoom            | L   | 0.413      | -            | -                | -                | -         |   -10.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3074 | 2024-04-09 | KOI                | L   | 0.407      | -            | -                | -                | -         |   -12.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3082 | 2024-04-09 | 1WIN               | W   | 0.406      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3090 | 2024-04-09 | 9 Pandas           | W   | 0.405      | -            | -                | -                | -         |     0.31 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3100 | 2024-04-08 | Metizport          | W   | 0.401      | -            | -                | -                | -         |     0.23 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3105 | 2024-04-08 | OG                 | W   | 0.400      | 0.684        | 0.137 (0.037)    | -                | -         |     0.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3115 | 2024-04-08 | 1WIN               | L   | 0.399      | -            | -                | -                | -         |   -12.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     3208 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.374      | -            | -                | -                | -         |     5.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     3248 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.367      | -            | -                | -                | -         |     5.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     3286 | 2024-04-02 | Apeks              | W   | 0.360      | -            | -                | -                | -         |     0.16 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     3295 | 2024-04-02 | Metizport          | W   | 0.359      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     3307 | 2024-04-01 | SINNERS            | L   | 0.354      | -            | -                | -                | -         |   -10.61 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           23 |     3346 | 2024-03-28 | brazylijski luz    | W   | 0.327      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           22 |     3377 | 2024-03-27 | Metizport          | W   | 0.321      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           21 |     3384 | 2024-03-27 | AURA               | W   | 0.321      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           20 |     3418 | 2024-03-25 | Rebels             | W   | 0.307      | -            | -                | -                | -         |     0.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           19 |     3434 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.294      | -            | -                | -                | -         |     0.19 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           18 |     3448 | 2024-03-22 | ex-Sprout          | W   | 0.287      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           17 |     3572 | 2024-03-16 | Gods Reign         | W   | 0.245      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           16 |     3593 | 2024-03-15 | Gods Reign         | W   | 0.238      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           15 |     3628 | 2024-03-14 | Bad News Kangaroos | W   | 0.231      | -            | -                | -                | -         |     0.05 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           14 |     3887 | 2024-03-04 | Young Ninjas       | L   | 0.167      | -            | -                | -                | -         |    -5.21 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           13 |     3934 | 2024-03-02 | Rebels             | W   | 0.153      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           12 |     3957 | 2024-03-01 | FORZE              | W   | 0.147      | -            | -                | -                | -         |     0.06 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           11 |     3959 | 2024-03-01 | 9 Pandas           | W   | 0.146      | -            | -                | -                | -         |     0.10 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|           10 |     3965 | 2024-02-29 | KOI                | W   | 0.141      | -            | -                | -                | -         |     0.15 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     3968 | 2024-02-29 | Spirit Academy     | W   | 0.139      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     3974 | 2024-02-29 | HAVU               | W   | 0.138      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     3977 | 2024-02-28 | kONO               | W   | 0.134      | -            | -                | -                | -         |     0.03 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     3983 | 2024-02-28 | FORZE              | L   | 0.133      | -            | -                | -                | -         |    -4.13 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4204 | 2024-02-18 | Monte              | L   | 0.068      | -            | -                | -                | -         |    -2.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4213 | 2024-02-18 | B8                 | W   | 0.066      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4231 | 2024-02-17 | kONO               | W   | 0.060      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4235 | 2024-02-17 | Monte              | L   | 0.060      | -            | -                | -                | -         |    -1.84 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4238 | 2024-02-17 | kONO               | W   | 0.059      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($134,480.82)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.42) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-16 |      0.859 | $10,000.00     | $8,593.06       |
| 2024-06-09 |      0.813 | $8,500.00      | $6,911.56       |
| 2024-06-02 |      0.765 | $15,000.00     | $11,474.65      |
| 2024-05-23 |      0.699 | $12,500.00     | $8,739.58       |
| 2024-04-28 |      0.531 | $20,000.00     | $10,625.93      |
| 2024-04-14 |      0.439 | $105,000.00    | $46,141.67      |
| 2024-03-16 |      0.245 | $28,500.00     | $6,994.38       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
