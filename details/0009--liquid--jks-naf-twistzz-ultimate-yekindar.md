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
Final Rank Value:  1672.6<br />
<br />
Final Rank Value (1672.6) = Starting Rank Value (1595.8) + Head To Head Adjustments (76.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.199[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.583<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.8
- 400 + ( ( 0.583 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1595.8


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
|           38 |       59 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    25.59 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      138 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.365 (0.212)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      182 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.498 (0.289)    | 0.317 (0.184)    | 1 (1.000) |    19.05 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1695 | 2024-05-29 | G2               | L   | 0.748      | -            | -                | -                | -         |    -3.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1720 | 2024-05-28 | Falcons          | W   | 0.741      | 0.624        | 0.221 (0.102)    | -                | 1 (0.741) |     6.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1738 | 2024-05-27 | 9z               | L   | 0.735      | -            | -                | -                | -         |   -16.46 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1749 | 2024-05-27 | Complexity       | W   | 0.733      | 0.624        | 0.342 (0.156)    | 0.373 (0.171)    | 1 (0.733) |    13.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1823 | 2024-05-23 | Eternal Fire     | L   | 0.705      | -            | -                | -                | -         |    -8.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1867 | 2024-05-22 | Astralis         | W   | 0.698      | 0.769        | 0.389 (0.209)    | 0.413 (0.222)    | -         |    15.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1912 | 2024-05-21 | ENCE             | W   | 0.691      | 0.769        | 0.174 (0.092)    | 0.432 (0.230)    | -         |     5.50 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1968 | 2024-05-19 | AMKAL            | W   | 0.678      | 0.769        | -                | 0.465 (0.243)    | -         |     2.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1983 | 2024-05-18 | OG               | W   | 0.674      | 0.769        | 0.138 (0.071)    | -                | -         |     1.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2273 | 2024-05-10 | Astralis         | L   | 0.619      | -            | -                | -                | -         |    -5.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2317 | 2024-05-08 | FlyQuest         | W   | 0.605      | 0.889        | -                | 0.286 (0.154)    | 1 (0.605) |     2.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2385 | 2024-05-04 | MOUZ             | L   | 0.580      | -            | -                | -                | -         |    -3.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2447 | 2024-05-01 | Monte            | W   | 0.560      | -            | -                | -                | 1 (0.560) |     0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2470 | 2024-04-30 | FURIA            | W   | 0.553      | 0.889        | 0.284 (0.140)    | 0.481 (0.236)    | 1 (0.553) |    10.46 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2714 | 2024-04-19 | M80              | L   | 0.482      | -            | -                | -                | -         |   -13.46 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2764 | 2024-04-18 | M80              | W   | 0.475      | -            | -                | -                | -         |     1.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2767 | 2024-04-18 | Legacy           | W   | 0.474      | -            | -                | -                | -         |     0.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2814 | 2024-04-17 | Akimbo           | W   | 0.468      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2819 | 2024-04-17 | straykids        | W   | 0.468      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2932 | 2024-04-12 | FaZe             | L   | 0.431      | -            | -                | -                | -         |    -5.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3017 | 2024-04-10 | MOUZ             | L   | 0.417      | -            | -                | -                | -         |    -2.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3095 | 2024-04-08 | G2               | W   | 0.404      | 0.624        | 1.000 (0.252)    | 0.490 (0.124)    | 1 (0.404) |    11.47 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3105 | 2024-04-07 | HEROIC           | W   | 0.403      | -            | -                | -                | 1 (0.403) |     5.86 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3777 | 2024-03-07 | SAW              | L   | 0.192      | -            | -                | -                | -         |    -5.53 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3859 | 2024-03-04 | Complexity       | L   | 0.174      | -            | -                | -                | -         |    -2.29 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3895 | 2024-03-03 | BOSS             | W   | 0.166      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3908 | 2024-03-02 | FURIA            | L   | 0.160      | -            | -                | -                | -         |    -1.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3923 | 2024-03-01 | BESTIA           | W   | 0.154      | -            | -                | -                | -         |     0.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3994 | 2024-02-26 | Nouns            | W   | 0.129      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3996 | 2024-02-26 | BOSS             | W   | 0.128      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4009 | 2024-02-25 | Wildcard         | W   | 0.122      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4014 | 2024-02-25 | Nouns            | L   | 0.121      | -            | -                | -                | -         |    -3.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4073 | 2024-02-22 | Party Astronauts | W   | 0.102      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4075 | 2024-02-22 | MIGHT            | W   | 0.102      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4081 | 2024-02-22 | ex-CatEvil       | W   | 0.101      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($123,414.88)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.773 | $6,000.00      | $4,639.17       |
| 2024-05-23 |      0.705 | $100,000.00    | $70,527.78      |
| 2024-05-12 |      0.632 | $32,000.00     | $20,235.56      |
| 2024-04-14 |      0.444 | $10,000.00     | $4,444.68       |
| 2024-03-10 |      0.214 | $5,000.00      | $1,067.71       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
