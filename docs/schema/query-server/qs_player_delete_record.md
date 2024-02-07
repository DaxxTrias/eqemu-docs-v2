# qs_player_delete_record

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcXNfcGxheWVyX2RlbGV0ZV9yZWNvcmQge1xuICAgICAgICBpbnQgY2hhcl9pZFxuICAgIH1cbiAgICBjaGFyYWN0ZXJfZGF0YSB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lX2luc3RhbmNlXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgfVxuICAgIHFzX3BsYXllcl9kZWxldGVfcmVjb3JkIHx8LS1veyBjaGFyYWN0ZXJfZGF0YSA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcXNfcGxheWVyX2RlbGV0ZV9yZWNvcmQge1xuICAgICAgICBpbnQgY2hhcl9pZFxuICAgIH1cbiAgICBjaGFyYWN0ZXJfZGF0YSB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lX2luc3RhbmNlXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgfVxuICAgIHFzX3BsYXllcl9kZWxldGVfcmVjb3JkIHx8LS1veyBjaGFyYWN0ZXJfZGF0YSA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgcXNfcGxheWVyX2RlbGV0ZV9yZWNvcmQge1xuICAgICAgICBpbnQgY2hhcl9pZFxuICAgIH1cbiAgICBjaGFyYWN0ZXJfZGF0YSB7XG4gICAgICAgIGludHVuc2lnbmVkIGlkXG4gICAgICAgIHZhcmNoYXIgbmFtZVxuICAgICAgICBpbnR1bnNpZ25lZCB6b25lX2luc3RhbmNlXG4gICAgICAgIGludHVuc2lnbmVkIHpvbmVfaWRcbiAgICAgICAgdmFyY2hhciBuYW5lXG4gICAgfVxuICAgIHFzX3BsYXllcl9kZWxldGVfcmVjb3JkIHx8LS1veyBjaGFyYWN0ZXJfZGF0YSA6IFwiT25lLXRvLU9uZVwiXG5cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6dHJ1ZSwiYXV0b1N5bmMiOnRydWUsInVwZGF0ZURpYWdyYW0iOnRydWV9){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | char_id | [character_data](../../schema/characters/character_data.md) | id |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| delete_id | int | Unique Delete Identifier |
| time | timestamp | Time Timestamp |
| char_id | int | [Character Identifier](../../schema/characters/character_data.md) |
| stack_size | mediumint | Stack Size |
| char_items | mediumint | [Character Items Identifier](../../schema/items/items.md) |

