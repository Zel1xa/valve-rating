### Roster Details<br />
Team Name: Hawks<br />
Roster: guidimon, KUN, nacho, santt1g, wait<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  513.2<br />
<br />
Final Rank Value (513.2) = Starting Rank Value (536.8) + Head To Head Adjustments (-23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.8
- 400 + ( ( 0.066 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 536.8


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
|           10 |      436 | 2024-07-19 | FURIA Academy     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | guidimon, KUN, nacho, santt1g, wait  |
|            9 |      538 | 2024-07-17 | Patins da Ferrari | L   | 1.000      | -            | -                | -                | -         |    -5.97 | guidimon, KUN, nacho, santt1g, wait  |
|            8 |      664 | 2024-07-15 | Solid             | L   | 1.000      | -            | -                | -                | -         |    -4.50 | guidimon, KUN, nacho, santt1g, wait  |
|            7 |      739 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |    -4.33 | guidimon, KUN, nacho, santt1g, wait  |
|            6 |      814 | 2024-07-07 | Hype              | L   | 1.000      | -            | -                | -                | -         |    -3.26 | F4QQ, guidimon, KUN, santt1g, wait   |
|            5 |     1464 | 2024-06-02 | Bounty Hunters    | L   | 0.802      | -            | -                | -                | -         |    -3.58 | ABM, christo, guidimon, KUN, santt1g |
|            4 |     1523 | 2024-05-31 | Vikings KR        | L   | 0.789      | -            | -                | -                | -         |    -4.69 | ABM, christo, guidimon, KUN, santt1g |
|            3 |     1547 | 2024-05-30 | Galorys           | L   | 0.782      | -            | -                | -                | -         |    -2.89 | ABM, christo, guidimon, KUN, santt1g |
|            2 |     1628 | 2024-05-27 | Case              | W   | 0.762      | 0.371        | 0.030 (0.008)    | 0.721 (0.204)    | 0 (0.000) |    21.39 | ABM, christo, guidimon, KUN, santt1g |
|            1 |     4252 | 2024-02-14 | W7M               | L   | 0.077      | -            | -                | -                | -         |    -0.32 | guidimon, KUN, nacho, nasher, PABLEK |

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
