# خطوات رفع المشروع على GitHub

1. أنشئ Repository جديد باسم:

```text
fixed-assets-erp-pro
```

2. اختَر Private.

3. افتح Terminal داخل مجلد المشروع ثم نفذ:

```bash
git init
git add .
git commit -m "Initial fixed assets ERP pro version"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/fixed-assets-erp-pro.git
git push -u origin main
```

4. بعد الرفع، تأكد أن ملف `.env` غير موجود في GitHub.
