### Roster Details<br />
Team Name: Astralis W<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  602.7<br />
<br />
Final Rank Value (602.7) = Starting Rank Value (620.8) + Head To Head Adjustments (-18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.173[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 620.8
- 400 + ( ( 0.108 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 620.8


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
|           12 |     2723 | 2024-04-19 | ENCE Athena       | L   | 0.481      | -            | -                | -                | -         |    -7.10 | anja, aurora, Ismo, josefine, marie |
|           11 |     2892 | 2024-04-14 | NAVI Javelins     | L   | 0.447      | -            | -                | -                | -         |    -3.38 | anja, aurora, Ismo, josefine, marie |
|           10 |     2901 | 2024-04-13 | NIP Impact        | L   | 0.441      | -            | -                | -                | -         |    -4.79 | anja, aurora, Ismo, josefine, marie |
|            9 |     2920 | 2024-04-12 | Permitta W        | W   | 0.434      | 0.303        | 0.000 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     4.75 | anja, aurora, Ismo, josefine, marie |
|            8 |     2940 | 2024-04-11 | Imperial fe       | L   | 0.428      | -            | -                | -                | -         |    -1.13 | anja, aurora, Ismo, josefine, marie |
|            7 |     2989 | 2024-04-10 | Imperial fe       | L   | 0.421      | -            | -                | -                | -         |    -1.12 | anja, aurora, Ismo, josefine, marie |
|            6 |     3072 | 2024-04-08 | Permitta W        | W   | 0.408      | 0.303        | 0.000 (0.000)    | 0.017 (0.002)    | 0 (0.000) |     4.43 | anja, aurora, Ismo, josefine, marie |
|            5 |     3215 | 2024-04-03 | NIP Impact        | L   | 0.375      | -            | -                | -                | -         |    -4.40 | anja, aurora, Ismo, josefine, marie |
|            4 |     3434 | 2024-03-21 | Astralis W        | L   | 0.288      | -            | -                | -                | -         |    -4.08 | anja, aurora, Ismo, josefine, marie |
|            3 |     3791 | 2024-03-06 | BIG EQUIPA        | L   | 0.188      | -            | -                | -                | -         |    -1.78 | anja, aurora, Ismo, josefine, marie |
|            2 |     4171 | 2024-02-18 | dream catchers fe | W   | 0.075      | 0.143        | 0.016 (0.000)    | 0.172 (0.002)    | 0 (0.000) |     1.49 | anja, aurora, Ismo, josefine, marie |
|            1 |     4174 | 2024-02-18 | Spirit fe         | L   | 0.074      | -            | -                | -                | -         |    -1.03 | anja, aurora, Ismo, josefine, marie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($420.40)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
