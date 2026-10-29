# Get More Fans · Open creator data

Aggregated, anonymous data on what performs on the social media of the content creators who use
[Get More Fans](https://getmorefans.app/?utm_source=github&utm_campaign=trafico-datos): best posting times (creators' local time, 2-hour blocks), formats that perform best and
rising hashtags. Updated every week.

## How to read it

- `median_score`: median performance of each piece against its own account's average (1.0 = that account's average).
  `lift_pct` is the same as a percentage.
- Every row pools at least 5 different accounts and 20 pieces, and no single account is more than
  40% of a row. `accounts` and `pieces` are rounded down (to 5 and 10). Nobody can be identified.
- `weekly/<year>-W<week>`: the 4 weeks before that Monday. `monthly/<year-month>`: the monthly report.
- `section`: `hour_block`, `format`, `weekday_<0-6>` (0 = Monday) or `hashtag`; `growth_pct`: change in usage share
  against the previous period.

## Files

- `latest.json` · `latest.csv`: the most recent week.
- (todavía ninguno)

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use it, quote it, chart it. Attribution: **«Data: Get More Fans»** with a link to
https://getmorefans.app/?utm_source=github&utm_campaign=trafico-datos

---

**ES** · Datos agregados y anónimos de lo que rinde en las redes de las creadoras de Get More Fans. Licencia CC BY 4.0:
citá «Datos: Get More Fans» con link a la web.

**PT** · Dados agregados e anônimos do que rende nas redes das criadoras da Get More Fans. Licença CC BY 4.0: cite
«Dados: Get More Fans» com link para o site.
