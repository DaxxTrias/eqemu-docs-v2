# char_create_combinations

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYWxsb2NhdGlvbl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgfVxuICAgIGNoYXJfY3JlYXRlX3BvaW50X2FsbG9jYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyBjaGFyX2NyZWF0ZV9wb2ludF9hbGxvY2F0aW9ucyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYWxsb2NhdGlvbl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgfVxuICAgIGNoYXJfY3JlYXRlX3BvaW50X2FsbG9jYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyBjaGFyX2NyZWF0ZV9wb2ludF9hbGxvY2F0aW9ucyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgYWxsb2NhdGlvbl9pZFxuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgfVxuICAgIGNoYXJfY3JlYXRlX3BvaW50X2FsbG9jYXRpb25zIHtcbiAgICAgICAgaW50dW5zaWduZWQgaWRcbiAgICB9XG4gICAgem9uZSB7XG4gICAgICAgIGludCB6b25laWRudW1iZXJcbiAgICAgICAgdmFyY2hhciBzaG9ydF9uYW1lXG4gICAgICAgIHRpbnlpbnR1bnNpZ25lZCB2ZXJzaW9uXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc1xuICAgICAgICB2YXJjaGFyIGNvbnRlbnRfZmxhZ3NfZGlzYWJsZWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyBjaGFyX2NyZWF0ZV9wb2ludF9hbGxvY2F0aW9ucyA6IFwiT25lLXRvLU9uZVwiXG4gICAgY2hhcl9jcmVhdGVfY29tYmluYXRpb25zIHx8LS1veyB6b25lIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | allocation_id | [char_create_point_allocations](../../schema/characters/char_create_point_allocations.md) | id |
| One-to-One | start_zone | [zone](../../schema/zone/zone.md) | zoneidnumber |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| allocation_id | int | [Allocation Identifier](char_create_point_allocations.md) |
| race | int | [Race](../../../../server/npc/race-list) |
| class | int | [Class](../../../../server/player/class-list) |
| deity | int | [Deity](../../../../server/player/deity-list) |
| start_zone | int | [Start Zone Identifier](../../../../server/zones/zone-list) |
| expansions_req | int | [Expansions Required](../../../../server/operation/expansion-bitmasks) |

