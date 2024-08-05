### Roster Details<br />
Team Name: FLuffy Gangsters<br />
Roster: Djon8, h1ghnesS, SoLb, takanashi, yuramyata<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
<br />
Final Rank Value:  665.8<br />
<br />
Final Rank Value (665.8) = Starting Rank Value (567.6) + Head To Head Adjustments (98.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 567.6
- 400 + ( ( 0.081 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 567.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      322 | 2024-07-22 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -5.08 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           13 |      337 | 2024-07-21 | Grannys Knockers  | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.129 (0.018)    | 0 (0.000) |    20.88 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           12 |      372 | 2024-07-20 | GenOne            | L   | 1.000      | -            | -                | -                | -         |   -21.52 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           11 |      414 | 2024-07-19 | ADEPTS            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    14.68 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           10 |      680 | 2024-07-12 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -1.40 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            9 |      762 | 2024-07-08 | TSM               | W   | 1.000      | 0.358        | 0.039 (0.014)    | 0.345 (0.124)    | 0 (0.000) |    27.25 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            8 |      764 | 2024-07-08 | Insilio           | W   | 1.000      | 0.358        | 0.023 (0.008)    | 0.554 (0.198)    | 0 (0.000) |    27.86 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            7 |      850 | 2024-06-16 | WOPA              | L   | 0.899      | -            | -                | -                | -         |   -13.31 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            6 |      884 | 2024-06-15 | TÓR               | W   | 0.892      | 0.143        | 0.025 (0.003)    | 0.117 (0.015)    | 0 (0.000) |    23.65 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            5 |      924 | 2024-06-14 | CPH Wolves        | L   | 0.885      | -            | -                | -                | -         |    -6.69 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            4 |      970 | 2024-06-13 | TÓR               | W   | 0.877      | 0.143        | 0.025 (0.003)    | 0.117 (0.015)    | 0 (0.000) |    23.98 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            3 |     1395 | 2024-06-03 | Aurora Young Blud | L   | 0.812      | -            | -                | -                | -         |    -5.49 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            2 |     1438 | 2024-06-01 | Portugal          | W   | 0.799      | 0.372        | 0.003 (0.001)    | 0.122 (0.036)    | 0 (0.000) |    16.35 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            1 |     1529 | 2024-05-29 | Enterprise        | L   | 0.779      | -            | -                | -                | -         |    -2.93 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
