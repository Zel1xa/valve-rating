### Roster Details<br />
Team Name: Intense<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Global Rank: [121](../standings_global.md)<br />
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
- 400 + ( ( 0.172 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 751.8


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
|           25 |       74 | 2024-08-01 | Legacy         | L   | 1.000      | -            | -                | -                | -         |    -5.33 | ckzao, diozera, fREQ, keiz, mxa |
|           24 |       81 | 2024-08-01 | Fluxo          | L   | 1.000      | -            | -                | -                | -         |    -4.09 | ckzao, diozera, fREQ, keiz, mxa |
|           23 |      206 | 2024-07-29 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -7.97 | ckzao, diozera, fREQ, keiz, mxa |
|           22 |      245 | 2024-07-28 | Fluxo          | W   | 1.000      | 0.143        | 0.124 (0.018)    | 0.723 (0.103)    | 0 (0.000) |    27.04 | ckzao, diozera, fREQ, keiz, mxa |
|           21 |      408 | 2024-07-23 | Vikings KR     | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.505 (0.187)    | 0 (0.000) |    17.74 | ckzao, diozera, fREQ, keiz, mxa |
|           20 |      433 | 2024-07-22 | Case           | L   | 1.000      | -            | -                | -                | -         |   -10.81 | ckzao, diozera, fREQ, keiz, mxa |
|           19 |      483 | 2024-07-20 | inSanitY       | L   | 1.000      | -            | -                | -                | -         |    -6.50 | ckzao, diozera, fREQ, keiz, mxa |
|           18 |      525 | 2024-07-19 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |    -3.32 | ckzao, diozera, fREQ, keiz, mxa |
|           17 |      559 | 2024-07-18 | Bounty Hunters | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.557 (0.206)    | 0 (0.000) |    23.22 | ckzao, diozera, fREQ, keiz, mxa |
|           16 |      712 | 2024-07-16 | Galorys        | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.204)    | 0 (0.000) |    18.29 | ckzao, diozera, fREQ, keiz, mxa |
|           15 |      787 | 2024-07-13 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -6.78 | ckzao, diozera, fREQ, keiz, mxa |
|           14 |      802 | 2024-07-12 | paiN Academy   | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.47 | ckzao, diozera, fREQ, keiz, mxa |
|           13 |      874 | 2024-07-08 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |    -5.95 | ckzao, diozera, fREQ, keiz, mxa |
|           12 |     1316 | 2024-06-07 | RED Canids     | L   | 0.815      | -            | -                | -                | -         |    -2.35 | ckzao, diozera, fREQ, keiz, mxa |
|           11 |     1519 | 2024-06-03 | Galorys        | W   | 0.788      | 0.371        | 0.030 (0.009)    | 0.552 (0.161)    | 0 (0.000) |    16.71 | ckzao, diozera, fREQ, keiz, mxa |
|           10 |     1592 | 2024-05-31 | Bounty Hunters | W   | 0.770      | 0.371        | 0.022 (0.006)    | 0.557 (0.159)    | 0 (0.000) |    16.59 | ckzao, diozera, fREQ, keiz, mxa |
|            9 |     1634 | 2024-05-30 | inSanitY       | L   | 0.761      | -            | -                | -                | -         |    -5.75 | ckzao, diozera, fREQ, keiz, mxa |
|            8 |     1669 | 2024-05-28 | FURIA Academy  | W   | 0.750      | 0.371        | 0.000 (0.000)    | 0.105 (0.029)    | 0 (0.000) |     5.67 | ckzao, diozera, fREQ, keiz, mxa |
|            7 |     2143 | 2024-05-13 | Case           | L   | 0.648      | -            | -                | -                | -         |    -6.38 | bsd, ckzao, diozera, fREQ, mxa  |
|            6 |     2165 | 2024-05-12 | ODDIK          | L   | 0.642      | -            | -                | -                | -         |    -4.48 | bsd, ckzao, diozera, fREQ, mxa  |
|            5 |     2240 | 2024-05-09 | RED Canids     | L   | 0.622      | -            | -                | -                | -         |    -2.39 | bsd, ckzao, diozera, fREQ, mxa  |
|            4 |     2269 | 2024-05-08 | Yawara         | W   | 0.614      | 0.435        | 0.000 (0.000)    | 0.049 (0.013)    | 0 (0.000) |     4.16 | bsd, ckzao, diozera, fREQ, mxa  |
|            3 |     2304 | 2024-05-06 | RED Canids     | L   | 0.600      | -            | -                | -                | -         |    -2.29 | bsd, ckzao, diozera, fREQ, mxa  |
|            2 |     3565 | 2024-03-13 | Fluxo          | L   | 0.242      | -            | -                | -                | -         |    -1.19 | bsd, ckzao, diozera, mxa, roz   |
|            1 |     4237 | 2024-02-14 | Fluxo          | L   | 0.057      | -            | -                | -                | -         |    -0.29 | bsd, ckzao, diozera, mxa, roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($750.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
