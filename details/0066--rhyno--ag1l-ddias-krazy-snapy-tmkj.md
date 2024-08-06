### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  984.1<br />
<br />
Final Rank Value (984.1) = Starting Rank Value (964.7) + Head To Head Adjustments (19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.7
- 400 + ( ( 0.275 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 964.7


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
|           25 |       14 | 2024-08-05 | Meteor        | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |     7.40 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      255 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -17.92 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      467 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | -                | 0.333 (0.048)    | 0 (0.000) |    10.07 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      575 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.74 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      648 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.457 (0.229)    | 0 (0.000) |     6.31 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      718 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.65 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      767 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.17 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1185 | 2024-06-11 | Nemiga        | L   | 0.831      | -            | -                | -                | -         |    -7.42 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1207 | 2024-06-10 | CYBERSHOKE    | W   | 0.824      | 0.500        | 0.039 (0.016)    | 0.346 (0.143)    | 0 (0.000) |     8.88 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1238 | 2024-06-09 | Rebels        | W   | 0.818      | 0.500        | 0.038 (0.016)    | 0.591 (0.242)    | 0 (0.000) |    14.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1335 | 2024-06-08 | NAVI Junior   | W   | 0.810      | 0.500        | -                | 0.089 (0.036)    | 0 (0.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1427 | 2024-06-06 | MOUZ NXT      | L   | 0.798      | -            | -                | -                | -         |    -8.21 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1538 | 2024-06-04 | Endpoint      | W   | 0.785      | 0.500        | 0.012 (0.005)    | 0.514 (0.202)    | -         |     9.79 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1735 | 2024-05-28 | Sampi         | L   | 0.736      | -            | -                | -                | -         |   -14.03 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1759 | 2024-05-27 | Endpoint      | W   | 0.730      | 0.435        | 0.012 (0.004)    | 0.514 (0.163)    | -         |     9.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1800 | 2024-05-25 | Zero Tenacity | L   | 0.716      | -            | -                | -                | -         |    -8.00 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1867 | 2024-05-22 | MOUZ NXT      | W   | 0.696      | 0.435        | 0.139 (0.042)    | 0.986 (0.298)    | -         |    12.63 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1904 | 2024-05-21 | B8            | L   | 0.691      | -            | -                | -                | -         |    -6.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2010 | 2024-05-18 | LEON          | W   | 0.669      | 0.143        | 0.007 (0.001)    | -                | -         |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2066 | 2024-05-16 | CPH Wolves    | W   | 0.657      | 0.143        | -                | 0.361 (0.034)    | -         |     5.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2131 | 2024-05-15 | EYEBALLERS    | W   | 0.649      | 0.143        | 0.005 (0.001)    | 0.500 (0.046)    | -         |     7.75 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2226 | 2024-05-12 | AL QATRAO     | W   | 0.630      | 0.306        | 0.004 (0.001)    | -                | 1 (0.630) |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2262 | 2024-05-11 | ALL-IN        | W   | 0.623      | -            | -                | -                | 1 (0.623) |     1.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3898 | 2024-03-03 | Portugal      | L   | 0.164      | -            | -                | -                | -         |    -4.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3912 | 2024-03-02 | AL QATRAO     | W   | 0.158      | -            | -                | -                | 1 (0.158) |     0.85 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,727.10)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.831 | $25,000.00     | $20,763.89      |
| 2024-05-12 |      0.630 | $2,693.00      | $1,697.34       |
| 2024-03-03 |      0.164 | $1,625.00      | $265.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
