# Large Language Models Testing Repository

This repository is dedicated to the evaluation and testing of various Large Language Models (LLMs). Here, you can find notebooks and results for each model we've assessed.

## Current Models Tested:
- [Mistral-7B-v0.1](https://huggingface.co/Open-Orca/Mistral-7B-OpenOrca) is a state-of-the-art Large Language Model (LLM) boasting 7 billion parameters. Designed as a generative text model, it is based on the transformer architecture with unique choices (**Grouped-Query Attention**, **Sliding-Window Attention**, **Byte-fallback BPE tokenizer**). Furthermore, this release is notable for its training: it has been fine-tuned on the **OpenOrca dataset**, an effort to emulate the dataset from Microsoft Research's Orca Paper. The training utilized OpenChat packing and was further enhanced with the Axolotl system. Lastly, Mistral-7B-v0.1 is trained on a selectively curated subset of data augmented from GPT-4. For this experiment, we are using a gptq version provided by https://huggingface.co/TheBloke/Mistral-7B-OpenOrca-GPTQ.

## Getting Started

1. **Clone the Repository**:
   ```
   git clone https://github.com/naoufal51/LLMs.git
   ```

2. **Navigate to the Notebook**:
   ```
   cd LLMs/notebooks
   ```

3. **Open the Desired Notebook**:
   Launch your Jupyter notebook or Jupyter lab environment and open the notebook for the respective LLM you wish to explore.

## Contribution

We welcome contributions from the community! If you've tested a new LLM or have additional insights on existing models, feel free to raise a Pull Request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add my new feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request.

## Future Plans

- Test and evaluate more upcoming LLMs.
- Add a benchmarking system to compare models based on various metrics.

## Feedback and Issues

If you'd like to report a bug, provide feedback, or have any questions, please open an issue. We appreciate all feedback and contributions.

## Acknowledgment