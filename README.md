# campus-network-unibi
Project Campus 2 Unibi
<img width="1919" height="743" alt="Image" src="https://github.com/user-attachments/assets/4ff74b5b-102d-41bd-9d14-ae0a30a64182" />

## Deskripsi
Project ini merupakan simulasi desain jaringan kampus Universitas Informatika dan Bisnis Indonesia
menggunakan Cisco Packet Tracer. Jaringan dirancang dengan segmentasi VLAN, subnetting,
serta mekanisme redundancy untuk meningkatkan keandalan dan keamanan jaringan.

## Tujuan Project
- Menerapkan konsep VLAN dan subnetting
- Memisahkan jaringan berdasarkan fungsi dan unit
- Mengimplementasikan core dan access switch
- Menerapkan server, wireless, dan IP phone
- Mensimulasikan jaringan kampus skala menengah

## Topologi Jaringan
Topologi jaringan menggunakan model hirarki yang terdiri dari:
- Router Core dan Router Backup
- Core Switch sebagai pusat distribusi
- Access Switch untuk setiap area/unit
- Server (DNS & Link)
- End device: PC, Laptop, Printer, Smartphone, IP Phone, Access Point, Camera

## VLAN & Subnet Configuration
| VLAN | Nama | Subnet | Keterangan |
|----:|------|--------|------------|
| 10 | Server | /29 | Server Link & DNS |
| 20 | Dosen | /28 | Area Dosen |
| 30 | Resepsionis | /28 | Front Office |
| 40 | Kantor | /24 | Administrasi |
| 50 | WiFi | /24 | Akses Wireless |
| 60 | CCTV | /28 | Kamera Keamanan |
| 70 | IP Phone | /29 | Voice Network |
| 80 | Khusus Lantai 2 | /25 | Area Lantai 2 |

## Fitur Jaringan
- VLAN Trunking
- Inter-VLAN Routing
- Subnetting IPv4
- Standby / Backup Router
- Wireless Access Point
- IP Phone
- CCTV Network

## Tools & Software
- Cisco Packet Tracer
- GitHub
- Laptop / PC

## Author
Nama : Muhamad Dhaffa  
Prodi : Informatika  
Universitas : Universitas Informatika dan Bisnis Indonesia

