# llm_sentiment
Simple LLM chat bot with real time sentiment analysis powered by OpenVINO

Based on https://github.com/openvinotoolkit/openvino_notebooks#-ai-trends---notebooks

A positive sentiment is as close to 1.0 as possible
![](https://github.com/samontab/llm_sentiment/blob/main/positive.png)

A negative sentiment is as close to -1.0 as possible
![](https://github.com/samontab/llm_sentiment/blob/main/negative.png)

# How to run it
```
git clone https://github.com/samontab/llm_sentiment.git
cd llm_sentiment
python3 -m venv llm_sentiment
source llm_sentiment/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab llm_sentiment.ipynb
```
