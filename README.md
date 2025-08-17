This project explores how different sampling parameters affect LLM outputs in real-time playgrounds.

## 🔑 Experiments
- Ran prompts in **Google AI Studio (Gemini Playground)** and **Cohere Playground**.  
- Compared outputs at varying **temperature** and **top-p** values.  
- Observed how **creativity vs. coherence** shifts with parameter changes.  
- Explored **Cohere embeddings** to visualize semantic differences between responses.  

## 📸 Screenshots
See the [`screenshots/`](./screenshots) folder for side-by-side outputs.

Example:

- **Temperature = 0.0** → Deterministic, nearly identical answers.  
- **Temperature = 1.5** → Diverse, creative, sometimes incoherent answers.  

## 📚 Findings
- Low temp → factual, repetitive, stable.  
- High temp → more creative, but risk of hallucination.  
- Low top-p → safer vocabulary.  
- High top-p → more variety, occasional off-topic drift.  
- Embeddings revealed clear **semantic clustering** for similar answers, and dispersion for diverse/high-temp outputs.  

## 🚀 Next Steps
- Reproduce experiments programmatically in Colab.  
- Compare multiple LLMs (Gemini, Cohere, ChatGPT, DeepSeek).  
