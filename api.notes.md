# API Sprint Notes

## Day 1 — Errors fixed
- CommandNotFoundException → program not installed or not on PATH. Install it, then reopen the terminal.
- Chain of errors → fix the FIRST one; the rest are symptoms.
- PSSecurityException → execution policy blocking scripts. Set-ExecutionPolicy -Scope CurrentUser RemoteSigned.