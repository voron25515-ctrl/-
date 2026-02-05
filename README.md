# -brawl-like/
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── client/
│   ├── main.py
│   ├── menu.py
│   ├── settings.py
│   ├── game_state.py
│   ├── modes/
│   │   ├── showdown.py
│   │   └── gemgrab.py
│   ├── engine/
│   │   ├── player.py
│   │   ├── bot.py
│   │   ├── ai.py
│   │   ├── bullet.py
│   │   ├── map.py
│   │   ├── super.py
│   │   ├── progression.py
│   │   ├── shop.py
│   │   └── save.py
│   ├── brawlers/
│   │   └── data.py
│   └── assets/
│       ├── sprites/
│       └── sounds/
│
├── server/
│   ├── server.py
│   ├── match.py
│   ├── team.py
│   ├── auth.py
│   ├── modes/
│   │   └── gemgrab.py
│   └── saves/
│
├── android/
│   └── buildozer.spec
│
└── docs/
    ├── architecture.md
    ├── roadmap.md
    └── gameplay.md
