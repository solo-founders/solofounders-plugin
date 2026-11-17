# Connectors

## How tool references work

Plugin files use `~~category` as a placeholder for whatever tool you connect in that category. The plugin works with no connectors at all — skills fall back to asking you questions. Connecting tools lets them pull context automatically.

## Connectors for this plugin

| Category | Placeholder | Used by | Options |
|----------|-------------|---------|---------|
| Calendar | `~~calendar` | solo-weekly | Google Calendar, Outlook |
| Email | `~~email` | fundraise-solo, solo-weekly | Gmail, Outlook, Superhuman |
| CRM | `~~CRM` | fundraise-solo | Attio, HubSpot, Affinity, Folk, Notion |
| Project tracker | `~~project tracker` | solo-weekly | Linear, Asana, Notion, GitHub Issues |
| Notes | `~~notes` | solo-weekly | Notion, Google Docs, Obsidian |
| Meeting notes | `~~meeting notes` | solo-weekly | Granola, Fireflies, Otter |

Email drafts are always created as drafts. Calendar events are created only after you confirm.
