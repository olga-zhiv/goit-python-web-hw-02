# 1. Базовий образ з Python
FROM python:3.13.3

# 2. Робоча директорія в контейнері
WORKDIR /project

# 3. Копіюємо файли у контейнер
COPY requirements.txt .
COPY assistant.py .

# 4. Встановлюємо залежності
RUN pip install --no-cache-dir -r requirements.txt

# 5. Команда за замовчуванням — запускає застосунок
CMD ["python", "assistant.py"]