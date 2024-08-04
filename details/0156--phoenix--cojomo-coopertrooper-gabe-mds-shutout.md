### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.2<br />
<br />
Final Rank Value (695.2) = Starting Rank Value (736.2) + Head To Head Adjustments (-40.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.078[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.2
- 400 + ( ( 0.164 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 736.2


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
|           48 |       20 | 2024-08-03 | Detonate         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      386 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      504 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.52 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      638 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.47 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      642 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.76 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      702 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.57 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      708 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.01 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1055 | 2024-06-14 | Akimbo           | L   | 0.861      | -            | -                | -                | -         |   -11.54 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1507 | 2024-06-04 | Mythic           | L   | 0.794      | -            | -                | -                | -         |   -10.57 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1808 | 2024-05-22 | BOSS             | L   | 0.709      | -            | -                | -                | -         |   -10.71 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1812 | 2024-05-22 | BOSS             | W   | 0.709      | 0.477        | 0.014 (0.005)    | 0.332 (0.112)    | 0 (0.000) |    11.87 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1857 | 2024-05-21 | NRG              | W   | 0.703      | 0.477        | 0.020 (0.007)    | 0.521 (0.175)    | 0 (0.000) |    16.33 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1859 | 2024-05-21 | NRG              | L   | 0.702      | -            | -                | -                | -         |    -5.70 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1892 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.696      | -            | -                | -                | -         |   -12.10 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1896 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.695      | 0.477        | 0.003 (0.001)    | 0.275 (0.091)    | 0 (0.000) |     9.96 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2059 | 2024-05-15 | Mythic           | L   | 0.663      | -            | -                | -                | -         |    -9.58 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2065 | 2024-05-15 | Mythic           | W   | 0.662      | 0.477        | 0.010 (0.003)    | 0.299 (0.095)    | 0 (0.000) |    11.55 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2126 | 2024-05-14 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -4.34 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2129 | 2024-05-14 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -4.51 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2183 | 2024-05-12 | NRG              | L   | 0.642      | -            | -                | -                | -         |    -6.31 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2190 | 2024-05-12 | Mythic           | W   | 0.641      | 0.270        | 0.010 (0.002)    | 0.299 (0.052)    | 0 (0.000) |    11.19 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2210 | 2024-05-11 | BOSS             | W   | 0.635      | 0.270        | 0.014 (0.002)    | 0.332 (0.057)    | 0 (0.000) |    11.96 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2213 | 2024-05-11 | NRG              | L   | 0.634      | -            | -                | -                | -         |    -6.29 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2216 | 2024-05-11 | Party Astronauts | W   | 0.634      | 0.270        | 0.041 (0.007)    | 0.531 (0.091)    | 0 (0.000) |    15.41 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2279 | 2024-05-08 | Nouns            | L   | 0.616      | -            | -                | -                | -         |    -4.63 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2281 | 2024-05-08 | Nouns            | L   | 0.615      | -            | -                | -                | -         |    -4.82 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2791 | 2024-04-17 | Nouns            | L   | 0.475      | -            | -                | -                | -         |    -3.61 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2943 | 2024-04-10 | MIGHT            | L   | 0.429      | -            | -                | -                | -         |   -10.42 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2948 | 2024-04-10 | MIGHT            | W   | 0.429      | -            | -                | -                | 0 (0.000) |     3.11 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3126 | 2024-04-04 | Carpe Diem       | W   | 0.389      | 0.477        | 0.005 (0.001)    | -                | -         |     4.98 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3131 | 2024-04-04 | Carpe Diem       | W   | 0.389      | 0.477        | 0.005 (0.001)    | -                | -         |     5.14 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3174 | 2024-04-03 | Limitless        | W   | 0.383      | 0.477        | -                | 0.167 (0.030)    | -         |     4.76 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3176 | 2024-04-03 | Limitless        | W   | 0.382      | 0.477        | -                | 0.167 (0.030)    | -         |     4.91 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3224 | 2024-04-02 | Party Astronauts | L   | 0.376      | -            | -                | -                | -         |    -2.87 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3228 | 2024-04-02 | BOSS             | L   | 0.375      | -            | -                | -                | -         |    -4.76 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3311 | 2024-03-27 | M80              | L   | 0.336      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3317 | 2024-03-27 | M80              | L   | 0.335      | -            | -                | -                | -         |    -0.66 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3436 | 2024-03-20 | LAG              | W   | 0.289      | 0.477        | 0.012 (0.002)    | 0.353 (0.049)    | -         |     6.00 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3438 | 2024-03-20 | LAG              | L   | 0.289      | -            | -                | -                | -         |    -3.16 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3454 | 2024-03-19 | Party Astronauts | L   | 0.283      | -            | -                | -                | -         |    -2.17 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3456 | 2024-03-19 | Party Astronauts | L   | 0.283      | -            | -                | -                | -         |    -2.20 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3551 | 2024-03-14 | Wildcard         | L   | 0.249      | -            | -                | -                | -         |    -2.40 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3554 | 2024-03-14 | Wildcard         | L   | 0.249      | -            | -                | -                | -         |    -2.44 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3583 | 2024-03-13 | Mythic           | W   | 0.242      | -            | -                | -                | -         |     4.35 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3626 | 2024-03-12 | bubibabu         | W   | 0.236      | -            | -                | -                | -         |     0.99 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4052 | 2024-02-22 | MIGHT            | L   | 0.109      | -            | -                | -                | -         |    -2.60 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4296 | 2024-02-13 | Take Flyte       | L   | 0.050      | -            | -                | -                | -         |    -0.84 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4299 | 2024-02-13 | Take Flyte       | W   | 0.049      | -            | -                | -                | -         |     0.73 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,326.04)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
