### Roster Details<br />
Team Name: Imperial<br />
Roster: decenty, felps, noway, try, VINI<br />
Global Rank: [30](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1222.5<br />
<br />
Final Rank Value (1222.5) = Starting Rank Value (1256.3) + Head To Head Adjustments (-33.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.612[<sup>1</sup>](#table2)
- Bounty Collected: 0.496[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.339[<sup>2</sup>](#table1)

The average of these factors is 0.416<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1256.3
- 400 + ( ( 0.416 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1256.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          100 |      279 | 2024-07-29 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -9.60 | decenty, felps, noway, try, VINI  |
|           99 |      283 | 2024-07-29 | MIBR              | W   | 1.000      | -            | -                | -                | -         |    21.67 | decenty, felps, noway, try, VINI  |
|           98 |      307 | 2024-07-28 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -9.51 | decenty, felps, noway, try, VINI  |
|           97 |      314 | 2024-07-28 | MIBR              | W   | 1.000      | -            | -                | -                | -         |    22.68 | decenty, felps, noway, try, VINI  |
|           96 |      361 | 2024-07-26 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |    13.96 | decenty, felps, noway, try, VINI  |
|           95 |      364 | 2024-07-26 | Sharks            | W   | 1.000      | -            | -                | -                | -         |     8.58 | decenty, felps, noway, try, VINI  |
|           94 |      393 | 2024-07-25 | Solid             | W   | 1.000      | -            | -                | -                | -         |     6.65 | decenty, felps, noway, try, VINI  |
|           93 |      396 | 2024-07-25 | Yawara            | W   | 1.000      | -            | -                | -                | -         |     0.72 | decenty, felps, noway, try, VINI  |
|           92 |      466 | 2024-07-23 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -25.24 | decenty, felps, noway, try, VINI  |
|           91 |      474 | 2024-07-23 | Atrix             | W   | 1.000      | -            | -                | -                | -         |     1.41 | decenty, felps, noway, try, VINI  |
|           90 |      561 | 2024-07-20 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -8.91 | decenty, felps, noway, try, VINI  |
|           89 |      641 | 2024-07-18 | BESTIA            | W   | 1.000      | -            | -                | -                | -         |     7.28 | decenty, felps, noway, try, VINI  |
|           88 |      651 | 2024-07-18 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -22.42 | decenty, felps, noway, try, VINI  |
|           87 |      657 | 2024-07-18 | Amigos de T2M4SS  | W   | 1.000      | -            | -                | -                | -         |     0.32 | decenty, felps, noway, try, VINI  |
|           86 |      701 | 2024-07-17 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |     4.14 | decenty, felps, noway, try, VINI  |
|           85 |      708 | 2024-07-17 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |     4.32 | decenty, felps, noway, try, VINI  |
|           84 |      821 | 2024-07-15 | Case              | L   | 1.000      | -            | -                | -                | -         |   -26.68 | decenty, felps, noway, VINI, zakk |
|           83 |      827 | 2024-07-15 | Case              | L   | 1.000      | -            | -                | -                | -         |   -27.81 | decenty, felps, noway, VINI, zakk |
|           82 |     1079 | 2024-06-15 | fnatic            | L   | 0.853      | -            | -                | -                | -         |    -7.19 | decenty, felps, HEN1, noway, VINI |
|           81 |     1103 | 2024-06-14 | KOI               | L   | 0.848      | -            | -                | -                | -         |   -20.28 | decenty, felps, HEN1, noway, VINI |
|           80 |     1231 | 2024-06-10 | paiN              | L   | 0.819      | -            | -                | -                | -         |   -11.05 | decenty, felps, HEN1, noway, VINI |
|           79 |     1257 | 2024-06-09 | RED Canids        | W   | 0.814      | 0.450        | -                | 0.732 (0.268)    | -         |     8.62 | decenty, felps, HEN1, noway, VINI |
|           78 |     1274 | 2024-06-09 | ODDIK             | W   | 0.813      | 0.371        | 0.099 (0.030)    | 0.805 (0.242)    | -         |     3.10 | decenty, felps, HEN1, noway, VINI |
|           77 |     1317 | 2024-06-08 | 9z                | W   | 0.808      | 0.450        | 0.404 (0.147)    | 0.591 (0.215)    | -         |    18.86 | decenty, felps, HEN1, noway, VINI |
|           76 |     1377 | 2024-06-07 | Galorys           | W   | 0.801      | -            | -                | -                | -         |     2.38 | decenty, felps, HEN1, noway, VINI |
|           75 |     1430 | 2024-06-06 | RED Canids        | L   | 0.795      | -            | -                | -                | -         |   -16.34 | decenty, felps, HEN1, noway, VINI |
|           74 |     1502 | 2024-06-05 | Sharks            | W   | 0.788      | 0.450        | -                | 0.547 (0.194)    | -         |     4.88 | decenty, felps, HEN1, noway, VINI |
|           73 |     1867 | 2024-05-22 | 9z                | W   | 0.695      | 0.450        | 0.404 (0.126)    | 0.591 (0.185)    | -         |    15.59 | decenty, felps, HEN1, noway, VINI |
|           72 |     1871 | 2024-05-22 | 9z                | W   | 0.695      | 0.450        | 0.404 (0.126)    | -                | -         |    16.36 | decenty, felps, HEN1, noway, VINI |
|           71 |     1879 | 2024-05-22 | Sharks            | L   | 0.694      | -            | -                | -                | -         |   -17.59 | decenty, felps, HEN1, noway, VINI |
|           70 |     1883 | 2024-05-22 | Sharks            | W   | 0.694      | -            | -                | -                | -         |     4.15 | decenty, felps, HEN1, noway, VINI |
|           69 |     1919 | 2024-05-21 | BESTIA            | L   | 0.688      | -            | -                | -                | -         |   -17.50 | decenty, felps, HEN1, noway, VINI |
|           68 |     1920 | 2024-05-21 | BESTIA            | L   | 0.687      | -            | -                | -                | -         |   -18.12 | decenty, felps, HEN1, noway, VINI |
|           67 |     2082 | 2024-05-16 | 9z                | W   | 0.654      | 0.384        | 0.404 (0.101)    | -                | -         |    15.75 | decenty, felps, HEN1, noway, VINI |
|           66 |     2137 | 2024-05-15 | Fluxo             | W   | 0.647      | 0.384        | 0.123 (0.031)    | -                | -         |     5.70 | decenty, felps, HEN1, noway, VINI |
|           65 |     2172 | 2024-05-14 | W7M               | W   | 0.642      | -            | -                | -                | -         |     1.37 | decenty, felps, HEN1, noway, VINI |
|           64 |     2175 | 2024-05-14 | W7M               | W   | 0.642      | -            | -                | -                | -         |     1.39 | decenty, felps, HEN1, noway, VINI |
|           63 |     2186 | 2024-05-14 | BESTIA            | W   | 0.641      | 0.384        | -                | 0.776 (0.191)    | -         |     3.18 | decenty, felps, HEN1, noway, VINI |
|           62 |     2223 | 2024-05-13 | KRÜ               | W   | 0.633      | -            | -                | -                | -         |     2.44 | decenty, felps, HEN1, noway, VINI |
|           61 |     2294 | 2024-05-10 | BESTIA            | L   | 0.614      | -            | -                | -                | -         |   -16.55 | decenty, felps, HEN1, noway, VINI |
|           60 |     2352 | 2024-05-07 | ODDIK             | W   | 0.595      | 0.435        | -                | 0.805 (0.208)    | -         |     2.95 | decenty, felps, HEN1, noway, VINI |
|           59 |     2389 | 2024-05-05 | inSanitY          | W   | 0.580      | -            | -                | -                | -         |     2.13 | decenty, felps, HEN1, noway, VINI |
|           58 |     2591 | 2024-04-26 | SAW               | L   | 0.519      | -            | -                | -                | -         |   -10.81 | decenty, felps, HEN1, noway, VINI |
|           57 |     2634 | 2024-04-24 | Eternal Fire      | L   | 0.507      | -            | -                | -                | -         |    -1.53 | decenty, felps, HEN1, noway, VINI |
|           56 |     2653 | 2024-04-23 | FaZe              | L   | 0.500      | -            | -                | -                | -         |    -1.37 | decenty, felps, HEN1, noway, VINI |
|           55 |     2706 | 2024-04-20 | paiN              | L   | 0.481      | -            | -                | -                | -         |    -5.38 | decenty, felps, HEN1, noway, VINI |
|           54 |     2736 | 2024-04-19 | paiN              | W   | 0.477      | 0.589        | 0.324 (0.091)    | 0.839 (0.235)    | 1 (0.477) |     9.74 | decenty, felps, HEN1, noway, VINI |
|           53 |     2749 | 2024-04-19 | paiN              | L   | 0.474      | -            | -                | -                | -         |    -5.18 | decenty, felps, HEN1, noway, VINI |
|           52 |     2785 | 2024-04-18 | MIBR              | L   | 0.469      | -            | -                | -                | -         |    -4.54 | decenty, felps, HEN1, noway, VINI |
|           51 |     2789 | 2024-04-18 | 9z                | W   | 0.469      | 0.589        | 0.404 (0.111)    | -                | 1 (0.469) |    11.97 | decenty, felps, HEN1, noway, VINI |
|           50 |     2793 | 2024-04-18 | Fluxo             | W   | 0.468      | -            | -                | -                | -         |     3.57 | decenty, felps, HEN1, noway, VINI |
|           49 |     2804 | 2024-04-18 | Metizport         | W   | 0.467      | -            | -                | -                | 1 (0.467) |     1.94 | decenty, felps, HEN1, noway, VINI |
|           48 |     2905 | 2024-04-15 | MIBR              | L   | 0.448      | -            | -                | -                | -         |    -4.38 | decenty, felps, HEN1, noway, VINI |
|           47 |     2920 | 2024-04-14 | paiN              | W   | 0.440      | 0.435        | 0.324 (0.062)    | -                | -         |     9.32 | decenty, felps, HEN1, noway, VINI |
|           46 |     2930 | 2024-04-13 | RED Canids        | W   | 0.435      | -            | -                | -                | -         |     3.68 | decenty, felps, HEN1, noway, VINI |
|           45 |     2966 | 2024-04-11 | adalYamigos       | W   | 0.422      | -            | -                | -                | -         |     0.35 | decenty, felps, HEN1, noway, VINI |
|           44 |     2976 | 2024-04-11 | paiN              | L   | 0.420      | -            | -                | -                | -         |    -4.24 | decenty, felps, HEN1, noway, VINI |
|           43 |     3004 | 2024-04-10 | Fluxo             | L   | 0.415      | -            | -                | -                | -         |   -10.05 | decenty, felps, HEN1, noway, VINI |
|           42 |     3007 | 2024-04-10 | Fluxo             | W   | 0.415      | -            | -                | -                | -         |     3.04 | decenty, felps, HEN1, noway, VINI |
|           41 |     3023 | 2024-04-10 | MIBR              | L   | 0.413      | -            | -                | -                | -         |    -4.29 | decenty, felps, HEN1, noway, VINI |
|           40 |     3064 | 2024-04-09 | Solid             | W   | 0.408      | -            | -                | -                | -         |     1.28 | decenty, felps, HEN1, noway, VINI |
|           39 |     3065 | 2024-04-09 | Solid             | W   | 0.407      | -            | -                | -                | -         |     1.29 | decenty, felps, HEN1, noway, VINI |
|           38 |     3078 | 2024-04-09 | paiN              | W   | 0.406      | -            | -                | -                | -         |     8.70 | decenty, felps, HEN1, noway, VINI |
|           37 |     3133 | 2024-04-07 | RED Canids        | W   | 0.395      | -            | -                | -                | -         |     3.18 | decenty, felps, HEN1, noway, VINI |
|           36 |     3136 | 2024-04-07 | FURIA Academy     | W   | 0.393      | -            | -                | -                | -         |     0.18 | decenty, felps, HEN1, noway, VINI |
|           35 |     3193 | 2024-04-04 | ODDIK             | W   | 0.375      | -            | -                | -                | -         |     1.93 | decenty, felps, HEN1, noway, VINI |
|           34 |     3199 | 2024-04-04 | ODDIK             | W   | 0.375      | -            | -                | -                | -         |     1.96 | decenty, felps, HEN1, noway, VINI |
|           33 |     3202 | 2024-04-04 | BESTIA            | W   | 0.374      | -            | -                | -                | -         |     2.14 | decenty, felps, HEN1, noway, VINI |
|           32 |     3231 | 2024-04-03 | Case              | W   | 0.368      | -            | -                | -                | -         |     1.43 | decenty, felps, HEN1, noway, VINI |
|           31 |     3234 | 2024-04-03 | Case              | W   | 0.368      | -            | -                | -                | -         |     1.45 | decenty, felps, HEN1, noway, VINI |
|           30 |     3439 | 2024-03-23 | FaZe              | L   | 0.292      | -            | -                | -                | -         |    -0.84 | decenty, felps, HEN1, noway, VINI |
|           29 |     3452 | 2024-03-22 | Vitality          | L   | 0.286      | -            | -                | -                | -         |    -0.33 | decenty, felps, HEN1, noway, VINI |
|           28 |     3462 | 2024-03-21 | Spirit            | L   | 0.281      | -            | -                | -                | -         |    -0.24 | decenty, felps, HEN1, noway, VINI |
|           27 |     3479 | 2024-03-21 | Virtus.pro        | W   | 0.279      | 1.000        | 0.499 (0.139)    | -                | 1 (0.279) |     8.12 | decenty, felps, HEN1, noway, VINI |
|           26 |     3499 | 2024-03-20 | GamerLegion       | W   | 0.273      | -            | -                | -                | 1 (0.273) |     0.58 | decenty, felps, HEN1, noway, VINI |
|           25 |     3512 | 2024-03-19 | Gaimin Gladiators | L   | 0.267      | -            | -                | -                | -         |    -6.96 | decenty, felps, HEN1, noway, VINI |
|           24 |     3528 | 2024-03-18 | Apeks             | W   | 0.259      | -            | -                | -                | 1 (0.259) |     1.00 | decenty, felps, HEN1, noway, VINI |
|           23 |     3544 | 2024-03-17 | HEROIC            | L   | 0.254      | -            | -                | -                | -         |    -1.29 | decenty, felps, HEN1, noway, VINI |
|           22 |     3556 | 2024-03-17 | ENCE              | W   | 0.252      | -            | -                | -                | 1 (0.252) |     6.13 | decenty, felps, HEN1, noway, VINI |
|           21 |     3786 | 2024-03-07 | Monte             | L   | 0.188      | -            | -                | -                | -         |    -4.86 | decenty, felps, HEN1, noway, VINI |
|           20 |     3908 | 2024-03-03 | paiN              | W   | 0.160      | -            | -                | -                | 1 (0.160) |     3.50 | decenty, felps, HEN1, noway, VINI |
|           19 |     3931 | 2024-03-02 | M80               | W   | 0.153      | -            | -                | -                | 1 (0.153) |     2.21 | decenty, felps, HEN1, noway, VINI |
|           18 |     3948 | 2024-03-01 | NRG               | W   | 0.148      | -            | -                | -                | 1 (0.148) |     0.44 | decenty, felps, HEN1, noway, VINI |
|           17 |     4039 | 2024-02-25 | Fluxo             | L   | 0.114      | -            | -                | -                | -         |    -2.75 | decenty, felps, HEN1, noway, VINI |
|           16 |     4071 | 2024-02-24 | BESTIA            | W   | 0.107      | -            | -                | -                | -         |     0.71 | decenty, felps, HEN1, noway, VINI |
|           15 |     4100 | 2024-02-22 | BESTIA            | L   | 0.095      | -            | -                | -                | -         |    -2.38 | decenty, felps, HEN1, noway, VINI |
|           14 |     4108 | 2024-02-22 | FURIA             | L   | 0.094      | -            | -                | -                | -         |    -0.21 | decenty, felps, HEN1, noway, VINI |
|           13 |     4123 | 2024-02-21 | 2GAME             | W   | 0.089      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           12 |     4126 | 2024-02-21 | 2GAME             | W   | 0.088      | -            | -                | -                | -         |     0.10 | decenty, felps, HEN1, noway, VINI |
|           11 |     4136 | 2024-02-21 | LA RUGONETA       | W   | 0.086      | -            | -                | -                | -         |     0.05 | decenty, felps, HEN1, noway, VINI |
|           10 |     4227 | 2024-02-17 | adalYamigos       | W   | 0.061      | -            | -                | -                | -         |     0.04 | decenty, felps, HEN1, noway, VINI |
|            9 |     4255 | 2024-02-16 | Galorys           | W   | 0.054      | -            | -                | -                | -         |     0.20 | decenty, felps, HEN1, noway, VINI |
|            8 |     4260 | 2024-02-16 | Galorys           | W   | 0.053      | -            | -                | -                | -         |     0.20 | decenty, felps, HEN1, noway, VINI |
|            7 |     4278 | 2024-02-15 | 9z                | W   | 0.049      | -            | -                | -                | -         |     1.28 | decenty, felps, HEN1, noway, VINI |
|            6 |     4280 | 2024-02-15 | Fluxo             | W   | 0.048      | -            | -                | -                | -         |     0.36 | decenty, felps, HEN1, noway, VINI |
|            5 |     4284 | 2024-02-15 | Solid             | W   | 0.048      | -            | -                | -                | -         |     0.18 | decenty, felps, HEN1, noway, VINI |
|            4 |     4314 | 2024-02-14 | Yawara            | W   | 0.042      | -            | -                | -                | -         |     0.02 | decenty, felps, HEN1, noway, VINI |
|            3 |     4351 | 2024-02-13 | RED Canids        | W   | 0.036      | -            | -                | -                | -         |     0.30 | decenty, felps, HEN1, noway, VINI |
|            2 |     4354 | 2024-02-13 | RED Canids        | L   | 0.035      | -            | -                | -                | -         |    -0.82 | decenty, felps, HEN1, noway, VINI |
|            1 |     4361 | 2024-02-13 | Solid             | W   | 0.034      | -            | -                | -                | -         |     0.13 | decenty, felps, HEN1, noway, VINI |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74,548.07)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.862 | $1,500.00      | $1,292.99       |
| 2024-06-10 |      0.822 | $1,500.00      | $1,232.53       |
| 2024-06-09 |      0.814 | $20,000.00     | $16,289.81      |
| 2024-05-16 |      0.654 | $20,000.00     | $13,075.00      |
| 2024-05-12 |      0.626 | $3,500.00      | $2,191.88       |
| 2024-04-20 |      0.481 | $50,000.00     | $24,057.87      |
| 2024-04-15 |      0.448 | $15,000.00     | $6,714.58       |
| 2024-03-31 |      0.347 | $20,000.00     | $6,941.67       |
| 2024-03-10 |      0.207 | $5,000.00      | $1,037.15       |
| 2024-02-25 |      0.114 | $15,000.00     | $1,714.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
