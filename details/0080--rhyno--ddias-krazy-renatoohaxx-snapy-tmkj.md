### Roster Details<br />
Team Name: Rhyno<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  909.8<br />
<br />
Final Rank Value (909.8) = Starting Rank Value (859.5) + Head To Head Adjustments (50.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.440[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.103[<sup>2</sup>](#table1)
- LAN Wins: 0.084[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.5
- 400 + ( ( 0.237 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 859.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2324 | 2024-06-11 | Nemiga        | L   | 0.607      | -            | -                | -                | -         |    -3.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     2346 | 2024-06-10 | CYBERSHOKE    | W   | 0.601      | 0.500        | 0.043 (0.013)    | 0.702 (0.211)    | 0 (0.000) |     9.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     2377 | 2024-06-09 | Rebels        | W   | 0.595      | 0.500        | 0.028 (0.008)    | 0.656 (0.195)    | 0 (0.000) |    10.76 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     2474 | 2024-06-08 | NAVI Junior   | W   | 0.586      | 0.500        | 0.001 (0.000)    | 0.144 (0.042)    | 0 (0.000) |     4.66 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     2566 | 2024-06-06 | MOUZ NXT      | L   | 0.575      | -            | -                | -                | -         |    -5.40 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     2677 | 2024-06-04 | Endpoint      | W   | 0.561      | 0.500        | 0.065 (0.018)    | 0.723 (0.203)    | 0 (0.000) |    11.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     2874 | 2024-05-28 | Sampi         | L   | 0.513      | -            | -                | -                | -         |    -7.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     2898 | 2024-05-27 | Endpoint      | W   | 0.506      | 0.435        | 0.065 (0.014)    | 0.723 (0.159)    | 0 (0.000) |    10.37 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     2939 | 2024-05-25 | Zero Tenacity | L   | 0.492      | -            | -                | -                | -         |    -4.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     3006 | 2024-05-22 | MOUZ NXT      | W   | 0.473      | 0.435        | 0.111 (0.023)    | 0.813 (0.167)    | 0 (0.000) |     9.60 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     3043 | 2024-05-21 | B8            | L   | 0.468      | -            | -                | -                | -         |    -3.37 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     3149 | 2024-05-18 | LEON          | W   | 0.446      | 0.143        | 0.005 (0.000)    | 0.080 (0.005)    | 0 (0.000) |     3.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     3205 | 2024-05-16 | CPH Wolves    | W   | 0.434      | 0.143        | 0.003 (0.000)    | 0.510 (0.032)    | 0 (0.000) |     5.23 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3270 | 2024-05-15 | EYEBALLERS    | W   | 0.426      | 0.143        | 0.003 (0.000)    | 0.298 (0.018)    | -         |     5.67 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3365 | 2024-05-12 | AL QATRAO     | W   | 0.407      | 0.306        | 0.002 (0.000)    | 0.015 (0.002)    | 1 (0.407) |     2.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3401 | 2024-05-11 | ALL-IN        | W   | 0.399      | -            | -                | -                | 1 (0.399) |     1.60 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,276.46)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.607 | $25,000.00     | $15,180.56      |
| 2024-05-12 |      0.407 | $2,693.00      | $1,095.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
