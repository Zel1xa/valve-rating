### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1671.9<br />
<br />
Final Rank Value (1671.9) = Starting Rank Value (1594.9) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.197[<sup>2</sup>](#table1)
- LAN Wins: 0.804[<sup>2</sup>](#table1)

The average of these factors is 0.582<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1594.9
- 400 + ( ( 0.582 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1594.9


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
|           38 |       65 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    25.60 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      144 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    26.87 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      188 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.498 (0.290)    | 0.316 (0.183)    | 1 (1.000) |    19.04 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1701 | 2024-05-29 | G2               | L   | 0.744      | -            | -                | -                | -         |    -3.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1726 | 2024-05-28 | Falcons          | W   | 0.737      | 0.624        | 0.220 (0.101)    | -                | 1 (0.737) |     6.25 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1744 | 2024-05-27 | 9z               | L   | 0.731      | -            | -                | -                | -         |   -16.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1755 | 2024-05-27 | Complexity       | W   | 0.729      | 0.624        | 0.341 (0.155)    | 0.372 (0.169)    | 1 (0.729) |    13.39 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1829 | 2024-05-23 | Eternal Fire     | L   | 0.701      | -            | -                | -                | -         |    -8.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1873 | 2024-05-22 | Astralis         | W   | 0.693      | 0.769        | 0.389 (0.207)    | 0.412 (0.220)    | -         |    15.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1918 | 2024-05-21 | ENCE             | W   | 0.687      | 0.769        | 0.173 (0.091)    | 0.431 (0.228)    | -         |     5.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1974 | 2024-05-19 | AMKAL            | W   | 0.674      | 0.769        | -                | 0.463 (0.240)    | -         |     2.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1989 | 2024-05-18 | OG               | W   | 0.669      | 0.769        | 0.137 (0.070)    | -                | -         |     0.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2279 | 2024-05-10 | Astralis         | L   | 0.615      | -            | -                | -                | -         |    -5.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2323 | 2024-05-08 | FlyQuest         | W   | 0.601      | 0.889        | -                | 0.284 (0.152)    | 1 (0.601) |     1.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2391 | 2024-05-04 | MOUZ             | L   | 0.575      | -            | -                | -                | -         |    -3.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2453 | 2024-05-01 | Monte            | W   | 0.555      | -            | -                | -                | 1 (0.555) |     0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2476 | 2024-04-30 | FURIA            | W   | 0.549      | 0.889        | 0.284 (0.139)    | 0.479 (0.234)    | 1 (0.549) |    10.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2720 | 2024-04-19 | M80              | L   | 0.478      | -            | -                | -                | -         |   -13.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2770 | 2024-04-18 | M80              | W   | 0.471      | -            | -                | -                | -         |     1.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2773 | 2024-04-18 | Legacy           | W   | 0.470      | -            | -                | -                | -         |     0.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2820 | 2024-04-17 | Akimbo           | W   | 0.464      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2825 | 2024-04-17 | straykids        | W   | 0.463      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2938 | 2024-04-12 | FaZe             | L   | 0.427      | -            | -                | -                | -         |    -5.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3023 | 2024-04-10 | MOUZ             | L   | 0.413      | -            | -                | -                | -         |    -2.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3101 | 2024-04-08 | G2               | W   | 0.400      | 0.624        | 1.000 (0.250)    | 0.489 (0.122)    | 1 (0.400) |    11.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3111 | 2024-04-07 | HEROIC           | W   | 0.398      | -            | -                | -                | 1 (0.398) |     5.77 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3783 | 2024-03-07 | SAW              | L   | 0.188      | -            | -                | -                | -         |    -5.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3865 | 2024-03-04 | Complexity       | L   | 0.170      | -            | -                | -                | -         |    -2.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3901 | 2024-03-03 | BOSS             | W   | 0.162      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3914 | 2024-03-02 | FURIA            | L   | 0.155      | -            | -                | -                | -         |    -1.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3929 | 2024-03-01 | BESTIA           | W   | 0.150      | -            | -                | -                | -         |     0.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     4000 | 2024-02-26 | Nouns            | W   | 0.125      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     4002 | 2024-02-26 | BOSS             | W   | 0.123      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4015 | 2024-02-25 | Wildcard         | W   | 0.118      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4020 | 2024-02-25 | Nouns            | L   | 0.117      | -            | -                | -                | -         |    -3.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4079 | 2024-02-22 | Party Astronauts | W   | 0.098      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4081 | 2024-02-22 | MIGHT            | W   | 0.097      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4087 | 2024-02-22 | ex-CatEvil       | W   | 0.097      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($122,756.13)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.769 | $6,000.00      | $4,613.33       |
| 2024-05-23 |      0.701 | $100,000.00    | $70,097.22      |
| 2024-05-12 |      0.628 | $32,000.00     | $20,097.78      |
| 2024-04-14 |      0.440 | $10,000.00     | $4,401.62       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
