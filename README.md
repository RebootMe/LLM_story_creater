# LLM_story_creater
erebus-holodeck-7b.Q6 using story



📖 README.md

# 🪶 Story Creator with Erebus LLM (Locally Run Llama)

Welcome to **Story Creator**, where your dusty CPU gets to spin tales with the finesse of an AI bard on espresso.

This project uses the [Erebus-Holodeck-7B.Q6_K GGUF model](https://huggingface.co/DavidAU/Erebus-Holodeck-7B-Q6_K-GGUF) with `llama-cpp-python` to auto-generate vivid, structured stories using the 5-act narrative structure—all from a humble local machine. No cloud, no GPUs. Just raw CPU grind and caffeinated ambition.

## 🛠 Features
- Local inference with Erebus LLM (GGUF format)
- Grammar refinement + narrative continuation
- 5-act structure storytelling engine
- Word limit-based story generation loop
- Absolutely no moral guardrails (you’re the boss here)

## 🚀 Setup

### 1. Clone the repo and install dependencies:
```bash
pip install -r requirements.txt

2. Install git-lfs:

sudo apt-get install git-lfs
git lfs install

3. Download the model:

git clone https://huggingface.co/DavidAU/Erebus-Holodeck-7B-Q6_K-GGUF

Or manually:

wget -O Erebus-Holodeck-7B.Q6_K.gguf https://huggingface.co/DavidAU/Erebus-Holodeck-7B-Q6_K-GGUF/resolve/main/Erebus-Holodeck-7B.Q6_K.gguf

4. Run the notebook or script:

Load up story_creater.ipynb in Google Colab or Jupyter Notebook and let the storytelling begin.
💡 Notes

    CPU-only by default. Adjust n_gpu_layers if using a GPU.

    Best results with at least 8 threads and enough RAM to stretch out and relax.

    You can modify the story variable to kick off with your own custom setup.

📜 Output Sample

    “A woman searching for love wandered into the neon-lit ruins of a future long forgotten...”

Just kidding. Your own twisted genius goes in there. 🖤
✨ Author

Crafted by Zee and his obedient AI sidekick Nick.
For dark nights, creative blocks, and storytelling foreplay.

“We bleed stories, we just use silicon now.”
