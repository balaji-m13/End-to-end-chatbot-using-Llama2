# End-to-end-chatbot-using-Llama2


## Steps to run the project

```bash
conda create -n schatbot python=3.8 -y
```
```bash
conda activate schatbot
```


```bash
pip install -r requirements.txt
```

### Download the quantize model mentioned in the model folder

```
### Download the following model:
llama-2-7b-chat.ggmlv3.q4_0.bin

### From the following url:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML

```

```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- Pinecone