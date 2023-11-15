# 🚀StockalyzerGPT🧠: Adaption of FinGPT Forecaster to include quantitative models

[Blueprint of FinGPT](https://arxiv.org/abs/2306.06031)

<https://huggingface.co/FinGPT>

## Why StockalyzerGPT?
1). It is costly to retrain an LLM model like BloombergGPT every month or every week, thus lightweight adaptation is highly favorable. FinGPT can be fine-tuned swiftly to incorporate new data (the cost falls significantly, less than **$300 per fine-tuning**). [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT)

2). Democratizing Internet-scale financial data is critical, say allowing timely updates of the model (monthly or weekly updates) using an automatic data curation pipeline.  BloombergGPT has privileged data access and APIs, while FinGPT presents a more accessible alternative. It prioritizes lightweight adaptation, leveraging the best available open-source LLMs. [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT)

3). The key technology is "RLHF (Reinforcement learning from human feedback)", which is missing in BloombergGPT. RLHF enables an LLM model to learn individual preferences (risk-aversion level, investing habits, personalized robo-advisor, etc.), which is the "secret" ingredient of ChatGPT and GPT4. [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT)

4). Explainability is a fundamental issue with the "black-box" problem associated with AI. StockalyzerGPT aims to leverage the explainability demonstrated with FinGPT and extrapolate this functionality to include quantitative models

## Why FinGPT?
 - Demonstrated ability of LLMs to provide explainability in financial forecasting
 - Opensourced fine-tuning LLM with publicly available data
 - [FinGPT-Forecaster](https://github.com/AI4Finance-Foundation/FinGPT/tree/master/fingpt/FinGPT_Forecaster)!  [Demo](https://huggingface.co/spaces/FinGPT/FinGPT-Forecaster)  [Model](https://huggingface.co/FinGPT/fingpt-forecaster_dow30_llama2-7b_lora)

## LICENSE

MIT License

**Disclaimer: I am sharing codes for academic purposes under the MIT education license. Nothing herein is financial advice, and NOT a recommendation to trade real money. Please use common sense and always first consult a professional before trading or investing.**

