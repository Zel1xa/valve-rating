### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  955.0<br />
<br />
Final Rank Value (955.0) = Starting Rank Value (897.1) + Head To Head Adjustments (58.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.177[<sup>2</sup>](#table1)

The average of these factors is 0.242<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 897.1
- 400 + ( ( 0.242 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 897.1


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
|           35 |     2539 | 2024-04-27 | MIBR              | L   | 0.531      | -            | -                | -                | -         |    -1.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           34 |     2589 | 2024-04-25 | Aurora            | W   | 0.519      | 0.500        | 0.421 (0.109)    | 0.759 (0.197)    | 1 (0.519) |    15.99 | CacaNito, jkaem, nawwk, sense, STYKO |
|           33 |     2595 | 2024-04-25 | sunday school     | W   | 0.517      | 0.500        | 0.003 (0.001)    | -                | 1 (0.517) |     2.50 | CacaNito, jkaem, nawwk, sense, STYKO |
|           32 |     2782 | 2024-04-18 | BetBoom           | L   | 0.469      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           31 |     2785 | 2024-04-18 | DMS               | W   | 0.468      | 0.143        | -                | 0.428 (0.029)    | 0 (0.000) |     6.85 | CacaNito, jkaem, nawwk, sense, STYKO |
|           30 |     2798 | 2024-04-18 | AMKAL             | W   | 0.468      | 0.143        | 0.130 (0.009)    | 0.453 (0.030)    | 0 (0.000) |    11.37 | CacaNito, jkaem, nawwk, sense, STYKO |
|           29 |     2964 | 2024-04-11 | Aurora            | L   | 0.421      | -            | -                | -                | -         |    -0.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|           28 |     3003 | 2024-04-10 | AMKAL             | L   | 0.415      | -            | -                | -                | -         |    -3.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|           27 |     3053 | 2024-04-09 | fnatic            | W   | 0.409      | 0.143        | 0.371 (0.022)    | 0.680 (0.040)    | 0 (0.000) |    12.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           26 |     3065 | 2024-04-09 | KOI               | W   | 0.408      | 0.143        | 0.058 (0.003)    | 0.357 (0.021)    | 0 (0.000) |     9.20 | CacaNito, jkaem, nawwk, sense, STYKO |
|           25 |     3087 | 2024-04-08 | fnatic            | L   | 0.402      | -            | -                | -                | -         |    -0.34 | CacaNito, jkaem, nawwk, sense, STYKO |
|           24 |     3099 | 2024-04-08 | GUN5              | W   | 0.401      | -            | -                | -                | -         |     0.71 | CacaNito, jkaem, nawwk, sense, STYKO |
|           23 |     3241 | 2024-04-03 | Monte             | L   | 0.367      | -            | -                | -                | -         |    -4.51 | CacaNito, jkaem, nawwk, sense, STYKO |
|           22 |     3271 | 2024-04-02 | Aurora            | L   | 0.362      | -            | -                | -                | -         |    -0.16 | CacaNito, jkaem, nawwk, sense, STYKO |
|           21 |     3279 | 2024-04-02 | B8                | W   | 0.361      | 0.143        | 0.170 (0.009)    | 0.912 (0.047)    | -         |     8.46 | CacaNito, jkaem, nawwk, sense, STYKO |
|           20 |     3304 | 2024-03-31 | B8                | L   | 0.347      | -            | -                | -                | -         |    -2.81 | CacaNito, jkaem, nawwk, sense, STYKO |
|           19 |     3336 | 2024-03-28 | 3DMAX             | L   | 0.328      | -            | -                | -                | -         |    -0.14 | CacaNito, jkaem, nawwk, sense, STYKO |
|           18 |     3401 | 2024-03-26 | FORZE             | L   | 0.314      | -            | -                | -                | -         |    -4.75 | CacaNito, jkaem, nawwk, sense, STYKO |
|           17 |     3501 | 2024-03-19 | Legacy            | L   | 0.268      | -            | -                | -                | -         |    -2.99 | CacaNito, jkaem, nawwk, sense, STYKO |
|           16 |     3514 | 2024-03-18 | Imperial          | L   | 0.260      | -            | -                | -                | -         |    -1.00 | CacaNito, jkaem, nawwk, sense, STYKO |
|           15 |     3527 | 2024-03-17 | AMKAL             | W   | 0.256      | 0.143        | 0.130 (0.005)    | 0.453 (0.017)    | 1 (0.256) |     6.29 | CacaNito, jkaem, nawwk, sense, STYKO |
|           14 |     3543 | 2024-03-17 | paiN              | L   | 0.254      | -            | -                | -                | -         |    -0.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|           13 |     3674 | 2024-03-12 | Metizport         | L   | 0.221      | -            | -                | -                | -         |    -3.40 | CacaNito, jkaem, nawwk, sense, STYKO |
|           12 |     3683 | 2024-03-11 | Virtus.pro        | L   | 0.216      | -            | -                | -                | -         |    -0.08 | CacaNito, jkaem, nawwk, sense, STYKO |
|           11 |     3693 | 2024-03-11 | KOI               | W   | 0.214      | 0.143        | 0.058 (0.002)    | 0.357 (0.011)    | -         |     4.96 | CacaNito, jkaem, nawwk, sense, STYKO |
|           10 |     3786 | 2024-03-07 | Space             | W   | 0.188      | 0.500        | -                | 0.429 (0.040)    | -         |     2.27 | CacaNito, jkaem, nawwk, sense, STYKO |
|            9 |     3814 | 2024-03-06 | PARIVISION        | L   | 0.181      | -            | -                | -                | -         |    -1.38 | CacaNito, jkaem, nawwk, sense, STYKO |
|            8 |     4124 | 2024-02-21 | Gaimin Gladiators | W   | 0.087      | 0.143        | -                | 0.331 (0.004)    | 1 (0.087) |     1.59 | CacaNito, jkaem, nawwk, sense, STYKO |
|            7 |     4155 | 2024-02-20 | Monte             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     1.58 | CacaNito, jkaem, nawwk, sense, STYKO |
|            6 |     4168 | 2024-02-19 | Cloud9            | L   | 0.075      | -            | -                | -                | -         |    -0.77 | CacaNito, jkaem, nawwk, sense, STYKO |
|            5 |     4178 | 2024-02-19 | OG                | W   | 0.074      | 0.143        | 0.137 (0.001)    | -                | 1 (0.074) |     1.47 | CacaNito, jkaem, nawwk, sense, STYKO |
|            4 |     4363 | 2024-02-11 | Metizport         | L   | 0.022      | -            | -                | -                | -         |    -0.35 | CacaNito, jkaem, nawwk, sense, STYKO |
|            3 |     4365 | 2024-02-11 | 3DMAX             | W   | 0.022      | 0.143        | 0.510 (0.002)    | -                | -         |     0.67 | CacaNito, jkaem, nawwk, sense, STYKO |
|            2 |     4378 | 2024-02-10 | Metizport         | W   | 0.014      | -            | -                | -                | -         |     0.23 | CacaNito, jkaem, nawwk, sense, STYKO |
|            1 |     4381 | 2024-02-10 | ex-Anonymo        | W   | 0.014      | -            | -                | -                | -         |     0.03 | CacaNito, jkaem, nawwk, sense, STYKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,486.96)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $500.00        | $407.33         |
| 2024-04-28 |      0.533 | $10,000.00     | $5,328.24       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,751.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
