### Roster Details<br />
Team Name: Steel Helmet<br />
Roster: 18yM, AE, captainMo, DD, xiaosaGe<br />
Global Rank: [213](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [27]( ../standings_asia.md)<br />
<br />
Final Rank Value:  491.5<br />
<br />
Final Rank Value (491.5) = Starting Rank Value (537.0) + Head To Head Adjustments (-45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.283[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.071<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 537.0
- 400 + ( ( 0.071 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 537.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      392 | 2024-08-27 | Bromo             | L   | 1.000      | -            | -                | -                | -         |   -13.84 | 18yM, AE, captainMo, DD, xiaosaGe |
|            9 |      409 | 2024-08-26 | TYLOO             | L   | 1.000      | -            | -                | -                | -         |    -2.22 | 18yM, AE, captainMo, DD, xiaosaGe |
|            8 |      510 | 2024-08-25 | red demon         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |    11.14 | 18yM, AE, captainMo, DD, xiaosaGe |
|            7 |      520 | 2024-08-24 | Bromo             | L   | 1.000      | -            | -                | -                | -         |   -14.71 | 18yM, AE, captainMo, DD, xiaosaGe |
|            6 |     1220 | 2024-08-03 | Chinggis Warriors | L   | 0.959      | -            | -                | -                | -         |    -3.65 | 18yM, AE, captainMo, DD, xiaosaGe |
|            5 |     1443 | 2024-07-28 | -72c              | L   | 0.920      | -            | -                | -                | -         |   -10.66 | 18yM, AE, captainMo, DD, xiaosaGe |
|            4 |     2015 | 2024-07-11 | CatEvil           | L   | 0.806      | -            | -                | -                | -         |   -11.40 | 18yM, AE, captainMo, DD, xiaosaGe |
|            3 |     2021 | 2024-07-11 | The MongolZ       | L   | 0.805      | -            | -                | -                | -         |    -0.02 | 18yM, AE, captainMo, DD, xiaosaGe |
|            2 |     4209 | 2024-04-09 | Nemiga            | L   | 0.185      | -            | -                | -                | -         |    -0.17 | 18yM, AE, captainMo, DD, xiaosaGe |
|            1 |     4239 | 2024-04-08 | Astralis          | L   | 0.179      | -            | -                | -                | -         |    -0.02 | 18yM, AE, captainMo, DD, xiaosaGe |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($877.31)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
