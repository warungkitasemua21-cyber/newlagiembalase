Versi ini menggunakan arsitektur asli Dashboard Piutang SBCR V2.

Dipertahankan:
- Login session asli
- APP_SESSION_SECRET
- ADMIN_USERNAME / ADMIN_PASSWORD
- Logout
- Upload server
- Penyimpanan online

Yang diganti:
- Data Performance Piutang -> Piutang Embalase
- Resume Agen
- Detail Faktur Embalase
- Histori Agen

Jangan mengganti modul login dengan login React lokal karena akan merusak session.
