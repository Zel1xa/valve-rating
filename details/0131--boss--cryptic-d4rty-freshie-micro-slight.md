### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, freshie, micro, SLIGHT<br />
Global Rank: [131](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  783.1<br />
<br />
Final Rank Value (783.1) = Starting Rank Value (808.3) + Head To Head Adjustments (-25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.123[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.3
- 400 + ( ( 0.199 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 808.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |       62 | 2024-08-03 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           57 |      170 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.34 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           56 |      174 | 2024-07-31 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.95 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           55 |      220 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -7.50 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           54 |      221 | 2024-07-30 | Nouns             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           53 |      541 | 2024-07-20 | NRG               | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           52 |      610 | 2024-07-18 | Elevate           | W   | 1.000      | 0.477        | 0.027 (0.013)    | 0.501 (0.239)    | 0 (0.000) |    21.85 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           51 |      612 | 2024-07-18 | Elevate           | L   | 1.000      | -            | -                | -                | -         |    -9.20 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           50 |      672 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    16.32 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           49 |      679 | 2024-07-17 | LAG               | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    17.82 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           48 |      788 | 2024-07-15 | Mythic            | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.285 (0.136)    | 0 (0.000) |    16.89 | Cryptic, d4rty, freshie, micro, SLIGHT   |
|           47 |     1048 | 2024-06-15 | Elevate           | L   | 0.858      | -            | -                | -                | -         |    -6.49 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           46 |     1097 | 2024-06-14 | Final Form        | W   | 0.848      | -            | -                | -                | 0 (0.000) |     6.23 | Cryptic, d4rty, freshie, Momo, Pluto     |
|           45 |     1534 | 2024-06-04 | Mythic            | L   | 0.784      | -            | -                | -                | -         |   -11.07 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           44 |     1844 | 2024-05-22 | Phoenix           | W   | 0.698      | 0.477        | -                | 0.271 (0.090)    | 0 (0.000) |    10.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           43 |     1848 | 2024-05-22 | Phoenix           | L   | 0.697      | -            | -                | -                | -         |   -11.69 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           42 |     1929 | 2024-05-20 | Limitless         | L   | 0.684      | -            | -                | -                | -         |   -10.78 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           41 |     1933 | 2024-05-20 | Limitless         | W   | 0.684      | -            | -                | -                | 0 (0.000) |    10.97 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           40 |     1964 | 2024-05-19 | M80               | L   | 0.677      | -            | -                | -                | -         |    -1.52 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           39 |     1965 | 2024-05-19 | M80               | L   | 0.676      | -            | -                | -                | -         |    -1.55 | Cryptic, d4rty, freshie, Pluto, PwnAlone |
|           38 |     2028 | 2024-05-17 | NRG               | L   | 0.663      | -            | -                | -                | -         |    -6.64 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     2092 | 2024-05-15 | Wildcard          | L   | 0.651      | -            | -                | -                | -         |    -7.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     2102 | 2024-05-15 | Wildcard          | L   | 0.651      | -            | -                | -                | -         |    -7.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     2151 | 2024-05-14 | MIGHT             | W   | 0.644      | -            | -                | -                | 0 (0.000) |     3.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     2159 | 2024-05-14 | MIGHT             | W   | 0.644      | -            | -                | -                | 0 (0.000) |     3.61 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     2246 | 2024-05-11 | Phoenix           | L   | 0.623      | -            | -                | -                | -         |   -11.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     2248 | 2024-05-11 | Party Astronauts  | W   | 0.623      | 0.270        | 0.041 (0.007)    | 0.510 (0.086)    | -         |    13.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     2251 | 2024-05-11 | NRG               | L   | 0.622      | -            | -                | -                | -         |    -8.05 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     2290 | 2024-05-09 | Nouns             | L   | 0.611      | -            | -                | -                | -         |    -6.20 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     2295 | 2024-05-09 | Nouns             | L   | 0.611      | -            | -                | -                | -         |    -6.51 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2411 | 2024-05-03 | Ninjas in Pyjamas | L   | 0.568      | -            | -                | -                | -         |    -0.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           27 |     2448 | 2024-05-02 | FlyQuest          | L   | 0.560      | -            | -                | -                | -         |    -2.17 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           26 |     2469 | 2024-05-01 | BIG               | L   | 0.553      | -            | -                | -                | -         |    -1.22 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           25 |     2616 | 2024-04-24 | Mythic            | L   | 0.511      | -            | -                | -                | -         |    -9.68 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           24 |     2617 | 2024-04-24 | Mythic            | W   | 0.511      | 0.477        | 0.010 (0.002)    | 0.285 (0.069)    | -         |     6.51 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           23 |     2946 | 2024-04-11 | Limitless         | W   | 0.424      | -            | -                | -                | -         |     3.65 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           22 |     2948 | 2024-04-11 | Limitless         | W   | 0.424      | -            | -                | -                | -         |     3.76 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           21 |     2977 | 2024-04-10 | NRG               | L   | 0.417      | -            | -                | -                | -         |    -5.99 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           20 |     2981 | 2024-04-10 | NRG               | W   | 0.417      | 0.477        | 0.020 (0.004)    | 0.502 (0.100)    | -         |     7.32 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           19 |     3034 | 2024-04-09 | LAG               | W   | 0.411      | 0.477        | 0.012 (0.002)    | 0.376 (0.074)    | -         |     6.95 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           18 |     3037 | 2024-04-09 | LAG               | W   | 0.411      | 0.477        | 0.012 (0.002)    | 0.376 (0.074)    | -         |     7.20 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           17 |     3166 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.377      | -            | -                | -                | -         |     5.21 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           16 |     3172 | 2024-04-04 | FLUFFY AIMERS     | W   | 0.377      | -            | -                | -                | -         |     5.39 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           15 |     3223 | 2024-04-03 | Party Astronauts  | L   | 0.370      | -            | -                | -                | -         |    -9.62 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           14 |     3259 | 2024-04-02 | Nouns             | L   | 0.364      | -            | -                | -                | -         |    -3.89 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           13 |     3264 | 2024-04-02 | Phoenix           | W   | 0.363      | -            | -                | -                | -         |     4.60 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           12 |     3340 | 2024-03-27 | Take Flyte        | W   | 0.324      | -            | -                | -                | -         |     3.87 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           11 |     3343 | 2024-03-27 | Take Flyte        | L   | 0.324      | -            | -                | -                | -         |    -6.47 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           10 |     3388 | 2024-03-26 | Elevate           | L   | 0.318      | -            | -                | -                | -         |    -2.52 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            9 |     3393 | 2024-03-26 | Elevate           | L   | 0.318      | -            | -                | -                | -         |    -2.57 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            8 |     3469 | 2024-03-20 | Party Astronauts  | L   | 0.278      | -            | -                | -                | -         |    -2.88 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            7 |     3471 | 2024-03-20 | Party Astronauts  | L   | 0.278      | -            | -                | -                | -         |    -2.94 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            6 |     3905 | 2024-03-03 | Liquid            | L   | 0.161      | -            | -                | -                | -         |    -0.07 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            5 |     3922 | 2024-03-02 | Complexity        | L   | 0.155      | -            | -                | -                | -         |    -0.04 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            4 |     3937 | 2024-03-01 | MIBR              | W   | 0.149      | 0.143        | 0.208 (0.004)    | -                | 1 (0.149) |     4.55 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            3 |     4006 | 2024-02-26 | Liquid            | L   | 0.123      | -            | -                | -                | -         |    -0.05 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            2 |     4020 | 2024-02-25 | Nouns             | L   | 0.118      | -            | -                | -                | -         |    -1.36 | brett, Cryptic, d4rty, freshie, PwnAlone |
|            1 |     4023 | 2024-02-25 | Wildcard          | W   | 0.117      | -            | -                | -                | -         |     2.19 | brett, Cryptic, d4rty, freshie, PwnAlone |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,479.13)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $648.02         |
| 2024-06-09 |      0.817 | $2,000.00      | $1,633.89       |
| 2024-05-12 |      0.628 | $3,500.00      | $2,197.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
