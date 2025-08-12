<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>图视文件更名助手</title>
  <style>
    body {
      font-family: KaiTi, sans-serif;
      background-color: #f3f8fc;
      color: #333;
      margin: 20px;
    }
    h1, h2 {
      text-align: center;
    }
    .content {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    a {
      color: #1a73e8;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <h1>图视文件更名助手</h1>

  <div class="content">
    <h2>项目简介</h2>
    <p>
      图视文件更名助手是一个基于 Python 的小型工具，旨在帮助用户自动化地重命名文件夹，特别是处理包含图片和视频文件的目录。
      该工具根据文件夹中的图片和视频数量以及文件夹总大小，自动生成清晰易懂的文件夹名称，极大地提高了管理大量文件夹的效率。
      该工具支持根据父目录名称为文件夹编号，并去除冗余的描述信息，使文件夹名称更加简洁明了。
    </p>

    <h2>功能特性</h2>
    <ul>
      <li>自动扫描父文件夹中的所有子文件夹。</li>
      <li>计算每个子文件夹中的图片数量、视频数量和文件夹总大小。</li>
      <li>根据文件夹内容生成新的文件夹名称，包含：
        <ul>
          <li>父目录名称作为前缀。</li>
          <li>自动编号（如 NO.001）。</li>
          <li>文件夹中的图片数量和视频数量（如果有）。</li>
          <li>文件夹的总大小（GB / MB）。</li>
        </ul>
      </li>
      <li>支持通过图形用户界面（GUI）选择目标文件夹进行操作。</li>
      <li>支持操作中显示当前进度和错误信息。</li>
    </ul>

    <h2>使用方法</h2>
    <p>1. 克隆本仓库：</p>
    <pre>
git clone https://github.com/yourusername/image-video-folder-renamer.git
cd image-video-folder-renamer
    </pre>

    <p>2. 安装依赖：</p>
    <pre>
pip install -r requirements.txt
    </pre>

    <p>3. 运行程序：</p>
    <pre>
python set_name.py
    </pre>

    <p>4. 在弹出的窗口中，点击“浏览”按钮选择父文件夹，点击“开始重命名”按钮，程序将自动扫描并重命名文件夹。</p>

    <h2>依赖</h2>
    <ul>
      <li>tkinter：用于创建图形界面。</li>
      <li>Pillow：用于处理图片。</li>
      <li>re：用于正则表达式匹配。</li>
      <li>os 和 unicodedata：用于处理文件路径和字符。</li>
      <li>messagebox 和 ttk：用于显示消息框和自定义按钮样式。</li>
    </ul>

    <h2>许可证</h2>
    <p>本项目采用 MIT 许可证，具体内容请查看 <a href="LICENSE">LICENSE</a> 文件。</p>

    <h2>致谢</h2>
    <ul>
      <li><a href="https://pillow.readthedocs.io/en/stable/">Pillow</a>：Python 图像处理库。</li>
      <li><a href="https://docs.python.org/3/library/tkinter.html">Tkinter</a>：Python 的标准 GUI 库。</li>
    </ul>

  </div>
</body>
</html>
