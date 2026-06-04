# Gridlock Hackathon 2.0 — Traffic Demand Prediction

HackerEarth solution: spatiotemporal lookup on `(geohash, day, timestamp)` for day 49.

## Source package

Download or extract **`gridlock_source_submission.zip`** — contains:

- `approach.txt` — methodology and tools
- `predict.py` — builds `submission.csv`
- `requirements.txt`
- `README.txt`

## Run locally

```bash
pip install -r requirements.txt
python predict.py --train <your_training.csv> --test test.csv --out submission.csv
```

Training CSV must include `geohash` (or `geohash6`), `day`, `timestamp`, and `demand`.

## Repo

https://github.com/Bannysukumar/Gridlock-Hackathon-2.0
