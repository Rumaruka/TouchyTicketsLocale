# TouchyTicketsLocale
The localization for my mobile idle game Touchy Tickets.

If you're interested in localizing Touchy Tickets for any other language, please create a pull request with your localization. The file names should be `Localization.ab.json`, `News.ab.json`, `NumberFormat.ab.json5` and `StoreDescription.ab.md`, where `ab` is the [two-letter ISO language name](https://www.loc.gov/standards/iso639-2/php/code_list.php) of your language.

Please note the following when localizing:
- Any JSON keys (`"Key": "Value"`) should **not** be edited.
- Anything enclosed in `<>` should **not** be edited, since these tags represent images, colors and other text formatting settings.
- `NumberFormat` contains formatting info that determines how big numbers look in the game. In this file, it is only necessary to modify the single letter after the formatting info for each line. For example, the German word for "billions" is "Milliarden", meaning the German version reads `"0,,,.00 Mr"` instead of `"0,,,.00 B"`.
- The section titles in `StoreDescription` don't need to be translated, since I basically just copy-paste the content into the store pages. It's just nicer to look at this way.
- Translations can be loose. We're localizing, not just translating. For example, if a news joke doesn't work in your language for whatever reason, you can pick a different joke or paraphrase it.