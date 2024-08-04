### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  961.1<br />
<br />
Final Rank Value (961.1) = Starting Rank Value (901.3) + Head To Head Adjustments (59.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.184[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 901.3
- 400 + ( ( 0.245 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 901.3


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
|           35 |     2471 | 2024-04-27 | MIBR              | L   | 0.545      | -            | -                | -                | -         |    -1.10 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2521 | 2024-04-25 | Aurora            | W   | 0.532      | 0.500        | 0.424 (0.113)    | 0.793 (0.211)    | 1 (0.532) |    16.38 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2527 | 2024-04-25 | sunday school     | W   | 0.531      | 0.500        | 0.003 (0.001)    | -                | 1 (0.531) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2714 | 2024-04-18 | BetBoom           | L   | 0.482      | -            | -                | -                | -         |    -1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2717 | 2024-04-18 | DMS               | W   | 0.482      | 0.143        | -                | 0.446 (0.031)    | 0 (0.000) |     6.94 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2730 | 2024-04-18 | AMKAL             | W   | 0.482      | 0.143        | 0.130 (0.009)    | 0.476 (0.033)    | 0 (0.000) |    11.62 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2896 | 2024-04-11 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -0.26 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2935 | 2024-04-10 | AMKAL             | L   | 0.429      | -            | -                | -                | -         |    -3.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     2985 | 2024-04-09 | fnatic            | W   | 0.422      | 0.143        | 0.371 (0.022)    | 0.708 (0.043)    | 0 (0.000) |    12.91 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     2997 | 2024-04-09 | KOI               | W   | 0.421      | 0.143        | 0.058 (0.004)    | 0.375 (0.023)    | 0 (0.000) |     9.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3019 | 2024-04-08 | fnatic            | L   | 0.416      | -            | -                | -                | -         |    -0.36 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3031 | 2024-04-08 | GUN5              | W   | 0.414      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3173 | 2024-04-03 | Monte             | L   | 0.381      | -            | -                | -                | -         |    -4.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3203 | 2024-04-02 | Aurora            | L   | 0.375      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3211 | 2024-04-02 | B8                | W   | 0.374      | 0.143        | 0.165 (0.009)    | 0.912 (0.049)    | -         |     8.70 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3236 | 2024-03-31 | B8                | L   | 0.361      | -            | -                | -                | -         |    -3.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3268 | 2024-03-28 | 3DMAX             | L   | 0.341      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3333 | 2024-03-26 | FORZE             | L   | 0.328      | -            | -                | -                | -         |    -4.98 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3433 | 2024-03-19 | Legacy            | L   | 0.281      | -            | -                | -                | -         |    -3.15 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3446 | 2024-03-18 | Imperial          | L   | 0.274      | -            | -                | -                | -         |    -1.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3459 | 2024-03-17 | AMKAL             | W   | 0.269      | 0.143        | 0.130 (0.005)    | 0.476 (0.018)    | 1 (0.269) |     6.58 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3475 | 2024-03-17 | paiN              | L   | 0.268      | -            | -                | -                | -         |    -0.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3606 | 2024-03-12 | Metizport         | L   | 0.235      | -            | -                | -                | -         |    -3.66 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3615 | 2024-03-11 | Virtus.pro        | L   | 0.229      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3625 | 2024-03-11 | KOI               | W   | 0.228      | 0.143        | 0.058 (0.002)    | 0.375 (0.012)    | -         |     5.27 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3718 | 2024-03-07 | Space             | W   | 0.202      | 0.500        | -                | 0.406 (0.041)    | -         |     2.40 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3746 | 2024-03-06 | PARIVISION        | L   | 0.195      | -            | -                | -                | -         |    -1.58 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4056 | 2024-02-21 | Gaimin Gladiators | W   | 0.100      | 0.143        | -                | 0.351 (0.005)    | 1 (0.100) |     1.84 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4087 | 2024-02-20 | Monte             | W   | 0.094      | -            | -                | -                | 1 (0.094) |     1.85 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4100 | 2024-02-19 | Cloud9            | L   | 0.089      | -            | -                | -                | -         |    -0.92 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4110 | 2024-02-19 | OG                | W   | 0.087      | 0.143        | 0.139 (0.002)    | -                | 1 (0.087) |     1.74 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4295 | 2024-02-11 | Metizport         | L   | 0.036      | -            | -                | -                | -         |    -0.57 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4297 | 2024-02-11 | 3DMAX             | W   | 0.035      | 0.143        | 0.506 (0.003)    | -                | -         |     1.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4310 | 2024-02-10 | Metizport         | W   | 0.028      | -            | -                | -                | -         |     0.44 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4313 | 2024-02-10 | ex-Anonymo        | W   | 0.028      | -            | -                | -                | -         |     0.05 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,765.98)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $500.00        | $414.13         |
| 2024-04-28 |      0.546 | $10,000.00     | $5,464.35       |
| 2024-03-20 |      0.289 | $10,000.00     | $2,887.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
