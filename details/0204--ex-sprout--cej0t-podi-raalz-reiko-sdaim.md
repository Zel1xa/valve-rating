### Roster Details<br />
Team Name: ex-Sprout<br />
Roster: cej0t, podi, raalz, reiko, Sdaim<br />
Global Rank: [204](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
<br />
Final Rank Value:  509.3<br />
<br />
Final Rank Value (509.3) = Starting Rank Value (511.1) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.1
- 400 + ( ( 0.054 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 511.1


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
|           11 |     3294 | 2024-03-28 | Rebels          | L   | 0.340      | -            | -                | -                | -         |    -0.67 | cej0t, podi, raalz, reiko, Sdaim     |
|           10 |     3368 | 2024-03-25 | ALTERNATE aTTaX | L   | 0.320      | -            | -                | -                | -         |    -0.69 | cej0t, podi, raalz, reiko, Sdaim     |
|            9 |     3397 | 2024-03-22 | Aurora          | L   | 0.300      | -            | -                | -                | -         |    -0.01 | cej0t, podi, raalz, reiko, Sdaim     |
|            8 |     3469 | 2024-03-19 | B8              | L   | 0.278      | -            | -                | -                | -         |    -0.33 | cej0t, podi, raalz, reiko, Sdaim     |
|            7 |     3755 | 2024-03-07 | Alliance        | L   | 0.198      | -            | -                | -                | -         |    -0.81 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            6 |     3819 | 2024-03-05 | KOI             | L   | 0.187      | -            | -                | -                | -         |    -0.23 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            5 |     3861 | 2024-03-03 | BetBoom         | L   | 0.173      | -            | -                | -                | -         |    -0.03 | Buzz, cej0t, raalz, reiko, sL1m3     |
|            4 |     4332 | 2024-02-11 | Metizport       | L   | 0.032      | -            | -                | -                | -         |    -0.14 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            3 |     4356 | 2024-02-09 | fnatic          | W   | 0.020      | 0.143        | 0.371 (0.001)    | 0.708 (0.002)    | 0 (0.000) |     0.62 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            2 |     4359 | 2024-02-09 | 3DMAX           | W   | 0.019      | 0.143        | 0.506 (0.001)    | 1.000 (0.003)    | 0 (0.000) |     0.61 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            1 |     4379 | 2024-02-07 | Metizport       | L   | 0.006      | -            | -                | -                | -         |    -0.03 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />