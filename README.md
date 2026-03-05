# Custom Protestant Calendar (2026–2037)

An `.ics` calendar file containing key Protestant liturgical and observance dates from 2026 through 2037, suitable for import into any calendar application that supports the iCalendar format.

## Included Holidays

The following events are included for each year in the range:

| Event | Description |
|---|---|
| **Ash Wednesday** | Marks the beginning of Lent, 46 days before Easter |
| **Palm Sunday** | The Sunday before Easter, commemorating Jesus' entry into Jerusalem |
| **Good Friday** | Commemorates the crucifixion of Jesus |
| **Ascension Day** | Observed 39 days after Easter Sunday |
| **Pentecost** | Celebrated 49 days after Easter Sunday |
| **Reformation Day** | October 31 — commemorates Martin Luther's 1517 theses |
| **First Sunday of Advent** | Marks the beginning of the Advent season |

> **Note:** Easter, Christmas, and St. Patrick's Day are intentionally excluded, as these are already present in most standard US calendar applications.

## Usage

### Import into a Calendar App

1. Download `holidays.ics`
2. Open your calendar application (Google Calendar, Apple Calendar, Proton Calendar, Outlook, etc.)
3. Use the import or "Add calendar from file" feature to load the `.ics` file

### Proton Calendar Notes

Proton Calendar has the following limitations to be aware of:
- Maximum file size: 10 MB
- Maximum events per import: 15,000
- Date range support appears to cap around 2040

This file is sized well within those constraints.

## Coverage

Years covered: **2026, 2027, 2028, 2029, 2030, 2031, 2032, 2033, 2034, 2035, 2036, 2037**

7 events × 12 years = **84 total events**

## Format

The file follows the [iCalendar (RFC 5545)](https://datatracker.ietf.org/doc/html/rfc5545) standard:

- `CALSCALE:GREGORIAN`
- All events are all-day (`VALUE=DATE`)
- Timezone reference: `America/New_York`
- Each event has a unique `UID` for deduplication on re-import

