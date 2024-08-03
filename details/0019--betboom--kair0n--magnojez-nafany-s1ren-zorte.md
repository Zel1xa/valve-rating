### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1414.4<br />
<br />
Final Rank Value (1414.4) = Starting Rank Value (1428.3) + Head To Head Adjustments (-13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.626[<sup>1</sup>](#table2)
- Bounty Collected: 0.545[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.566[<sup>2</sup>](#table1)

The average of these factors is 0.503<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1428.3
- 400 + ( ( 0.503 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1428.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |     1260 | 2024-06-07 | Astralis          | L   | 0.819      | -            | -                | -                | -         |    -4.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1315 | 2024-06-06 | Eternal Fire      | W   | 0.813      | 0.715        | 0.746 (0.434)    | 0.474 (0.276)    | 1 (0.813) |    19.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1326 | 2024-06-06 | Complexity        | W   | 0.812      | 0.715        | 0.313 (0.182)    | 0.394 (0.229)    | 1 (0.812) |    20.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1360 | 2024-06-05 | BIG               | W   | 0.807      | 0.715        | 0.156 (0.090)    | 0.316 (0.182)    | 1 (0.807) |    11.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1375 | 2024-06-05 | FURIA             | L   | 0.806      | -            | -                | -                | -         |    -6.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1384 | 2024-06-05 | fnatic            | W   | 0.805      | 0.715        | 0.290 (0.167)    | 0.627 (0.361)    | 1 (0.805) |    10.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1663 | 2024-05-25 | B8                | L   | 0.733      | -            | -                | -                | -         |   -17.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1688 | 2024-05-24 | DMS               | W   | 0.724      | -            | -                | -                | 0 (0.000) |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1778 | 2024-05-21 | Eternal Fire      | L   | 0.706      | -            | -                | -                | -         |    -3.62 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1806 | 2024-05-20 | MIBR              | W   | 0.701      | 0.769        | 0.210 (0.113)    | 0.682 (0.367)    | -         |    12.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1812 | 2024-05-20 | Astralis          | L   | 0.700      | -            | -                | -                | -         |    -2.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1826 | 2024-05-20 | MIBR              | W   | 0.698      | 0.769        | 0.210 (0.113)    | 0.682 (0.366)    | -         |    13.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     1987 | 2024-05-15 | Falcons           | L   | 0.667      | -            | -                | -                | -         |    -9.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2052 | 2024-05-14 | MOUZ              | L   | 0.659      | -            | -                | -                | -         |    -1.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2094 | 2024-05-12 | B8                | L   | 0.647      | -            | -                | -                | -         |   -17.16 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2098 | 2024-05-12 | 9 Pandas          | W   | 0.646      | 0.435        | -                | 0.715 (0.201)    | -         |     2.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2131 | 2024-05-11 | Metizport         | W   | 0.639      | -            | -                | -                | -         |     1.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2148 | 2024-05-10 | Enterprise        | W   | 0.632      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2207 | 2024-05-07 | FlyQuest          | L   | 0.613      | -            | -                | -                | -         |   -14.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2258 | 2024-05-04 | AMKAL             | L   | 0.593      | -            | -                | -                | -         |   -14.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2263 | 2024-05-04 | 9 Pandas          | W   | 0.592      | 0.435        | -                | 0.715 (0.184)    | -         |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2286 | 2024-05-03 | Insilio           | W   | 0.584      | -            | -                | -                | -         |     1.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2327 | 2024-05-01 | EYEBALLERS        | W   | 0.573      | -            | -                | -                | -         |     0.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2357 | 2024-04-30 | 3DMAX             | L   | 0.565      | -            | -                | -                | -         |    -4.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2431 | 2024-04-26 | M80               | W   | 0.541      | 0.889        | 0.188 (0.090)    | 0.608 (0.292)    | 1 (0.541) |     4.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2444 | 2024-04-26 | Falcons           | W   | 0.539      | 0.889        | 0.225 (0.108)    | -                | 1 (0.539) |     8.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2467 | 2024-04-25 | Vitality          | L   | 0.533      | -            | -                | -                | -         |    -1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2499 | 2024-04-23 | M80               | W   | 0.520      | 0.889        | 0.188 (0.087)    | 0.608 (0.281)    | 1 (0.520) |     4.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2608 | 2024-04-19 | Cloud9            | L   | 0.493      | -            | -                | -                | -         |   -13.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2619 | 2024-04-19 | Eternal Fire      | L   | 0.492      | -            | -                | -                | -         |    -2.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2643 | 2024-04-18 | Apeks             | W   | 0.487      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2647 | 2024-04-18 | brazylijski luz   | W   | 0.487      | -            | -                | -                | -         |     0.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2654 | 2024-04-18 | Serbia            | W   | 0.486      | -            | -                | -                | -         |     0.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2773 | 2024-04-14 | 3DMAX             | W   | 0.459      | 0.358        | 0.504 (0.083)    | -                | -         |    11.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2779 | 2024-04-13 | OG                | L   | 0.454      | -            | -                | -                | -         |   -12.69 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2783 | 2024-04-13 | Aurora            | L   | 0.453      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2791 | 2024-04-13 | Sampi             | W   | 0.451      | -            | -                | -                | -         |     0.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2818 | 2024-04-11 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2826 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.440      | -            | -                | -                | -         |    10.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2832 | 2024-04-11 | AMKAL             | L   | 0.439      | -            | -                | -                | -         |   -11.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2871 | 2024-04-10 | Aurora            | W   | 0.433      | -            | -                | -                | -         |    10.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     2930 | 2024-04-09 | BIG               | W   | 0.426      | -            | -                | -                | -         |     5.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3002 | 2024-04-06 | Alliance          | W   | 0.406      | -            | -                | -                | -         |     0.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3016 | 2024-04-05 | BLEED             | W   | 0.400      | -            | -                | -                | -         |     1.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3052 | 2024-04-04 | Alliance          | W   | 0.394      | -            | -                | -                | -         |     0.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3065 | 2024-04-04 | BLEED             | W   | 0.392      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3233 | 2024-03-27 | FAVBET            | L   | 0.340      | -            | -                | -                | -         |   -10.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3270 | 2024-03-24 | FORZE             | L   | 0.318      | -            | -                | -                | -         |    -9.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3283 | 2024-03-23 | fnatic            | W   | 0.312      | -            | -                | -                | -         |     4.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3324 | 2024-03-21 | B8                | W   | 0.298      | -            | -                | -                | -         |     1.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3715 | 2024-03-05 | BLEED             | L   | 0.192      | -            | -                | -                | -         |    -5.60 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3733 | 2024-03-04 | Gaimin Gladiators | W   | 0.185      | -            | -                | -                | -         |     0.47 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3745 | 2024-03-03 | ex-Preasy         | L   | 0.180      | -            | -                | -                | -         |    -5.53 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3750 | 2024-03-03 | ex-Sprout         | W   | 0.180      | -            | -                | -                | -         |     0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3792 | 2024-03-01 | ex-Preasy         | W   | 0.167      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3824 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.152      | -            | -                | -                | -         |     0.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     3931 | 2024-02-23 | ex-Guild Eagles   | L   | 0.119      | -            | -                | -                | -         |    -3.63 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4071 | 2024-02-17 | Eternal Fire      | L   | 0.080      | -            | -                | -                | -         |    -0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4099 | 2024-02-16 | Natus Vincere     | L   | 0.073      | -            | -                | -                | -         |    -0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4132 | 2024-02-15 | Enterprise        | W   | 0.065      | -            | -                | -                | 1 (0.065) |     0.12 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4166 | 2024-02-14 | Into the Breach   | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4170 | 2024-02-14 | fnatic            | L   | 0.059      | -            | -                | -                | -         |    -1.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4253 | 2024-02-08 | FORZE             | L   | 0.020      | -            | -                | -                | -         |    -0.61 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4260 | 2024-02-08 | Nemiga            | L   | 0.019      | -            | -                | -                | -         |    -0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82,152.92)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $20,000.00     | $16,656.48      |
| 2024-05-26 |      0.740 | $2,000.00      | $1,479.54       |
| 2024-05-23 |      0.719 | $12,500.00     | $8,988.43       |
| 2024-05-12 |      0.647 | $10,000.00     | $6,466.44       |
| 2024-05-12 |      0.646 | $17,500.00     | $11,307.75      |
| 2024-05-04 |      0.593 | $10,000.00     | $5,931.02       |
| 2024-05-02 |      0.580 | $1,000.00      | $579.77         |
| 2024-04-14 |      0.459 | $52,500.00     | $24,115.97      |
| 2024-04-14 |      0.459 | $9,000.00      | $4,130.42       |
| 2024-03-06 |      0.200 | $12,500.00     | $2,497.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
