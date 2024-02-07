# tradeskill_recipe

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdHJhZGVza2lsbF9yZWNpcGUge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBjb250ZW50X2ZsYWdzIHtcbiAgICAgICAgdmFyY2hhciBmbGFnX25hbWVcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgICAgIGludCByZWNpcGVfaWRcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGUgfHwtLW97IGNvbnRlbnRfZmxhZ3MgOiBcIk9uZS10by1PbmVcIlxuICAgIHRyYWRlc2tpbGxfcmVjaXBlIHx8LS1veyBjb250ZW50X2ZsYWdzIDogXCJPbmUtdG8tT25lXCJcbiAgICB0cmFkZXNraWxsX3JlY2lwZSB8fC0tb3sgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdHJhZGVza2lsbF9yZWNpcGUge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBjb250ZW50X2ZsYWdzIHtcbiAgICAgICAgdmFyY2hhciBmbGFnX25hbWVcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgICAgIGludCByZWNpcGVfaWRcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGUgfHwtLW97IGNvbnRlbnRfZmxhZ3MgOiBcIk9uZS10by1PbmVcIlxuICAgIHRyYWRlc2tpbGxfcmVjaXBlIHx8LS1veyBjb250ZW50X2ZsYWdzIDogXCJPbmUtdG8tT25lXCJcbiAgICB0cmFkZXNraWxsX3JlY2lwZSB8fC0tb3sgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgdHJhZGVza2lsbF9yZWNpcGUge1xuICAgICAgICBpbnQgaWRcbiAgICAgICAgdmFyY2hhciBjb250ZW50X2ZsYWdzXG4gICAgICAgIHZhcmNoYXIgY29udGVudF9mbGFnc19kaXNhYmxlZFxuICAgIH1cbiAgICBjb250ZW50X2ZsYWdzIHtcbiAgICAgICAgdmFyY2hhciBmbGFnX25hbWVcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyB7XG4gICAgICAgIGludCBpdGVtX2lkXG4gICAgICAgIGludCByZWNpcGVfaWRcbiAgICB9XG4gICAgdHJhZGVza2lsbF9yZWNpcGUgfHwtLW97IGNvbnRlbnRfZmxhZ3MgOiBcIk9uZS10by1PbmVcIlxuICAgIHRyYWRlc2tpbGxfcmVjaXBlIHx8LS1veyBjb250ZW50X2ZsYWdzIDogXCJPbmUtdG8tT25lXCJcbiAgICB0cmFkZXNraWxsX3JlY2lwZSB8fC0tb3sgdHJhZGVza2lsbF9yZWNpcGVfZW50cmllcyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | content_flags | [content_flags](../../schema/flagging/content_flags.md) | flag_name |
| One-to-One | content_flags_disabled | [content_flags](../../schema/flagging/content_flags.md) | flag_name |
| Has-Many | id | [tradeskill_recipe_entries](../../schema/tradeskills/tradeskill_recipe_entries.md) | recipe_id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Unique Tradeskill Recipe Identifier |
| name | varchar | Recipe Name |
| tradeskill | smallint | [Tradeskill](../../../../server/player/skills) |
| skillneeded | smallint | Skill Level Needed |
| trivial | smallint | Trivial Skill Level |
| nofail | tinyint | No Fail: 0 = False, 1 = True |
| replace_container | tinyint | Replace Container: 0 = False, 1 = True |
| notes | tinytext | Notes |
| must_learn | tinyint | Must Learn: 0 = False, 1 = True |
| learned_by_item_id | int |  |
| quest | tinyint | Quest Controlled: 0 = False, 1 = True |
| enabled | tinyint | Enabled: 0 = False, 1 = True |
| min_expansion | tinyint | [Minimum Expansion](../../../../server/operation/expansion-list) |
| max_expansion | tinyint | [Maximum Expansion](../../../../server/operation/expansion-list) |
| content_flags | varchar | Content Flags Required to be Enabled |
| content_flags_disabled | varchar | Content Flags Required to be Disabled |

