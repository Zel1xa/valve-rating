### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1420.1<br />
<br />
Final Rank Value (1420.1) = Starting Rank Value (1423.8) + Head To Head Adjustments (-3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.625[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.562[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1423.8
- 400 + ( ( 0.501 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1423.8


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
|           64 |     1332 | 2024-06-07 | Astralis          | L   | 0.814      | -            | -                | -                | -         |    -3.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1387 | 2024-06-06 | Eternal Fire      | W   | 0.808      | 0.715        | 0.742 (0.429)    | 0.458 (0.264)    | 1 (0.808) |    19.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1398 | 2024-06-06 | Complexity        | W   | 0.807      | 0.715        | 0.310 (0.179)    | 0.380 (0.219)    | 1 (0.807) |    20.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1432 | 2024-06-05 | BIG               | W   | 0.802      | 0.715        | 0.155 (0.089)    | 0.304 (0.174)    | 1 (0.802) |    10.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1447 | 2024-06-05 | FURIA             | L   | 0.801      | -            | -                | -                | -         |    -6.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1456 | 2024-06-05 | fnatic            | W   | 0.800      | 0.715        | 0.371 (0.212)    | 0.708 (0.405)    | 1 (0.800) |    15.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1739 | 2024-05-25 | B8                | L   | 0.727      | -            | -                | -                | -         |   -17.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1764 | 2024-05-24 | DMS               | W   | 0.719      | -            | -                | -                | 0 (0.000) |     1.64 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1854 | 2024-05-21 | Eternal Fire      | L   | 0.701      | -            | -                | -                | -         |    -3.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1882 | 2024-05-20 | MIBR              | W   | 0.695      | 0.769        | 0.209 (0.112)    | 0.659 (0.352)    | -         |    12.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1888 | 2024-05-20 | Astralis          | L   | 0.694      | -            | -                | -                | -         |    -2.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1902 | 2024-05-20 | MIBR              | W   | 0.692      | 0.769        | 0.209 (0.111)    | 0.659 (0.351)    | -         |    13.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2064 | 2024-05-15 | Falcons           | L   | 0.661      | -            | -                | -                | -         |    -9.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2129 | 2024-05-14 | MOUZ              | L   | 0.653      | -            | -                | -                | -         |    -1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2171 | 2024-05-12 | B8                | L   | 0.641      | -            | -                | -                | -         |   -16.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2175 | 2024-05-12 | 9 Pandas          | W   | 0.640      | 0.435        | -                | 0.690 (0.192)    | -         |     2.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2208 | 2024-05-11 | Metizport         | W   | 0.633      | -            | -                | -                | -         |     1.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2225 | 2024-05-10 | Enterprise        | W   | 0.627      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2285 | 2024-05-07 | FlyQuest          | L   | 0.607      | -            | -                | -                | -         |   -14.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2336 | 2024-05-04 | AMKAL             | L   | 0.588      | -            | -                | -                | -         |   -14.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2341 | 2024-05-04 | 9 Pandas          | W   | 0.587      | 0.435        | -                | 0.690 (0.176)    | -         |     1.62 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2364 | 2024-05-03 | Insilio           | W   | 0.579      | -            | -                | -                | -         |     1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2405 | 2024-05-01 | EYEBALLERS        | W   | 0.567      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2435 | 2024-04-30 | 3DMAX             | L   | 0.560      | -            | -                | -                | -         |    -4.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2509 | 2024-04-26 | M80               | W   | 0.535      | 0.889        | 0.188 (0.090)    | 0.587 (0.279)    | 1 (0.535) |     4.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2523 | 2024-04-26 | Falcons           | W   | 0.533      | 0.889        | 0.224 (0.106)    | -                | 1 (0.533) |     8.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2546 | 2024-04-25 | Vitality          | L   | 0.527      | -            | -                | -                | -         |    -1.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2578 | 2024-04-23 | M80               | W   | 0.515      | 0.889        | 0.188 (0.086)    | 0.587 (0.269)    | 1 (0.515) |     4.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2687 | 2024-04-19 | Cloud9            | L   | 0.488      | -            | -                | -                | -         |   -13.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2698 | 2024-04-19 | Eternal Fire      | L   | 0.487      | -            | -                | -                | -         |    -2.41 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2722 | 2024-04-18 | Apeks             | W   | 0.482      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2726 | 2024-04-18 | brazylijski luz   | W   | 0.481      | -            | -                | -                | -         |     0.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2733 | 2024-04-18 | Serbia            | W   | 0.481      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2852 | 2024-04-14 | 3DMAX             | W   | 0.453      | 0.358        | 0.506 (0.082)    | -                | -         |    11.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2858 | 2024-04-13 | OG                | L   | 0.448      | -            | -                | -                | -         |   -12.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2862 | 2024-04-13 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2870 | 2024-04-13 | Sampi             | W   | 0.446      | -            | -                | -                | -         |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2897 | 2024-04-11 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -3.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2905 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.434      | -            | -                | -                | -         |    11.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2911 | 2024-04-11 | AMKAL             | L   | 0.433      | -            | -                | -                | -         |   -11.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2950 | 2024-04-10 | Aurora            | W   | 0.427      | -            | -                | -                | -         |    10.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3009 | 2024-04-09 | BIG               | W   | 0.420      | -            | -                | -                | -         |     4.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3081 | 2024-04-06 | Alliance          | W   | 0.400      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3095 | 2024-04-05 | BLEED             | W   | 0.395      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3131 | 2024-04-04 | Alliance          | W   | 0.388      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3144 | 2024-04-04 | BLEED             | W   | 0.387      | -            | -                | -                | -         |     1.06 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3314 | 2024-03-27 | FAVBET            | L   | 0.335      | -            | -                | -                | -         |   -10.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3352 | 2024-03-24 | FORZE             | L   | 0.313      | -            | -                | -                | -         |    -9.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3366 | 2024-03-23 | fnatic            | W   | 0.306      | -            | -                | -                | -         |     6.62 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3408 | 2024-03-21 | B8                | W   | 0.293      | -            | -                | -                | -         |     1.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3802 | 2024-03-05 | BLEED             | L   | 0.187      | -            | -                | -                | -         |    -5.44 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3820 | 2024-03-04 | Gaimin Gladiators | W   | 0.179      | -            | -                | -                | -         |     0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3832 | 2024-03-03 | ex-Preasy         | L   | 0.175      | -            | -                | -                | -         |    -5.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3837 | 2024-03-03 | ex-Sprout         | W   | 0.175      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3879 | 2024-03-01 | ex-Preasy         | W   | 0.162      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3911 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.147      | -            | -                | -                | -         |     0.37 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4018 | 2024-02-23 | ex-Guild Eagles   | L   | 0.114      | -            | -                | -                | -         |    -3.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4159 | 2024-02-17 | Eternal Fire      | L   | 0.074      | -            | -                | -                | -         |    -0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4187 | 2024-02-16 | Natus Vincere     | L   | 0.068      | -            | -                | -                | -         |    -0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4220 | 2024-02-15 | Enterprise        | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.11 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4254 | 2024-02-14 | Into the Breach   | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4258 | 2024-02-14 | fnatic            | L   | 0.054      | -            | -                | -                | -         |    -0.54 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4341 | 2024-02-08 | FORZE             | L   | 0.015      | -            | -                | -                | -         |    -0.45 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4348 | 2024-02-08 | Nemiga            | L   | 0.014      | -            | -                | -                | -         |    -0.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,346.46)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.827 | $20,000.00     | $16,546.76      |
| 2024-05-26 |      0.734 | $2,000.00      | $1,468.56       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,919.85       |
| 2024-05-12 |      0.641 | $10,000.00     | $6,411.57       |
| 2024-05-12 |      0.641 | $17,500.00     | $11,211.75      |
| 2024-05-04 |      0.588 | $10,000.00     | $5,876.16       |
| 2024-05-02 |      0.574 | $1,000.00      | $574.28         |
| 2024-04-14 |      0.454 | $52,500.00     | $23,827.95      |
| 2024-04-14 |      0.453 | $9,000.00      | $4,081.04       |
| 2024-03-06 |      0.194 | $12,500.00     | $2,428.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
