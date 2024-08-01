### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  570.4<br />
<br />
Final Rank Value (570.4) = Starting Rank Value (550.1) + Head To Head Adjustments (20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.274[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.073<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 550.1
- 400 + ( ( 0.073 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 550.1


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
|           16 |     3509 | 2024-03-15 | MOUZ NXT        | L   | 0.273      | -            | -                | -                | -         |    -0.53 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           15 |     3549 | 2024-03-14 | ex-Preasy       | L   | 0.266      | -            | -                | -                | -         |    -1.74 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           14 |     3640 | 2024-03-11 | ECLOT           | W   | 0.246      | 0.371        | 0.064 (0.006)    | 0.501 (0.046)    | 0 (0.000) |     7.39 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3656 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.240      | 0.371        | 0.032 (0.003)    | 0.564 (0.050)    | 0 (0.000) |     6.94 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3687 | 2024-03-09 | Alliance        | L   | 0.233      | -            | -                | -                | -         |    -1.17 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3703 | 2024-03-08 | Passion UA      | L   | 0.227      | -            | -                | -                | -         |    -0.34 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3808 | 2024-03-05 | 500             | L   | 0.206      | -            | -                | -                | -         |    -1.75 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3825 | 2024-03-04 | Sashi           | W   | 0.199      | 0.371        | 0.187 (0.014)    | 0.971 (0.072)    | 0 (0.000) |     6.07 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3956 | 2024-02-26 | 9INE            | W   | 0.154      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.08 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3979 | 2024-02-25 | Secret          | W   | 0.147      | 0.358        | 0.000 (0.000)    | 0.060 (0.003)    | 0 (0.000) |     2.25 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     4033 | 2024-02-23 | Sampi           | L   | 0.133      | -            | -                | -                | -         |    -0.54 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     4088 | 2024-02-21 | MOUZ NXT        | L   | 0.119      | -            | -                | -                | -         |    -0.20 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4168 | 2024-02-17 | The Chosen Few  | W   | 0.095      | 0.358        | 0.001 (0.000)    | 0.046 (0.002)    | 0 (0.000) |     2.00 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4327 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.055      | -            | -                | -                | -         |    -0.13 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4401 | 2024-02-05 | Sashi           | L   | 0.013      | -            | -                | -                | -         |    -0.01 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4446 | 2024-02-03 | Sangal          | W   | 0.001      | 0.358        | 0.221 (0.000)    | 0.823 (0.000)    | 0 (0.000) |     0.02 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
