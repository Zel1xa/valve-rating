### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  880.2<br />
<br />
Final Rank Value (880.2) = Starting Rank Value (925.3) + Head To Head Adjustments (-45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.3
- 400 + ( ( 0.256 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 925.3


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
|           48 |       46 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.52 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      389 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.26 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      469 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | -                | 0.233 (0.101)    | 0 (0.000) |    12.29 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      564 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.89 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      716 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.393 (0.171)    | 0 (0.000) |    14.58 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      762 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.25 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1032 | 2024-06-16 | ARCRED          | W   | 0.863      | 0.450        | 0.041 (0.016)    | 0.378 (0.147)    | 0 (0.000) |    16.78 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1052 | 2024-06-15 | System5         | L   | 0.858      | -            | -                | -                | -         |   -20.95 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1065 | 2024-06-15 | Spirit Academy  | W   | 0.857      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     7.92 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1096 | 2024-06-14 | Zero Tenacity   | L   | 0.851      | -            | -                | -                | -         |    -7.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1103 | 2024-06-14 | LEON            | W   | 0.850      | -            | -                | -                | 0 (0.000) |     6.24 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1245 | 2024-06-09 | Insilio         | L   | 0.818      | -            | -                | -                | -         |   -10.64 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1392 | 2024-06-07 | SINNERS         | L   | 0.803      | -            | -                | -                | -         |    -9.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1505 | 2024-06-05 | ARCRED          | L   | 0.790      | -            | -                | -                | -         |   -11.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1521 | 2024-06-05 | Rare Atom       | L   | 0.789      | -            | -                | -                | -         |   -16.34 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1570 | 2024-06-03 | Insilio         | W   | 0.778      | 0.372        | 0.023 (0.007)    | 0.552 (0.160)    | 0 (0.000) |    12.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1579 | 2024-06-03 | HAVU            | L   | 0.777      | -            | -                | -                | -         |   -19.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1613 | 2024-06-01 | Zero Tenacity   | W   | 0.765      | 0.372        | 0.143 (0.041)    | 1.000 (0.285)    | 0 (0.000) |    17.51 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1676 | 2024-05-30 | Portugal        | W   | 0.752      | -            | -                | -                | 0 (0.000) |     4.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1689 | 2024-05-30 | FURIA           | L   | 0.750      | -            | -                | -                | -         |    -0.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1733 | 2024-05-28 | MOUZ NXT        | L   | 0.737      | -            | -                | -                | -         |    -7.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1774 | 2024-05-26 | Zero Tenacity   | L   | 0.723      | -            | -                | -                | -         |    -6.59 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1784 | 2024-05-25 | B8              | L   | 0.718      | -            | -                | -                | -         |    -5.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1822 | 2024-05-23 | Nexus           | W   | 0.704      | 0.435        | 0.014 (0.004)    | 0.457 (0.140)    | 0 (0.000) |     6.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1915 | 2024-05-21 | Endpoint        | W   | 0.689      | 0.435        | 0.012 (0.004)    | 0.514 (0.154)    | 0 (0.000) |    10.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2253 | 2024-05-11 | 9 Pandas        | L   | 0.624      | -            | -                | -                | -         |    -8.15 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2279 | 2024-05-10 | Nemiga          | W   | 0.616      | 0.435        | 0.315 (0.084)    | 0.721 (0.193)    | -         |    15.30 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2336 | 2024-05-07 | Insilio         | W   | 0.598      | 0.435        | 0.023 (0.006)    | 0.552 (0.143)    | -         |     9.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2379 | 2024-05-05 | HAVU            | W   | 0.583      | -            | -                | -                | -         |     4.18 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2409 | 2024-05-03 | V1dar           | W   | 0.570      | -            | -                | -                | -         |     1.86 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2466 | 2024-05-01 | GL Academy      | L   | 0.556      | -            | -                | -                | -         |   -12.69 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2508 | 2024-04-29 | Permitta        | L   | 0.542      | -            | -                | -                | -         |    -7.98 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2539 | 2024-04-27 | Astralis Talent | W   | 0.531      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2699 | 2024-04-20 | Zero Tenacity   | L   | 0.484      | -            | -                | -                | -         |    -4.96 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2779 | 2024-04-18 | Sashi           | L   | 0.471      | -            | -                | -                | -         |    -3.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2789 | 2024-04-18 | Aurora          | W   | 0.471      | 0.143        | 0.421 (0.028)    | -                | -         |    14.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2796 | 2024-04-18 | NOM             | W   | 0.470      | -            | -                | -                | -         |     1.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2849 | 2024-04-17 | JANO            | W   | 0.462      | -            | -                | -                | -         |     2.96 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3489 | 2024-03-19 | Sashi           | L   | 0.271      | -            | -                | -                | -         |    -2.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3546 | 2024-03-16 | Permitta        | W   | 0.251      | 0.372        | -                | 0.901 (0.084)    | -         |     4.54 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3683 | 2024-03-11 | Nexus           | L   | 0.218      | -            | -                | -                | -         |    -4.29 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3720 | 2024-03-09 | Spirit Academy  | W   | 0.204      | -            | -                | -                | -         |     0.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3746 | 2024-03-08 | ARCRED          | W   | 0.198      | -            | -                | -                | -         |     3.02 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3976 | 2024-02-27 | Spirit Academy  | L   | 0.131      | -            | -                | -                | -         |    -3.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3980 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.131      | -            | -                | -                | -         |     2.40 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4385 | 2024-02-09 | FORZE           | L   | 0.010      | -            | -                | -                | -         |    -0.18 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4396 | 2024-02-08 | AMKAL           | L   | 0.005      | -            | -                | -                | -         |    -0.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4399 | 2024-02-08 | ex-Guild Eagles | W   | 0.004      | -            | -                | -                | -         |     0.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,497.46)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $30,000.00     | $25,891.67      |
| 2024-06-10 |      0.825 | $3,300.00      | $2,722.04       |
| 2024-05-12 |      0.631 | $2,000.00      | $1,262.08       |
| 2024-03-25 |      0.311 | $2,000.00      | $621.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
