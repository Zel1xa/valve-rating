### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.5<br />
<br />
Final Rank Value (1315.5) = Starting Rank Value (1311.3) + Head To Head Adjustments (4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.572[<sup>2</sup>](#table1)

The average of these factors is 0.444<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1311.3
- 400 + ( ( 0.444 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1311.3


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
|           34 |       95 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      132 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.498 (0.289)    | 0.316 (0.184)    | 1 (1.000) |    27.82 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      190 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1074 | 2024-06-15 | Permitta      | L   | 0.855      | -            | -                | -                | -         |   -23.74 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1102 | 2024-06-14 | Space         | W   | 0.850      | 0.435        | -                | 0.439 (0.162)    | 0 (0.000) |     2.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1421 | 2024-06-06 | fnatic        | L   | 0.798      | -            | -                | -                | -         |    -7.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1460 | 2024-06-06 | Eternal Fire  | L   | 0.796      | -            | -                | -                | -         |    -3.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1484 | 2024-06-05 | BetBoom       | L   | 0.792      | -            | -                | -                | -         |   -10.85 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1506 | 2024-06-05 | Complexity    | L   | 0.790      | -            | -                | -                | -         |    -3.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1516 | 2024-06-05 | FURIA         | W   | 0.789      | 0.715        | 0.284 (0.160)    | 0.480 (0.271)    | 1 (0.789) |    19.86 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1698 | 2024-05-29 | HEROIC        | L   | 0.746      | -            | -                | -                | -         |    -4.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1709 | 2024-05-29 | Virtus.pro    | W   | 0.744      | 0.624        | 0.498 (0.231)    | 0.316 (0.147)    | 1 (0.744) |    20.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1725 | 2024-05-28 | FlyQuest      | W   | 0.739      | 0.624        | 0.104 (0.048)    | 0.285 (0.132)    | 1 (0.739) |     8.74 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1749 | 2024-05-27 | Natus Vincere | L   | 0.732      | -            | -                | -                | -         |    -0.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1945 | 2024-05-20 | MIBR          | L   | 0.683      | -            | -                | -                | -         |    -6.76 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1960 | 2024-05-19 | Astralis      | L   | 0.678      | -            | -                | -                | -         |    -1.63 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2338 | 2024-05-07 | G2            | L   | 0.597      | -            | -                | -                | -         |    -0.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2402 | 2024-05-03 | HEROIC        | W   | 0.571      | 0.889        | 0.225 (0.114)    | 0.364 (0.185)    | 1 (0.571) |    14.82 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2412 | 2024-05-03 | PERA          | W   | 0.570      | 0.889        | 0.048 (0.024)    | 0.445 (0.226)    | 1 (0.570) |     2.10 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2439 | 2024-05-02 | Natus Vincere | L   | 0.563      | -            | -                | -                | -         |    -0.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2461 | 2024-05-01 | BOSS          | W   | 0.556      | 0.889        | -                | 0.326 (0.161)    | 1 (0.556) |     1.23 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2674 | 2024-04-21 | BLEED         | L   | 0.489      | -            | -                | -                | -         |   -12.56 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2700 | 2024-04-20 | GamerLegion   | W   | 0.483      | 0.384        | 0.173 (0.032)    | -                | 0 (0.000) |     4.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2810 | 2024-04-18 | LEON          | W   | 0.469      | -            | -                | -                | 0 (0.000) |     0.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2919 | 2024-04-13 | OG            | L   | 0.436      | -            | -                | -                | -         |   -11.27 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2928 | 2024-04-12 | FORZE         | W   | 0.431      | 0.684        | 0.058 (0.017)    | -                | -         |     1.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2999 | 2024-04-10 | Gods Reign    | W   | 0.418      | 0.684        | 0.040 (0.011)    | 0.200 (0.057)    | -         |     0.71 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3061 | 2024-04-09 | BetBoom       | L   | 0.410      | -            | -                | -                | -         |    -4.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3236 | 2024-04-03 | EYEBALLERS    | W   | 0.370      | 0.384        | -                | 0.500 (0.071)    | -         |     1.12 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3718 | 2024-03-09 | Spirit        | L   | 0.205      | -            | -                | -                | -         |    -0.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3749 | 2024-03-08 | GamerLegion   | W   | 0.198      | -            | -                | -                | -         |     0.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3879 | 2024-03-03 | Young Ninjas  | L   | 0.165      | -            | -                | -                | -         |    -4.97 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3939 | 2024-03-01 | AMKAL         | W   | 0.149      | 0.500        | 0.130 (0.010)    | -                | -         |     1.33 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3966 | 2024-02-28 | BLEED         | L   | 0.136      | -            | -                | -                | -         |    -3.76 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($49,548.44)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.864 | $2,000.00      | $1,728.33       |
| 2024-06-09 |      0.817 | $8,000.00      | $6,537.78       |
| 2024-06-02 |      0.771 | $6,000.00      | $4,628.33       |
| 2024-05-12 |      0.631 | $17,500.00     | $11,034.72      |
| 2024-04-14 |      0.444 | $35,000.00     | $15,531.25      |
| 2024-03-10 |      0.212 | $7,500.00      | $1,588.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
