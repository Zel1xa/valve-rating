### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1419.9<br />
<br />
Final Rank Value (1419.9) = Starting Rank Value (1424.0) + Head To Head Adjustments (-4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.625[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.561[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1424.0
- 400 + ( ( 0.501 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1424.0


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
|           64 |     1356 | 2024-06-07 | Astralis          | L   | 0.812      | -            | -                | -                | -         |    -3.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1411 | 2024-06-06 | Eternal Fire      | W   | 0.806      | 0.715        | 0.742 (0.428)    | 0.458 (0.264)    | 1 (0.806) |    19.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1422 | 2024-06-06 | Complexity        | W   | 0.806      | 0.715        | 0.342 (0.197)    | 0.380 (0.219)    | 1 (0.806) |    20.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1456 | 2024-06-05 | BIG               | W   | 0.801      | 0.715        | 0.155 (0.089)    | 0.304 (0.174)    | 1 (0.801) |    10.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1471 | 2024-06-05 | FURIA             | L   | 0.800      | -            | -                | -                | -         |    -6.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1480 | 2024-06-05 | fnatic            | W   | 0.799      | 0.715        | 0.371 (0.212)    | 0.708 (0.405)    | 1 (0.799) |    15.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1763 | 2024-05-25 | B8                | L   | 0.726      | -            | -                | -                | -         |   -17.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1788 | 2024-05-24 | DMS               | W   | 0.718      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1878 | 2024-05-21 | Eternal Fire      | L   | 0.700      | -            | -                | -                | -         |    -3.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1906 | 2024-05-20 | MIBR              | W   | 0.694      | 0.769        | 0.209 (0.112)    | 0.659 (0.352)    | -         |    12.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1912 | 2024-05-20 | Astralis          | L   | 0.693      | -            | -                | -                | -         |    -2.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1926 | 2024-05-20 | MIBR              | W   | 0.691      | 0.769        | 0.209 (0.111)    | 0.659 (0.350)    | -         |    13.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2088 | 2024-05-15 | Falcons           | L   | 0.660      | -            | -                | -                | -         |    -9.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2153 | 2024-05-14 | MOUZ              | L   | 0.652      | -            | -                | -                | -         |    -1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2195 | 2024-05-12 | B8                | L   | 0.640      | -            | -                | -                | -         |   -16.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2199 | 2024-05-12 | 9 Pandas          | W   | 0.639      | 0.435        | -                | 0.690 (0.192)    | -         |     2.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2232 | 2024-05-11 | Metizport         | W   | 0.632      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2249 | 2024-05-10 | Enterprise        | W   | 0.625      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2309 | 2024-05-07 | FlyQuest          | L   | 0.606      | -            | -                | -                | -         |   -14.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2360 | 2024-05-04 | AMKAL             | L   | 0.587      | -            | -                | -                | -         |   -14.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2365 | 2024-05-04 | 9 Pandas          | W   | 0.586      | 0.435        | -                | 0.690 (0.176)    | -         |     1.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2388 | 2024-05-03 | Insilio           | W   | 0.578      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2429 | 2024-05-01 | EYEBALLERS        | W   | 0.566      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2459 | 2024-04-30 | 3DMAX             | L   | 0.558      | -            | -                | -                | -         |    -4.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2533 | 2024-04-26 | M80               | W   | 0.534      | 0.889        | 0.188 (0.089)    | 0.587 (0.279)    | 1 (0.534) |     4.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2547 | 2024-04-26 | Falcons           | W   | 0.532      | 0.889        | 0.223 (0.106)    | -                | 1 (0.532) |     8.62 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2570 | 2024-04-25 | Vitality          | L   | 0.526      | -            | -                | -                | -         |    -1.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2602 | 2024-04-23 | M80               | W   | 0.514      | 0.889        | 0.188 (0.086)    | 0.587 (0.268)    | 1 (0.514) |     4.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2711 | 2024-04-19 | Cloud9            | L   | 0.487      | -            | -                | -                | -         |   -13.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2722 | 2024-04-19 | Eternal Fire      | L   | 0.486      | -            | -                | -                | -         |    -2.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2746 | 2024-04-18 | Apeks             | W   | 0.481      | -            | -                | -                | -         |     1.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2750 | 2024-04-18 | brazylijski luz   | W   | 0.480      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2757 | 2024-04-18 | Serbia            | W   | 0.480      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2876 | 2024-04-14 | 3DMAX             | W   | 0.452      | 0.358        | 0.506 (0.082)    | -                | -         |    11.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2882 | 2024-04-13 | OG                | L   | 0.447      | -            | -                | -                | -         |   -12.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2886 | 2024-04-13 | Aurora            | L   | 0.446      | -            | -                | -                | -         |    -3.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2894 | 2024-04-13 | Sampi             | W   | 0.445      | -            | -                | -                | -         |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2921 | 2024-04-11 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -3.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2929 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.433      | -            | -                | -                | -         |    11.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2935 | 2024-04-11 | AMKAL             | L   | 0.432      | -            | -                | -                | -         |   -11.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2974 | 2024-04-10 | Aurora            | W   | 0.426      | -            | -                | -                | -         |    10.55 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3033 | 2024-04-09 | BIG               | W   | 0.419      | -            | -                | -                | -         |     4.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3105 | 2024-04-06 | Alliance          | W   | 0.399      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3119 | 2024-04-05 | BLEED             | W   | 0.393      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3155 | 2024-04-04 | Alliance          | W   | 0.387      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3168 | 2024-04-04 | BLEED             | W   | 0.386      | -            | -                | -                | -         |     1.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3338 | 2024-03-27 | FAVBET            | L   | 0.334      | -            | -                | -                | -         |   -10.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3376 | 2024-03-24 | FORZE             | L   | 0.312      | -            | -                | -                | -         |    -9.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3390 | 2024-03-23 | fnatic            | W   | 0.305      | -            | -                | -                | -         |     6.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3432 | 2024-03-21 | B8                | W   | 0.292      | -            | -                | -                | -         |     1.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3826 | 2024-03-05 | BLEED             | L   | 0.186      | -            | -                | -                | -         |    -5.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3844 | 2024-03-04 | Gaimin Gladiators | W   | 0.178      | -            | -                | -                | -         |     0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3856 | 2024-03-03 | ex-Preasy         | L   | 0.174      | -            | -                | -                | -         |    -5.32 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3861 | 2024-03-03 | ex-Sprout         | W   | 0.173      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3903 | 2024-03-01 | ex-Preasy         | W   | 0.161      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3935 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.146      | -            | -                | -                | -         |     0.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4042 | 2024-02-23 | ex-Guild Eagles   | L   | 0.112      | -            | -                | -                | -         |    -3.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4183 | 2024-02-17 | Eternal Fire      | L   | 0.073      | -            | -                | -                | -         |    -0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4211 | 2024-02-16 | Natus Vincere     | L   | 0.067      | -            | -                | -                | -         |    -0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4244 | 2024-02-15 | Enterprise        | W   | 0.059      | -            | -                | -                | 1 (0.059) |     0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4278 | 2024-02-14 | Into the Breach   | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4282 | 2024-02-14 | fnatic            | L   | 0.053      | -            | -                | -                | -         |    -0.53 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4365 | 2024-02-08 | FORZE             | L   | 0.014      | -            | -                | -                | -         |    -0.42 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4372 | 2024-02-08 | Nemiga            | L   | 0.013      | -            | -                | -                | -         |    -0.32 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,189.93)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $20,000.00     | $16,525.46      |
| 2024-05-26 |      0.733 | $2,000.00      | $1,466.44       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,906.54       |
| 2024-05-12 |      0.640 | $10,000.00     | $6,400.93       |
| 2024-05-12 |      0.640 | $17,500.00     | $11,193.11      |
| 2024-05-04 |      0.587 | $10,000.00     | $5,865.51       |
| 2024-05-02 |      0.573 | $1,000.00      | $573.22         |
| 2024-04-14 |      0.453 | $52,500.00     | $23,772.05      |
| 2024-04-14 |      0.452 | $9,000.00      | $4,071.46       |
| 2024-03-06 |      0.193 | $12,500.00     | $2,415.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
