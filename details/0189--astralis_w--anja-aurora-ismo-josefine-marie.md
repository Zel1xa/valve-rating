### Roster Details<br />
Team Name: Astralis W<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  603.3<br />
<br />
Final Rank Value (603.3) = Starting Rank Value (621.2) + Head To Head Adjustments (-17.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 621.2
- 400 + ( ( 0.108 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 621.2


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
|           12 |     2742 | 2024-04-19 | ENCE Athena       | L   | 0.475      | -            | -                | -                | -         |    -7.01 | anja, aurora, Ismo, josefine, marie |
|           11 |     2911 | 2024-04-14 | NAVI Javelins     | L   | 0.441      | -            | -                | -                | -         |    -3.34 | anja, aurora, Ismo, josefine, marie |
|           10 |     2920 | 2024-04-13 | NIP Impact        | L   | 0.435      | -            | -                | -                | -         |    -4.72 | anja, aurora, Ismo, josefine, marie |
|            9 |     2939 | 2024-04-12 | Permitta W        | W   | 0.427      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.68 | anja, aurora, Ismo, josefine, marie |
|            8 |     2959 | 2024-04-11 | Imperial fe       | L   | 0.422      | -            | -                | -                | -         |    -1.11 | anja, aurora, Ismo, josefine, marie |
|            7 |     3008 | 2024-04-10 | Imperial fe       | L   | 0.415      | -            | -                | -                | -         |    -1.10 | anja, aurora, Ismo, josefine, marie |
|            6 |     3091 | 2024-04-08 | Permitta W        | W   | 0.402      | 0.303        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     4.36 | anja, aurora, Ismo, josefine, marie |
|            5 |     3234 | 2024-04-03 | NIP Impact        | L   | 0.368      | -            | -                | -                | -         |    -4.33 | anja, aurora, Ismo, josefine, marie |
|            4 |     3453 | 2024-03-21 | Astralis W        | L   | 0.282      | -            | -                | -                | -         |    -3.99 | anja, aurora, Ismo, josefine, marie |
|            3 |     3810 | 2024-03-06 | BIG EQUIPA        | L   | 0.182      | -            | -                | -                | -         |    -1.73 | anja, aurora, Ismo, josefine, marie |
|            2 |     4190 | 2024-02-18 | dream catchers fe | W   | 0.069      | 0.143        | 0.016 (0.000)    | 0.167 (0.002)    | 0 (0.000) |     1.38 | anja, aurora, Ismo, josefine, marie |
|            1 |     4193 | 2024-02-18 | Spirit fe         | L   | 0.068      | -            | -                | -                | -         |    -0.94 | anja, aurora, Ismo, josefine, marie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($415.20)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
