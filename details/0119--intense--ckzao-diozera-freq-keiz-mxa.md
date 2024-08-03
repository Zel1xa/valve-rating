### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
<br />
Final Rank Value:  802.6<br />
<br />
Final Rank Value (802.6) = Starting Rank Value (750.6) + Head To Head Adjustments (52.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 750.6
- 400 + ( ( 0.171 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 750.6


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
|           25 |       49 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.03 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |       51 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.29 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      172 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -8.34 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      211 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.125 (0.018)    | 0.746 (0.107)    | 0 (0.000) |    26.78 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      372 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.479 (0.177)    | 0 (0.000) |    17.70 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      400 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.80 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      449 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.53 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      491 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -4.22 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      525 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.502 (0.186)    | 0 (0.000) |    23.11 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      676 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.571 (0.212)    | 0 (0.000) |    17.84 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      748 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -7.15 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      761 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.54 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      832 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.33 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1243 | 2024-06-07 | RED Canids     | L   | 0.820      | -            | -                | -                | -         |    -3.13 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1446 | 2024-06-03 | Galorys        | W   | 0.794      | 0.371        | 0.030 (0.009)    | 0.571 (0.168)    | 0 (0.000) |    16.90 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1517 | 2024-05-31 | Bounty Hunters | W   | 0.775      | 0.371        | 0.022 (0.006)    | 0.502 (0.144)    | 0 (0.000) |    16.72 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1559 | 2024-05-30 | inSanitY       | L   | 0.766      | -            | -                | -                | -         |    -5.87 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1594 | 2024-05-28 | FURIA Academy  | W   | 0.755      | 0.371        | 0.000 (0.000)    | 0.108 (0.030)    | 0 (0.000) |     5.77 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2066 | 2024-05-13 | Case           | L   | 0.654      | -            | -                | -                | -         |    -6.54 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2088 | 2024-05-12 | ODDIK          | L   | 0.647      | -            | -                | -                | -         |    -4.65 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2163 | 2024-05-09 | RED Canids     | L   | 0.628      | -            | -                | -                | -         |    -3.16 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2191 | 2024-05-08 | Yawara         | W   | 0.619      | 0.435        | 0.000 (0.000)    | 0.050 (0.014)    | 0 (0.000) |     4.24 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2226 | 2024-05-06 | RED Canids     | L   | 0.606      | -            | -                | -                | -         |    -3.08 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3480 | 2024-03-13 | Fluxo          | L   | 0.248      | -            | -                | -                | -         |    -1.22 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4149 | 2024-02-14 | Fluxo          | L   | 0.062      | -            | -                | -                | -         |    -0.32 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
