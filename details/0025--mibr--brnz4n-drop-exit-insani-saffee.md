### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1314.6<br />
<br />
Final Rank Value (1314.6) = Starting Rank Value (1415.7) + Head To Head Adjustments (-101.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.301[<sup>2</sup>](#table1)
- LAN Wins: 0.599[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1415.7
- 400 + ( ( 0.495 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1415.7


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
|           81 |       91 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.98 | brnz4n, drop, exit, insani, saffee |
|           80 |       93 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      107 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.716 (0.265)    | -         |     7.85 | brnz4n, drop, exit, insani, saffee |
|           78 |      134 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.823 (0.305)    | -         |     5.02 | brnz4n, drop, exit, insani, saffee |
|           77 |      181 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      184 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.823 (0.370)    | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           75 |      190 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.823 (0.370)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      220 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      223 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      229 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      265 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.66 | brnz4n, drop, exit, insani, saffee |
|           70 |      290 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      296 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      386 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.542 (0.244)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      387 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.542 (0.244)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      650 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.15 | brnz4n, drop, exit, insani, saffee |
|           65 |      702 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.43 | brnz4n, drop, exit, insani, saffee |
|           64 |     1072 | 2024-06-15 | Complexity     | L   | 0.854      | -            | -                | -                | -         |    -6.54 | brnz4n, drop, exit, insani, saffee |
|           63 |     1098 | 2024-06-14 | Alliance       | W   | 0.849      | -            | -                | -                | 1 (0.849) |     1.25 | brnz4n, drop, exit, insani, saffee |
|           62 |     1111 | 2024-06-14 | ENCE           | L   | 0.847      | -            | -                | -                | -         |   -15.32 | brnz4n, drop, exit, insani, saffee |
|           61 |     1353 | 2024-06-07 | Bounty Hunters | L   | 0.804      | -            | -                | -                | -         |   -24.03 | brnz4n, drop, exit, insani, saffee |
|           60 |     1414 | 2024-06-06 | 9z             | L   | 0.797      | -            | -                | -                | -         |   -11.86 | brnz4n, drop, exit, insani, saffee |
|           59 |     1482 | 2024-06-05 | BESTIA         | W   | 0.790      | 0.450        | -                | 0.793 (0.282)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1536 | 2024-06-04 | Galorys        | W   | 0.783      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1860 | 2024-05-22 | paiN           | W   | 0.696      | 0.450        | 0.324 (0.101)    | 0.857 (0.268)    | -         |     8.37 | brnz4n, drop, exit, insani, saffee |
|           56 |     1864 | 2024-05-22 | paiN           | W   | 0.696      | 0.450        | 0.324 (0.101)    | 0.857 (0.268)    | -         |     8.87 | brnz4n, drop, exit, insani, saffee |
|           55 |     1938 | 2024-05-20 | BetBoom        | L   | 0.683      | -            | -                | -                | -         |   -12.60 | brnz4n, drop, exit, insani, saffee |
|           54 |     1949 | 2024-05-20 | BIG            | W   | 0.681      | 0.769        | 0.154 (0.081)    | -                | -         |     6.75 | brnz4n, drop, exit, insani, saffee |
|           53 |     1958 | 2024-05-20 | BetBoom        | L   | 0.680      | -            | -                | -                | -         |   -13.03 | brnz4n, drop, exit, insani, saffee |
|           52 |     2035 | 2024-05-17 | HEROIC         | L   | 0.662      | -            | -                | -                | -         |    -7.50 | brnz4n, drop, exit, insani, saffee |
|           51 |     2068 | 2024-05-16 | Aurora         | W   | 0.655      | 0.769        | 0.421 (0.212)    | 0.776 (0.391)    | 1 (0.655) |    13.58 | brnz4n, drop, exit, insani, saffee |
|           50 |     2126 | 2024-05-15 | HEROIC         | L   | 0.647      | -            | -                | -                | -         |    -7.31 | brnz4n, drop, exit, insani, saffee |
|           49 |     2532 | 2024-04-28 | Aurora         | W   | 0.533      | 0.500        | 0.421 (0.112)    | -                | 1 (0.533) |    12.23 | brnz4n, drop, exit, insani, saffee |
|           48 |     2535 | 2024-04-27 | Apeks          | W   | 0.531      | -            | -                | -                | 1 (0.531) |     1.07 | brnz4n, drop, exit, insani, saffee |
|           47 |     2561 | 2024-04-26 | Rooster        | W   | 0.525      | -            | -                | -                | 1 (0.525) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2584 | 2024-04-26 | Rebels         | L   | 0.519      | -            | -                | -                | -         |   -15.15 | brnz4n, drop, exit, insani, saffee |
|           45 |     2587 | 2024-04-25 | KZG            | W   | 0.518      | -            | -                | -                | 1 (0.518) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2697 | 2024-04-20 | paiN           | L   | 0.482      | -            | -                | -                | -         |    -8.86 | brnz4n, drop, exit, insani, saffee |
|           43 |     2706 | 2024-04-20 | OG             | W   | 0.481      | -            | -                | -                | 1 (0.481) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           42 |     2719 | 2024-04-19 | paiN           | W   | 0.478      | -            | -                | -                | -         |     6.62 | brnz4n, drop, exit, insani, saffee |
|           41 |     2726 | 2024-04-19 | FURIA          | W   | 0.477      | 0.589        | 0.284 (0.080)    | -                | 1 (0.477) |    11.77 | brnz4n, drop, exit, insani, saffee |
|           40 |     2745 | 2024-04-19 | paiN           | L   | 0.475      | -            | -                | -                | -         |    -8.45 | brnz4n, drop, exit, insani, saffee |
|           39 |     2767 | 2024-04-18 | Imperial       | W   | 0.471      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           38 |     2772 | 2024-04-18 | paiN           | W   | 0.470      | -            | -                | -                | -         |     6.63 | brnz4n, drop, exit, insani, saffee |
|           37 |     2776 | 2024-04-18 | OG             | W   | 0.470      | -            | -                | -                | 1 (0.470) |     1.53 | brnz4n, drop, exit, insani, saffee |
|           36 |     2821 | 2024-04-17 | RED Canids     | W   | 0.463      | -            | -                | -                | -         |     1.89 | brnz4n, drop, exit, insani, saffee |
|           35 |     2827 | 2024-04-17 | Case           | W   | 0.463      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2866 | 2024-04-16 | Bounty Hunters | W   | 0.457      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2887 | 2024-04-15 | Imperial       | W   | 0.449      | 0.435        | 0.233 (0.046)    | -                | -         |     4.39 | brnz4n, drop, exit, insani, saffee |
|           32 |     2901 | 2024-04-14 | Galorys        | W   | 0.443      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2915 | 2024-04-13 | Case           | W   | 0.435      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2946 | 2024-04-11 | paiN           | W   | 0.424      | -            | -                | -                | -         |     6.55 | brnz4n, drop, exit, insani, saffee |
|           29 |     2984 | 2024-04-10 | Galorys        | W   | 0.417      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2988 | 2024-04-10 | Galorys        | W   | 0.417      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3005 | 2024-04-10 | Imperial       | W   | 0.415      | -            | -                | -                | -         |     4.31 | brnz4n, drop, exit, insani, saffee |
|           26 |     3036 | 2024-04-09 | adalYamigos    | W   | 0.410      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3041 | 2024-04-09 | adalYamigos    | W   | 0.410      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3048 | 2024-04-09 | RED Canids     | W   | 0.409      | -            | -                | -                | -         |     1.82 | brnz4n, drop, exit, insani, saffee |
|           23 |     3078 | 2024-04-08 | W7M            | W   | 0.404      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3112 | 2024-04-07 | paiN           | W   | 0.397      | -            | -                | -                | -         |     6.52 | brnz4n, drop, exit, insani, saffee |
|           21 |     3129 | 2024-04-06 | Bounty Hunters | W   | 0.390      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3146 | 2024-04-05 | Fluxo          | W   | 0.384      | -            | -                | -                | -         |     1.58 | brnz4n, drop, exit, insani, saffee |
|           19 |     3147 | 2024-04-05 | Fluxo          | L   | 0.383      | -            | -                | -                | -         |   -10.63 | brnz4n, drop, exit, insani, saffee |
|           18 |     3150 | 2024-04-05 | ODDIK          | W   | 0.382      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3171 | 2024-04-04 | Solid          | W   | 0.377      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3177 | 2024-04-04 | Solid          | W   | 0.377      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3210 | 2024-04-03 | Fluxo          | W   | 0.370      | -            | -                | -                | -         |     1.44 | brnz4n, drop, exit, insani, saffee |
|           14 |     3258 | 2024-04-02 | Fluxo          | W   | 0.364      | -            | -                | -                | -         |     1.40 | brnz4n, drop, exit, insani, saffee |
|           13 |     3261 | 2024-04-02 | Sharks         | W   | 0.363      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3347 | 2024-03-27 | Case           | W   | 0.324      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3353 | 2024-03-27 | Case           | W   | 0.324      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3393 | 2024-03-26 | ODDIK          | W   | 0.317      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3395 | 2024-03-26 | ODDIK          | W   | 0.317      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3587 | 2024-03-14 | Sharks         | W   | 0.237      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            7 |     3589 | 2024-03-14 | Sharks         | W   | 0.237      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3661 | 2024-03-12 | Fluxo          | L   | 0.223      | -            | -                | -                | -         |    -6.17 | brnz4n, drop, exit, insani, saffee |
|            5 |     3700 | 2024-03-10 | Galorys        | W   | 0.210      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3748 | 2024-03-08 | LA RUGONETA    | W   | 0.196      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3879 | 2024-03-03 | Legacy         | L   | 0.163      | -            | -                | -                | -         |    -4.65 | brnz4n, drop, exit, insani, saffee |
|            2 |     3911 | 2024-03-02 | NRG            | W   | 0.156      | -            | -                | -                | 1 (0.156) |     0.20 | brnz4n, drop, exit, insani, saffee |
|            1 |     3933 | 2024-03-01 | BOSS           | L   | 0.150      | -            | -                | -                | -         |    -4.56 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,582.69)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $3,000.00      | $2,583.33       |
| 2024-06-09 |      0.816 | $3,000.00      | $2,448.89       |
| 2024-04-28 |      0.533 | $50,000.00     | $26,655.09      |
| 2024-04-20 |      0.483 | $20,000.00     | $9,659.26       |
| 2024-04-15 |      0.449 | $25,000.00     | $11,236.11      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
