### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1417.7<br />
<br />
Final Rank Value (1417.7) = Starting Rank Value (1419.1) + Head To Head Adjustments (-1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.547[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.555[<sup>2</sup>](#table1)

The average of these factors is 0.497<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1419.1
- 400 + ( ( 0.497 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1419.1


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
|           64 |     1384 | 2024-06-07 | Astralis          | L   | 0.803      | -            | -                | -                | -         |    -3.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1439 | 2024-06-06 | Eternal Fire      | W   | 0.797      | 0.715        | 0.739 (0.422)    | 0.449 (0.256)    | 1 (0.797) |    19.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1450 | 2024-06-06 | Complexity        | W   | 0.797      | 0.715        | 0.342 (0.195)    | 0.373 (0.212)    | 1 (0.797) |    20.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1484 | 2024-06-05 | BIG               | W   | 0.792      | 0.715        | 0.154 (0.087)    | 0.297 (0.168)    | 1 (0.792) |    10.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1499 | 2024-06-05 | FURIA             | L   | 0.791      | -            | -                | -                | -         |    -6.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1508 | 2024-06-05 | fnatic            | W   | 0.790      | 0.715        | 0.371 (0.209)    | 0.696 (0.393)    | 1 (0.790) |    15.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1791 | 2024-05-25 | B8                | L   | 0.717      | -            | -                | -                | -         |   -17.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1816 | 2024-05-24 | DMS               | W   | 0.709      | -            | -                | -                | 0 (0.000) |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1906 | 2024-05-21 | Eternal Fire      | L   | 0.691      | -            | -                | -                | -         |    -3.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1934 | 2024-05-20 | MIBR              | W   | 0.685      | 0.769        | 0.208 (0.110)    | 0.648 (0.341)    | -         |    12.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1940 | 2024-05-20 | Astralis          | L   | 0.684      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1954 | 2024-05-20 | MIBR              | W   | 0.682      | 0.769        | 0.208 (0.109)    | 0.648 (0.340)    | -         |    13.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2116 | 2024-05-15 | Falcons           | L   | 0.651      | -            | -                | -                | -         |    -9.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2181 | 2024-05-14 | MOUZ              | L   | 0.643      | -            | -                | -                | -         |    -1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2223 | 2024-05-12 | B8                | L   | 0.631      | -            | -                | -                | -         |   -16.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2227 | 2024-05-12 | 9 Pandas          | W   | 0.630      | 0.435        | -                | 0.717 (0.196)    | -         |     2.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2260 | 2024-05-11 | Metizport         | W   | 0.623      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2277 | 2024-05-10 | Enterprise        | W   | 0.616      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2337 | 2024-05-07 | FlyQuest          | L   | 0.597      | -            | -                | -                | -         |   -14.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2388 | 2024-05-04 | AMKAL             | L   | 0.578      | -            | -                | -                | -         |   -14.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2393 | 2024-05-04 | 9 Pandas          | W   | 0.577      | 0.435        | -                | 0.717 (0.180)    | -         |     1.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2416 | 2024-05-03 | Insilio           | W   | 0.569      | -            | -                | -                | -         |     1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2457 | 2024-05-01 | EYEBALLERS        | W   | 0.557      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2487 | 2024-04-30 | 3DMAX             | L   | 0.549      | -            | -                | -                | -         |    -3.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2561 | 2024-04-26 | M80               | W   | 0.525      | 0.889        | 0.188 (0.088)    | 0.576 (0.269)    | 1 (0.525) |     4.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2575 | 2024-04-26 | Falcons           | W   | 0.523      | 0.889        | 0.221 (0.103)    | -                | 1 (0.523) |     8.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2598 | 2024-04-25 | Vitality          | L   | 0.517      | -            | -                | -                | -         |    -1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2630 | 2024-04-23 | M80               | W   | 0.505      | 0.889        | 0.188 (0.084)    | 0.576 (0.259)    | 1 (0.505) |     4.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2739 | 2024-04-19 | Cloud9            | L   | 0.478      | -            | -                | -                | -         |   -13.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2750 | 2024-04-19 | Eternal Fire      | L   | 0.477      | -            | -                | -                | -         |    -2.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2774 | 2024-04-18 | Apeks             | W   | 0.472      | -            | -                | -                | -         |     1.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2778 | 2024-04-18 | brazylijski luz   | W   | 0.471      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2785 | 2024-04-18 | Serbia            | W   | 0.471      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2904 | 2024-04-14 | 3DMAX             | W   | 0.443      | 0.358        | 0.509 (0.081)    | -                | -         |    11.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2910 | 2024-04-13 | OG                | L   | 0.438      | -            | -                | -                | -         |   -12.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2914 | 2024-04-13 | Aurora            | L   | 0.437      | -            | -                | -                | -         |    -2.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2922 | 2024-04-13 | Sampi             | W   | 0.436      | -            | -                | -                | -         |     0.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2949 | 2024-04-11 | Aurora            | L   | 0.425      | -            | -                | -                | -         |    -2.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2957 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.424      | -            | -                | -                | -         |    10.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2963 | 2024-04-11 | AMKAL             | L   | 0.423      | -            | -                | -                | -         |   -11.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     3002 | 2024-04-10 | Aurora            | W   | 0.417      | -            | -                | -                | -         |    10.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3061 | 2024-04-09 | BIG               | W   | 0.410      | -            | -                | -                | -         |     4.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3133 | 2024-04-06 | Alliance          | W   | 0.390      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3147 | 2024-04-05 | BLEED             | W   | 0.384      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3183 | 2024-04-04 | Alliance          | W   | 0.378      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3196 | 2024-04-04 | BLEED             | W   | 0.377      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3366 | 2024-03-27 | FAVBET            | L   | 0.325      | -            | -                | -                | -         |    -9.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3404 | 2024-03-24 | FORZE             | L   | 0.303      | -            | -                | -                | -         |    -8.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3418 | 2024-03-23 | fnatic            | W   | 0.296      | -            | -                | -                | -         |     6.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3460 | 2024-03-21 | B8                | W   | 0.283      | -            | -                | -                | -         |     1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3854 | 2024-03-05 | BLEED             | L   | 0.177      | -            | -                | -                | -         |    -5.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3872 | 2024-03-04 | Gaimin Gladiators | W   | 0.169      | -            | -                | -                | -         |     0.42 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3884 | 2024-03-03 | ex-Preasy         | L   | 0.165      | -            | -                | -                | -         |    -5.05 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3889 | 2024-03-03 | ex-Sprout         | W   | 0.164      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3931 | 2024-03-01 | ex-Preasy         | W   | 0.152      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3963 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.137      | -            | -                | -                | -         |     0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4070 | 2024-02-23 | ex-Guild Eagles   | L   | 0.103      | -            | -                | -                | -         |    -3.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4211 | 2024-02-17 | Eternal Fire      | L   | 0.064      | -            | -                | -                | -         |    -0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4239 | 2024-02-16 | Natus Vincere     | L   | 0.058      | -            | -                | -                | -         |    -0.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4272 | 2024-02-15 | Enterprise        | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4306 | 2024-02-14 | Into the Breach   | W   | 0.044      | -            | -                | -                | 1 (0.044) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4310 | 2024-02-14 | fnatic            | L   | 0.044      | -            | -                | -                | -         |    -0.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4393 | 2024-02-08 | FORZE             | L   | 0.005      | -            | -                | -                | -         |    -0.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4400 | 2024-02-08 | Nemiga            | L   | 0.004      | -            | -                | -                | -         |    -0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79,859.44)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $20,000.00     | $16,344.44      |
| 2024-05-26 |      0.724 | $2,000.00      | $1,448.33       |
| 2024-05-23 |      0.703 | $12,500.00     | $8,793.40       |
| 2024-05-12 |      0.631 | $10,000.00     | $6,310.42       |
| 2024-05-12 |      0.631 | $17,500.00     | $11,034.72      |
| 2024-05-04 |      0.578 | $10,000.00     | $5,775.00       |
| 2024-05-02 |      0.564 | $1,000.00      | $564.17         |
| 2024-04-14 |      0.444 | $52,500.00     | $23,296.88      |
| 2024-04-14 |      0.443 | $9,000.00      | $3,990.00       |
| 2024-03-06 |      0.184 | $12,500.00     | $2,302.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
