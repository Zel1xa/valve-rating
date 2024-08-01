### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1520.1<br />
<br />
Final Rank Value (1520.1) = Starting Rank Value (1451.7) + Head To Head Adjustments (68.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.670[<sup>1</sup>](#table2)
- Bounty Collected: 0.544[<sup>2</sup>](#table1)
- Opponent Network: 0.186[<sup>2</sup>](#table1)
- LAN Wins: 0.643[<sup>2</sup>](#table1)

The average of these factors is 0.511<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1451.7
- 400 + ( ( 0.511 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1451.7


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
|           36 |       35 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.483 (0.281)    | 0.326 (0.190)    | 1 (1.000) |    23.03 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1572 | 2024-05-29 | G2               | L   | 0.776      | -            | -                | -                | -         |    -1.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1597 | 2024-05-28 | Falcons          | W   | 0.770      | 0.624        | 0.206 (0.099)    | 0.249 (0.120)    | 1 (0.770) |    10.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1615 | 2024-05-27 | 9z               | L   | 0.763      | -            | -                | -                | -         |   -20.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1626 | 2024-05-27 | Complexity       | W   | 0.762      | 0.624        | 0.318 (0.151)    | 0.366 (0.174)    | 1 (0.762) |    16.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1702 | 2024-05-23 | Eternal Fire     | L   | 0.734      | -            | -                | -                | -         |    -5.70 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1756 | 2024-05-22 | Astralis         | W   | 0.726      | 0.769        | 0.359 (0.200)    | 0.385 (0.215)    | -         |    17.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1806 | 2024-05-21 | ENCE             | W   | 0.719      | 0.769        | 0.174 (0.096)    | 0.403 (0.223)    | -         |     8.55 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1872 | 2024-05-19 | AMKAL            | W   | 0.707      | 0.769        | 0.132 (0.072)    | 0.482 (0.262)    | -         |     3.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1887 | 2024-05-18 | OG               | W   | 0.702      | 0.769        | 0.143 (0.077)    | -                | -         |     1.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2187 | 2024-05-10 | Astralis         | L   | 0.647      | -            | -                | -                | -         |    -4.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2233 | 2024-05-08 | FlyQuest         | W   | 0.634      | 0.889        | 0.106 (0.060)    | 0.323 (0.182)    | 1 (0.634) |     4.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2301 | 2024-05-04 | MOUZ             | L   | 0.608      | -            | -                | -                | -         |    -1.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2365 | 2024-05-01 | Monte            | W   | 0.588      | -            | -                | -                | 1 (0.588) |     1.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2389 | 2024-04-30 | FURIA            | W   | 0.582      | 0.889        | 0.286 (0.148)    | 0.495 (0.256)    | 1 (0.582) |    13.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2639 | 2024-04-19 | M80              | L   | 0.510      | -            | -                | -                | -         |   -12.43 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2690 | 2024-04-18 | M80              | W   | 0.504      | -            | -                | -                | -         |     3.52 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2693 | 2024-04-18 | Legacy           | W   | 0.503      | -            | -                | -                | -         |     1.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2741 | 2024-04-17 | Akimbo           | W   | 0.496      | -            | -                | -                | -         |     0.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2746 | 2024-04-17 | straykids        | W   | 0.496      | -            | -                | -                | -         |     0.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2862 | 2024-04-12 | FaZe             | L   | 0.460      | -            | -                | -                | -         |    -2.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2947 | 2024-04-10 | MOUZ             | L   | 0.446      | -            | -                | -                | -         |    -1.25 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3025 | 2024-04-08 | G2               | W   | 0.433      | 0.624        | 1.000 (0.270)    | 0.500 (0.135)    | 1 (0.433) |    12.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3035 | 2024-04-07 | HEROIC           | W   | 0.431      | 0.624        | -                | 0.381 (0.102)    | 1 (0.431) |     9.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3726 | 2024-03-07 | SAW              | L   | 0.221      | -            | -                | -                | -         |    -5.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3813 | 2024-03-04 | Complexity       | L   | 0.203      | -            | -                | -                | -         |    -1.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3849 | 2024-03-03 | BOSS             | W   | 0.194      | -            | -                | -                | 1 (0.194) |     0.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3862 | 2024-03-02 | FURIA            | L   | 0.188      | -            | -                | -                | -         |    -0.98 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3878 | 2024-03-01 | BESTIA           | W   | 0.183      | -            | -                | -                | 1 (0.183) |     0.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3950 | 2024-02-26 | Nouns            | W   | 0.157      | -            | -                | -                | -         |     0.24 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3952 | 2024-02-26 | BOSS             | W   | 0.156      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3966 | 2024-02-25 | Wildcard         | W   | 0.151      | -            | -                | -                | -         |     0.23 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3971 | 2024-02-25 | Nouns            | L   | 0.150      | -            | -                | -                | -         |    -4.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4035 | 2024-02-22 | Party Astronauts | W   | 0.130      | -            | -                | -                | -         |     0.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4037 | 2024-02-22 | MIGHT            | W   | 0.130      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4043 | 2024-02-22 | ex-CatEvil       | W   | 0.130      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,271.13)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.802 | $6,000.00      | $4,810.00       |
| 2024-05-23 |      0.734 | $100,000.00    | $73,375.00      |
| 2024-05-12 |      0.661 | $32,000.00     | $21,146.67      |
| 2024-04-14 |      0.473 | $10,000.00     | $4,729.40       |
| 2024-03-10 |      0.242 | $5,000.00      | $1,210.07       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
