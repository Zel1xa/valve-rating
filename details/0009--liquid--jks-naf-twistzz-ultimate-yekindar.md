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
Final Rank Value (1672.6) = Starting Rank Value (1595.7) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.202[<sup>2</sup>](#table1)
- LAN Wins: 0.806[<sup>2</sup>](#table1)

The average of these factors is 0.584<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.7
- 400 + ( ( 0.584 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1595.7


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
|           38 |       50 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.370 (0.215)    | 1 (1.000) |    25.59 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      129 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.370 (0.215)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      173 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.498 (0.289)    | 0.321 (0.187)    | 1 (1.000) |    19.07 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1686 | 2024-05-29 | G2               | L   | 0.749      | -            | -                | -                | -         |    -3.17 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1711 | 2024-05-28 | Falcons          | W   | 0.743      | 0.624        | 0.222 (0.103)    | -                | 1 (0.743) |     6.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1729 | 2024-05-27 | 9z               | L   | 0.737      | -            | -                | -                | -         |   -16.48 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1740 | 2024-05-27 | Complexity       | W   | 0.735      | 0.624        | 0.342 (0.157)    | 0.378 (0.173)    | 1 (0.735) |    13.53 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1814 | 2024-05-23 | Eternal Fire     | L   | 0.707      | -            | -                | -                | -         |    -8.83 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1858 | 2024-05-22 | Astralis         | W   | 0.699      | 0.769        | 0.390 (0.209)    | 0.419 (0.225)    | -         |    15.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1903 | 2024-05-21 | ENCE             | W   | 0.693      | 0.769        | 0.168 (0.089)    | 0.438 (0.233)    | -         |     5.45 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1959 | 2024-05-19 | AMKAL            | W   | 0.680      | 0.769        | -                | 0.472 (0.246)    | -         |     2.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1974 | 2024-05-18 | OG               | W   | 0.675      | 0.769        | 0.138 (0.072)    | -                | -         |     1.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2264 | 2024-05-10 | Astralis         | L   | 0.620      | -            | -                | -                | -         |    -5.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2308 | 2024-05-08 | FlyQuest         | W   | 0.607      | 0.889        | -                | 0.290 (0.157)    | 1 (0.607) |     2.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2376 | 2024-05-04 | MOUZ             | L   | 0.581      | -            | -                | -                | -         |    -3.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2438 | 2024-05-01 | Monte            | W   | 0.561      | -            | -                | -                | 1 (0.561) |     0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2461 | 2024-04-30 | FURIA            | W   | 0.555      | 0.889        | 0.284 (0.140)    | 0.487 (0.240)    | 1 (0.555) |    10.50 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2705 | 2024-04-19 | M80              | L   | 0.483      | -            | -                | -                | -         |   -13.50 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2755 | 2024-04-18 | M80              | W   | 0.477      | -            | -                | -                | -         |     1.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2758 | 2024-04-18 | Legacy           | W   | 0.476      | -            | -                | -                | -         |     0.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2805 | 2024-04-17 | Akimbo           | W   | 0.469      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2810 | 2024-04-17 | straykids        | W   | 0.469      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2923 | 2024-04-12 | FaZe             | L   | 0.433      | -            | -                | -                | -         |    -5.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3008 | 2024-04-10 | MOUZ             | L   | 0.419      | -            | -                | -                | -         |    -2.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3086 | 2024-04-08 | G2               | W   | 0.406      | 0.624        | 1.000 (0.253)    | 0.496 (0.126)    | 1 (0.406) |    11.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3096 | 2024-04-07 | HEROIC           | W   | 0.404      | -            | -                | -                | 1 (0.404) |     5.90 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3768 | 2024-03-07 | SAW              | L   | 0.194      | -            | -                | -                | -         |    -5.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3850 | 2024-03-04 | Complexity       | L   | 0.176      | -            | -                | -                | -         |    -2.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3886 | 2024-03-03 | BOSS             | W   | 0.168      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3899 | 2024-03-02 | FURIA            | L   | 0.161      | -            | -                | -                | -         |    -1.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3914 | 2024-03-01 | BESTIA           | W   | 0.156      | -            | -                | -                | -         |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3985 | 2024-02-26 | Nouns            | W   | 0.130      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3987 | 2024-02-26 | BOSS             | W   | 0.129      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4000 | 2024-02-25 | Wildcard         | W   | 0.124      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4005 | 2024-02-25 | Nouns            | L   | 0.123      | -            | -                | -                | -         |    -3.78 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4064 | 2024-02-22 | Party Astronauts | W   | 0.103      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4066 | 2024-02-22 | MIGHT            | W   | 0.103      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4072 | 2024-02-22 | ex-CatEvil       | W   | 0.103      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($123,648.63)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.775 | $6,000.00      | $4,648.33       |
| 2024-05-23 |      0.707 | $100,000.00    | $70,680.56      |
| 2024-05-12 |      0.634 | $32,000.00     | $20,284.44      |
| 2024-04-14 |      0.446 | $10,000.00     | $4,459.95       |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
