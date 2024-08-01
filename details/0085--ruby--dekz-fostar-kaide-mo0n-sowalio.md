### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  922.5<br />
<br />
Final Rank Value (922.5) = Starting Rank Value (944.0) + Head To Head Adjustments (-21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.496[<sup>1</sup>](#table2)
- Bounty Collected: 0.379[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.264<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.0
- 400 + ( ( 0.264 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 944.0


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
|           48 |      247 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      327 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.424 (0.184)    | 0 (0.000) |    16.66 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      394 | 2024-07-20 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    15.11 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      425 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.81 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      584 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.405 (0.176)    | 0 (0.000) |    14.72 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      631 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.53 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      905 | 2024-06-16 | ARCRED          | W   | 0.892      | 0.450        | 0.038 (0.015)    | 0.327 (0.131)    | 0 (0.000) |    16.15 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      924 | 2024-06-15 | System5         | L   | 0.886      | -            | -                | -                | -         |   -21.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |      936 | 2024-06-15 | Spirit Academy  | W   | 0.886      | 0.450        | 0.014 (0.005)    | -                | 0 (0.000) |     8.27 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |      961 | 2024-06-14 | Zero Tenacity   | L   | 0.880      | -            | -                | -                | -         |    -9.32 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |      967 | 2024-06-14 | LEON            | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1111 | 2024-06-09 | Insilio         | L   | 0.846      | -            | -                | -                | -         |   -11.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1267 | 2024-06-07 | SINNERS         | L   | 0.831      | -            | -                | -                | -         |   -10.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1385 | 2024-06-05 | ARCRED          | L   | 0.819      | -            | -                | -                | -         |   -13.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1401 | 2024-06-05 | Rare Atom       | L   | 0.817      | -            | -                | -                | -         |   -21.78 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1450 | 2024-06-03 | Insilio         | W   | 0.807      | 0.372        | 0.023 (0.007)    | 0.554 (0.166)    | 0 (0.000) |    12.53 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1459 | 2024-06-03 | HAVU            | L   | 0.806      | -            | -                | -                | -         |   -19.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1494 | 2024-06-01 | Zero Tenacity   | W   | 0.794      | 0.372        | 0.139 (0.041)    | 1.000 (0.295)    | 0 (0.000) |    17.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1557 | 2024-05-30 | Portugal        | W   | 0.780      | -            | -                | -                | 0 (0.000) |     4.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1570 | 2024-05-30 | FURIA           | L   | 0.778      | -            | -                | -                | -         |    -0.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1614 | 2024-05-28 | MOUZ NXT        | L   | 0.766      | -            | -                | -                | -         |    -8.39 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1657 | 2024-05-26 | Zero Tenacity   | L   | 0.752      | -            | -                | -                | -         |    -7.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1667 | 2024-05-25 | B8              | L   | 0.747      | -            | -                | -                | -         |    -5.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1705 | 2024-05-23 | Nexus           | W   | 0.733      | 0.435        | 0.014 (0.004)    | 0.504 (0.160)    | 0 (0.000) |     6.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1813 | 2024-05-21 | Endpoint        | W   | 0.718      | 0.435        | -                | 0.555 (0.173)    | -         |    10.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2171 | 2024-05-11 | 9 Pandas        | L   | 0.653      | -            | -                | -                | -         |    -8.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2197 | 2024-05-10 | Nemiga          | W   | 0.644      | 0.435        | 0.324 (0.091)    | 0.697 (0.195)    | -         |    15.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2256 | 2024-05-07 | Insilio         | W   | 0.626      | 0.435        | 0.023 (0.006)    | 0.554 (0.151)    | -         |     9.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2299 | 2024-05-05 | HAVU            | W   | 0.612      | -            | -                | -                | -         |     4.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2329 | 2024-05-03 | V1dar           | W   | 0.598      | -            | -                | -                | -         |     1.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2388 | 2024-05-01 | GL Academy      | L   | 0.584      | -            | -                | -                | -         |   -13.51 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2431 | 2024-04-29 | Permitta        | L   | 0.571      | -            | -                | -                | -         |    -9.17 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2462 | 2024-04-27 | Astralis Talent | W   | 0.559      | -            | -                | -                | -         |     0.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2628 | 2024-04-20 | Zero Tenacity   | L   | 0.512      | -            | -                | -                | -         |    -5.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2710 | 2024-04-18 | Sashi           | L   | 0.500      | -            | -                | -                | -         |    -4.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2720 | 2024-04-18 | Aurora          | W   | 0.499      | 0.143        | 0.431 (0.031)    | -                | -         |    15.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2727 | 2024-04-18 | NOM             | W   | 0.499      | -            | -                | -                | -         |     1.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2781 | 2024-04-17 | JANO            | W   | 0.491      | -            | -                | -                | -         |     3.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3436 | 2024-03-19 | Sashi           | L   | 0.300      | -            | -                | -                | -         |    -2.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3493 | 2024-03-16 | Permitta        | W   | 0.279      | -            | -                | -                | -         |     4.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3635 | 2024-03-11 | Nexus           | L   | 0.246      | -            | -                | -                | -         |    -4.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3673 | 2024-03-09 | Spirit Academy  | W   | 0.233      | -            | -                | -                | -         |     0.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3699 | 2024-03-08 | ARCRED          | W   | 0.226      | -            | -                | -                | -         |     2.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3936 | 2024-02-27 | Spirit Academy  | L   | 0.160      | -            | -                | -                | -         |    -4.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3940 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.160      | -            | -                | -                | -         |     2.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4363 | 2024-02-09 | FORZE           | L   | 0.039      | -            | -                | -                | -         |    -0.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4374 | 2024-02-08 | AMKAL           | L   | 0.033      | -            | -                | -                | -         |    -0.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4377 | 2024-02-08 | ex-Guild Eagles | W   | 0.032      | -            | -                | -                | -         |     0.34 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,564.65)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $30,000.00     | $26,750.00      |
| 2024-06-10 |      0.853 | $3,300.00      | $2,816.46       |
| 2024-05-12 |      0.660 | $2,000.00      | $1,319.31       |
| 2024-03-25 |      0.339 | $2,000.00      | $678.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
