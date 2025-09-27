<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>图视文件更名助手</title>
  <style>
    /* 全局样式 */
    body {
      font-family: "KaiTi", "SimHei", sans-serif;
      background-color: #f3f8fc;
      color: #333;
      margin: 0;
      padding: 0;
    }

    h1, h2 {
      text-align: center;
      color: #1a73e8;
      margin: 0;
    }

    h1 {
      font-size: 36px;
      font-weight: bold;
      margin-top: 50px;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 26px;
      font-weight: bold;
      margin-top: 40px;
      margin-bottom: 20px;
    }

    .container {
      max-width: 960px;
      margin: 30px auto;
      padding: 30px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
      line-height: 1.6;
      font-size: 16px;
    }

    p {
      margin-bottom: 15px;
    }

    ul {
      padding-left: 25px;
      margin-bottom: 15px;
    }

    li {
      margin-bottom: 10px;
    }

    pre {
      background-color: #f0f0f0;
      padding: 12px 15px;
      border-radius: 6px;
      font-size: 15px;
      overflow-x: auto;
    }

    a {
      color: #1a73e8;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      font-size: 14px;
      color: #999;
      margin-top: 50px;
      padding-bottom: 20px;
    }

    /* 按钮样式示例 */
    .btn {
      display: inline-block;
      padding: 10px 20px;
      margin-top: 10px;
      background-color: #1a73e8;
      color: white;
      font-weight: bold;
      border-radius: 6px;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #155ab6;
    }
  </style>
</head>
<body>

  <h1>图视文件更名助手</h1>

  <div class="container">
    <h2>项目简介</h2>
    <p>
      图视文件更名助手是一个基于 Python 的小型工具，旨在帮助用户自动化重命名文件夹，尤其是包含图片和视频的目录。
      它会根据文件夹中的文件数量及总大小自动生成清晰易懂的文件夹名称，从而大幅提高管理效率。
    </p>

    <h2>功能特性</h2>
    <ul>
      <li>自动扫描父文件夹中的所有子文件夹。</li>
      <li>计算每个子文件夹中的图片数量、视频数量及文件夹总大小。</li>
      <li>生成新的文件夹名称，包含：
        <ul>
          <li>父目录名称作为前缀</li>
          <li>自动编号（如 NO.001）</li>
          <li>图片数量和视频数量（如有）</li>
          <li>文件夹总大小（GB/MB）</li>
        </ul>
      </li>
      <li>提供图形用户界面（GUI）选择目标文件夹进行操作。</li>
      <li>实时显示进度及错误信息。</li>
    </ul>

    <h2>使用方法</h2>
    <p>1. 克隆仓库：</p>
    <pre>
git clone https://github.com/yourusername/image-video-folder-renamer.git
cd image-video-folder-renamer
    </pre>

    <p>2. 安装依赖：</p>
    <pre>pip install -r requirements.txt</pre>

    <p>3. 运行程序：</p>
    <pre>python set_name.py</pre>

    <p>4. 在弹出的窗口中点击“浏览”选择父文件夹，然后点击“开始重命名”。程序会自动扫描并重命名文件夹。</p>

    <h2>依赖</h2>
    <ul>
      <li>tkinter：图形界面库</li>
      <li>Pillow：图片处理库</li>
      <li>re：正则表达式</li>
      <li>os 与 unicodedata：文件路径与字符处理</li>
      <li>messagebox 与 ttk：消息框与自定义按钮样式</li>
    </ul>

    <h2>许可证</h2>
    <p>本项目采用 MIT 许可证，详情请查看 <a href="LICENSE">LICENSE</a> 文件。</p>

    <h2>致谢</h2>
    <ul>
      <li><a href="https://pillow.readthedocs.io/en/stable/">Pillow</a>：Python 图像处理库</li>
      <li><a href="https://docs.python.org/3/library/tkinter.html">Tkinter</a>：Python 标准 GUI 库</li>
    </ul>
  </div>

  <footer>
    <p>© 2025 图视文件更名助手 - 版权所有</p>
  </footer>

</body>
</html>
