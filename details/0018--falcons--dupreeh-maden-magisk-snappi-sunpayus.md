### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1428.8<br />
<br />
Final Rank Value (1428.8) = Starting Rank Value (1416.8) + Head To Head Adjustments (12.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.712[<sup>2</sup>](#table1)

The average of these factors is 0.495<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1416.8
- 400 + ( ( 0.495 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1416.8


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
|           26 |      114 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.72 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      234 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.100)    | 0.265 (0.154)    | 1 (1.000) |     5.33 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      267 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1033 | 2024-06-16 | Complexity       | L   | 0.861      | -            | -                | -                | -         |    -7.45 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1038 | 2024-06-16 | ENCE             | W   | 0.860      | 0.500        | 0.173 (0.075)    | 0.431 (0.186)    | 1 (0.860) |    11.35 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1067 | 2024-06-15 | The MongolZ      | W   | 0.855      | 0.500        | 1.000 (0.427)    | 0.709 (0.303)    | 1 (0.855) |    24.91 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1077 | 2024-06-15 | Party Astronauts | W   | 0.853      | 0.500        | 0.041 (0.017)    | 0.522 (0.222)    | 1 (0.853) |     2.17 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1118 | 2024-06-14 | Aurora           | L   | 0.847      | -            | -                | -                | -         |   -13.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1726 | 2024-05-28 | Liquid           | L   | 0.737      | -            | -                | -                | -         |    -6.25 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1747 | 2024-05-27 | Monte            | W   | 0.730      | 0.624        | 0.080 (0.036)    | 0.611 (0.278)    | 1 (0.730) |     2.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1759 | 2024-05-27 | G2               | L   | 0.729      | -            | -                | -                | -         |    -1.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2009 | 2024-05-18 | Spirit           | L   | 0.667      | -            | -                | -                | -         |    -1.31 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2041 | 2024-05-17 | Virtus.pro       | W   | 0.661      | 0.769        | 0.498 (0.253)    | 0.316 (0.160)    | 1 (0.661) |    16.90 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2120 | 2024-05-15 | BetBoom          | W   | 0.649      | 0.769        | 0.248 (0.124)    | 0.526 (0.262)    | 1 (0.649) |     9.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2179 | 2024-05-14 | Virtus.pro       | L   | 0.642      | -            | -                | -                | -         |    -3.45 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2554 | 2024-04-27 | G2               | L   | 0.527      | -            | -                | -                | -         |    -0.75 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2579 | 2024-04-26 | BetBoom          | L   | 0.520      | -            | -                | -                | -         |    -8.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2605 | 2024-04-25 | TYLOO            | W   | 0.514      | 0.889        | 0.019 (0.009)    | 0.088 (0.040)    | 1 (0.514) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2625 | 2024-04-24 | The MongolZ      | L   | 0.507      | -            | -                | -                | -         |    -0.93 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3800 | 2024-03-06 | Metizport        | L   | 0.183      | -            | -                | -                | -         |    -5.44 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4253 | 2024-02-16 | AMKAL            | L   | 0.054      | -            | -                | -                | -         |    -1.39 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4279 | 2024-02-15 | Eternal Fire     | L   | 0.047      | -            | -                | -                | -         |    -0.26 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4308 | 2024-02-14 | FaZe             | L   | 0.042      | -            | -                | -                | -         |    -0.25 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4313 | 2024-02-14 | 3DMAX            | W   | 0.041      | 0.143        | 0.509 (0.003)    | 1.000 (0.006)    | 1 (0.041) |     1.06 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4369 | 2024-02-10 | Spirit           | L   | 0.016      | -            | -                | -                | -         |    -0.03 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4382 | 2024-02-09 | ENCE             | W   | 0.009      | 1.000        | 0.173 (0.002)    | 0.431 (0.004)    | 1 (0.009) |     0.17 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,450.90)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.861 | $20,000.00     | $17,222.22      |
| 2024-06-02 |      0.769 | $5,000.00      | $3,844.44       |
| 2024-05-19 |      0.674 | $50,000.00     | $33,708.33      |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |
| 2024-02-11 |      0.022 | $80,000.00     | $1,733.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
