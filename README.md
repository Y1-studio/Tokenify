# Tokenify

**A high-performance visualizer for LLM tokenization.** 

Tokenify allows researchers and developers to analyze how LLM vocabularies segment text, providing full support for UTF-8 byte-level mapping and greedy matching to reveal the exact tokenization process.

## ⚙️ Technical Specifications

*   **Algorithm**: Implements a **Trie (Prefix Tree)** for $O(N)$ greedy longest-match tokenization, ensuring optimal performance and accuracy.
*   **Byte-Level Support**: Integrated **Byte-to-Unicode mapping** to accurately visualize multi-byte UTF-8 character fragmentation (standard in GPT and Llama architectures).
*   **Aleph Heuristic**: Employs a specialized heuristic analysis of vocabulary files to automatically detect and toggle between **Text** and **Byte** encoding modes.
*   **Privacy**: 100% client-side execution; no data is transmitted to a server, ensuring complete data privacy.

## 🌟 Key Features

*   **Vocab Agnostic**: Supports any standard JSON-based vocabulary mapping.
*   **Visual Segmentation**: Intuitive color-coded token boundaries with hoverable Token ID tooltips.
*   **Real-time Analysis**: Instantaneous token and character counts as you type.
*   **Zero-Install**: Runs entirely in the browser with no dependencies.
