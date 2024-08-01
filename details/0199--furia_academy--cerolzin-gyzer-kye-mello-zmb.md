### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: cerolzin, GYZER, kye, mello, zmb<br />
Global Rank: [199](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  524.0<br />
<br />
Final Rank Value (524.0) = Starting Rank Value (515.1) + Head To Head Adjustments (8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.1
- 400 + ( ( 0.056 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 515.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2887 | 2024-04-11 | Case        | L   | 0.454      | -            | -                | -                | -         |    -1.47 | cerolzin, GYZER, kye, mello, zmb      |
|           10 |     3042 | 2024-04-07 | Imperial    | L   | 0.428      | -            | -                | -                | -         |    -0.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            9 |     3540 | 2024-03-14 | Case        | L   | 0.268      | -            | -                | -                | -         |    -0.80 | Bruninho, cerolzin, GYZER, kye, mello |
|            8 |     3606 | 2024-03-12 | Solid       | W   | 0.255      | 0.303        | 0.027 (0.002)    | 0.843 (0.065)    | 0 (0.000) |     7.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            7 |     3618 | 2024-03-11 | BESTIA      | L   | 0.250      | -            | -                | -                | -         |    -0.46 | Bruninho, cerolzin, GYZER, kye, mello |
|            6 |     3643 | 2024-03-10 | Case        | L   | 0.243      | -            | -                | -                | -         |    -0.66 | Bruninho, cerolzin, GYZER, kye, mello |
|            5 |     3647 | 2024-03-10 | Flamengo    | W   | 0.242      | 0.435        | 0.000 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     3.59 | Bruninho, cerolzin, GYZER, kye, mello |
|            4 |     3690 | 2024-03-08 | BESTIA      | L   | 0.230      | -            | -                | -                | -         |    -0.41 | Bruninho, cerolzin, GYZER, kye, mello |
|            3 |     4146 | 2024-02-18 | BESTIA      | L   | 0.101      | -            | -                | -                | -         |    -0.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            2 |     4198 | 2024-02-16 | Dusty Roots | W   | 0.088      | 0.435        | 0.007 (0.000)    | 0.325 (0.012)    | 0 (0.000) |     2.42 | Bruninho, cerolzin, GYZER, kye, mello |
|            1 |     4318 | 2024-02-12 | BESTIA      | L   | 0.063      | -            | -                | -                | -         |    -0.11 | Bruninho, cerolzin, GYZER, kye, mello |

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
