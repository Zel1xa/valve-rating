### Roster Details<br />
Team Name: FURIA Academy<br />
Roster: cerolzin, GYZER, kye, mello, zmb<br />
Global Rank: [198](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [55]( ../standings_americas.md)<br />
<br />
Final Rank Value:  518.6<br />
<br />
Final Rank Value (518.6) = Starting Rank Value (511.5) + Head To Head Adjustments (7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.5
- 400 + ( ( 0.054 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 511.5


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
|           11 |     2963 | 2024-04-11 | Case        | L   | 0.421      | -            | -                | -                | -         |    -1.36 | cerolzin, GYZER, kye, mello, zmb      |
|           10 |     3118 | 2024-04-07 | Imperial    | L   | 0.395      | -            | -                | -                | -         |    -0.18 | Bruninho, cerolzin, GYZER, kye, mello |
|            9 |     3601 | 2024-03-14 | Case        | L   | 0.236      | -            | -                | -                | -         |    -0.71 | Bruninho, cerolzin, GYZER, kye, mello |
|            8 |     3664 | 2024-03-12 | Solid       | W   | 0.222      | 0.303        | 0.024 (0.002)    | 0.825 (0.056)    | 0 (0.000) |     6.25 | Bruninho, cerolzin, GYZER, kye, mello |
|            7 |     3676 | 2024-03-11 | BESTIA      | L   | 0.217      | -            | -                | -                | -         |    -0.40 | Bruninho, cerolzin, GYZER, kye, mello |
|            6 |     3701 | 2024-03-10 | Case        | L   | 0.210      | -            | -                | -                | -         |    -0.58 | Bruninho, cerolzin, GYZER, kye, mello |
|            5 |     3705 | 2024-03-10 | Flamengo    | W   | 0.209      | 0.435        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     3.12 | Bruninho, cerolzin, GYZER, kye, mello |
|            4 |     3747 | 2024-03-08 | BESTIA      | L   | 0.197      | -            | -                | -                | -         |    -0.34 | Bruninho, cerolzin, GYZER, kye, mello |
|            3 |     4188 | 2024-02-18 | BESTIA      | L   | 0.069      | -            | -                | -                | -         |    -0.12 | Bruninho, cerolzin, GYZER, kye, mello |
|            2 |     4240 | 2024-02-16 | Dusty Roots | W   | 0.055      | 0.435        | 0.006 (0.000)    | 0.366 (0.009)    | 0 (0.000) |     1.52 | Bruninho, cerolzin, GYZER, kye, mello |
|            1 |     4352 | 2024-02-12 | BESTIA      | L   | 0.030      | -            | -                | -                | -         |    -0.05 | Bruninho, cerolzin, GYZER, kye, mello |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
