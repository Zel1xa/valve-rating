### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  881.0<br />
<br />
Final Rank Value (881.0) = Starting Rank Value (930.6) + Head To Head Adjustments (-49.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.6
- 400 + ( ( 0.260 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 930.6


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
|           48 |        6 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.55 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      337 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.26 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      417 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.417 (0.181)    | 0 (0.000) |    17.62 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      512 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.93 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      665 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.401 (0.174)    | 0 (0.000) |    14.60 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      710 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.29 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      980 | 2024-06-16 | ARCRED          | W   | 0.873      | 0.450        | 0.041 (0.016)    | 0.344 (0.135)    | 0 (0.000) |    15.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1000 | 2024-06-15 | System5         | L   | 0.868      | -            | -                | -                | -         |   -21.10 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1013 | 2024-06-15 | Spirit Academy  | W   | 0.867      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.09 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1044 | 2024-06-14 | Zero Tenacity   | L   | 0.861      | -            | -                | -                | -         |    -7.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1051 | 2024-06-14 | LEON            | W   | 0.860      | -            | -                | -                | 0 (0.000) |     6.38 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1193 | 2024-06-09 | Insilio         | L   | 0.828      | -            | -                | -                | -         |   -10.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1340 | 2024-06-07 | SINNERS         | L   | 0.813      | -            | -                | -                | -         |    -9.98 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1453 | 2024-06-05 | ARCRED          | L   | 0.800      | -            | -                | -                | -         |   -13.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1469 | 2024-06-05 | Rare Atom       | L   | 0.799      | -            | -                | -                | -         |   -20.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1518 | 2024-06-03 | Insilio         | W   | 0.788      | 0.372        | 0.023 (0.007)    | 0.561 (0.165)    | 0 (0.000) |    12.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1527 | 2024-06-03 | HAVU            | L   | 0.787      | -            | -                | -                | -         |   -19.48 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1561 | 2024-06-01 | Zero Tenacity   | W   | 0.775      | 0.372        | 0.137 (0.040)    | 1.000 (0.289)    | 0 (0.000) |    17.69 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1624 | 2024-05-30 | Portugal        | W   | 0.762      | -            | -                | -                | 0 (0.000) |     4.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1637 | 2024-05-30 | FURIA           | L   | 0.760      | -            | -                | -                | -         |    -0.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1681 | 2024-05-28 | MOUZ NXT        | L   | 0.747      | -            | -                | -                | -         |    -7.91 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1722 | 2024-05-26 | Zero Tenacity   | L   | 0.733      | -            | -                | -                | -         |    -6.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1732 | 2024-05-25 | B8              | L   | 0.728      | -            | -                | -                | -         |    -5.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1770 | 2024-05-23 | Nexus           | W   | 0.714      | 0.435        | 0.014 (0.004)    | 0.465 (0.144)    | 0 (0.000) |     6.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1863 | 2024-05-21 | Endpoint        | W   | 0.699      | 0.435        | -                | 0.522 (0.159)    | 0 (0.000) |    10.34 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2201 | 2024-05-11 | 9 Pandas        | L   | 0.634      | -            | -                | -                | -         |    -8.36 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2227 | 2024-05-10 | Nemiga          | W   | 0.626      | 0.435        | 0.317 (0.086)    | 0.695 (0.189)    | -         |    15.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2284 | 2024-05-07 | Insilio         | W   | 0.608      | 0.435        | 0.023 (0.006)    | 0.561 (0.148)    | -         |     9.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2327 | 2024-05-05 | HAVU            | W   | 0.593      | -            | -                | -                | -         |     4.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2357 | 2024-05-03 | V1dar           | W   | 0.580      | -            | -                | -                | -         |     1.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2414 | 2024-05-01 | GL Academy      | L   | 0.566      | -            | -                | -                | -         |   -12.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2456 | 2024-04-29 | Permitta        | L   | 0.552      | -            | -                | -                | -         |    -8.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2487 | 2024-04-27 | Astralis Talent | W   | 0.541      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2647 | 2024-04-20 | Zero Tenacity   | L   | 0.494      | -            | -                | -                | -         |    -5.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2727 | 2024-04-18 | Sashi           | L   | 0.481      | -            | -                | -                | -         |    -4.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2737 | 2024-04-18 | Aurora          | W   | 0.481      | 0.143        | 0.423 (0.029)    | -                | -         |    14.85 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2744 | 2024-04-18 | NOM             | W   | 0.480      | -            | -                | -                | -         |     1.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2797 | 2024-04-17 | JANO            | W   | 0.472      | -            | -                | -                | -         |     2.95 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3437 | 2024-03-19 | Sashi           | L   | 0.282      | -            | -                | -                | -         |    -2.18 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3494 | 2024-03-16 | Permitta        | W   | 0.261      | 0.372        | -                | 0.876 (0.085)    | -         |     4.51 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3631 | 2024-03-11 | Nexus           | L   | 0.228      | -            | -                | -                | -         |    -4.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3668 | 2024-03-09 | Spirit Academy  | W   | 0.215      | -            | -                | -                | -         |     0.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3694 | 2024-03-08 | ARCRED          | W   | 0.208      | -            | -                | -                | -         |     2.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3924 | 2024-02-27 | Spirit Academy  | L   | 0.142      | -            | -                | -                | -         |    -4.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3928 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.141      | -            | -                | -                | -         |     2.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4333 | 2024-02-09 | FORZE           | L   | 0.021      | -            | -                | -                | -         |    -0.36 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4344 | 2024-02-08 | AMKAL           | L   | 0.015      | -            | -                | -                | -         |    -0.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4347 | 2024-02-08 | ex-Guild Eagles | W   | 0.014      | -            | -                | -                | -         |     0.15 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,874.78)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $30,000.00     | $26,195.14      |
| 2024-06-10 |      0.835 | $3,300.00      | $2,755.42       |
| 2024-05-12 |      0.641 | $2,000.00      | $1,282.31       |
| 2024-03-25 |      0.321 | $2,000.00      | $641.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
