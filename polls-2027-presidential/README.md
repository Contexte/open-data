# List of polls for the 2027 French presidential election

This dataset lists voting-intention polls for the 2027 French presidential election, collected automatically from each pollster's published notice to the [Commission des sondages](https://www.commission-des-sondages.fr/). It is updated automatically as new polls are added, and covers both the first round (`Premier_Tour`) and the second round (`Second_Tour`).

## Format

One row per candidate, per hypothesis, per round (long format) — a poll testing several second-round match-ups (e.g. Le Pen/Macron, Le Pen/Attal) appears as several rows, one per candidate per match-up.

Columns: `numero_sondage`, `institut`, `commanditaire`, `echantillon`, `date_debut`, `date_fin`, `tour`, `hypothese`, `candidat`, `intention_vote`, `score_min`, `score_max`.

`score_min`/`score_max` give the 95% confidence interval around `intention_vote`, computed from the sample size.

## Files

* [Polls](https://github.com/Contexte/open-data/blob/master/polls-2027-presidential/polls.csv)

## License

The data is published under the [ODbL 1.0 license](https://opendatacommons.org/licenses/odbl/summary/index.html).

## Attribution

No attribution required.

## Contact

For any question, error report or suggestion about this dataset, please use [this form](https://contexte.typeform.com/to/kvhgKz).
