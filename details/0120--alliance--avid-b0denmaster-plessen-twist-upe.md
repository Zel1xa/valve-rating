### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.4<br />
<br />
Final Rank Value (818.4) = Starting Rank Value (850.3) + Head To Head Adjustments (-31.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.3
- 400 + ( ( 0.220 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 850.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |        6 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.81 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       15 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.25 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       68 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      141 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.230 (0.079)    | 0 (0.000) |    16.50 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      269 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.46 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1083 | 2024-06-14 | MIBR            | L   | 0.854      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1099 | 2024-06-14 | Complexity      | L   | 0.853      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1239 | 2024-06-09 | Johnny Speeds   | L   | 0.821      | -            | -                | -                | -         |    -2.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1262 | 2024-06-09 | Lilmix          | W   | 0.820      | 0.347        | 0.023 (0.006)    | 0.098 (0.028)    | 1 (0.820) |    13.42 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1658 | 2024-05-31 | VP.Prodigy      | L   | 0.759      | -            | -                | -                | -         |    -9.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1795 | 2024-05-24 | B8              | L   | 0.714      | -            | -                | -                | -         |    -3.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2169 | 2024-05-14 | kONO            | L   | 0.647      | -            | -                | -                | -         |   -10.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2473 | 2024-04-30 | B8              | L   | 0.553      | -            | -                | -                | -         |    -5.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2499 | 2024-04-29 | Endpoint        | W   | 0.546      | 0.384        | 0.012 (0.002)    | 0.520 (0.109)    | 0 (0.000) |     9.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2512 | 2024-04-28 | DMS             | W   | 0.540      | 0.500        | -                | 0.444 (0.120)    | 0 (0.000) |     9.34 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2551 | 2024-04-26 | B8              | L   | 0.528      | -            | -                | -                | -         |    -4.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2626 | 2024-04-23 | Metizport       | L   | 0.507      | -            | -                | -                | -         |    -7.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2643 | 2024-04-22 | B8              | W   | 0.500      | 0.384        | 0.165 (0.032)    | 0.947 (0.182)    | 0 (0.000) |    11.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2666 | 2024-04-21 | Sangal          | L   | 0.492      | -            | -                | -                | -         |    -2.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2747 | 2024-04-19 | 9 Pandas        | W   | 0.479      | 0.500        | 0.081 (0.019)    | 0.727 (0.174)    | 0 (0.000) |    10.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2819 | 2024-04-17 | Nemiga          | L   | 0.467      | -            | -                | -                | -         |    -2.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2831 | 2024-04-17 | ECLOT           | L   | 0.466      | -            | -                | -                | -         |    -2.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2878 | 2024-04-15 | HAVU            | W   | 0.453      | 0.384        | -                | 0.159 (0.028)    | 0 (0.000) |     4.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2882 | 2024-04-15 | MOUZ NXT        | L   | 0.452      | -            | -                | -                | -         |    -3.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2910 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.439      | -            | -                | -                | -         |    -4.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2951 | 2024-04-11 | Zero Tenacity   | W   | 0.427      | 0.384        | 0.137 (0.022)    | 1.000 (0.164)    | 0 (0.000) |    10.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3044 | 2024-04-09 | BLEED           | L   | 0.414      | -            | -                | -                | -         |    -4.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3060 | 2024-04-09 | Astralis Talent | W   | 0.412      | 0.371        | 0.009 (0.001)    | 0.162 (0.025)    | 0 (0.000) |     5.19 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3105 | 2024-04-07 | Johnny Speeds   | L   | 0.401      | -            | -                | -                | -         |    -1.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3108 | 2024-04-07 | EYEBALLERS      | L   | 0.400      | -            | -                | -                | -         |    -5.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3117 | 2024-04-06 | Lilmix          | W   | 0.395      | -            | -                | -                | 0 (0.000) |     0.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3122 | 2024-04-06 | BetBoom         | L   | 0.393      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3139 | 2024-04-05 | BLEED           | L   | 0.387      | -            | -                | -                | -         |    -4.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3172 | 2024-04-04 | BetBoom         | L   | 0.381      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3182 | 2024-04-04 | Benched Heroes  | W   | 0.380      | -            | -                | -                | -         |     0.85 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3227 | 2024-04-03 | AMKAL           | L   | 0.373      | -            | -                | -                | -         |    -2.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3626 | 2024-03-13 | MOUZ NXT        | L   | 0.233      | -            | -                | -                | -         |    -1.95 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3658 | 2024-03-12 | Passion UA      | L   | 0.226      | -            | -                | -                | -         |    -1.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3698 | 2024-03-10 | EYEBALLERS      | W   | 0.214      | -            | -                | -                | -         |     3.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3708 | 2024-03-09 | BLUDS           | W   | 0.208      | -            | -                | -                | -         |     0.47 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3722 | 2024-03-09 | Johnny Speeds   | W   | 0.207      | 0.143        | 0.122 (0.004)    | 0.940 (0.028)    | -         |     6.02 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3729 | 2024-03-09 | Entropiq        | W   | 0.206      | -            | -                | -                | -         |     1.02 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3772 | 2024-03-07 | ex-Sprout       | W   | 0.193      | -            | -                | -                | -         |     0.77 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3803 | 2024-03-06 | Sashi           | L   | 0.186      | -            | -                | -                | -         |    -0.98 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3847 | 2024-03-05 | Viperio         | W   | 0.179      | -            | -                | -                | -         |     0.41 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3927 | 2024-03-01 | 9INE            | L   | 0.153      | -            | -                | -                | -         |    -4.24 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3954 | 2024-02-28 | Sangal          | W   | 0.139      | 0.143        | 0.219 (0.004)    | -                | -         |     3.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4009 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.121      | 0.358        | 0.031 (0.001)    | -                | -         |     2.58 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4180 | 2024-02-18 | Portugal        | W   | 0.073      | -            | -                | -                | -         |     0.65 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,441.70)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.867 | $2,000.00      | $1,733.89       |
| 2024-06-09 |      0.821 | $2,889.00      | $2,370.59       |
| 2024-05-18 |      0.674 | $500.00        | $337.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
