### Roster Details<br />
Team Name: 1WIN<br />
Roster: buster, HObbit, lattykk, neaLaN, Ryujin<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.5<br />
<br />
Final Rank Value (949.5) = Starting Rank Value (889.7) + Head To Head Adjustments (59.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.176[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 889.7
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 889.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |       26 | 2024-08-03 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -16.12 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           41 |      137 | 2024-07-31 | Into the Breach | W   | 1.000      | 0.435        | -                | 0.236 (0.103)    | 0 (0.000) |     7.08 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           40 |      179 | 2024-07-30 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |   -11.49 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           39 |      202 | 2024-07-29 | CYBERSHOKE      | L   | 1.000      | -            | -                | -                | -         |   -17.36 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           38 |      214 | 2024-07-29 | NOM             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.16 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           37 |      252 | 2024-07-28 | TSM             | W   | 1.000      | 0.143        | 0.040 (0.006)    | -                | 0 (0.000) |    16.53 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           36 |      265 | 2024-07-27 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.364 (0.158)    | 0 (0.000) |    11.33 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           35 |      362 | 2024-07-24 | BC.Game         | W   | 1.000      | 0.435        | -                | 0.275 (0.120)    | 0 (0.000) |     7.14 | buster, HObbit, lattykk, neaLaN, Ryujin |
|           34 |     1257 | 2024-06-08 | Monte           | L   | 0.822      | -            | -                | -                | -         |   -10.86 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           33 |     1258 | 2024-06-08 | Quixal          | W   | 0.821      | -            | -                | -                | 0 (0.000) |     1.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           32 |     1268 | 2024-06-08 | AMKAL           | L   | 0.821      | -            | -                | -                | -         |    -5.79 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           31 |     1389 | 2024-06-06 | FAVBET          | L   | 0.807      | -            | -                | -                | -         |   -18.54 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           30 |     1567 | 2024-06-01 | Insilio         | L   | 0.775      | -            | -                | -                | -         |   -13.95 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           29 |     1625 | 2024-05-30 | V1dar           | W   | 0.761      | -            | -                | -                | 0 (0.000) |     1.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           28 |     1712 | 2024-05-26 | 9 Pandas        | L   | 0.734      | -            | -                | -                | -         |   -10.10 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           27 |     1737 | 2024-05-25 | FURIA           | W   | 0.727      | 0.435        | 0.284 (0.090)    | 0.491 (0.155)    | 0 (0.000) |    22.19 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           26 |     1761 | 2024-05-23 | ECSTATIC        | W   | 0.715      | -            | -                | -                | 0 (0.000) |     0.82 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           25 |     1935 | 2024-05-18 | SINNERS         | W   | 0.681      | 0.435        | 0.037 (0.011)    | 0.758 (0.224)    | 0 (0.000) |    12.78 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           24 |     2015 | 2024-05-16 | Zero Tenacity   | W   | 0.667      | 0.435        | 0.137 (0.040)    | 1.000 (0.290)    | -         |    13.80 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           23 |     2137 | 2024-05-13 | Permitta        | W   | 0.649      | 0.435        | 0.024 (0.007)    | 0.876 (0.247)    | -         |     9.05 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           22 |     2239 | 2024-05-09 | Sashi           | L   | 0.621      | -            | -                | -                | -         |    -3.72 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           21 |     2265 | 2024-05-08 | Nemiga          | W   | 0.613      | 0.396        | 0.317 (0.077)    | 0.695 (0.169)    | -         |    15.16 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           20 |     2275 | 2024-05-07 | BLEED           | W   | 0.608      | 0.396        | 0.091 (0.022)    | 0.397 (0.096)    | -         |    13.21 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           19 |     2323 | 2024-05-05 | ex-Guild Eagles | W   | 0.593      | -            | -                | -                | -         |     7.37 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           18 |     2367 | 2024-05-02 | Soda            | W   | 0.575      | -            | -                | -                | -         |     0.96 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           17 |     2375 | 2024-05-02 | 500             | W   | 0.574      | -            | -                | -                | -         |     4.74 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           16 |     2438 | 2024-04-29 | ECLOT           | L   | 0.555      | -            | -                | -                | -         |    -3.07 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           15 |     2440 | 2024-04-29 | SINNERS         | L   | 0.554      | -            | -                | -                | -         |    -5.75 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           14 |     2456 | 2024-04-28 | Sangal          | L   | 0.549      | -            | -                | -                | -         |    -4.32 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           13 |     2488 | 2024-04-27 | Nemiga          | L   | 0.541      | -            | -                | -                | -         |    -3.68 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           12 |     2537 | 2024-04-25 | Permitta        | W   | 0.528      | 0.435        | 0.024 (0.005)    | 0.876 (0.201)    | -         |     9.34 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           11 |     2576 | 2024-04-23 | HAVU            | W   | 0.514      | -            | -                | -                | -         |     3.73 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|           10 |     2615 | 2024-04-21 | Nemiga          | L   | 0.500      | -            | -                | -                | -         |    -3.45 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            9 |     2635 | 2024-04-20 | Portugal        | W   | 0.495      | -            | -                | -                | -         |     3.47 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            8 |     2807 | 2024-04-16 | ENCE Academy    | W   | 0.468      | -            | -                | -                | -         |     4.02 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            7 |     2835 | 2024-04-15 | Lazer Cats      | W   | 0.459      | -            | -                | -                | -         |     1.59 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            6 |     2999 | 2024-04-09 | Aurora          | L   | 0.421      | -            | -                | -                | -         |    -0.20 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            5 |     3020 | 2024-04-08 | 9 Pandas        | W   | 0.415      | 0.143        | 0.082 (0.005)    | -                | -         |     8.40 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            4 |     3032 | 2024-04-08 | Aurora          | W   | 0.414      | 0.143        | 0.424 (0.025)    | -                | -         |    12.88 | buster, Jyo, lattykk, neaLaN, Ryujin    |
|            3 |     3624 | 2024-03-11 | Insilio         | L   | 0.228      | -            | -                | -                | -         |    -3.56 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            2 |     3646 | 2024-03-10 | VP.Prodigy      | W   | 0.221      | -            | -                | -                | -         |     3.30 | buster, lattykk, neaLaN, oz1k, Ryujin   |
|            1 |     3774 | 2024-03-05 | ARCRED          | L   | 0.189      | -            | -                | -                | -         |    -3.20 | buster, lattykk, neaLaN, oz1k, Ryujin   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,639.44)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.735 | $5,000.00      | $3,675.00       |
| 2024-05-09 |      0.621 | $8,000.00      | $4,964.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
