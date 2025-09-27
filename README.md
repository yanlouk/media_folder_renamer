# 图视文件更名助手

---

## 项目简介

图视文件更名助手是一个基于 Python 的工具，旨在帮助用户自动化重命名文件夹，尤其是包含图片和视频的目录。  
它会根据文件夹中的文件数量及总大小生成清晰易懂的文件夹名称，大幅提高管理效率。

---

## 功能特性

- 自动扫描父文件夹下所有子文件夹
- 统计每个子文件夹的图片数量、视频数量及文件夹总大小
- 自动生成新文件夹名称，包含：
  - 父目录名称作为前缀
  - 自动编号（如 NO.001）
  - 图片数量和视频数量（如有）
  - 文件夹总大小（GB/MB）
- 提供图形界面（GUI）选择目标文件夹
- 显示进度及错误信息

---

## 使用方法

1. 克隆仓库：

```bash
git clone https://github.com/yourusername/image-video-folder-renamer.git
cd image-video-folder-renamer
```
2.安装依赖

```bash
pip install -r requirements.txt
```
3.运行程序：

```bash
python set_name.py
```
4.在弹出的窗口中点击“浏览”选择父文件夹，然后点击“开始重命名”。程序将自动扫描并重命名文件夹。

## 依赖

- tkinter：图形界面库

- Pillow：图像处理库

- re：正则表达式

- os 与 unicodedata：文件路径与字符处理

- messagebox 与 ttk：消息框与自定义按钮样式

## 许可证

本项目采用 MIT 许可证，详情请查看 LICENSE
 文件。
