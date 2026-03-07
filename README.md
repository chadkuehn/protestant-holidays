# Curated Events

Two `.ics` calendar files covering key Christian and Jewish observance dates from 2026 through 2037, suitable for import into any calendar application that supports the iCalendar format.

## Calendars

### christian-curated.ics

Key Protestant liturgical dates. The following events are included for each year in the range:

| Event                      | Description                                                         |
| -------------------------- | ------------------------------------------------------------------- |
| **Ash Wednesday**          | Marks the beginning of Lent, 46 days before Easter                  |
| **Holy Week**              | The week from Palm Sunday through Holy Saturday                     |
| **Palm Sunday**            | The Sunday before Easter, commemorating Jesus' entry into Jerusalem |
| **Good Friday**            | Commemorates the crucifixion of Jesus                               |
| **Ascension Day**          | Observed 39 days after Easter Sunday                                |
| **Pentecost**              | Celebrated 49 days after Easter Sunday                              |
| **Reformation Day**        | October 31 — commemorates Martin Luther's 1517 theses               |
| **First Sunday of Advent** | Marks the beginning of the Advent season                            |

> **Note:** Easter (Resurrection Sunday), Christmas, and St. Patrick's Day are intentionally excluded, as these are already present in most standard US calendar applications.

8 events × 12 years = **96 total events**

---

### jewish-curated.ics

Key Jewish feasts and holy days. The following events are included for each year in the range:

| Event                                      | Description                                                                       |
| ------------------------------------------ | --------------------------------------------------------------------------------- |
| **Purim**                                  | Celebrates the deliverance of the Jewish people as recorded in the Book of Esther |
| **Passover / Feast of Unleavened Bread**   | Commemorates the Exodus from Egypt; seven days of unleavened bread                |
| **Shavuot (Feast of Weeks)**               | Celebrates the giving of the Torah at Sinai, 50 days after Passover               |
| **Rosh Hashanah (Feast of Trumpets)**      | The Jewish New Year; begins the ten Days of Awe leading to Yom Kippur             |
| **Yom Kippur (Day of Atonement)**          | The holiest day of the Jewish year — a day of fasting, prayer, and repentance     |
| **Sukkot (Feast of Tabernacles / Booths)** | Seven-day harvest festival commemorating the Israelites' wilderness wandering     |
| **Hanukkah (Feast of Dedication)**         | Eight-day Festival of Lights celebrating the rededication of the Temple (~165 BC) |

7 events × 12 years = **84 total events**

## Coverage

Both calendars cover: **2026, 2027, 2028, 2029, 2030, 2031, 2032, 2033, 2034, 2035, 2036, 2037**

## Usage

### Subscribe via URL

Many calendar apps support subscribing to a calendar via URL, which keeps the calendar in sync automatically:

```
https://chadkuehn.github.io/curated-events/christian-curated.ics
```

```
https://chadkuehn.github.io/curated-events/jewish-curated.ics
```

Use the "Add calendar from URL" or "Subscribe" feature in your app and paste the URL above.

### Import into a Calendar App

1. Download the desired `.ics` file or use the URL above
2. Open your calendar application (Google Calendar, Apple Calendar, Proton Calendar, Outlook, etc.)
3. Use the import or "Add calendar from file" feature to load the `.ics` file

### Proton Calendar Notes

Proton Calendar has the following limitations to be aware of:

- Maximum file size: 10 MB
- Maximum events per import: 15,000
- Date range support appears to cap around 12-13 years out

Both files are sized well within those constraints.

## Format

The files follow the [iCalendar (RFC 5545)](https://datatracker.ietf.org/doc/html/rfc5545) standard:

- `CALSCALE:GREGORIAN`
- All events are all-day (`VALUE=DATE`)
- Timezone reference: `America/Chicago`
- Each event has a unique `UID` for deduplication on re-import
