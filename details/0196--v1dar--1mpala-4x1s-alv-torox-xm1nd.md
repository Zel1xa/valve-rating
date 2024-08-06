### Roster Details<br />
Team Name: V1dar<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
<br />
Final Rank Value:  542.8<br />
<br />
Final Rank Value (542.8) = Starting Rank Value (521.0) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.0
- 400 + ( ( 0.059 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 521.0


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
|           12 |     1635 | 2024-06-01 | Verdant          | L   | 0.761      | -            | -                | -                | -         |    -2.80 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           11 |     1702 | 2024-05-30 | 1WIN             | L   | 0.747      | -            | -                | -                | -         |    -1.51 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           10 |     1724 | 2024-05-29 | Grannys Knockers | W   | 0.741      | 0.372        | 0.004 (0.001)    | 0.125 (0.035)    | 0 (0.000) |    18.63 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            9 |     2267 | 2024-05-11 | Verdant          | L   | 0.621      | -            | -                | -                | -         |    -1.82 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            8 |     2426 | 2024-05-03 | RUBY             | L   | 0.566      | -            | -                | -                | -         |    -1.78 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            7 |     2469 | 2024-05-01 | B8               | L   | 0.553      | -            | -                | -                | -         |    -0.94 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            6 |     2499 | 2024-04-30 | MOUZ NXT         | L   | 0.546      | -            | -                | -                | -         |    -0.96 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            5 |     2566 | 2024-04-27 | Viperio          | W   | 0.526      | 0.143        | 0.001 (0.000)    | 0.035 (0.003)    | 0 (0.000) |    10.51 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            4 |     3716 | 2024-03-10 | MOUZ NXT         | L   | 0.208      | -            | -                | -                | -         |    -0.34 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     3826 | 2024-03-06 | Endpoint         | L   | 0.180      | -            | -                | -                | -         |    -0.65 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     3990 | 2024-02-27 | FORZE            | L   | 0.128      | -            | -                | -                | -         |    -0.47 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     3994 | 2024-02-27 | Sashi            | W   | 0.127      | 0.143        | 0.184 (0.003)    | 0.958 (0.017)    | 0 (0.000) |     3.90 | 1mpala, 4X1s, Alv, lom1k, torox |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
