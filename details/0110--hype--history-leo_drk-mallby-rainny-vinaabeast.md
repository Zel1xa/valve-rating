### Roster Details<br />
Team Name: Hype<br />
Roster: history, leo_drk, MaLLby, rainny, vinaabEAST<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  840.1<br />
<br />
Final Rank Value (840.1) = Starting Rank Value (881.5) + Head To Head Adjustments (-41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.350[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.235<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 881.5
- 400 + ( ( 0.235 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 881.5


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
|           47 |       97 | 2024-08-01 | Vikings KR  | L   | 1.000      | -            | -                | -                | -         |   -17.48 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           46 |      108 | 2024-08-01 | Sharks      | L   | 1.000      | -            | -                | -                | -         |    -9.06 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           45 |      143 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.64 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           44 |      147 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.95 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           43 |      167 | 2024-07-31 | 9z Academy  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.49 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           42 |      193 | 2024-07-30 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -10.24 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           41 |      342 | 2024-07-25 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.19 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           40 |      345 | 2024-07-25 | inSanitY    | W   | 1.000      | 0.143        | 0.048 (0.007)    | -                | 0 (0.000) |    21.19 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           39 |      423 | 2024-07-23 | BESTIA      | L   | 1.000      | -            | -                | -                | -         |    -9.55 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           38 |      436 | 2024-07-23 | Dusty Roots | L   | 1.000      | -            | -                | -                | -         |   -20.11 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           37 |      453 | 2024-07-22 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -18.37 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           36 |      456 | 2024-07-22 | ODDIK       | W   | 1.000      | 0.333        | 0.099 (0.033)    | 0.832 (0.277)    | 0 (0.000) |    21.08 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           35 |      481 | 2024-07-21 | W7M         | W   | 1.000      | 0.333        | -                | 0.537 (0.179)    | 0 (0.000) |    13.76 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           34 |      503 | 2024-07-20 | Solid       | L   | 1.000      | -            | -                | -                | -         |   -15.69 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           33 |      508 | 2024-07-20 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -10.34 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           32 |      559 | 2024-07-19 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -12.48 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           31 |      588 | 2024-07-18 | KRÜ         | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.493 (0.164)    | 0 (0.000) |    14.76 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           30 |      603 | 2024-07-18 | Case        | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.805 (0.298)    | 0 (0.000) |    15.15 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           29 |      654 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -5.33 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           28 |      659 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -5.61 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           27 |      711 | 2024-07-16 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -17.86 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           26 |      716 | 2024-07-16 | KRÜ         | W   | 1.000      | 0.450        | 0.023 (0.010)    | 0.493 (0.222)    | 0 (0.000) |    13.45 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           25 |      723 | 2024-07-16 | W7M         | W   | 1.000      | 0.333        | -                | 0.537 (0.179)    | 0 (0.000) |    11.78 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           24 |      729 | 2024-07-16 | SPORT       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.37 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           23 |      759 | 2024-07-15 | Smoke       | L   | 1.000      | -            | -                | -                | -         |   -23.14 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           22 |      763 | 2024-07-15 | Smoke       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.86 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           21 |      839 | 2024-07-11 | Dusty Roots | W   | 1.000      | -            | -                | -                | -         |    11.87 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           20 |      844 | 2024-07-11 | W7M         | L   | 1.000      | -            | -                | -                | -         |   -20.03 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           19 |      866 | 2024-07-10 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -12.82 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           18 |      904 | 2024-07-08 | Galorys     | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.204)    | -         |    12.15 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           17 |      917 | 2024-07-07 | Hawks       | W   | 1.000      | -            | -                | -                | -         |     3.64 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           16 |     1103 | 2024-06-13 | ODDIK       | L   | 0.853      | -            | -                | -                | -         |   -11.71 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           15 |     1205 | 2024-06-09 | KRÜ         | W   | 0.828      | 0.450        | 0.023 (0.008)    | 0.493 (0.184)    | -         |    11.96 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           14 |     1265 | 2024-06-08 | paiN        | L   | 0.822      | -            | -                | -                | -         |    -2.07 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           13 |     1282 | 2024-06-08 | Sharks      | L   | 0.820      | -            | -                | -                | -         |    -8.71 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           12 |     1323 | 2024-06-07 | inSanitY    | W   | 0.815      | 0.450        | 0.048 (0.018)    | 0.463 (0.170)    | -         |    15.46 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           11 |     1591 | 2024-06-01 | Galorys     | W   | 0.774      | 0.371        | 0.030 (0.009)    | -                | -         |    12.62 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           10 |     1643 | 2024-05-30 | W7M         | W   | 0.762      | -            | -                | -                | -         |     8.60 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            9 |     1701 | 2024-05-28 | Corinthians | W   | 0.747      | -            | -                | -                | -         |     2.55 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            8 |     1999 | 2024-05-17 | Case        | L   | 0.674      | -            | -                | -                | -         |    -9.76 | history, leo_drk, MaLLby, r1see, rainny      |
|            7 |     2031 | 2024-05-16 | Sharks      | L   | 0.667      | -            | -                | -                | -         |    -7.38 | BALEROSTYLE, history, leo_drk, r1see, rainny |
|            6 |     2077 | 2024-05-15 | Galorys     | L   | 0.661      | -            | -                | -                | -         |   -10.45 | history, leo_drk, MaLLby, r1see, rainny      |
|            5 |     2085 | 2024-05-15 | BESTIA      | W   | 0.660      | 0.371        | 0.095 (0.023)    | 0.801 (0.196)    | -         |    12.38 | history, leo_drk, MaLLby, r1see, rainny      |
|            4 |     2138 | 2024-05-14 | W7M         | W   | 0.654      | -            | -                | -                | -         |     8.21 | history, leo_drk, MaLLby, r1see, rainny      |
|            3 |     2148 | 2024-05-14 | Case        | W   | 0.653      | -            | -                | -                | -         |    10.54 | history, leo_drk, MaLLby, r1see, rainny      |
|            2 |     2170 | 2024-05-13 | Fluxo       | L   | 0.647      | -            | -                | -                | -         |    -4.60 | history, leo_drk, MaLLby, r1see, rainny      |
|            1 |     2829 | 2024-04-16 | Fluxo       | L   | 0.469      | -            | -                | -                | -         |    -3.78 | history, leo_drk, MaLLby, r1see, rainny      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,184.43)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-16 |      0.874 | $2,500.00      | $2,184.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
