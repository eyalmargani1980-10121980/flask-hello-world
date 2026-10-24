# שימוש באימג' בסיס של Python
FROM python:3.9-slim

# הגדרת תיקיית העבודה בתוך הקונטיינר
WORKDIR /app

# התקנת הספרייה Flask
RUN pip install --no-cache-dir flask

# העתקת קובץ האפליקציה לתוך הקונטיינר
COPY app.py .

# חשיפת הפורט שבו האפליקציה רצה
EXPOSE 5000

# פקודת ההרצה של האפליקציה
CMD ["python", "app.py"]
