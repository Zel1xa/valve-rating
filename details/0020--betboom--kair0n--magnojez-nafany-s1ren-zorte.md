### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1420.0<br />
<br />
Final Rank Value (1420.0) = Starting Rank Value (1424.2) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.625[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.562[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1424.2
- 400 + ( ( 0.501 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1424.2


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
|           64 |     1355 | 2024-06-07 | Astralis          | L   | 0.813      | -            | -                | -                | -         |    -3.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1410 | 2024-06-06 | Eternal Fire      | W   | 0.807      | 0.715        | 0.742 (0.428)    | 0.458 (0.264)    | 1 (0.807) |    19.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1421 | 2024-06-06 | Complexity        | W   | 0.806      | 0.715        | 0.342 (0.197)    | 0.380 (0.219)    | 1 (0.806) |    20.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1455 | 2024-06-05 | BIG               | W   | 0.801      | 0.715        | 0.155 (0.089)    | 0.304 (0.174)    | 1 (0.801) |    10.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1470 | 2024-06-05 | FURIA             | L   | 0.800      | -            | -                | -                | -         |    -6.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1479 | 2024-06-05 | fnatic            | W   | 0.799      | 0.715        | 0.371 (0.212)    | 0.708 (0.405)    | 1 (0.799) |    15.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1762 | 2024-05-25 | B8                | L   | 0.727      | -            | -                | -                | -         |   -17.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1787 | 2024-05-24 | DMS               | W   | 0.718      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1877 | 2024-05-21 | Eternal Fire      | L   | 0.700      | -            | -                | -                | -         |    -3.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1905 | 2024-05-20 | MIBR              | W   | 0.694      | 0.769        | 0.209 (0.112)    | 0.659 (0.352)    | -         |    12.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1911 | 2024-05-20 | Astralis          | L   | 0.694      | -            | -                | -                | -         |    -2.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1925 | 2024-05-20 | MIBR              | W   | 0.692      | 0.769        | 0.209 (0.111)    | 0.659 (0.350)    | -         |    13.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2087 | 2024-05-15 | Falcons           | L   | 0.660      | -            | -                | -                | -         |    -9.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2152 | 2024-05-14 | MOUZ              | L   | 0.653      | -            | -                | -                | -         |    -1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2194 | 2024-05-12 | B8                | L   | 0.640      | -            | -                | -                | -         |   -16.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2198 | 2024-05-12 | 9 Pandas          | W   | 0.639      | 0.435        | -                | 0.690 (0.192)    | -         |     2.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2231 | 2024-05-11 | Metizport         | W   | 0.632      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2248 | 2024-05-10 | Enterprise        | W   | 0.626      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2308 | 2024-05-07 | FlyQuest          | L   | 0.606      | -            | -                | -                | -         |   -14.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2359 | 2024-05-04 | AMKAL             | L   | 0.587      | -            | -                | -                | -         |   -14.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2364 | 2024-05-04 | 9 Pandas          | W   | 0.586      | 0.435        | -                | 0.690 (0.176)    | -         |     1.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2387 | 2024-05-03 | Insilio           | W   | 0.578      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2428 | 2024-05-01 | EYEBALLERS        | W   | 0.566      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2458 | 2024-04-30 | 3DMAX             | L   | 0.559      | -            | -                | -                | -         |    -4.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2532 | 2024-04-26 | M80               | W   | 0.534      | 0.889        | 0.188 (0.089)    | 0.587 (0.279)    | 1 (0.534) |     4.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2546 | 2024-04-26 | Falcons           | W   | 0.532      | 0.889        | 0.223 (0.106)    | -                | 1 (0.532) |     8.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2569 | 2024-04-25 | Vitality          | L   | 0.526      | -            | -                | -                | -         |    -1.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2601 | 2024-04-23 | M80               | W   | 0.514      | 0.889        | 0.188 (0.086)    | 0.587 (0.268)    | 1 (0.514) |     4.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2710 | 2024-04-19 | Cloud9            | L   | 0.487      | -            | -                | -                | -         |   -13.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2721 | 2024-04-19 | Eternal Fire      | L   | 0.486      | -            | -                | -                | -         |    -2.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2745 | 2024-04-18 | Apeks             | W   | 0.481      | -            | -                | -                | -         |     1.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2749 | 2024-04-18 | brazylijski luz   | W   | 0.481      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2756 | 2024-04-18 | Serbia            | W   | 0.480      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2875 | 2024-04-14 | 3DMAX             | W   | 0.453      | 0.358        | 0.506 (0.082)    | -                | -         |    11.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2881 | 2024-04-13 | OG                | L   | 0.447      | -            | -                | -                | -         |   -12.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2885 | 2024-04-13 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2893 | 2024-04-13 | Sampi             | W   | 0.445      | -            | -                | -                | -         |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2920 | 2024-04-11 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2928 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.433      | -            | -                | -                | -         |    11.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2934 | 2024-04-11 | AMKAL             | L   | 0.432      | -            | -                | -                | -         |   -11.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2973 | 2024-04-10 | Aurora            | W   | 0.427      | -            | -                | -                | -         |    10.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3032 | 2024-04-09 | BIG               | W   | 0.419      | -            | -                | -                | -         |     4.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3104 | 2024-04-06 | Alliance          | W   | 0.399      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3118 | 2024-04-05 | BLEED             | W   | 0.394      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3154 | 2024-04-04 | Alliance          | W   | 0.387      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3167 | 2024-04-04 | BLEED             | W   | 0.386      | -            | -                | -                | -         |     1.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3337 | 2024-03-27 | FAVBET            | L   | 0.334      | -            | -                | -                | -         |   -10.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3375 | 2024-03-24 | FORZE             | L   | 0.312      | -            | -                | -                | -         |    -9.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3389 | 2024-03-23 | fnatic            | W   | 0.305      | -            | -                | -                | -         |     6.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3431 | 2024-03-21 | B8                | W   | 0.292      | -            | -                | -                | -         |     1.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3825 | 2024-03-05 | BLEED             | L   | 0.186      | -            | -                | -                | -         |    -5.42 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3843 | 2024-03-04 | Gaimin Gladiators | W   | 0.179      | -            | -                | -                | -         |     0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3855 | 2024-03-03 | ex-Preasy         | L   | 0.174      | -            | -                | -                | -         |    -5.33 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3860 | 2024-03-03 | ex-Sprout         | W   | 0.174      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3902 | 2024-03-01 | ex-Preasy         | W   | 0.161      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3934 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.146      | -            | -                | -                | -         |     0.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4041 | 2024-02-23 | ex-Guild Eagles   | L   | 0.113      | -            | -                | -                | -         |    -3.44 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4182 | 2024-02-17 | Eternal Fire      | L   | 0.074      | -            | -                | -                | -         |    -0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4210 | 2024-02-16 | Natus Vincere     | L   | 0.067      | -            | -                | -                | -         |    -0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4243 | 2024-02-15 | Enterprise        | W   | 0.059      | -            | -                | -                | 1 (0.059) |     0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4277 | 2024-02-14 | Into the Breach   | W   | 0.054      | -            | -                | -                | 1 (0.054) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4281 | 2024-02-14 | fnatic            | L   | 0.053      | -            | -                | -                | -         |    -0.53 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4364 | 2024-02-08 | FORZE             | L   | 0.014      | -            | -                | -                | -         |    -0.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4371 | 2024-02-08 | Nemiga            | L   | 0.013      | -            | -                | -                | -         |    -0.33 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,234.17)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.827 | $20,000.00     | $16,531.48      |
| 2024-05-26 |      0.734 | $2,000.00      | $1,467.04       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-05-12 |      0.640 | $10,000.00     | $6,403.94       |
| 2024-05-12 |      0.640 | $17,500.00     | $11,198.38      |
| 2024-05-04 |      0.587 | $10,000.00     | $5,868.52       |
| 2024-05-02 |      0.574 | $1,000.00      | $573.52         |
| 2024-04-14 |      0.453 | $52,500.00     | $23,787.85      |
| 2024-04-14 |      0.453 | $9,000.00      | $4,074.17       |
| 2024-03-06 |      0.194 | $12,500.00     | $2,418.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
