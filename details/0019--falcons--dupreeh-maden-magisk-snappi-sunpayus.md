### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1428.1<br />
<br />
Final Rank Value (1428.1) = Starting Rank Value (1421.6) + Head To Head Adjustments (6.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.606[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.719[<sup>2</sup>](#table1)

The average of these factors is 0.500<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.6
- 400 + ( ( 0.500 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1421.6


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
|           27 |       52 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.51 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      170 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.174 (0.101)    | 0.271 (0.157)    | 1 (1.000) |     5.36 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      203 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -6.47 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      969 | 2024-06-16 | Complexity       | L   | 0.874      | -            | -                | -                | -         |    -7.85 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      974 | 2024-06-16 | ENCE             | W   | 0.874      | 0.500        | 0.169 (0.074)    | 0.400 (0.175)    | 1 (0.874) |    11.00 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1003 | 2024-06-15 | The MongolZ      | W   | 0.868      | 0.500        | 1.000 (0.434)    | 0.721 (0.313)    | 1 (0.868) |    25.20 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1013 | 2024-06-15 | Party Astronauts | W   | 0.866      | 0.500        | 0.041 (0.018)    | 0.531 (0.230)    | 1 (0.866) |     2.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1054 | 2024-06-14 | Aurora           | L   | 0.860      | -            | -                | -                | -         |   -13.98 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1662 | 2024-05-28 | Liquid           | L   | 0.750      | -            | -                | -                | -         |    -8.44 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1683 | 2024-05-27 | Monte            | W   | 0.743      | 0.624        | 0.080 (0.037)    | 0.618 (0.287)    | 1 (0.743) |     2.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1695 | 2024-05-27 | G2               | L   | 0.742      | -            | -                | -                | -         |    -1.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1945 | 2024-05-18 | Spirit           | L   | 0.681      | -            | -                | -                | -         |    -1.37 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1977 | 2024-05-17 | Virtus.pro       | W   | 0.674      | 0.769        | 0.497 (0.257)    | 0.323 (0.167)    | 1 (0.674) |    17.16 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2056 | 2024-05-15 | BetBoom          | W   | 0.662      | 0.769        | 0.251 (0.128)    | 0.542 (0.276)    | 1 (0.662) |     9.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2115 | 2024-05-14 | Virtus.pro       | L   | 0.655      | -            | -                | -                | -         |    -3.60 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2490 | 2024-04-27 | G2               | L   | 0.540      | -            | -                | -                | -         |    -0.80 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2515 | 2024-04-26 | BetBoom          | L   | 0.534      | -            | -                | -                | -         |    -8.68 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2541 | 2024-04-25 | TYLOO            | W   | 0.527      | 0.889        | 0.019 (0.009)    | 0.092 (0.043)    | 1 (0.527) |     0.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2561 | 2024-04-24 | The MongolZ      | L   | 0.520      | -            | -                | -                | -         |    -1.00 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     3736 | 2024-03-06 | Metizport        | L   | 0.196      | -            | -                | -                | -         |    -5.84 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            7 |     4189 | 2024-02-16 | AMKAL            | L   | 0.067      | -            | -                | -                | -         |    -1.74 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4215 | 2024-02-15 | Eternal Fire     | L   | 0.060      | -            | -                | -                | -         |    -0.34 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4244 | 2024-02-14 | FaZe             | L   | 0.055      | -            | -                | -                | -         |    -0.33 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4249 | 2024-02-14 | 3DMAX            | W   | 0.055      | 0.143        | 0.506 (0.004)    | 1.000 (0.008)    | 1 (0.055) |     1.39 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4305 | 2024-02-10 | Spirit           | L   | 0.029      | -            | -                | -                | -         |    -0.06 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4318 | 2024-02-09 | ENCE             | W   | 0.022      | 1.000        | 0.169 (0.004)    | 0.400 (0.009)    | 1 (0.022) |     0.40 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4353 | 2024-02-06 | Natus Vincere    | W   | 0.002      | -            | -                | -                | -         |     0.05 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,677.57)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.874 | $20,000.00     | $17,488.89      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,911.11       |
| 2024-05-19 |      0.688 | $50,000.00     | $34,375.00      |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |
| 2024-03-10 |      0.223 | $5,000.00      | $1,112.85       |
| 2024-02-11 |      0.035 | $80,000.00     | $2,800.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
