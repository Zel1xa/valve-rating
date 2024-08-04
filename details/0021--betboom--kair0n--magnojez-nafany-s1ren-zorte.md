### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1418.6<br />
<br />
Final Rank Value (1418.6) = Starting Rank Value (1424.2) + Head To Head Adjustments (-5.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.625[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.562[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1424.2
- 400 + ( ( 0.501 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1424.2


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
|           64 |     1324 | 2024-06-07 | Astralis          | L   | 0.814      | -            | -                | -                | -         |    -4.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1379 | 2024-06-06 | Eternal Fire      | W   | 0.808      | 0.715        | 0.743 (0.429)    | 0.458 (0.265)    | 1 (0.808) |    19.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1390 | 2024-06-06 | Complexity        | W   | 0.807      | 0.715        | 0.310 (0.179)    | 0.380 (0.219)    | 1 (0.807) |    20.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1424 | 2024-06-05 | BIG               | W   | 0.802      | 0.715        | 0.155 (0.089)    | 0.304 (0.175)    | 1 (0.802) |    10.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1439 | 2024-06-05 | FURIA             | L   | 0.802      | -            | -                | -                | -         |    -6.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1448 | 2024-06-05 | fnatic            | W   | 0.801      | 0.715        | 0.371 (0.212)    | 0.708 (0.406)    | 1 (0.801) |    15.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1731 | 2024-05-25 | B8                | L   | 0.728      | -            | -                | -                | -         |   -17.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1756 | 2024-05-24 | DMS               | W   | 0.719      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1846 | 2024-05-21 | Eternal Fire      | L   | 0.702      | -            | -                | -                | -         |    -3.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1874 | 2024-05-20 | MIBR              | W   | 0.696      | 0.769        | 0.209 (0.112)    | 0.659 (0.352)    | -         |    12.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1880 | 2024-05-20 | Astralis          | L   | 0.695      | -            | -                | -                | -         |    -2.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1894 | 2024-05-20 | MIBR              | W   | 0.693      | 0.769        | 0.209 (0.111)    | 0.659 (0.351)    | -         |    13.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2056 | 2024-05-15 | Falcons           | L   | 0.662      | -            | -                | -                | -         |    -9.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2121 | 2024-05-14 | MOUZ              | L   | 0.654      | -            | -                | -                | -         |    -1.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2163 | 2024-05-12 | B8                | L   | 0.642      | -            | -                | -                | -         |   -17.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2167 | 2024-05-12 | 9 Pandas          | W   | 0.641      | 0.435        | -                | 0.690 (0.192)    | -         |     2.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2200 | 2024-05-11 | Metizport         | W   | 0.634      | -            | -                | -                | -         |     1.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2217 | 2024-05-10 | Enterprise        | W   | 0.627      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2277 | 2024-05-07 | FlyQuest          | L   | 0.608      | -            | -                | -                | -         |   -14.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2328 | 2024-05-04 | AMKAL             | L   | 0.588      | -            | -                | -                | -         |   -14.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2333 | 2024-05-04 | 9 Pandas          | W   | 0.588      | 0.435        | -                | 0.690 (0.176)    | -         |     1.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2356 | 2024-05-03 | Insilio           | W   | 0.579      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2397 | 2024-05-01 | EYEBALLERS        | W   | 0.568      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2427 | 2024-04-30 | 3DMAX             | L   | 0.560      | -            | -                | -                | -         |    -4.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2501 | 2024-04-26 | M80               | W   | 0.536      | 0.889        | 0.188 (0.090)    | 0.587 (0.280)    | 1 (0.536) |     4.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2515 | 2024-04-26 | Falcons           | W   | 0.534      | 0.889        | 0.224 (0.106)    | -                | 1 (0.534) |     8.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2538 | 2024-04-25 | Vitality          | L   | 0.528      | -            | -                | -                | -         |    -1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2570 | 2024-04-23 | M80               | W   | 0.515      | 0.889        | 0.188 (0.086)    | 0.587 (0.269)    | 1 (0.515) |     4.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2679 | 2024-04-19 | Cloud9            | L   | 0.489      | -            | -                | -                | -         |   -13.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2690 | 2024-04-19 | Eternal Fire      | L   | 0.488      | -            | -                | -                | -         |    -2.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2714 | 2024-04-18 | Apeks             | W   | 0.482      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2718 | 2024-04-18 | brazylijski luz   | W   | 0.482      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2725 | 2024-04-18 | Serbia            | W   | 0.482      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2844 | 2024-04-14 | 3DMAX             | W   | 0.454      | 0.358        | 0.506 (0.082)    | -                | -         |    11.16 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2850 | 2024-04-13 | OG                | L   | 0.449      | -            | -                | -                | -         |   -12.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2854 | 2024-04-13 | Aurora            | L   | 0.448      | -            | -                | -                | -         |    -3.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2862 | 2024-04-13 | Sampi             | W   | 0.447      | -            | -                | -                | -         |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2889 | 2024-04-11 | Aurora            | L   | 0.436      | -            | -                | -                | -         |    -3.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2897 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.435      | -            | -                | -                | -         |    10.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2903 | 2024-04-11 | AMKAL             | L   | 0.434      | -            | -                | -                | -         |   -11.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2942 | 2024-04-10 | Aurora            | W   | 0.428      | -            | -                | -                | -         |    10.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3001 | 2024-04-09 | BIG               | W   | 0.421      | -            | -                | -                | -         |     4.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3073 | 2024-04-06 | Alliance          | W   | 0.401      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3087 | 2024-04-05 | BLEED             | W   | 0.395      | -            | -                | -                | -         |     1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3123 | 2024-04-04 | Alliance          | W   | 0.389      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3136 | 2024-04-04 | BLEED             | W   | 0.388      | -            | -                | -                | -         |     1.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3306 | 2024-03-27 | FAVBET            | L   | 0.336      | -            | -                | -                | -         |   -10.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3344 | 2024-03-24 | FORZE             | L   | 0.314      | -            | -                | -                | -         |    -9.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3358 | 2024-03-23 | fnatic            | W   | 0.307      | -            | -                | -                | -         |     6.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3400 | 2024-03-21 | B8                | W   | 0.294      | -            | -                | -                | -         |     1.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3794 | 2024-03-05 | BLEED             | L   | 0.188      | -            | -                | -                | -         |    -5.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3812 | 2024-03-04 | Gaimin Gladiators | W   | 0.180      | -            | -                | -                | -         |     0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3824 | 2024-03-03 | ex-Preasy         | L   | 0.176      | -            | -                | -                | -         |    -5.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3829 | 2024-03-03 | ex-Sprout         | W   | 0.175      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3871 | 2024-03-01 | ex-Preasy         | W   | 0.163      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3903 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.147      | -            | -                | -                | -         |     0.37 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4010 | 2024-02-23 | ex-Guild Eagles   | L   | 0.114      | -            | -                | -                | -         |    -3.48 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4151 | 2024-02-17 | Eternal Fire      | L   | 0.075      | -            | -                | -                | -         |    -0.42 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4179 | 2024-02-16 | Natus Vincere     | L   | 0.068      | -            | -                | -                | -         |    -0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4212 | 2024-02-15 | Enterprise        | W   | 0.061      | -            | -                | -                | 1 (0.061) |     0.11 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4246 | 2024-02-14 | Into the Breach   | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4250 | 2024-02-14 | fnatic            | L   | 0.055      | -            | -                | -                | -         |    -0.55 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4333 | 2024-02-08 | FORZE             | L   | 0.016      | -            | -                | -                | -         |    -0.47 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4340 | 2024-02-08 | Nemiga            | L   | 0.015      | -            | -                | -                | -         |    -0.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,451.94)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $20,000.00     | $16,561.11      |
| 2024-05-26 |      0.735 | $2,000.00      | $1,470.00       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,928.82       |
| 2024-05-12 |      0.642 | $10,000.00     | $6,418.75       |
| 2024-05-12 |      0.641 | $17,500.00     | $11,224.31      |
| 2024-05-04 |      0.588 | $10,000.00     | $5,883.33       |
| 2024-05-02 |      0.575 | $1,000.00      | $575.00         |
| 2024-04-14 |      0.455 | $52,500.00     | $23,865.63      |
| 2024-04-14 |      0.454 | $9,000.00      | $4,087.50       |
| 2024-03-06 |      0.195 | $12,500.00     | $2,437.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
