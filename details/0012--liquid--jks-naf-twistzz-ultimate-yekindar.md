### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1582.1<br />
<br />
Final Rank Value (1582.1) = Starting Rank Value (1499.5) + Head To Head Adjustments (82.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.666[<sup>1</sup>](#table2)
- Bounty Collected: 0.584[<sup>2</sup>](#table1)
- Opponent Network: 0.188[<sup>2</sup>](#table1)
- LAN Wins: 0.713[<sup>2</sup>](#table1)

The average of these factors is 0.538<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1499.5
- 400 + ( ( 0.538 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1499.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |       82 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.331 (0.192)    | 1 (1.000) |    28.06 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      124 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.497 (0.289)    | 0.323 (0.188)    | 1 (1.000) |    21.59 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1637 | 2024-05-29 | G2               | L   | 0.757      | -            | -                | -                | -         |    -2.30 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1662 | 2024-05-28 | Falcons          | W   | 0.750      | 0.624        | 0.224 (0.105)    | 0.247 (0.116)    | 1 (0.750) |     8.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1680 | 2024-05-27 | 9z               | L   | 0.744      | -            | -                | -                | -         |   -14.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1691 | 2024-05-27 | Complexity       | W   | 0.742      | 0.624        | 0.310 (0.144)    | 0.380 (0.176)    | 1 (0.742) |    15.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1765 | 2024-05-23 | Eternal Fire     | L   | 0.714      | -            | -                | -                | -         |    -6.77 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1809 | 2024-05-22 | Astralis         | W   | 0.707      | 0.769        | 0.352 (0.191)    | 0.382 (0.207)    | -         |    16.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1854 | 2024-05-21 | ENCE             | W   | 0.700      | 0.769        | 0.169 (0.091)    | 0.400 (0.215)    | -         |     7.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1910 | 2024-05-19 | AMKAL            | W   | 0.688      | 0.769        | 0.130 (0.069)    | 0.476 (0.251)    | -         |     3.17 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1925 | 2024-05-18 | OG               | W   | 0.683      | 0.769        | 0.139 (0.073)    | -                | -         |     1.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2215 | 2024-05-10 | Astralis         | L   | 0.628      | -            | -                | -                | -         |    -4.82 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2259 | 2024-05-08 | FlyQuest         | W   | 0.615      | 0.889        | -                | 0.290 (0.158)    | 1 (0.615) |     3.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2327 | 2024-05-04 | MOUZ             | L   | 0.589      | -            | -                | -                | -         |    -2.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2389 | 2024-05-01 | Monte            | W   | 0.569      | -            | -                | -                | 1 (0.569) |     1.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2412 | 2024-04-30 | FURIA            | W   | 0.562      | 0.889        | 0.284 (0.142)    | 0.491 (0.245)    | 1 (0.562) |    12.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2656 | 2024-04-19 | M80              | L   | 0.491      | -            | -                | -                | -         |   -12.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2706 | 2024-04-18 | M80              | W   | 0.484      | -            | -                | -                | -         |     2.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2709 | 2024-04-18 | Legacy           | W   | 0.483      | -            | -                | -                | -         |     0.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2756 | 2024-04-17 | Akimbo           | W   | 0.477      | -            | -                | -                | -         |     0.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2761 | 2024-04-17 | straykids        | W   | 0.477      | -            | -                | -                | -         |     0.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2874 | 2024-04-12 | FaZe             | L   | 0.440      | -            | -                | -                | -         |    -3.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2959 | 2024-04-10 | MOUZ             | L   | 0.426      | -            | -                | -                | -         |    -1.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3037 | 2024-04-08 | G2               | W   | 0.413      | 0.624        | 1.000 (0.258)    | 0.498 (0.128)    | 1 (0.413) |    12.21 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3047 | 2024-04-07 | HEROIC           | W   | 0.412      | -            | -                | -                | 1 (0.412) |     7.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3719 | 2024-03-07 | SAW              | L   | 0.201      | -            | -                | -                | -         |    -5.46 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3801 | 2024-03-04 | Complexity       | L   | 0.183      | -            | -                | -                | -         |    -1.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3837 | 2024-03-03 | BOSS             | W   | 0.175      | -            | -                | -                | 1 (0.175) |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3850 | 2024-03-02 | FURIA            | L   | 0.169      | -            | -                | -                | -         |    -1.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3865 | 2024-03-01 | BESTIA           | W   | 0.163      | -            | -                | -                | -         |     0.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3936 | 2024-02-26 | Nouns            | W   | 0.138      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3938 | 2024-02-26 | BOSS             | W   | 0.137      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3951 | 2024-02-25 | Wildcard         | W   | 0.131      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3956 | 2024-02-25 | Nouns            | L   | 0.130      | -            | -                | -                | -         |    -3.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4015 | 2024-02-22 | Party Astronauts | W   | 0.111      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4017 | 2024-02-22 | MIGHT            | W   | 0.111      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4023 | 2024-02-22 | ex-CatEvil       | W   | 0.110      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102,296.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.782 | $6,000.00      | $4,693.33       |
| 2024-05-23 |      0.714 | $100,000.00    | $71,430.56      |
| 2024-05-12 |      0.641 | $32,000.00     | $20,524.44      |
| 2024-04-14 |      0.453 | $10,000.00     | $4,534.95       |
| 2024-03-10 |      0.223 | $5,000.00      | $1,112.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
