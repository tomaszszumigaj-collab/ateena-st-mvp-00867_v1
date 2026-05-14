ATEENA MVP 8.6.7 — Cloud fix deploy package

Zmiany:
- requirements.txt używa opencv-contrib-python-headless==4.10.0.84
- dodano packages.txt: libgl1, libglib2.0-0
- przy deployu w Streamlit ustaw Python 3.12 w Advanced settings
- jeśli wcześniej app była wdrożona na złej wersji Pythona lub z nieudanym buildem, zrób nową aplikację albo usuń starą i wdroż ponownie
