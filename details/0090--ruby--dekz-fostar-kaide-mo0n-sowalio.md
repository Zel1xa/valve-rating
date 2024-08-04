### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [90](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [65]( ../standings_europe.md)<br />
<br />
Final Rank Value:  880.2<br />
<br />
Final Rank Value (880.2) = Starting Rank Value (930.7) + Head To Head Adjustments (-50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.167[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.7
- 400 + ( ( 0.260 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 930.7


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
|           48 |        1 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.53 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      329 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.27 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      409 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.417 (0.181)    | 0 (0.000) |    17.34 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      504 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.96 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      657 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.401 (0.174)    | 0 (0.000) |    14.58 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      702 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.32 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      972 | 2024-06-16 | ARCRED          | W   | 0.874      | 0.450        | 0.041 (0.016)    | 0.344 (0.135)    | 0 (0.000) |    16.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      992 | 2024-06-15 | System5         | L   | 0.869      | -            | -                | -                | -         |   -21.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1005 | 2024-06-15 | Spirit Academy  | W   | 0.868      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.09 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1036 | 2024-06-14 | Zero Tenacity   | L   | 0.862      | -            | -                | -                | -         |    -7.30 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1043 | 2024-06-14 | LEON            | W   | 0.861      | -            | -                | -                | 0 (0.000) |     6.38 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1185 | 2024-06-09 | Insilio         | L   | 0.828      | -            | -                | -                | -         |   -10.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1332 | 2024-06-07 | SINNERS         | L   | 0.814      | -            | -                | -                | -         |   -10.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1445 | 2024-06-05 | ARCRED          | L   | 0.801      | -            | -                | -                | -         |   -13.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1461 | 2024-06-05 | Rare Atom       | L   | 0.799      | -            | -                | -                | -         |   -20.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1510 | 2024-06-03 | Insilio         | W   | 0.789      | 0.372        | 0.023 (0.007)    | 0.561 (0.165)    | 0 (0.000) |    12.37 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1519 | 2024-06-03 | HAVU            | L   | 0.788      | -            | -                | -                | -         |   -19.51 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1553 | 2024-06-01 | Zero Tenacity   | W   | 0.776      | 0.372        | 0.137 (0.040)    | 1.000 (0.289)    | 0 (0.000) |    17.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1616 | 2024-05-30 | Portugal        | W   | 0.762      | -            | -                | -                | 0 (0.000) |     4.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1629 | 2024-05-30 | FURIA           | L   | 0.761      | -            | -                | -                | -         |    -0.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1673 | 2024-05-28 | MOUZ NXT        | L   | 0.748      | -            | -                | -                | -         |    -7.93 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1714 | 2024-05-26 | Zero Tenacity   | L   | 0.734      | -            | -                | -                | -         |    -6.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1724 | 2024-05-25 | B8              | L   | 0.729      | -            | -                | -                | -         |    -5.22 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1762 | 2024-05-23 | Nexus           | W   | 0.715      | 0.435        | 0.014 (0.004)    | 0.465 (0.144)    | 0 (0.000) |     6.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1855 | 2024-05-21 | Endpoint        | W   | 0.700      | 0.435        | -                | 0.522 (0.159)    | 0 (0.000) |    10.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2193 | 2024-05-11 | 9 Pandas        | L   | 0.635      | -            | -                | -                | -         |    -8.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2219 | 2024-05-10 | Nemiga          | W   | 0.626      | 0.435        | 0.317 (0.086)    | 0.695 (0.189)    | -         |    15.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2276 | 2024-05-07 | Insilio         | W   | 0.608      | 0.435        | 0.023 (0.006)    | 0.561 (0.148)    | -         |     9.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2319 | 2024-05-05 | HAVU            | W   | 0.594      | -            | -                | -                | -         |     4.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2349 | 2024-05-03 | V1dar           | W   | 0.581      | -            | -                | -                | -         |     1.88 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2406 | 2024-05-01 | GL Academy      | L   | 0.566      | -            | -                | -                | -         |   -12.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2448 | 2024-04-29 | Permitta        | L   | 0.553      | -            | -                | -                | -         |    -8.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2479 | 2024-04-27 | Astralis Talent | W   | 0.541      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2639 | 2024-04-20 | Zero Tenacity   | L   | 0.494      | -            | -                | -                | -         |    -5.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2719 | 2024-04-18 | Sashi           | L   | 0.482      | -            | -                | -                | -         |    -4.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2729 | 2024-04-18 | Aurora          | W   | 0.482      | 0.143        | 0.424 (0.029)    | -                | -         |    14.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2736 | 2024-04-18 | NOM             | W   | 0.481      | -            | -                | -                | -         |     1.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2789 | 2024-04-17 | JANO            | W   | 0.473      | -            | -                | -                | -         |     2.95 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3429 | 2024-03-19 | Sashi           | L   | 0.282      | -            | -                | -                | -         |    -2.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3486 | 2024-03-16 | Permitta        | W   | 0.262      | 0.372        | -                | 0.876 (0.085)    | -         |     4.53 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3623 | 2024-03-11 | Nexus           | L   | 0.229      | -            | -                | -                | -         |    -4.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3660 | 2024-03-09 | Spirit Academy  | W   | 0.215      | -            | -                | -                | -         |     0.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3686 | 2024-03-08 | ARCRED          | W   | 0.209      | -            | -                | -                | -         |     2.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3916 | 2024-02-27 | Spirit Academy  | L   | 0.142      | -            | -                | -                | -         |    -4.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3920 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.142      | -            | -                | -                | -         |     2.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4325 | 2024-02-09 | FORZE           | L   | 0.021      | -            | -                | -                | -         |    -0.38 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4336 | 2024-02-08 | AMKAL           | L   | 0.016      | -            | -                | -                | -         |    -0.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4339 | 2024-02-08 | ex-Guild Eagles | W   | 0.015      | -            | -                | -                | -         |     0.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,901.54)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $30,000.00     | $26,216.67      |
| 2024-06-10 |      0.836 | $3,300.00      | $2,757.79       |
| 2024-05-12 |      0.642 | $2,000.00      | $1,283.75       |
| 2024-03-25 |      0.322 | $2,000.00      | $643.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
