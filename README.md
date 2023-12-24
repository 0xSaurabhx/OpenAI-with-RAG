# OpenAI-with-RAG
OpenAI RAG Application which Stores Webpages as Index


## Installation

```bash
git clone https://github.com/0xSaurabhx/OpenAI-with-RAG
cd OpenAI-with-RAG
pip install -r requirements.txt
```

## Add Knowledge Base

```python
PAGES = [
    #Replace Below Links
    "https://resources.nvidia.com/en-us-large-language-model-ebooks/llm-ebook-part1",
    "https://resources.nvidia.com/en-us-large-language-model-ebooks/llm-ebook-part2",
]
```
## Run Locally

```bash
python data_pipeline.py
python build_index.py
streamlit run streamlit_app.py
```
