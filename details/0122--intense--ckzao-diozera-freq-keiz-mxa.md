### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  808.3<br />
<br />
Final Rank Value (808.3) = Starting Rank Value (752.1) + Head To Head Adjustments (56.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 752.1
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 752.1


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
|           25 |      128 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.38 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |      135 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.12 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      262 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -8.01 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      301 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.123 (0.018)    | 0.716 (0.102)    | 0 (0.000) |    26.99 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      462 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.501 (0.186)    | 0 (0.000) |    17.72 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      489 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.82 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      539 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.56 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      581 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.37 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      615 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.552 (0.205)    | 0 (0.000) |    23.17 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      768 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.542 (0.201)    | 0 (0.000) |    18.30 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      843 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.82 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      858 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.48 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      930 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.00 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1372 | 2024-06-07 | RED Canids     | L   | 0.802      | -            | -                | -                | -         |    -2.37 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1575 | 2024-06-03 | Galorys        | W   | 0.775      | 0.371        | 0.030 (0.009)    | 0.542 (0.156)    | 0 (0.000) |    16.44 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1648 | 2024-05-31 | Bounty Hunters | W   | 0.757      | 0.371        | 0.022 (0.006)    | 0.552 (0.155)    | 0 (0.000) |    16.29 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1690 | 2024-05-30 | inSanitY       | L   | 0.748      | -            | -                | -                | -         |    -5.72 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1725 | 2024-05-28 | FURIA Academy  | W   | 0.737      | 0.371        | 0.000 (0.000)    | 0.104 (0.028)    | 0 (0.000) |     5.56 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2199 | 2024-05-13 | Case           | L   | 0.636      | -            | -                | -                | -         |    -6.27 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2221 | 2024-05-12 | ODDIK          | L   | 0.629      | -            | -                | -                | -         |    -4.42 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2296 | 2024-05-09 | RED Canids     | L   | 0.609      | -            | -                | -                | -         |    -2.38 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2325 | 2024-05-08 | Yawara         | W   | 0.601      | 0.435        | 0.000 (0.000)    | 0.048 (0.013)    | 0 (0.000) |     4.06 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2360 | 2024-05-06 | RED Canids     | L   | 0.588      | -            | -                | -                | -         |    -2.29 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3621 | 2024-03-13 | Fluxo          | L   | 0.230      | -            | -                | -                | -         |    -1.14 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4293 | 2024-02-14 | Fluxo          | L   | 0.044      | -            | -                | -                | -         |    -0.23 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
