<div align="center">

# 🛠️ Hackintosh-Auto-EFI
**The Ultimate Automated OpenCore EFI Generator**

[![GitHub Stars](https://img.shields.io/github/stars/congtuhaixinhzai/Hackintosh-Auto-EFI?style=for-the-badge&color=ffd700)](https://github.com/congtuhaixinhzai/Hackintosh-Auto-EFI/stargazers)
[![License](https://img.shields.io/github/license/congtuhaixinhzai/Hackintosh-Auto-EFI?style=for-the-badge&color=007bff)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.8+-3776ab?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Trendshift](https://img.shields.io/endpoint?url=https%3A%2F%2Ftrendshift.io%2Fapi%2Fbadge%2Frepositories%2F15410&style=for-the-badge)](https://trendshift.io/repositories/15410)

---

A specialized tool that streamlines [OpenCore](https://github.com/acidanthera/OpenCorePkg) EFI creation. 
**Automate the hard parts, focus on the journey.**

[✨ Features](#-features) • [🚀 How To Use](#-how-to-use) • [🤝 Contributing](#-contributing) • [📞 Contact](#-contact)

</div>

> [!IMPORTANT]
> ### 🚀 OpenCore Legacy Patcher 3.0.0 – macOS Tahoe 26 Support!
> Bản cập nhật 3.0.0 mang đến khả năng hỗ trợ sơ khởi cho **macOS Tahoe 26**.
> - **Yêu cầu:** Sử dụng bản build từ [congtuhaixinhzai/OpenCore-Legacy-Patcher](https://github.com/congtuhaixinhzai/OpenCore-Legacy-Patcher/releases/tag/3.0.0).
> - **Lưu ý:** Các bản build chính thức từ Dortania hiện chưa hỗ trợ phiên bản này.

---

## ✨ Features

1. **Comprehensive Hardware Support** Hỗ trợ phần cứng hiện đại nhất thông qua `Compatibility Checker`.
   - **CPU Intel:** Từ Nehalem (1st Gen) ➡️ **Arrow Lake (15th Gen/Core Ultra Series 2)**.
   - **CPU AMD:** Ryzen & Threadripper (via [AMD Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)).
   - **GPU:** Hỗ trợ đầy đủ Intel iGPU (đến Gen 10), AMD dGPU (Navi 21/22/23) và các dòng NVIDIA cũ.

2. **Automated ACPI & Kexts** - Tích hợp **SSDTTime** để tự động tạo các bản vá: FakeEC, FixHPET, PLUG, RTCAWAC...
   - Tự động nhận diện và thêm Kexts dựa trên cấu hình thực tế của máy.
   - Fix lỗi Sleep (GPRW/UPRW) và quản lý thiết bị PCI thông minh.

3. **Advanced EFI Configurations** - Cấu hình **CpuTopologyRebuild** cho các CPU có nhân P-core & E-core.
   - Tự động Spoof GPU ID và CPU ID cho các dòng không được hỗ trợ mặc định.
   - Tối ưu SMBIOS cho cả hiệu năng và quản lý điện năng.
   - Tích hợp sẵn các bản vá cho iServices và sửa lỗi nhận diện ổ đĩa.

---

## 🚀 How To Use

### 1. Download
Tải phiên bản mới nhất từ repository:
- 📥 [Download ZIP](https://github.com/congtuhaixinhzai/Hackintosh-Auto-EFI/archive/refs/heads/main.zip)

### 2. Execution
Chạy công cụ tương ứng với hệ điều hành của bạn:

| Platform | Command / File |
| :--- | :--- |
| **Windows** | Run `Hackintosh-Auto-EFI.bat` |
| **macOS** | Run `Hackintosh-Auto-EFI.command` |
| **Linux** | Run `python3 Hackintosh-Auto-EFI.py` |

### 3. Workflow
- **Export Report:** Trên Windows, hãy chọn `E. Export hardware report` để công cụ quét BIOS và phần cứng chính xác nhất.
- **Customize:** Bạn có thể tùy chỉnh các Kexts hoặc ACPI theo nhu cầu riêng trước khi build.
- **Build:** Chọn **Build OpenCore EFI**, tool sẽ tự động tải các bản build mới nhất từ Dortania và GitHub.

---

## 🤝 Contributing

Mọi sự đóng góp đều rất quý giá! Nếu bạn có ý tưởng cải tiến, đừng ngần ngại:
1. **Fork** dự án.
2. Tạo **Pull Request**.
3. Hoặc mở một **Issue** với tag "enhancement".

Hãy tặng dự án 1 ⭐ Star nếu nó giúp ích cho bạn!

---

## 📜 License & Credits

- **License:** BSD 3-Clause License.
- **Credits:** Cảm ơn [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [SSDTTime](https://github.com/congtuhaixinhzai/SSDTTime) và cộng đồng Hackintosh.

---

## 📞 Contact

<div align="center">

**Congtuhaixinhzai**

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/congtuhaixinhzai)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/congtuhaixinhzai)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:congtuhaixinhzai@gmail.com)

</div>

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=congtuhaixinhzai/Hackintosh-Auto-EFI&type=Date)](https://star-history.com/#congtuhaixinhzai/Hackintosh-Auto-EFI&Date)
