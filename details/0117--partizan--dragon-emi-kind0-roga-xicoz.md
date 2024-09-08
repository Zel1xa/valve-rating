### Roster Details<br />
Team Name: Partizan<br />
Roster: Dragon, emi, Kind0, ROGA, xicoz<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  784.5<br />
<br />
Final Rank Value (784.5) = Starting Rank Value (747.8) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.330[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.8
- 400 + ( ( 0.180 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 747.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       20 | 2024-09-07 | Enterprise      | W   | 1.000      | 0.384        | 0.039 (0.015)    | 0.697 (0.268)    | 0 (0.000) |    17.36 | Dragon, emi, Kind0, ROGA, xicoz     |
|           14 |      205 | 2024-09-01 | Rebels          | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.656 (0.252)    | 0 (0.000) |    24.00 | c0llins, Dragon, emi, Kind0, ROGA   |
|           13 |     1983 | 2024-07-13 | Nexus           | L   | 0.821      | -            | -                | -                | -         |   -13.86 | c0llins, choiv7, Dragon, emi, Kind0 |
|           12 |     2034 | 2024-07-10 | Israel          | W   | 0.801      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 0 (0.000) |     3.02 | c0llins, Dragon, emi, Kind0, VLDN   |
|           11 |     2045 | 2024-07-09 | North Macedonia | W   | 0.795      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.04 | c0llins, choiv7, Dragon, emi, Kind0 |
|           10 |     2052 | 2024-07-09 | Turkey          | L   | 0.794      | -            | -                | -                | -         |   -19.86 | c0llins, choiv7, Dragon, emi, Kind0 |
|            9 |     2605 | 2024-06-06 | Passion UA      | L   | 0.572      | -            | -                | -                | -         |    -3.37 | aidKiT, c0llins, Dragon, emi, xicoz |
|            8 |     2696 | 2024-06-04 | Passion UA      | L   | 0.560      | -            | -                | -                | -         |    -3.24 | aidKiT, c0llins, Dragon, emi, xicoz |
|            7 |     2741 | 2024-06-02 | Apogee          | W   | 0.546      | 0.371        | 0.006 (0.001)    | 0.198 (0.040)    | 0 (0.000) |     8.62 | aidKiT, c0llins, Dragon, emi, xicoz |
|            6 |     2830 | 2024-05-30 | Permitta        | W   | 0.526      | 0.371        | 0.032 (0.006)    | 0.968 (0.189)    | 0 (0.000) |    11.67 | aidKiT, c0llins, Dragon, emi, xicoz |
|            5 |     2929 | 2024-05-25 | Zero Tenacity   | L   | 0.494      | -            | -                | -                | -         |    -2.31 | aidKiT, c0llins, Dragon, emi, xicoz |
|            4 |     2937 | 2024-05-25 | UNiTY           | W   | 0.493      | 0.371        | 0.026 (0.005)    | 0.394 (0.072)    | 0 (0.000) |    10.66 | aidKiT, c0llins, Dragon, emi, xicoz |
|            3 |     2949 | 2024-05-24 | ex-Guild Eagles | L   | 0.486      | -            | -                | -                | -         |    -7.84 | aidKiT, c0llins, Dragon, emi, xicoz |
|            2 |     3051 | 2024-05-21 | kONO            | W   | 0.466      | 0.371        | 0.025 (0.004)    | 0.532 (0.092)    | 0 (0.000) |     9.31 | aidKiT, c0llins, Dragon, emi, xicoz |
|            1 |     3924 | 2024-04-18 | BetBoom         | L   | 0.247      | -            | -                | -                | -         |    -0.49 | aidKiT, c0llins, Dragon, emi, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,859.72)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
