### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.6<br />
<br />
Final Rank Value (695.6) = Starting Rank Value (736.4) + Head To Head Adjustments (-40.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.4
- 400 + ( ( 0.164 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 736.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |       48 | 2024-08-03 | DETONATE         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.73 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      414 | 2024-07-24 | Aether           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      532 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.53 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      666 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.49 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      670 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.79 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      730 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.57 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      736 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.01 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1083 | 2024-06-14 | Akimbo           | L   | 0.852      | -            | -                | -                | -         |   -11.44 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1535 | 2024-06-04 | Mythic           | L   | 0.785      | -            | -                | -                | -         |   -10.47 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1836 | 2024-05-22 | BOSS             | L   | 0.700      | -            | -                | -                | -         |   -10.56 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1840 | 2024-05-22 | BOSS             | W   | 0.700      | 0.477        | 0.014 (0.005)    | 0.326 (0.109)    | 0 (0.000) |    11.74 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1885 | 2024-05-21 | NRG              | W   | 0.694      | 0.477        | 0.020 (0.007)    | 0.514 (0.170)    | 0 (0.000) |    16.10 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1887 | 2024-05-21 | NRG              | L   | 0.693      | -            | -                | -                | -         |    -5.66 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1920 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.687      | -            | -                | -                | -         |   -11.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1924 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.686      | 0.477        | 0.003 (0.001)    | 0.311 (0.102)    | 0 (0.000) |     9.95 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2087 | 2024-05-15 | Mythic           | L   | 0.654      | -            | -                | -                | -         |    -9.45 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2093 | 2024-05-15 | Mythic           | W   | 0.653      | 0.477        | 0.010 (0.003)    | 0.292 (0.091)    | 0 (0.000) |    11.40 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2154 | 2024-05-14 | Elevate          | L   | 0.646      | -            | -                | -                | -         |    -4.29 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2157 | 2024-05-14 | Elevate          | L   | 0.646      | -            | -                | -                | -         |    -4.46 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2211 | 2024-05-12 | NRG              | L   | 0.633      | -            | -                | -                | -         |    -6.22 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2218 | 2024-05-12 | Mythic           | W   | 0.632      | 0.270        | 0.010 (0.002)    | 0.292 (0.050)    | 0 (0.000) |    11.04 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2238 | 2024-05-11 | BOSS             | W   | 0.626      | 0.270        | 0.014 (0.002)    | 0.326 (0.055)    | 0 (0.000) |    11.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2241 | 2024-05-11 | NRG              | L   | 0.625      | -            | -                | -                | -         |    -6.20 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2244 | 2024-05-11 | Party Astronauts | W   | 0.625      | 0.270        | 0.041 (0.007)    | 0.522 (0.088)    | 0 (0.000) |    15.17 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2307 | 2024-05-08 | Nouns            | L   | 0.607      | -            | -                | -                | -         |    -4.60 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2309 | 2024-05-08 | Nouns            | L   | 0.606      | -            | -                | -                | -         |    -4.79 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2819 | 2024-04-17 | Nouns            | L   | 0.466      | -            | -                | -                | -         |    -3.57 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2971 | 2024-04-10 | MIGHT            | L   | 0.420      | -            | -                | -                | -         |   -10.21 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2976 | 2024-04-10 | MIGHT            | W   | 0.420      | -            | -                | -                | 0 (0.000) |     3.03 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3154 | 2024-04-04 | Carpe Diem       | W   | 0.380      | 0.477        | 0.005 (0.001)    | -                | -         |     4.86 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3159 | 2024-04-04 | Carpe Diem       | W   | 0.380      | 0.477        | 0.005 (0.001)    | -                | -         |     5.02 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3202 | 2024-04-03 | Limitless        | W   | 0.374      | 0.477        | -                | 0.163 (0.029)    | -         |     4.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3204 | 2024-04-03 | Limitless        | W   | 0.373      | 0.477        | -                | 0.163 (0.029)    | -         |     4.79 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3252 | 2024-04-02 | Party Astronauts | L   | 0.367      | -            | -                | -                | -         |    -2.81 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3256 | 2024-04-02 | BOSS             | L   | 0.366      | -            | -                | -                | -         |    -4.63 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3339 | 2024-03-27 | M80              | L   | 0.327      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3345 | 2024-03-27 | M80              | L   | 0.326      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3464 | 2024-03-20 | LAG              | W   | 0.280      | 0.477        | 0.012 (0.002)    | 0.385 (0.051)    | -         |     5.78 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3466 | 2024-03-20 | LAG              | L   | 0.280      | -            | -                | -                | -         |    -3.08 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3482 | 2024-03-19 | Party Astronauts | L   | 0.274      | -            | -                | -                | -         |    -2.11 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3484 | 2024-03-19 | Party Astronauts | L   | 0.274      | -            | -                | -                | -         |    -2.14 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3579 | 2024-03-14 | Wildcard         | L   | 0.240      | -            | -                | -                | -         |    -2.32 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3582 | 2024-03-14 | Wildcard         | L   | 0.240      | -            | -                | -                | -         |    -2.36 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3611 | 2024-03-13 | Mythic           | W   | 0.233      | -            | -                | -                | -         |     4.19 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3654 | 2024-03-12 | bubibabu         | W   | 0.227      | -            | -                | -                | -         |     0.95 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4080 | 2024-02-22 | MIGHT            | L   | 0.099      | -            | -                | -                | -         |    -2.39 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4324 | 2024-02-13 | Take Flyte       | L   | 0.041      | -            | -                | -                | -         |    -0.68 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4327 | 2024-02-13 | Take Flyte       | W   | 0.040      | -            | -                | -                | -         |     0.59 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,311.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
