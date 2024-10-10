# NeuralFusionII
NeuralFusionII is a custom transformer LLM model crafted using PyTorch, designed for enthusiasts.

Not to be confused with https://github.com/weders/NeuralFusion.

# Strengths
 - 🤓 Specifically fine tuned for mathematics, science, physics, biology and exams
 - 💪 8/42 billion parameters
 - 🔗 Chain of Thought (42b)
 - 🧪 Highly technical training data
 - 🚀 Adam optimiser, custom BPE tokenizer
 - 💥 Max 4K token input

# Additional Detail
Model is able go into technical contexts, effectively.

Precise and to the point, giving exactly the information you asked for. Nothing else; succinct dataset.

Support for custom instructions: Giving the model context by appending instructions and additional information to input prompts before inference.

Dynamic blocks in the forward() method allow for the one-to-one piping of ParaSync autoencoder outputs, to directly influence output, based on system performance and behaviour flags.

Current inference code supports integration of TypoDetectFX, a custom 7 layer fully connected filter network designed to catch problematic/sensitive prompts and/or fix a prompt before inference by a larger model (preprocessing such as: grammar correction, spelling errors, etc.).

# FAQ
**Q: Why is there no source code?**

A: Unlike NeuralWorks and NeuralWorksCustom, I’ve chosen not to make the source code public for collaboration at this time. This decision is primarily for IP protection, as NeuralFusionII is novel (ParaSync system), and I want to further research and refine the model before releasing anything. Academic publications are definitely on the horizon, but for now, I’m focused on ensuring that NeuralFusionII reaches its full potential before making it publicly available.

# Questions?

motions.07-busses@icloud.com

Thanks.
