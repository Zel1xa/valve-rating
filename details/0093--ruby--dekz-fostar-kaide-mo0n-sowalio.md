### Roster Details<br />
Team Name: RUBY<br />
Roster: dekz, fostar, Kaide, mo0N, sowalio<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  874.5<br />
<br />
Final Rank Value (874.5) = Starting Rank Value (924.9) + Head To Head Adjustments (-50.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.495[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.159[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 924.9
- 400 + ( ( 0.257 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 924.9


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
|           48 |       22 | 2024-08-04 | Project G       | L   | 1.000      | -            | -                | -                | -         |   -27.42 | dekz, fostar, Kaide, mo0N, sowalio |
|           47 |      365 | 2024-07-25 | 9z              | L   | 1.000      | -            | -                | -                | -         |    -1.21 | dekz, fostar, Kaide, mo0N, sowalio |
|           46 |      445 | 2024-07-23 | Metizport       | W   | 1.000      | 0.435        | -                | 0.236 (0.102)    | 0 (0.000) |    12.37 | dekz, fostar, Kaide, mo0N, sowalio |
|           45 |      540 | 2024-07-20 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |    -8.78 | dekz, fostar, Kaide, mo0N, sowalio |
|           44 |      692 | 2024-07-17 | VP.Prodigy      | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.400 (0.174)    | 0 (0.000) |    14.72 | dekz, fostar, Kaide, mo0N, sowalio |
|           43 |      738 | 2024-07-16 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -15.14 | dekz, fostar, Kaide, mo0N, sowalio |
|           42 |     1008 | 2024-06-16 | ARCRED          | W   | 0.870      | 0.450        | 0.041 (0.016)    | 0.344 (0.135)    | 0 (0.000) |    15.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           41 |     1028 | 2024-06-15 | System5         | L   | 0.864      | -            | -                | -                | -         |   -20.97 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           40 |     1041 | 2024-06-15 | Spirit Academy  | W   | 0.864      | 0.450        | 0.013 (0.005)    | -                | 0 (0.000) |     8.12 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           39 |     1072 | 2024-06-14 | Zero Tenacity   | L   | 0.858      | -            | -                | -                | -         |    -7.19 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           38 |     1079 | 2024-06-14 | LEON            | W   | 0.857      | -            | -                | -                | 0 (0.000) |     6.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           37 |     1221 | 2024-06-09 | Insilio         | L   | 0.824      | -            | -                | -                | -         |   -10.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           36 |     1368 | 2024-06-07 | SINNERS         | L   | 0.809      | -            | -                | -                | -         |    -9.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           35 |     1481 | 2024-06-05 | ARCRED          | L   | 0.797      | -            | -                | -                | -         |   -12.90 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           34 |     1497 | 2024-06-05 | Rare Atom       | L   | 0.795      | -            | -                | -                | -         |   -20.07 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           33 |     1546 | 2024-06-03 | Insilio         | W   | 0.785      | 0.372        | 0.023 (0.007)    | 0.561 (0.164)    | 0 (0.000) |    12.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           32 |     1555 | 2024-06-03 | HAVU            | L   | 0.784      | -            | -                | -                | -         |   -19.32 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           31 |     1589 | 2024-06-01 | Zero Tenacity   | W   | 0.772      | 0.372        | 0.137 (0.039)    | 1.000 (0.287)    | 0 (0.000) |    17.67 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           30 |     1652 | 2024-05-30 | Portugal        | W   | 0.758      | -            | -                | -                | 0 (0.000) |     4.63 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           29 |     1665 | 2024-05-30 | FURIA           | L   | 0.756      | -            | -                | -                | -         |    -0.57 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           28 |     1709 | 2024-05-28 | MOUZ NXT        | L   | 0.744      | -            | -                | -                | -         |    -7.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           27 |     1750 | 2024-05-26 | Zero Tenacity   | L   | 0.730      | -            | -                | -                | -         |    -6.62 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           26 |     1760 | 2024-05-25 | B8              | L   | 0.725      | -            | -                | -                | -         |    -5.10 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           25 |     1798 | 2024-05-23 | Nexus           | W   | 0.711      | 0.435        | 0.014 (0.004)    | 0.465 (0.144)    | 0 (0.000) |     6.60 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           24 |     1891 | 2024-05-21 | Endpoint        | W   | 0.696      | 0.435        | 0.012 (0.004)    | 0.522 (0.158)    | 0 (0.000) |    10.45 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           23 |     2229 | 2024-05-11 | 9 Pandas        | L   | 0.631      | -            | -                | -                | -         |    -8.21 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           22 |     2255 | 2024-05-10 | Nemiga          | W   | 0.622      | 0.435        | 0.317 (0.086)    | 0.733 (0.198)    | -         |    15.49 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           21 |     2312 | 2024-05-07 | Insilio         | W   | 0.604      | 0.435        | 0.023 (0.006)    | 0.561 (0.147)    | -         |     9.70 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           20 |     2355 | 2024-05-05 | HAVU            | W   | 0.590      | -            | -                | -                | -         |     4.26 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           19 |     2385 | 2024-05-03 | V1dar           | W   | 0.576      | -            | -                | -                | -         |     1.90 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           18 |     2442 | 2024-05-01 | GL Academy      | L   | 0.562      | -            | -                | -                | -         |   -12.81 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           17 |     2484 | 2024-04-29 | Permitta        | L   | 0.549      | -            | -                | -                | -         |    -8.31 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           16 |     2515 | 2024-04-27 | Astralis Talent | W   | 0.537      | -            | -                | -                | -         |     0.80 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           15 |     2675 | 2024-04-20 | Zero Tenacity   | L   | 0.490      | -            | -                | -                | -         |    -5.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           14 |     2755 | 2024-04-18 | Sashi           | L   | 0.478      | -            | -                | -                | -         |    -4.03 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           13 |     2765 | 2024-04-18 | Aurora          | W   | 0.477      | 0.143        | 0.423 (0.029)    | -                | -         |    14.76 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           12 |     2772 | 2024-04-18 | NOM             | W   | 0.477      | -            | -                | -                | -         |     1.65 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           11 |     2825 | 2024-04-17 | JANO            | W   | 0.469      | -            | -                | -                | -         |     3.00 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|           10 |     3465 | 2024-03-19 | Sashi           | L   | 0.278      | -            | -                | -                | -         |    -2.10 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            9 |     3522 | 2024-03-16 | Permitta        | W   | 0.257      | 0.372        | -                | 0.876 (0.084)    | -         |     4.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            8 |     3659 | 2024-03-11 | Nexus           | L   | 0.224      | -            | -                | -                | -         |    -4.42 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            7 |     3696 | 2024-03-09 | Spirit Academy  | W   | 0.211      | -            | -                | -                | -         |     0.74 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            6 |     3722 | 2024-03-08 | ARCRED          | W   | 0.204      | -            | -                | -                | -         |     2.71 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            5 |     3952 | 2024-02-27 | Spirit Academy  | L   | 0.138      | -            | -                | -                | -         |    -3.90 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            4 |     3956 | 2024-02-27 | ALTERNATE aTTaX | W   | 0.138      | -            | -                | -                | -         |     2.52 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            3 |     4361 | 2024-02-09 | FORZE           | L   | 0.017      | -            | -                | -                | -         |    -0.30 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            2 |     4372 | 2024-02-08 | AMKAL           | L   | 0.012      | -            | -                | -                | -         |    -0.08 | dekz, Kaide, mo0N, sowalio, w1nt3r |
|            1 |     4375 | 2024-02-08 | ex-Guild Eagles | W   | 0.010      | -            | -                | -                | -         |     0.11 | dekz, Kaide, mo0N, sowalio, w1nt3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,746.13)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $30,000.00     | $26,091.67      |
| 2024-06-10 |      0.832 | $3,300.00      | $2,744.04       |
| 2024-05-12 |      0.638 | $2,000.00      | $1,275.42       |
| 2024-03-25 |      0.318 | $2,000.00      | $635.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
