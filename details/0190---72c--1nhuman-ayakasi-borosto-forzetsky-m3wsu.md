### Roster Details<br />
Team Name: -72c<br />
Roster: 1nhuman, ayakasi, borosto, forzetsky, m3wsu<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  606.8<br />
<br />
Final Rank Value (606.8) = Starting Rank Value (625.4) + Head To Head Adjustments (-18.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.4
- 400 + ( ( 0.116 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 625.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      338 | 2024-08-28 | NomadS       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.069 (0.010)    | 0 (0.000) |    10.84 | 1nhuman, ayakasi, borosto, forzetsky, m3wsu     |
|           10 |      355 | 2024-08-28 | GR           | L   | 1.000      | -            | -                | -                | -         |   -14.79 | 1nhuman, ayakasi, borosto, forzetsky, m3wsu     |
|            9 |      480 | 2024-08-26 | NomadS       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.069 (0.010)    | 0 (0.000) |    11.34 | 1nhuman, ayakasi, borosto, forzetsky, m3wsu     |
|            8 |      488 | 2024-08-26 | THE          | L   | 1.000      | -            | -                | -                | -         |   -19.23 | 1nhuman, ayakasi, borosto, forzetsky, m3wsu     |
|            7 |      494 | 2024-08-25 | SUBUTAI      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |    10.40 | 1nhuman, ayakasi, borosto, forzetsky, m3wsu     |
|            6 |     1412 | 2024-07-29 | CatEvil      | L   | 0.926      | -            | -                | -                | -         |   -14.58 | 1nhuman, borosto, forzetsky, lkeyy, timeagento  |
|            5 |     1443 | 2024-07-28 | Steel Helmet | W   | 0.920      | 0.143        | 0.003 (0.000)    | 0.038 (0.005)    | 0 (0.000) |    10.66 | 1nhuman, borosto, forzetsky, lkeyy, timeagento  |
|            4 |     2652 | 2024-06-05 | The QUBE     | L   | 0.566      | -            | -                | -                | -         |    -8.16 | 1nhuman, aviva, borosto, forzetsky, youka       |
|            3 |     2692 | 2024-06-04 | ATOX         | L   | 0.560      | -            | -                | -                | -         |    -5.03 | 1nhuman, aviva, borosto, forzetsky, youka       |
|            2 |     4778 | 2024-03-13 | ATOX         | L   | 0.006      | -            | -                | -                | -         |    -0.06 | borosto, forzetsky, m3wsu, serrakura, shandarez |
|            1 |     4786 | 2024-03-13 | THE          | W   | 0.006      | 0.143        | 0.000 (0.000)    | 0.113 (0.000)    | 0 (0.000) |     0.06 | borosto, forzetsky, m3wsu, serrakura, shandarez |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($770.25)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
