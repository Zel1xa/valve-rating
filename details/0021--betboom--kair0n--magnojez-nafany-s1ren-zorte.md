### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1419.7<br />
<br />
Final Rank Value (1419.7) = Starting Rank Value (1426.0) + Head To Head Adjustments (-6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.625[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.270[<sup>2</sup>](#table1)
- LAN Wins: 0.564[<sup>2</sup>](#table1)

The average of these factors is 0.502<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1426.0
- 400 + ( ( 0.502 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1426.0


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
|           64 |     1320 | 2024-06-07 | Astralis          | L   | 0.817      | -            | -                | -                | -         |    -4.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1375 | 2024-06-06 | Eternal Fire      | W   | 0.811      | 0.715        | 0.743 (0.431)    | 0.458 (0.266)    | 1 (0.811) |    19.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1386 | 2024-06-06 | Complexity        | W   | 0.810      | 0.715        | 0.311 (0.180)    | 0.380 (0.221)    | 1 (0.810) |    20.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1420 | 2024-06-05 | BIG               | W   | 0.805      | 0.715        | 0.155 (0.090)    | 0.305 (0.176)    | 1 (0.805) |    11.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1435 | 2024-06-05 | FURIA             | L   | 0.805      | -            | -                | -                | -         |    -6.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1444 | 2024-06-05 | fnatic            | W   | 0.804      | 0.715        | 0.371 (0.213)    | 0.709 (0.407)    | 1 (0.804) |    15.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1727 | 2024-05-25 | B8                | L   | 0.731      | -            | -                | -                | -         |   -17.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1752 | 2024-05-24 | DMS               | W   | 0.723      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1842 | 2024-05-21 | Eternal Fire      | L   | 0.705      | -            | -                | -                | -         |    -3.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1870 | 2024-05-20 | MIBR              | W   | 0.699      | 0.769        | 0.210 (0.113)    | 0.659 (0.354)    | -         |    12.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1876 | 2024-05-20 | Astralis          | L   | 0.698      | -            | -                | -                | -         |    -2.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1890 | 2024-05-20 | MIBR              | W   | 0.696      | 0.769        | 0.210 (0.112)    | 0.659 (0.353)    | -         |    13.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2052 | 2024-05-15 | Falcons           | L   | 0.665      | -            | -                | -                | -         |    -9.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2117 | 2024-05-14 | MOUZ              | L   | 0.657      | -            | -                | -                | -         |    -1.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2159 | 2024-05-12 | B8                | L   | 0.645      | -            | -                | -                | -         |   -17.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2163 | 2024-05-12 | 9 Pandas          | W   | 0.644      | 0.435        | -                | 0.691 (0.193)    | -         |     2.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2196 | 2024-05-11 | Metizport         | W   | 0.637      | -            | -                | -                | -         |     1.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2213 | 2024-05-10 | Enterprise        | W   | 0.630      | -            | -                | -                | -         |     1.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2273 | 2024-05-07 | FlyQuest          | L   | 0.611      | -            | -                | -                | -         |   -14.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2324 | 2024-05-04 | AMKAL             | L   | 0.591      | -            | -                | -                | -         |   -14.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2329 | 2024-05-04 | 9 Pandas          | W   | 0.591      | 0.435        | -                | 0.691 (0.177)    | -         |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2352 | 2024-05-03 | Insilio           | W   | 0.583      | -            | -                | -                | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2393 | 2024-05-01 | EYEBALLERS        | W   | 0.571      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2423 | 2024-04-30 | 3DMAX             | L   | 0.563      | -            | -                | -                | -         |    -4.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2497 | 2024-04-26 | M80               | W   | 0.539      | 0.889        | 0.188 (0.090)    | 0.587 (0.281)    | 1 (0.539) |     4.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2510 | 2024-04-26 | Falcons           | W   | 0.537      | 0.889        | 0.225 (0.107)    | -                | 1 (0.537) |     8.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2533 | 2024-04-25 | Vitality          | L   | 0.531      | -            | -                | -                | -         |    -1.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2565 | 2024-04-23 | M80               | W   | 0.518      | 0.889        | 0.188 (0.087)    | 0.587 (0.271)    | 1 (0.518) |     4.70 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2674 | 2024-04-19 | Cloud9            | L   | 0.492      | -            | -                | -                | -         |   -13.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2685 | 2024-04-19 | Eternal Fire      | L   | 0.491      | -            | -                | -                | -         |    -2.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2709 | 2024-04-18 | Apeks             | W   | 0.485      | -            | -                | -                | -         |     1.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2713 | 2024-04-18 | brazylijski luz   | W   | 0.485      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2720 | 2024-04-18 | Serbia            | W   | 0.485      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2839 | 2024-04-14 | 3DMAX             | W   | 0.457      | 0.358        | 0.505 (0.083)    | -                | -         |    11.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2845 | 2024-04-13 | OG                | L   | 0.452      | -            | -                | -                | -         |   -12.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2849 | 2024-04-13 | Aurora            | L   | 0.451      | -            | -                | -                | -         |    -3.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2857 | 2024-04-13 | Sampi             | W   | 0.450      | -            | -                | -                | -         |     0.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2884 | 2024-04-11 | Aurora            | L   | 0.439      | -            | -                | -                | -         |    -3.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2892 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.438      | -            | -                | -                | -         |    11.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2898 | 2024-04-11 | AMKAL             | L   | 0.437      | -            | -                | -                | -         |   -11.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2937 | 2024-04-10 | Aurora            | W   | 0.431      | -            | -                | -                | -         |    10.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     2996 | 2024-04-09 | BIG               | W   | 0.424      | -            | -                | -                | -         |     4.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3068 | 2024-04-06 | Alliance          | W   | 0.404      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3082 | 2024-04-05 | BLEED             | W   | 0.398      | -            | -                | -                | -         |     1.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3118 | 2024-04-04 | Alliance          | W   | 0.392      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3131 | 2024-04-04 | BLEED             | W   | 0.391      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3301 | 2024-03-27 | FAVBET            | L   | 0.339      | -            | -                | -                | -         |   -10.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3339 | 2024-03-24 | FORZE             | L   | 0.317      | -            | -                | -                | -         |    -9.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3353 | 2024-03-23 | fnatic            | W   | 0.310      | -            | -                | -                | -         |     6.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3395 | 2024-03-21 | B8                | W   | 0.297      | -            | -                | -                | -         |     1.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3788 | 2024-03-05 | BLEED             | L   | 0.191      | -            | -                | -                | -         |    -5.55 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3806 | 2024-03-04 | Gaimin Gladiators | W   | 0.183      | -            | -                | -                | -         |     0.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3818 | 2024-03-03 | ex-Preasy         | L   | 0.179      | -            | -                | -                | -         |    -5.47 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3823 | 2024-03-03 | ex-Sprout         | W   | 0.178      | -            | -                | -                | -         |     0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3865 | 2024-03-01 | ex-Preasy         | W   | 0.166      | -            | -                | -                | -         |     0.14 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3897 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.151      | -            | -                | -                | -         |     0.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4004 | 2024-02-23 | ex-Guild Eagles   | L   | 0.117      | -            | -                | -                | -         |    -3.58 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4144 | 2024-02-17 | Eternal Fire      | L   | 0.078      | -            | -                | -                | -         |    -0.44 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4172 | 2024-02-16 | Natus Vincere     | L   | 0.071      | -            | -                | -                | -         |    -0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4205 | 2024-02-15 | Enterprise        | W   | 0.064      | -            | -                | -                | 1 (0.064) |     0.11 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4239 | 2024-02-14 | Into the Breach   | W   | 0.058      | -            | -                | -                | 1 (0.058) |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4243 | 2024-02-14 | fnatic            | L   | 0.058      | -            | -                | -                | -         |    -0.58 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4326 | 2024-02-08 | FORZE             | L   | 0.019      | -            | -                | -                | -         |    -0.56 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4333 | 2024-02-08 | Nemiga            | L   | 0.018      | -            | -                | -                | -         |    -0.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($81,901.11)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $20,000.00     | $16,622.22      |
| 2024-05-26 |      0.738 | $2,000.00      | $1,476.11       |
| 2024-05-23 |      0.717 | $12,500.00     | $8,967.01       |
| 2024-05-12 |      0.645 | $10,000.00     | $6,449.31       |
| 2024-05-12 |      0.644 | $17,500.00     | $11,277.78      |
| 2024-05-04 |      0.591 | $10,000.00     | $5,913.89       |
| 2024-05-02 |      0.578 | $1,000.00      | $578.06         |
| 2024-04-14 |      0.458 | $52,500.00     | $24,026.04      |
| 2024-04-14 |      0.457 | $9,000.00      | $4,115.00       |
| 2024-03-06 |      0.198 | $12,500.00     | $2,475.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
