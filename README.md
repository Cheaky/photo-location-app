# 📍 照片位置提取器

批量提取照片的GPS位置和地址信息，导出带水印的照片。

## 功能特点

- 📁 批量导入照片
- 📍 提取GPS经纬度
- 🏠 获取详细地址（支持"在XX附近"格式）
- 📅 提取拍摄时间
- 🖼️ 导出带位置水印的照片
- 📊 导出Excel表格
- 🔧 批量重命名

## 使用方法

1. 打开 `index.html`
2. 输入高德地图API Key（免费申请：https://console.amap.com/）
3. 选择照片
4. 导出Excel或带水印的照片

## 部署到GitHub Pages

### 方法一：手动部署

1. 登录 GitHub
2. 创建新仓库（如：`photo-location-app`）
3. 将 `index.html` 和 `README.md` 上传到仓库
4. 进入仓库 Settings → Pages
5. Source 选择 `main branch`，点击 Save
6. 等待部署完成后访问生成的链接

### 方法二：使用Git命令

```bash
# 克隆仓库
git clone https://github.com/你的用户名/photo-location-app.git
cd photo-location-app

# 添加文件
git add .
git commit -m "Add photo location app"

# 推送到GitHub
git push origin main
```

然后在仓库设置中启用GitHub Pages。

## API Key 申请

1. 访问 https://console.amap.com/
2. 注册/登录账号
3. 创建应用获取Web服务API Key
4. 将Key填入应用输入框

## 许可证

MIT License