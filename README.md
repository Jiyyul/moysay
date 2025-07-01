moysay/
└── backend/
    ├── app.py                     ← 메인 서버 실행 파일
    ├── routes/
    │   ├── __init__.py            ← Blueprint 등록
    │   ├── schedule_routes.py     ← /submit, /schedules
    │   └── user_routes.py         ← (필요 시) 사용자 관련
    ├── models/
    │   ├── __init__.py
    │   └── schedule_model.py      ← Pydantic 또는 dict
    ├── services/
    │   └── schedule_logic.py      ← 시간 겹침 계산 등
    ├── utils/
    │   └── file_io.py             ← JSON 읽고 쓰기
    ├── data/
    │   └── schedule.json
    ├── moysay_venv
    └── requirements.txt
