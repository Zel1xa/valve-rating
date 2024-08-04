### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.1<br />
<br />
Final Rank Value (851.1) = Starting Rank Value (849.5) + Head To Head Adjustments (1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.5
- 400 + ( ( 0.220 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 849.5


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
|           47 |       29 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.54 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      100 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.190 (0.065)    | 0 (0.000) |    16.40 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      226 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -11.00 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1042 | 2024-06-14 | MIBR            | L   | 0.861      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1058 | 2024-06-14 | Complexity      | L   | 0.860      | -            | -                | -                | -         |    -0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1198 | 2024-06-09 | Johnny Speeds   | L   | 0.827      | -            | -                | -                | -         |    -2.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1221 | 2024-06-09 | Lilmix          | W   | 0.826      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.826) |    13.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1617 | 2024-05-31 | VP.Prodigy      | L   | 0.766      | -            | -                | -                | -         |    -9.96 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1754 | 2024-05-24 | B8              | L   | 0.721      | -            | -                | -                | -         |    -3.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2128 | 2024-05-14 | kONO            | L   | 0.653      | -            | -                | -                | -         |   -10.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2432 | 2024-04-30 | B8              | L   | 0.560      | -            | -                | -                | -         |    -5.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2458 | 2024-04-29 | Endpoint        | W   | 0.552      | 0.384        | 0.012 (0.003)    | 0.522 (0.111)    | 0 (0.000) |     9.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2471 | 2024-04-28 | DMS             | W   | 0.547      | 0.500        | -                | 0.446 (0.122)    | 0 (0.000) |     9.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2510 | 2024-04-26 | B8              | L   | 0.535      | -            | -                | -                | -         |    -4.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2585 | 2024-04-23 | Metizport       | L   | 0.514      | -            | -                | -                | -         |    -6.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2602 | 2024-04-22 | B8              | W   | 0.507      | 0.384        | 0.165 (0.032)    | 0.912 (0.178)    | 0 (0.000) |    11.76 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2625 | 2024-04-21 | Sangal          | L   | 0.499      | -            | -                | -                | -         |    -2.76 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2706 | 2024-04-19 | 9 Pandas        | W   | 0.486      | 0.500        | 0.082 (0.020)    | 0.690 (0.168)    | 0 (0.000) |    10.33 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2778 | 2024-04-17 | Nemiga          | L   | 0.474      | -            | -                | -                | -         |    -2.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2790 | 2024-04-17 | ECLOT           | L   | 0.473      | -            | -                | -                | -         |    -2.06 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2837 | 2024-04-15 | HAVU            | W   | 0.460      | 0.384        | -                | 0.160 (0.028)    | 0 (0.000) |     4.26 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2841 | 2024-04-15 | MOUZ NXT        | L   | 0.459      | -            | -                | -                | -         |    -3.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2869 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.446      | -            | -                | -                | -         |    -4.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2910 | 2024-04-11 | Zero Tenacity   | W   | 0.433      | 0.384        | 0.137 (0.023)    | 1.000 (0.167)    | 0 (0.000) |    10.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3003 | 2024-04-09 | BLEED           | L   | 0.421      | -            | -                | -                | -         |    -4.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3019 | 2024-04-09 | Astralis Talent | W   | 0.419      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     5.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3064 | 2024-04-07 | Johnny Speeds   | L   | 0.408      | -            | -                | -                | -         |    -1.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3067 | 2024-04-07 | EYEBALLERS      | L   | 0.407      | -            | -                | -                | -         |    -5.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3076 | 2024-04-06 | Lilmix          | W   | 0.402      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3081 | 2024-04-06 | BetBoom         | L   | 0.400      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3098 | 2024-04-05 | BLEED           | L   | 0.394      | -            | -                | -                | -         |    -4.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3131 | 2024-04-04 | BetBoom         | L   | 0.388      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3141 | 2024-04-04 | Benched Heroes  | W   | 0.387      | -            | -                | -                | -         |     0.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3186 | 2024-04-03 | AMKAL           | L   | 0.380      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3585 | 2024-03-13 | MOUZ NXT        | L   | 0.240      | -            | -                | -                | -         |    -2.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3617 | 2024-03-12 | Passion UA      | L   | 0.233      | -            | -                | -                | -         |    -1.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3657 | 2024-03-10 | EYEBALLERS      | W   | 0.220      | -            | -                | -                | -         |     3.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3667 | 2024-03-09 | BLUDS           | W   | 0.215      | -            | -                | -                | -         |     0.49 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3681 | 2024-03-09 | Johnny Speeds   | W   | 0.214      | 0.143        | 0.122 (0.004)    | 0.902 (0.028)    | -         |     6.19 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3688 | 2024-03-09 | Entropiq        | W   | 0.213      | -            | -                | -                | -         |     1.06 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3731 | 2024-03-07 | ex-Sprout       | W   | 0.200      | -            | -                | -                | -         |     0.82 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3762 | 2024-03-06 | Sashi           | L   | 0.193      | -            | -                | -                | -         |    -1.01 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3806 | 2024-03-05 | Viperio         | W   | 0.186      | -            | -                | -                | -         |     0.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3886 | 2024-03-01 | 9INE            | L   | 0.160      | -            | -                | -                | -         |    -4.42 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3913 | 2024-02-28 | Sangal          | W   | 0.146      | 0.143        | 0.219 (0.005)    | -                | -         |     3.90 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     3968 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.127      | 0.358        | 0.031 (0.001)    | 0.560 (0.026)    | -         |     2.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4139 | 2024-02-18 | Portugal        | W   | 0.080      | -            | -                | -                | -         |     0.71 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,478.25)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.874 | $2,000.00      | $1,747.45       |
| 2024-06-09 |      0.827 | $2,889.00      | $2,390.18       |
| 2024-05-18 |      0.681 | $500.00        | $340.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
