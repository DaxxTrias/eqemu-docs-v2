# data_buckets

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZGF0YV9idWNrZXRzIHtcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgbWVyY2hhbnRsaXN0IHtcbiAgICAgICAgaW50IG1lcmNoYW50aWRcbiAgICAgICAgaW50IGl0ZW1cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgICAgICB2YXJjaGFyIGJ1Y2tldF9uYW1lXG4gICAgICAgIHZhcmNoYXIgbWVyY2hhbnRfaWRcbiAgICB9XG4gICAgc3BlbGxfYnVja2V0cyB7XG4gICAgICAgIGJpZ2ludHVuc2lnbmVkIHNwZWxsaWRcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgZGF0YV9idWNrZXRzIHx8LS1veyBtZXJjaGFudGxpc3QgOiBcIkhhcy1NYW55XCJcbiAgICBkYXRhX2J1Y2tldHMgfHwtLW97IHNwZWxsX2J1Y2tldHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZGF0YV9idWNrZXRzIHtcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgbWVyY2hhbnRsaXN0IHtcbiAgICAgICAgaW50IG1lcmNoYW50aWRcbiAgICAgICAgaW50IGl0ZW1cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgICAgICB2YXJjaGFyIGJ1Y2tldF9uYW1lXG4gICAgICAgIHZhcmNoYXIgbWVyY2hhbnRfaWRcbiAgICB9XG4gICAgc3BlbGxfYnVja2V0cyB7XG4gICAgICAgIGJpZ2ludHVuc2lnbmVkIHNwZWxsaWRcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgZGF0YV9idWNrZXRzIHx8LS1veyBtZXJjaGFudGxpc3QgOiBcIkhhcy1NYW55XCJcbiAgICBkYXRhX2J1Y2tldHMgfHwtLW97IHNwZWxsX2J1Y2tldHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgZGF0YV9idWNrZXRzIHtcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgbWVyY2hhbnRsaXN0IHtcbiAgICAgICAgaW50IG1lcmNoYW50aWRcbiAgICAgICAgaW50IGl0ZW1cbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgICAgICB2YXJjaGFyIGJ1Y2tldF9uYW1lXG4gICAgICAgIHZhcmNoYXIgbWVyY2hhbnRfaWRcbiAgICB9XG4gICAgc3BlbGxfYnVja2V0cyB7XG4gICAgICAgIGJpZ2ludHVuc2lnbmVkIHNwZWxsaWRcbiAgICAgICAgdmFyY2hhciBrZXlcbiAgICB9XG4gICAgZGF0YV9idWNrZXRzIHx8LS1veyBtZXJjaGFudGxpc3QgOiBcIkhhcy1NYW55XCJcbiAgICBkYXRhX2J1Y2tldHMgfHwtLW97IHNwZWxsX2J1Y2tldHMgOiBcIkhhcy1NYW55XCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | key | [merchantlist](../../schema/merchants/merchantlist.md) | bucket_name |
| Has-Many | key | [spell_buckets](../../schema/spells/spell_buckets.md) | key |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | bigint | Unique Data Bucket Identifier |
| key | varchar | Key |
| value | text | Value |
| expires | int | Expiration UNIX Timestamp |
| character_id | bigint |  |
| npc_id | bigint |  |
| bot_id | bigint |  |

