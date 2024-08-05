### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.5<br />
<br />
Final Rank Value (1431.5) = Starting Rank Value (1420.6) + Head To Head Adjustments (10.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.605[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.717[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1420.6
- 400 + ( ( 0.499 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1420.6


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
|           26 |       87 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.74 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      206 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.101)    | 0.271 (0.157)    | 1 (1.000) |     5.31 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      239 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.64 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1005 | 2024-06-16 | Complexity       | L   | 0.870      | -            | -                | -                | -         |    -7.57 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1010 | 2024-06-16 | ENCE             | W   | 0.870      | 0.500        | 0.168 (0.073)    | 0.439 (0.191)    | 1 (0.870) |    11.22 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1039 | 2024-06-15 | The MongolZ      | W   | 0.864      | 0.500        | 1.000 (0.432)    | 0.721 (0.311)    | 1 (0.864) |    25.13 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1049 | 2024-06-15 | Party Astronauts | W   | 0.862      | 0.500        | 0.041 (0.018)    | 0.531 (0.229)    | 1 (0.862) |     2.18 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1090 | 2024-06-14 | Aurora           | L   | 0.856      | -            | -                | -                | -         |   -13.77 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1698 | 2024-05-28 | Liquid           | L   | 0.746      | -            | -                | -                | -         |    -6.38 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1719 | 2024-05-27 | Monte            | W   | 0.739      | 0.624        | 0.080 (0.037)    | 0.619 (0.286)    | 1 (0.739) |     2.26 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1731 | 2024-05-27 | G2               | L   | 0.738      | -            | -                | -                | -         |    -1.25 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1981 | 2024-05-18 | Spirit           | L   | 0.676      | -            | -                | -                | -         |    -1.34 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2013 | 2024-05-17 | Virtus.pro       | W   | 0.670      | 0.769        | 0.497 (0.256)    | 0.323 (0.166)    | 1 (0.670) |    17.12 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2092 | 2024-05-15 | BetBoom          | W   | 0.658      | 0.769        | 0.250 (0.126)    | 0.540 (0.273)    | 1 (0.658) |     9.26 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2151 | 2024-05-14 | Virtus.pro       | L   | 0.651      | -            | -                | -                | -         |    -3.51 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2526 | 2024-04-27 | G2               | L   | 0.536      | -            | -                | -                | -         |    -0.78 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2551 | 2024-04-26 | BetBoom          | L   | 0.530      | -            | -                | -                | -         |    -8.60 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2577 | 2024-04-25 | TYLOO            | W   | 0.523      | 0.889        | 0.019 (0.009)    | 0.091 (0.042)    | 1 (0.523) |     0.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2597 | 2024-04-24 | The MongolZ      | L   | 0.516      | -            | -                | -                | -         |    -0.97 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3772 | 2024-03-06 | Metizport        | L   | 0.192      | -            | -                | -                | -         |    -5.81 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4225 | 2024-02-16 | AMKAL            | L   | 0.063      | -            | -                | -                | -         |    -1.63 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4251 | 2024-02-15 | Eternal Fire     | L   | 0.056      | -            | -                | -                | -         |    -0.31 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4280 | 2024-02-14 | FaZe             | L   | 0.051      | -            | -                | -                | -         |    -0.30 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4285 | 2024-02-14 | 3DMAX            | W   | 0.050      | 0.143        | 0.507 (0.004)    | 1.000 (0.007)    | 1 (0.050) |     1.29 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4341 | 2024-02-10 | Spirit           | L   | 0.025      | -            | -                | -                | -         |    -0.05 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4354 | 2024-02-09 | ENCE             | W   | 0.018      | 1.000        | 0.168 (0.003)    | 0.439 (0.008)    | 1 (0.018) |     0.33 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,981.74)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.870 | $20,000.00     | $17,405.56      |
| 2024-06-02 |      0.778 | $5,000.00      | $3,890.28       |
| 2024-05-19 |      0.683 | $50,000.00     | $34,166.67      |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |
| 2024-02-11 |      0.031 | $80,000.00     | $2,466.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
