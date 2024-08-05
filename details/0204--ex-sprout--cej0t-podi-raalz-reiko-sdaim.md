### Roster Details<br />
Team Name: ex-Sprout<br />
Roster: cej0t, podi, raalz, reiko, Sdaim<br />
Global Rank: [204](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
<br />
Final Rank Value:  504.6<br />
<br />
Final Rank Value (504.6) = Starting Rank Value (506.6) + Head To Head Adjustments (-2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.208[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 506.6
- 400 + ( ( 0.052 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 506.6


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
|           10 |     3320 | 2024-03-28 | Rebels          | L   | 0.333      | -            | -                | -                | -         |    -0.65 | cej0t, podi, raalz, reiko, Sdaim     |
|            9 |     3394 | 2024-03-25 | ALTERNATE aTTaX | L   | 0.313      | -            | -                | -                | -         |    -0.66 | cej0t, podi, raalz, reiko, Sdaim     |
|            8 |     3423 | 2024-03-22 | Aurora          | L   | 0.293      | -            | -                | -                | -         |    -0.01 | cej0t, podi, raalz, reiko, Sdaim     |
|            7 |     3495 | 2024-03-19 | B8              | L   | 0.271      | -            | -                | -                | -         |    -0.32 | cej0t, podi, raalz, reiko, Sdaim     |
|            6 |     3781 | 2024-03-07 | Alliance        | L   | 0.191      | -            | -                | -                | -         |    -0.76 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            5 |     3845 | 2024-03-05 | KOI             | L   | 0.180      | -            | -                | -                | -         |    -0.22 | cej0t, raalz, reiko, Sdaim, sL1m3    |
|            4 |     3887 | 2024-03-03 | BetBoom         | L   | 0.166      | -            | -                | -                | -         |    -0.03 | Buzz, cej0t, raalz, reiko, sL1m3     |
|            3 |     4358 | 2024-02-11 | Metizport       | L   | 0.025      | -            | -                | -                | -         |    -0.11 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            2 |     4382 | 2024-02-09 | fnatic          | W   | 0.012      | 0.143        | 0.371 (0.001)    | 0.697 (0.001)    | 0 (0.000) |     0.39 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |
|            1 |     4385 | 2024-02-09 | 3DMAX           | W   | 0.012      | 0.143        | 0.508 (0.001)    | 1.000 (0.002)    | 0 (0.000) |     0.38 | Anlelele, cej0t, raalz, Sdaim, sL1m3 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
