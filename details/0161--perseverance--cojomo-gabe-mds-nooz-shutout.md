### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [161](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  684.7<br />
<br />
Final Rank Value (684.7) = Starting Rank Value (738.4) + Head To Head Adjustments (-53.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 738.4
- 400 + ( ( 0.165 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 738.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      328 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.32 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      446 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -6.00 | CoJoMo, Gabe, mds, nooz, shutout   |
|           45 |      580 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -6.02 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      584 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -6.37 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      641 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.62 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      647 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.06 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |      972 | 2024-06-14 | Akimbo           | L   | 0.868      | -            | -                | -                | -         |   -11.63 | CoJoMo, Gabe, mds, shutout, xaler  |
|           40 |     1411 | 2024-06-04 | Mythic           | L   | 0.800      | -            | -                | -                | -         |   -10.62 | CoJoMo, Gabe, Louie, mds, shutout  |
|           39 |     1708 | 2024-05-22 | BOSS             | L   | 0.716      | -            | -                | -                | -         |   -10.81 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1712 | 2024-05-22 | BOSS             | W   | 0.716      | 0.477        | 0.014 (0.005)    | 0.344 (0.118)    | 0 (0.000) |    11.98 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1757 | 2024-05-21 | NRG              | W   | 0.709      | 0.477        | 0.020 (0.007)    | 0.538 (0.182)    | 0 (0.000) |    16.53 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1759 | 2024-05-21 | NRG              | L   | 0.709      | -            | -                | -                | -         |    -5.70 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1792 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.702      | -            | -                | -                | -         |   -12.28 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1796 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.702      | 0.477        | 0.003 (0.001)    | 0.283 (0.095)    | 0 (0.000) |     9.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     1958 | 2024-05-15 | Mythic           | L   | 0.669      | -            | -                | -                | -         |    -9.63 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     1964 | 2024-05-15 | Mythic           | W   | 0.669      | 0.477        | 0.010 (0.003)    | 0.311 (0.099)    | 0 (0.000) |    11.71 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2025 | 2024-05-14 | Elevate          | L   | 0.662      | -            | -                | -                | -         |    -5.09 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2028 | 2024-05-14 | Elevate          | L   | 0.662      | -            | -                | -                | -         |    -5.32 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2082 | 2024-05-12 | NRG              | L   | 0.649      | -            | -                | -                | -         |    -6.36 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2089 | 2024-05-12 | Mythic           | W   | 0.647      | 0.270        | 0.010 (0.002)    | 0.311 (0.054)    | 0 (0.000) |    11.32 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2109 | 2024-05-11 | BOSS             | W   | 0.641      | 0.270        | 0.014 (0.002)    | 0.344 (0.060)    | 0 (0.000) |    12.02 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2112 | 2024-05-11 | NRG              | L   | 0.641      | -            | -                | -                | -         |    -6.32 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2115 | 2024-05-11 | Party Astronauts | W   | 0.641      | 0.270        | 0.041 (0.007)    | 0.550 (0.095)    | 0 (0.000) |    15.53 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2178 | 2024-05-08 | Nouns            | L   | 0.622      | -            | -                | -                | -         |    -4.84 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2179 | 2024-05-08 | Nouns            | L   | 0.622      | -            | -                | -                | -         |    -5.04 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2688 | 2024-04-17 | Nouns            | L   | 0.481      | -            | -                | -                | -         |    -3.77 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2840 | 2024-04-10 | MIGHT            | L   | 0.436      | -            | -                | -                | -         |   -10.60 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2845 | 2024-04-10 | MIGHT            | W   | 0.436      | -            | -                | -                | 0 (0.000) |     3.13 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3023 | 2024-04-04 | Carpe Diem       | W   | 0.396      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     5.04 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3028 | 2024-04-04 | Carpe Diem       | W   | 0.396      | 0.477        | 0.005 (0.001)    | -                | -         |     5.21 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3071 | 2024-04-03 | Limitless        | W   | 0.389      | 0.477        | -                | 0.174 (0.032)    | -         |     4.81 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3073 | 2024-04-03 | Limitless        | W   | 0.389      | 0.477        | -                | 0.174 (0.032)    | -         |     4.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3121 | 2024-04-02 | Party Astronauts | L   | 0.383      | -            | -                | -                | -         |    -2.83 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3125 | 2024-04-02 | BOSS             | L   | 0.381      | -            | -                | -                | -         |    -4.89 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3208 | 2024-03-27 | M80              | L   | 0.342      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3214 | 2024-03-27 | M80              | L   | 0.342      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3328 | 2024-03-20 | LAG              | W   | 0.296      | 0.477        | 0.012 (0.002)    | 0.353 (0.050)    | -         |     6.25 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3330 | 2024-03-20 | LAG              | L   | 0.296      | -            | -                | -                | -         |    -3.10 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3346 | 2024-03-19 | Party Astronauts | L   | 0.290      | -            | -                | -                | -         |    -2.20 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3348 | 2024-03-19 | Party Astronauts | L   | 0.289      | -            | -                | -                | -         |    -2.23 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3442 | 2024-03-14 | Wildcard         | L   | 0.256      | -            | -                | -                | -         |    -2.18 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3445 | 2024-03-14 | Wildcard         | L   | 0.255      | -            | -                | -                | -         |    -2.21 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3474 | 2024-03-13 | Mythic           | W   | 0.248      | -            | -                | -                | -         |     4.47 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3516 | 2024-03-12 | bubibabu         | W   | 0.242      | -            | -                | -                | -         |     1.01 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     3941 | 2024-02-22 | MIGHT            | L   | 0.115      | -            | -                | -                | -         |    -2.77 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4184 | 2024-02-13 | Take Flyte       | L   | 0.056      | -            | -                | -                | -         |    -0.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4187 | 2024-02-13 | Take Flyte       | W   | 0.056      | -            | -                | -                | -         |     0.82 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,336.52)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
