# OSRS-Analysis
#### Context
I wanted to determine the differences between two weapons (shown below) in the game Old School RuneScape.
Data was collected over 6 hours (3 hours per weapon) with 10-minute intervals between observations.

|                    | Iron Scimitar | Event RPG |
|        :-:         |      :-:      |    :-:    |
|   Relative Speed   |     slower    |   faster  |
| Has Attack Bonuses |      yes      |     no    |

#### Goals:
- determine which weapon is more accurate
- determine which weapon is more efficient
- obtain estimates of the time it would take to reach level 75 Defence using each weapon

#### Methods:
- linear regression
- hypothesis testing

#### Results:

|                               | Iron Scimitar | Event RPG |
|            :-:                |      :-:      |    :-:    |
| Probability of Successful hit |     0.21      |   0.19    |
|      Efficiency (exp/hr)      |     1260      |   1500    |
|     Hours until level 75      |      844      |    709    |

The Iron Scimitar was more accurate while the Event RPG was more efficient for training.

#### References
*Old School Runescape* [Game]. (2013). Cambridge: Jagex Ltd.
