 Gemma Text Simplifier

Build with Gemma Hackathon — GDG on Campus Makerere**
Track:Local Language & Accessibility

What This Does

Gemma Text Simplifier rewrites complex, jargon-heavy text — legal notices, academic writing, official documents — into simple, plain language anyone can understand. Paste in a dense paragraph, get back one clear, easy-to-read version, powered by Gemma 4.

 Demo

- 🎨 Live demo: https://a0ec812627806baba3.gradio.live
- 📓 Kaggle notebook:https://www.kaggle.com/code/hellenanamuyanja/notebookc55caa38ae/edit
- 🎥 Demo video:https://youtu.be/GcWIjgyS2C4

 How Gemma Is Used

This tool runs Gemma 4 (e2b-it, instruction-tuned) directly via Hugging Face Transformers on a Kaggle Notebook (GPU T4 x2). User input is wrapped in a chat-formatted prompt with explicit constraints — return exactly one simplified version, no alternative options, no glossary, no extra commentary — ensuring clean, consistent output suitable for a real app rather than a chat conversation.

Tech Stack

- Gemma 4 (e2b-it) via Hugging Face Transformers
- Python
- Gradio (web interface)
- Kaggle Notebook, GPU T4 x2

 Running This

Open `notebook.ipynb` in a Kaggle Notebook with GPU T4 x2 enabled, install dependencies, and run all cells in order:

```bash
pip install -r requirements.txt
```

The final cell launches a Gradio interface with a public shareable link.

> Note: Requires access to Gemma 4 on Kaggle (Models → google/gemma-4 → Request Access) and a GPU for reasonable inference speed.
 Why It Matters

Dense official language — government notices, legal forms, technical documents — quietly excludes readers without specialized education or fluency in formal English. This tool makes that information accessible using an open, freely runnable model. With more development, it could extend to simplifying and translating into local Ugandan languages directly.

Team

Namuyanja Hellena 

## License

MIT# build-with-gemma
