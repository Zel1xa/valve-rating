### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
<br />
Final Rank Value:  908.0<br />
<br />
Final Rank Value (908.0) = Starting Rank Value (931.0) + Head To Head Adjustments (-23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.0
- 400 + ( ( 0.260 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 931.0


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
|           47 |      326 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.27 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      406 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.418 (0.182)    | 0 (0.000) |    17.37 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      501 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -9.04 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      654 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.402 (0.175)    | 0 (0.000) |    14.58 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      699 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.32 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |      968 | 2024-06-16 | ARCRED          | W   | 0.877      | 0.450        | 0.041 (0.016)    | 0.344 (0.136)    | 0 (0.000) |    16.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |      988 | 2024-06-15 | System5         | L   | 0.872      | -            | -                | -                | -         |   -21.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1001 | 2024-06-15 | Spirit Academy  | W   | 0.871      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1032 | 2024-06-14 | Zero Tenacity   | L   | 0.865      | -            | -                | -                | -         |    -7.33 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1039 | 2024-06-14 | LEON            | W   | 0.864      | -            | -                | -                | 0 (0.000) |     6.39 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1181 | 2024-06-09 | Insilio         | L   | 0.831      | -            | -                | -                | -         |   -10.81 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1328 | 2024-06-07 | SINNERS         | L   | 0.817      | -            | -                | -                | -         |   -10.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1441 | 2024-06-05 | ARCRED          | L   | 0.804      | -            | -                | -                | -         |   -13.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1457 | 2024-06-05 | Rare Atom       | L   | 0.802      | -            | -                | -                | -         |   -20.29 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1506 | 2024-06-03 | Insilio         | W   | 0.792      | 0.372        | 0.023 (0.007)    | 0.561 (0.166)    | 0 (0.000) |    12.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1515 | 2024-06-03 | HAVU            | L   | 0.791      | -            | -                | -                | -         |   -19.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1549 | 2024-06-01 | Zero Tenacity   | W   | 0.779      | 0.372        | 0.137 (0.040)    | 1.000 (0.290)    | 0 (0.000) |    17.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1612 | 2024-05-30 | Portugal        | W   | 0.765      | -            | -                | -                | 0 (0.000) |     4.61 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1625 | 2024-05-30 | FURIA           | L   | 0.764      | -            | -                | -                | -         |    -0.61 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1669 | 2024-05-28 | MOUZ NXT        | L   | 0.751      | -            | -                | -                | -         |    -7.96 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1710 | 2024-05-26 | Zero Tenacity   | L   | 0.737      | -            | -                | -                | -         |    -6.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1720 | 2024-05-25 | B8              | L   | 0.732      | -            | -                | -                | -         |    -5.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1758 | 2024-05-23 | Nexus           | W   | 0.718      | 0.435        | 0.014 (0.004)    | 0.465 (0.145)    | 0 (0.000) |     6.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1851 | 2024-05-21 | Endpoint        | W   | 0.703      | 0.435        | -                | 0.522 (0.160)    | 0 (0.000) |    10.38 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2189 | 2024-05-11 | 9 Pandas        | L   | 0.638      | -            | -                | -                | -         |    -8.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2215 | 2024-05-10 | Nemiga          | W   | 0.629      | 0.435        | 0.318 (0.087)    | 0.695 (0.190)    | -         |    15.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2272 | 2024-05-07 | Insilio         | W   | 0.611      | 0.435        | 0.023 (0.006)    | 0.561 (0.149)    | -         |     9.68 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2315 | 2024-05-05 | HAVU            | W   | 0.597      | -            | -                | -                | -         |     4.22 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2345 | 2024-05-03 | V1dar           | W   | 0.584      | -            | -                | -                | -         |     1.89 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2402 | 2024-05-01 | GL Academy      | L   | 0.569      | -            | -                | -                | -         |   -13.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2444 | 2024-04-29 | Permitta        | L   | 0.556      | -            | -                | -                | -         |    -8.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2475 | 2024-04-27 | Astralis Talent | W   | 0.544      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2634 | 2024-04-20 | Zero Tenacity   | L   | 0.497      | -            | -                | -                | -         |    -5.30 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2714 | 2024-04-18 | Sashi           | L   | 0.485      | -            | -                | -                | -         |    -4.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2724 | 2024-04-18 | Aurora          | W   | 0.485      | 0.143        | 0.424 (0.029)    | -                | -         |    14.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2731 | 2024-04-18 | NOM             | W   | 0.484      | -            | -                | -                | -         |     1.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2784 | 2024-04-17 | JANO            | W   | 0.476      | -            | -                | -                | -         |     2.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3424 | 2024-03-19 | Sashi           | L   | 0.285      | -            | -                | -                | -         |    -2.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3481 | 2024-03-16 | Permitta        | W   | 0.265      | 0.372        | -                | 0.876 (0.086)    | -         |     4.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3617 | 2024-03-11 | Nexus           | L   | 0.232      | -            | -                | -                | -         |    -4.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3654 | 2024-03-09 | Spirit Academy  | W   | 0.218      | -            | -                | -                | -         |     0.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3680 | 2024-03-08 | ARCRED          | W   | 0.212      | -            | -                | -                | -         |     2.75 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3910 | 2024-02-27 | Spirit Academy  | L   | 0.145      | -            | -                | -                | -         |    -4.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3914 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.145      | -            | -                | -                | -         |     2.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4318 | 2024-02-09 | FORZE           | L   | 0.024      | -            | -                | -                | -         |    -0.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4329 | 2024-02-08 | AMKAL           | L   | 0.019      | -            | -                | -                | -         |    -0.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4332 | 2024-02-08 | ex-Guild Eagles | W   | 0.018      | -            | -                | -                | -         |     0.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,015.51)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $30,000.00     | $26,308.33      |
| 2024-06-10 |      0.839 | $3,300.00      | $2,767.88       |
| 2024-05-12 |      0.645 | $2,000.00      | $1,289.86       |
| 2024-03-25 |      0.325 | $2,000.00      | $649.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
