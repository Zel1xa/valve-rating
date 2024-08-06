### Roster Details<br />
Team Name: V1dar<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Global Rank: [195](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
<br />
Final Rank Value:  542.8<br />
<br />
Final Rank Value (542.8) = Starting Rank Value (521.1) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.1
- 400 + ( ( 0.059 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 521.1


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
|           12 |     1626 | 2024-06-01 | Verdant          | L   | 0.762      | -            | -                | -                | -         |    -2.81 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           11 |     1693 | 2024-05-30 | 1WIN             | L   | 0.748      | -            | -                | -                | -         |    -1.52 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           10 |     1715 | 2024-05-29 | Grannys Knockers | W   | 0.742      | 0.372        | 0.004 (0.001)    | 0.125 (0.035)    | 0 (0.000) |    18.66 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            9 |     2258 | 2024-05-11 | Verdant          | L   | 0.622      | -            | -                | -                | -         |    -1.83 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            8 |     2417 | 2024-05-03 | RUBY             | L   | 0.567      | -            | -                | -                | -         |    -1.81 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            7 |     2460 | 2024-05-01 | B8               | L   | 0.554      | -            | -                | -                | -         |    -0.94 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            6 |     2490 | 2024-04-30 | MOUZ NXT         | L   | 0.547      | -            | -                | -                | -         |    -0.96 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            5 |     2557 | 2024-04-27 | Viperio          | W   | 0.527      | 0.143        | 0.001 (0.000)    | 0.036 (0.003)    | 0 (0.000) |    10.53 | 1mpala, 4X1s, Alv, torox, xm1nd |
|            4 |     3707 | 2024-03-10 | MOUZ NXT         | L   | 0.209      | -            | -                | -                | -         |    -0.34 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     3817 | 2024-03-06 | Endpoint         | L   | 0.181      | -            | -                | -                | -         |    -0.66 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     3981 | 2024-02-27 | FORZE            | L   | 0.129      | -            | -                | -                | -         |    -0.47 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     3985 | 2024-02-27 | Sashi            | W   | 0.128      | 0.143        | 0.184 (0.003)    | 0.958 (0.018)    | 0 (0.000) |     3.93 | 1mpala, 4X1s, Alv, lom1k, torox |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />