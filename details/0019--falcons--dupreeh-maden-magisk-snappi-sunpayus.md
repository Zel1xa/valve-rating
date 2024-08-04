### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1431.5<br />
<br />
Final Rank Value (1431.5) = Starting Rank Value (1421.3) + Head To Head Adjustments (10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.606[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.719[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.3
- 400 + ( ( 0.499 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1421.3


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
|           27 |       61 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.76 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           26 |      178 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.174 (0.101)    | 0.271 (0.157)    | 1 (1.000) |     5.29 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      211 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.66 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      977 | 2024-06-16 | Complexity       | L   | 0.874      | -            | -                | -                | -         |    -7.82 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |      982 | 2024-06-16 | ENCE             | W   | 0.873      | 0.500        | 0.169 (0.074)    | 0.400 (0.175)    | 1 (0.873) |    11.06 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1011 | 2024-06-15 | The MongolZ      | W   | 0.867      | 0.500        | 1.000 (0.434)    | 0.721 (0.313)    | 1 (0.867) |    25.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1021 | 2024-06-15 | Party Astronauts | W   | 0.865      | 0.500        | 0.041 (0.018)    | 0.531 (0.230)    | 1 (0.865) |     2.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1062 | 2024-06-14 | Aurora           | L   | 0.859      | -            | -                | -                | -         |   -13.95 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1670 | 2024-05-28 | Liquid           | L   | 0.750      | -            | -                | -                | -         |    -6.50 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1691 | 2024-05-27 | Monte            | W   | 0.743      | 0.624        | 0.080 (0.037)    | 0.619 (0.287)    | 1 (0.743) |     2.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1703 | 2024-05-27 | G2               | L   | 0.741      | -            | -                | -                | -         |    -1.27 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1953 | 2024-05-18 | Spirit           | L   | 0.680      | -            | -                | -                | -         |    -1.37 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     1985 | 2024-05-17 | Virtus.pro       | W   | 0.673      | 0.769        | 0.497 (0.257)    | 0.323 (0.167)    | 1 (0.673) |    17.19 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2064 | 2024-05-15 | BetBoom          | W   | 0.661      | 0.769        | 0.251 (0.127)    | 0.541 (0.275)    | 1 (0.661) |     9.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2123 | 2024-05-14 | Virtus.pro       | L   | 0.654      | -            | -                | -                | -         |    -3.55 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2498 | 2024-04-27 | G2               | L   | 0.540      | -            | -                | -                | -         |    -0.79 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2523 | 2024-04-26 | BetBoom          | L   | 0.533      | -            | -                | -                | -         |    -8.66 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2549 | 2024-04-25 | TYLOO            | W   | 0.526      | 0.889        | 0.019 (0.009)    | 0.092 (0.043)    | 1 (0.526) |     0.42 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2569 | 2024-04-24 | The MongolZ      | L   | 0.520      | -            | -                | -                | -         |    -0.99 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     3744 | 2024-03-06 | Metizport        | L   | 0.195      | -            | -                | -                | -         |    -5.82 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            7 |     4197 | 2024-02-16 | AMKAL            | L   | 0.066      | -            | -                | -                | -         |    -1.72 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            6 |     4223 | 2024-02-15 | Eternal Fire     | L   | 0.060      | -            | -                | -                | -         |    -0.33 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4252 | 2024-02-14 | FaZe             | L   | 0.055      | -            | -                | -                | -         |    -0.32 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4257 | 2024-02-14 | 3DMAX            | W   | 0.054      | 0.143        | 0.506 (0.004)    | 1.000 (0.008)    | 1 (0.054) |     1.37 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4313 | 2024-02-10 | Spirit           | L   | 0.028      | -            | -                | -                | -         |    -0.06 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4326 | 2024-02-09 | ENCE             | W   | 0.022      | 1.000        | 0.169 (0.004)    | 0.400 (0.009)    | 1 (0.022) |     0.39 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4361 | 2024-02-06 | Natus Vincere    | W   | 0.001      | -            | -                | -                | -         |     0.02 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72,557.73)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.874 | $20,000.00     | $17,474.54      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,907.52       |
| 2024-05-19 |      0.687 | $50,000.00     | $34,339.12      |
| 2024-05-12 |      0.641 | $7,000.00      | $4,484.70       |
| 2024-03-10 |      0.222 | $5,000.00      | $1,109.26       |
| 2024-02-11 |      0.034 | $80,000.00     | $2,742.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
