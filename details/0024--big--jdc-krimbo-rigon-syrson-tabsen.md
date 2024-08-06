### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.0<br />
<br />
Final Rank Value (1315.0) = Starting Rank Value (1310.6) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.572[<sup>2</sup>](#table1)

The average of these factors is 0.444<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1310.6
- 400 + ( ( 0.444 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1310.6


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
|           34 |       99 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.96 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      136 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.498 (0.290)    | 0.316 (0.183)    | 1 (1.000) |    27.82 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      194 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1078 | 2024-06-15 | Permitta      | L   | 0.853      | -            | -                | -                | -         |   -23.66 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1106 | 2024-06-14 | Space         | W   | 0.848      | 0.435        | -                | 0.439 (0.162)    | 0 (0.000) |     2.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1425 | 2024-06-06 | fnatic        | L   | 0.796      | -            | -                | -                | -         |    -7.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1464 | 2024-06-06 | Eternal Fire  | L   | 0.794      | -            | -                | -                | -         |    -3.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1488 | 2024-06-05 | BetBoom       | L   | 0.789      | -            | -                | -                | -         |   -10.82 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1510 | 2024-06-05 | Complexity    | L   | 0.788      | -            | -                | -                | -         |    -3.35 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1520 | 2024-06-05 | FURIA         | W   | 0.787      | 0.715        | 0.284 (0.160)    | 0.479 (0.270)    | 1 (0.787) |    19.82 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1702 | 2024-05-29 | HEROIC        | L   | 0.744      | -            | -                | -                | -         |    -4.53 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1713 | 2024-05-29 | Virtus.pro    | W   | 0.742      | 0.624        | 0.498 (0.231)    | 0.316 (0.146)    | 1 (0.742) |    20.43 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1729 | 2024-05-28 | FlyQuest      | W   | 0.736      | 0.624        | 0.104 (0.048)    | 0.284 (0.131)    | 1 (0.736) |     8.69 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1753 | 2024-05-27 | Natus Vincere | L   | 0.729      | -            | -                | -                | -         |    -0.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1949 | 2024-05-20 | MIBR          | L   | 0.681      | -            | -                | -                | -         |    -6.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1964 | 2024-05-19 | Astralis      | L   | 0.676      | -            | -                | -                | -         |    -1.62 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2342 | 2024-05-07 | G2            | L   | 0.595      | -            | -                | -                | -         |    -0.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2406 | 2024-05-03 | HEROIC        | W   | 0.569      | 0.889        | 0.225 (0.114)    | 0.363 (0.183)    | 1 (0.569) |    14.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2416 | 2024-05-03 | PERA          | W   | 0.567      | 0.889        | 0.048 (0.024)    | 0.445 (0.224)    | 1 (0.567) |     2.10 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2443 | 2024-05-02 | Natus Vincere | L   | 0.560      | -            | -                | -                | -         |    -0.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2465 | 2024-05-01 | BOSS          | W   | 0.554      | 0.889        | -                | 0.326 (0.160)    | 1 (0.554) |     1.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2678 | 2024-04-21 | BLEED         | L   | 0.487      | -            | -                | -                | -         |   -12.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2704 | 2024-04-20 | GamerLegion   | W   | 0.481      | 0.384        | 0.173 (0.032)    | -                | 0 (0.000) |     4.08 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2814 | 2024-04-18 | LEON          | W   | 0.467      | -            | -                | -                | 0 (0.000) |     0.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2923 | 2024-04-13 | OG            | L   | 0.434      | -            | -                | -                | -         |   -11.21 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2932 | 2024-04-12 | FORZE         | W   | 0.428      | 0.684        | 0.057 (0.017)    | -                | -         |     1.53 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     3003 | 2024-04-10 | Gods Reign    | W   | 0.415      | 0.684        | 0.040 (0.011)    | 0.199 (0.057)    | -         |     0.70 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3065 | 2024-04-09 | BetBoom       | L   | 0.408      | -            | -                | -                | -         |    -4.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3240 | 2024-04-03 | EYEBALLERS    | W   | 0.367      | 0.384        | -                | 0.499 (0.070)    | -         |     1.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3722 | 2024-03-09 | Spirit        | L   | 0.203      | -            | -                | -                | -         |    -0.21 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3753 | 2024-03-08 | GamerLegion   | W   | 0.195      | -            | -                | -                | -         |     0.30 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3883 | 2024-03-03 | Young Ninjas  | L   | 0.163      | -            | -                | -                | -         |    -4.89 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3943 | 2024-03-01 | AMKAL         | W   | 0.147      | 0.500        | 0.130 (0.010)    | -                | -         |     1.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3970 | 2024-02-28 | BLEED         | L   | 0.133      | -            | -                | -                | -         |    -3.69 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($49,358.44)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.862 | $2,000.00      | $1,723.33       |
| 2024-06-09 |      0.815 | $8,000.00      | $6,517.78       |
| 2024-06-02 |      0.769 | $6,000.00      | $4,613.33       |
| 2024-05-12 |      0.628 | $17,500.00     | $10,990.97      |
| 2024-04-14 |      0.441 | $35,000.00     | $15,443.75      |
| 2024-03-10 |      0.209 | $7,500.00      | $1,569.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />