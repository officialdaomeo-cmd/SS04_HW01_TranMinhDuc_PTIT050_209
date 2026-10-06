# Báo cáo Bài 1: Khởi tạo Local Repository và Cấu hình danh tính

## 1. Các lệnh cấu hình đã thực hiện

- Khởi tạo repository:
  ```bash
  git init
  ```
- Cấu hình danh tính cục bộ (local):
  ```bash
  git config --local user.name "Hoc Vien"
  git config --local user.email "hocvien@example.com"
  ```
- Thêm tệp vào Staging Area và commit:
  ```bash
  git add README.md
  git commit -m "Initial commit: Add README.md"
  ```

## 2. Kết quả kiểm tra

### Kết quả `git config --local --list`

```text
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
user.name=Hoc Vien
user.email=hocvien@example.com
```

### Kết quả `git log --oneline`

```text
05076aa Initial commit: Add README.md
```
