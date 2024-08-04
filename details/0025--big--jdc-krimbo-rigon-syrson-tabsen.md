### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1316.0<br />
<br />
Final Rank Value (1316.0) = Starting Rank Value (1313.9) + Head To Head Adjustments (2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.576[<sup>2</sup>](#table1)

The average of these factors is 0.447<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1313.9
- 400 + ( ( 0.447 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1313.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       34 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.99 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |       71 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.496 (0.288)    | 0.324 (0.188)    | 1 (1.000) |    27.73 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      127 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.74 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1010 | 2024-06-15 | Permitta      | L   | 0.869      | -            | -                | -                | -         |   -24.24 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1038 | 2024-06-14 | Space         | W   | 0.864      | 0.435        | -                | 0.406 (0.153)    | 0 (0.000) |     2.26 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1357 | 2024-06-06 | fnatic        | L   | 0.812      | -            | -                | -                | -         |    -7.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1396 | 2024-06-06 | Eternal Fire  | L   | 0.810      | -            | -                | -                | -         |    -3.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1420 | 2024-06-05 | BetBoom       | L   | 0.805      | -            | -                | -                | -         |   -11.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1442 | 2024-06-05 | Complexity    | L   | 0.804      | -            | -                | -                | -         |    -3.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1452 | 2024-06-05 | FURIA         | W   | 0.803      | 0.715        | 0.284 (0.163)    | 0.491 (0.282)    | 1 (0.803) |    19.98 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1634 | 2024-05-29 | HEROIC        | L   | 0.760      | -            | -                | -                | -         |    -4.65 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1645 | 2024-05-29 | Virtus.pro    | W   | 0.758      | 0.624        | 0.496 (0.235)    | 0.324 (0.153)    | 1 (0.758) |    20.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1661 | 2024-05-28 | FlyQuest      | W   | 0.752      | 0.624        | 0.104 (0.049)    | 0.291 (0.137)    | 1 (0.752) |     8.99 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1685 | 2024-05-27 | Natus Vincere | L   | 0.746      | -            | -                | -                | -         |    -0.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1881 | 2024-05-20 | MIBR          | L   | 0.697      | -            | -                | -                | -         |    -6.80 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1896 | 2024-05-19 | Astralis      | L   | 0.692      | -            | -                | -                | -         |    -2.03 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2274 | 2024-05-07 | G2            | L   | 0.611      | -            | -                | -                | -         |    -0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2338 | 2024-05-03 | HEROIC        | W   | 0.585      | 0.889        | 0.229 (0.119)    | 0.375 (0.195)    | 1 (0.585) |    15.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2348 | 2024-05-03 | PERA          | W   | 0.583      | 0.889        | 0.048 (0.025)    | 0.453 (0.235)    | 1 (0.583) |     2.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2375 | 2024-05-02 | Natus Vincere | L   | 0.577      | -            | -                | -                | -         |    -0.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2397 | 2024-05-01 | BOSS          | W   | 0.570      | 0.889        | -                | 0.333 (0.169)    | 1 (0.570) |     1.24 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2609 | 2024-04-21 | BLEED         | L   | 0.503      | -            | -                | -                | -         |   -12.90 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2635 | 2024-04-20 | GamerLegion   | W   | 0.497      | 0.384        | 0.174 (0.033)    | -                | 0 (0.000) |     4.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2745 | 2024-04-18 | LEON          | W   | 0.483      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2854 | 2024-04-13 | OG            | L   | 0.450      | -            | -                | -                | -         |   -11.61 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2863 | 2024-04-12 | FORZE         | W   | 0.445      | 0.684        | 0.058 (0.018)    | -                | -         |     1.61 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2934 | 2024-04-10 | Gods Reign    | W   | 0.432      | 0.684        | 0.041 (0.012)    | 0.204 (0.060)    | -         |     0.73 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     2996 | 2024-04-09 | BetBoom       | L   | 0.424      | -            | -                | -                | -         |    -4.91 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3171 | 2024-04-03 | EYEBALLERS    | W   | 0.384      | 0.384        | -                | 0.510 (0.075)    | -         |     1.15 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3652 | 2024-03-09 | Spirit        | L   | 0.219      | -            | -                | -                | -         |    -0.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3683 | 2024-03-08 | GamerLegion   | W   | 0.211      | -            | -                | -                | -         |     0.35 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3813 | 2024-03-03 | Young Ninjas  | L   | 0.179      | -            | -                | -                | -         |    -5.40 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3873 | 2024-03-01 | AMKAL         | W   | 0.163      | 0.500        | 0.130 (0.011)    | -                | -         |     1.45 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3900 | 2024-02-28 | BLEED         | L   | 0.150      | -            | -                | -                | -         |    -4.15 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,603.99)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.878 | $2,000.00      | $1,756.11       |
| 2024-06-09 |      0.831 | $8,000.00      | $6,648.89       |
| 2024-06-02 |      0.785 | $6,000.00      | $4,711.67       |
| 2024-05-12 |      0.644 | $17,500.00     | $11,277.78      |
| 2024-04-14 |      0.458 | $35,000.00     | $16,017.36      |
| 2024-03-10 |      0.226 | $7,500.00      | $1,692.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
