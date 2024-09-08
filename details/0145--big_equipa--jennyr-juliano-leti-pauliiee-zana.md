### Roster Details<br />
Team Name: BIG EQUIPA<br />
Roster: JennyR, juliano, LETi, pauliiee, Zana<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  710.7<br />
<br />
Final Rank Value (710.7) = Starting Rank Value (712.5) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.5
- 400 + ( ( 0.161 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 712.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      264 | 2024-08-29 | Crescent fe       | W   | 1.000      | 0.328        | 0.003 (0.001)    | 0.060 (0.020)    | 0 (0.000) |    12.76 | JennyR, juliano, LETi, pauliiee, Zana   |
|           13 |     1693 | 2024-07-20 | dream catchers fe | L   | 0.867      | -            | -                | -                | -         |   -14.14 | JennyR, juliano, kyossa, pauliiee, Zana |
|           12 |     2747 | 2024-06-01 | HSG fe            | L   | 0.543      | -            | -                | -                | -         |    -7.38 | JennyR, juliano, kyossa, pauliiee, Zana |
|           11 |     2785 | 2024-05-31 | Imperial fe       | L   | 0.536      | -            | -                | -                | -         |    -4.23 | JennyR, juliano, kyossa, pauliiee, Zana |
|           10 |     2797 | 2024-05-31 | FlyQuest RED      | W   | 0.534      | 0.524        | 0.014 (0.004)    | 0.162 (0.045)    | 1 (0.534) |     8.50 | JennyR, juliano, kyossa, pauliiee, Zana |
|            9 |     3113 | 2024-05-19 | NAVI Javelins     | L   | 0.453      | -            | -                | -                | -         |    -6.17 | JennyR, juliano, kyossa, pauliiee, Zana |
|            8 |     3138 | 2024-05-18 | Nemesis fe        | W   | 0.447      | 0.281        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.01 | JennyR, juliano, kyossa, pauliiee, Zana |
|            7 |     3824 | 2024-04-20 | Fearless Cheetahs | W   | 0.261      | 0.331        | 0.001 (0.000)    | 0.027 (0.002)    | 0 (0.000) |     3.07 | JennyR, juliano, kyossa, pauliiee, Zana |
|            6 |     3872 | 2024-04-19 | NIP Impact        | W   | 0.255      | 0.331        | 0.004 (0.000)    | 0.208 (0.018)    | 0 (0.000) |     3.60 | JennyR, juliano, kyossa, pauliiee, Zana |
|            5 |     4260 | 2024-04-07 | Imperial fe       | L   | 0.173      | -            | -                | -                | -         |    -1.38 | JennyR, juliano, kyossa, pauliiee, Zana |
|            4 |     4275 | 2024-04-06 | Spirit fe         | W   | 0.166      | 0.262        | 0.005 (0.000)    | 0.107 (0.005)    | 0 (0.000) |     2.12 | JennyR, juliano, kyossa, pauliiee, Zana |
|            3 |     4325 | 2024-04-04 | ENCE Athena       | W   | 0.155      | 0.331        | 0.001 (0.000)    | 0.048 (0.002)    | 0 (0.000) |     1.77 | JennyR, juliano, kyossa, pauliiee, Zana |
|            2 |     4459 | 2024-03-28 | Astralis W        | L   | 0.108      | -            | -                | -                | -         |    -2.12 | JennyR, juliano, kyossa, pauliiee, Zana |
|            1 |     4734 | 2024-03-14 | Imperial fe       | L   | 0.015      | -            | -                | -                | -         |    -0.12 | JennyR, juliano, kyossa, pauliiee, Zana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,842.22)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
