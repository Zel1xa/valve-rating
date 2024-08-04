### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
<br />
Final Rank Value:  799.5<br />
<br />
Final Rank Value (799.5) = Starting Rank Value (777.7) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.112[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.7
- 400 + ( ( 0.185 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 777.7


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
|           15 |     3412 | 2024-03-20 | Imperial        | L   | 0.291      | -            | -                | -                | -         |    -0.63 | acoR, isak, Keoz, Snax, volt |
|           14 |     3430 | 2024-03-19 | Eternal Fire    | L   | 0.284      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|           13 |     3439 | 2024-03-18 | Legacy          | W   | 0.277      | 0.143        | 0.122 (0.005)    | 0.642 (0.025)    | 1 (0.277) |     6.86 | acoR, isak, Keoz, Snax, volt |
|           12 |     3448 | 2024-03-17 | SAW             | L   | 0.273      | -            | -                | -                | -         |    -0.88 | acoR, isak, Keoz, Snax, volt |
|           11 |     3464 | 2024-03-17 | AMKAL           | W   | 0.271      | 0.143        | 0.130 (0.005)    | 0.477 (0.018)    | 1 (0.271) |     7.49 | acoR, isak, Keoz, Snax, volt |
|           10 |     3683 | 2024-03-08 | BIG             | L   | 0.211      | -            | -                | -                | -         |    -0.35 | acoR, isak, Keoz, Snax, volt |
|            9 |     3988 | 2024-02-24 | 9 Pandas        | L   | 0.124      | -            | -                | -                | -         |    -0.90 | acoR, isak, Keoz, Snax, volt |
|            8 |     3995 | 2024-02-24 | ex-Guild Eagles | W   | 0.123      | 0.143        | 0.007 (0.000)    | 0.220 (0.004)    | 1 (0.123) |     2.12 | acoR, isak, Keoz, Snax, volt |
|            7 |     4003 | 2024-02-23 | fnatic          | W   | 0.118      | 0.143        | 0.371 (0.006)    | 0.709 (0.012)    | 1 (0.118) |     3.66 | acoR, isak, Keoz, Snax, volt |
|            6 |     4021 | 2024-02-22 | HEROIC          | L   | 0.111      | -            | -                | -                | -         |    -0.04 | acoR, isak, Keoz, Snax, volt |
|            5 |     4047 | 2024-02-21 | OG              | W   | 0.104      | 0.143        | 0.140 (0.002)    | 0.129 (0.002)    | 1 (0.104) |     2.53 | acoR, isak, Keoz, Snax, volt |
|            4 |     4079 | 2024-02-20 | ENCE            | L   | 0.097      | -            | -                | -                | -         |    -0.06 | acoR, isak, Keoz, Snax, volt |
|            3 |     4100 | 2024-02-19 | PERA            | W   | 0.092      | 0.143        | 0.048 (0.001)    | 0.453 (0.006)    | 1 (0.092) |     2.01 | acoR, isak, Keoz, Snax, volt |
|            2 |     4109 | 2024-02-19 | Vitality        | L   | 0.090      | -            | -                | -                | -         |    -0.01 | acoR, isak, Keoz, Snax, volt |
|            1 |     4351 | 2024-02-06 | HEROIC          | L   | 0.004      | -            | -                | -                | -         |    -0.00 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,655.07)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |
| 2024-03-10 |      0.226 | $5,000.00      | $1,128.13       |
| 2024-02-11 |      0.038 | $16,000.00     | $608.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
