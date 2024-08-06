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
Final Rank Value (1417.7) = Starting Rank Value (1417.6) + Head To Head Adjustments (0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.547[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 0.554[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1417.6
- 400 + ( ( 0.496 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1417.6


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
|           64 |     1388 | 2024-06-07 | Astralis          | L   | 0.801      | -            | -                | -                | -         |    -3.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1443 | 2024-06-06 | Eternal Fire      | W   | 0.795      | 0.715        | 0.739 (0.420)    | 0.448 (0.255)    | 1 (0.795) |    19.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1454 | 2024-06-06 | Complexity        | W   | 0.794      | 0.715        | 0.341 (0.194)    | 0.372 (0.211)    | 1 (0.794) |    20.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1488 | 2024-06-05 | BIG               | W   | 0.789      | 0.715        | 0.154 (0.087)    | 0.297 (0.167)    | 1 (0.789) |    10.79 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1503 | 2024-06-05 | FURIA             | L   | 0.788      | -            | -                | -                | -         |    -6.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1512 | 2024-06-05 | fnatic            | W   | 0.787      | 0.715        | 0.371 (0.209)    | 0.695 (0.392)    | 1 (0.787) |    14.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1795 | 2024-05-25 | B8                | L   | 0.715      | -            | -                | -                | -         |   -17.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1820 | 2024-05-24 | DMS               | W   | 0.706      | -            | -                | -                | 0 (0.000) |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1910 | 2024-05-21 | Eternal Fire      | L   | 0.688      | -            | -                | -                | -         |    -3.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1938 | 2024-05-20 | MIBR              | W   | 0.683      | 0.769        | 0.208 (0.109)    | 0.647 (0.340)    | -         |    12.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1944 | 2024-05-20 | Astralis          | L   | 0.682      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1958 | 2024-05-20 | MIBR              | W   | 0.680      | 0.769        | 0.208 (0.109)    | 0.647 (0.338)    | -         |    13.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2120 | 2024-05-15 | Falcons           | L   | 0.649      | -            | -                | -                | -         |    -9.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2185 | 2024-05-14 | MOUZ              | L   | 0.641      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2227 | 2024-05-12 | B8                | L   | 0.629      | -            | -                | -                | -         |   -16.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2231 | 2024-05-12 | 9 Pandas          | W   | 0.628      | 0.435        | -                | 0.716 (0.195)    | -         |     2.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2264 | 2024-05-11 | Metizport         | W   | 0.621      | -            | -                | -                | -         |     1.68 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2281 | 2024-05-10 | Enterprise        | W   | 0.614      | -            | -                | -                | -         |     1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2341 | 2024-05-07 | FlyQuest          | L   | 0.595      | -            | -                | -                | -         |   -14.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2392 | 2024-05-04 | AMKAL             | L   | 0.575      | -            | -                | -                | -         |   -14.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2397 | 2024-05-04 | 9 Pandas          | W   | 0.574      | 0.435        | -                | 0.716 (0.179)    | -         |     1.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2420 | 2024-05-03 | Insilio           | W   | 0.566      | -            | -                | -                | -         |     1.23 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2461 | 2024-05-01 | EYEBALLERS        | W   | 0.554      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2491 | 2024-04-30 | 3DMAX             | L   | 0.547      | -            | -                | -                | -         |    -3.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2565 | 2024-04-26 | M80               | W   | 0.523      | 0.889        | 0.188 (0.087)    | 0.576 (0.267)    | 1 (0.523) |     4.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2579 | 2024-04-26 | Falcons           | W   | 0.520      | 0.889        | 0.220 (0.102)    | -                | 1 (0.520) |     8.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2602 | 2024-04-25 | Vitality          | L   | 0.515      | -            | -                | -                | -         |    -1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2634 | 2024-04-23 | M80               | W   | 0.502      | 0.889        | 0.188 (0.084)    | 0.576 (0.257)    | 1 (0.502) |     4.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2743 | 2024-04-19 | Cloud9            | L   | 0.475      | -            | -                | -                | -         |   -13.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2754 | 2024-04-19 | Eternal Fire      | L   | 0.474      | -            | -                | -                | -         |    -2.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2778 | 2024-04-18 | Apeks             | W   | 0.469      | -            | -                | -                | -         |     1.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2782 | 2024-04-18 | brazylijski luz   | W   | 0.469      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2789 | 2024-04-18 | Serbia            | W   | 0.468      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2908 | 2024-04-14 | 3DMAX             | W   | 0.441      | 0.358        | 0.509 (0.080)    | -                | -         |    11.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2914 | 2024-04-13 | OG                | L   | 0.435      | -            | -                | -                | -         |   -12.14 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2918 | 2024-04-13 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -2.90 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2926 | 2024-04-13 | Sampi             | W   | 0.433      | -            | -                | -                | -         |     0.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2953 | 2024-04-11 | Aurora            | L   | 0.422      | -            | -                | -                | -         |    -2.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2961 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.422      | -            | -                | -                | -         |    10.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2967 | 2024-04-11 | AMKAL             | L   | 0.421      | -            | -                | -                | -         |   -10.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     3006 | 2024-04-10 | Aurora            | W   | 0.415      | -            | -                | -                | -         |    10.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3065 | 2024-04-09 | BIG               | W   | 0.408      | -            | -                | -                | -         |     4.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3137 | 2024-04-06 | Alliance          | W   | 0.388      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3151 | 2024-04-05 | BLEED             | W   | 0.382      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3187 | 2024-04-04 | Alliance          | W   | 0.376      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3200 | 2024-04-04 | BLEED             | W   | 0.374      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3370 | 2024-03-27 | FAVBET            | L   | 0.322      | -            | -                | -                | -         |    -9.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3408 | 2024-03-24 | FORZE             | L   | 0.300      | -            | -                | -                | -         |    -8.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3422 | 2024-03-23 | fnatic            | W   | 0.294      | -            | -                | -                | -         |     6.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3464 | 2024-03-21 | B8                | W   | 0.280      | -            | -                | -                | -         |     1.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3858 | 2024-03-05 | BLEED             | L   | 0.174      | -            | -                | -                | -         |    -5.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3876 | 2024-03-04 | Gaimin Gladiators | W   | 0.167      | -            | -                | -                | -         |     0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3888 | 2024-03-03 | ex-Preasy         | L   | 0.162      | -            | -                | -                | -         |    -4.97 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3893 | 2024-03-03 | ex-Sprout         | W   | 0.162      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3935 | 2024-03-01 | ex-Preasy         | W   | 0.149      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3967 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.134      | -            | -                | -                | -         |     0.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4074 | 2024-02-23 | ex-Guild Eagles   | L   | 0.101      | -            | -                | -                | -         |    -3.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4215 | 2024-02-17 | Eternal Fire      | L   | 0.062      | -            | -                | -                | -         |    -0.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4243 | 2024-02-16 | Natus Vincere     | L   | 0.055      | -            | -                | -                | -         |    -0.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4276 | 2024-02-15 | Enterprise        | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4310 | 2024-02-14 | Into the Breach   | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4314 | 2024-02-14 | fnatic            | L   | 0.041      | -            | -                | -                | -         |    -0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4397 | 2024-02-08 | FORZE             | L   | 0.002      | -            | -                | -                | -         |    -0.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4404 | 2024-02-08 | Nemiga            | L   | 0.001      | -            | -                | -                | -         |    -0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79,491.94)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $20,000.00     | $16,294.44      |
| 2024-05-26 |      0.722 | $2,000.00      | $1,443.33       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,762.15       |
| 2024-05-12 |      0.629 | $10,000.00     | $6,285.42       |
| 2024-05-12 |      0.628 | $17,500.00     | $10,990.97      |
| 2024-05-04 |      0.575 | $10,000.00     | $5,750.00       |
| 2024-05-02 |      0.562 | $1,000.00      | $561.67         |
| 2024-04-14 |      0.441 | $52,500.00     | $23,165.63      |
| 2024-04-14 |      0.441 | $9,000.00      | $3,967.50       |
| 2024-03-06 |      0.182 | $12,500.00     | $2,270.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
