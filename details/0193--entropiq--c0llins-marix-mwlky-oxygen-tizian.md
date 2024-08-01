### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  569.8<br />
<br />
Final Rank Value (569.8) = Starting Rank Value (549.7) + Head To Head Adjustments (20.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.073<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 549.7
- 400 + ( ( 0.073 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 549.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     3515 | 2024-03-15 | MOUZ NXT        | L   | 0.272      | -            | -                | -                | -         |    -0.53 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           14 |     3555 | 2024-03-14 | ex-Preasy       | L   | 0.264      | -            | -                | -                | -         |    -1.74 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3646 | 2024-03-11 | ECLOT           | W   | 0.244      | 0.371        | 0.064 (0.006)    | 0.501 (0.045)    | 0 (0.000) |     7.34 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3662 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.239      | 0.371        | 0.032 (0.003)    | 0.563 (0.050)    | 0 (0.000) |     6.89 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3693 | 2024-03-09 | Alliance        | L   | 0.231      | -            | -                | -                | -         |    -1.16 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3709 | 2024-03-08 | Passion UA      | L   | 0.225      | -            | -                | -                | -         |    -0.34 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3814 | 2024-03-05 | 500             | L   | 0.205      | -            | -                | -                | -         |    -1.74 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3831 | 2024-03-04 | Sashi           | W   | 0.198      | 0.371        | 0.186 (0.014)    | 0.970 (0.071)    | 0 (0.000) |     6.01 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3962 | 2024-02-26 | 9INE            | W   | 0.152      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.06 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     3985 | 2024-02-25 | Secret          | W   | 0.145      | 0.358        | 0.000 (0.000)    | 0.060 (0.003)    | 0 (0.000) |     2.22 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     4039 | 2024-02-23 | Sampi           | L   | 0.131      | -            | -                | -                | -         |    -0.53 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4094 | 2024-02-21 | MOUZ NXT        | L   | 0.117      | -            | -                | -                | -         |    -0.20 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4174 | 2024-02-17 | The Chosen Few  | W   | 0.094      | 0.358        | 0.001 (0.000)    | 0.046 (0.002)    | 0 (0.000) |     1.97 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4333 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.053      | -            | -                | -                | -         |    -0.13 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4407 | 2024-02-05 | Sashi           | L   | 0.011      | -            | -                | -                | -         |    -0.01 | c0llins, Marix, mwlky, oxygeN, tiziaN |

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
