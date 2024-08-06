### Roster Details<br />
Team Name: Liquid<br />
Roster: jks, NAF, Twistzz, ultimate, YEKINDAR<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1671.8<br />
<br />
Final Rank Value (1671.8) = Starting Rank Value (1595.0) + Head To Head Adjustments (76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.192[<sup>2</sup>](#table1)
- LAN Wins: 0.804[<sup>2</sup>](#table1)

The average of these factors is 0.581<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1595.0
- 400 + ( ( 0.581 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1595.0


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
|           38 |       83 | 2024-08-03 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.357 (0.207)    | 1 (1.000) |    25.60 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           37 |      162 | 2024-08-01 | Natus Vincere    | W   | 1.000      | 0.581        | 1.000 (0.581)    | 0.357 (0.207)    | 1 (1.000) |    26.86 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           36 |      206 | 2024-07-31 | Virtus.pro       | W   | 1.000      | 0.581        | 0.499 (0.290)    | 0.308 (0.179)    | 1 (1.000) |    19.01 | jks, NAF, Twistzz, ultimate, YEKINDAR  |
|           35 |     1719 | 2024-05-29 | G2               | L   | 0.742      | -            | -                | -                | -         |    -3.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     1744 | 2024-05-28 | Falcons          | W   | 0.735      | 0.624        | 0.219 (0.101)    | -                | 1 (0.735) |     6.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     1762 | 2024-05-27 | 9z               | L   | 0.729      | -            | -                | -                | -         |   -16.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1773 | 2024-05-27 | Complexity       | W   | 0.727      | 0.624        | 0.341 (0.155)    | 0.364 (0.165)    | 1 (0.727) |    13.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1847 | 2024-05-23 | Eternal Fire     | L   | 0.699      | -            | -                | -                | -         |    -8.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1891 | 2024-05-22 | Astralis         | W   | 0.692      | 0.769        | 0.389 (0.207)    | 0.403 (0.214)    | -         |    15.19 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1936 | 2024-05-21 | ENCE             | W   | 0.685      | 0.769        | 0.173 (0.091)    | 0.422 (0.222)    | -         |     5.54 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     1992 | 2024-05-19 | AMKAL            | W   | 0.672      | 0.769        | -                | 0.452 (0.234)    | -         |     2.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     2007 | 2024-05-18 | OG               | W   | 0.668      | 0.769        | 0.137 (0.070)    | -                | -         |     0.98 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2297 | 2024-05-10 | Astralis         | L   | 0.613      | -            | -                | -                | -         |    -5.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2341 | 2024-05-08 | FlyQuest         | W   | 0.599      | 0.889        | -                | 0.277 (0.148)    | 1 (0.599) |     1.95 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2409 | 2024-05-04 | MOUZ             | L   | 0.574      | -            | -                | -                | -         |    -3.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     2471 | 2024-05-01 | Monte            | W   | 0.554      | -            | -                | -                | 1 (0.554) |     0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     2494 | 2024-04-30 | FURIA            | W   | 0.547      | 0.889        | 0.284 (0.138)    | 0.468 (0.228)    | 1 (0.547) |    10.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     2738 | 2024-04-19 | M80              | L   | 0.476      | -            | -                | -                | -         |   -13.30 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     2788 | 2024-04-18 | M80              | W   | 0.469      | -            | -                | -                | -         |     1.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     2791 | 2024-04-18 | Legacy           | W   | 0.468      | -            | -                | -                | -         |     0.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     2838 | 2024-04-17 | Akimbo           | W   | 0.462      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     2843 | 2024-04-17 | straykids        | W   | 0.462      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     2956 | 2024-04-12 | FaZe             | L   | 0.425      | -            | -                | -                | -         |    -5.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     3041 | 2024-04-10 | MOUZ             | L   | 0.411      | -            | -                | -                | -         |    -2.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     3119 | 2024-04-08 | G2               | W   | 0.398      | 0.624        | 1.000 (0.248)    | 0.478 (0.119)    | 1 (0.398) |    11.30 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     3129 | 2024-04-07 | HEROIC           | W   | 0.397      | -            | -                | -                | 1 (0.397) |     5.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     3801 | 2024-03-07 | SAW              | L   | 0.186      | -            | -                | -                | -         |    -5.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     3883 | 2024-03-04 | Complexity       | L   | 0.168      | -            | -                | -                | -         |    -2.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     3919 | 2024-03-03 | BOSS             | W   | 0.160      | -            | -                | -                | -         |     0.06 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     3932 | 2024-03-02 | FURIA            | L   | 0.153      | -            | -                | -                | -         |    -1.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     3947 | 2024-03-01 | BESTIA           | W   | 0.148      | -            | -                | -                | -         |     0.18 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     4018 | 2024-02-26 | Nouns            | W   | 0.123      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     4020 | 2024-02-26 | BOSS             | W   | 0.122      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4033 | 2024-02-25 | Wildcard         | W   | 0.116      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4038 | 2024-02-25 | Nouns            | L   | 0.115      | -            | -                | -                | -         |    -3.55 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4097 | 2024-02-22 | Party Astronauts | W   | 0.096      | -            | -                | -                | -         |     0.07 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     4099 | 2024-02-22 | MIGHT            | W   | 0.095      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     4105 | 2024-02-22 | ex-CatEvil       | W   | 0.095      | -            | -                | -                | -         |     0.00 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($122,479.88)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-06-02 |      0.767 | $6,000.00      | $4,602.50       |
| 2024-05-23 |      0.699 | $100,000.00    | $69,916.67      |
| 2024-05-12 |      0.626 | $32,000.00     | $20,040.00      |
| 2024-04-14 |      0.438 | $10,000.00     | $4,383.56       |
| 2024-03-10 |      0.207 | $5,000.00      | $1,037.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
