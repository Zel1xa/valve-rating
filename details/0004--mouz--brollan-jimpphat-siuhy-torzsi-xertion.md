### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1867.2<br />
<br />
Final Rank Value (1867.2) = Starting Rank Value (1843.8) + Head To Head Adjustments (23.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.657[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.838[<sup>2</sup>](#table1)

The average of these factors is 0.706<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1843.8
- 400 + ( ( 0.706 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1843.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      481 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.21 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      524 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.491 (0.491)    | 1 (1.000) |     5.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      661 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1660 | 2024-05-28 | G2                 | L   | 0.751      | -            | -                | -                | -         |   -10.32 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1681 | 2024-05-27 | Complexity         | W   | 0.744      | 0.624        | -                | 0.380 (0.176)    | 1 (0.744) |     4.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1690 | 2024-05-27 | 9z                 | L   | 0.743      | -            | -                | -                | -         |   -21.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1909 | 2024-05-19 | Spirit             | W   | 0.688      | 0.769        | 1.000 (0.528)    | 0.460 (0.243)    | 1 (0.688) |    11.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1937 | 2024-05-18 | HEROIC             | W   | 0.681      | 0.769        | -                | 0.374 (0.196)    | 1 (0.681) |     2.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2016 | 2024-05-16 | Virtus.pro         | W   | 0.667      | 0.769        | 0.497 (0.255)    | -                | 1 (0.667) |     5.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2121 | 2024-05-14 | BetBoom            | W   | 0.654      | 0.769        | -                | 0.542 (0.272)    | 1 (0.654) |     1.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2164 | 2024-05-12 | Vitality           | W   | 0.641      | 0.889        | 0.649 (0.370)    | 0.383 (0.218)    | 1 (0.641) |     9.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2186 | 2024-05-11 | Complexity         | W   | 0.636      | 0.889        | 0.310 (0.175)    | 0.380 (0.215)    | 1 (0.636) |     4.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2234 | 2024-05-09 | G2                 | W   | 0.622      | 0.889        | 1.000 (0.553)    | 0.498 (0.275)    | 1 (0.622) |    12.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2327 | 2024-05-04 | Liquid             | W   | 0.589      | 0.889        | 0.315 (0.165)    | 0.460 (0.241)    | -         |     2.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2395 | 2024-05-01 | GamerLegion        | W   | 0.568      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2426 | 2024-04-30 | Bad News Kangaroos | W   | 0.560      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2846 | 2024-04-14 | FaZe               | L   | 0.453      | -            | -                | -                | -         |   -10.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2863 | 2024-04-13 | G2                 | W   | 0.446      | 0.624        | 1.000 (0.278)    | -                | -         |     9.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2959 | 2024-04-10 | Liquid             | W   | 0.426      | -            | -                | -                | -         |     1.71 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3033 | 2024-04-08 | FURIA              | W   | 0.414      | -            | -                | -                | -         |     3.83 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3044 | 2024-04-07 | TYLOO              | W   | 0.412      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3245 | 2024-03-29 | G2                 | L   | 0.349      | -            | -                | -                | -         |    -3.45 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3368 | 2024-03-22 | Complexity         | W   | 0.301      | -            | -                | -                | -         |     2.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3388 | 2024-03-21 | Eternal Fire       | W   | 0.295      | 1.000        | 0.743 (0.219)    | -                | -         |     2.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3398 | 2024-03-21 | Gaimin Gladiators  | W   | 0.294      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4079 | 2024-02-20 | Spirit             | W   | 0.095      | -            | -                | -                | -         |     1.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4101 | 2024-02-19 | Gaimin Gladiators  | W   | 0.089      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4114 | 2024-02-19 | ex-Guild Eagles    | W   | 0.087      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4309 | 2024-02-10 | FaZe               | L   | 0.028      | -            | -                | -                | -         |    -0.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4352 | 2024-02-06 | ENCE               | W   | 0.002      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($442,344.03)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,911.11       |
| 2024-05-19 |      0.688 | $300,000.00    | $206,250.00     |
| 2024-05-12 |      0.641 | $170,000.00    | $109,036.11     |
| 2024-04-14 |      0.453 | $42,000.00     | $19,046.81      |
| 2024-03-31 |      0.362 | $45,000.00     | $16,300.00      |
| 2024-02-11 |      0.035 | $80,000.00     | $2,800.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
