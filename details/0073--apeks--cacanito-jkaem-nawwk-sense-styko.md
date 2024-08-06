### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  954.7<br />
<br />
Final Rank Value (954.7) = Starting Rank Value (896.5) + Head To Head Adjustments (58.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.177[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 896.5
- 400 + ( ( 0.242 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 896.5


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
|           35 |     2535 | 2024-04-27 | MIBR              | L   | 0.531      | -            | -                | -                | -         |    -1.07 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2585 | 2024-04-25 | Aurora            | W   | 0.519      | 0.500        | 0.421 (0.109)    | 0.776 (0.201)    | 1 (0.519) |    16.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2591 | 2024-04-25 | sunday school     | W   | 0.517      | 0.500        | 0.003 (0.001)    | -                | 1 (0.517) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2778 | 2024-04-18 | BetBoom           | L   | 0.469      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2781 | 2024-04-18 | DMS               | W   | 0.469      | 0.143        | -                | 0.437 (0.029)    | 0 (0.000) |     6.87 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2794 | 2024-04-18 | AMKAL             | W   | 0.468      | 0.143        | 0.130 (0.009)    | 0.463 (0.031)    | 0 (0.000) |    11.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2960 | 2024-04-11 | Aurora            | L   | 0.422      | -            | -                | -                | -         |    -0.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     2999 | 2024-04-10 | AMKAL             | L   | 0.416      | -            | -                | -                | -         |    -3.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3049 | 2024-04-09 | fnatic            | W   | 0.409      | 0.143        | 0.371 (0.022)    | 0.695 (0.041)    | 0 (0.000) |    12.52 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3061 | 2024-04-09 | KOI               | W   | 0.408      | 0.143        | 0.058 (0.003)    | 0.365 (0.021)    | 0 (0.000) |     9.22 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3083 | 2024-04-08 | fnatic            | L   | 0.402      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3095 | 2024-04-08 | GUN5              | W   | 0.401      | -            | -                | -                | -         |     0.72 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3237 | 2024-04-03 | Monte             | L   | 0.368      | -            | -                | -                | -         |    -4.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3267 | 2024-04-02 | Aurora            | L   | 0.362      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3275 | 2024-04-02 | B8                | W   | 0.361      | 0.143        | 0.164 (0.008)    | 0.933 (0.048)    | -         |     8.45 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3300 | 2024-03-31 | B8                | L   | 0.347      | -            | -                | -                | -         |    -2.83 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3332 | 2024-03-28 | 3DMAX             | L   | 0.328      | -            | -                | -                | -         |    -0.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3397 | 2024-03-26 | FORZE             | L   | 0.314      | -            | -                | -                | -         |    -4.75 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3497 | 2024-03-19 | Legacy            | L   | 0.268      | -            | -                | -                | -         |    -2.98 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3510 | 2024-03-18 | Imperial          | L   | 0.261      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3523 | 2024-03-17 | AMKAL             | W   | 0.256      | 0.143        | 0.130 (0.005)    | 0.463 (0.017)    | 1 (0.256) |     6.30 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3539 | 2024-03-17 | paiN              | L   | 0.254      | -            | -                | -                | -         |    -0.46 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3670 | 2024-03-12 | Metizport         | L   | 0.221      | -            | -                | -                | -         |    -3.40 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3679 | 2024-03-11 | Virtus.pro        | L   | 0.216      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3689 | 2024-03-11 | KOI               | W   | 0.215      | 0.143        | 0.058 (0.002)    | 0.365 (0.011)    | -         |     4.97 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3782 | 2024-03-07 | Space             | W   | 0.188      | 0.500        | -                | 0.439 (0.041)    | -         |     2.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3810 | 2024-03-06 | PARIVISION        | L   | 0.182      | -            | -                | -                | -         |    -1.39 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4120 | 2024-02-21 | Gaimin Gladiators | W   | 0.087      | 0.143        | -                | 0.339 (0.004)    | 1 (0.087) |     1.60 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4151 | 2024-02-20 | Monte             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     1.58 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4164 | 2024-02-19 | Cloud9            | L   | 0.076      | -            | -                | -                | -         |    -0.78 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4174 | 2024-02-19 | OG                | W   | 0.074      | 0.143        | 0.137 (0.001)    | -                | 1 (0.074) |     1.48 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4359 | 2024-02-11 | Metizport         | L   | 0.023      | -            | -                | -                | -         |    -0.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4361 | 2024-02-11 | 3DMAX             | W   | 0.022      | 0.143        | 0.509 (0.002)    | -                | -         |     0.68 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4374 | 2024-02-10 | Metizport         | W   | 0.015      | -            | -                | -                | -         |     0.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4377 | 2024-02-10 | ex-Anonymo        | W   | 0.014      | -            | -                | -                | -         |     0.03 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,492.65)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $500.00        | $407.47         |
| 2024-04-28 |      0.533 | $10,000.00     | $5,331.02       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
