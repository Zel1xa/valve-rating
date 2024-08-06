### Roster Details<br />
Team Name: Astralis W<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  603.3<br />
<br />
Final Rank Value (603.3) = Starting Rank Value (621.0) + Head To Head Adjustments (-17.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.107<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 621.0
- 400 + ( ( 0.107 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 621.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2753 | 2024-04-19 | ENCE Athena       | L   | 0.474      | -            | -                | -                | -         |    -6.99 | anja, aurora, Ismo, josefine, marie |
|           11 |     2922 | 2024-04-14 | NAVI Javelins     | L   | 0.439      | -            | -                | -                | -         |    -3.33 | anja, aurora, Ismo, josefine, marie |
|           10 |     2931 | 2024-04-13 | NIP Impact        | L   | 0.433      | -            | -                | -                | -         |    -4.71 | anja, aurora, Ismo, josefine, marie |
|            9 |     2950 | 2024-04-12 | Permitta W        | W   | 0.426      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.67 | anja, aurora, Ismo, josefine, marie |
|            8 |     2970 | 2024-04-11 | Imperial fe       | L   | 0.420      | -            | -                | -                | -         |    -1.10 | anja, aurora, Ismo, josefine, marie |
|            7 |     3019 | 2024-04-10 | Imperial fe       | L   | 0.413      | -            | -                | -                | -         |    -1.10 | anja, aurora, Ismo, josefine, marie |
|            6 |     3102 | 2024-04-08 | Permitta W        | W   | 0.400      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.34 | anja, aurora, Ismo, josefine, marie |
|            5 |     3245 | 2024-04-03 | NIP Impact        | L   | 0.367      | -            | -                | -                | -         |    -4.31 | anja, aurora, Ismo, josefine, marie |
|            4 |     3464 | 2024-03-21 | Astralis W        | L   | 0.281      | -            | -                | -                | -         |    -3.97 | anja, aurora, Ismo, josefine, marie |
|            3 |     3821 | 2024-03-06 | BIG EQUIPA        | L   | 0.181      | -            | -                | -                | -         |    -1.71 | anja, aurora, Ismo, josefine, marie |
|            2 |     4201 | 2024-02-18 | dream catchers fe | W   | 0.068      | 0.143        | 0.016 (0.000)    | 0.167 (0.002)    | 0 (0.000) |     1.35 | anja, aurora, Ismo, josefine, marie |
|            1 |     4204 | 2024-02-18 | Spirit fe         | L   | 0.067      | -            | -                | -                | -         |    -0.93 | anja, aurora, Ismo, josefine, marie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($414.02)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
