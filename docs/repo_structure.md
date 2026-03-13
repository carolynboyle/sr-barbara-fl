sr-barbara-flutter/
├── pubspec.yaml
├── lib/
│   ├── main.dart
│   ├── models/
│   │   ├── sentence.dart
│   │   ├── player.dart
│   │   └── game_session.dart
│   ├── services/
│   │   ├── database.dart (SQLite init & queries)
│   │   └── sentence_service.dart (load from sentences.sqlite)
│   ├── screens/
│   │   └── game_screen.dart
│   ├── widgets/
│   │   ├── sr_barbara.dart (animated image)
│   │   ├── diagram_painter.dart (CustomPaint)
│   │   └── pos_popup.dart
│   └── state/
│       └── game_state.dart (or use Provider/Riverpod)
├── assets/
│   ├── images/
│   │   └── sr_barbara.png
│   └── data/
│       └── sentences.sqlite (bundled)
├── scripts/
│   └── export_sentences.py (query PostgreSQL → sentences.sqlite)
└── README.md