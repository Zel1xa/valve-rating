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
Final Rank Value:  1626.8<br />
<br />
Final Rank Value (1626.8) = Starting Rank Value (1566.3) + Head To Head Adjustments (60.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.698[<sup>1</sup>](#table2)
- Bounty Collected: 0.630[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.856[<sup>2</sup>](#table1)

The average of these factors is 0.602<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1566.3
- 400 + ( ( 0.602 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1566.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      190 | 2024-09-01 | Legacy        | W   | 1.000      | -            | -                | -                | -         |     1.24 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |      193 | 2024-09-01 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | -         |     0.25 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           34 |      208 | 2024-08-31 | Legacy        | L   | 1.000      | -            | -                | -                | -         |   -30.45 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           33 |      211 | 2024-08-31 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | -         |     0.20 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           32 |      874 | 2024-08-13 | FaZe          | L   | 1.000      | -            | -                | -                | -         |   -12.83 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           31 |      886 | 2024-08-13 | Complexity    | W   | 1.000      | 1.000        | 0.337 (0.337)    | 0.367 (0.367)    | 1 (1.000) |     9.19 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           30 |      936 | 2024-08-12 | FURIA         | W   | 1.000      | 1.000        | 0.319 (0.319)    | 0.513 (0.513)    | 1 (1.000) |    11.97 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           29 |      981 | 2024-08-10 | FaZe          | L   | 1.000      | -            | -                | -                | -         |   -12.95 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           28 |     1029 | 2024-08-08 | FURIA         | W   | 0.994      | -            | -                | -                | 1 (0.994) |    12.18 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           27 |     1056 | 2024-08-07 | paiN          | W   | 0.988      | 0.143        | -                | 0.935 (0.132)    | 1 (0.988) |    10.90 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           26 |     1197 | 2024-08-03 | Natus Vincere | W   | 0.962      | 0.581        | 1.000 (0.559)    | 0.473 (0.264)    | 1 (0.962) |    26.11 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           25 |     1276 | 2024-08-01 | Natus Vincere | W   | 0.948      | 0.581        | 1.000 (0.551)    | 0.473 (0.260)    | 1 (0.948) |    26.67 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           24 |     1320 | 2024-07-31 | Virtus.pro    | W   | 0.941      | 0.581        | 0.520 (0.284)    | 0.288 (0.158)    | 1 (0.941) |    14.07 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           23 |     2836 | 2024-05-29 | G2            | L   | 0.523      | -            | -                | -                | -         |    -1.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2861 | 2024-05-28 | Falcons       | W   | 0.516      | 0.624        | 0.297 (0.096)    | 0.477 (0.154)    | 1 (0.516) |     6.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2879 | 2024-05-27 | 9z            | L   | 0.510      | -            | -                | -                | -         |   -11.29 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2890 | 2024-05-27 | Complexity    | W   | 0.508      | 0.624        | 0.337 (0.107)    | -                | 1 (0.508) |     7.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2964 | 2024-05-23 | Eternal Fire  | L   | 0.480      | -            | -                | -                | -         |    -2.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     3008 | 2024-05-22 | Astralis      | W   | 0.473      | 0.769        | 0.343 (0.125)    | -                | -         |     7.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     3053 | 2024-05-21 | ENCE          | W   | 0.466      | -            | -                | -                | -         |     1.84 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     3109 | 2024-05-19 | AMKAL         | W   | 0.453      | 0.769        | -                | 0.397 (0.138)    | -         |     1.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3124 | 2024-05-18 | OG            | W   | 0.449      | 0.769        | -                | 0.352 (0.121)    | -         |     0.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3414 | 2024-05-10 | Astralis      | L   | 0.394      | -            | -                | -                | -         |    -6.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3458 | 2024-05-08 | FlyQuest      | W   | 0.380      | -            | -                | -                | 1 (0.380) |     0.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3526 | 2024-05-04 | MOUZ          | L   | 0.355      | -            | -                | -                | -         |    -1.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3588 | 2024-05-01 | Monte         | W   | 0.335      | -            | -                | -                | -         |     0.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3611 | 2024-04-30 | FURIA         | W   | 0.328      | 0.889        | 0.319 (0.093)    | 0.513 (0.149)    | -         |     5.89 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3855 | 2024-04-19 | M80           | L   | 0.257      | -            | -                | -                | -         |    -7.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3905 | 2024-04-18 | M80           | W   | 0.250      | -            | -                | -                | -         |     0.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3908 | 2024-04-18 | Legacy        | W   | 0.249      | -            | -                | -                | -         |     0.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3955 | 2024-04-17 | Akimbo        | W   | 0.243      | -            | -                | -                | -         |     0.06 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3960 | 2024-04-17 | straykids     | W   | 0.243      | -            | -                | -                | -         |     0.04 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4073 | 2024-04-12 | FaZe          | L   | 0.206      | -            | -                | -                | -         |    -1.77 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4158 | 2024-04-10 | MOUZ          | L   | 0.192      | -            | -                | -                | -         |    -1.03 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4236 | 2024-04-08 | G2            | W   | 0.179      | 0.624        | 1.000 (0.112)    | -                | -         |     5.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4246 | 2024-04-07 | HEROIC        | W   | 0.178      | -            | -                | -                | -         |     1.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($112,286.52)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $24,000.00     | $24,000.00      |
| 2024-08-04 |      0.967 | $22,500.00     | $21,759.90      |
| 2024-06-02 |      0.548 | $6,000.00      | $3,288.33       |
| 2024-05-23 |      0.480 | $100,000.00    | $48,013.89      |
| 2024-05-12 |      0.407 | $32,000.00     | $13,031.11      |
| 2024-04-14 |      0.219 | $10,000.00     | $2,193.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
