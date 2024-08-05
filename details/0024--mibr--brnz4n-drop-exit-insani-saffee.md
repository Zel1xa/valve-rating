### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1317.0<br />
<br />
Final Rank Value (1317.0) = Starting Rank Value (1420.2) + Head To Head Adjustments (-103.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.606[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.2
- 400 + ( ( 0.499 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1420.2


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
|           81 |       63 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.97 | brnz4n, drop, exit, insani, saffee |
|           80 |       65 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.99 | brnz4n, drop, exit, insani, saffee |
|           79 |       79 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.725 (0.269)    | -         |     7.83 | brnz4n, drop, exit, insani, saffee |
|           78 |      106 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.833 (0.309)    | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           77 |      153 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.61 | brnz4n, drop, exit, insani, saffee |
|           76 |      156 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.833 (0.375)    | -         |     5.46 | brnz4n, drop, exit, insani, saffee |
|           75 |      162 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.833 (0.375)    | -         |     5.75 | brnz4n, drop, exit, insani, saffee |
|           74 |      192 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.05 | brnz4n, drop, exit, insani, saffee |
|           73 |      195 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           72 |      201 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      237 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.65 | brnz4n, drop, exit, insani, saffee |
|           70 |      262 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      268 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.66 | brnz4n, drop, exit, insani, saffee |
|           68 |      358 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      359 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.24 | brnz4n, drop, exit, insani, saffee |
|           66 |      622 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.22 | brnz4n, drop, exit, insani, saffee |
|           65 |      674 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.44 | brnz4n, drop, exit, insani, saffee |
|           64 |     1044 | 2024-06-15 | Complexity     | L   | 0.863      | -            | -                | -                | -         |    -6.65 | brnz4n, drop, exit, insani, saffee |
|           63 |     1070 | 2024-06-14 | Alliance       | W   | 0.858      | -            | -                | -                | 1 (0.858) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1083 | 2024-06-14 | ENCE           | L   | 0.857      | -            | -                | -                | -         |   -15.75 | brnz4n, drop, exit, insani, saffee |
|           61 |     1325 | 2024-06-07 | Bounty Hunters | L   | 0.813      | -            | -                | -                | -         |   -24.32 | brnz4n, drop, exit, insani, saffee |
|           60 |     1386 | 2024-06-06 | 9z             | L   | 0.806      | -            | -                | -                | -         |   -12.06 | brnz4n, drop, exit, insani, saffee |
|           59 |     1454 | 2024-06-05 | BESTIA         | W   | 0.799      | 0.450        | -                | 0.802 (0.289)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1508 | 2024-06-04 | Galorys        | W   | 0.793      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1832 | 2024-05-22 | paiN           | W   | 0.705      | 0.450        | 0.326 (0.103)    | 0.868 (0.275)    | -         |     8.48 | brnz4n, drop, exit, insani, saffee |
|           56 |     1836 | 2024-05-22 | paiN           | W   | 0.705      | 0.450        | 0.326 (0.103)    | 0.868 (0.275)    | -         |     9.00 | brnz4n, drop, exit, insani, saffee |
|           55 |     1910 | 2024-05-20 | BetBoom        | L   | 0.692      | -            | -                | -                | -         |   -12.83 | brnz4n, drop, exit, insani, saffee |
|           54 |     1921 | 2024-05-20 | BIG            | W   | 0.690      | 0.769        | 0.155 (0.082)    | -                | -         |     6.76 | brnz4n, drop, exit, insani, saffee |
|           53 |     1930 | 2024-05-20 | BetBoom        | L   | 0.689      | -            | -                | -                | -         |   -13.28 | brnz4n, drop, exit, insani, saffee |
|           52 |     2007 | 2024-05-17 | HEROIC         | L   | 0.671      | -            | -                | -                | -         |    -7.64 | brnz4n, drop, exit, insani, saffee |
|           51 |     2040 | 2024-05-16 | Aurora         | W   | 0.665      | 0.769        | 0.423 (0.216)    | 0.792 (0.404)    | 1 (0.665) |    13.50 | brnz4n, drop, exit, insani, saffee |
|           50 |     2098 | 2024-05-15 | HEROIC         | L   | 0.657      | -            | -                | -                | -         |    -7.46 | brnz4n, drop, exit, insani, saffee |
|           49 |     2504 | 2024-04-28 | Aurora         | W   | 0.542      | 0.500        | 0.423 (0.115)    | -                | 1 (0.542) |    12.25 | brnz4n, drop, exit, insani, saffee |
|           48 |     2507 | 2024-04-27 | Apeks          | W   | 0.541      | -            | -                | -                | 1 (0.541) |     1.09 | brnz4n, drop, exit, insani, saffee |
|           47 |     2533 | 2024-04-26 | Rooster        | W   | 0.535      | -            | -                | -                | 1 (0.535) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2556 | 2024-04-26 | Rebels         | L   | 0.529      | -            | -                | -                | -         |   -15.45 | brnz4n, drop, exit, insani, saffee |
|           45 |     2559 | 2024-04-25 | KZG            | W   | 0.527      | -            | -                | -                | 1 (0.527) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2669 | 2024-04-20 | paiN           | L   | 0.491      | -            | -                | -                | -         |    -9.02 | brnz4n, drop, exit, insani, saffee |
|           43 |     2678 | 2024-04-20 | OG             | W   | 0.490      | -            | -                | -                | 1 (0.490) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           42 |     2691 | 2024-04-19 | paiN           | W   | 0.487      | -            | -                | -                | -         |     6.76 | brnz4n, drop, exit, insani, saffee |
|           41 |     2698 | 2024-04-19 | FURIA          | W   | 0.486      | 0.589        | 0.284 (0.081)    | -                | 1 (0.486) |    11.90 | brnz4n, drop, exit, insani, saffee |
|           40 |     2717 | 2024-04-19 | paiN           | L   | 0.484      | -            | -                | -                | -         |    -8.60 | brnz4n, drop, exit, insani, saffee |
|           39 |     2739 | 2024-04-18 | Imperial       | W   | 0.480      | -            | -                | -                | -         |     4.66 | brnz4n, drop, exit, insani, saffee |
|           38 |     2744 | 2024-04-18 | paiN           | W   | 0.479      | -            | -                | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           37 |     2748 | 2024-04-18 | OG             | W   | 0.479      | -            | -                | -                | 1 (0.479) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           36 |     2793 | 2024-04-17 | RED Canids     | W   | 0.473      | -            | -                | -                | -         |     1.91 | brnz4n, drop, exit, insani, saffee |
|           35 |     2799 | 2024-04-17 | Case           | W   | 0.472      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2838 | 2024-04-16 | Bounty Hunters | W   | 0.466      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2859 | 2024-04-15 | Imperial       | W   | 0.459      | 0.435        | 0.236 (0.047)    | -                | -         |     4.51 | brnz4n, drop, exit, insani, saffee |
|           32 |     2873 | 2024-04-14 | Galorys        | W   | 0.452      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2887 | 2024-04-13 | Case           | W   | 0.444      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2918 | 2024-04-11 | paiN           | W   | 0.433      | -            | -                | -                | -         |     6.72 | brnz4n, drop, exit, insani, saffee |
|           29 |     2956 | 2024-04-10 | Galorys        | W   | 0.426      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2960 | 2024-04-10 | Galorys        | W   | 0.426      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2977 | 2024-04-10 | Imperial       | W   | 0.424      | -            | -                | -                | -         |     4.45 | brnz4n, drop, exit, insani, saffee |
|           26 |     3008 | 2024-04-09 | adalYamigos    | W   | 0.420      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3013 | 2024-04-09 | adalYamigos    | W   | 0.419      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3020 | 2024-04-09 | RED Canids     | W   | 0.418      | -            | -                | -                | -         |     1.85 | brnz4n, drop, exit, insani, saffee |
|           23 |     3050 | 2024-04-08 | W7M            | W   | 0.413      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3084 | 2024-04-07 | paiN           | W   | 0.406      | -            | -                | -                | -         |     6.70 | brnz4n, drop, exit, insani, saffee |
|           21 |     3101 | 2024-04-06 | Bounty Hunters | W   | 0.399      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           20 |     3118 | 2024-04-05 | Fluxo          | W   | 0.393      | -            | -                | -                | -         |     1.60 | brnz4n, drop, exit, insani, saffee |
|           19 |     3119 | 2024-04-05 | Fluxo          | L   | 0.393      | -            | -                | -                | -         |   -10.89 | brnz4n, drop, exit, insani, saffee |
|           18 |     3122 | 2024-04-05 | ODDIK          | W   | 0.392      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3143 | 2024-04-04 | Solid          | W   | 0.386      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3149 | 2024-04-04 | Solid          | W   | 0.386      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           15 |     3182 | 2024-04-03 | Fluxo          | W   | 0.380      | -            | -                | -                | -         |     1.46 | brnz4n, drop, exit, insani, saffee |
|           14 |     3230 | 2024-04-02 | Fluxo          | W   | 0.373      | -            | -                | -                | -         |     1.42 | brnz4n, drop, exit, insani, saffee |
|           13 |     3233 | 2024-04-02 | Sharks         | W   | 0.372      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3319 | 2024-03-27 | Case           | W   | 0.333      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3325 | 2024-03-27 | Case           | W   | 0.333      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3365 | 2024-03-26 | ODDIK          | W   | 0.326      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            9 |     3367 | 2024-03-26 | ODDIK          | W   | 0.326      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            8 |     3559 | 2024-03-14 | Sharks         | W   | 0.246      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            7 |     3561 | 2024-03-14 | Sharks         | W   | 0.246      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            6 |     3633 | 2024-03-12 | Fluxo          | L   | 0.232      | -            | -                | -                | -         |    -6.44 | brnz4n, drop, exit, insani, saffee |
|            5 |     3672 | 2024-03-10 | Galorys        | W   | 0.219      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|            4 |     3720 | 2024-03-08 | LA RUGONETA    | W   | 0.205      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3851 | 2024-03-03 | Legacy         | L   | 0.172      | -            | -                | -                | -         |    -4.91 | brnz4n, drop, exit, insani, saffee |
|            2 |     3883 | 2024-03-02 | NRG            | W   | 0.165      | -            | -                | -                | 1 (0.165) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3905 | 2024-03-01 | BOSS           | L   | 0.159      | -            | -                | -                | -         |    -4.84 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,508.52)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.870 | $3,000.00      | $2,610.83       |
| 2024-06-09 |      0.825 | $3,000.00      | $2,476.39       |
| 2024-04-28 |      0.542 | $50,000.00     | $27,113.43      |
| 2024-04-20 |      0.492 | $20,000.00     | $9,842.59       |
| 2024-04-15 |      0.459 | $25,000.00     | $11,465.28      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
