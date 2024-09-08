### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [132](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
<br />
Final Rank Value:  745.0<br />
<br />
Final Rank Value (745.0) = Starting Rank Value (708.9) + Head To Head Adjustments (36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.9
- 400 + ( ( 0.160 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 708.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      425 | 2024-08-26 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -4.95 | ckzao, diozera, fREQ, keiz, mxa |
|           25 |      447 | 2024-08-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |    -7.57 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |     1260 | 2024-08-01 | Legacy         | L   | 0.950      | -            | -                | -                | -         |    -6.11 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |     1267 | 2024-08-01 | Fluxo          | L   | 0.949      | -            | -                | -                | -         |    -3.83 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |     1394 | 2024-07-29 | BESTIA         | L   | 0.929      | -            | -                | -                | -         |    -7.17 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |     1433 | 2024-07-28 | Fluxo          | W   | 0.921      | 0.143        | 0.122 (0.016)    | 0.649 (0.085)    | 0 (0.000) |    25.00 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |     1594 | 2024-07-23 | Vikings KR     | W   | 0.888      | 0.371        | 0.006 (0.002)    | 0.439 (0.144)    | 0 (0.000) |    15.79 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |     1621 | 2024-07-22 | Case           | L   | 0.881      | -            | -                | -                | -         |    -8.38 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |     1671 | 2024-07-20 | inSanitY       | L   | 0.869      | -            | -                | -                | -         |    -6.07 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |     1713 | 2024-07-19 | RED Canids     | L   | 0.861      | -            | -                | -                | -         |    -3.65 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |     1747 | 2024-07-18 | Bounty Hunters | W   | 0.856      | 0.371        | 0.026 (0.008)    | 0.440 (0.140)    | 0 (0.000) |    19.40 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |     1902 | 2024-07-16 | Galorys        | W   | 0.840      | 0.371        | 0.019 (0.006)    | 0.372 (0.116)    | 0 (0.000) |    15.64 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |     1978 | 2024-07-13 | BESTIA         | L   | 0.822      | -            | -                | -                | -         |    -5.42 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |     1993 | 2024-07-12 | paiN Academy   | W   | 0.814      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.55 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     2065 | 2024-07-08 | BESTIA         | L   | 0.788      | -            | -                | -                | -         |    -4.70 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     2507 | 2024-06-07 | RED Canids     | L   | 0.581      | -            | -                | -                | -         |    -2.37 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     2710 | 2024-06-03 | Galorys        | W   | 0.555      | 0.371        | 0.019 (0.004)    | 0.372 (0.076)    | 0 (0.000) |    11.33 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     2783 | 2024-05-31 | Bounty Hunters | W   | 0.536      | 0.371        | 0.026 (0.005)    | 0.440 (0.087)    | 0 (0.000) |    11.20 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     2825 | 2024-05-30 | inSanitY       | L   | 0.527      | -            | -                | -                | -         |    -4.32 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2860 | 2024-05-28 | FURIA Academy  | W   | 0.516      | 0.371        | 0.000 (0.000)    | 0.079 (0.015)    | 0 (0.000) |     4.37 | ckzao, diozera, fREQ, keiz, mxa |
|            6 |     3334 | 2024-05-13 | Case           | L   | 0.415      | -            | -                | -                | -         |    -2.98 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     3356 | 2024-05-12 | ODDIK          | L   | 0.408      | -            | -                | -                | -         |    -1.33 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     3431 | 2024-05-09 | RED Canids     | L   | 0.389      | -            | -                | -                | -         |    -2.08 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     3460 | 2024-05-08 | Yawara         | W   | 0.380      | 0.435        | 0.000 (0.000)    | 0.033 (0.005)    | 0 (0.000) |     2.83 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3495 | 2024-05-06 | RED Canids     | L   | 0.367      | -            | -                | -                | -         |    -2.01 | bsd, ckzao, diozera, fREQ, mxa  |
|            1 |     4756 | 2024-03-13 | Fluxo          | L   | 0.009      | -            | -                | -                | -         |    -0.14 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($716.94)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
