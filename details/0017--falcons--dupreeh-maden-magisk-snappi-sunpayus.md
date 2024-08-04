### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.4<br />
<br />
Final Rank Value (1431.4) = Starting Rank Value (1420.8) + Head To Head Adjustments (10.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.606[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.718[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.8
- 400 + ( ( 0.499 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1420.8


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
|           26 |       83 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.75 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      202 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.101)    | 0.271 (0.157)    | 1 (1.000) |     5.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      235 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.65 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1001 | 2024-06-16 | Complexity       | L   | 0.873      | -            | -                | -                | -         |    -7.58 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1006 | 2024-06-16 | ENCE             | W   | 0.872      | 0.500        | 0.169 (0.074)    | 0.400 (0.174)    | 1 (0.872) |    11.10 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1035 | 2024-06-15 | The MongolZ      | W   | 0.866      | 0.500        | 1.000 (0.433)    | 0.721 (0.312)    | 1 (0.866) |    25.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1045 | 2024-06-15 | Party Astronauts | W   | 0.864      | 0.500        | 0.041 (0.018)    | 0.531 (0.230)    | 1 (0.864) |     2.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1086 | 2024-06-14 | Aurora           | L   | 0.858      | -            | -                | -                | -         |   -13.87 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1694 | 2024-05-28 | Liquid           | L   | 0.748      | -            | -                | -                | -         |    -6.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1715 | 2024-05-27 | Monte            | W   | 0.742      | 0.624        | 0.080 (0.037)    | 0.619 (0.287)    | 1 (0.742) |     2.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1727 | 2024-05-27 | G2               | L   | 0.740      | -            | -                | -                | -         |    -1.26 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1977 | 2024-05-18 | Spirit           | L   | 0.679      | -            | -                | -                | -         |    -1.35 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2009 | 2024-05-17 | Virtus.pro       | W   | 0.672      | 0.769        | 0.497 (0.257)    | 0.323 (0.167)    | 1 (0.672) |    17.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2088 | 2024-05-15 | BetBoom          | W   | 0.660      | 0.769        | 0.251 (0.127)    | 0.541 (0.274)    | 1 (0.660) |     9.30 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2147 | 2024-05-14 | Virtus.pro       | L   | 0.653      | -            | -                | -                | -         |    -3.52 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2522 | 2024-04-27 | G2               | L   | 0.539      | -            | -                | -                | -         |    -0.79 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2547 | 2024-04-26 | BetBoom          | L   | 0.532      | -            | -                | -                | -         |    -8.62 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2573 | 2024-04-25 | TYLOO            | W   | 0.525      | 0.889        | 0.019 (0.009)    | 0.092 (0.043)    | 1 (0.525) |     0.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2593 | 2024-04-24 | The MongolZ      | L   | 0.519      | -            | -                | -                | -         |    -0.98 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3768 | 2024-03-06 | Metizport        | L   | 0.194      | -            | -                | -                | -         |    -5.88 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4221 | 2024-02-16 | AMKAL            | L   | 0.065      | -            | -                | -                | -         |    -1.69 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4247 | 2024-02-15 | Eternal Fire     | L   | 0.058      | -            | -                | -                | -         |    -0.33 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4276 | 2024-02-14 | FaZe             | L   | 0.054      | -            | -                | -                | -         |    -0.32 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4281 | 2024-02-14 | 3DMAX            | W   | 0.053      | 0.143        | 0.506 (0.004)    | 1.000 (0.008)    | 1 (0.053) |     1.35 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4337 | 2024-02-10 | Spirit           | L   | 0.027      | -            | -                | -                | -         |    -0.05 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4350 | 2024-02-09 | ENCE             | W   | 0.021      | 1.000        | 0.169 (0.003)    | 0.400 (0.008)    | 1 (0.021) |     0.37 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,379.91)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.873 | $20,000.00     | $17,453.24      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,902.20       |
| 2024-05-19 |      0.686 | $50,000.00     | $34,285.88      |
| 2024-05-12 |      0.640 | $7,000.00      | $4,477.25       |
| 2024-03-10 |      0.221 | $5,000.00      | $1,103.94       |
| 2024-02-11 |      0.033 | $80,000.00     | $2,657.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
