# 📄 Debian Installation Report for IoT, MQTT, Kafka Course

> Students must complete all sections of this form during Debian installation and submit it upon completion.

---

## 🔧 General Information

| Title                  | Value                                               |
| -----------------------| --------------------------------------------------- |
| Full Name              |  Pitpibool Thongchua|
| Student ID              | 6510301016|
| Installation Date      | 11 June 2025|


---

## 🖥️ Device Information

- 💻 **Device Model / Type**: Dell Edge Gateway 5000 

- 🧬 **Firmware Type**:  
  - [ ] UEFI  
  - [x] BIOS  
- 🏷️ **Installation Type**:  
  - [x] Physical PC  
  - [ ] Virtual Machine (VM)

---

## 🗂️ Custom Partitioning

| Partition     | Size   | Filesystem | Mount Point           | Notes              |
|---------------|--------|------------|------------------------|--------------------|
| `/boot`       | 512MB  | ext4       | `/boot`                | For boot loader    |
| `swap`        | 1GB    | swap       | -                      | Swap space         |
| `/` or others |        |            |                        |                    |


|Filesystem    | Size | Used | Avail | Use% | Mounted on  |
|--------------|------|------|-------|------|-------------|
|udev          | 1.9G |    0 |  1.9G |   0% | /dev        |
|tmpfs         | 379M | 776K |  378M |   1% | /run        |
|/dev/sda1     |  29G | 1.5G |   26G |   6% | /           |
|tmpfs         | 1.9G |    0 |  1.9G |   0% | /dev/shm    |
|tmpfs         | 5.0M |    0 |  5.0M |   0% | /run/lock   |
|tmpfs         | 379M |    0 |  379M |   0% | /run/user/1000  |
---

## 🌐 Network Configuration (Static IP)

| Title                   | Value                                               |
| ------------------------| --------------------------------------------------- |
| Network Interface Name  | enp1s0|
| IP Address              | 172.30.15.32|
| Netmask                 | 255.255.255.0|
| Gateway                 | 172.30.15.254|
| DNS                     | 8.8.8.8|

---

## 🖧 Hostname

- 🖥️ **Hostname Set**: FDT6510301016

---

## 👤 User Account

- 👨‍💻 **Username Created**: pitpibool
- 🔐 **Is a Root Password Set?**:  
  - [X] Yes  
  - [ ] No

---

## ✅ Additional Problems Notes (if any)

> _____________________________________________________________________  
> _____________________________________________________________________  
> _____________________________________________________________________

