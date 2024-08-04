### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  565.3<br />
<br />
Final Rank Value (565.3) = Starting Rank Value (546.8) + Head To Head Adjustments (18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 546.8
- 400 + ( ( 0.072 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 546.8


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
|           14 |     3503 | 2024-03-15 | MOUZ NXT        | L   | 0.257      | -            | -                | -                | -         |    -0.54 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3539 | 2024-03-14 | ex-Preasy       | L   | 0.249      | -            | -                | -                | -         |    -1.67 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3628 | 2024-03-11 | ECLOT           | W   | 0.229      | 0.371        | 0.063 (0.005)    | 0.559 (0.047)    | 0 (0.000) |     7.04 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3644 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.224      | 0.371        | 0.032 (0.003)    | 0.561 (0.047)    | 0 (0.000) |     6.47 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3674 | 2024-03-09 | Alliance        | L   | 0.217      | -            | -                | -                | -         |    -1.08 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3690 | 2024-03-08 | Passion UA      | L   | 0.210      | -            | -                | -                | -         |    -0.33 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3790 | 2024-03-05 | 500             | L   | 0.190      | -            | -                | -                | -         |    -1.77 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3807 | 2024-03-04 | Sashi           | W   | 0.183      | 0.371        | 0.184 (0.012)    | 0.964 (0.065)    | 0 (0.000) |     5.56 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     3936 | 2024-02-26 | 9INE            | W   | 0.137      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.88 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     3957 | 2024-02-25 | Secret          | W   | 0.131      | 0.358        | 0.000 (0.000)    | 0.059 (0.003)    | 0 (0.000) |     2.00 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4007 | 2024-02-23 | Sampi           | L   | 0.116      | -            | -                | -                | -         |    -0.48 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4060 | 2024-02-21 | MOUZ NXT        | L   | 0.103      | -            | -                | -                | -         |    -0.19 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4140 | 2024-02-17 | The Chosen Few  | W   | 0.079      | 0.358        | 0.001 (0.000)    | 0.043 (0.001)    | 0 (0.000) |     1.66 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4289 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.039      | -            | -                | -                | -         |    -0.10 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
