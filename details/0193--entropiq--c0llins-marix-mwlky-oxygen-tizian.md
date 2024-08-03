### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, oxygeN, tiziaN<br />
Global Rank: [193](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  566.1<br />
<br />
Final Rank Value (566.1) = Starting Rank Value (547.5) + Head To Head Adjustments (18.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 547.5
- 400 + ( ( 0.072 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 547.5


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
|           14 |     3431 | 2024-03-15 | MOUZ NXT        | L   | 0.259      | -            | -                | -                | -         |    -0.56 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           13 |     3467 | 2024-03-14 | ex-Preasy       | L   | 0.251      | -            | -                | -                | -         |    -1.69 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           12 |     3555 | 2024-03-11 | ECLOT           | W   | 0.231      | 0.371        | 0.063 (0.005)    | 0.578 (0.049)    | 0 (0.000) |     7.10 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           11 |     3571 | 2024-03-10 | ALTERNATE aTTaX | W   | 0.226      | 0.371        | 0.032 (0.003)    | 0.580 (0.049)    | 0 (0.000) |     6.52 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|           10 |     3601 | 2024-03-09 | Alliance        | L   | 0.218      | -            | -                | -                | -         |    -1.08 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            9 |     3617 | 2024-03-08 | Passion UA      | L   | 0.212      | -            | -                | -                | -         |    -0.33 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            8 |     3717 | 2024-03-05 | 500             | L   | 0.192      | -            | -                | -                | -         |    -1.79 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            7 |     3734 | 2024-03-04 | Sashi           | W   | 0.184      | 0.371        | 0.184 (0.013)    | 0.998 (0.068)    | 0 (0.000) |     5.61 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            6 |     3863 | 2024-02-26 | 9INE            | W   | 0.139      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.90 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            5 |     3884 | 2024-02-25 | Secret          | W   | 0.132      | 0.358        | 0.000 (0.000)    | 0.061 (0.003)    | 0 (0.000) |     2.03 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            4 |     3934 | 2024-02-23 | Sampi           | L   | 0.118      | -            | -                | -                | -         |    -0.48 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            3 |     3987 | 2024-02-21 | MOUZ NXT        | L   | 0.104      | -            | -                | -                | -         |    -0.20 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            2 |     4067 | 2024-02-17 | The Chosen Few  | W   | 0.081      | 0.358        | 0.001 (0.000)    | 0.045 (0.001)    | 0 (0.000) |     1.69 | c0llins, Marix, mwlky, oxygeN, tiziaN |
|            1 |     4216 | 2024-02-11 | ALTERNATE aTTaX | L   | 0.040      | -            | -                | -                | -         |    -0.10 | c0llins, Marix, mwlky, oxygeN, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
