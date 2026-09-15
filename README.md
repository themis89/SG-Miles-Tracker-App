# SG-Miles-Tracker-App
track credit miles gained from spendings

## KanaSensei

`kana-trainer.html` is a standalone hiragana/katakana drill trainer — open it directly in a browser, no build step. A 5-minute timed sprint (hidden timer by default, toggleable) quizzes hiragana, katakana, or both against 4-choice romaji options, with per-character mnemonics shown after each answer, real pronunciation audio, and a Sensei-style grade on the report card. A "Confusable Traps" drill and reference guide covers commonly-confused lookalike pairs (シ/ツ/ソ/ン, さ/ち, ぬ/め, る/ろ, ね/れ/わ). The header's day toggle switches the dashboard between "Routine" and "Surprise" mode to preview both flows.

Progress persists locally in the browser (localStorage): every completed drill is logged to a **Test History** page (linked from the dashboard), and the dashboard's "Standard Radar" — accuracy, last surprise-test score, characters mastered, most-flagged characters — is computed live from that history rather than shown as fixed demo values.

Note: "Surprise" mode is still a manual toggle rather than an automatic day-based trigger.