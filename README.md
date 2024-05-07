<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">形状</font></font></h1><a id="user-content-shap-e" class="anchor" aria-label="永久链接：Shap-E" href="#shap-e"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://arxiv.org/abs/2305.02463" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是Shap-E：生成条件 3D 隐式函数</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的官方代码和模型版本</font><font style="vertical-align: inherit;">。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关如何使用此存储库的指南，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="#usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法。</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#samples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解我们的文本条件模型可以生成的示例。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">样品</font></font></h1><a id="user-content-samples" class="anchor" aria-label="永久链接：样本" href="#samples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是我们的文本条件模型中的一些突出显示的示例。有关选定提示的随机样本，请参阅</font></font><a href="/openai/shap-e/blob/main/samples.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">samples.md</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<table>
    <tbody>
        <tr>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/a_chair_that_looks_like_an_avocado/2.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/a_chair_that_looks_like_an_avocado/2.gif" alt="一把看起来像鳄梨的椅子" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
    </animated-image>
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/an_airplane_that_looks_like_a_banana/3.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/an_airplane_that_looks_like_a_banana/3.gif" alt="一架看起来像香蕉的飞机" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
   </animated-image>
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/a_spaceship/0.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/a_spaceship/0.gif" alt="一艘宇宙飞船" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      </animated-image>
            </td>
        </tr>
        <tr>
            <td align="center"><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一把看起来像鳄梨的</font><font style="vertical-align: inherit;">椅子</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一架看起来像香蕉的</font><font style="vertical-align: inherit;">飞机</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一艘宇宙飞船</font></font></td>
        </tr>
        <tr>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/a_birthday_cupcake/3.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/a_birthday_cupcake/3.gif" alt="生日纸杯蛋糕" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
     
          
       </animated-image>
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/a_chair_that_looks_like_a_tree/2.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/a_chair_that_looks_like_a_tree/2.gif" alt="一把看起来像树的椅子" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
    
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/openai/shap-e/blob/main/samples/a_green_boot/3.gif" data-target="animated-image.originalLink"><img src="/openai/shap-e/raw/main/samples/a_green_boot/3.gif" alt="绿色靴子" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      
          
     
            </td>
        </tr>
        <tr>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生日纸杯蛋糕</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一把看起来像树的</font><font style="vertical-align: inherit;">椅子</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">绿色靴子</font></font></td>
        </tr>
        <tr>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/a_penguin/1.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/a_penguin/1.gif" alt="一只企鹅" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
    
          
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="https://github.com/openai/shap-e/blob/main/samples/ube_ice_cream_cone/3.gif" data-target="animated-image.originalLink"><img src="https://github.com/openai/shap-e/raw/main/samples/ube_ice_cream_cone/3.gif" alt="宇部冰淇淋甜筒" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
     
            </td>
            <td align="center">
                <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/openai/shap-e/blob/main/samples/a_bowl_of_vegetables/2.gif" data-target="animated-image.originalLink"><img src="/openai/shap-e/raw/main/samples/a_bowl_of_vegetables/2.gif" alt="一碗蔬菜" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
       
            </td>
        </tr>
        <tr>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一只企鹅</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">宇部冰淇淋甜筒</font></font></td>
            <td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一碗蔬菜</font></font></td>
        </tr>
    </tbody>
</table><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h1><a id="user-content-usage" class="anchor" aria-label="永久链接：用法" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装与</font></font><code>pip install -e .</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要开始使用示例，请参阅以下笔记本：</font></font></p><ul dir="auto">
<li><a href="/openai/shap-e/blob/main/shap_e/examples/sample_text_to_3d.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sample_text_to_3d.ipynb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 根据文本提示对 3D 模型进行采样。</font></font></li>
<li><a href="/openai/shap-e/blob/main/shap_e/examples/sample_image_to_3d.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sample_image_to_3d.ipynb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 以合成视图图像为条件对 3D 模型进行采样。为了获得最佳结果，您应该从输入图像中删除背景。</font></font></li>
<li><a href="/openai/shap-e/blob/main/shap_e/examples/encode_model.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">encode_model.ipynb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 加载 3D 模型或修剪网格，创建一批多视图渲染和点云，将它们编码为潜在的，然后将其渲染回来。为此，请安装 Blender 版本 3.3.1 或更高版本，并将环境变量设置</font></font><code>BLENDER_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Blender 可执行文件的路径。</font></font></li>
</ul><table>




</table></article></div>
