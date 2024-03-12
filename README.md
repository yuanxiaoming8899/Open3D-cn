<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p align="center" dir="auto">
<a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/isl-org/Open3D/main/docs/_static/open3d_logo_horizontal.png"><img src="https://raw.githubusercontent.com/isl-org/Open3D/main/docs/_static/open3d_logo_horizontal.png" width="320" style="max-width: 100%;"></a>
</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D：用于 3D 数据处理的现代库</font></font></h1><a id="user-content-open3d-a-modern-library-for-3d-data-processing" class="anchor" aria-label="永久链接：Open3D：用于 3D 数据处理的现代库" href="#open3d-a-modern-library-for-3d-data-processing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto">
    <a href="https://www.open3d.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主页</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs/release/getting_started.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速入门</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs/release/compilation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs/release/index.html#python-api-index" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蟒蛇</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs/release/cpp_api.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> |
    </font></font><a href="https://github.com/isl-org/Open3D-ML"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-ML</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> |
    </font></font><a href="https://github.com/isl-org/Open3D/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">观众</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.open3d.org/docs/release/contribute/contribute.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://www.youtube.com/channel/UCRJBlASPfPBtPXJSPffJV-w" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">|
    </font></font><a href="https://github.com/isl-org/Open3D/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论坛</font></font></a>
</h4><a id="user-content-----homepage-----docs-----quick-start-----compile-----python-----c-----open3d-ml-----viewer-----contribute-----demo-----forum" class="anchor" aria-label="永久链接： 主页 |  文档 |  快速入门 |  编译 |  蟒蛇 |  C++ |  Open3D-ML |  观众|  贡献 |  演示 |  论坛" href="#----homepage-----docs-----quick-start-----compile-----python-----c-----open3d-ml-----viewer-----contribute-----demo-----forum"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D 是一个开源库，支持快速开发处理 3D 数据的软件。</font><font style="vertical-align: inherit;">Open3D 前端公开了一组精心挑选的 C++ 和 Python 数据结构和算法。</font><font style="vertical-align: inherit;">后端经过高度优化并设置为并行化。</font><font style="vertical-align: inherit;">我们欢迎开源社区的贡献。</font></font></p>
<p dir="auto"><a href="https://github.com/isl-org/Open3D/actions?query=workflow%3A%22Ubuntu+CI%22"><img src="https://github.com/isl-org/Open3D/actions/workflows/ubuntu.yml/badge.svg" alt="Ubuntu CI" style="max-width: 100%;"></a>
<a href="https://github.com/isl-org/Open3D/actions?query=workflow%3A%22macOS+CI%22"><img src="https://github.com/isl-org/Open3D/actions/workflows/macos.yml/badge.svg" alt="macOS CI" style="max-width: 100%;"></a>
<a href="https://github.com/isl-org/Open3D/actions?query=workflow%3A%22Windows+CI%22"><img src="https://github.com/isl-org/Open3D/actions/workflows/windows.yml/badge.svg" alt="视窗持续集成" style="max-width: 100%;"></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D 的核心功能包括：</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D 数据结构</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D数据处理算法</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">场景重建</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表面对准</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D可视化</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于物理的渲染 (PBR)</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyTorch 和 TensorFlow 的 3D 机器学习支持</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">针对核心 3D 操作的 GPU 加速</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供 C++ 和 Python 版本</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下简要概述了 Open3D 的不同组件以及它们如何组合在一起以实现完整的端到端管道：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://private-user-images.githubusercontent.com/41028320/282678882-e9b8645a-a823-4d78-8310-e85207bbc3e4.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTAyNDI1MTQsIm5iZiI6MTcxMDI0MjIxNCwicGF0aCI6Ii80MTAyODMyMC8yODI2Nzg4ODItZTliODY0NWEtYTgyMy00ZDc4LTgzMTAtZTg1MjA3YmJjM2U0LmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzEyVDExMTY1NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdkMWIwYzFmYTVjNDkxODU4NTE4NjIxN2U1MTFmNDU3MjgxNzdmZDU5ZWMwYzQzNTg1MDI2MmRjMzFiMTQ1ZDQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.wVKtYM6odeJPUqcdzy1LLnG-JuFZxwJBmC7Q7KgQkpg"><img src="https://private-user-images.githubusercontent.com/41028320/282678882-e9b8645a-a823-4d78-8310-e85207bbc3e4.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTAyNDI1MTQsIm5iZiI6MTcxMDI0MjIxNCwicGF0aCI6Ii80MTAyODMyMC8yODI2Nzg4ODItZTliODY0NWEtYTgyMy00ZDc4LTgzMTAtZTg1MjA3YmJjM2U0LmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzEyVDExMTY1NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdkMWIwYzFmYTVjNDkxODU4NTE4NjIxN2U1MTFmNDU3MjgxNzdmZDU5ZWMwYzQzNTg1MDI2MmRjMzFiMTQ1ZDQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.wVKtYM6odeJPUqcdzy1LLnG-JuFZxwJBmC7Q7KgQkpg" alt="Open3D_层" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多信息，请访问</font></font><a href="https://www.open3d.org/docs" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D 文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python快速入门</font></font></h2><a id="user-content-python-quick-start" class="anchor" aria-label="永久链接：Python 快速入门" href="#python-quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预构建的 pip 包支持 Ubuntu 18.04+、macOS 10.15+ 和 Windows 10+（64 位）以及 Python 3.8-3.11。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Install</span>
pip install open3d       <span class="pl-c"><span class="pl-c">#</span> or</span>
pip install open3d-cpu   <span class="pl-c"><span class="pl-c">#</span> Smaller CPU only wheel on x86_64 Linux (v0.17+)</span>

<span class="pl-c"><span class="pl-c">#</span> Verify installation</span>
python -c <span class="pl-s"><span class="pl-pds">"</span>import open3d as o3d; print(o3d.__version__)<span class="pl-pds">"</span></span>

<span class="pl-c"><span class="pl-c">#</span> Python API</span>
python -c <span class="pl-s"><span class="pl-pds">"</span>import open3d as o3d; <span class="pl-cce">\</span></span>
<span class="pl-s">           mesh = o3d.geometry.TriangleMesh.create_sphere(); <span class="pl-cce">\</span></span>
<span class="pl-s">           mesh.compute_vertex_normals(); <span class="pl-cce">\</span></span>
<span class="pl-s">           o3d.visualization.draw(mesh, raw_mode=True)<span class="pl-pds">"</span></span>

<span class="pl-c"><span class="pl-c">#</span> Open3D CLI</span>
open3d example visualization/draw</pre><div class="zeroclipboard-container">
  

# Verify installation
python -c &quot;import open3d as o3d; print(o3d.__version__)&quot;


# Open3D CLI
open3d example visualization/draw" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要获取 Open3D 的最新功能，请安装
</font></font><a href="https://www.open3d.org/docs/latest/getting_started.html#development-version-pip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发 pip 包</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">要从源代码编译 Open3D，请参阅
</font></font><a href="https://www.open3d.org/docs/release/compilation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码编译</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">C++ 快速入门</font></font></h2><a id="user-content-c-quick-start" class="anchor" aria-label="永久链接：C++ 快速入门" href="#c-quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看以下链接以开始使用 Open3D C++ API</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载Open3D二进制包：</font></font><a href="https://github.com/isl-org/Open3D/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Release</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="https://www.open3d.org/docs/latest/getting_started.html#c" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新开发版本</font></font></a></li>
<li><a href="https://www.open3d.org/docs/release/compilation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源代码编译 Open3D</font></font></a></li>
<li><a href="https://www.open3d.org/docs/release/cpp_api.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D C++ API</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要在 C++ 项目中使用 Open3D，请查看以下示例</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/isl-org/open3d-cmake-find-package"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 CMake 中查找预安装的 Open3D 包</font></font></a></li>
<li><a href="https://github.com/isl-org/open3d-cmake-external-project"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Open3D 作为 CMake 外部项目</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-查看器应用程序</font></font></h2><a id="user-content-open3d-viewer-app" class="anchor" aria-label="永久链接：Open3D-Viewer 应用程序" href="#open3d-viewer-app"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/isl-org/Open3D/main/docs/_static/open3d_viewer.png"><img width="480" src="https://raw.githubusercontent.com/isl-org/Open3D/main/docs/_static/open3d_viewer.png" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-Viewer 是一款独立的 3D 查看器应用程序，可在 Debian (Ubuntu)、macOS 和 Windows 上使用。</font></font><a href="https://github.com/isl-org/Open3D/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从发布页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载 Open3D Viewer
 </font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-ML</font></font></h2><a id="user-content-open3d-ml" class="anchor" aria-label="永久链接：Open3D-ML" href="#open3d-ml"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><animated-image data-catalyst="" style="width: 480px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/isl-org/Open3D-ML/main/docs/images/getting_started_ml_visualizer.gif" data-target="animated-image.originalLink" hidden=""><img src="https://raw.githubusercontent.com/isl-org/Open3D-ML/main/docs/images/getting_started_ml_visualizer.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://raw.githubusercontent.com/isl-org/Open3D-ML/main/docs/images/getting_started_ml_visualizer.gif" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="" class="AnimatedImagePlayer-animatedImage" src="https://raw.githubusercontent.com/isl-org/Open3D-ML/main/docs/images/getting_started_ml_visualizer.gif">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://raw.githubusercontent.com/isl-org/Open3D-ML/main/docs/images/getting_started_ml_visualizer.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-ML 是 Open3D 针对 3D 机器学习任务的扩展。</font><font style="vertical-align: inherit;">它构建在 Open3D 核心库之上，并通过用于 3D 数据处理的机器学习工具对其进行扩展。</font><font style="vertical-align: inherit;">要尝试一下，请使用 PyTorch 或 TensorFlow 安装 Open3D 并查看
</font></font><a href="https://github.com/isl-org/Open3D-ML"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Open3D-ML</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沟通渠道</font></font></h2><a id="user-content-communication-channels" class="anchor" aria-label="永久链接：沟通渠道" href="#communication-channels"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="https://github.com/isl-org/Open3D/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub Issue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：错误报告、功能请求等。</font></font></li>
<li><a href="https://github.com/isl-org/Open3D/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">论坛</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：讨论 Open3D 的使用。</font></font></li>
<li><a href="https://discord.gg/D35BGvn" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不和谐聊天</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：与其他用户和开发人员在线聊天、讨论和协作。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 Open3D，</font><font style="vertical-align: inherit;">请引用</font></font><a href="https://arxiv.org/abs/1801.09847" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的工作。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@article</span>{<span class="pl-en">Zhou2018</span>,
    <span class="pl-s">author</span>    = <span class="pl-s"><span class="pl-pds">{</span>Qian-Yi Zhou and Jaesik Park and Vladlen Koltun<span class="pl-pds">}</span></span>,
    <span class="pl-s">title</span>     = <span class="pl-s"><span class="pl-pds">{</span>{Open3D}: {A} Modern Library for {3D} Data Processing<span class="pl-pds">}</span></span>,
    <span class="pl-s">journal</span>   = <span class="pl-s"><span class="pl-pds">{</span>arXiv:1801.09847<span class="pl-pds">}</span></span>,
    <span class="pl-s">year</span>      = <span class="pl-s"><span class="pl-pds">{</span>2018<span class="pl-pds">}</span></span>,
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{Zhou2018,
    author    = {Qian-Yi Zhou and Jaesik Park and Vladlen Koltun},
    title     = {{Open3D}: {A} Modern Library for {3D} Data Processing},
    journal   = {arXiv:1801.09847},
    year      = {2018},
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
