### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [1](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [1]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1973.4<br />
<br />
Final Rank Value (1973.4) = Starting Rank Value (1991.1) + Head To Head Adjustments (-17.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.768[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.772<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1991.1
- 400 + ( ( 0.772 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1991.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       13 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.55 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |      331 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.492 (0.492)    | 1 (1.000) |    15.58 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      364 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.379 (0.379)    | 1 (1.000) |    13.62 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      394 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.663 (0.663)    | 0.410 (0.410)    | 1 (1.000) |     7.98 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      533 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.495 (0.495)    | 1 (1.000) |     4.14 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      851 | 2024-06-16 | Spirit       | L   | 0.898      | -            | -                | -                | -         |   -13.99 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      872 | 2024-06-15 | Virtus.pro   | W   | 0.893      | 0.729        | 0.494 (0.321)    | 0.327 (0.213)    | 1 (0.893) |     5.56 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      962 | 2024-06-13 | FaZe         | W   | 0.878      | 0.729        | 0.663 (0.424)    | 0.410 (0.262)    | 1 (0.878) |     7.62 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      991 | 2024-06-12 | Astralis     | W   | 0.871      | 0.729        | -                | 0.386 (0.245)    | 1 (0.871) |     6.08 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1533 | 2024-05-29 | HEROIC       | L   | 0.779      | -            | -                | -                | -         |   -21.60 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1554 | 2024-05-28 | Spirit       | L   | 0.772      | -            | -                | -                | -         |   -13.45 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1572 | 2024-05-27 | BIG          | W   | 0.767      | -            | -                | -                | 1 (0.767) |     0.43 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     2138 | 2024-05-08 | FaZe         | L   | 0.639      | -            | -                | -                | -         |   -15.30 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     2188 | 2024-05-05 | Complexity   | L   | 0.619      | -            | -                | -                | -         |   -16.84 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     2262 | 2024-05-02 | BIG          | W   | 0.598      | -            | -                | -                | 1 (0.598) |     0.26 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2285 | 2024-05-01 | FlyQuest     | W   | 0.591      | -            | -                | -                | -         |     0.22 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     3116 | 2024-03-31 | FaZe         | W   | 0.386      | -            | -                | -                | -         |     2.41 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     3121 | 2024-03-30 | G2           | W   | 0.380      | 1.000        | 1.000 (0.380)    | 0.492 (0.187)    | -         |     6.08 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     3131 | 2024-03-29 | Eternal Fire | W   | 0.372      | 1.000        | 0.752 (0.280)    | -                | -         |     2.39 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3224 | 2024-03-24 | paiN         | W   | 0.339      | 1.000        | -                | 0.797 (0.270)    | -         |     0.51 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3233 | 2024-03-23 | Cloud9       | L   | 0.333      | -            | -                | -                | -         |   -10.42 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3249 | 2024-03-22 | Spirit       | L   | 0.326      | -            | -                | -                | -         |    -6.22 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3265 | 2024-03-21 | G2           | W   | 0.320      | 1.000        | 1.000 (0.320)    | -                | -         |     5.13 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3282 | 2024-03-21 | The MongolZ  | W   | 0.318      | 1.000        | 1.000 (0.318)    | 0.719 (0.228)    | -         |     4.38 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     4062 | 2024-02-16 | BetBoom      | W   | 0.092      | -            | -                | -                | -         |     0.13 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     4091 | 2024-02-15 | Virtus.pro   | L   | 0.085      | -            | -                | -                | -         |    -2.17 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     4122 | 2024-02-14 | Enterprise   | W   | 0.080      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4140 | 2024-02-14 | KOI          | W   | 0.078      | -            | -                | -                | -         |     0.02 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4236 | 2024-02-06 | Falcons      | L   | 0.025      | -            | -                | -                | -         |    -0.76 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4244 | 2024-02-05 | Eternal Fire | W   | 0.020      | -            | -                | -                | -         |     0.11 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4264 | 2024-02-04 | Apeks        | W   | 0.012      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4294 | 2024-02-03 | Spirit       | L   | 0.006      | -            | -                | -                | -         |    -0.10 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($702,923.92)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.898 | $85,000.00     | $76,349.28      |
| 2024-06-02 |      0.806 | $5,000.00      | $4,030.02       |
| 2024-05-12 |      0.665 | $23,500.00     | $15,631.53      |
| 2024-03-31 |      0.386 | $500,000.00    | $193,002.31     |
| 2024-02-11 |      0.059 | $24,000.00     | $1,410.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
