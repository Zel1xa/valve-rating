### Roster Details<br />
Team Name: Astralis W<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Global Rank: [190](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
<br />
Final Rank Value:  602.9<br />
<br />
Final Rank Value (602.9) = Starting Rank Value (621.0) + Head To Head Adjustments (-18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.173[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 621.0
- 400 + ( ( 0.108 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 621.0


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
|           12 |     2732 | 2024-04-19 | ENCE Athena       | L   | 0.480      | -            | -                | -                | -         |    -7.08 | anja, aurora, Ismo, josefine, marie |
|           11 |     2901 | 2024-04-14 | NAVI Javelins     | L   | 0.445      | -            | -                | -                | -         |    -3.37 | anja, aurora, Ismo, josefine, marie |
|           10 |     2910 | 2024-04-13 | NIP Impact        | L   | 0.439      | -            | -                | -                | -         |    -4.77 | anja, aurora, Ismo, josefine, marie |
|            9 |     2929 | 2024-04-12 | Permitta W        | W   | 0.432      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.74 | anja, aurora, Ismo, josefine, marie |
|            8 |     2949 | 2024-04-11 | Imperial fe       | L   | 0.426      | -            | -                | -                | -         |    -1.12 | anja, aurora, Ismo, josefine, marie |
|            7 |     2998 | 2024-04-10 | Imperial fe       | L   | 0.419      | -            | -                | -                | -         |    -1.11 | anja, aurora, Ismo, josefine, marie |
|            6 |     3081 | 2024-04-08 | Permitta W        | W   | 0.406      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.41 | anja, aurora, Ismo, josefine, marie |
|            5 |     3224 | 2024-04-03 | NIP Impact        | L   | 0.373      | -            | -                | -                | -         |    -4.38 | anja, aurora, Ismo, josefine, marie |
|            4 |     3443 | 2024-03-21 | Astralis W        | L   | 0.287      | -            | -                | -                | -         |    -4.06 | anja, aurora, Ismo, josefine, marie |
|            3 |     3800 | 2024-03-06 | BIG EQUIPA        | L   | 0.187      | -            | -                | -                | -         |    -1.77 | anja, aurora, Ismo, josefine, marie |
|            2 |     4180 | 2024-02-18 | dream catchers fe | W   | 0.074      | 0.143        | 0.016 (0.000)    | 0.170 (0.002)    | 0 (0.000) |     1.46 | anja, aurora, Ismo, josefine, marie |
|            1 |     4183 | 2024-02-18 | Spirit fe         | L   | 0.073      | -            | -                | -                | -         |    -1.01 | anja, aurora, Ismo, josefine, marie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($419.10)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
