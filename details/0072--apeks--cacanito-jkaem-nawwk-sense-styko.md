### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.3<br />
<br />
Final Rank Value (956.3) = Starting Rank Value (898.3) + Head To Head Adjustments (58.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.359[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.179[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.3
- 400 + ( ( 0.243 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 898.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2529 | 2024-04-27 | MIBR              | L   | 0.536      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2579 | 2024-04-25 | Aurora            | W   | 0.523      | 0.500        | 0.422 (0.110)    | 0.778 (0.204)    | 1 (0.523) |    16.13 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2585 | 2024-04-25 | sunday school     | W   | 0.522      | 0.500        | 0.003 (0.001)    | -                | 1 (0.522) |     2.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2772 | 2024-04-18 | BetBoom           | L   | 0.473      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2775 | 2024-04-18 | DMS               | W   | 0.473      | 0.143        | -                | 0.438 (0.030)    | 0 (0.000) |     6.91 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2788 | 2024-04-18 | AMKAL             | W   | 0.473      | 0.143        | 0.130 (0.009)    | 0.465 (0.031)    | 0 (0.000) |    11.46 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2954 | 2024-04-11 | Aurora            | L   | 0.426      | -            | -                | -                | -         |    -0.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2993 | 2024-04-10 | AMKAL             | L   | 0.420      | -            | -                | -                | -         |    -3.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3043 | 2024-04-09 | fnatic            | W   | 0.413      | 0.143        | 0.371 (0.022)    | 0.697 (0.041)    | 0 (0.000) |    12.65 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3055 | 2024-04-09 | KOI               | W   | 0.412      | 0.143        | 0.058 (0.003)    | 0.367 (0.022)    | 0 (0.000) |     9.32 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3077 | 2024-04-08 | fnatic            | L   | 0.407      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3089 | 2024-04-08 | GUN5              | W   | 0.405      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3231 | 2024-04-03 | Monte             | L   | 0.372      | -            | -                | -                | -         |    -4.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3261 | 2024-04-02 | Aurora            | L   | 0.366      | -            | -                | -                | -         |    -0.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3269 | 2024-04-02 | B8                | W   | 0.365      | 0.143        | 0.165 (0.009)    | 0.935 (0.049)    | -         |     8.54 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3294 | 2024-03-31 | B8                | L   | 0.352      | -            | -                | -                | -         |    -2.88 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3326 | 2024-03-28 | 3DMAX             | L   | 0.332      | -            | -                | -                | -         |    -0.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3391 | 2024-03-26 | FORZE             | L   | 0.318      | -            | -                | -                | -         |    -4.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3491 | 2024-03-19 | Legacy            | L   | 0.272      | -            | -                | -                | -         |    -3.03 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3504 | 2024-03-18 | Imperial          | L   | 0.265      | -            | -                | -                | -         |    -1.01 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3517 | 2024-03-17 | AMKAL             | W   | 0.260      | 0.143        | 0.130 (0.005)    | 0.465 (0.017)    | 1 (0.260) |     6.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3533 | 2024-03-17 | paiN              | L   | 0.258      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3664 | 2024-03-12 | Metizport         | L   | 0.226      | -            | -                | -                | -         |    -4.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3673 | 2024-03-11 | Virtus.pro        | L   | 0.220      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3683 | 2024-03-11 | KOI               | W   | 0.219      | 0.143        | 0.058 (0.002)    | 0.367 (0.011)    | -         |     5.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3776 | 2024-03-07 | Space             | W   | 0.193      | 0.500        | -                | 0.439 (0.042)    | -         |     2.30 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3804 | 2024-03-06 | PARIVISION        | L   | 0.186      | -            | -                | -                | -         |    -1.44 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4114 | 2024-02-21 | Gaimin Gladiators | W   | 0.091      | 0.143        | -                | 0.342 (0.004)    | 1 (0.091) |     1.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4145 | 2024-02-20 | Monte             | W   | 0.085      | -            | -                | -                | 1 (0.085) |     1.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4158 | 2024-02-19 | Cloud9            | L   | 0.080      | -            | -                | -                | -         |    -0.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4168 | 2024-02-19 | OG                | W   | 0.078      | 0.143        | 0.138 (0.002)    | -                | 1 (0.078) |     1.56 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4353 | 2024-02-11 | Metizport         | L   | 0.027      | -            | -                | -                | -         |    -0.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4355 | 2024-02-11 | 3DMAX             | W   | 0.026      | 0.143        | 0.508 (0.002)    | -                | -         |     0.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4368 | 2024-02-10 | Metizport         | W   | 0.019      | -            | -                | -                | -         |     0.24 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4371 | 2024-02-10 | ex-Anonymo        | W   | 0.018      | -            | -                | -                | -         |     0.03 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,580.91)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $500.00        | $409.62         |
| 2024-04-28 |      0.537 | $10,000.00     | $5,374.07       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,797.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
