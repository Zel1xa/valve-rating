### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  564.6<br />
<br />
Final Rank Value (564.6) = Starting Rank Value (546.5) + Head To Head Adjustments (18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 546.5
- 400 + ( ( 0.072 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 546.5


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
|           14 |     3508 | 2024-03-15 | MOUZ NXT        | L   | 0.254      | -            | -                | -                | -         |    -0.53 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3544 | 2024-03-14 | ex-Preasy       | L   | 0.246      | -            | -                | -                | -         |    -1.66 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3634 | 2024-03-11 | ECLOT           | W   | 0.226      | 0.371        | 0.062 (0.005)    | 0.559 (0.047)    | 0 (0.000) |     6.95 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3650 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.221      | 0.371        | 0.031 (0.003)    | 0.560 (0.046)    | 0 (0.000) |     6.38 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3680 | 2024-03-09 | Alliance        | L   | 0.214      | -            | -                | -                | -         |    -1.06 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3696 | 2024-03-08 | Passion UA      | L   | 0.207      | -            | -                | -                | -         |    -0.32 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3796 | 2024-03-05 | 500             | L   | 0.187      | -            | -                | -                | -         |    -1.75 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3813 | 2024-03-04 | Sashi           | W   | 0.180      | 0.371        | 0.184 (0.012)    | 0.962 (0.064)    | 0 (0.000) |     5.47 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     3942 | 2024-02-26 | 9INE            | W   | 0.134      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.84 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     3963 | 2024-02-25 | Secret          | W   | 0.128      | 0.358        | 0.000 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     1.96 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     4013 | 2024-02-23 | Sampi           | L   | 0.113      | -            | -                | -                | -         |    -0.47 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     4066 | 2024-02-21 | MOUZ NXT        | L   | 0.100      | -            | -                | -                | -         |    -0.19 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4147 | 2024-02-17 | The Chosen Few  | W   | 0.076      | 0.358        | 0.001 (0.000)    | 0.042 (0.001)    | 0 (0.000) |     1.59 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4296 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.036      | -            | -                | -                | -         |    -0.09 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
