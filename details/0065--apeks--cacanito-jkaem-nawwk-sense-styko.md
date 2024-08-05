### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  983.3<br />
<br />
Final Rank Value (983.3) = Starting Rank Value (921.3) + Head To Head Adjustments (62.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.202[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 921.3
- 400 + ( ( 0.253 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 921.3


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
|           37 |     2354 | 2024-04-27 | MIBR              | L   | 0.569      | -            | -                | -                | -         |    -1.21 | CacaNito, jkaem, nawwk, sense, STYKO |
|           36 |     2404 | 2024-04-25 | Aurora            | W   | 0.556      | 0.500        | 0.429 (0.119)    | 0.800 (0.222)    | 1 (0.556) |    17.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           35 |     2410 | 2024-04-25 | sunday school     | W   | 0.554      | -            | -                | -                | 1 (0.554) |     2.42 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2597 | 2024-04-18 | BetBoom           | L   | 0.506      | -            | -                | -                | -         |    -1.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2600 | 2024-04-18 | DMS               | W   | 0.506      | 0.143        | -                | 0.447 (0.032)    | 0 (0.000) |     6.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2613 | 2024-04-18 | AMKAL             | W   | 0.505      | 0.143        | 0.131 (0.009)    | 0.484 (0.035)    | 0 (0.000) |    11.99 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2779 | 2024-04-11 | Aurora            | L   | 0.459      | -            | -                | -                | -         |    -0.28 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2818 | 2024-04-10 | AMKAL             | L   | 0.453      | -            | -                | -                | -         |    -3.82 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2868 | 2024-04-09 | fnatic            | W   | 0.446      | 0.143        | 0.371 (0.024)    | 0.633 (0.040)    | 0 (0.000) |    13.64 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2880 | 2024-04-09 | KOI               | W   | 0.445      | 0.143        | 0.059 (0.004)    | 0.382 (0.024)    | 0 (0.000) |     9.95 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     2902 | 2024-04-08 | fnatic            | L   | 0.439      | -            | -                | -                | -         |    -0.37 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     2914 | 2024-04-08 | GUN5              | W   | 0.438      | -            | -                | -                | -         |     0.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3056 | 2024-04-03 | Monte             | L   | 0.405      | -            | -                | -                | -         |    -5.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3086 | 2024-04-02 | Aurora            | L   | 0.399      | -            | -                | -                | -         |    -0.20 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3094 | 2024-04-02 | B8                | W   | 0.398      | 0.143        | 0.167 (0.009)    | 0.879 (0.050)    | -         |     9.12 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3119 | 2024-03-31 | B8                | L   | 0.385      | -            | -                | -                | -         |    -3.33 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3151 | 2024-03-28 | 3DMAX             | L   | 0.365      | -            | -                | -                | -         |    -0.18 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3216 | 2024-03-26 | FORZE             | L   | 0.351      | -            | -                | -                | -         |    -5.43 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3316 | 2024-03-19 | Legacy            | L   | 0.305      | -            | -                | -                | -         |    -3.76 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3329 | 2024-03-18 | Imperial          | L   | 0.298      | -            | -                | -                | -         |    -1.11 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3342 | 2024-03-17 | AMKAL             | W   | 0.293      | 0.143        | 0.131 (0.005)    | 0.484 (0.020)    | 1 (0.293) |     7.04 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3358 | 2024-03-17 | paiN              | L   | 0.291      | -            | -                | -                | -         |    -0.54 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3489 | 2024-03-12 | Metizport         | L   | 0.258      | -            | -                | -                | -         |    -4.17 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3498 | 2024-03-11 | Virtus.pro        | L   | 0.253      | -            | -                | -                | -         |    -0.09 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3508 | 2024-03-11 | KOI               | W   | 0.252      | 0.143        | 0.059 (0.002)    | 0.382 (0.014)    | -         |     5.79 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3601 | 2024-03-07 | Space             | W   | 0.225      | 0.500        | -                | 0.406 (0.046)    | -         |     2.52 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3629 | 2024-03-06 | PARIVISION        | L   | 0.219      | -            | -                | -                | -         |    -2.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3939 | 2024-02-21 | Gaimin Gladiators | W   | 0.124      | -            | -                | -                | 1 (0.124) |     2.28 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3970 | 2024-02-20 | Monte             | W   | 0.117      | 0.143        | 0.062 (0.001)    | -                | 1 (0.117) |     2.32 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     3983 | 2024-02-19 | Cloud9            | L   | 0.113      | -            | -                | -                | -         |    -1.13 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     3993 | 2024-02-19 | OG                | W   | 0.111      | 0.143        | 0.143 (0.002)    | -                | 1 (0.111) |     2.19 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4178 | 2024-02-11 | Metizport         | L   | 0.060      | -            | -                | -                | -         |    -0.98 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4180 | 2024-02-11 | 3DMAX             | W   | 0.059      | 0.143        | 0.499 (0.004)    | 1.000 (0.008)    | -         |     1.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4193 | 2024-02-10 | Metizport         | W   | 0.052      | -            | -                | -                | -         |     0.79 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4196 | 2024-02-10 | ex-Anonymo        | W   | 0.051      | -            | -                | -                | -         |     0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4264 | 2024-02-04 | Natus Vincere     | L   | 0.012      | -            | -                | -                | -         |    -0.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4285 | 2024-02-03 | Complexity        | L   | 0.006      | -            | -                | -                | -         |    -0.00 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,841.35)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.852 | $500.00        | $426.02         |
| 2024-04-28 |      0.570 | $10,000.00     | $5,702.18       |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |
| 2024-02-11 |      0.059 | $10,000.00     | $587.82         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
