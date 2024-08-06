### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [91](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  885.4<br />
<br />
Final Rank Value (885.4) = Starting Rank Value (932.1) + Head To Head Adjustments (-46.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.1
- 400 + ( ( 0.259 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 932.1


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
|           48 |       55 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.62 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      395 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.31 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      475 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | 0.036 (0.016)    | 0.472 (0.205)    | 0 (0.000) |    17.35 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      570 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.87 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      722 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.383 (0.166)    | 0 (0.000) |    14.64 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      768 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.25 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1038 | 2024-06-16 | ARCRED          | W   | 0.860      | 0.450        | 0.041 (0.016)    | 0.369 (0.143)    | 0 (0.000) |    16.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1058 | 2024-06-15 | System5         | L   | 0.854      | -            | -                | -                | -         |   -20.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1071 | 2024-06-15 | Spirit Academy  | W   | 0.854      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     7.93 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1102 | 2024-06-14 | Zero Tenacity   | L   | 0.848      | -            | -                | -                | -         |    -7.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1109 | 2024-06-14 | LEON            | W   | 0.847      | -            | -                | -                | 0 (0.000) |     6.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1251 | 2024-06-09 | Insilio         | L   | 0.814      | -            | -                | -                | -         |   -10.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1398 | 2024-06-07 | SINNERS         | L   | 0.799      | -            | -                | -                | -         |    -9.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1511 | 2024-06-05 | ARCRED          | L   | 0.787      | -            | -                | -                | -         |   -11.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1527 | 2024-06-05 | Rare Atom       | L   | 0.785      | -            | -                | -                | -         |   -20.84 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1576 | 2024-06-03 | Insilio         | W   | 0.775      | 0.372        | 0.023 (0.007)    | 0.539 (0.156)    | 0 (0.000) |    12.22 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1585 | 2024-06-03 | HAVU            | L   | 0.774      | -            | -                | -                | -         |   -19.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1619 | 2024-06-01 | Zero Tenacity   | W   | 0.762      | 0.372        | 0.143 (0.041)    | 1.000 (0.284)    | 0 (0.000) |    17.39 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1682 | 2024-05-30 | Portugal        | W   | 0.748      | -            | -                | -                | 0 (0.000) |     4.44 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1695 | 2024-05-30 | FURIA           | L   | 0.746      | -            | -                | -                | -         |    -0.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1739 | 2024-05-28 | MOUZ NXT        | L   | 0.734      | -            | -                | -                | -         |    -7.77 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1780 | 2024-05-26 | Zero Tenacity   | L   | 0.720      | -            | -                | -                | -         |    -6.58 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1790 | 2024-05-25 | B8              | L   | 0.715      | -            | -                | -                | -         |    -5.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1828 | 2024-05-23 | Nexus           | W   | 0.700      | 0.435        | 0.014 (0.004)    | 0.447 (0.136)    | 0 (0.000) |     6.47 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1921 | 2024-05-21 | Endpoint        | W   | 0.685      | 0.435        | -                | 0.502 (0.149)    | 0 (0.000) |    10.14 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2259 | 2024-05-11 | 9 Pandas        | L   | 0.620      | -            | -                | -                | -         |    -8.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2285 | 2024-05-10 | Nemiga          | W   | 0.612      | 0.435        | 0.314 (0.084)    | 0.704 (0.187)    | -         |    15.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2342 | 2024-05-07 | Insilio         | W   | 0.594      | 0.435        | 0.023 (0.006)    | 0.539 (0.139)    | -         |     9.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2385 | 2024-05-05 | HAVU            | W   | 0.580      | -            | -                | -                | -         |     4.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2415 | 2024-05-03 | V1dar           | W   | 0.566      | -            | -                | -                | -         |     1.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2472 | 2024-05-01 | GL Academy      | L   | 0.552      | -            | -                | -                | -         |   -12.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2514 | 2024-04-29 | Permitta        | L   | 0.539      | -            | -                | -                | -         |    -8.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2545 | 2024-04-27 | Astralis Talent | W   | 0.527      | -            | -                | -                | -         |     0.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2705 | 2024-04-20 | Zero Tenacity   | L   | 0.480      | -            | -                | -                | -         |    -5.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2785 | 2024-04-18 | Sashi           | L   | 0.468      | -            | -                | -                | -         |    -4.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2795 | 2024-04-18 | Aurora          | W   | 0.467      | 0.143        | 0.420 (0.028)    | -                | -         |    14.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2802 | 2024-04-18 | NOM             | W   | 0.467      | -            | -                | -                | -         |     1.56 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2855 | 2024-04-17 | JANO            | W   | 0.459      | -            | -                | -                | -         |     2.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3495 | 2024-03-19 | Sashi           | L   | 0.268      | -            | -                | -                | -         |    -2.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3552 | 2024-03-16 | Permitta        | W   | 0.247      | 0.372        | -                | 0.919 (0.085)    | -         |     4.41 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3689 | 2024-03-11 | Nexus           | L   | 0.214      | -            | -                | -                | -         |    -4.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3726 | 2024-03-09 | Spirit Academy  | W   | 0.201      | -            | -                | -                | -         |     0.67 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3752 | 2024-03-08 | ARCRED          | W   | 0.194      | -            | -                | -                | -         |     2.91 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3982 | 2024-02-27 | Spirit Academy  | L   | 0.128      | -            | -                | -                | -         |    -3.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3986 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.128      | -            | -                | -                | -         |     2.30 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4391 | 2024-02-09 | FORZE           | L   | 0.007      | -            | -                | -                | -         |    -0.13 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4402 | 2024-02-08 | AMKAL           | L   | 0.001      | -            | -                | -                | -         |    -0.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4405 | 2024-02-08 | ex-Guild Eagles | W   | 0.000      | -            | -                | -                | -         |     0.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,369.67)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.860 | $30,000.00     | $25,788.89      |
| 2024-06-10 |      0.821 | $3,300.00      | $2,710.74       |
| 2024-05-12 |      0.628 | $2,000.00      | $1,255.23       |
| 2024-03-25 |      0.307 | $2,000.00      | $614.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
