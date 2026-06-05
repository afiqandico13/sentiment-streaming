# Real-time Sentiment Analysis for Bali Tourism

Streaming data komentar wisatawan, analisis sentimen menggunakan IndoBERT, dan dashboard real-time dengan Streamlit.

## Setup

1. Install Redis (lihat instruksi di atas)
2. Jalankan `redis-server`
3. Install dependencies: `pip install -r requirements.txt`
4. Jalankan consumer: `python consumer.py`
5. Jalankan producer: `python producer.py`
6. Jalankan dashboard: `streamlit run dashboard/app.py`

## Tech Stack

- Redis: message broker
- IndoBERT (w11wo/indonesian-roberta-base-sentiment-classifier)
- Streamlit
- SQLite