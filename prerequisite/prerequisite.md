# 先決條件

## 環境準備
請確保 LAB（實驗室環境）已經準備好並且正在運行，以便執行後續任務。

**藍圖**

![](/_static/intro/intro-0.png)

![](/_static/intro/intro-1.png)

> **注意：** 課程依賴於私有註冊伺服器 Harbor Registry（港灣註冊伺服器），請確保 Harbor Registry 已經啟動並正常運作後再繼續。

遠端桌面連線到 Windows 10 跳板機（Jumphost）。

登入遠端桌面（RDP，Remote Desktop Protocol），以存取 Harbor Registry 伺服器，確認服務正在運行且你能夠成功登入。

![](/_static/intro/intro-5.png)

Windows 10 RDP 登入密碼可依下列方式取得：

![](/_static/intro/intro-6.png)

**Windows 10 跳板機**

![](/_static/intro/intro-7.png)

啟動 putty（終端模擬器），並使用以下認證登入。

| **使用者名稱** | ubuntu |
|--------------|--------|
| **密碼** | HelloUDF |

![](/_static/intro/intro-2.png)

你應該能夠在 "reg" 伺服器上看到以下提示。

![](/_static/intro/intro-3.png)

執行以下命令以確認註冊服務正在運行。

```bash
sudo systemctl status harbor
```
