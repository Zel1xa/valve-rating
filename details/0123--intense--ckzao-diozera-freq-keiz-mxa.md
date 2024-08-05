### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [31]( ../standings_americas.md)<br />
<br />
Final Rank Value:  808.3<br />
<br />
Final Rank Value (808.3) = Starting Rank Value (751.9) + Head To Head Adjustments (56.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 751.9
- 400 + ( ( 0.172 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 751.9


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
|           25 |      121 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.36 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |      128 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.11 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      255 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -8.00 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      294 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.123 (0.018)    | 0.716 (0.102)    | 0 (0.000) |    27.01 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      455 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.500 (0.185)    | 0 (0.000) |    17.73 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      482 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.82 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      532 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.54 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      574 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.35 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      608 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.551 (0.204)    | 0 (0.000) |    23.18 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      761 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.543 (0.201)    | 0 (0.000) |    18.29 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      836 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.81 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      851 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.48 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      923 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -5.98 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1365 | 2024-06-07 | RED Canids     | L   | 0.807      | -            | -                | -                | -         |    -2.36 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1568 | 2024-06-03 | Galorys        | W   | 0.780      | 0.371        | 0.030 (0.009)    | 0.543 (0.157)    | 0 (0.000) |    16.54 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1641 | 2024-05-31 | Bounty Hunters | W   | 0.762      | 0.371        | 0.022 (0.006)    | 0.551 (0.156)    | 0 (0.000) |    16.39 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1683 | 2024-05-30 | inSanitY       | L   | 0.753      | -            | -                | -                | -         |    -5.74 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1718 | 2024-05-28 | FURIA Academy  | W   | 0.742      | 0.371        | 0.000 (0.000)    | 0.104 (0.029)    | 0 (0.000) |     5.60 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2192 | 2024-05-13 | Case           | L   | 0.641      | -            | -                | -                | -         |    -6.31 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2214 | 2024-05-12 | ODDIK          | L   | 0.634      | -            | -                | -                | -         |    -4.44 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2289 | 2024-05-09 | RED Canids     | L   | 0.614      | -            | -                | -                | -         |    -2.39 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2318 | 2024-05-08 | Yawara         | W   | 0.606      | 0.435        | 0.000 (0.000)    | 0.048 (0.013)    | 0 (0.000) |     4.10 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2353 | 2024-05-06 | RED Canids     | L   | 0.593      | -            | -                | -                | -         |    -2.29 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3614 | 2024-03-13 | Fluxo          | L   | 0.234      | -            | -                | -                | -         |    -1.16 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4286 | 2024-02-14 | Fluxo          | L   | 0.049      | -            | -                | -                | -         |    -0.25 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
