### Roster Details<br />
Team Name: V1dar<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Global Rank: [195](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
<br />
Final Rank Value:  543.5<br />
<br />
Final Rank Value (543.5) = Starting Rank Value (521.5) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.5
- 400 + ( ( 0.059 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 521.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1558 | 2024-06-01 | Verdant          | L   | 0.776      | -            | -                | -                | -         |    -2.91 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           11 |     1625 | 2024-05-30 | 1WIN             | L   | 0.761      | -            | -                | -                | -         |    -1.80 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           10 |     1647 | 2024-05-29 | Grannys Knockers | W   | 0.756      | 0.372        | 0.004 (0.001)    | 0.130 (0.037)    | 0 (0.000) |    18.96 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            9 |     2190 | 2024-05-11 | Verdant          | L   | 0.635      | -            | -                | -                | -         |    -1.90 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            8 |     2349 | 2024-05-03 | RUBY             | L   | 0.581      | -            | -                | -                | -         |    -1.88 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            7 |     2392 | 2024-05-01 | B8               | L   | 0.568      | -            | -                | -                | -         |    -0.99 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            6 |     2422 | 2024-04-30 | MOUZ NXT         | L   | 0.561      | -            | -                | -                | -         |    -1.01 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            5 |     2489 | 2024-04-27 | Viperio          | W   | 0.541      | 0.143        | 0.001 (0.000)    | 0.037 (0.003)    | 0 (0.000) |    10.76 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            4 |     3639 | 2024-03-10 | MOUZ NXT         | L   | 0.222      | -            | -                | -                | -         |    -0.37 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     3749 | 2024-03-06 | Endpoint         | L   | 0.195      | -            | -                | -                | -         |    -0.71 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     3913 | 2024-02-27 | FORZE            | L   | 0.142      | -            | -                | -                | -         |    -0.52 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     3917 | 2024-02-27 | Sashi            | W   | 0.142      | 0.143        | 0.184 (0.004)    | 0.962 (0.020)    | 0 (0.000) |     4.34 | 1mpala, 4X1s, Alv, lom1k, torox |

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
