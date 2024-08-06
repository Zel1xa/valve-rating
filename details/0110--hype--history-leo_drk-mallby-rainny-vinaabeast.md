### Roster Details<br />
Team Name: Hype<br />
Roster: history, leo_drk, MaLLby, rainny, vinaabEAST<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  838.0<br />
<br />
Final Rank Value (838.0) = Starting Rank Value (880.5) + Head To Head Adjustments (-42.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.234<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 880.5
- 400 + ( ( 0.234 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 880.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      131 | 2024-08-01 | Vikings KR  | L   | 1.000      | -            | -                | -                | -         |   -17.47 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           46 |      142 | 2024-08-01 | Sharks      | L   | 1.000      | -            | -                | -                | -         |    -9.10 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           45 |      177 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.69 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           44 |      181 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -6.00 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           43 |      201 | 2024-07-31 | 9z Academy  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.53 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           42 |      227 | 2024-07-30 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -10.29 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           41 |      376 | 2024-07-25 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.24 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           40 |      379 | 2024-07-25 | inSanitY    | W   | 1.000      | 0.143        | 0.048 (0.007)    | -                | 0 (0.000) |    21.13 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           39 |      457 | 2024-07-23 | BESTIA      | L   | 1.000      | -            | -                | -                | -         |    -9.60 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           38 |      470 | 2024-07-23 | Dusty Roots | L   | 1.000      | -            | -                | -                | -         |   -20.06 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           37 |      487 | 2024-07-22 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -18.38 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           36 |      490 | 2024-07-22 | ODDIK       | W   | 1.000      | 0.333        | 0.099 (0.033)    | 0.805 (0.268)    | 0 (0.000) |    21.05 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           35 |      515 | 2024-07-21 | W7M         | W   | 1.000      | 0.333        | -                | 0.519 (0.173)    | 0 (0.000) |    13.78 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           34 |      537 | 2024-07-20 | Solid       | L   | 1.000      | -            | -                | -                | -         |   -15.69 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           33 |      542 | 2024-07-20 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -10.37 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           32 |      593 | 2024-07-19 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -12.55 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           31 |      622 | 2024-07-18 | KRÜ         | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.479 (0.160)    | 0 (0.000) |    14.74 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           30 |      637 | 2024-07-18 | Case        | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | 0 (0.000) |    15.15 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           29 |      688 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -5.40 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           28 |      693 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -5.68 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           27 |      745 | 2024-07-16 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -17.89 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           26 |      750 | 2024-07-16 | KRÜ         | W   | 1.000      | 0.450        | 0.023 (0.010)    | 0.479 (0.215)    | 0 (0.000) |    13.43 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           25 |      757 | 2024-07-16 | W7M         | W   | 1.000      | 0.333        | -                | 0.519 (0.173)    | 0 (0.000) |    11.79 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           24 |      763 | 2024-07-16 | SPORT       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.46 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           23 |      793 | 2024-07-15 | Smoke       | L   | 1.000      | -            | -                | -                | -         |   -23.09 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           22 |      797 | 2024-07-15 | Smoke       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.92 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           21 |      873 | 2024-07-11 | Dusty Roots | W   | 1.000      | -            | -                | -                | -         |    11.95 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           20 |      878 | 2024-07-11 | W7M         | L   | 1.000      | -            | -                | -                | -         |   -20.02 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           19 |      900 | 2024-07-10 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -12.84 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           18 |      938 | 2024-07-08 | Galorys     | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.530 (0.196)    | -         |    12.17 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           17 |      951 | 2024-07-07 | Hawks       | W   | 1.000      | -            | -                | -                | -         |     3.67 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           16 |     1137 | 2024-06-13 | ODDIK       | L   | 0.841      | -            | -                | -                | -         |   -11.55 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           15 |     1239 | 2024-06-09 | KRÜ         | W   | 0.815      | 0.450        | 0.023 (0.008)    | 0.479 (0.176)    | -         |    11.77 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           14 |     1299 | 2024-06-08 | paiN        | L   | 0.809      | -            | -                | -                | -         |    -2.08 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           13 |     1316 | 2024-06-08 | Sharks      | L   | 0.808      | -            | -                | -                | -         |    -8.66 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           12 |     1357 | 2024-06-07 | inSanitY    | W   | 0.802      | 0.450        | 0.048 (0.017)    | 0.447 (0.162)    | -         |    15.15 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           11 |     1625 | 2024-06-01 | Galorys     | W   | 0.761      | 0.371        | 0.030 (0.008)    | -                | -         |    12.40 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           10 |     1677 | 2024-05-30 | W7M         | W   | 0.749      | -            | -                | -                | -         |     8.46 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            9 |     1735 | 2024-05-28 | Corinthians | W   | 0.734      | -            | -                | -                | -         |     2.52 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            8 |     2033 | 2024-05-17 | Case        | L   | 0.661      | -            | -                | -                | -         |    -9.60 | history, leo_drk, MaLLby, r1see, rainny      |
|            7 |     2065 | 2024-05-16 | Sharks      | L   | 0.655      | -            | -                | -                | -         |    -7.31 | BALEROSTYLE, history, leo_drk, r1see, rainny |
|            6 |     2111 | 2024-05-15 | Galorys     | L   | 0.649      | -            | -                | -                | -         |   -10.26 | history, leo_drk, MaLLby, r1see, rainny      |
|            5 |     2119 | 2024-05-15 | BESTIA      | W   | 0.648      | 0.371        | 0.096 (0.023)    | 0.776 (0.186)    | -         |    12.14 | history, leo_drk, MaLLby, r1see, rainny      |
|            4 |     2172 | 2024-05-14 | W7M         | W   | 0.642      | -            | -                | -                | -         |     8.05 | history, leo_drk, MaLLby, r1see, rainny      |
|            3 |     2182 | 2024-05-14 | Case        | W   | 0.641      | -            | -                | -                | -         |    10.32 | history, leo_drk, MaLLby, r1see, rainny      |
|            2 |     2204 | 2024-05-13 | Fluxo       | L   | 0.634      | -            | -                | -                | -         |    -4.59 | history, leo_drk, MaLLby, r1see, rainny      |
|            1 |     2863 | 2024-04-16 | Fluxo       | L   | 0.456      | -            | -                | -                | -         |    -3.73 | history, leo_drk, MaLLby, r1see, rainny      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,153.24)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-16 |      0.861 | $2,500.00      | $2,153.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
