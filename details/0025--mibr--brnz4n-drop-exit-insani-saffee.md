### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1313.5<br />
<br />
Final Rank Value (1313.5) = Starting Rank Value (1414.2) + Head To Head Adjustments (-100.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.599[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.2
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1414.2


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
|           81 |       98 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           80 |      100 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      114 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.701 (0.260)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      141 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.805 (0.298)    | -         |     5.01 | brnz4n, drop, exit, insani, saffee |
|           77 |      188 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      191 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           75 |      197 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      227 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      230 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      236 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|           71 |      272 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.67 | brnz4n, drop, exit, insani, saffee |
|           70 |      297 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      303 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      393 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      394 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      657 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.15 | brnz4n, drop, exit, insani, saffee |
|           65 |      709 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.42 | brnz4n, drop, exit, insani, saffee |
|           64 |     1079 | 2024-06-15 | Complexity     | L   | 0.853      | -            | -                | -                | -         |    -6.51 | brnz4n, drop, exit, insani, saffee |
|           63 |     1105 | 2024-06-14 | Alliance       | W   | 0.848      | -            | -                | -                | 1 (0.848) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           62 |     1118 | 2024-06-14 | ENCE           | L   | 0.847      | -            | -                | -                | -         |   -15.25 | brnz4n, drop, exit, insani, saffee |
|           61 |     1360 | 2024-06-07 | Bounty Hunters | L   | 0.803      | -            | -                | -                | -         |   -24.01 | brnz4n, drop, exit, insani, saffee |
|           60 |     1421 | 2024-06-06 | 9z             | L   | 0.796      | -            | -                | -                | -         |   -11.83 | brnz4n, drop, exit, insani, saffee |
|           59 |     1489 | 2024-06-05 | BESTIA         | W   | 0.789      | 0.450        | -                | 0.776 (0.276)    | -         |     2.54 | brnz4n, drop, exit, insani, saffee |
|           58 |     1543 | 2024-06-04 | Galorys        | W   | 0.783      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1867 | 2024-05-22 | paiN           | W   | 0.695      | 0.450        | 0.324 (0.101)    | 0.838 (0.262)    | -         |     8.35 | brnz4n, drop, exit, insani, saffee |
|           56 |     1871 | 2024-05-22 | paiN           | W   | 0.695      | 0.450        | 0.324 (0.101)    | 0.838 (0.262)    | -         |     8.86 | brnz4n, drop, exit, insani, saffee |
|           55 |     1945 | 2024-05-20 | BetBoom        | L   | 0.682      | -            | -                | -                | -         |   -12.56 | brnz4n, drop, exit, insani, saffee |
|           54 |     1956 | 2024-05-20 | BIG            | W   | 0.680      | 0.769        | 0.154 (0.080)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1965 | 2024-05-20 | BetBoom        | L   | 0.679      | -            | -                | -                | -         |   -12.99 | brnz4n, drop, exit, insani, saffee |
|           52 |     2042 | 2024-05-17 | HEROIC         | L   | 0.661      | -            | -                | -                | -         |    -7.48 | brnz4n, drop, exit, insani, saffee |
|           51 |     2075 | 2024-05-16 | Aurora         | W   | 0.655      | 0.769        | 0.420 (0.212)    | 0.759 (0.382)    | 1 (0.655) |    13.66 | brnz4n, drop, exit, insani, saffee |
|           50 |     2133 | 2024-05-15 | HEROIC         | L   | 0.647      | -            | -                | -                | -         |    -7.29 | brnz4n, drop, exit, insani, saffee |
|           49 |     2539 | 2024-04-28 | Aurora         | W   | 0.532      | 0.500        | 0.420 (0.112)    | -                | 1 (0.532) |    12.29 | brnz4n, drop, exit, insani, saffee |
|           48 |     2542 | 2024-04-27 | Apeks          | W   | 0.531      | -            | -                | -                | 1 (0.531) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2568 | 2024-04-26 | Rooster        | W   | 0.525      | -            | -                | -                | 1 (0.525) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2591 | 2024-04-26 | Rebels         | L   | 0.519      | -            | -                | -                | -         |   -15.12 | brnz4n, drop, exit, insani, saffee |
|           45 |     2594 | 2024-04-25 | KZG            | W   | 0.517      | -            | -                | -                | 1 (0.517) |     0.22 | brnz4n, drop, exit, insani, saffee |
|           44 |     2704 | 2024-04-20 | paiN           | L   | 0.481      | -            | -                | -                | -         |    -8.85 | brnz4n, drop, exit, insani, saffee |
|           43 |     2713 | 2024-04-20 | OG             | W   | 0.480      | -            | -                | -                | 1 (0.480) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2726 | 2024-04-19 | paiN           | W   | 0.477      | -            | -                | -                | -         |     6.61 | brnz4n, drop, exit, insani, saffee |
|           41 |     2733 | 2024-04-19 | FURIA          | W   | 0.476      | 0.589        | 0.284 (0.080)    | -                | 1 (0.476) |    11.76 | brnz4n, drop, exit, insani, saffee |
|           40 |     2752 | 2024-04-19 | paiN           | L   | 0.475      | -            | -                | -                | -         |    -8.44 | brnz4n, drop, exit, insani, saffee |
|           39 |     2774 | 2024-04-18 | Imperial       | W   | 0.471      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           38 |     2779 | 2024-04-18 | paiN           | W   | 0.469      | -            | -                | -                | -         |     6.62 | brnz4n, drop, exit, insani, saffee |
|           37 |     2783 | 2024-04-18 | OG             | W   | 0.469      | -            | -                | -                | 1 (0.469) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2828 | 2024-04-17 | RED Canids     | W   | 0.463      | -            | -                | -                | -         |     1.88 | brnz4n, drop, exit, insani, saffee |
|           35 |     2834 | 2024-04-17 | Case           | W   | 0.462      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2873 | 2024-04-16 | Bounty Hunters | W   | 0.456      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2894 | 2024-04-15 | Imperial       | W   | 0.449      | 0.435        | 0.233 (0.045)    | -                | -         |     4.39 | brnz4n, drop, exit, insani, saffee |
|           32 |     2908 | 2024-04-14 | Galorys        | W   | 0.442      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2922 | 2024-04-13 | Case           | W   | 0.435      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2953 | 2024-04-11 | paiN           | W   | 0.423      | -            | -                | -                | -         |     6.54 | brnz4n, drop, exit, insani, saffee |
|           29 |     2991 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2995 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3012 | 2024-04-10 | Imperial       | W   | 0.414      | -            | -                | -                | -         |     4.31 | brnz4n, drop, exit, insani, saffee |
|           26 |     3043 | 2024-04-09 | adalYamigos    | W   | 0.410      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3048 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3055 | 2024-04-09 | RED Canids     | W   | 0.408      | -            | -                | -                | -         |     1.81 | brnz4n, drop, exit, insani, saffee |
|           23 |     3085 | 2024-04-08 | W7M            | W   | 0.403      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3119 | 2024-04-07 | paiN           | W   | 0.397      | -            | -                | -                | -         |     6.50 | brnz4n, drop, exit, insani, saffee |
|           21 |     3136 | 2024-04-06 | Bounty Hunters | W   | 0.390      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3153 | 2024-04-05 | Fluxo          | W   | 0.383      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3154 | 2024-04-05 | Fluxo          | L   | 0.383      | -            | -                | -                | -         |   -10.61 | brnz4n, drop, exit, insani, saffee |
|           18 |     3157 | 2024-04-05 | ODDIK          | W   | 0.382      | -            | -                | -                | -         |     0.97 | brnz4n, drop, exit, insani, saffee |
|           17 |     3178 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3184 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3217 | 2024-04-03 | Fluxo          | W   | 0.370      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3265 | 2024-04-02 | Fluxo          | W   | 0.363      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3268 | 2024-04-02 | Sharks         | W   | 0.362      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3354 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3360 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3400 | 2024-03-26 | ODDIK          | W   | 0.317      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3402 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3594 | 2024-03-14 | Sharks         | W   | 0.237      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            7 |     3596 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3668 | 2024-03-12 | Fluxo          | L   | 0.222      | -            | -                | -                | -         |    -6.16 | brnz4n, drop, exit, insani, saffee |
|            5 |     3707 | 2024-03-10 | Galorys        | W   | 0.209      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3755 | 2024-03-08 | LA RUGONETA    | W   | 0.195      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3886 | 2024-03-03 | Legacy         | L   | 0.163      | -            | -                | -                | -         |    -4.63 | brnz4n, drop, exit, insani, saffee |
|            2 |     3918 | 2024-03-02 | NRG            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     0.20 | brnz4n, drop, exit, insani, saffee |
|            1 |     3940 | 2024-03-01 | BOSS           | L   | 0.149      | -            | -                | -                | -         |    -4.54 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,517.22)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.860 | $3,000.00      | $2,581.39       |
| 2024-06-09 |      0.816 | $3,000.00      | $2,446.94       |
| 2024-04-28 |      0.532 | $50,000.00     | $26,622.69      |
| 2024-04-20 |      0.482 | $20,000.00     | $9,646.30       |
| 2024-04-15 |      0.449 | $25,000.00     | $11,219.91      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
