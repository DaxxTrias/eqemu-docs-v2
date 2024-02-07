# bot_heal_rotation_targets

!!! info
	This page was last generated 2024.02.07

## Relationship Diagram(s)

[Diagram Edit](https://mermaid.live/edit#eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB7XG4gICAgICAgIHZhcmNoYXIgaGVhbF9yb3RhdGlvbl9pbmRleFxuICAgIH1cbiAgICBib3RfaGVhbF9yb3RhdGlvbnMge1xuICAgICAgICB2YXJjaGFyIGJvdF9pZFxuICAgICAgICB2YXJjaGFyIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB8fC0tb3sgYm90X2hlYWxfcm90YXRpb25zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams-edit}

[![](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB7XG4gICAgICAgIHZhcmNoYXIgaGVhbF9yb3RhdGlvbl9pbmRleFxuICAgIH1cbiAgICBib3RfaGVhbF9yb3RhdGlvbnMge1xuICAgICAgICB2YXJjaGFyIGJvdF9pZFxuICAgICAgICB2YXJjaGFyIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB8fC0tb3sgYm90X2hlYWxfcm90YXRpb25zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=)](https://mermaid.ink/img/eyJjb2RlIjoiZXJEaWFncmFtXG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB7XG4gICAgICAgIHZhcmNoYXIgaGVhbF9yb3RhdGlvbl9pbmRleFxuICAgIH1cbiAgICBib3RfaGVhbF9yb3RhdGlvbnMge1xuICAgICAgICB2YXJjaGFyIGJvdF9pZFxuICAgICAgICB2YXJjaGFyIGhlYWxfcm90YXRpb25faW5kZXhcbiAgICB9XG4gICAgYm90X2hlYWxfcm90YXRpb25fdGFyZ2V0cyB8fC0tb3sgYm90X2hlYWxfcm90YXRpb25zIDogXCJPbmUtdG8tT25lXCJcblxuIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjp0cnVlLCJhdXRvU3luYyI6dHJ1ZSwidXBkYXRlRGlhZ3JhbSI6dHJ1ZX0=){target=diagrams}


## Relationships

| Relationship Type | Local Key | Relates to Table | Foreign Key |
| :--- | :--- | :--- | :--- |
| One-to-One | heal_rotation_index | [bot_heal_rotations](../../schema/bots/bot_heal_rotations.md) | heal_rotation_index |


## Schema

| Column | Data Type | Description |
| :--- | :--- | :--- |
| target_index | int | Unique Bot Heal Rotation Target Identifier |
| heal_rotation_index | int | [Heal Rotation Identifier](bot_heal_rotations.md) |
| target_name | varchar | Target Name |

