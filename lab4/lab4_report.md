University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FTMI]
Course: [Cloud platforms as the basis of technology entrepreneurship]([https://](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/)) 
Year: 2025
Group: U4125
Author: Filianin Ivan Victorovich
Lab: Lab4
Date of create: 03. 05. 2025
Date of finished: -

Итак, GiftGuruGiftGuru — это веб‑сервис, который принимает параметры получателя подарка (возраст, интерес, повод, бюджет) и запрашивает у LLM персональные идеи подарков. 

![image](https://github.com/user-attachments/assets/b00c9c18-7b8f-42d4-bbbe-08a28fe72c6d)

MVP
Компоненты: Cloud Run · Vertex AI (Gemini Pro) · Firestore · Cloud Storage · Cloud Logging.
![Cost MVP](https://github.com/user-attachments/assets/0ef5178e-e4cf-4971-a06e-b0143930aa80)

Тест с партнёрами
Компоненты: Cloud Run (2 vCPU, min‑inst=1) · Vertex AI (PaLM‑2 Text‑Bison) · Cloud SQL · Firestore · Pub/Sub · Artifact Registry · Cloud Build · Cloud Storage.
![Cost Partn](https://github.com/user-attachments/assets/8782d067-a4c8-40bc-aa6a-80946079886f)

Продакшн
Компоненты: Cloud LB + Cloud Armor · Cloud Run (2 vCPU, 50 M req) · Vertex AI (Text‑Bison) · Cloud SQL (n2‑custom 2 vCPU / 8 GB) · Memorystore (1 shard) · Cloud CDN · Cloud Logging.
![Cost Prod](https://github.com/user-attachments/assets/014b2dc3-b8da-4a34-a3db-d5e9a03a82a1)

Расходы растут от $1.6 (учебный MVP) до $56 (пилот с партнёрами) и $358 (продакшн‑система).
