### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
<br />
Final Rank Value:  841.7<br />
<br />
Final Rank Value (841.7) = Starting Rank Value (903.0) + Head To Head Adjustments (-61.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.367[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 903.0
- 400 + ( ( 0.244 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 903.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           95 |       40 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.731 (0.329)    | 0 (0.000) |    23.67 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |       46 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      143 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      161 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.030 (0.011)    | 0.720 (0.263)    | 0 (0.000) |    19.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      205 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      206 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      278 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.81 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      328 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      368 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -13.75 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      447 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.74 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      498 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.99 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      501 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.32 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      514 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      566 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      587 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -18.08 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      612 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -7.75 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      618 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.048 (0.022)    | 0.419 (0.189)    | 0 (0.000) |    24.30 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      694 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -13.69 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      713 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      755 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.06 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      785 | 2024-06-30 | Vikings KR        | L   | 0.992      | -            | -                | -                | -         |   -16.76 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      792 | 2024-06-29 | inSanitY          | L   | 0.986      | -            | -                | -                | -         |    -8.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      803 | 2024-06-27 | Sharks            | L   | 0.974      | -            | -                | -                | -         |    -8.64 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |      805 | 2024-06-27 | KRÜ               | W   | 0.973      | -            | -                | -                | 0 (0.000) |    15.82 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |      828 | 2024-06-18 | inSanitY          | L   | 0.914      | -            | -                | -                | -         |    -9.25 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1055 | 2024-06-09 | ODDIK             | L   | 0.854      | -            | -                | -                | -         |   -10.83 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1149 | 2024-06-08 | Case              | W   | 0.845      | 0.450        | 0.030 (0.011)    | 0.720 (0.274)    | 0 (0.000) |    13.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1178 | 2024-06-07 | Imperial          | L   | 0.840      | -            | -                | -                | -         |    -2.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1206 | 2024-06-07 | W7M               | L   | 0.838      | -            | -                | -                | -         |   -16.10 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1224 | 2024-06-06 | paiN              | L   | 0.835      | -            | -                | -                | -         |    -1.75 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           65 |     1237 | 2024-06-06 | ex-Corinthians    | W   | 0.834      | -            | -                | -                | -         |     3.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1355 | 2024-06-04 | MIBR              | L   | 0.821      | -            | -                | -                | -         |    -0.95 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           63 |     1394 | 2024-06-03 | Intense           | L   | 0.813      | -            | -                | -                | -         |   -17.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1442 | 2024-06-01 | Hype              | L   | 0.799      | -            | -                | -                | -         |   -12.99 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1495 | 2024-05-30 | Hawks             | W   | 0.787      | -            | -                | -                | -         |     3.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           60 |     1581 | 2024-05-27 | Dusty Roots       | W   | 0.765      | -            | -                | -                | -         |     9.99 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           59 |     1761 | 2024-05-20 | Case              | L   | 0.719      | -            | -                | -                | -         |   -10.80 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     1786 | 2024-05-19 | Solid             | W   | 0.713      | 0.303        | -                | 0.817 (0.176)    | -         |    10.80 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     1812 | 2024-05-18 | ODDIK             | L   | 0.706      | -            | -                | -                | -         |    -9.24 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     1928 | 2024-05-15 | Hype              | W   | 0.687      | -            | -                | -                | -         |    10.89 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     1937 | 2024-05-15 | Case              | L   | 0.686      | -            | -                | -                | -         |   -11.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     1978 | 2024-05-14 | Case              | L   | 0.681      | -            | -                | -                | -         |   -11.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     1983 | 2024-05-14 | Case              | W   | 0.680      | 0.450        | 0.030 (0.009)    | 0.720 (0.221)    | -         |     9.67 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     1995 | 2024-05-14 | 9z                | L   | 0.679      | -            | -                | -                | -         |    -0.62 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2014 | 2024-05-13 | 9z                | L   | 0.674      | -            | -                | -                | -         |    -0.62 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2019 | 2024-05-13 | Yawara            | W   | 0.673      | -            | -                | -                | -         |     2.14 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2039 | 2024-05-12 | KRÜ               | W   | 0.666      | -            | -                | -                | -         |    11.07 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2078 | 2024-05-11 | Case              | W   | 0.659      | 0.384        | -                | 0.720 (0.182)    | -         |    10.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2137 | 2024-05-08 | paiN              | L   | 0.640      | -            | -                | -                | -         |    -0.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2140 | 2024-05-08 | paiN              | L   | 0.639      | -            | -                | -                | -         |    -0.95 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2162 | 2024-05-07 | KRÜ               | L   | 0.632      | -            | -                | -                | -         |    -9.81 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2197 | 2024-05-05 | W7M               | L   | 0.618      | -            | -                | -                | -         |   -11.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2505 | 2024-04-20 | Solid             | W   | 0.521      | 0.450        | -                | 0.817 (0.192)    | -         |     7.88 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2506 | 2024-04-20 | Solid             | L   | 0.520      | -            | -                | -                | -         |    -8.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2682 | 2024-04-16 | Case              | L   | 0.494      | -            | -                | -                | -         |    -7.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2720 | 2024-04-14 | MIBR              | L   | 0.480      | -            | -                | -                | -         |    -0.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2739 | 2024-04-13 | Fluxo             | W   | 0.472      | 0.435        | 0.126 (0.026)    | -                | -         |    10.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2748 | 2024-04-12 | Sharks            | W   | 0.467      | -            | -                | -                | -         |     4.99 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2768 | 2024-04-11 | Vikings KR        | L   | 0.460      | -            | -                | -                | -         |    -8.80 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2775 | 2024-04-11 | BESTIA            | W   | 0.459      | 0.435        | 0.095 (0.019)    | 0.731 (0.146)    | -         |     8.64 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2803 | 2024-04-10 | MIBR              | L   | 0.454      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2807 | 2024-04-10 | MIBR              | L   | 0.454      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     2857 | 2024-04-09 | BESTIA            | W   | 0.447      | 0.450        | 0.095 (0.019)    | 0.731 (0.147)    | -         |     8.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     2862 | 2024-04-09 | BESTIA            | L   | 0.447      | -            | -                | -                | -         |    -5.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     2935 | 2024-04-07 | paiN              | L   | 0.433      | -            | -                | -                | -         |    -0.61 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3165 | 2024-03-27 | Fluxo             | W   | 0.361      | 0.450        | 0.126 (0.020)    | -                | -         |     8.10 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3171 | 2024-03-27 | Fluxo             | L   | 0.361      | -            | -                | -                | -         |    -3.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3211 | 2024-03-26 | 2GAME             | W   | 0.354      | -            | -                | -                | -         |     2.73 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3213 | 2024-03-26 | 2GAME             | W   | 0.354      | -            | -                | -                | -         |     2.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3407 | 2024-03-14 | W7M               | W   | 0.274      | -            | -                | -                | -         |     3.63 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3409 | 2024-03-14 | W7M               | W   | 0.274      | -            | -                | -                | -         |     3.72 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3453 | 2024-03-13 | RED Canids        | L   | 0.266      | -            | -                | -                | -         |    -2.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3497 | 2024-03-11 | LA RUGONETA       | L   | 0.253      | -            | -                | -                | -         |    -6.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3519 | 2024-03-10 | MIBR              | L   | 0.247      | -            | -                | -                | -         |    -0.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3577 | 2024-03-08 | ODDIK             | W   | 0.232      | 0.435        | 0.097 (0.010)    | -                | -         |     4.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     3858 | 2024-02-24 | Sharks            | L   | 0.148      | -            | -                | -                | -         |    -1.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     3866 | 2024-02-24 | Sharks            | L   | 0.147      | -            | -                | -                | -         |    -1.81 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     3889 | 2024-02-23 | Corinthians       | L   | 0.141      | -            | -                | -                | -         |    -3.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     3890 | 2024-02-23 | Corinthians       | W   | 0.140      | -            | -                | -                | -         |     0.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     3907 | 2024-02-22 | MIBR Academy      | W   | 0.134      | -            | -                | -                | -         |     0.45 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     3922 | 2024-02-21 | adalYamigos       | L   | 0.128      | -            | -                | -                | -         |    -3.40 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     3926 | 2024-02-21 | adalYamigos       | L   | 0.127      | -            | -                | -                | -         |    -3.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     3933 | 2024-02-21 | Sharks            | L   | 0.125      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4001 | 2024-02-18 | Sharks            | L   | 0.108      | -            | -                | -                | -         |    -1.39 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4003 | 2024-02-18 | Case              | W   | 0.106      | -            | -                | -                | -         |     1.91 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4029 | 2024-02-17 | Sharks            | W   | 0.100      | -            | -                | -                | -         |     1.88 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4032 | 2024-02-17 | Corinthians       | W   | 0.099      | -            | -                | -                | -         |     0.32 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4053 | 2024-02-16 | Flamengo          | W   | 0.094      | -            | -                | -                | -         |     0.28 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4056 | 2024-02-16 | Imperial          | L   | 0.093      | -            | -                | -                | -         |    -0.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4061 | 2024-02-16 | Imperial          | L   | 0.092      | -            | -                | -                | -         |    -0.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4087 | 2024-02-15 | 9z Academy        | W   | 0.086      | -            | -                | -                | -         |     0.27 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4114 | 2024-02-14 | Solid             | L   | 0.081      | -            | -                | -                | -         |    -1.29 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4128 | 2024-02-14 | Sharks            | L   | 0.079      | -            | -                | -                | -         |    -1.00 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4163 | 2024-02-13 | Case              | L   | 0.073      | -            | -                | -                | -         |    -1.01 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4173 | 2024-02-12 | inSanitY          | W   | 0.067      | -            | -                | -                | -         |     0.12 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,951.74)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.920 | $1,075.00      | $988.89         |
| 2024-06-09 |      0.853 | $1,500.00      | $1,280.12       |
| 2024-04-15 |      0.487 | $5,000.00      | $2,432.80       |
| 2024-04-11 |      0.460 | $592.00        | $272.59         |
| 2024-02-22 |      0.134 | $1,417.00      | $189.18         |
| 2024-02-21 |      0.125 | $1,500.00      | $188.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
