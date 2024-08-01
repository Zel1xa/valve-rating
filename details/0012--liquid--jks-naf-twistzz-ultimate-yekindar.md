### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1596.4<br />
<br />
Final Rank Value (1596.4) = Starting Rank Value (1524.7) + Head To Head Adjustments (71.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.670[<sup>1</sup>](#table2)
- Bounty Collected: 0.586[<sup>2</sup>](#table1)
- Opponent Network: 0.194[<sup>2</sup>](#table1)
- LAN Wins: 0.736[<sup>2</sup>](#table1)

The average of these factors is 0.547<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1524.7
- 400 + ( ( 0.547 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1524.7


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
|           37 |        4 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.331 (0.192)    | 1 (1.000) |    28.00 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |       42 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.484 (0.281)    | 0.326 (0.189)    | 1 (1.000) |    21.21 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1578 | 2024-05-29 | G2               | L   | 0.775      | -            | -                | -                | -         |    -2.54 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1603 | 2024-05-28 | Falcons          | W   | 0.768      | 0.624        | 0.205 (0.098)    | 0.249 (0.119)    | 1 (0.768) |     8.68 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1621 | 2024-05-27 | 9z               | L   | 0.762      | -            | -                | -                | -         |   -21.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1632 | 2024-05-27 | Complexity       | W   | 0.760      | 0.624        | 0.318 (0.151)    | 0.366 (0.174)    | 1 (0.760) |    15.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1708 | 2024-05-23 | Eternal Fire     | L   | 0.732      | -            | -                | -                | -         |    -7.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1762 | 2024-05-22 | Astralis         | W   | 0.725      | 0.769        | 0.359 (0.200)    | 0.385 (0.214)    | -         |    16.55 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1812 | 2024-05-21 | ENCE             | W   | 0.718      | 0.769        | 0.173 (0.096)    | 0.403 (0.222)    | -         |     6.87 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1878 | 2024-05-19 | AMKAL            | W   | 0.705      | 0.769        | 0.132 (0.071)    | 0.482 (0.261)    | -         |     2.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     1893 | 2024-05-18 | OG               | W   | 0.701      | 0.769        | 0.143 (0.077)    | -                | -         |     1.43 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2193 | 2024-05-10 | Astralis         | L   | 0.646      | -            | -                | -                | -         |    -5.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2239 | 2024-05-08 | FlyQuest         | W   | 0.632      | 0.889        | -                | 0.322 (0.181)    | 1 (0.632) |     3.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2307 | 2024-05-04 | MOUZ             | L   | 0.607      | -            | -                | -                | -         |    -2.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2371 | 2024-05-01 | Monte            | W   | 0.587      | -            | -                | -                | 1 (0.587) |     0.99 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2395 | 2024-04-30 | FURIA            | W   | 0.580      | 0.889        | 0.286 (0.148)    | 0.494 (0.255)    | 1 (0.580) |    12.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2645 | 2024-04-19 | M80              | L   | 0.509      | -            | -                | -                | -         |   -13.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2696 | 2024-04-18 | M80              | W   | 0.502      | -            | -                | -                | -         |     2.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2699 | 2024-04-18 | Legacy           | W   | 0.501      | -            | -                | -                | -         |     0.92 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2747 | 2024-04-17 | Akimbo           | W   | 0.495      | -            | -                | -                | -         |     0.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2752 | 2024-04-17 | straykids        | W   | 0.494      | -            | -                | -                | -         |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2868 | 2024-04-12 | FaZe             | L   | 0.458      | -            | -                | -                | -         |    -3.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     2953 | 2024-04-10 | MOUZ             | L   | 0.444      | -            | -                | -                | -         |    -1.78 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3031 | 2024-04-08 | G2               | W   | 0.431      | 0.624        | 1.000 (0.269)    | 0.500 (0.134)    | 1 (0.431) |    12.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3041 | 2024-04-07 | HEROIC           | W   | 0.430      | -            | -                | -                | 1 (0.430) |     7.82 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3732 | 2024-03-07 | SAW              | L   | 0.219      | -            | -                | -                | -         |    -5.98 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3819 | 2024-03-04 | Complexity       | L   | 0.201      | -            | -                | -                | -         |    -2.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3855 | 2024-03-03 | BOSS             | W   | 0.193      | -            | -                | -                | 1 (0.193) |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3868 | 2024-03-02 | FURIA            | L   | 0.186      | -            | -                | -                | -         |    -1.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3884 | 2024-03-01 | BESTIA           | W   | 0.181      | -            | -                | -                | -         |     0.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     3956 | 2024-02-26 | Nouns            | W   | 0.156      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     3958 | 2024-02-26 | BOSS             | W   | 0.155      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     3972 | 2024-02-25 | Wildcard         | W   | 0.149      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     3977 | 2024-02-25 | Nouns            | L   | 0.148      | -            | -                | -                | -         |    -4.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4041 | 2024-02-22 | Party Astronauts | W   | 0.129      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4043 | 2024-02-22 | MIGHT            | W   | 0.128      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4049 | 2024-02-22 | ex-CatEvil       | W   | 0.128      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($105,016.13)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-02 |      0.800 | $6,000.00      | $4,800.00       |
| 2024-05-23 |      0.732 | $100,000.00    | $73,208.33      |
| 2024-05-12 |      0.659 | $32,000.00     | $21,093.33      |
| 2024-04-14 |      0.471 | $10,000.00     | $4,712.73       |
| 2024-03-10 |      0.240 | $5,000.00      | $1,201.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
