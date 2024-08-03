### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  912.0<br />
<br />
Final Rank Value (912.0) = Starting Rank Value (933.7) + Head To Head Adjustments (-21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.261<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 933.7
- 400 + ( ( 0.261 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 933.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      303 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -4.09 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      382 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.433 (0.188)    | 0 (0.000) |    17.04 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      478 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -9.61 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      629 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.416 (0.181)    | 0 (0.000) |    14.30 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      673 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.69 | dekz, fostar, Kaide, mo0N, sowalio |
|           41 |      931 | 2024-06-16 | ARCRED          | W   | 0.879      | 0.450        | 0.041 (0.016)    | 0.356 (0.141)    | 0 (0.000) |    15.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |      947 | 2024-06-15 | System5         | L   | 0.873      | -            | -                | -                | -         |   -21.44 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |      959 | 2024-06-15 | Spirit Academy  | W   | 0.873      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     7.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |      989 | 2024-06-14 | LEON            | W   | 0.866      | -            | -                | -                | 0 (0.000) |     6.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1127 | 2024-06-09 | Insilio         | L   | 0.833      | -            | -                | -                | -         |   -10.83 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1268 | 2024-06-07 | SINNERS         | L   | 0.818      | -            | -                | -                | -         |   -10.22 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1382 | 2024-06-05 | ARCRED          | L   | 0.806      | -            | -                | -                | -         |   -13.12 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1397 | 2024-06-05 | Rare Atom       | L   | 0.804      | -            | -                | -                | -         |   -20.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1445 | 2024-06-03 | Insilio         | W   | 0.794      | 0.372        | 0.023 (0.007)    | 0.581 (0.172)    | 0 (0.000) |    12.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1454 | 2024-06-03 | HAVU            | L   | 0.793      | -            | -                | -                | -         |   -19.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1487 | 2024-06-01 | Zero Tenacity   | W   | 0.781      | 0.372        | 0.137 (0.040)    | 1.000 (0.291)    | 0 (0.000) |    17.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1549 | 2024-05-30 | Portugal        | W   | 0.767      | -            | -                | -                | 0 (0.000) |     4.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1562 | 2024-05-30 | FURIA           | L   | 0.765      | -            | -                | -                | -         |    -0.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1606 | 2024-05-28 | MOUZ NXT        | L   | 0.753      | -            | -                | -                | -         |    -8.09 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1646 | 2024-05-26 | Zero Tenacity   | L   | 0.739      | -            | -                | -                | -         |    -6.89 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1656 | 2024-05-25 | B8              | L   | 0.734      | -            | -                | -                | -         |    -5.33 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1694 | 2024-05-23 | Nexus           | W   | 0.720      | 0.435        | 0.014 (0.004)    | 0.441 (0.138)    | 0 (0.000) |     6.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1787 | 2024-05-21 | Endpoint        | W   | 0.704      | 0.435        | -                | 0.540 (0.165)    | 0 (0.000) |    10.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2124 | 2024-05-11 | 9 Pandas        | L   | 0.640      | -            | -                | -                | -         |    -8.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2150 | 2024-05-10 | Nemiga          | W   | 0.631      | 0.435        | 0.318 (0.087)    | 0.719 (0.197)    | -         |    15.29 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2206 | 2024-05-07 | Insilio         | W   | 0.613      | 0.435        | 0.023 (0.006)    | 0.581 (0.155)    | -         |     9.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2249 | 2024-05-05 | HAVU            | W   | 0.599      | -            | -                | -                | -         |     4.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2279 | 2024-05-03 | V1dar           | W   | 0.585      | -            | -                | -                | -         |     1.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2336 | 2024-05-01 | GL Academy      | L   | 0.571      | -            | -                | -                | -         |   -13.13 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2378 | 2024-04-29 | Permitta        | L   | 0.558      | -            | -                | -                | -         |    -8.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2409 | 2024-04-27 | Astralis Talent | W   | 0.546      | -            | -                | -                | -         |     0.78 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2568 | 2024-04-20 | Zero Tenacity   | L   | 0.499      | -            | -                | -                | -         |    -5.37 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2648 | 2024-04-18 | Sashi           | L   | 0.487      | -            | -                | -                | -         |    -4.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2658 | 2024-04-18 | Aurora          | W   | 0.486      | 0.143        | 0.425 (0.030)    | -                | -         |    15.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2665 | 2024-04-18 | NOM             | W   | 0.486      | -            | -                | -                | -         |     1.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2718 | 2024-04-17 | JANO            | W   | 0.478      | -            | -                | -                | -         |     2.95 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3353 | 2024-03-19 | Sashi           | L   | 0.287      | -            | -                | -                | -         |    -2.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3410 | 2024-03-16 | Permitta        | W   | 0.266      | 0.372        | -                | 0.887 (0.088)    | -         |     4.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3544 | 2024-03-11 | Nexus           | L   | 0.233      | -            | -                | -                | -         |    -4.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3581 | 2024-03-09 | Spirit Academy  | W   | 0.220      | -            | -                | -                | -         |     0.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3607 | 2024-03-08 | ARCRED          | W   | 0.213      | -            | -                | -                | -         |     2.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3837 | 2024-02-27 | Spirit Academy  | L   | 0.147      | -            | -                | -                | -         |    -4.17 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3841 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.147      | -            | -                | -                | -         |     2.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4245 | 2024-02-09 | FORZE           | L   | 0.026      | -            | -                | -                | -         |    -0.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4256 | 2024-02-08 | AMKAL           | L   | 0.020      | -            | -                | -                | -         |    -0.15 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4259 | 2024-02-08 | ex-Guild Eagles | W   | 0.019      | -            | -                | -                | -         |     0.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,079.41)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.879 | $30,000.00     | $26,359.72      |
| 2024-06-10 |      0.840 | $3,300.00      | $2,773.53       |
| 2024-05-12 |      0.647 | $2,000.00      | $1,293.29       |
| 2024-03-25 |      0.326 | $2,000.00      | $652.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
