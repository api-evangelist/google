---
title: "EmbeddingGemma 2: The Developer Guide"
url: "https://developers.googleblog.com/embeddinggemma-2-the-developer-guide/"
date: "2026-10-10"
feed_url: "https://developers.googleblog.com/feeds/posts/default"
---
EmbeddingGemma 2 is a compact, open-source multimodal embedding model that maps text, code, images, video, and audio into a unified 768-dimensional space. Developers can use the sentence-transformers library to selectively load modular modality encoders—ranging from 270M to 740M parameters—to optimize memory usage. Additionally, Matryoshka Representation Learning enables dynamic dimension truncation down to 128d, significantly reducing vector database storage requirements while maintaining high retrieval performance.
