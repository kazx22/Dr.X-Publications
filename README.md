# Dr.X-Publications

A brief description of what your project does.

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/kazx22/Dr.X-Publications.git
cd Dr.X-Publications
```

### 2. Create and Activate the Conda Environment

Use the provided env.yml to set up the environment:

```bash
conda env create -f env.yml
conda activate nlp
```

### 3. Use your own nomic key

Get the nomic key and put it in the below code empty spaces

```bash
os.environ["NOMIC_API_KEY"] = "Generate Nomic Key and Put Here"
```

### 4. Download the llama

The llama model you wana use just put it in this model path. where your file is

```bash
llm = LlamaCpp(
    model_path="../models/llama-2-7b.Q2_K.gguf",
    temperature=0.7,
    max_tokens=300,
    top_p=1,
    n_ctx=2048,
    n_batch=64,
    verbose=True
)
```
