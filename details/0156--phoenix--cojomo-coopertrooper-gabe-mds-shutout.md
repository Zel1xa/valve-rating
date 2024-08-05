### Roster Details<br />
Team Name: Phoenix<br />
Roster: CoJoMo, CooperTrooper, Gabe, mds, shutout<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.5<br />
<br />
Final Rank Value (695.5) = Starting Rank Value (736.5) + Head To Head Adjustments (-41.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.078[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.5
- 400 + ( ( 0.164 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 736.5


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
|           48 |       37 | 2024-08-03 | Detonate         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | CoJoMo, CooperTrooper, Gabe, mds, shutout |
|           47 |      403 | 2024-07-24 | Victorum         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | CoJoMo, Gabe, mds, nooz, shutout          |
|           46 |      521 | 2024-07-20 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.53 | CoJoMo, Gabe, mds, nooz, shutout          |
|           45 |      655 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.49 | CoJoMo, Gabe, mds, shutout, xaler         |
|           44 |      659 | 2024-07-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.78 | CoJoMo, Gabe, mds, shutout, xaler         |
|           43 |      719 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -15.59 | CoJoMo, Gabe, mds, shutout, xaler         |
|           42 |      725 | 2024-07-16 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -17.02 | CoJoMo, Gabe, mds, shutout, xaler         |
|           41 |     1072 | 2024-06-14 | Akimbo           | L   | 0.855      | -            | -                | -                | -         |   -11.48 | CoJoMo, Gabe, mds, shutout, xaler         |
|           40 |     1524 | 2024-06-04 | Mythic           | L   | 0.788      | -            | -                | -                | -         |   -10.51 | CoJoMo, Gabe, Louie, mds, shutout         |
|           39 |     1825 | 2024-05-22 | BOSS             | L   | 0.704      | -            | -                | -                | -         |   -10.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           38 |     1829 | 2024-05-22 | BOSS             | W   | 0.703      | 0.477        | 0.014 (0.005)    | 0.331 (0.111)    | 0 (0.000) |    11.76 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           37 |     1874 | 2024-05-21 | NRG              | W   | 0.697      | 0.477        | 0.020 (0.007)    | 0.520 (0.173)    | 0 (0.000) |    16.19 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           36 |     1876 | 2024-05-21 | NRG              | L   | 0.697      | -            | -                | -                | -         |    -5.67 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           35 |     1909 | 2024-05-20 | FLUFFY AIMERS    | L   | 0.690      | -            | -                | -                | -         |   -11.89 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           34 |     1913 | 2024-05-20 | FLUFFY AIMERS    | W   | 0.690      | 0.477        | 0.003 (0.001)    | 0.314 (0.103)    | 0 (0.000) |     9.99 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           33 |     2076 | 2024-05-15 | Mythic           | L   | 0.657      | -            | -                | -                | -         |    -9.50 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           32 |     2082 | 2024-05-15 | Mythic           | W   | 0.657      | 0.477        | 0.010 (0.003)    | 0.297 (0.093)    | 0 (0.000) |    11.45 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           31 |     2143 | 2024-05-14 | Elevate          | L   | 0.650      | -            | -                | -                | -         |    -4.31 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           30 |     2146 | 2024-05-14 | Elevate          | L   | 0.649      | -            | -                | -                | -         |    -4.48 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           29 |     2200 | 2024-05-12 | NRG              | L   | 0.636      | -            | -                | -                | -         |    -6.25 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           28 |     2207 | 2024-05-12 | Mythic           | W   | 0.635      | 0.270        | 0.010 (0.002)    | 0.297 (0.051)    | 0 (0.000) |    11.09 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           27 |     2227 | 2024-05-11 | BOSS             | W   | 0.629      | 0.270        | 0.014 (0.002)    | 0.331 (0.056)    | 0 (0.000) |    11.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           26 |     2230 | 2024-05-11 | NRG              | L   | 0.629      | -            | -                | -                | -         |    -6.23 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           25 |     2233 | 2024-05-11 | Party Astronauts | W   | 0.628      | 0.270        | 0.041 (0.007)    | 0.529 (0.090)    | 0 (0.000) |    15.27 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           24 |     2296 | 2024-05-08 | Nouns            | L   | 0.610      | -            | -                | -                | -         |    -4.61 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           23 |     2298 | 2024-05-08 | Nouns            | L   | 0.610      | -            | -                | -                | -         |    -4.80 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           22 |     2808 | 2024-04-17 | Nouns            | L   | 0.469      | -            | -                | -                | -         |    -3.58 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           21 |     2960 | 2024-04-10 | MIGHT            | L   | 0.424      | -            | -                | -                | -         |   -10.29 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           20 |     2965 | 2024-04-10 | MIGHT            | W   | 0.423      | -            | -                | -                | 0 (0.000) |     3.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           19 |     3143 | 2024-04-04 | Carpe Diem       | W   | 0.384      | 0.477        | 0.005 (0.001)    | -                | -         |     4.90 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           18 |     3148 | 2024-04-04 | Carpe Diem       | W   | 0.383      | 0.477        | 0.005 (0.001)    | -                | -         |     5.06 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           17 |     3191 | 2024-04-03 | Limitless        | W   | 0.377      | 0.477        | -                | 0.166 (0.030)    | -         |     4.68 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           16 |     3193 | 2024-04-03 | Limitless        | W   | 0.377      | 0.477        | -                | 0.166 (0.030)    | -         |     4.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           15 |     3241 | 2024-04-02 | Party Astronauts | L   | 0.370      | -            | -                | -                | -         |    -2.83 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           14 |     3245 | 2024-04-02 | BOSS             | L   | 0.369      | -            | -                | -                | -         |    -4.70 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           13 |     3328 | 2024-03-27 | M80              | L   | 0.330      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           12 |     3334 | 2024-03-27 | M80              | L   | 0.330      | -            | -                | -                | -         |    -0.65 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|           11 |     3453 | 2024-03-20 | LAG              | W   | 0.284      | 0.477        | 0.012 (0.002)    | 0.351 (0.047)    | -         |     5.86 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|           10 |     3455 | 2024-03-20 | LAG              | L   | 0.283      | -            | -                | -                | -         |    -3.11 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            9 |     3471 | 2024-03-19 | Party Astronauts | L   | 0.277      | -            | -                | -                | -         |    -2.13 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            8 |     3473 | 2024-03-19 | Party Astronauts | L   | 0.277      | -            | -                | -                | -         |    -2.16 | BeaKie, CoJoMo, Gabe, mds, X-23           |
|            7 |     3568 | 2024-03-14 | Wildcard         | L   | 0.243      | -            | -                | -                | -         |    -2.35 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            6 |     3571 | 2024-03-14 | Wildcard         | L   | 0.243      | -            | -                | -                | -         |    -2.40 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            5 |     3600 | 2024-03-13 | Mythic           | W   | 0.236      | -            | -                | -                | -         |     4.25 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            4 |     3643 | 2024-03-12 | bubibabu         | W   | 0.230      | -            | -                | -                | -         |     0.97 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            3 |     4069 | 2024-02-22 | MIGHT            | L   | 0.103      | -            | -                | -                | -         |    -2.47 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            2 |     4313 | 2024-02-13 | Take Flyte       | L   | 0.044      | -            | -                | -                | -         |    -0.74 | BeaKie, CoJoMo, Gabe, mds, shutout        |
|            1 |     4316 | 2024-02-13 | Take Flyte       | W   | 0.044      | -            | -                | -                | -         |     0.64 | BeaKie, CoJoMo, Gabe, mds, shutout        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,316.89)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
