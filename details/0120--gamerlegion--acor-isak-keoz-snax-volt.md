### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  799.8<br />
<br />
Final Rank Value (799.8) = Starting Rank Value (778.0) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.113[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.0
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 778.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     3341 | 2024-03-20 | Imperial        | L   | 0.293      | -            | -                | -                | -         |    -0.73 | acoR, isak, Keoz, Snax, volt |
|           14 |     3359 | 2024-03-19 | Eternal Fire    | L   | 0.285      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           13 |     3368 | 2024-03-18 | Legacy          | W   | 0.279      | 0.143        | 0.122 (0.005)    | 0.663 (0.026)    | 1 (0.279) |     6.88 | acoR, isak, Keoz, Snax, volt |
|           12 |     3377 | 2024-03-17 | SAW             | L   | 0.275      | -            | -                | -                | -         |    -0.88 | acoR, isak, Keoz, Snax, volt |
|           11 |     3393 | 2024-03-17 | AMKAL           | W   | 0.273      | 0.143        | 0.130 (0.005)    | 0.494 (0.019)    | 1 (0.273) |     7.55 | acoR, isak, Keoz, Snax, volt |
|           10 |     3610 | 2024-03-08 | BIG             | L   | 0.213      | -            | -                | -                | -         |    -0.34 | acoR, isak, Keoz, Snax, volt |
|            9 |     3915 | 2024-02-24 | 9 Pandas        | L   | 0.126      | -            | -                | -                | -         |    -0.92 | acoR, isak, Keoz, Snax, volt |
|            8 |     3922 | 2024-02-24 | ex-Guild Eagles | W   | 0.125      | 0.143        | 0.007 (0.000)    | 0.228 (0.004)    | 1 (0.125) |     2.16 | acoR, isak, Keoz, Snax, volt |
|            7 |     3930 | 2024-02-23 | fnatic          | W   | 0.120      | 0.143        | 0.290 (0.005)    | 0.627 (0.011)    | 1 (0.120) |     3.62 | acoR, isak, Keoz, Snax, volt |
|            6 |     3948 | 2024-02-22 | HEROIC          | L   | 0.113      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            5 |     3975 | 2024-02-21 | OG              | W   | 0.106      | 0.143        | 0.140 (0.002)    | 0.133 (0.002)    | 1 (0.106) |     2.54 | acoR, isak, Keoz, Snax, volt |
|            4 |     4006 | 2024-02-20 | ENCE            | L   | 0.099      | -            | -                | -                | -         |    -0.07 | acoR, isak, Keoz, Snax, volt |
|            3 |     4027 | 2024-02-19 | PERA            | W   | 0.093      | 0.143        | 0.048 (0.001)    | 0.468 (0.006)    | 1 (0.093) |     2.05 | acoR, isak, Keoz, Snax, volt |
|            2 |     4036 | 2024-02-19 | Vitality        | L   | 0.092      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            1 |     4278 | 2024-02-06 | HEROIC          | L   | 0.005      | -            | -                | -                | -         |    -0.00 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,708.17)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |
| 2024-03-10 |      0.227 | $5,000.00      | $1,136.69       |
| 2024-02-11 |      0.040 | $16,000.00     | $636.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
