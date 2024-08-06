### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  807.5<br />
<br />
Final Rank Value (807.5) = Starting Rank Value (751.7) + Head To Head Adjustments (55.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 751.7
- 400 + ( ( 0.171 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 751.7


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
|           25 |      132 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.38 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |      139 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.14 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      266 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -8.03 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      305 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.123 (0.018)    | 0.701 (0.100)    | 0 (0.000) |    26.98 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      466 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.490 (0.182)    | 0 (0.000) |    17.70 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      493 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.84 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      543 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.58 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      585 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.38 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      619 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.540 (0.200)    | 0 (0.000) |    23.15 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      772 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.530 (0.196)    | 0 (0.000) |    18.27 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      847 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.85 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      862 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.49 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      934 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.02 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1376 | 2024-06-07 | RED Canids     | L   | 0.802      | -            | -                | -                | -         |    -2.37 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1579 | 2024-06-03 | Galorys        | W   | 0.775      | 0.371        | 0.030 (0.009)    | 0.530 (0.152)    | 0 (0.000) |    16.41 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1652 | 2024-05-31 | Bounty Hunters | W   | 0.757      | 0.371        | 0.022 (0.006)    | 0.540 (0.151)    | 0 (0.000) |    16.25 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1694 | 2024-05-30 | inSanitY       | L   | 0.748      | -            | -                | -                | -         |    -5.74 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1729 | 2024-05-28 | FURIA Academy  | W   | 0.737      | 0.371        | 0.000 (0.000)    | 0.102 (0.028)    | 0 (0.000) |     5.57 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2203 | 2024-05-13 | Case           | L   | 0.636      | -            | -                | -                | -         |    -6.29 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2225 | 2024-05-12 | ODDIK          | L   | 0.629      | -            | -                | -                | -         |    -4.43 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2300 | 2024-05-09 | RED Canids     | L   | 0.609      | -            | -                | -                | -         |    -2.39 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2329 | 2024-05-08 | Yawara         | W   | 0.601      | 0.435        | 0.000 (0.000)    | 0.047 (0.012)    | 0 (0.000) |     4.07 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2364 | 2024-05-06 | RED Canids     | L   | 0.588      | -            | -                | -                | -         |    -2.30 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3625 | 2024-03-13 | Fluxo          | L   | 0.229      | -            | -                | -                | -         |    -1.15 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4297 | 2024-02-14 | Fluxo          | L   | 0.044      | -            | -                | -                | -         |    -0.23 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
