### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: cerolzin, GYZER, kye, mello, zmb<br />
Global Rank: [199](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  520.0<br />
<br />
Final Rank Value (520.0) = Starting Rank Value (512.3) + Head To Head Adjustments (7.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 512.3
- 400 + ( ( 0.055 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 512.3


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
|           11 |     2931 | 2024-04-11 | Case        | L   | 0.433      | -            | -                | -                | -         |    -1.40 | cerolzin, GYZER, kye, mello, zmb      |
|           10 |     3086 | 2024-04-07 | Imperial    | L   | 0.407      | -            | -                | -                | -         |    -0.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            9 |     3569 | 2024-03-14 | Case        | L   | 0.247      | -            | -                | -                | -         |    -0.75 | Bruninho, cerolzin, GYZER, kye, mello |
|            8 |     3632 | 2024-03-12 | Solid       | W   | 0.234      | 0.303        | 0.025 (0.002)    | 0.836 (0.059)    | 0 (0.000) |     6.58 | Bruninho, cerolzin, GYZER, kye, mello |
|            7 |     3644 | 2024-03-11 | BESTIA      | L   | 0.229      | -            | -                | -                | -         |    -0.42 | Bruninho, cerolzin, GYZER, kye, mello |
|            6 |     3669 | 2024-03-10 | Case        | L   | 0.221      | -            | -                | -                | -         |    -0.62 | Bruninho, cerolzin, GYZER, kye, mello |
|            5 |     3673 | 2024-03-10 | Flamengo    | W   | 0.220      | 0.435        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     3.29 | Bruninho, cerolzin, GYZER, kye, mello |
|            4 |     3715 | 2024-03-08 | BESTIA      | L   | 0.208      | -            | -                | -                | -         |    -0.36 | Bruninho, cerolzin, GYZER, kye, mello |
|            3 |     4156 | 2024-02-18 | BESTIA      | L   | 0.080      | -            | -                | -                | -         |    -0.14 | Bruninho, cerolzin, GYZER, kye, mello |
|            2 |     4208 | 2024-02-16 | Dusty Roots | W   | 0.067      | 0.435        | 0.006 (0.000)    | 0.369 (0.011)    | 0 (0.000) |     1.83 | Bruninho, cerolzin, GYZER, kye, mello |
|            1 |     4320 | 2024-02-12 | BESTIA      | L   | 0.042      | -            | -                | -                | -         |    -0.07 | Bruninho, cerolzin, GYZER, kye, mello |

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
