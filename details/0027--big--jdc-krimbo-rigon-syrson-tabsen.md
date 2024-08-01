### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1235.8<br />
<br />
Final Rank Value (1235.8) = Starting Rank Value (1238.9) + Head To Head Adjustments (-3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.478[<sup>2</sup>](#table1)

The average of these factors is 0.407<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1238.9
- 400 + ( ( 0.407 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1238.9


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
|           32 |       41 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.52 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |      938 | 2024-06-15 | Permitta      | L   | 0.886      | -            | -                | -                | -         |   -23.71 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |      960 | 2024-06-14 | Space         | W   | 0.881      | 0.435        | -                | 0.406 (0.155)    | 0 (0.000) |     3.09 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1292 | 2024-06-06 | fnatic        | L   | 0.829      | -            | -                | -                | -         |   -10.28 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1332 | 2024-06-06 | Eternal Fire  | L   | 0.826      | -            | -                | -                | -         |    -2.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1357 | 2024-06-05 | BetBoom       | L   | 0.822      | -            | -                | -                | -         |    -9.34 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1380 | 2024-06-05 | Complexity    | L   | 0.821      | -            | -                | -                | -         |    -2.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1390 | 2024-06-05 | FURIA         | W   | 0.819      | 0.715        | 0.286 (0.168)    | 0.495 (0.290)    | 1 (0.819) |    21.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1573 | 2024-05-29 | HEROIC        | L   | 0.776      | -            | -                | -                | -         |    -3.65 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1584 | 2024-05-29 | Virtus.pro    | W   | 0.775      | 0.624        | 0.483 (0.234)    | 0.326 (0.158)    | 1 (0.775) |    22.17 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1600 | 2024-05-28 | FlyQuest      | W   | 0.769      | 0.624        | 0.106 (0.051)    | 0.323 (0.155)    | 1 (0.769) |    11.72 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1624 | 2024-05-27 | Natus Vincere | L   | 0.762      | -            | -                | -                | -         |    -0.40 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1843 | 2024-05-20 | MIBR          | L   | 0.713      | -            | -                | -                | -         |    -5.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1862 | 2024-05-19 | Astralis      | L   | 0.708      | -            | -                | -                | -         |    -1.46 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2252 | 2024-05-07 | G2            | L   | 0.627      | -            | -                | -                | -         |    -0.38 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2316 | 2024-05-03 | HEROIC        | W   | 0.602      | 0.889        | 0.209 (0.112)    | 0.381 (0.204)    | 1 (0.602) |    16.51 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2326 | 2024-05-03 | PERA          | W   | 0.600      | 0.889        | 0.048 (0.026)    | 0.452 (0.241)    | 1 (0.600) |     3.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2354 | 2024-05-02 | Natus Vincere | L   | 0.593      | -            | -                | -                | -         |    -0.25 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2377 | 2024-05-01 | BOSS          | W   | 0.587      | 0.889        | 0.014 (0.007)    | 0.334 (0.174)    | 1 (0.587) |     1.92 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2595 | 2024-04-21 | BLEED         | L   | 0.520      | -            | -                | -                | -         |   -12.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2623 | 2024-04-20 | GamerLegion   | W   | 0.514      | 0.384        | 0.176 (0.035)    | -                | 0 (0.000) |     5.86 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2735 | 2024-04-18 | LEON          | W   | 0.499      | -            | -                | -                | 0 (0.000) |     0.81 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2846 | 2024-04-13 | OG            | L   | 0.467      | -            | -                | -                | -         |   -11.01 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2855 | 2024-04-12 | FORZE         | W   | 0.461      | 0.684        | 0.060 (0.019)    | 0.186 (0.059)    | 0 (0.000) |     2.49 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2927 | 2024-04-10 | Gods Reign    | W   | 0.448      | 0.684        | 0.042 (0.013)    | 0.206 (0.063)    | -         |     1.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     2989 | 2024-04-09 | BetBoom       | L   | 0.440      | -            | -                | -                | -         |    -3.69 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3170 | 2024-04-03 | EYEBALLERS    | W   | 0.400      | 0.384        | -                | 0.513 (0.079)    | -         |     1.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3665 | 2024-03-09 | Spirit        | L   | 0.235      | -            | -                | -                | -         |    -0.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3696 | 2024-03-08 | GamerLegion   | W   | 0.228      | -            | -                | -                | -         |     0.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3831 | 2024-03-03 | Young Ninjas  | L   | 0.195      | -            | -                | -                | -         |    -5.75 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3892 | 2024-03-01 | AMKAL         | W   | 0.179      | 0.500        | 0.132 (0.012)    | -                | -         |     2.16 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3920 | 2024-02-28 | BLEED         | L   | 0.166      | -            | -                | -                | -         |    -4.30 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,349.55)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $2,000.00      | $1,788.89       |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-06-02 |      0.802 | $6,000.00      | $4,810.00       |
| 2024-05-12 |      0.661 | $17,500.00     | $11,564.58      |
| 2024-04-14 |      0.474 | $35,000.00     | $16,590.97      |
| 2024-03-10 |      0.242 | $7,500.00      | $1,815.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
