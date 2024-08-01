### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  730.9<br />
<br />
Final Rank Value (730.9) = Starting Rank Value (611.1) + Head To Head Adjustments (119.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.103[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 611.1
- 400 + ( ( 0.103 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 611.1


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
|           23 |      116 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -5.61 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      155 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.122 (0.017)    | 0.702 (0.100)    | 0 (0.000) |    28.54 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      316 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.459 (0.170)    | 0 (0.000) |    21.18 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      344 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |    -7.36 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      396 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -4.19 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      439 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -2.27 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      476 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.512 (0.190)    | 0 (0.000) |    26.20 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      633 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.568 (0.210)    | 0 (0.000) |    22.54 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      714 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -4.14 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      729 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.92 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      801 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -3.46 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1243 | 2024-06-07 | RED Canids     | L   | 0.833      | -            | -                | -                | -         |    -1.72 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1451 | 2024-06-03 | Galorys        | W   | 0.807      | 0.371        | 0.030 (0.009)    | 0.568 (0.170)    | 0 (0.000) |    20.48 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1525 | 2024-05-31 | Bounty Hunters | W   | 0.788      | 0.371        | 0.022 (0.006)    | 0.512 (0.149)    | 0 (0.000) |    20.10 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1567 | 2024-05-30 | inSanitY       | L   | 0.779      | -            | -                | -                | -         |    -3.63 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1602 | 2024-05-28 | FURIA Academy  | W   | 0.768      | 0.371        | 0.000 (0.000)    | 0.104 (0.030)    | 0 (0.000) |     9.54 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2111 | 2024-05-13 | Case           | L   | 0.667      | -            | -                | -                | -         |    -3.77 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2135 | 2024-05-12 | ODDIK          | L   | 0.660      | -            | -                | -                | -         |    -2.28 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2210 | 2024-05-09 | RED Canids     | L   | 0.641      | -            | -                | -                | -         |    -1.47 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2241 | 2024-05-08 | Yawara         | W   | 0.632      | 0.435        | 0.000 (0.000)    | 0.049 (0.013)    | 0 (0.000) |     7.43 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2276 | 2024-05-06 | RED Canids     | L   | 0.619      | -            | -                | -                | -         |    -1.38 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3569 | 2024-03-13 | Fluxo          | L   | 0.261      | -            | -                | -                | -         |    -0.63 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4257 | 2024-02-14 | Fluxo          | L   | 0.075      | -            | -                | -                | -         |    -0.20 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
