# edsm_log_bridge
publishes the log entries in players journal, generated by elite dangerous to database

# build as exe
using pyinstaller:
pyinstaller --clean -n EDWatcher --onefile --add-binary icon.ico;. --additional-hooks-dir hooks --windowed --icon icon.ico edsm_log_bridge_daemon.py
