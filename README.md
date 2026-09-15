# SG-Miles-Tracker-App
track credit miles gained from spendings

## KanaSensei

`kana-trainer.html` is a standalone hiragana/katakana drill trainer — open it directly in a browser, no build step. A 5-minute timed sprint (hidden timer by default, toggleable) quizzes hiragana, katakana, or both against 4-choice romaji options, with per-character mnemonics shown after each answer and a Sensei-style grade on the report card. A "Confusable Traps" drill and reference guide covers commonly-confused lookalike pairs (シ/ツ/ソ/ン, さ/ち, ぬ/め, る/ろ, ね/れ/わ). The header's day toggle switches the dashboard between "Routine" and "Surprise" mode to preview both flows.

Note: this build is stateless — nothing persists between page loads (dashboard stats are fixed demo values, and "Surprise" mode is a manual toggle rather than an automatic day-based trigger). Ask for real progress tracking and auto-scheduled surprise tests if you want that wired in.