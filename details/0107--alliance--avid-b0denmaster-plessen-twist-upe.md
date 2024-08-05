### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.4<br />
<br />
Final Rank Value (848.4) = Starting Rank Value (849.2) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.098[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.2
- 400 + ( ( 0.218 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 849.2


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
|           47 |      102 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -11.64 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      917 | 2024-06-14 | MIBR            | L   | 0.886      | -            | -                | -                | -         |    -1.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           45 |      933 | 2024-06-14 | Complexity      | L   | 0.884      | -            | -                | -                | -         |    -0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     1073 | 2024-06-09 | Johnny Speeds   | L   | 0.852      | -            | -                | -                | -         |    -2.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1096 | 2024-06-09 | Lilmix          | W   | 0.851      | 0.347        | 0.023 (0.007)    | 0.098 (0.029)    | 1 (0.851) |    14.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1492 | 2024-05-31 | VP.Prodigy      | L   | 0.790      | -            | -                | -                | -         |   -10.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1629 | 2024-05-24 | B8              | L   | 0.746      | -            | -                | -                | -         |    -3.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     2003 | 2024-05-14 | kONO            | L   | 0.678      | -            | -                | -                | -         |   -10.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     2307 | 2024-04-30 | B8              | L   | 0.584      | -            | -                | -                | -         |    -5.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2333 | 2024-04-29 | Endpoint        | W   | 0.577      | 0.384        | 0.012 (0.003)    | 0.523 (0.116)    | 0 (0.000) |     9.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2346 | 2024-04-28 | DMS             | W   | 0.571      | 0.500        | 0.003 (0.001)    | 0.447 (0.128)    | 0 (0.000) |     9.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2385 | 2024-04-26 | B8              | L   | 0.559      | -            | -                | -                | -         |    -4.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2460 | 2024-04-23 | Metizport       | L   | 0.538      | -            | -                | -                | -         |    -6.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2477 | 2024-04-22 | B8              | W   | 0.531      | 0.384        | 0.167 (0.034)    | 0.879 (0.179)    | 0 (0.000) |    12.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2500 | 2024-04-21 | Sangal          | L   | 0.524      | -            | -                | -                | -         |    -2.99 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2581 | 2024-04-19 | 9 Pandas        | W   | 0.510      | 0.500        | 0.082 (0.021)    | 0.579 (0.148)    | 0 (0.000) |    10.99 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2653 | 2024-04-17 | Nemiga          | L   | 0.499      | -            | -                | -                | -         |    -2.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2665 | 2024-04-17 | ECLOT           | L   | 0.497      | -            | -                | -                | -         |    -3.37 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2712 | 2024-04-15 | HAVU            | W   | 0.485      | 0.384        | -                | 0.162 (0.030)    | 0 (0.000) |     4.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2716 | 2024-04-15 | MOUZ NXT        | L   | 0.484      | -            | -                | -                | -         |    -3.78 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2744 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.471      | -            | -                | -                | -         |    -5.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2785 | 2024-04-11 | Zero Tenacity   | W   | 0.458      | 0.384        | 0.138 (0.024)    | 1.000 (0.176)    | 0 (0.000) |    11.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2878 | 2024-04-09 | BLEED           | L   | 0.445      | -            | -                | -                | -         |    -4.34 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2894 | 2024-04-09 | Astralis Talent | W   | 0.443      | 0.371        | 0.009 (0.001)    | 0.162 (0.027)    | 0 (0.000) |     5.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     2939 | 2024-04-07 | Johnny Speeds   | L   | 0.432      | -            | -                | -                | -         |    -1.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     2942 | 2024-04-07 | EYEBALLERS      | L   | 0.431      | -            | -                | -                | -         |    -5.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     2951 | 2024-04-06 | Lilmix          | W   | 0.426      | -            | -                | -                | 0 (0.000) |     0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     2956 | 2024-04-06 | BetBoom         | L   | 0.425      | -            | -                | -                | -         |    -0.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     2973 | 2024-04-05 | BLEED           | L   | 0.418      | -            | -                | -                | -         |    -4.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3006 | 2024-04-04 | BetBoom         | L   | 0.413      | -            | -                | -                | -         |    -0.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3016 | 2024-04-04 | Benched Heroes  | W   | 0.412      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3061 | 2024-04-03 | AMKAL           | L   | 0.404      | -            | -                | -                | -         |    -2.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3460 | 2024-03-13 | MOUZ NXT        | L   | 0.264      | -            | -                | -                | -         |    -2.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3492 | 2024-03-12 | Passion UA      | L   | 0.258      | -            | -                | -                | -         |    -1.94 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3532 | 2024-03-10 | EYEBALLERS      | W   | 0.245      | -            | -                | -                | -         |     4.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3542 | 2024-03-09 | BLUDS           | W   | 0.239      | -            | -                | -                | -         |     0.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3556 | 2024-03-09 | Johnny Speeds   | W   | 0.238      | 0.143        | 0.123 (0.004)    | 0.817 (0.028)    | -         |     6.93 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3563 | 2024-03-09 | Entropiq        | W   | 0.237      | -            | -                | -                | -         |     1.22 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3606 | 2024-03-07 | ex-Sprout       | W   | 0.224      | -            | -                | -                | -         |     0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3637 | 2024-03-06 | Sashi           | L   | 0.217      | -            | -                | -                | -         |    -1.10 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3681 | 2024-03-05 | Viperio         | W   | 0.210      | -            | -                | -                | -         |     0.48 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3761 | 2024-03-01 | 9INE            | L   | 0.184      | -            | -                | -                | -         |    -5.11 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3788 | 2024-02-28 | Sangal          | W   | 0.171      | 0.143        | 0.219 (0.005)    | -                | -         |     4.53 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3843 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.152      | 0.358        | 0.032 (0.002)    | 0.564 (0.031)    | -         |     3.32 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     4014 | 2024-02-18 | Portugal        | W   | 0.104      | -            | -                | -                | -         |     0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4243 | 2024-02-06 | 9INE            | W   | 0.024      | -            | -                | -                | -         |     0.10 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4267 | 2024-02-04 | Secret          | L   | 0.012      | -            | -                | -                | -         |    -0.32 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,610.28)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.898 | $2,000.00      | $1,796.45       |
| 2024-06-09 |      0.852 | $2,889.00      | $2,460.96       |
| 2024-05-18 |      0.706 | $500.00        | $352.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
