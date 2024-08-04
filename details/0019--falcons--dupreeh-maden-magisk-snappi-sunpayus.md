### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1429.4<br />
<br />
Final Rank Value (1429.4) = Starting Rank Value (1423.1) + Head To Head Adjustments (6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.607[<sup>1</sup>](#table2)
- Bounty Collected: 0.508[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.721[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1423.1
- 400 + ( ( 0.501 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1423.1


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
|           27 |       49 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.52 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      167 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.174 (0.101)    | 0.271 (0.158)    | 1 (1.000) |     5.35 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      200 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      965 | 2024-06-16 | Complexity       | L   | 0.877      | -            | -                | -                | -         |    -7.90 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      970 | 2024-06-16 | ENCE             | W   | 0.877      | 0.500        | 0.170 (0.074)    | 0.401 (0.176)    | 1 (0.877) |    11.00 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |      999 | 2024-06-15 | The MongolZ      | W   | 0.871      | 0.500        | 1.000 (0.436)    | 0.720 (0.314)    | 1 (0.871) |    25.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1009 | 2024-06-15 | Party Astronauts | W   | 0.869      | 0.500        | 0.041 (0.018)    | 0.532 (0.231)    | 1 (0.869) |     2.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1050 | 2024-06-14 | Aurora           | L   | 0.863      | -            | -                | -                | -         |   -14.10 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1658 | 2024-05-28 | Liquid           | L   | 0.753      | -            | -                | -                | -         |    -8.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1679 | 2024-05-27 | Monte            | W   | 0.746      | 0.624        | 0.080 (0.037)    | 0.618 (0.288)    | 1 (0.746) |     2.26 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1691 | 2024-05-27 | G2               | L   | 0.745      | -            | -                | -                | -         |    -1.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1941 | 2024-05-18 | Spirit           | L   | 0.684      | -            | -                | -                | -         |    -1.38 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1973 | 2024-05-17 | Virtus.pro       | W   | 0.677      | 0.769        | 0.496 (0.258)    | 0.324 (0.168)    | 1 (0.677) |    17.22 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2052 | 2024-05-15 | BetBoom          | W   | 0.665      | 0.769        | 0.252 (0.129)    | 0.543 (0.278)    | 1 (0.665) |     9.35 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2111 | 2024-05-14 | Virtus.pro       | L   | 0.658      | -            | -                | -                | -         |    -3.62 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2486 | 2024-04-27 | G2               | L   | 0.543      | -            | -                | -                | -         |    -0.81 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2510 | 2024-04-26 | BetBoom          | L   | 0.537      | -            | -                | -                | -         |    -8.73 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2536 | 2024-04-25 | TYLOO            | W   | 0.530      | 0.889        | 0.019 (0.009)    | 0.092 (0.043)    | 1 (0.530) |     0.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2556 | 2024-04-24 | The MongolZ      | L   | 0.523      | -            | -                | -                | -         |    -1.02 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     3730 | 2024-03-06 | Metizport        | L   | 0.199      | -            | -                | -                | -         |    -5.93 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            7 |     4182 | 2024-02-16 | AMKAL            | L   | 0.070      | -            | -                | -                | -         |    -1.82 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4208 | 2024-02-15 | Eternal Fire     | L   | 0.063      | -            | -                | -                | -         |    -0.36 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4237 | 2024-02-14 | FaZe             | L   | 0.059      | -            | -                | -                | -         |    -0.35 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4242 | 2024-02-14 | 3DMAX            | W   | 0.058      | 0.143        | -                | 1.000 (0.008)    | 1 (0.058) |     1.47 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4298 | 2024-02-10 | Spirit           | L   | 0.032      | -            | -                | -                | -         |    -0.06 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4311 | 2024-02-09 | ENCE             | W   | 0.025      | 1.000        | 0.170 (0.004)    | 0.401 (0.010)    | 1 (0.025) |     0.45 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4346 | 2024-02-06 | Natus Vincere    | W   | 0.005      | 1.000        | 1.000 (0.005)    | -                | -         |     0.14 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($73,187.85)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.877 | $20,000.00     | $17,550.00      |
| 2024-06-02 |      0.785 | $5,000.00      | $3,926.39       |
| 2024-05-19 |      0.691 | $50,000.00     | $34,527.78      |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-03-10 |      0.226 | $5,000.00      | $1,128.13       |
| 2024-02-11 |      0.038 | $80,000.00     | $3,044.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
