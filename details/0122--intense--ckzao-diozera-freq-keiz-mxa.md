### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  808.8<br />
<br />
Final Rank Value (808.8) = Starting Rank Value (751.8) + Head To Head Adjustments (57.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 751.8
- 400 + ( ( 0.172 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 751.8


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
|           25 |       96 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.33 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |      103 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      230 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -7.97 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      269 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.124 (0.018)    | 0.724 (0.103)    | 0 (0.000) |    27.04 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      430 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.506 (0.187)    | 0 (0.000) |    17.74 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      457 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.81 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      507 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.50 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      549 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.33 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      583 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.557 (0.206)    | 0 (0.000) |    23.22 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      736 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.204)    | 0 (0.000) |    18.30 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      811 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.78 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      826 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.47 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      898 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -5.95 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1340 | 2024-06-07 | RED Canids     | L   | 0.814      | -            | -                | -                | -         |    -2.35 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1543 | 2024-06-03 | Galorys        | W   | 0.787      | 0.371        | 0.030 (0.009)    | 0.552 (0.161)    | 0 (0.000) |    16.69 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1616 | 2024-05-31 | Bounty Hunters | W   | 0.769      | 0.371        | 0.022 (0.006)    | 0.557 (0.159)    | 0 (0.000) |    16.56 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1658 | 2024-05-30 | inSanitY       | L   | 0.759      | -            | -                | -                | -         |    -5.75 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1693 | 2024-05-28 | FURIA Academy  | W   | 0.749      | 0.371        | 0.000 (0.000)    | 0.105 (0.029)    | 0 (0.000) |     5.66 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2167 | 2024-05-13 | Case           | L   | 0.647      | -            | -                | -                | -         |    -6.37 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2189 | 2024-05-12 | ODDIK          | L   | 0.641      | -            | -                | -                | -         |    -4.47 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2264 | 2024-05-09 | RED Canids     | L   | 0.621      | -            | -                | -                | -         |    -2.39 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2293 | 2024-05-08 | Yawara         | W   | 0.613      | 0.435        | 0.000 (0.000)    | 0.049 (0.013)    | 0 (0.000) |     4.15 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2328 | 2024-05-06 | RED Canids     | L   | 0.599      | -            | -                | -                | -         |    -2.29 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3589 | 2024-03-13 | Fluxo          | L   | 0.241      | -            | -                | -                | -         |    -1.18 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4261 | 2024-02-14 | Fluxo          | L   | 0.055      | -            | -                | -                | -         |    -0.28 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
