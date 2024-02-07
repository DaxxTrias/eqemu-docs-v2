# char_create_point_allocations

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgIH1cbiAgICBjaGFyX2NyZWF0ZV9jb21iaW5hdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgICAgIGludHVuc2lnbmVkIGFsbG9jYXRpb25faWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMgfHwtLW97IGNoYXJfY3JlYXRlX2NvbWJpbmF0aW9ucyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgIH1cbiAgICBjaGFyX2NyZWF0ZV9jb21iaW5hdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgICAgIGludHVuc2lnbmVkIGFsbG9jYXRpb25faWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMgfHwtLW97IGNoYXJfY3JlYXRlX2NvbWJpbmF0aW9ucyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBpZFxuICAgIH1cbiAgICBjaGFyX2NyZWF0ZV9jb21iaW5hdGlvbnMge1xuICAgICAgICBpbnR1bnNpZ25lZCBzdGFydF96b25lXG4gICAgICAgIGludHVuc2lnbmVkIGFsbG9jYXRpb25faWRcbiAgICB9XG4gICAgY2hhcl9jcmVhdGVfcG9pbnRfYWxsb2NhdGlvbnMgfHwtLW97IGNoYXJfY3JlYXRlX2NvbWJpbmF0aW9ucyA6IFwiSGFzLU1hbnlcIlxuXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOnRydWUsImF1dG9TeW5jIjp0cnVlLCJ1cGRhdGVEaWFncmFtIjp0cnVlfQ==){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| Has-Many | id | [char_create_combinations](../../schema/characters/char_create_combinations.md) | allocation_id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| id | int | Allocation Identifier |
| base_str | int | Base Strength |
| base_sta | int | Base Stamina |
| base_dex | int | Base Dexterity |
| base_agi | int | Base Agility |
| base_int | int | Base Intelligence |
| base_wis | int | Base Wisdom |
| base_cha | int | Base Charisma |
| alloc_str | int | Allocated Strength |
| alloc_sta | int | Allocated Stamina |
| alloc_dex | int | Allocated Dexterity |
| alloc_agi | int | Allocated Agility |
| alloc_int | int | Allocated Intelligence |
| alloc_wis | int | Allocated Wisdom |
| alloc_cha | int | Allocated Charisma |

