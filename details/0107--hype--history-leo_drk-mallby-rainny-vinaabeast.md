### Roster Details<br />
Team Name: Hype<br />
Roster: history, leo_drk, MaLLby, rainny, vinaabEAST<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  841.2<br />
<br />
Final Rank Value (841.2) = Starting Rank Value (876.8) + Head To Head Adjustments (-35.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.233<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.8
- 400 + ( ( 0.233 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 876.8


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
|           43 |       56 | 2024-08-01 | Sharks      | L   | 1.000      | -            | -                | -                | -         |    -9.03 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           42 |       86 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.65 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           41 |       90 | 2024-07-31 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.96 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           40 |      111 | 2024-07-31 | 9z Academy  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.76 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           39 |      135 | 2024-07-30 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -10.22 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           38 |      284 | 2024-07-25 | Fluxo       | L   | 1.000      | -            | -                | -                | -         |    -5.22 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           37 |      287 | 2024-07-25 | inSanitY    | W   | 1.000      | 0.143        | 0.049 (0.007)    | -                | 0 (0.000) |    21.59 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           36 |      365 | 2024-07-23 | BESTIA      | L   | 1.000      | -            | -                | -                | -         |    -9.58 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           35 |      378 | 2024-07-23 | Dusty Roots | L   | 1.000      | -            | -                | -                | -         |   -19.74 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           34 |      395 | 2024-07-22 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -17.42 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           33 |      398 | 2024-07-22 | ODDIK       | W   | 1.000      | 0.333        | 0.098 (0.033)    | 0.857 (0.286)    | 0 (0.000) |    20.57 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           32 |      423 | 2024-07-21 | W7M         | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.554 (0.185)    | 0 (0.000) |    14.19 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           31 |      445 | 2024-07-20 | Solid       | L   | 1.000      | -            | -                | -                | -         |   -14.84 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           30 |      450 | 2024-07-20 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -10.86 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           29 |      501 | 2024-07-19 | Sharks      | L   | 1.000      | -            | -                | -                | -         |   -12.39 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           28 |      530 | 2024-07-18 | KRÜ         | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.466 (0.155)    | 0 (0.000) |    15.94 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           27 |      546 | 2024-07-18 | Case        | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.750 (0.278)    | 0 (0.000) |    15.96 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           26 |      596 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -6.23 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           25 |      601 | 2024-07-17 | RED Canids  | L   | 1.000      | -            | -                | -                | -         |    -6.60 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           24 |      650 | 2024-07-16 | KRÜ         | L   | 1.000      | -            | -                | -                | -         |   -16.52 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           23 |      655 | 2024-07-16 | KRÜ         | W   | 1.000      | 0.450        | 0.023 (0.010)    | 0.466 (0.210)    | 0 (0.000) |    14.91 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           22 |      662 | 2024-07-16 | W7M         | W   | 1.000      | 0.333        | -                | 0.554 (0.185)    | 0 (0.000) |    12.36 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           21 |      668 | 2024-07-16 | SPORT       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.10 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           20 |      698 | 2024-07-15 | Smoke       | L   | 1.000      | -            | -                | -                | -         |   -22.43 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           19 |      702 | 2024-07-15 | Smoke       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.60 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           18 |      774 | 2024-07-11 | Dusty Roots | W   | 1.000      | -            | -                | -                | -         |    12.56 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           17 |      778 | 2024-07-11 | W7M         | L   | 1.000      | -            | -                | -                | -         |   -19.34 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           16 |      800 | 2024-07-10 | ODDIK       | L   | 1.000      | -            | -                | -                | -         |   -12.37 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           15 |      838 | 2024-07-08 | Galorys     | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.571 (0.212)    | -         |    12.70 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           14 |      851 | 2024-07-07 | Hawks       | W   | 1.000      | -            | -                | -                | -         |     4.21 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           13 |     1017 | 2024-06-13 | ODDIK       | L   | 0.860      | -            | -                | -                | -         |   -11.26 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           12 |     1189 | 2024-06-08 | Sharks      | L   | 0.827      | -            | -                | -                | -         |    -8.74 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           11 |     1227 | 2024-06-07 | inSanitY    | W   | 0.821      | 0.450        | 0.049 (0.018)    | 0.437 (0.162)    | -         |    16.00 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|           10 |     1544 | 2024-05-30 | W7M         | W   | 0.769      | 0.371        | -                | 0.554 (0.158)    | -         |     8.54 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            9 |     1602 | 2024-05-28 | Corinthians | W   | 0.754      | -            | -                | -                | -         |     2.52 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            8 |     1898 | 2024-05-17 | Case        | L   | 0.680      | -            | -                | -                | -         |    -9.90 | history, leo_drk, MaLLby, r1see, rainny      |
|            7 |     1930 | 2024-05-16 | Sharks      | L   | 0.674      | -            | -                | -                | -         |    -7.56 | BALEROSTYLE, history, leo_drk, r1see, rainny |
|            6 |     1976 | 2024-05-15 | Galorys     | L   | 0.668      | -            | -                | -                | -         |   -10.82 | history, leo_drk, MaLLby, r1see, rainny      |
|            5 |     1984 | 2024-05-15 | BESTIA      | W   | 0.667      | 0.371        | 0.091 (0.023)    | 0.756 (0.187)    | -         |    12.24 | history, leo_drk, MaLLby, r1see, rainny      |
|            4 |     2037 | 2024-05-14 | W7M         | W   | 0.661      | -            | -                | -                | -         |     8.23 | history, leo_drk, MaLLby, r1see, rainny      |
|            3 |     2047 | 2024-05-14 | Case        | W   | 0.660      | 0.303        | 0.029 (0.006)    | -                | -         |    10.57 | history, leo_drk, MaLLby, r1see, rainny      |
|            2 |     2069 | 2024-05-13 | Fluxo       | L   | 0.653      | -            | -                | -                | -         |    -4.66 | history, leo_drk, MaLLby, r1see, rainny      |
|            1 |     2726 | 2024-04-16 | Fluxo       | L   | 0.475      | -            | -                | -                | -         |    -3.83 | history, leo_drk, MaLLby, r1see, rainny      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,200.81)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-06-16 |      0.880 | $2,500.00      | $2,200.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
