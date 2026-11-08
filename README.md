# Denysochek Umbrel Community App Store

Кастомний репозиторій додатків (Community App Store) для **UmbrelOS**.

## 📦 Доступні додатки:
- **Mono Actual Sync** (`denysochek-mono-actual-sync`) — синхронізація транзакцій Monobank у ваш сервер Actual Budget з підтримкою української мови та актуальних версій Actual Budget API.

---

## 🚀 Як додати цей магазин у свій Umbrel:

### Через веб-інтерфейс Umbrel:
1. Відкрийте **App Store** у вашому Umbrel.
2. Натисніть на іконку **⋯** (три крапки у верхньому правому кутку біля пошуку) і виберіть **Community App Stores**.
3. У поле **URL** вставте посилання на цей репозиторій:
   ```text
   https://github.com/denysochek/umbrel-community-app-store
   ```
4. Натисніть **Add**.
5. Тепер додаток **Mono Actual Sync** зʼявиться у вашому App Store — встановіть його в 1 клік!

### Через термінал (SSH):
```bash
sudo ~/umbrel/scripts/repo add https://github.com/denysochek/umbrel-community-app-store.git
sudo ~/umbrel/scripts/repo update
sudo ~/umbrel/scripts/app install denysochek-mono-actual-sync
```
