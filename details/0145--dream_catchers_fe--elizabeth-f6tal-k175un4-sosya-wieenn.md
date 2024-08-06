### Roster Details<br />
Team Name: dream catchers fe<br />
Roster: Elizabeth, f6tal, k175un4, sosya, wieenN<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [95]( ../standings_europe.md)<br />
<br />
Final Rank Value:  744.6<br />
<br />
Final Rank Value (744.6) = Starting Rank Value (717.5) + Head To Head Adjustments (27.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.357[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 717.5
- 400 + ( ( 0.155 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 717.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      518 | 2024-07-21 | France fe   | W   | 1.000      | 0.294        | 0.006 (0.002)    | 0.117 (0.035)    | 0 (0.000) |    13.43 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|           10 |      523 | 2024-07-21 | Spirit fe   | W   | 1.000      | 0.294        | 0.005 (0.001)    | 0.139 (0.041)    | 0 (0.000) |    11.64 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            9 |      557 | 2024-07-20 | BIG EQUIPA  | W   | 1.000      | 0.294        | 0.017 (0.005)    | 0.146 (0.043)    | 0 (0.000) |    18.14 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            8 |      833 | 2024-07-14 | CENSORED fe | L   | 1.000      | -            | -                | -                | -         |   -15.96 | Elizabeth, f6tal, k175un4, t4tty, wieenN |
|            7 |      963 | 2024-06-30 | YeYO        | W   | 0.958      | 0.250        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.65 | Elizabeth, f6tal, k175un4, sosya, wieenN |
|            6 |     1024 | 2024-06-16 | NIP Impact  | L   | 0.864      | -            | -                | -                | -         |   -13.40 | k175un4, sosya, Stormy, unknxwn, wieenN  |
|            5 |     2902 | 2024-04-14 | Spirit fe   | W   | 0.444      | 0.250        | 0.005 (0.001)    | 0.139 (0.015)    | 0 (0.000) |     5.67 | k175un4, sosya, Stormy, trigusha, wieenN |
|            4 |     3113 | 2024-04-07 | ENCE Athena | W   | 0.398      | 0.250        | 0.002 (0.000)    | 0.034 (0.003)    | 0 (0.000) |     4.88 | k175un4, sosya, Stormy, trigusha, wieenN |
|            3 |     3880 | 2024-03-03 | BIG EQUIPA  | L   | 0.165      | -            | -                | -                | -         |    -2.20 | k175un4, sosya, Stormy, trigusha, wieenN |
|            2 |     4182 | 2024-02-18 | Astralis W  | L   | 0.072      | -            | -                | -                | -         |    -1.43 | k175un4, mikeri, sosya, Stormy, wieenN   |
|            1 |     4186 | 2024-02-18 | Crescent fe | L   | 0.071      | -            | -                | -                | -         |    -1.29 | k175un4, mikeri, sosya, Stormy, wieenN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,107.00)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-07-14 |      1.000 | $500.00        | $500.00         |
| 2024-06-30 |      0.958 | $750.00        | $718.32         |
| 2024-06-16 |      0.864 | $250.00        | $216.05         |
| 2024-04-14 |      0.444 | $750.00        | $332.71         |
| 2024-04-07 |      0.398 | $750.00        | $298.70         |
| 2024-03-03 |      0.165 | $250.00        | $41.23          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
