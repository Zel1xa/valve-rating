### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1432.7<br />
<br />
Final Rank Value (1432.7) = Starting Rank Value (1428.4) + Head To Head Adjustments (4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.607[<sup>1</sup>](#table2)
- Bounty Collected: 0.508[<sup>2</sup>](#table1)
- Opponent Network: 0.174[<sup>2</sup>](#table1)
- LAN Wins: 0.722[<sup>2</sup>](#table1)

The average of these factors is 0.503<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1428.4
- 400 + ( ( 0.503 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1428.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       41 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.50 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           27 |      144 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.174 (0.101)    | 0.281 (0.163)    | 1 (1.000) |     5.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      177 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.46 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      927 | 2024-06-16 | Complexity       | L   | 0.879      | -            | -                | -                | -         |    -8.07 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      933 | 2024-06-16 | ENCE             | W   | 0.878      | 0.500        | 0.170 (0.075)    | 0.415 (0.182)    | 1 (0.878) |    10.50 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      957 | 2024-06-15 | The MongolZ      | W   | 0.873      | 0.500        | 1.000 (0.436)    | 0.745 (0.325)    | 1 (0.873) |    25.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |      966 | 2024-06-15 | Party Astronauts | W   | 0.871      | 0.500        | 0.041 (0.018)    | 0.550 (0.239)    | 1 (0.871) |     2.16 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1000 | 2024-06-14 | Aurora           | L   | 0.865      | -            | -                | -                | -         |   -14.24 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1595 | 2024-05-28 | Liquid           | L   | 0.755      | -            | -                | -                | -         |    -8.70 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1616 | 2024-05-27 | Monte            | W   | 0.748      | 0.624        | 0.080 (0.037)    | 0.639 (0.298)    | 1 (0.748) |     2.11 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1628 | 2024-05-27 | G2               | L   | 0.747      | -            | -                | -                | -         |    -1.35 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1876 | 2024-05-18 | Spirit           | L   | 0.685      | -            | -                | -                | -         |    -1.37 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1908 | 2024-05-17 | Virtus.pro       | W   | 0.679      | 0.769        | 0.496 (0.259)    | 0.335 (0.175)    | 1 (0.679) |    17.11 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1987 | 2024-05-15 | BetBoom          | W   | 0.667      | 0.769        | 0.252 (0.129)    | 0.563 (0.288)    | 1 (0.667) |     9.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2046 | 2024-05-14 | Virtus.pro       | L   | 0.660      | -            | -                | -                | -         |    -3.76 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2420 | 2024-04-27 | G2               | L   | 0.545      | -            | -                | -                | -         |    -0.85 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2444 | 2024-04-26 | BetBoom          | L   | 0.539      | -            | -                | -                | -         |    -8.92 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2470 | 2024-04-25 | TYLOO            | W   | 0.532      | 0.889        | 0.019 (0.009)    | 0.096 (0.045)    | 1 (0.532) |     0.41 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2490 | 2024-04-24 | The MongolZ      | L   | 0.525      | -            | -                | -                | -         |    -1.03 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     3657 | 2024-03-06 | Metizport        | L   | 0.201      | -            | -                | -                | -         |    -6.00 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            8 |     4109 | 2024-02-16 | AMKAL            | L   | 0.072      | -            | -                | -                | -         |    -1.87 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            7 |     4135 | 2024-02-15 | Eternal Fire     | L   | 0.065      | -            | -                | -                | -         |    -0.37 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4164 | 2024-02-14 | FaZe             | L   | 0.060      | -            | -                | -                | -         |    -0.35 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4169 | 2024-02-14 | 3DMAX            | W   | 0.059      | 0.143        | -                | 1.000 (0.008)    | 1 (0.059) |     1.50 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4225 | 2024-02-10 | Spirit           | L   | 0.034      | -            | -                | -                | -         |    -0.07 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4240 | 2024-02-09 | ENCE             | W   | 0.027      | 1.000        | 0.170 (0.005)    | 0.415 (0.011)    | 1 (0.027) |     0.47 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4273 | 2024-02-06 | Natus Vincere    | W   | 0.006      | 1.000        | 1.000 (0.006)    | -                | -         |     0.19 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4282 | 2024-02-05 | Complexity       | W   | 0.000      | -            | -                | -                | -         |     0.01 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($73,473.91)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.879 | $20,000.00     | $17,584.26      |
| 2024-06-02 |      0.787 | $5,000.00      | $3,934.95       |
| 2024-05-19 |      0.692 | $50,000.00     | $34,613.43      |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-03-10 |      0.227 | $5,000.00      | $1,136.69       |
| 2024-02-11 |      0.040 | $80,000.00     | $3,181.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
