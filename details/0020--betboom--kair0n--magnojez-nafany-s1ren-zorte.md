### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1418.8<br />
<br />
Final Rank Value (1418.8) = Starting Rank Value (1421.5) + Head To Head Adjustments (-2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.624[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.558[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.5
- 400 + ( ( 0.499 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1421.5


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
|           64 |     1373 | 2024-06-07 | Astralis          | L   | 0.807      | -            | -                | -                | -         |    -3.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1428 | 2024-06-06 | Eternal Fire      | W   | 0.801      | 0.715        | 0.740 (0.424)    | 0.455 (0.261)    | 1 (0.801) |    19.63 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1439 | 2024-06-06 | Complexity        | W   | 0.800      | 0.715        | 0.342 (0.196)    | 0.378 (0.216)    | 1 (0.800) |    20.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1473 | 2024-06-05 | BIG               | W   | 0.795      | 0.715        | 0.155 (0.088)    | 0.302 (0.172)    | 1 (0.795) |    10.88 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1488 | 2024-06-05 | FURIA             | L   | 0.794      | -            | -                | -                | -         |    -6.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1497 | 2024-06-05 | fnatic            | W   | 0.793      | 0.715        | 0.371 (0.210)    | 0.706 (0.400)    | 1 (0.793) |    15.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1780 | 2024-05-25 | B8                | L   | 0.721      | -            | -                | -                | -         |   -17.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1805 | 2024-05-24 | DMS               | W   | 0.712      | -            | -                | -                | 0 (0.000) |     1.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1895 | 2024-05-21 | Eternal Fire      | L   | 0.694      | -            | -                | -                | -         |    -3.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1923 | 2024-05-20 | MIBR              | W   | 0.688      | 0.769        | 0.208 (0.110)    | 0.657 (0.347)    | -         |    12.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1929 | 2024-05-20 | Astralis          | L   | 0.688      | -            | -                | -                | -         |    -2.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1943 | 2024-05-20 | MIBR              | W   | 0.686      | 0.769        | 0.208 (0.110)    | 0.657 (0.346)    | -         |    13.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2105 | 2024-05-15 | Falcons           | L   | 0.654      | -            | -                | -                | -         |    -9.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2170 | 2024-05-14 | MOUZ              | L   | 0.647      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2212 | 2024-05-12 | B8                | L   | 0.634      | -            | -                | -                | -         |   -16.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2216 | 2024-05-12 | 9 Pandas          | W   | 0.633      | 0.435        | -                | 0.727 (0.200)    | -         |     2.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2249 | 2024-05-11 | Metizport         | W   | 0.626      | -            | -                | -                | -         |     0.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2266 | 2024-05-10 | Enterprise        | W   | 0.620      | -            | -                | -                | -         |     1.19 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2326 | 2024-05-07 | FlyQuest          | L   | 0.600      | -            | -                | -                | -         |   -14.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2377 | 2024-05-04 | AMKAL             | L   | 0.581      | -            | -                | -                | -         |   -14.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2382 | 2024-05-04 | 9 Pandas          | W   | 0.580      | 0.435        | -                | 0.727 (0.183)    | -         |     1.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2405 | 2024-05-03 | Insilio           | W   | 0.572      | -            | -                | -                | -         |     1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2446 | 2024-05-01 | EYEBALLERS        | W   | 0.560      | -            | -                | -                | -         |     0.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2476 | 2024-04-30 | 3DMAX             | L   | 0.553      | -            | -                | -                | -         |    -3.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2550 | 2024-04-26 | M80               | W   | 0.528      | 0.889        | 0.188 (0.088)    | 0.584 (0.274)    | 1 (0.528) |     4.82 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2564 | 2024-04-26 | Falcons           | W   | 0.526      | 0.889        | 0.222 (0.104)    | -                | 1 (0.526) |     8.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2587 | 2024-04-25 | Vitality          | L   | 0.520      | -            | -                | -                | -         |    -1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2619 | 2024-04-23 | M80               | W   | 0.508      | 0.889        | 0.188 (0.085)    | 0.584 (0.264)    | 1 (0.508) |     4.62 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2728 | 2024-04-19 | Cloud9            | L   | 0.481      | -            | -                | -                | -         |   -13.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2739 | 2024-04-19 | Eternal Fire      | L   | 0.480      | -            | -                | -                | -         |    -2.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2763 | 2024-04-18 | Apeks             | W   | 0.475      | -            | -                | -                | -         |     1.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2767 | 2024-04-18 | brazylijski luz   | W   | 0.475      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2774 | 2024-04-18 | Serbia            | W   | 0.474      | -            | -                | -                | -         |     0.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2893 | 2024-04-14 | 3DMAX             | W   | 0.447      | 0.358        | 0.508 (0.081)    | -                | -         |    11.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2899 | 2024-04-13 | OG                | L   | 0.441      | -            | -                | -                | -         |   -12.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2903 | 2024-04-13 | Aurora            | L   | 0.441      | -            | -                | -                | -         |    -3.03 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2911 | 2024-04-13 | Sampi             | W   | 0.439      | -            | -                | -                | -         |     0.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2938 | 2024-04-11 | Aurora            | L   | 0.428      | -            | -                | -                | -         |    -3.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2946 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.427      | -            | -                | -                | -         |    10.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2952 | 2024-04-11 | AMKAL             | L   | 0.426      | -            | -                | -                | -         |   -11.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2991 | 2024-04-10 | Aurora            | W   | 0.421      | -            | -                | -                | -         |    10.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3050 | 2024-04-09 | BIG               | W   | 0.413      | -            | -                | -                | -         |     4.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3122 | 2024-04-06 | Alliance          | W   | 0.393      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3136 | 2024-04-05 | BLEED             | W   | 0.388      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3172 | 2024-04-04 | Alliance          | W   | 0.381      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3185 | 2024-04-04 | BLEED             | W   | 0.380      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3355 | 2024-03-27 | FAVBET            | L   | 0.328      | -            | -                | -                | -         |   -10.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3393 | 2024-03-24 | FORZE             | L   | 0.306      | -            | -                | -                | -         |    -9.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3407 | 2024-03-23 | fnatic            | W   | 0.299      | -            | -                | -                | -         |     6.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3449 | 2024-03-21 | B8                | W   | 0.286      | -            | -                | -                | -         |     1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3843 | 2024-03-05 | BLEED             | L   | 0.180      | -            | -                | -                | -         |    -5.24 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3861 | 2024-03-04 | Gaimin Gladiators | W   | 0.172      | -            | -                | -                | -         |     0.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3873 | 2024-03-03 | ex-Preasy         | L   | 0.168      | -            | -                | -                | -         |    -5.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3878 | 2024-03-03 | ex-Sprout         | W   | 0.168      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3920 | 2024-03-01 | ex-Preasy         | W   | 0.155      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3952 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.140      | -            | -                | -                | -         |     0.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4059 | 2024-02-23 | ex-Guild Eagles   | L   | 0.107      | -            | -                | -                | -         |    -3.25 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4200 | 2024-02-17 | Eternal Fire      | L   | 0.068      | -            | -                | -                | -         |    -0.38 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4228 | 2024-02-16 | Natus Vincere     | L   | 0.061      | -            | -                | -                | -         |    -0.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4261 | 2024-02-15 | Enterprise        | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.10 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4295 | 2024-02-14 | Into the Breach   | W   | 0.048      | -            | -                | -                | 1 (0.048) |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4299 | 2024-02-14 | fnatic            | L   | 0.047      | -            | -                | -                | -         |    -0.47 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4382 | 2024-02-08 | FORZE             | L   | 0.008      | -            | -                | -                | -         |    -0.25 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4389 | 2024-02-08 | Nemiga            | L   | 0.007      | -            | -                | -                | -         |    -0.18 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($80,349.44)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $20,000.00     | $16,411.11      |
| 2024-05-26 |      0.728 | $2,000.00      | $1,455.00       |
| 2024-05-23 |      0.707 | $12,500.00     | $8,835.07       |
| 2024-05-12 |      0.634 | $10,000.00     | $6,343.75       |
| 2024-05-12 |      0.634 | $17,500.00     | $11,093.06      |
| 2024-05-04 |      0.581 | $10,000.00     | $5,808.33       |
| 2024-05-02 |      0.568 | $1,000.00      | $567.50         |
| 2024-04-14 |      0.447 | $52,500.00     | $23,471.88      |
| 2024-04-14 |      0.447 | $9,000.00      | $4,020.00       |
| 2024-03-06 |      0.188 | $12,500.00     | $2,343.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
