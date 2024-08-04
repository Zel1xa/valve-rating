### Roster Details<br />
Team Name: Hawks<br />
Roster: guidimon, KUN, nacho, santt1g, wait<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [56]( ../standings_americas.md)<br />
<br />
Final Rank Value:  512.4<br />
<br />
Final Rank Value (512.4) = Starting Rank Value (536.2) + Head To Head Adjustments (-23.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.2
- 400 + ( ( 0.067 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 536.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      517 | 2024-07-19 | FURIA Academy     | L   | 1.000      | -            | -                | -                | -         |   -15.42 | guidimon, KUN, nacho, santt1g, wait  |
|            9 |      620 | 2024-07-17 | Patins da Ferrari | L   | 1.000      | -            | -                | -                | -         |    -5.69 | guidimon, KUN, nacho, santt1g, wait  |
|            8 |      734 | 2024-07-15 | Solid             | L   | 1.000      | -            | -                | -                | -         |    -4.65 | guidimon, KUN, nacho, santt1g, wait  |
|            7 |      806 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |    -4.11 | guidimon, KUN, nacho, santt1g, wait  |
|            6 |      881 | 2024-07-07 | Hype              | L   | 1.000      | -            | -                | -                | -         |    -3.65 | F4QQ, guidimon, KUN, santt1g, wait   |
|            5 |     1525 | 2024-06-02 | Bounty Hunters    | L   | 0.785      | -            | -                | -                | -         |    -3.43 | ABM, christo, guidimon, KUN, santt1g |
|            4 |     1584 | 2024-05-31 | Vikings KR        | L   | 0.773      | -            | -                | -                | -         |    -4.60 | ABM, christo, guidimon, KUN, santt1g |
|            3 |     1608 | 2024-05-30 | Galorys           | L   | 0.766      | -            | -                | -                | -         |    -2.94 | ABM, christo, guidimon, KUN, santt1g |
|            2 |     1689 | 2024-05-27 | Case              | W   | 0.745      | 0.371        | 0.029 (0.008)    | 0.804 (0.222)    | 0 (0.000) |    20.92 | ABM, christo, guidimon, KUN, santt1g |
|            1 |     4223 | 2024-02-14 | W7M               | L   | 0.060      | -            | -                | -                | -         |    -0.29 | guidimon, KUN, nacho, nasher, PABLEK |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
