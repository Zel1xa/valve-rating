### Roster Details<br />
Team Name: HEROIC<br />
Roster: kyxsan, NertZ, sAw, sjuush, TeSeS<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1563.1<br />
<br />
Final Rank Value (1563.1) = Starting Rank Value (1577.6) + Head To Head Adjustments (-14.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.270[<sup>2</sup>](#table1)
- LAN Wins: 0.868[<sup>2</sup>](#table1)

The average of these factors is 0.572<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1577.6
- 400 + ( ( 0.572 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1577.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      101 | 2024-07-30 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -3.58 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           46 |      126 | 2024-07-29 | Complexity        | W   | 1.000      | 0.581        | 0.318 (0.185)    | 0.366 (0.213)    | 1 (1.000) |    15.63 | kyxsan, NertZ, sAw, sjuush, TeSeS      |
|           45 |     1311 | 2024-06-06 | ENCE              | W   | 0.828      | 0.715        | 0.174 (0.103)    | 0.403 (0.239)    | 1 (0.828) |     5.88 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           44 |     1330 | 2024-06-06 | Sashi             | W   | 0.826      | 0.715        | 0.187 (0.110)    | 0.971 (0.574)    | 1 (0.826) |     3.44 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           43 |     1342 | 2024-06-06 | The MongolZ       | L   | 0.826      | -            | -                | -                | -         |    -3.09 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           42 |     1372 | 2024-06-05 | Ninjas in Pyjamas | L   | 0.821      | -            | -                | -                | -         |   -18.18 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           41 |     1394 | 2024-06-05 | Astralis          | L   | 0.819      | -            | -                | -                | -         |    -8.08 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           40 |     1527 | 2024-05-31 | Vitality          | L   | 0.788      | -            | -                | -                | -         |    -4.42 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           39 |     1573 | 2024-05-29 | BIG               | W   | 0.776      | -            | -                | -                | 1 (0.776) |     3.65 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           38 |     1585 | 2024-05-29 | Natus Vincere     | W   | 0.775      | 0.624        | 1.000 (0.484)    | 0.331 (0.160)    | 1 (0.775) |    21.77 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           37 |     1605 | 2024-05-28 | M80               | W   | 0.768      | 0.624        | 0.190 (0.091)    | 0.641 (0.308)    | 1 (0.768) |     4.03 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           36 |     1620 | 2024-05-27 | Virtus.pro        | L   | 0.763      | -            | -                | -                | -         |    -8.09 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           35 |     1899 | 2024-05-18 | MOUZ              | L   | 0.701      | -            | -                | -                | -         |    -2.65 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           34 |     1934 | 2024-05-17 | MIBR              | W   | 0.694      | 0.769        | 0.201 (0.107)    | 0.637 (0.340)    | 1 (0.694) |     7.96 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           33 |     1973 | 2024-05-16 | Spirit            | L   | 0.687      | -            | -                | -                | -         |    -2.50 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           32 |     2029 | 2024-05-15 | MIBR              | W   | 0.680      | 0.769        | 0.201 (0.105)    | 0.637 (0.333)    | 1 (0.680) |     7.77 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           31 |     2303 | 2024-05-04 | Ninjas in Pyjamas | L   | 0.608      | -            | -                | -                | -         |   -12.81 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           30 |     2316 | 2024-05-03 | BIG               | L   | 0.602      | -            | -                | -                | -         |   -16.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           29 |     2327 | 2024-05-03 | FlyQuest          | W   | 0.600      | 0.889        | -                | 0.323 (0.172)    | 1 (0.600) |     2.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           28 |     2347 | 2024-05-02 | Complexity        | L   | 0.594      | -            | -                | -                | -         |    -7.86 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           27 |     2395 | 2024-04-30 | Ninjas in Pyjamas | W   | 0.581      | 0.889        | 0.207 (0.107)    | 0.409 (0.211)    | 1 (0.581) |     5.95 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     2934 | 2024-04-10 | G2                | L   | 0.447      | -            | -                | -                | -         |    -1.36 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     2993 | 2024-04-09 | FURIA             | W   | 0.440      | 0.624        | 0.286 (0.079)    | -                | -         |     9.43 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     3024 | 2024-04-08 | 9z                | W   | 0.433      | 0.624        | -                | 0.554 (0.150)    | -         |     1.30 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     3035 | 2024-04-07 | Liquid            | L   | 0.431      | -            | -                | -                | -         |    -9.13 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     3353 | 2024-03-23 | paiN              | L   | 0.329      | -            | -                | -                | -         |    -7.84 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           21 |     3374 | 2024-03-22 | Virtus.pro        | L   | 0.320      | -            | -                | -                | -         |    -3.29 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           20 |     3387 | 2024-03-21 | Complexity        | L   | 0.315      | -            | -                | -                | -         |    -4.29 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           19 |     3394 | 2024-03-21 | FaZe              | W   | 0.314      | 1.000        | 0.638 (0.200)    | -                | -         |     6.74 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           18 |     3444 | 2024-03-18 | Eternal Fire      | W   | 0.294      | -            | -                | -                | -         |     6.43 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     3463 | 2024-03-17 | Imperial          | W   | 0.289      | -            | -                | -                | -         |     1.50 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           16 |     3472 | 2024-03-17 | Lynn Vision       | W   | 0.287      | -            | -                | -                | -         |     0.35 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           15 |     3580 | 2024-03-13 | Metizport         | W   | 0.261      | -            | -                | -                | -         |     0.22 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           14 |     3605 | 2024-03-12 | Virtus.pro        | L   | 0.255      | -            | -                | -                | -         |    -2.49 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     3624 | 2024-03-11 | ENCE              | W   | 0.248      | -            | -                | -                | -         |     2.95 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     3633 | 2024-03-11 | ex-Preasy         | W   | 0.247      | -            | -                | -                | -         |     0.11 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     3676 | 2024-03-09 | OG                | L   | 0.234      | -            | -                | -                | -         |    -7.09 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     3752 | 2024-03-06 | Young Ninjas      | W   | 0.215      | -            | -                | -                | -         |     0.07 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     4048 | 2024-02-22 | GamerLegion       | W   | 0.128      | -            | -                | -                | -         |     0.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     4070 | 2024-02-21 | Spirit            | L   | 0.121      | -            | -                | -                | -         |    -0.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     4105 | 2024-02-20 | Astralis          | W   | 0.113      | -            | -                | -                | -         |     2.33 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            6 |     4121 | 2024-02-19 | Vitality          | L   | 0.109      | -            | -                | -                | -         |    -0.63 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            5 |     4129 | 2024-02-19 | ex-Preasy         | W   | 0.107      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            4 |     4383 | 2024-02-06 | G2                | L   | 0.022      | -            | -                | -                | -         |    -0.06 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            3 |     4390 | 2024-02-06 | GamerLegion       | W   | 0.020      | -            | -                | -                | -         |     0.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            2 |     4398 | 2024-02-05 | Vitality          | W   | 0.013      | -            | -                | -                | -         |     0.35 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            1 |     4450 | 2024-02-03 | G2                | L   | 0.000      | -            | -                | -                | -         |     0.00 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68,362.47)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-06-02 |      0.802 | $10,000.00     | $8,016.67       |
| 2024-05-19 |      0.707 | $50,000.00     | $35,347.22      |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-04-14 |      0.473 | $6,000.00      | $2,837.64       |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |
| 2024-03-10 |      0.242 | $7,500.00      | $1,815.10       |
| 2024-02-11 |      0.054 | $24,000.00     | $1,306.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
