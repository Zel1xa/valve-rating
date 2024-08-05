### Roster Details<br />
Team Name: Falcons<br />
Roster: dupreeh, Maden, Magisk, Snappi, SunPayus<br />
Global Rank: [17](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1430.3<br />
<br />
Final Rank Value (1430.3) = Starting Rank Value (1418.8) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.604[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.714[<sup>2</sup>](#table1)

The average of these factors is 0.497<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1418.8
- 400 + ( ( 0.497 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1418.8


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
|           26 |      108 | 2024-08-02 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.73 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           25 |      228 | 2024-07-30 | GamerLegion      | W   | 1.000      | 0.581        | 0.173 (0.101)    | 0.266 (0.154)    | 1 (1.000) |     5.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           24 |      261 | 2024-07-29 | Astralis         | L   | 1.000      | -            | -                | -                | -         |    -5.63 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           23 |     1027 | 2024-06-16 | Complexity       | L   | 0.865      | -            | -                | -                | -         |    -7.51 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           22 |     1032 | 2024-06-16 | ENCE             | W   | 0.865      | 0.500        | 0.174 (0.075)    | 0.432 (0.187)    | 1 (0.865) |    11.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           21 |     1061 | 2024-06-15 | The MongolZ      | W   | 0.859      | 0.500        | 1.000 (0.429)    | 0.710 (0.305)    | 1 (0.859) |    25.02 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           20 |     1071 | 2024-06-15 | Party Astronauts | W   | 0.857      | 0.500        | 0.041 (0.018)    | 0.523 (0.224)    | 1 (0.857) |     2.17 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           19 |     1112 | 2024-06-14 | Aurora           | L   | 0.851      | -            | -                | -                | -         |   -13.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           18 |     1720 | 2024-05-28 | Liquid           | L   | 0.741      | -            | -                | -                | -         |    -6.31 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           17 |     1741 | 2024-05-27 | Monte            | W   | 0.734      | 0.624        | 0.080 (0.037)    | 0.611 (0.280)    | 1 (0.734) |     2.28 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           16 |     1753 | 2024-05-27 | G2               | L   | 0.733      | -            | -                | -                | -         |    -1.23 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           15 |     2003 | 2024-05-18 | Spirit           | L   | 0.672      | -            | -                | -                | -         |    -1.32 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           14 |     2035 | 2024-05-17 | Virtus.pro       | W   | 0.665      | 0.769        | 0.498 (0.254)    | 0.317 (0.162)    | 1 (0.665) |    17.00 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           13 |     2114 | 2024-05-15 | BetBoom          | W   | 0.653      | 0.769        | 0.249 (0.125)    | 0.529 (0.265)    | 1 (0.653) |     9.21 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           12 |     2173 | 2024-05-14 | Virtus.pro       | L   | 0.646      | -            | -                | -                | -         |    -3.48 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           11 |     2548 | 2024-04-27 | G2               | L   | 0.531      | -            | -                | -                | -         |    -0.77 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|           10 |     2573 | 2024-04-26 | BetBoom          | L   | 0.525      | -            | -                | -                | -         |    -8.51 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            9 |     2599 | 2024-04-25 | TYLOO            | W   | 0.518      | 0.889        | 0.019 (0.009)    | 0.089 (0.041)    | 1 (0.518) |     0.43 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            8 |     2619 | 2024-04-24 | The MongolZ      | L   | 0.511      | -            | -                | -                | -         |    -0.94 | dupreeh, Maden, Magisk, Snappi, SunPayus |
|            7 |     3794 | 2024-03-06 | Metizport        | L   | 0.187      | -            | -                | -                | -         |    -5.66 | Maden, Magisk, s1mple, Snappi, SunPayus  |
|            6 |     4247 | 2024-02-16 | AMKAL            | L   | 0.058      | -            | -                | -                | -         |    -1.50 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            5 |     4273 | 2024-02-15 | Eternal Fire     | L   | 0.051      | -            | -                | -                | -         |    -0.28 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            4 |     4302 | 2024-02-14 | FaZe             | L   | 0.046      | -            | -                | -                | -         |    -0.28 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            3 |     4307 | 2024-02-14 | 3DMAX            | W   | 0.046      | 0.143        | 0.508 (0.003)    | 1.000 (0.007)    | 1 (0.046) |     1.17 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            2 |     4363 | 2024-02-10 | Spirit           | L   | 0.020      | -            | -                | -                | -         |    -0.04 | BOROS, Maden, Magisk, Snappi, SunPayus   |
|            1 |     4376 | 2024-02-09 | ENCE             | W   | 0.013      | 1.000        | 0.174 (0.002)    | 0.432 (0.006)    | 1 (0.013) |     0.24 | BOROS, Maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($71,169.93)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-06-16 |      0.865 | $20,000.00     | $17,308.33      |
| 2024-06-02 |      0.773 | $5,000.00      | $3,865.97       |
| 2024-05-19 |      0.678 | $50,000.00     | $33,923.61      |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |
| 2024-03-10 |      0.214 | $5,000.00      | $1,067.71       |
| 2024-02-11 |      0.026 | $80,000.00     | $2,077.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
