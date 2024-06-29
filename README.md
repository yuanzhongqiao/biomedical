<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BigBIO：生物医学数据集库</font></font></h1><a id="user-content-bigbio-biomedical-dataset-library" class="anchor" aria-label="永久链接：BigBIO：生物医学数据集库" href="#bigbio-biomedical-dataset-library"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（BigScience Biomedical）是一个开放的生物医学数据加载器库，使用 Huggingface（🤗）的</font><font style="vertical-align: inherit;">以数据为中心的机器学习</font></font><a href="https://huggingface.co/docs/datasets/" rel="nofollow"><code>datasets</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库构建。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的目标包括：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻量级、以编程方式大规模访问生物医学数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提高数据处理的可重复性</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更好地记录数据集来源、许可和其他关键属性</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更轻松地生成用于自然语言提示和多任务学习的元数据集</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前</font></font><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">126+ 生物医学数据集</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10+ 种语言</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12 个任务类别</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按任务类型协调数据集架构</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">粗/细粒度任务类型</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">领域</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等的元数据！</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用</font></font><code>BigBIO</code></h2><a id="user-content-how-to-use-bigbio" class="anchor" aria-label="永久链接：如何使用 BigBIO" href="#how-to-use-bigbio"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用这些数据集的首选方法是从</font></font><a href="https://huggingface.co/bigbio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方</font></font><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中心</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问它们。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">至少，请确保已</font></font><code>datasets</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装库。最好按如下方式安装要求：</font></font></p>
<p dir="auto"><code>pip install -r requirements.txt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<br>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font></font><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按如下方式访问数据集：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">datasets</span> <span class="pl-k">import</span> <span class="pl-s1">load_dataset</span>
<span class="pl-s1">data</span> <span class="pl-c1">=</span> <span class="pl-en">load_dataset</span>(<span class="pl-s">"bigbio/biosses"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from datasets import load_dataset
data = load_dataset(&quot;bigbio/biosses&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在大多数情况下，脚本默认加载数据集的原始架构。您还可以访问拆分</font></font><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，以简化对特定任务中数据集中关键信息的访问。</font></font></p>
<br>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，</font></font><code>biosses</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集遵循</font></font><code>pairs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于模式，其中基于文本的输入（句子、段落）被分配一个“翻译”对。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">datasets</span> <span class="pl-k">import</span> <span class="pl-s1">load_dataset</span>
<span class="pl-s1">data</span> <span class="pl-c1">=</span> <span class="pl-en">load_dataset</span>(<span class="pl-s">"bigbio/biosses"</span>, <span class="pl-s1">name</span><span class="pl-c1">=</span><span class="pl-s">"biosses_bigbio_pairs"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from datasets import load_dataset
data = load_dataset(&quot;bigbio/biosses&quot;, name=&quot;biosses_bigbio_pairs&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通常，您可以按如下方式加载数据集：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># Load original schema</span>
<span class="pl-s1">data</span> <span class="pl-c1">=</span> <span class="pl-en">load_dataset</span>(<span class="pl-s">"bigbio/&lt;your_dataset&gt;"</span>)

<span class="pl-c"># Load BigBIO schema</span>
<span class="pl-s1">data</span> <span class="pl-c1">=</span> <span class="pl-en">load_dataset</span>(<span class="pl-s">"bigbio/&lt;your_dataset_here&gt;"</span>, <span class="pl-s1">name</span><span class="pl-c1">=</span><span class="pl-s">"&lt;your_dataset&gt;_bigbio_&lt;schema_name&gt;"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Load original schema
data = load_dataset(&quot;bigbio/<your_dataset>&quot;)

# Load BigBIO schema
data = load_dataset(&quot;bigbio/<your_dataset_here>&quot;, name=&quot;<your_dataset>_bigbio_<schema_name>&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">检查 Hub 上的数据卡，了解您可以使用哪些拆分。您可以在下面的</font><a href="##Documentation"><font style="vertical-align: inherit;">文档</font></a><font style="vertical-align: inherit;">中找到有关</font></font><a href="/bigscience-workshop/biomedical/blob/main/task_schemas.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的更多信息。</font></font><a href="##Documentation"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准支持</font></font></h2><a id="user-content-benchmark-support" class="anchor" aria-label="固定链接：基准支持" href="#benchmark-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包括对其他流行的英语生物医学基准中的几乎所有数据集的支持。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务类型</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据集</font></font></th>
<th align="center"><a href="https://arxiv.org/abs/2206.15076" rel="nofollow"><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（我们的）</font></font></a></th>
<th align="center"><a href="https://arxiv.org/abs/1906.05474" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝色的</font></font></a></th>
<th align="center"><a href="https://microsoft.github.io/BLURB/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简介</font></font></a></th>
<th align="center"><a href="https://arxiv.org/abs/2204.07600" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">盒子</font></font></a></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要 DUA</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC2GM</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC5-化学</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC5 疾病</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循证医学皮科</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日语非语言职业资格证书考试</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NCBI 疾病</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">化学保护</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接直接投资</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">广泛性焦虑症</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量保证</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PubMed问答</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">质量保证</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物科学质量协会</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直流</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主键</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">船用运输系统</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生物酶</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">船用运输系统</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医学影像系统</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">n2c2 2010</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ShARe/CLEF 2013</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自然语言处理</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医学神经科学研究所</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">n2c2 死亡 2006</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直流</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">n2c2 射频高清 2014</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解剖学杂志</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BC4CHEMD</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP09</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP11EPI</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP11ID</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP13CG</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP13GE</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BioNLP13PC</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工艺</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">外PTM</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">净资产收益率</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">林奈</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">销售点</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吉尼亚</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">南非</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">医疗药品</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">✓</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简写</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冠状病毒</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私人的</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简写</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">烹饪</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私人的</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简写</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">激素替代疗法</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私人的</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简写</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">加速度计</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私人的</font></font></td>
<td align="center"></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简写</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">肢端肥大症</font></font></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">私人的</font></font></td>
<td align="center"></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">* 表示数据集实施正在进行中</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2><a id="user-content-documentation" class="anchor" aria-label="永久链接：文档" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li>
<p dir="auto"><a href="/bigscience-workshop/biomedical/blob/main/task_schemas.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务模式概述</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是对所实施模式的深入解释</font></font><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/bigscience-workshop/biomedical/tree/master/streamlit_demo"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Streamlit 可视化演示</font></font></a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/bigscience-workshop/biomedical/tree/master/figures/data_card"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BigBIO 数据卡</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">报告库中每个数据集的统计数据。</font></font></p>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></h2><a id="user-content-tutorials" class="anchor" aria-label="永久链接：教程" href="#tutorials"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TBA-链接可能尚不适用！</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程
</font></font><ul dir="auto">
<li><a href="https://github.com/bigscience-workshop/biomedical/blob/master/notebooks/materializing_meta_datasets/materializing-meta-datasets.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">物化元数据集</font></font></a></li>
<li><a href="https://github.com/bigscience-workshop/biomedical/tree/master/notebooks/promptengineering"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">及时工程和评估</font></font></a></li>
<li><a href="/bigscience-workshop/biomedical/blob/main/notebooks/bloomprompting/bloompipeline.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">利用 BLOOM 进行快速工程</font></font></a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2><a id="user-content-contributing" class="anchor" aria-label="永久链接：贡献" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><code>BigBIO</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个开源项目 - 热烈欢迎您的参与！如果您很高兴加入我们，我们建议您采取以下步骤：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正在寻找创意？查看我们的</font></font><a href="https://github.com/orgs/bigscience-workshop/projects/6"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">志愿者项目委员会</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解我们可能需要哪些帮助。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/bigscience-workshop/biomedical/issues/new?assignees=&amp;labels=&amp;template=add-dataset.md&amp;title="><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有自己的想法吗？以问题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的形式联系管理员</font><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照</font></font><a href="/bigscience-workshop/biomedical/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">官方贡献指南规定的指导方针来实现你的想法</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等待管理员批准；批准是迭代的，但如果被接受将属于主存储库。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前，只有管理员会将所有接受的更改合并到 Hub。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎加入我们的</font></font><a href="https://discord.com/invite/Cwf3nT3ajP" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></h2><a id="user-content-citing" class="anchor" aria-label="永久链接：引用" href="#citing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你在工作中使用 BigBIO，请引用</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{fries2022bigbio,
	title = {
		BigBIO: A Framework for Data-Centric Biomedical Natural Language
		Processing
	},
	author = {
		Fries, Jason Alan and Weber, Leon and Seelam, Natasha and Altay,
		Gabriel and Datta, Debajyoti and Garda, Samuele and Kang, Myungsun
		and Su, Ruisi and Kusa, Wojciech and Cahyawijaya, Samuel and others
	},
	journal = {arXiv preprint arXiv:2206.15076},
	year = 2022
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{fries2022bigbio,
	title = {
		BigBIO: A Framework for Data-Centric Biomedical Natural Language
		Processing
	},
	author = {
		Fries, Jason Alan and Weber, Leon and Seelam, Natasha and Altay,
		Gabriel and Datta, Debajyoti and Garda, Samuele and Kang, Myungsun
		and Su, Ruisi and Kusa, Wojciech and Cahyawijaya, Samuel and others
	},
	journal = {arXiv preprint arXiv:2206.15076},
	year = 2022
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2><a id="user-content-acknowledgements" class="anchor" aria-label="永久链接：致谢" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><code>BigBIO</code><font style="vertical-align: inherit;"></font><a href="/bigscience-workshop/biomedical/blob/main/HACKATHON.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一项开源社区努力，通过 BigScience 和Biomedical Hackathon</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的众多志愿者的努力才得以实现</font><font style="vertical-align: inherit;">。</font></font></p>
</article></div>
