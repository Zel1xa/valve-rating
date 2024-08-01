### Roster Details<br />
Team Name: K10<br />
Roster: Adam9130, bevve, MMS, shushan, Speedy<br />
Global Rank: [155](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  698.3<br />
<br />
Final Rank Value (698.3) = Starting Rank Value (691.6) + Head To Head Adjustments (6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 691.6
- 400 + ( ( 0.142 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 691.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      364 | 2024-07-21 | Astralis Talent | L   | 1.000      | -            | -                | -                | -         |   -14.85 | Adam9130, bevve, MMS, shushan, Speedy    |
|            9 |      483 | 2024-07-18 | 9INE            | L   | 1.000      | -            | -                | -                | -         |    -6.67 | Adam9130, bevve, MMS, shushan, Speedy    |
|            8 |      566 | 2024-07-17 | GL Academy      | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.102 (0.015)    | 0 (0.000) |    17.65 | Adam9130, bevve, meztal, shushan, Speedy |
|            7 |      880 | 2024-06-17 | UNiTY           | L   | 0.900      | -            | -                | -                | -         |    -5.50 | Adam9130, bevve, dobbo, MMS, shushan     |
|            6 |      882 | 2024-06-17 | kONO            | L   | 0.899      | -            | -                | -                | -         |    -8.60 | Adam9130, bevve, dobbo, MMS, shushan     |
|            5 |     1059 | 2024-06-10 | Fraud5          | W   | 0.855      | 0.282        | 0.004 (0.001)    | 0.056 (0.014)    | 0 (0.000) |    11.39 | Adam9130, bevve, dobbo, MMS, shushan     |
|            4 |     1411 | 2024-06-04 | Verdant         | W   | 0.815      | 0.282        | 0.015 (0.003)    | 0.305 (0.070)    | 0 (0.000) |    19.79 | Adam9130, bevve, dobbo, MMS, shushan     |
|            3 |     1495 | 2024-06-01 | CYBERSHOKE      | L   | 0.795      | -            | -                | -                | -         |    -6.20 | Adam9130, bevve, dobbo, MMS, shushan     |
|            2 |     1549 | 2024-05-30 | The Last Resort | W   | 0.782      | 0.282        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.92 | Adam9130, bevve, dobbo, MMS, shushan     |
|            1 |     2473 | 2024-04-27 | GL Academy      | L   | 0.559      | -            | -                | -                | -         |    -7.21 | Adam9130, bevve, dobbo, MMS, shushan     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,536.90)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-18 |      0.906 | $1,000.00      | $905.56         |
| 2024-06-10 |      0.855 | $1,908.00      | $1,631.34       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
