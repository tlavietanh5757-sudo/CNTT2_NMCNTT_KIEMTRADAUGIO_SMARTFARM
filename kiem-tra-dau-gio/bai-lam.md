# Bai_kiem_tra_dau_gio_SmartFarm
## Hệ Thống Giám Sát Trạm Cảm Biến Nông Trại (SmartFarm Monitor)


  **[Chức năng 1] Khởi tạo “căn cứ số” (Terminal):**
  Dòng lệnh duy nhất trong PowerShell để tạo thư mục gốc smartfarm-system cùng 4 thư mục con: docs, scripts, data, backup (đúng như hình) là: 
  `mkdir -p smartfarm-system/docs/script/data/backup`

  **[Chức năng 2] Robot lọc log tự động (auto_report.ps1):**

  Tại thư mục script: touch auto_report.ps1 
  Tạo tiêu đề báo cáo: echo "BAO CAO SU CO ngay27/10 7:15" >> bao-cao-su-co.txt
        cat loi-he-thong.log | grep "ERROR" >> bao-cao-su-co.txt
**[Chức năng 4] Tài liệu README.md (đặt trong docs/):**


