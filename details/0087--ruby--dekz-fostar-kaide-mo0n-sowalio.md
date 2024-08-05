### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [87](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  911.6<br />
<br />
Final Rank Value (911.6) = Starting Rank Value (938.8) + Head To Head Adjustments (-27.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.261<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 938.8
- 400 + ( ( 0.261 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 938.8


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
|           47 |      212 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.20 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      292 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.427 (0.186)    | 0 (0.000) |    17.48 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      387 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -9.02 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      539 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.406 (0.176)    | 0 (0.000) |    14.57 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      585 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.42 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      855 | 2024-06-16 | ARCRED          | W   | 0.898      | 0.450        | 0.038 (0.015)    | 0.328 (0.132)    | 0 (0.000) |    16.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      875 | 2024-06-15 | System5         | L   | 0.892      | -            | -                | -                | -         |   -21.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |      888 | 2024-06-15 | Spirit Academy  | W   | 0.892      | 0.450        | 0.014 (0.005)    | -                | 0 (0.000) |     8.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |      919 | 2024-06-14 | Zero Tenacity   | L   | 0.886      | -            | -                | -                | -         |    -7.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |      926 | 2024-06-14 | LEON            | W   | 0.885      | -            | -                | -                | 0 (0.000) |     6.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1068 | 2024-06-09 | Insilio         | L   | 0.852      | -            | -                | -                | -         |   -10.96 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1215 | 2024-06-07 | SINNERS         | L   | 0.837      | -            | -                | -                | -         |   -10.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1328 | 2024-06-05 | ARCRED          | L   | 0.825      | -            | -                | -                | -         |   -13.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1344 | 2024-06-05 | Rare Atom       | L   | 0.823      | -            | -                | -                | -         |   -21.94 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1393 | 2024-06-03 | Insilio         | W   | 0.813      | 0.372        | 0.023 (0.007)    | 0.554 (0.168)    | 0 (0.000) |    12.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1402 | 2024-06-03 | HAVU            | L   | 0.812      | -            | -                | -                | -         |   -20.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1436 | 2024-06-01 | Zero Tenacity   | W   | 0.800      | 0.372        | 0.138 (0.041)    | 1.000 (0.298)    | 0 (0.000) |    18.18 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1499 | 2024-05-30 | Portugal        | W   | 0.786      | -            | -                | -                | 0 (0.000) |     4.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1512 | 2024-05-30 | FURIA           | L   | 0.784      | -            | -                | -                | -         |    -0.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1556 | 2024-05-28 | MOUZ NXT        | L   | 0.772      | -            | -                | -                | -         |    -8.27 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1597 | 2024-05-26 | Zero Tenacity   | L   | 0.758      | -            | -                | -                | -         |    -7.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1607 | 2024-05-25 | B8              | L   | 0.753      | -            | -                | -                | -         |    -5.33 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1645 | 2024-05-23 | Nexus           | W   | 0.739      | 0.435        | 0.014 (0.004)    | 0.465 (0.149)    | 0 (0.000) |     6.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1738 | 2024-05-21 | Endpoint        | W   | 0.724      | 0.435        | -                | 0.523 (0.164)    | 0 (0.000) |    10.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2076 | 2024-05-11 | 9 Pandas        | L   | 0.659      | -            | -                | -                | -         |    -8.66 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2102 | 2024-05-10 | Nemiga          | W   | 0.650      | 0.435        | 0.322 (0.091)    | 0.698 (0.197)    | -         |    15.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2159 | 2024-05-07 | Insilio         | W   | 0.632      | 0.435        | 0.023 (0.006)    | 0.554 (0.152)    | -         |    10.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2202 | 2024-05-05 | HAVU            | W   | 0.618      | -            | -                | -                | -         |     4.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2232 | 2024-05-03 | V1dar           | W   | 0.604      | -            | -                | -                | -         |     1.93 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2289 | 2024-05-01 | GL Academy      | L   | 0.590      | -            | -                | -                | -         |   -13.53 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2331 | 2024-04-29 | Permitta        | L   | 0.577      | -            | -                | -                | -         |    -9.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2362 | 2024-04-27 | Astralis Talent | W   | 0.565      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2522 | 2024-04-20 | Zero Tenacity   | L   | 0.518      | -            | -                | -                | -         |    -5.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2602 | 2024-04-18 | Sashi           | L   | 0.506      | -            | -                | -                | -         |    -4.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2612 | 2024-04-18 | Aurora          | W   | 0.505      | 0.143        | 0.429 (0.031)    | -                | -         |    15.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2619 | 2024-04-18 | NOM             | W   | 0.505      | -            | -                | -                | -         |     1.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2672 | 2024-04-17 | JANO            | W   | 0.497      | -            | -                | -                | -         |     3.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3312 | 2024-03-19 | Sashi           | L   | 0.306      | -            | -                | -                | -         |    -2.39 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3369 | 2024-03-16 | Permitta        | W   | 0.285      | 0.372        | -                | 0.799 (0.085)    | -         |     4.69 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3506 | 2024-03-11 | Nexus           | L   | 0.252      | -            | -                | -                | -         |    -5.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3543 | 2024-03-09 | Spirit Academy  | W   | 0.239      | -            | -                | -                | -         |     0.81 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3569 | 2024-03-08 | ARCRED          | W   | 0.232      | -            | -                | -                | -         |     2.89 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3799 | 2024-02-27 | Spirit Academy  | L   | 0.166      | -            | -                | -                | -         |    -4.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3803 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.166      | -            | -                | -                | -         |     3.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4208 | 2024-02-09 | FORZE           | L   | 0.045      | -            | -                | -                | -         |    -0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4219 | 2024-02-08 | AMKAL           | L   | 0.039      | -            | -                | -                | -         |    -0.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4222 | 2024-02-08 | ex-Guild Eagles | W   | 0.038      | -            | -                | -                | -         |     0.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,788.63)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.898 | $30,000.00     | $26,930.14      |
| 2024-06-10 |      0.859 | $3,300.00      | $2,836.27       |
| 2024-05-12 |      0.666 | $2,000.00      | $1,331.31       |
| 2024-03-25 |      0.345 | $2,000.00      | $690.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
