### Roster Details<br />
Team Name: Perseverance<br />
Roster: CoJoMo, Gabe, mds, nooz, shutout<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  688.0<br />
<br />
Final Rank Value (688.0) = Starting Rank Value (742.1) + Head To Head Adjustments (-54.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.286[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 742.1
- 400 + ( ( 0.166 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 742.1


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
|           48 |      266 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.23 | CoJoMo, Gabe, mds, nooz, shutout   |
|           47 |      386 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout   |
|           46 |      527 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.51 | CoJoMo, Gabe, mds, shutout, xaler  |
|           45 |      531 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.80 | CoJoMo, Gabe, mds, shutout, xaler  |
|           44 |      591 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.47 | CoJoMo, Gabe, mds, shutout, xaler  |
|           43 |      597 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -16.90 | CoJoMo, Gabe, mds, shutout, xaler  |
|           42 |      943 | 2024-06-14 | Akimbo           | L   | 0.882      | -            | -                | -                | -         |   -11.61 | CoJoMo, Gabe, mds, shutout, xaler  |
|           41 |     1409 | 2024-06-04 | Mythic           | L   | 0.815      | -            | -                | -                | -         |   -10.61 | CoJoMo, Gabe, Louie, mds, shutout  |
|           40 |     1713 | 2024-05-22 | BOSS             | L   | 0.731      | -            | -                | -                | -         |   -11.12 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           39 |     1717 | 2024-05-22 | BOSS             | W   | 0.730      | 0.477        | 0.014 (0.005)    | 0.334 (0.116)    | 0 (0.000) |    12.12 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           38 |     1772 | 2024-05-21 | NRG              | W   | 0.724      | 0.477        | 0.020 (0.007)    | 0.519 (0.179)    | 0 (0.000) |    17.14 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           37 |     1775 | 2024-05-21 | NRG              | L   | 0.724      | -            | -                | -                | -         |    -5.53 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           36 |     1813 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.717      | -            | -                | -                | -         |   -12.46 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           35 |     1817 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.717      | 0.477        | 0.003 (0.001)    | 0.305 (0.104)    | 0 (0.000) |    10.26 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           34 |     1854 | 2024-05-19 | NRG              | L   | 0.710      | -            | -                | -                | -         |    -5.59 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           33 |     1990 | 2024-05-15 | Mythic           | L   | 0.684      | -            | -                | -                | -         |    -9.85 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           32 |     1996 | 2024-05-15 | Mythic           | W   | 0.684      | 0.477        | 0.010 (0.003)    | 0.304 (0.099)    | 0 (0.000) |    11.96 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           31 |     2063 | 2024-05-14 | Elevate          | L   | 0.677      | -            | -                | -                | -         |    -4.43 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           30 |     2066 | 2024-05-14 | Elevate          | L   | 0.676      | -            | -                | -                | -         |    -4.61 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           29 |     2123 | 2024-05-12 | NRG              | L   | 0.663      | -            | -                | -                | -         |    -6.46 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           28 |     2130 | 2024-05-12 | Mythic           | W   | 0.662      | 0.270        | 0.010 (0.002)    | 0.304 (0.054)    | 0 (0.000) |    11.60 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           27 |     2150 | 2024-05-11 | BOSS             | W   | 0.656      | 0.270        | 0.014 (0.003)    | 0.334 (0.059)    | 0 (0.000) |    12.43 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           26 |     2153 | 2024-05-11 | NRG              | L   | 0.656      | -            | -                | -                | -         |    -6.44 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           25 |     2156 | 2024-05-11 | Party Astronauts | W   | 0.655      | 0.270        | 0.042 (0.007)    | 0.532 (0.094)    | 0 (0.000) |    16.05 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           24 |     2219 | 2024-05-08 | Nouns            | L   | 0.637      | -            | -                | -                | -         |    -4.75 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           23 |     2221 | 2024-05-08 | Nouns            | L   | 0.637      | -            | -                | -                | -         |    -4.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           22 |     2744 | 2024-04-17 | Nouns            | L   | 0.496      | -            | -                | -                | -         |    -3.73 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           21 |     2899 | 2024-04-10 | MIGHT            | L   | 0.451      | -            | -                | -                | -         |   -10.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           20 |     2904 | 2024-04-10 | MIGHT            | W   | 0.450      | -            | -                | -                | 0 (0.000) |     3.22 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           19 |     3082 | 2024-04-04 | Carpe Diem       | W   | 0.411      | 0.477        | 0.005 (0.001)    | -                | 0 (0.000) |     5.20 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           18 |     3087 | 2024-04-04 | Carpe Diem       | W   | 0.410      | 0.477        | 0.005 (0.001)    | -                | -         |     5.38 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           17 |     3131 | 2024-04-03 | Limitless        | W   | 0.404      | 0.477        | -                | 0.170 (0.033)    | -         |     4.97 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           16 |     3133 | 2024-04-03 | Limitless        | W   | 0.404      | 0.477        | -                | 0.170 (0.033)    | -         |     5.14 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           15 |     3188 | 2024-04-02 | Party Astronauts | L   | 0.397      | -            | -                | -                | -         |    -2.96 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           14 |     3192 | 2024-04-02 | BOSS             | L   | 0.396      | -            | -                | -                | -         |    -4.95 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           13 |     3275 | 2024-03-27 | M80              | L   | 0.357      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           12 |     3281 | 2024-03-27 | M80              | L   | 0.357      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout |
|           11 |     3405 | 2024-03-20 | LAG              | W   | 0.310      | 0.477        | 0.013 (0.002)    | 0.371 (0.055)    | -         |     6.64 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|           10 |     3407 | 2024-03-20 | LAG              | L   | 0.310      | -            | -                | -                | -         |    -3.18 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            9 |     3423 | 2024-03-19 | Party Astronauts | L   | 0.304      | -            | -                | -                | -         |    -2.27 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            8 |     3425 | 2024-03-19 | Party Astronauts | L   | 0.304      | -            | -                | -                | -         |    -2.31 | BeaKie, CoJoMo, Gabe, mds, X-23    |
|            7 |     3520 | 2024-03-14 | Wildcard         | L   | 0.270      | -            | -                | -                | -         |    -2.27 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            6 |     3523 | 2024-03-14 | Wildcard         | L   | 0.270      | -            | -                | -                | -         |    -2.31 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            5 |     3556 | 2024-03-13 | Mythic           | W   | 0.263      | -            | -                | -                | -         |     4.76 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            4 |     3599 | 2024-03-12 | bubibabu         | W   | 0.257      | -            | -                | -                | -         |     1.05 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            3 |     4040 | 2024-02-22 | MIGHT            | L   | 0.130      | -            | -                | -                | -         |    -3.13 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            2 |     4286 | 2024-02-13 | Take Flyte       | L   | 0.071      | -            | -                | -                | -         |    -1.21 | BeaKie, CoJoMo, Gabe, mds, shutout |
|            1 |     4289 | 2024-02-13 | Take Flyte       | W   | 0.071      | -            | -                | -                | -         |     1.03 | BeaKie, CoJoMo, Gabe, mds, shutout |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,360.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
