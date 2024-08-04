### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1317.3<br />
<br />
Final Rank Value (1317.3) = Starting Rank Value (1423.0) + Head To Head Adjustments (-105.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.596[<sup>1</sup>](#table2)
- Bounty Collected: 0.488[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.611[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1423.0
- 400 + ( ( 0.501 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1423.0


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
|           81 |       26 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.95 | brnz4n, drop, exit, insani, saffee |
|           80 |       28 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -26.08 | brnz4n, drop, exit, insani, saffee |
|           79 |       43 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.722 (0.267)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |       69 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.829 (0.307)    | -         |     4.90 | brnz4n, drop, exit, insani, saffee |
|           77 |      114 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.60 | brnz4n, drop, exit, insani, saffee |
|           76 |      117 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.829 (0.373)    | -         |     5.35 | brnz4n, drop, exit, insani, saffee |
|           75 |      123 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.829 (0.373)    | -         |     5.63 | brnz4n, drop, exit, insani, saffee |
|           74 |      153 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.06 | brnz4n, drop, exit, insani, saffee |
|           73 |      156 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           72 |      162 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      198 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.61 | brnz4n, drop, exit, insani, saffee |
|           70 |      223 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      229 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.62 | brnz4n, drop, exit, insani, saffee |
|           68 |      319 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.21 | brnz4n, drop, exit, insani, saffee |
|           67 |      320 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           66 |      583 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.34 | brnz4n, drop, exit, insani, saffee |
|           65 |      638 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.46 | brnz4n, drop, exit, insani, saffee |
|           64 |     1004 | 2024-06-15 | Complexity     | L   | 0.870      | -            | -                | -                | -         |    -7.00 | brnz4n, drop, exit, insani, saffee |
|           63 |     1030 | 2024-06-14 | Alliance       | W   | 0.865      | -            | -                | -                | 1 (0.865) |     1.25 | brnz4n, drop, exit, insani, saffee |
|           62 |     1043 | 2024-06-14 | ENCE           | L   | 0.864      | -            | -                | -                | -         |   -16.27 | brnz4n, drop, exit, insani, saffee |
|           61 |     1285 | 2024-06-07 | Bounty Hunters | L   | 0.820      | -            | -                | -                | -         |   -24.55 | brnz4n, drop, exit, insani, saffee |
|           60 |     1346 | 2024-06-06 | 9z             | L   | 0.813      | -            | -                | -                | -         |   -12.33 | brnz4n, drop, exit, insani, saffee |
|           59 |     1414 | 2024-06-05 | BESTIA         | W   | 0.806      | 0.450        | -                | 0.799 (0.290)    | -         |     2.56 | brnz4n, drop, exit, insani, saffee |
|           58 |     1468 | 2024-06-04 | Galorys        | W   | 0.800      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           57 |     1792 | 2024-05-22 | paiN           | W   | 0.712      | 0.450        | 0.328 (0.105)    | 0.865 (0.277)    | -         |     8.56 | brnz4n, drop, exit, insani, saffee |
|           56 |     1796 | 2024-05-22 | paiN           | W   | 0.712      | 0.450        | 0.328 (0.105)    | 0.865 (0.277)    | -         |     9.10 | brnz4n, drop, exit, insani, saffee |
|           55 |     1870 | 2024-05-20 | BetBoom        | L   | 0.699      | -            | -                | -                | -         |   -12.98 | brnz4n, drop, exit, insani, saffee |
|           54 |     1881 | 2024-05-20 | BIG            | W   | 0.697      | 0.769        | 0.155 (0.083)    | -                | -         |     6.80 | brnz4n, drop, exit, insani, saffee |
|           53 |     1890 | 2024-05-20 | BetBoom        | L   | 0.696      | -            | -                | -                | -         |   -13.42 | brnz4n, drop, exit, insani, saffee |
|           52 |     1967 | 2024-05-17 | HEROIC         | L   | 0.678      | -            | -                | -                | -         |    -7.84 | brnz4n, drop, exit, insani, saffee |
|           51 |     2000 | 2024-05-16 | Aurora         | W   | 0.672      | 0.769        | 0.424 (0.219)    | 0.794 (0.410)    | 1 (0.672) |    13.47 | brnz4n, drop, exit, insani, saffee |
|           50 |     2058 | 2024-05-15 | HEROIC         | L   | 0.664      | -            | -                | -                | -         |    -7.67 | brnz4n, drop, exit, insani, saffee |
|           49 |     2464 | 2024-04-28 | Aurora         | W   | 0.549      | 0.500        | 0.424 (0.117)    | -                | 1 (0.549) |    12.29 | brnz4n, drop, exit, insani, saffee |
|           48 |     2467 | 2024-04-27 | Apeks          | W   | 0.548      | -            | -                | -                | 1 (0.548) |     1.11 | brnz4n, drop, exit, insani, saffee |
|           47 |     2493 | 2024-04-26 | Rooster        | W   | 0.542      | -            | -                | -                | 1 (0.542) |     0.45 | brnz4n, drop, exit, insani, saffee |
|           46 |     2515 | 2024-04-26 | Rebels         | L   | 0.536      | -            | -                | -                | -         |   -15.68 | brnz4n, drop, exit, insani, saffee |
|           45 |     2518 | 2024-04-25 | KZG            | W   | 0.534      | -            | -                | -                | 1 (0.534) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2628 | 2024-04-20 | paiN           | L   | 0.498      | -            | -                | -                | -         |    -9.15 | brnz4n, drop, exit, insani, saffee |
|           43 |     2637 | 2024-04-20 | OG             | W   | 0.497      | -            | -                | -                | 1 (0.497) |     1.58 | brnz4n, drop, exit, insani, saffee |
|           42 |     2650 | 2024-04-19 | paiN           | W   | 0.494      | -            | -                | -                | -         |     6.87 | brnz4n, drop, exit, insani, saffee |
|           41 |     2657 | 2024-04-19 | FURIA          | W   | 0.493      | 0.589        | 0.284 (0.082)    | -                | 1 (0.493) |    12.00 | brnz4n, drop, exit, insani, saffee |
|           40 |     2676 | 2024-04-19 | paiN           | L   | 0.492      | -            | -                | -                | -         |    -8.72 | brnz4n, drop, exit, insani, saffee |
|           39 |     2698 | 2024-04-18 | Imperial       | W   | 0.488      | -            | -                | -                | -         |     4.76 | brnz4n, drop, exit, insani, saffee |
|           38 |     2703 | 2024-04-18 | paiN           | W   | 0.486      | -            | -                | -                | -         |     6.88 | brnz4n, drop, exit, insani, saffee |
|           37 |     2707 | 2024-04-18 | OG             | W   | 0.486      | -            | -                | -                | 1 (0.486) |     1.57 | brnz4n, drop, exit, insani, saffee |
|           36 |     2752 | 2024-04-17 | RED Canids     | W   | 0.480      | -            | -                | -                | -         |     1.92 | brnz4n, drop, exit, insani, saffee |
|           35 |     2758 | 2024-04-17 | Case           | W   | 0.479      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2797 | 2024-04-16 | Bounty Hunters | W   | 0.473      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2818 | 2024-04-15 | Imperial       | W   | 0.466      | 0.435        | 0.238 (0.048)    | -                | -         |     4.61 | brnz4n, drop, exit, insani, saffee |
|           32 |     2832 | 2024-04-14 | Galorys        | W   | 0.459      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2846 | 2024-04-13 | Case           | W   | 0.452      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2877 | 2024-04-11 | paiN           | W   | 0.440      | -            | -                | -                | -         |     6.85 | brnz4n, drop, exit, insani, saffee |
|           29 |     2915 | 2024-04-10 | Galorys        | W   | 0.433      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2919 | 2024-04-10 | Galorys        | W   | 0.433      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2936 | 2024-04-10 | Imperial       | W   | 0.431      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           26 |     2967 | 2024-04-09 | adalYamigos    | W   | 0.427      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     2972 | 2024-04-09 | adalYamigos    | W   | 0.426      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     2979 | 2024-04-09 | RED Canids     | W   | 0.425      | -            | -                | -                | -         |     1.87 | brnz4n, drop, exit, insani, saffee |
|           23 |     3009 | 2024-04-08 | W7M            | W   | 0.420      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3043 | 2024-04-07 | paiN           | W   | 0.414      | -            | -                | -                | -         |     6.85 | brnz4n, drop, exit, insani, saffee |
|           21 |     3060 | 2024-04-06 | Bounty Hunters | W   | 0.407      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           20 |     3077 | 2024-04-05 | Fluxo          | W   | 0.400      | -            | -                | -                | -         |     1.62 | brnz4n, drop, exit, insani, saffee |
|           19 |     3078 | 2024-04-05 | Fluxo          | L   | 0.400      | -            | -                | -                | -         |   -11.11 | brnz4n, drop, exit, insani, saffee |
|           18 |     3081 | 2024-04-05 | ODDIK          | W   | 0.399      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           17 |     3102 | 2024-04-04 | Solid          | W   | 0.393      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           16 |     3108 | 2024-04-04 | Solid          | W   | 0.393      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           15 |     3141 | 2024-04-03 | Fluxo          | W   | 0.387      | -            | -                | -                | -         |     1.47 | brnz4n, drop, exit, insani, saffee |
|           14 |     3189 | 2024-04-02 | Fluxo          | W   | 0.380      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           13 |     3192 | 2024-04-02 | Sharks         | W   | 0.379      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3278 | 2024-03-27 | Case           | W   | 0.340      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3284 | 2024-03-27 | Case           | W   | 0.340      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           10 |     3324 | 2024-03-26 | ODDIK          | W   | 0.334      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            9 |     3326 | 2024-03-26 | ODDIK          | W   | 0.333      | -            | -                | -                | -         |     0.93 | brnz4n, drop, exit, insani, saffee |
|            8 |     3518 | 2024-03-14 | Sharks         | W   | 0.254      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|            7 |     3520 | 2024-03-14 | Sharks         | W   | 0.253      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|            6 |     3591 | 2024-03-12 | Fluxo          | L   | 0.239      | -            | -                | -                | -         |    -6.65 | brnz4n, drop, exit, insani, saffee |
|            5 |     3630 | 2024-03-10 | Galorys        | W   | 0.226      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|            4 |     3678 | 2024-03-08 | LA RUGONETA    | W   | 0.212      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3809 | 2024-03-03 | Legacy         | L   | 0.180      | -            | -                | -                | -         |    -5.12 | brnz4n, drop, exit, insani, saffee |
|            2 |     3841 | 2024-03-02 | NRG            | W   | 0.172      | -            | -                | -                | 1 (0.172) |     0.22 | brnz4n, drop, exit, insani, saffee |
|            1 |     3863 | 2024-03-01 | BOSS           | L   | 0.166      | -            | -                | -                | -         |    -5.07 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68,237.96)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.877 | $3,000.00      | $2,632.50       |
| 2024-06-09 |      0.833 | $3,000.00      | $2,498.06       |
| 2024-04-28 |      0.549 | $50,000.00     | $27,474.54      |
| 2024-04-20 |      0.499 | $20,000.00     | $9,987.04       |
| 2024-04-15 |      0.466 | $25,000.00     | $11,645.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
