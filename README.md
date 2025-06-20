# Monitoring VM Server dengan Zabbix

Repositori ini berisi dokumentasi dan konfigurasi untuk monitoring performa server virtual (VM) menggunakan Zabbix.

## 🌐 Server Monitoring

- **Monitoring Tool**: Zabbix
- **Zabbix Server IP**: `18.138.33.154`
- **Akses Web UI**: [http://18.138.33.154/zabbix](http://18.138.33.154/zabbix)

## 🖥️ VM yang Dimonitor

Server VM yang dimonitor mencakup parameter-parameter berikut:

| Parameter         | Keterangan                   |
|------------------|------------------------------|
| CPU Usage         | Realtime dan historis        |
| Memory Usage      | Total, used, available       |
| Disk Usage        | Kapasitas dan pemakaian I/O |
| Network Traffic   | Incoming dan outgoing rate   |
| Ping Response     | Ketersediaan dan latency     |

Contoh hasil monitoring:
```bash
CPU Usage        : 55%
Memory Used      : 3.2 GB / 8 GB
Disk Used        : 70% (40 GB / 60 GB)
Network In/Out   : 500 KBps / 200 KBps
Availability     : Online
