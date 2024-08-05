### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1419.3<br />
<br />
Final Rank Value (1419.3) = Starting Rank Value (1422.6) + Head To Head Adjustments (-3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.624[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.267[<sup>2</sup>](#table1)
- LAN Wins: 0.560[<sup>2</sup>](#table1)

The average of these factors is 0.500<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1422.6
- 400 + ( ( 0.500 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1422.6


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
|           64 |     1360 | 2024-06-07 | Astralis          | L   | 0.810      | -            | -                | -                | -         |    -3.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1415 | 2024-06-06 | Eternal Fire      | W   | 0.804      | 0.715        | 0.741 (0.426)    | 0.457 (0.263)    | 1 (0.804) |    19.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1426 | 2024-06-06 | Complexity        | W   | 0.803      | 0.715        | 0.342 (0.197)    | 0.380 (0.218)    | 1 (0.803) |    20.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1460 | 2024-06-05 | BIG               | W   | 0.798      | 0.715        | 0.155 (0.088)    | 0.303 (0.173)    | 1 (0.798) |    10.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1475 | 2024-06-05 | FURIA             | L   | 0.797      | -            | -                | -                | -         |    -6.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1484 | 2024-06-05 | fnatic            | W   | 0.797      | 0.715        | 0.371 (0.211)    | 0.708 (0.403)    | 1 (0.797) |    15.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1767 | 2024-05-25 | B8                | L   | 0.724      | -            | -                | -                | -         |   -17.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1792 | 2024-05-24 | DMS               | W   | 0.715      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1882 | 2024-05-21 | Eternal Fire      | L   | 0.697      | -            | -                | -                | -         |    -3.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1910 | 2024-05-20 | MIBR              | W   | 0.692      | 0.769        | 0.209 (0.111)    | 0.659 (0.350)    | -         |    12.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1916 | 2024-05-20 | Astralis          | L   | 0.691      | -            | -                | -                | -         |    -2.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1930 | 2024-05-20 | MIBR              | W   | 0.689      | 0.769        | 0.209 (0.111)    | 0.659 (0.349)    | -         |    13.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2092 | 2024-05-15 | Falcons           | L   | 0.658      | -            | -                | -                | -         |    -9.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2157 | 2024-05-14 | MOUZ              | L   | 0.650      | -            | -                | -                | -         |    -1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2199 | 2024-05-12 | B8                | L   | 0.638      | -            | -                | -                | -         |   -16.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2203 | 2024-05-12 | 9 Pandas          | W   | 0.637      | 0.435        | -                | 0.690 (0.191)    | -         |     2.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2236 | 2024-05-11 | Metizport         | W   | 0.630      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2253 | 2024-05-10 | Enterprise        | W   | 0.623      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2313 | 2024-05-07 | FlyQuest          | L   | 0.604      | -            | -                | -                | -         |   -14.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2364 | 2024-05-04 | AMKAL             | L   | 0.584      | -            | -                | -                | -         |   -14.64 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2369 | 2024-05-04 | 9 Pandas          | W   | 0.583      | 0.435        | -                | 0.690 (0.175)    | -         |     1.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2392 | 2024-05-03 | Insilio           | W   | 0.575      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2433 | 2024-05-01 | EYEBALLERS        | W   | 0.564      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2463 | 2024-04-30 | 3DMAX             | L   | 0.556      | -            | -                | -                | -         |    -4.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2537 | 2024-04-26 | M80               | W   | 0.532      | 0.889        | 0.188 (0.089)    | 0.587 (0.277)    | 1 (0.532) |     4.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2551 | 2024-04-26 | Falcons           | W   | 0.530      | 0.889        | 0.223 (0.105)    | -                | 1 (0.530) |     8.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2574 | 2024-04-25 | Vitality          | L   | 0.524      | -            | -                | -                | -         |    -1.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2606 | 2024-04-23 | M80               | W   | 0.511      | 0.889        | 0.188 (0.085)    | 0.587 (0.267)    | 1 (0.511) |     4.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2715 | 2024-04-19 | Cloud9            | L   | 0.485      | -            | -                | -                | -         |   -13.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2726 | 2024-04-19 | Eternal Fire      | L   | 0.483      | -            | -                | -                | -         |    -2.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2750 | 2024-04-18 | Apeks             | W   | 0.478      | -            | -                | -                | -         |     1.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2754 | 2024-04-18 | brazylijski luz   | W   | 0.478      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2761 | 2024-04-18 | Serbia            | W   | 0.477      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2880 | 2024-04-14 | 3DMAX             | W   | 0.450      | 0.358        | 0.507 (0.082)    | -                | -         |    11.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2886 | 2024-04-13 | OG                | L   | 0.445      | -            | -                | -                | -         |   -12.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2890 | 2024-04-13 | Aurora            | L   | 0.444      | -            | -                | -                | -         |    -3.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2898 | 2024-04-13 | Sampi             | W   | 0.443      | -            | -                | -                | -         |     0.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2925 | 2024-04-11 | Aurora            | L   | 0.432      | -            | -                | -                | -         |    -3.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2933 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.431      | -            | -                | -                | -         |    10.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2939 | 2024-04-11 | AMKAL             | L   | 0.430      | -            | -                | -                | -         |   -11.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2978 | 2024-04-10 | Aurora            | W   | 0.424      | -            | -                | -                | -         |    10.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3037 | 2024-04-09 | BIG               | W   | 0.417      | -            | -                | -                | -         |     4.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3109 | 2024-04-06 | Alliance          | W   | 0.397      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3123 | 2024-04-05 | BLEED             | W   | 0.391      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3159 | 2024-04-04 | Alliance          | W   | 0.385      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3172 | 2024-04-04 | BLEED             | W   | 0.383      | -            | -                | -                | -         |     1.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3342 | 2024-03-27 | FAVBET            | L   | 0.331      | -            | -                | -                | -         |   -10.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3380 | 2024-03-24 | FORZE             | L   | 0.309      | -            | -                | -                | -         |    -9.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3394 | 2024-03-23 | fnatic            | W   | 0.303      | -            | -                | -                | -         |     6.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3436 | 2024-03-21 | B8                | W   | 0.289      | -            | -                | -                | -         |     1.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3830 | 2024-03-05 | BLEED             | L   | 0.183      | -            | -                | -                | -         |    -5.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3848 | 2024-03-04 | Gaimin Gladiators | W   | 0.176      | -            | -                | -                | -         |     0.44 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3860 | 2024-03-03 | ex-Preasy         | L   | 0.171      | -            | -                | -                | -         |    -5.25 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3865 | 2024-03-03 | ex-Sprout         | W   | 0.171      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3907 | 2024-03-01 | ex-Preasy         | W   | 0.158      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3939 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.143      | -            | -                | -                | -         |     0.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4046 | 2024-02-23 | ex-Guild Eagles   | L   | 0.110      | -            | -                | -                | -         |    -3.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4187 | 2024-02-17 | Eternal Fire      | L   | 0.071      | -            | -                | -                | -         |    -0.40 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4215 | 2024-02-16 | Natus Vincere     | L   | 0.064      | -            | -                | -                | -         |    -0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4248 | 2024-02-15 | Enterprise        | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4282 | 2024-02-14 | Into the Breach   | W   | 0.051      | -            | -                | -                | 1 (0.051) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4286 | 2024-02-14 | fnatic            | L   | 0.050      | -            | -                | -                | -         |    -0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4369 | 2024-02-08 | FORZE             | L   | 0.012      | -            | -                | -                | -         |    -0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4376 | 2024-02-08 | Nemiga            | L   | 0.010      | -            | -                | -                | -         |    -0.26 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($80,839.44)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $20,000.00     | $16,477.78      |
| 2024-05-26 |      0.731 | $2,000.00      | $1,461.67       |
| 2024-05-23 |      0.710 | $12,500.00     | $8,876.74       |
| 2024-05-12 |      0.638 | $10,000.00     | $6,377.08       |
| 2024-05-12 |      0.637 | $17,500.00     | $11,151.39      |
| 2024-05-04 |      0.584 | $10,000.00     | $5,841.67       |
| 2024-05-02 |      0.571 | $1,000.00      | $570.83         |
| 2024-04-14 |      0.450 | $52,500.00     | $23,646.88      |
| 2024-04-14 |      0.450 | $9,000.00      | $4,050.00       |
| 2024-03-06 |      0.191 | $12,500.00     | $2,385.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
