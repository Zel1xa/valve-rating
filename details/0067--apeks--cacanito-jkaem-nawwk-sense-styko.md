### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  960.8<br />
<br />
Final Rank Value (960.8) = Starting Rank Value (901.0) + Head To Head Adjustments (59.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.184[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.0
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.0


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
|           35 |     2479 | 2024-04-27 | MIBR              | L   | 0.544      | -            | -                | -                | -         |    -1.10 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2529 | 2024-04-25 | Aurora            | W   | 0.531      | 0.500        | 0.423 (0.113)    | 0.793 (0.211)    | 1 (0.531) |    16.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2535 | 2024-04-25 | sunday school     | W   | 0.530      | 0.500        | 0.003 (0.001)    | -                | 1 (0.530) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2722 | 2024-04-18 | BetBoom           | L   | 0.482      | -            | -                | -                | -         |    -1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2725 | 2024-04-18 | DMS               | W   | 0.481      | 0.143        | -                | 0.446 (0.031)    | 0 (0.000) |     6.93 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2738 | 2024-04-18 | AMKAL             | W   | 0.481      | 0.143        | 0.130 (0.009)    | 0.475 (0.033)    | 0 (0.000) |    11.60 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2904 | 2024-04-11 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -0.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2943 | 2024-04-10 | AMKAL             | L   | 0.428      | -            | -                | -                | -         |    -3.41 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     2993 | 2024-04-09 | fnatic            | W   | 0.422      | 0.143        | 0.371 (0.022)    | 0.708 (0.043)    | 0 (0.000) |    12.89 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3005 | 2024-04-09 | KOI               | W   | 0.421      | 0.143        | 0.058 (0.004)    | 0.375 (0.023)    | 0 (0.000) |     9.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3027 | 2024-04-08 | fnatic            | L   | 0.415      | -            | -                | -                | -         |    -0.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3039 | 2024-04-08 | GUN5              | W   | 0.413      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3181 | 2024-04-03 | Monte             | L   | 0.380      | -            | -                | -                | -         |    -4.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3211 | 2024-04-02 | Aurora            | L   | 0.375      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3219 | 2024-04-02 | B8                | W   | 0.374      | 0.143        | 0.165 (0.009)    | 0.912 (0.049)    | -         |     8.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3244 | 2024-03-31 | B8                | L   | 0.360      | -            | -                | -                | -         |    -2.99 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3276 | 2024-03-28 | 3DMAX             | L   | 0.340      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3341 | 2024-03-26 | FORZE             | L   | 0.327      | -            | -                | -                | -         |    -4.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3441 | 2024-03-19 | Legacy            | L   | 0.280      | -            | -                | -                | -         |    -3.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3454 | 2024-03-18 | Imperial          | L   | 0.273      | -            | -                | -                | -         |    -1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3467 | 2024-03-17 | AMKAL             | W   | 0.268      | 0.143        | 0.130 (0.005)    | 0.475 (0.018)    | 1 (0.268) |     6.56 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3483 | 2024-03-17 | paiN              | L   | 0.267      | -            | -                | -                | -         |    -0.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3614 | 2024-03-12 | Metizport         | L   | 0.234      | -            | -                | -                | -         |    -3.63 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3623 | 2024-03-11 | Virtus.pro        | L   | 0.228      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3633 | 2024-03-11 | KOI               | W   | 0.227      | 0.143        | 0.058 (0.002)    | 0.375 (0.012)    | -         |     5.25 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3726 | 2024-03-07 | Space             | W   | 0.201      | 0.500        | -                | 0.406 (0.041)    | -         |     2.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3754 | 2024-03-06 | PARIVISION        | L   | 0.194      | -            | -                | -                | -         |    -1.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4064 | 2024-02-21 | Gaimin Gladiators | W   | 0.100      | 0.143        | -                | 0.351 (0.005)    | 1 (0.100) |     1.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4095 | 2024-02-20 | Monte             | W   | 0.093      | -            | -                | -                | 1 (0.093) |     1.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4108 | 2024-02-19 | Cloud9            | L   | 0.088      | -            | -                | -                | -         |    -0.92 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4118 | 2024-02-19 | OG                | W   | 0.087      | 0.143        | 0.139 (0.002)    | -                | 1 (0.087) |     1.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4303 | 2024-02-11 | Metizport         | L   | 0.035      | -            | -                | -                | -         |    -0.55 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4305 | 2024-02-11 | 3DMAX             | W   | 0.034      | 0.143        | 0.506 (0.002)    | -                | -         |     1.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4318 | 2024-02-10 | Metizport         | W   | 0.027      | -            | -                | -                | -         |     0.43 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4321 | 2024-02-10 | ex-Anonymo        | W   | 0.027      | -            | -                | -                | -         |     0.05 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,751.27)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $500.00        | $413.77         |
| 2024-04-28 |      0.546 | $10,000.00     | $5,457.18       |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
