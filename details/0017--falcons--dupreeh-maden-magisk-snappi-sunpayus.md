### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1429.6<br />
<br />
Final Rank Value (1429.6) = Starting Rank Value (1417.9) + Head To Head Adjustments (11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.604[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.713[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1417.9
- 400 + ( ( 0.496 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1417.9


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
|           26 |      110 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.73 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      230 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.100)    | 0.266 (0.154)    | 1 (1.000) |     5.33 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      263 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.62 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1029 | 2024-06-16 | Complexity       | L   | 0.864      | -            | -                | -                | -         |    -7.49 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1034 | 2024-06-16 | ENCE             | W   | 0.863      | 0.500        | 0.174 (0.075)    | 0.432 (0.186)    | 1 (0.863) |    11.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1063 | 2024-06-15 | The MongolZ      | W   | 0.857      | 0.500        | 1.000 (0.429)    | 0.710 (0.304)    | 1 (0.857) |    24.97 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1073 | 2024-06-15 | Party Astronauts | W   | 0.855      | 0.500        | 0.041 (0.018)    | 0.522 (0.223)    | 1 (0.855) |     2.17 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1114 | 2024-06-14 | Aurora           | L   | 0.849      | -            | -                | -                | -         |   -13.41 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1722 | 2024-05-28 | Liquid           | L   | 0.739      | -            | -                | -                | -         |    -6.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1743 | 2024-05-27 | Monte            | W   | 0.733      | 0.624        | 0.080 (0.037)    | 0.611 (0.279)    | 1 (0.733) |     2.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1755 | 2024-05-27 | G2               | L   | 0.731      | -            | -                | -                | -         |    -1.22 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2005 | 2024-05-18 | Spirit           | L   | 0.670      | -            | -                | -                | -         |    -1.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2037 | 2024-05-17 | Virtus.pro       | W   | 0.663      | 0.769        | 0.498 (0.254)    | 0.316 (0.161)    | 1 (0.663) |    16.96 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2116 | 2024-05-15 | BetBoom          | W   | 0.651      | 0.769        | 0.249 (0.124)    | 0.527 (0.264)    | 1 (0.651) |     9.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2175 | 2024-05-14 | Virtus.pro       | L   | 0.644      | -            | -                | -                | -         |    -3.47 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2550 | 2024-04-27 | G2               | L   | 0.530      | -            | -                | -                | -         |    -0.76 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2575 | 2024-04-26 | BetBoom          | L   | 0.523      | -            | -                | -                | -         |    -8.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2601 | 2024-04-25 | TYLOO            | W   | 0.516      | 0.889        | 0.019 (0.009)    | 0.089 (0.041)    | 1 (0.516) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2621 | 2024-04-24 | The MongolZ      | L   | 0.510      | -            | -                | -                | -         |    -0.94 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3796 | 2024-03-06 | Metizport        | L   | 0.185      | -            | -                | -                | -         |    -5.61 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4249 | 2024-02-16 | AMKAL            | L   | 0.056      | -            | -                | -                | -         |    -1.46 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4275 | 2024-02-15 | Eternal Fire     | L   | 0.049      | -            | -                | -                | -         |    -0.27 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4304 | 2024-02-14 | FaZe             | L   | 0.045      | -            | -                | -                | -         |    -0.27 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4309 | 2024-02-14 | 3DMAX            | W   | 0.044      | 0.143        | 0.509 (0.003)    | 1.000 (0.006)    | 1 (0.044) |     1.13 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4365 | 2024-02-10 | Spirit           | L   | 0.018      | -            | -                | -                | -         |    -0.04 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4378 | 2024-02-09 | ENCE             | W   | 0.012      | 1.000        | 0.174 (0.002)    | 0.432 (0.005)    | 1 (0.012) |     0.21 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,868.40)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.864 | $20,000.00     | $17,272.22      |
| 2024-06-02 |      0.771 | $5,000.00      | $3,856.94       |
| 2024-05-19 |      0.677 | $50,000.00     | $33,833.33      |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-03-10 |      0.212 | $5,000.00      | $1,058.68       |
| 2024-02-11 |      0.024 | $80,000.00     | $1,933.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
