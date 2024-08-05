### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  877.2<br />
<br />
Final Rank Value (877.2) = Starting Rank Value (924.6) + Head To Head Adjustments (-47.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.6
- 400 + ( ( 0.256 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 924.6


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
|           48 |       36 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.47 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      378 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.24 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      458 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | -                | 0.235 (0.102)    | 0 (0.000) |    12.41 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      553 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.78 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      705 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.398 (0.173)    | 0 (0.000) |    14.61 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      751 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.16 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1021 | 2024-06-16 | ARCRED          | W   | 0.866      | 0.450        | 0.041 (0.016)    | 0.343 (0.134)    | 0 (0.000) |    15.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1041 | 2024-06-15 | System5         | L   | 0.861      | -            | -                | -                | -         |   -20.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1054 | 2024-06-15 | Spirit Academy  | W   | 0.860      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1085 | 2024-06-14 | Zero Tenacity   | L   | 0.854      | -            | -                | -                | -         |    -7.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1092 | 2024-06-14 | LEON            | W   | 0.854      | -            | -                | -                | 0 (0.000) |     6.31 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1234 | 2024-06-09 | Insilio         | L   | 0.821      | -            | -                | -                | -         |   -10.69 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1381 | 2024-06-07 | SINNERS         | L   | 0.806      | -            | -                | -                | -         |    -9.17 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1494 | 2024-06-05 | ARCRED          | L   | 0.794      | -            | -                | -                | -         |   -12.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1510 | 2024-06-05 | Rare Atom       | L   | 0.792      | -            | -                | -                | -         |   -16.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1559 | 2024-06-03 | Insilio         | W   | 0.781      | 0.372        | 0.023 (0.007)    | 0.559 (0.163)    | 0 (0.000) |    12.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1568 | 2024-06-03 | HAVU            | L   | 0.780      | -            | -                | -                | -         |   -19.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1602 | 2024-06-01 | Zero Tenacity   | W   | 0.768      | 0.372        | 0.137 (0.039)    | 1.000 (0.286)    | 0 (0.000) |    17.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1665 | 2024-05-30 | Portugal        | W   | 0.755      | -            | -                | -                | 0 (0.000) |     4.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1678 | 2024-05-30 | FURIA           | L   | 0.753      | -            | -                | -                | -         |    -0.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1722 | 2024-05-28 | MOUZ NXT        | L   | 0.741      | -            | -                | -                | -         |    -7.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1763 | 2024-05-26 | Zero Tenacity   | L   | 0.726      | -            | -                | -                | -         |    -6.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1773 | 2024-05-25 | B8              | L   | 0.722      | -            | -                | -                | -         |    -5.07 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1811 | 2024-05-23 | Nexus           | W   | 0.707      | 0.435        | 0.014 (0.004)    | 0.464 (0.142)    | 0 (0.000) |     6.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1904 | 2024-05-21 | Endpoint        | W   | 0.692      | 0.435        | 0.012 (0.004)    | 0.520 (0.157)    | 0 (0.000) |    10.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2242 | 2024-05-11 | 9 Pandas        | L   | 0.627      | -            | -                | -                | -         |    -8.17 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2268 | 2024-05-10 | Nemiga          | W   | 0.619      | 0.435        | 0.316 (0.085)    | 0.731 (0.197)    | -         |    15.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2325 | 2024-05-07 | Insilio         | W   | 0.601      | 0.435        | 0.023 (0.006)    | 0.559 (0.146)    | -         |     9.66 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2368 | 2024-05-05 | HAVU            | W   | 0.587      | -            | -                | -                | -         |     4.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2398 | 2024-05-03 | V1dar           | W   | 0.573      | -            | -                | -                | -         |     1.89 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2455 | 2024-05-01 | GL Academy      | L   | 0.559      | -            | -                | -                | -         |   -12.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2497 | 2024-04-29 | Permitta        | L   | 0.546      | -            | -                | -                | -         |    -8.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2528 | 2024-04-27 | Astralis Talent | W   | 0.534      | -            | -                | -                | -         |     0.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2688 | 2024-04-20 | Zero Tenacity   | L   | 0.487      | -            | -                | -                | -         |    -5.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2768 | 2024-04-18 | Sashi           | L   | 0.475      | -            | -                | -                | -         |    -3.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2778 | 2024-04-18 | Aurora          | W   | 0.474      | 0.143        | 0.422 (0.029)    | -                | -         |    14.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2785 | 2024-04-18 | NOM             | W   | 0.474      | -            | -                | -                | -         |     1.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2838 | 2024-04-17 | JANO            | W   | 0.466      | -            | -                | -                | -         |     2.98 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3478 | 2024-03-19 | Sashi           | L   | 0.275      | -            | -                | -                | -         |    -2.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3535 | 2024-03-16 | Permitta        | W   | 0.254      | 0.372        | -                | 0.873 (0.083)    | -         |     4.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3672 | 2024-03-11 | Nexus           | L   | 0.221      | -            | -                | -                | -         |    -4.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3709 | 2024-03-09 | Spirit Academy  | W   | 0.208      | -            | -                | -                | -         |     0.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3735 | 2024-03-08 | ARCRED          | W   | 0.201      | -            | -                | -                | -         |     2.67 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3965 | 2024-02-27 | Spirit Academy  | L   | 0.135      | -            | -                | -                | -         |    -3.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3969 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.134      | -            | -                | -                | -         |     2.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4374 | 2024-02-09 | FORZE           | L   | 0.014      | -            | -                | -                | -         |    -0.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4385 | 2024-02-08 | AMKAL           | L   | 0.008      | -            | -                | -                | -         |    -0.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4388 | 2024-02-08 | ex-Guild Eagles | W   | 0.007      | -            | -                | -                | -         |     0.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,621.79)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $30,000.00     | $25,991.67      |
| 2024-06-10 |      0.828 | $3,300.00      | $2,733.04       |
| 2024-05-12 |      0.634 | $2,000.00      | $1,268.75       |
| 2024-03-25 |      0.314 | $2,000.00      | $628.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
