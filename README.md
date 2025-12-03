# coze-workflow
The workflow built on Coze.


## Run the workflow
For each workflow, just copy and paste the content of the json file into the Coze workflow to run it.

对于每一个工作流，将json文件的内容复制并粘贴在Coze工作流中即可运行。

## Each workflow description
1. `get_public_article.json`: 扣子 × 飞书 × DeepSeek：批量提取公众号文章内容的自动化工作流
   该工作流通过 Coze自动化编排 + 飞书文档/多维表格存储 + DeepSeek 文本理解能力，实现公众号文章的批量抓取与结构化解析。流程会自动完成文章链接获取、正文抽取、格式清洗、内容摘要、标签分类等步骤，并将结果同步到飞书进行存档或二次分析。整个过程无需人工干预，适合构建高效的内容知识库与信息爬取系统。
2. `official_article_generation.json`: 自动生成公众号文章的 AI 内容创作工作流
   这个工作流旨在帮助用户快速生成高质量、可直接发布的公众号文章。用户仅需提供主题、角度或目标读者，系统便会调用 DeepSeek 等大模型自动完成选题拆解、文章结构规划、段落写作、标题优化、封面文案等工作。支持可控风格（科普、情感、商业、职场等）与批量创作模式，适用于内容创作者、企业新媒体运营及个人品牌打造。
3. `stick_man_video_generate.json`: 火柴人情绪表达视频生成：心理学科普短视频创作工作流
   该工作流利用火柴人的极简视觉语言和丰富肢体表现，通过 AI 自动生成“火柴人演绎心理学情绪场景”的短视频脚本与分镜。系统会根据输入主题（如情绪困惑、职场压力、人际冲突）自动构建情境、角色动作、转场设计和情绪表达点，再由视频生成模型渲染成生动有趣的短视频。输出具有强共鸣、轻松易传播的心理学内容，适合做情绪科普账号或短视频栏目。
