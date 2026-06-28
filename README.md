# Esports Live Chat Toxicity Dataset

A manually annotated dataset of esports tournament live chat messages for toxic and hate speech detection. Collected from Twitch and YouTube streams across five competitive games.

## Dataset

**File:** `data.csv`  
**Total messages:** 4,957  
**Label distribution:** 1,677 toxic (33.8%) · 3,280 non-toxic (66.2%)

| Game | Messages |
|------|----------|
| CS:GO | 3,878 |
| Rainbow Six Siege | 537 |
| PUBG | 325 |
| Call of Duty | 144 |
| Rocket League | 80 |

### Columns

| Column | Description |
|--------|-------------|
| `message` | Raw chat message text |
| `game` | Game the message was collected from |
| `label` | `1` = toxic, `0` = non-toxic |

## Annotation

Messages were independently labeled by two annotators using a binary scheme:
- **Toxic (1):** Direct insults, slurs, threats, and targeted harassment
- **Non-toxic (0):** Neutral commentary and general viewer chat

Messages where annotators disagreed were removed. Only messages with full consensus were retained.

## Paper

> Mudabbir Hussain, Abida Tasnim Maria, and Md Shamihul Islam Khan Limon.
> **"Real-Time Detection of Toxic and Hate Speech in Esports Live Chat: A Comparative Study of Machine Learning and Deep Learning Approaches"**
> *(under review)*
