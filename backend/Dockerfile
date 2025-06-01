# از یک تصویر رسمی پایتون استفاده کن
FROM python:3.10-slim

# دایرکتوری کاری در کانتینر
WORKDIR /app

# کپی کردن فایل‌ها
COPY . .

# نصب وابستگی‌ها
RUN pip install --no-cache-dir -r requirements.txt

# پورت برای اجرای Flask
EXPOSE 5000

# اجرای برنامه
CMD ["python", "main.py"]
