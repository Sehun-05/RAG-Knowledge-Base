# RAG-Knowledge-Base
基于Python+LangChain+Ollama的本地RAG知识库问答系统

#项目功能
- 支持PDF/TXT/Word多格式文档上传与解析
- 自动文本分块、向量化，构建本地向量知识库
- 语义检索+检索增强生成（RAG），实现精准问答
- 本地部署，数据安全可控，无需GPU即可运行

#技术栈
- Python
- LangChain
- FAISS（向量数据库）
- Ollama（Qwen-7B 开源大模型）
- HuggingFace Embeddings

#运行方式
-安装 Ollama：https://ollama.com/
-拉取大模型：ollama pull qwen:7b
-安装依赖：pip install -r requirements.txt
-运行项目：python 1.py

#项目亮点
- 完整实现 RAG 全流程，从数据处理到模型落地闭环
- 解决大模型幻觉问题，实现外部知识精准调用
- 支持多文档上传，可快速搭建个人/企业私有知识库
- 代码规范，可复现性强，适配AI算法/大模型应用开发岗位
