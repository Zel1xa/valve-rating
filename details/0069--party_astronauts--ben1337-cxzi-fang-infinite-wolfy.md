### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
<br />
Final Rank Value:  966.0<br />
<br />
Final Rank Value (966.0) = Starting Rank Value (923.0) + Head To Head Adjustments (43.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.176[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 923.0
- 400 + ( ( 0.254 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 923.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           73 |       60 | 2024-08-03 | Elevate       | L   | 1.000      | -            | -                | -                | -         |   -19.14 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           72 |      220 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.502 (0.239)    | 0 (0.000) |    15.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      224 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.502 (0.239)    | 0 (0.000) |    16.94 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      451 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | 0.477        | -                | 0.304 (0.145)    | 0 (0.000) |     6.54 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      453 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -25.52 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      539 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -20.59 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      675 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.40 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      679 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.68 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      741 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      747 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.52 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |     1083 | 2024-06-15 | Falcons       | L   | 0.852      | -            | -                | -                | -         |    -2.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |     1127 | 2024-06-14 | The MongolZ   | L   | 0.845      | -            | -                | -                | -         |    -0.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1238 | 2024-06-09 | Legacy        | L   | 0.817      | -            | -                | -                | -         |   -11.60 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1306 | 2024-06-08 | Wildcard      | W   | 0.809      | 0.384        | 0.048 (0.015)    | 0.418 (0.130)    | 0 (0.000) |    11.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1324 | 2024-06-08 | NRG           | L   | 0.808      | -            | -                | -                | -         |   -15.48 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1356 | 2024-06-07 | Nouns         | L   | 0.804      | -            | -                | -                | -         |   -12.98 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1364 | 2024-06-07 | Legacy        | W   | 0.803      | 0.143        | 0.122 (0.014)    | -                | 0 (0.000) |    13.71 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1370 | 2024-06-07 | NRG           | W   | 0.802      | 0.384        | -                | 0.502 (0.155)    | -         |     9.90 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1383 | 2024-06-07 | Nouns         | W   | 0.801      | -            | -                | -                | -         |    13.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1414 | 2024-06-06 | NRG           | W   | 0.797      | 0.477        | 0.020 (0.008)    | 0.502 (0.191)    | -         |    11.02 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1433 | 2024-06-06 | E-Xolos LAZER | W   | 0.795      | -            | -                | -                | -         |     6.84 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1484 | 2024-06-05 | Wildcard      | L   | 0.790      | -            | -                | -                | -         |   -12.87 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1535 | 2024-06-04 | Elevate       | W   | 0.784      | 0.477        | 0.027 (0.010)    | 0.501 (0.187)    | -         |    13.77 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1844 | 2024-05-22 | Nouns         | L   | 0.697      | -            | -                | -                | -         |   -10.73 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1853 | 2024-05-22 | M80           | W   | 0.697      | 0.477        | 0.188 (0.062)    | 0.563 (0.187)    | -         |    18.58 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1857 | 2024-05-22 | M80           | L   | 0.696      | -            | -                | -                | -         |    -3.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1891 | 2024-05-21 | Limitless     | W   | 0.691      | -            | -                | -                | -         |     3.20 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1894 | 2024-05-21 | Limitless     | W   | 0.690      | -            | -                | -                | -         |     3.30 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1927 | 2024-05-20 | Akimbo        | W   | 0.684      | -            | -                | -                | -         |     6.10 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1996 | 2024-05-18 | NRG           | L   | 0.669      | -            | -                | -                | -         |   -10.55 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     2029 | 2024-05-17 | Legacy        | W   | 0.663      | 0.303        | 0.122 (0.024)    | -                | -         |    12.94 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     2057 | 2024-05-16 | FLUFFY AIMERS | W   | 0.657      | -            | -                | -                | -         |     5.46 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     2060 | 2024-05-16 | FLUFFY AIMERS | W   | 0.657      | -            | -                | -                | -         |     5.71 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2150 | 2024-05-14 | Mythic        | W   | 0.644      | -            | -                | -                | -         |     6.91 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2157 | 2024-05-14 | Mythic        | L   | 0.644      | -            | -                | -                | -         |   -13.72 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2250 | 2024-05-11 | BOSS          | L   | 0.622      | -            | -                | -                | -         |   -13.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2254 | 2024-05-11 | Phoenix       | L   | 0.622      | -            | -                | -                | -         |   -15.08 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2313 | 2024-05-08 | LAG           | W   | 0.604      | -            | -                | -                | -         |     6.67 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2318 | 2024-05-08 | LAG           | W   | 0.604      | -            | -                | -                | -         |     7.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2338 | 2024-05-07 | Elevate       | L   | 0.597      | -            | -                | -                | -         |    -8.62 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2339 | 2024-05-07 | Elevate       | W   | 0.597      | 0.477        | 0.027 (0.008)    | 0.501 (0.143)    | -         |    10.44 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2357 | 2024-05-06 | NRG           | L   | 0.590      | -            | -                | -                | -         |   -11.45 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2358 | 2024-05-06 | NRG           | W   | 0.590      | 0.477        | -                | 0.502 (0.141)    | -         |     7.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2429 | 2024-05-02 | Wildcard      | L   | 0.564      | -            | -                | -                | -         |   -10.46 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2430 | 2024-05-02 | Wildcard      | W   | 0.563      | 0.477        | 0.048 (0.013)    | -                | -         |     7.40 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2566 | 2024-04-27 | Aurora        | L   | 0.525      | -            | -                | -                | -         |    -0.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2568 | 2024-04-26 | sunday school | W   | 0.524      | -            | -                | -                | 1 (0.524) |     2.50 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2595 | 2024-04-25 | Aurora        | L   | 0.517      | -            | -                | -                | -         |    -0.32 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     3035 | 2024-04-09 | Take Flyte    | W   | 0.410      | -            | -                | -                | -         |     2.73 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     3041 | 2024-04-09 | Take Flyte    | W   | 0.410      | -            | -                | -                | -         |     2.79 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3165 | 2024-04-04 | MIGHT         | W   | 0.377      | -            | -                | -                | -         |     1.14 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3172 | 2024-04-04 | MIGHT         | W   | 0.377      | -            | -                | -                | -         |     1.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3262 | 2024-04-02 | Phoenix       | W   | 0.364      | -            | -                | -                | -         |     2.80 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3265 | 2024-04-02 | Nouns         | L   | 0.363      | -            | -                | -                | -         |    -5.95 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3343 | 2024-03-27 | Carpe Diem    | W   | 0.324      | -            | -                | -                | -         |     2.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3346 | 2024-03-27 | Carpe Diem    | W   | 0.324      | -            | -                | -                | -         |     2.03 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3388 | 2024-03-26 | Nouns         | L   | 0.318      | -            | -                | -                | -         |    -5.28 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3393 | 2024-03-26 | Nouns         | L   | 0.317      | -            | -                | -                | -         |    -5.42 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3471 | 2024-03-20 | BOSS          | W   | 0.277      | -            | -                | -                | -         |     2.88 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3473 | 2024-03-20 | BOSS          | W   | 0.277      | -            | -                | -                | -         |     2.94 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3492 | 2024-03-19 | Phoenix       | W   | 0.271      | -            | -                | -                | -         |     2.09 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3494 | 2024-03-19 | Phoenix       | W   | 0.270      | -            | -                | -                | -         |     2.13 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3622 | 2024-03-13 | Carpe Diem    | W   | 0.229      | -            | -                | -                | -         |     1.47 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3663 | 2024-03-12 | Elevate       | W   | 0.224      | -            | -                | -                | -         |     4.24 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     4043 | 2024-02-24 | Wildcard      | L   | 0.110      | -            | -                | -                | -         |    -1.98 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     4049 | 2024-02-24 | ex-CatEvil    | W   | 0.110      | -            | -                | -                | -         |     0.17 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4085 | 2024-02-22 | Liquid        | L   | 0.097      | -            | -                | -                | -         |    -0.07 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4086 | 2024-02-22 | NRG           | W   | 0.097      | -            | -                | -                | -         |     1.22 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4092 | 2024-02-22 | Take Flyte    | W   | 0.096      | -            | -                | -                | -         |     0.71 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4139 | 2024-02-20 | NRG           | W   | 0.084      | -            | -                | -                | -         |     1.06 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4141 | 2024-02-20 | Mythic        | W   | 0.083      | -            | -                | -                | -         |     0.85 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4164 | 2024-02-19 | NRG           | L   | 0.077      | -            | -                | -                | -         |    -1.46 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4167 | 2024-02-19 | Akimbo        | W   | 0.076      | -            | -                | -                | -         |     0.68 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,118.56)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $2,000.00      | $1,720.93       |
| 2024-06-09 |      0.817 | $5,000.00      | $4,084.26       |
| 2024-06-09 |      0.817 | $7,000.00      | $5,716.02       |
| 2024-04-28 |      0.532 | $3,000.00      | $1,597.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
