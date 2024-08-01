### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [86](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  922.5<br />
<br />
Final Rank Value (922.5) = Starting Rank Value (944.0) + Head To Head Adjustments (-21.5)<br />

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
|           48 |      245 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      325 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.038 (0.017)    | 0.425 (0.185)    | 0 (0.000) |    16.66 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      392 | 2024-07-20 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    15.10 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      423 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.81 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      582 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.405 (0.176)    | 0 (0.000) |    14.72 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      629 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.53 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      903 | 2024-06-16 | ARCRED          | W   | 0.892      | 0.450        | 0.038 (0.015)    | 0.327 (0.131)    | 0 (0.000) |    16.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      922 | 2024-06-15 | System5         | L   | 0.887      | -            | -                | -                | -         |   -21.53 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |      934 | 2024-06-15 | Spirit Academy  | W   | 0.886      | 0.450        | 0.014 (0.005)    | -                | 0 (0.000) |     8.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |      959 | 2024-06-14 | Zero Tenacity   | L   | 0.880      | -            | -                | -                | -         |    -9.33 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |      965 | 2024-06-14 | LEON            | W   | 0.879      | -            | -                | -                | 0 (0.000) |     6.46 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1109 | 2024-06-09 | Insilio         | L   | 0.846      | -            | -                | -                | -         |   -11.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1265 | 2024-06-07 | SINNERS         | L   | 0.832      | -            | -                | -                | -         |   -10.53 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1383 | 2024-06-05 | ARCRED          | L   | 0.819      | -            | -                | -                | -         |   -13.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1399 | 2024-06-05 | Rare Atom       | L   | 0.818      | -            | -                | -                | -         |   -21.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1448 | 2024-06-03 | Insilio         | W   | 0.807      | 0.372        | 0.023 (0.007)    | 0.554 (0.166)    | 0 (0.000) |    12.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1457 | 2024-06-03 | HAVU            | L   | 0.806      | -            | -                | -                | -         |   -20.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1492 | 2024-06-01 | Zero Tenacity   | W   | 0.794      | 0.372        | 0.139 (0.041)    | 1.000 (0.296)    | 0 (0.000) |    17.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1555 | 2024-05-30 | Portugal        | W   | 0.780      | -            | -                | -                | 0 (0.000) |     4.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1568 | 2024-05-30 | FURIA           | L   | 0.779      | -            | -                | -                | -         |    -0.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1612 | 2024-05-28 | MOUZ NXT        | L   | 0.766      | -            | -                | -                | -         |    -8.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1655 | 2024-05-26 | Zero Tenacity   | L   | 0.752      | -            | -                | -                | -         |    -7.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1665 | 2024-05-25 | B8              | L   | 0.747      | -            | -                | -                | -         |    -5.88 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1703 | 2024-05-23 | Nexus           | W   | 0.733      | 0.435        | 0.014 (0.004)    | 0.504 (0.160)    | 0 (0.000) |     6.48 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1811 | 2024-05-21 | Endpoint        | W   | 0.718      | 0.435        | -                | 0.555 (0.173)    | -         |    10.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2169 | 2024-05-11 | 9 Pandas        | L   | 0.653      | -            | -                | -                | -         |    -8.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2195 | 2024-05-10 | Nemiga          | W   | 0.644      | 0.435        | 0.324 (0.091)    | 0.697 (0.195)    | -         |    15.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2254 | 2024-05-07 | Insilio         | W   | 0.626      | 0.435        | 0.023 (0.006)    | 0.554 (0.151)    | -         |     9.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2297 | 2024-05-05 | HAVU            | W   | 0.612      | -            | -                | -                | -         |     4.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2327 | 2024-05-03 | V1dar           | W   | 0.599      | -            | -                | -                | -         |     1.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2386 | 2024-05-01 | GL Academy      | L   | 0.584      | -            | -                | -                | -         |   -13.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2429 | 2024-04-29 | Permitta        | L   | 0.571      | -            | -                | -                | -         |    -9.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2460 | 2024-04-27 | Astralis Talent | W   | 0.559      | -            | -                | -                | -         |     0.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2626 | 2024-04-20 | Zero Tenacity   | L   | 0.512      | -            | -                | -                | -         |    -5.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2708 | 2024-04-18 | Sashi           | L   | 0.500      | -            | -                | -                | -         |    -4.50 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2718 | 2024-04-18 | Aurora          | W   | 0.500      | 0.143        | 0.431 (0.031)    | -                | -         |    15.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2725 | 2024-04-18 | NOM             | W   | 0.499      | -            | -                | -                | -         |     1.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2779 | 2024-04-17 | JANO            | W   | 0.491      | -            | -                | -                | -         |     3.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3434 | 2024-03-19 | Sashi           | L   | 0.300      | -            | -                | -                | -         |    -2.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3491 | 2024-03-16 | Permitta        | W   | 0.280      | -            | -                | -                | -         |     4.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3633 | 2024-03-11 | Nexus           | L   | 0.247      | -            | -                | -                | -         |    -4.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3671 | 2024-03-09 | Spirit Academy  | W   | 0.233      | -            | -                | -                | -         |     0.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3697 | 2024-03-08 | ARCRED          | W   | 0.227      | -            | -                | -                | -         |     2.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3934 | 2024-02-27 | Spirit Academy  | L   | 0.160      | -            | -                | -                | -         |    -4.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3938 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.160      | -            | -                | -                | -         |     2.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4361 | 2024-02-09 | FORZE           | L   | 0.039      | -            | -                | -                | -         |    -0.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4372 | 2024-02-08 | AMKAL           | L   | 0.034      | -            | -                | -                | -         |    -0.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4375 | 2024-02-08 | ex-Guild Eagles | W   | 0.033      | -            | -                | -                | -         |     0.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,575.01)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.892 | $30,000.00     | $26,758.33      |
| 2024-06-10 |      0.854 | $3,300.00      | $2,817.38       |
| 2024-05-12 |      0.660 | $2,000.00      | $1,319.86       |
| 2024-03-25 |      0.340 | $2,000.00      | $679.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
