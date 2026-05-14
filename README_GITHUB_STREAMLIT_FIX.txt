ATEENA MVP 8.6.7 — deploy-ready fix

WAŻNE:
1. Na Streamlit Community Cloud ustaw PYTHON 3.12 w Advanced settings.
2. Jeśli obecna appka jest już wdrożona na innym Pythonie, musisz ją usunąć i wdrożyć ponownie.
3. Ten pakiet pinuje MediaPipe do 0.10.35.

Dlaczego:
- w requirements.txt MediaPipe jest instalowany tylko dla Python < 3.13,
- brak MediaPipe powoduje fallback prior only.

Main file path:
app.py
