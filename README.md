# Sistem Monitoring Suhu & Kelembaban (Node-RED)

## Fitur
- Penyimpanan riwayat data sensor & endpoint `GET /api/history`
- Endpoint `PUT /api/threshold` untuk mengubah batas suhu maksimum & memicu peringatan suhu berlebih
- Autentikasi header `x-api-key` pada `PUT /api/threshold`
- Dashboard grafik real-time Chart.js di `/dashboard`
- Pengiriman data real-time melalui WebSocket `/ws/sensor`

## Cara Menjalankan
1. Jalankan Node-RED (`node-red`).
2. Buka editor di `http://localhost:1880` dan import `flows.json` jika diperlukan.
3. Buka dashboard di `http://localhost:1880/dashboard`.