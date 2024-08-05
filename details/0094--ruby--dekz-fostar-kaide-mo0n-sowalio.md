### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  880.3<br />
<br />
Final Rank Value (880.3) = Starting Rank Value (925.5) + Head To Head Adjustments (-45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.158[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.5
- 400 + ( ( 0.256 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 925.5


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
|           48 |       44 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.53 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      387 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.26 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      467 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | -                | 0.233 (0.101)    | 0 (0.000) |    12.29 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      562 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.89 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      714 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.393 (0.171)    | 0 (0.000) |    14.58 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      760 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.24 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1030 | 2024-06-16 | ARCRED          | W   | 0.865      | 0.450        | 0.041 (0.016)    | 0.378 (0.147)    | 0 (0.000) |    16.82 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1050 | 2024-06-15 | System5         | L   | 0.860      | -            | -                | -                | -         |   -21.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1063 | 2024-06-15 | Spirit Academy  | W   | 0.859      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     7.94 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1094 | 2024-06-14 | Zero Tenacity   | L   | 0.853      | -            | -                | -                | -         |    -7.28 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1101 | 2024-06-14 | LEON            | W   | 0.852      | -            | -                | -                | 0 (0.000) |     6.25 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1243 | 2024-06-09 | Insilio         | L   | 0.819      | -            | -                | -                | -         |   -10.66 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1390 | 2024-06-07 | SINNERS         | L   | 0.805      | -            | -                | -                | -         |    -9.13 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1503 | 2024-06-05 | ARCRED          | L   | 0.792      | -            | -                | -                | -         |   -11.66 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1519 | 2024-06-05 | Rare Atom       | L   | 0.790      | -            | -                | -                | -         |   -16.39 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1568 | 2024-06-03 | Insilio         | W   | 0.780      | 0.372        | 0.023 (0.007)    | 0.552 (0.160)    | 0 (0.000) |    12.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1577 | 2024-06-03 | HAVU            | L   | 0.779      | -            | -                | -                | -         |   -19.23 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1611 | 2024-06-01 | Zero Tenacity   | W   | 0.767      | 0.372        | 0.143 (0.041)    | 1.000 (0.285)    | 0 (0.000) |    17.55 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1674 | 2024-05-30 | Portugal        | W   | 0.753      | -            | -                | -                | 0 (0.000) |     4.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1687 | 2024-05-30 | FURIA           | L   | 0.752      | -            | -                | -                | -         |    -0.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1731 | 2024-05-28 | MOUZ NXT        | L   | 0.739      | -            | -                | -                | -         |    -7.61 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1772 | 2024-05-26 | Zero Tenacity   | L   | 0.725      | -            | -                | -                | -         |    -6.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1782 | 2024-05-25 | B8              | L   | 0.720      | -            | -                | -                | -         |    -5.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1820 | 2024-05-23 | Nexus           | W   | 0.706      | 0.435        | 0.014 (0.004)    | 0.458 (0.140)    | 0 (0.000) |     6.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1913 | 2024-05-21 | Endpoint        | W   | 0.691      | 0.435        | 0.012 (0.004)    | 0.514 (0.154)    | 0 (0.000) |    10.37 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2251 | 2024-05-11 | 9 Pandas        | L   | 0.626      | -            | -                | -                | -         |    -8.16 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2277 | 2024-05-10 | Nemiga          | W   | 0.617      | 0.435        | 0.316 (0.085)    | 0.722 (0.194)    | -         |    15.35 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2334 | 2024-05-07 | Insilio         | W   | 0.599      | 0.435        | 0.023 (0.006)    | 0.552 (0.144)    | -         |     9.67 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2377 | 2024-05-05 | HAVU            | W   | 0.585      | -            | -                | -                | -         |     4.20 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2407 | 2024-05-03 | V1dar           | W   | 0.572      | -            | -                | -                | -         |     1.87 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2464 | 2024-05-01 | GL Academy      | L   | 0.557      | -            | -                | -                | -         |   -12.73 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2506 | 2024-04-29 | Permitta        | L   | 0.544      | -            | -                | -                | -         |    -8.01 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2537 | 2024-04-27 | Astralis Talent | W   | 0.532      | -            | -                | -                | -         |     0.79 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2697 | 2024-04-20 | Zero Tenacity   | L   | 0.485      | -            | -                | -                | -         |    -4.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2777 | 2024-04-18 | Sashi           | L   | 0.473      | -            | -                | -                | -         |    -3.99 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2787 | 2024-04-18 | Aurora          | W   | 0.473      | 0.143        | 0.422 (0.028)    | -                | -         |    14.61 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2794 | 2024-04-18 | NOM             | W   | 0.472      | -            | -                | -                | -         |     1.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2847 | 2024-04-17 | JANO            | W   | 0.464      | -            | -                | -                | -         |     2.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3487 | 2024-03-19 | Sashi           | L   | 0.273      | -            | -                | -                | -         |    -2.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3544 | 2024-03-16 | Permitta        | W   | 0.252      | 0.372        | -                | 0.902 (0.085)    | -         |     4.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3681 | 2024-03-11 | Nexus           | L   | 0.220      | -            | -                | -                | -         |    -4.33 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3718 | 2024-03-09 | Spirit Academy  | W   | 0.206      | -            | -                | -                | -         |     0.72 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3744 | 2024-03-08 | ARCRED          | W   | 0.200      | -            | -                | -                | -         |     3.04 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3974 | 2024-02-27 | Spirit Academy  | L   | 0.133      | -            | -                | -                | -         |    -3.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3978 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.133      | -            | -                | -                | -         |     2.43 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4383 | 2024-02-09 | FORZE           | L   | 0.012      | -            | -                | -                | -         |    -0.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4394 | 2024-02-08 | AMKAL           | L   | 0.007      | -            | -                | -                | -         |    -0.05 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4397 | 2024-02-08 | ex-Guild Eagles | W   | 0.006      | -            | -                | -                | -         |     0.06 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,564.81)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.865 | $30,000.00     | $25,945.83      |
| 2024-06-10 |      0.827 | $3,300.00      | $2,728.00       |
| 2024-05-12 |      0.633 | $2,000.00      | $1,265.69       |
| 2024-03-25 |      0.313 | $2,000.00      | $625.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
