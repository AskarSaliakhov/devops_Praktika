`Задание`:
Изучить `Gitlab CI` или `github actions`, с помощью него автоматизировать сборку собственного приложения и упаковку в контейнер(ы). Добавить телеграмм бота для отправки уведомлений о триггере и/или процессе/результатах сборки.

*Решение*
`CI/CD` запускается каждый раз при `git push` или `pull request`

**Cборка**
- Автоматическая: `CI/CD` запускается каждый раз при `git push` или `pull request`
- Ручная: скрипты: `build.sh` и `deploy.sh.`

**Скриншоты**

____________________________________


**Каждый раз при сборке**

<img width="369" alt="devops_tg" src="https://github.com/user-attachments/assets/259eef68-d916-4d86-aad2-38d066bad856">

<img width="944" alt="dockerhub" src="https://github.com/user-attachments/assets/a4d3544b-aad1-489a-8827-0ede25116adc">
<img width="949" alt="github" src="https://github.com/user-attachments/assets/ff473ffa-1c86-4fa4-b977-a706641c0d51">

**Repositiry secrets**
- PASSWORD
- USERNAME
- TELEGRAM_BOT_TOKEN
- TELEGRAM_CHAT_ID
<img width="926" alt="github-secrets" src="https://github.com/user-attachments/assets/6e44db6c-6d6f-4159-b982-171c763830d5">
<img width="951" alt="details" src="https://github.com/user-attachments/assets/2d4290b6-9d99-4b94-8531-392af3b1a96c">
