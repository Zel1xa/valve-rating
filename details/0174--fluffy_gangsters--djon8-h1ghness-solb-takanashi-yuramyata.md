### Roster Details<br />
Team Name: FLuffy Gangsters<br />
Roster: Djon8, h1ghnesS, SoLb, takanashi, yuramyata<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
<br />
Final Rank Value:  666.1<br />
<br />
Final Rank Value (666.1) = Starting Rank Value (567.3) + Head To Head Adjustments (98.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 567.3
- 400 + ( ( 0.081 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 567.3


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
|           14 |      358 | 2024-07-22 | 9INE              | L   | 1.000      | -            | -                | -                | -         |    -4.56 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           13 |      374 | 2024-07-21 | Grannys Knockers  | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.129 (0.018)    | 0 (0.000) |    20.82 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           12 |      410 | 2024-07-20 | GenOne            | L   | 1.000      | -            | -                | -                | -         |   -21.52 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           11 |      454 | 2024-07-19 | ADEPTS            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    14.66 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|           10 |      732 | 2024-07-12 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -1.44 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            9 |      814 | 2024-07-08 | TSM               | W   | 1.000      | 0.358        | 0.039 (0.014)    | 0.347 (0.124)    | 0 (0.000) |    27.26 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            8 |      816 | 2024-07-08 | Insilio           | W   | 1.000      | 0.358        | 0.023 (0.008)    | 0.554 (0.198)    | 0 (0.000) |    27.82 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            7 |      900 | 2024-06-16 | WOPA              | L   | 0.892      | -            | -                | -                | -         |   -13.24 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            6 |      931 | 2024-06-15 | TÓR               | W   | 0.886      | 0.143        | 0.025 (0.003)    | 0.117 (0.015)    | 0 (0.000) |    23.46 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            5 |      964 | 2024-06-14 | CPH Wolves        | L   | 0.879      | -            | -                | -                | -         |    -6.65 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            4 |     1011 | 2024-06-13 | TÓR               | W   | 0.871      | 0.143        | 0.025 (0.003)    | 0.117 (0.015)    | 0 (0.000) |    23.79 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            3 |     1452 | 2024-06-03 | Aurora Young Blud | L   | 0.806      | -            | -                | -                | -         |    -4.85 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            2 |     1496 | 2024-06-01 | Portugal          | W   | 0.793      | 0.372        | 0.003 (0.001)    | 0.122 (0.036)    | 0 (0.000) |    16.20 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |
|            1 |     1587 | 2024-05-29 | Enterprise        | L   | 0.773      | -            | -                | -                | -         |    -3.00 | Djon8, h1ghnesS, SoLb, takanashi, yuramyata |

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
