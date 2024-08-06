### Roster Details<br />
Team Name: ex-Sprout<br />
Roster: cej0t, podi, raalz, reiko, Sdaim<br />
Global Rank: [205](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
<br />
Final Rank Value:  499.0<br />
<br />
Final Rank Value (499.0) = Starting Rank Value (501.2) + Head To Head Adjustments (-2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.049<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 501.2
- 400 + ( ( 0.049 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 501.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3340 | 2024-03-28 | Rebels          | L   | 0.327      | -            | -                | -                | -         |    -0.61 | cej0t, podi, raalz, reiko, Sdaim     |
|            9 |     3414 | 2024-03-25 | ALTERNATE aTTaX | L   | 0.307      | -            | -                | -                | -         |    -0.62 | cej0t, podi, raalz, reiko, Sdaim     |
|            8 |     3443 | 2024-03-22 | Aurora          | L   | 0.287      | -            | -                | -                | -         |    -0.01 | cej0t, podi, raalz, reiko, Sdaim     |
|            7 |     3515 | 2024-03-19 | B8              | L   | 0.266      | -            | -                | -                | -         |    -0.30 | cej0t, podi, raalz, reiko, Sdaim     |
|            6 |     3801 | 2024-03-07 | Alliance        | L   | 0.186      | -            | -                | -                | -         |    -0.72 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            5 |     3865 | 2024-03-05 | KOI             | L   | 0.174      | -            | -                | -                | -         |    -0.21 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            4 |     3907 | 2024-03-03 | BetBoom         | L   | 0.161      | -            | -                | -                | -         |    -0.03 | Buzz, cej0t, raalz, reiko, sL1m3     |
|            3 |     4378 | 2024-02-11 | Metizport       | L   | 0.019      | -            | -                | -                | -         |    -0.06 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            2 |     4402 | 2024-02-09 | fnatic          | W   | 0.007      | 0.143        | 0.371 (0.000)    | 0.680 (0.001)    | 0 (0.000) |     0.21 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            1 |     4405 | 2024-02-09 | 3DMAX           | W   | 0.006      | 0.143        | 0.510 (0.000)    | 1.000 (0.001)    | 0 (0.000) |     0.20 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |

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
