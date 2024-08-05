### Roster Details<br />
Team Name: BIG<br />
Roster: JDC, Krimbo, rigoN, syrsoN, tabseN<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1315.8<br />
<br />
Final Rank Value (1315.8) = Starting Rank Value (1311.7) + Head To Head Adjustments (4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.552[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.573[<sup>2</sup>](#table1)

The average of these factors is 0.445<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1311.7
- 400 + ( ( 0.445 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1311.7


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
|           34 |       93 | 2024-08-02 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.97 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           33 |      130 | 2024-08-01 | Virtus.pro    | W   | 1.000      | 0.581        | 0.498 (0.289)    | 0.317 (0.184)    | 1 (1.000) |    27.82 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           32 |      188 | 2024-07-31 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -0.72 | JDC, Krimbo, rigoN, syrsoN, tabseN  |
|           31 |     1072 | 2024-06-15 | Permitta      | L   | 0.857      | -            | -                | -                | -         |   -23.79 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           30 |     1100 | 2024-06-14 | Space         | W   | 0.852      | 0.435        | -                | 0.439 (0.163)    | 0 (0.000) |     2.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           29 |     1419 | 2024-06-06 | fnatic        | L   | 0.800      | -            | -                | -                | -         |    -7.57 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           28 |     1458 | 2024-06-06 | Eternal Fire  | L   | 0.798      | -            | -                | -                | -         |    -3.59 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           27 |     1482 | 2024-06-05 | BetBoom       | L   | 0.793      | -            | -                | -                | -         |   -10.87 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           26 |     1504 | 2024-06-05 | Complexity    | L   | 0.792      | -            | -                | -                | -         |    -3.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           25 |     1514 | 2024-06-05 | FURIA         | W   | 0.791      | 0.715        | 0.284 (0.161)    | 0.481 (0.272)    | 1 (0.791) |    19.89 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           24 |     1696 | 2024-05-29 | HEROIC        | L   | 0.748      | -            | -                | -                | -         |    -4.54 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           23 |     1707 | 2024-05-29 | Virtus.pro    | W   | 0.746      | 0.624        | 0.498 (0.232)    | 0.317 (0.148)    | 1 (0.746) |    20.55 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           22 |     1723 | 2024-05-28 | FlyQuest      | W   | 0.740      | 0.624        | 0.104 (0.048)    | 0.286 (0.132)    | 1 (0.740) |     8.78 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           21 |     1747 | 2024-05-27 | Natus Vincere | L   | 0.734      | -            | -                | -                | -         |    -0.58 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           20 |     1943 | 2024-05-20 | MIBR          | L   | 0.685      | -            | -                | -                | -         |    -6.77 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           19 |     1958 | 2024-05-19 | Astralis      | L   | 0.680      | -            | -                | -                | -         |    -1.63 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           18 |     2336 | 2024-05-07 | G2            | L   | 0.599      | -            | -                | -                | -         |    -0.50 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           17 |     2400 | 2024-05-03 | HEROIC        | W   | 0.573      | 0.889        | 0.225 (0.115)    | 0.365 (0.186)    | 1 (0.573) |    14.88 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           16 |     2410 | 2024-05-03 | PERA          | W   | 0.571      | 0.889        | 0.048 (0.024)    | 0.446 (0.226)    | 1 (0.571) |     2.11 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           15 |     2437 | 2024-05-02 | Natus Vincere | L   | 0.565      | -            | -                | -                | -         |    -0.36 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           14 |     2459 | 2024-05-01 | BOSS          | W   | 0.558      | 0.889        | -                | 0.327 (0.162)    | 1 (0.558) |     1.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           13 |     2672 | 2024-04-21 | BLEED         | L   | 0.491      | -            | -                | -                | -         |   -12.60 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           12 |     2698 | 2024-04-20 | GamerLegion   | W   | 0.485      | 0.384        | 0.173 (0.032)    | -                | 0 (0.000) |     4.13 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           11 |     2808 | 2024-04-18 | LEON          | W   | 0.471      | -            | -                | -                | 0 (0.000) |     0.52 | JDC, Krimbo, prosus, syrsoN, tabseN |
|           10 |     2917 | 2024-04-13 | OG            | L   | 0.438      | -            | -                | -                | -         |   -11.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            9 |     2926 | 2024-04-12 | FORZE         | W   | 0.433      | 0.684        | 0.058 (0.017)    | -                | -         |     1.55 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            8 |     2997 | 2024-04-10 | Gods Reign    | W   | 0.420      | 0.684        | 0.040 (0.012)    | 0.200 (0.057)    | -         |     0.71 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            7 |     3059 | 2024-04-09 | BetBoom       | L   | 0.412      | -            | -                | -                | -         |    -4.80 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            6 |     3234 | 2024-04-03 | EYEBALLERS    | W   | 0.372      | 0.384        | -                | 0.500 (0.071)    | -         |     1.12 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            5 |     3716 | 2024-03-09 | Spirit        | L   | 0.207      | -            | -                | -                | -         |    -0.22 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            4 |     3747 | 2024-03-08 | GamerLegion   | W   | 0.199      | -            | -                | -                | -         |     0.31 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            3 |     3877 | 2024-03-03 | Young Ninjas  | L   | 0.167      | -            | -                | -                | -         |    -5.02 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            2 |     3937 | 2024-03-01 | AMKAL         | W   | 0.151      | 0.500        | 0.130 (0.010)    | -                | -         |     1.35 | JDC, Krimbo, prosus, syrsoN, tabseN |
|            1 |     3964 | 2024-02-28 | BLEED         | L   | 0.138      | -            | -                | -                | -         |    -3.81 | JDC, Krimbo, prosus, syrsoN, tabseN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($49,685.66)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.866 | $2,000.00      | $1,731.94       |
| 2024-06-09 |      0.819 | $8,000.00      | $6,552.22       |
| 2024-06-02 |      0.773 | $6,000.00      | $4,639.17       |
| 2024-05-12 |      0.632 | $17,500.00     | $11,066.32      |
| 2024-04-14 |      0.446 | $35,000.00     | $15,594.44      |
| 2024-03-10 |      0.214 | $7,500.00      | $1,601.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
