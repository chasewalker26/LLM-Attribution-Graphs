# CAGE - Context Attribution (for LLMs) via Graph Explanations
The Official Implementation of "Explaining the Reasoning of Large Language Models Using Attribution Graphs"

 * Paper - [PREPRINT](https://iclr.cc/virtual/2025/poster/28207](https://arxiv.org/abs/2512.15663)

**To cite this software please use:**
```
@article{walker2025explaining,
  title={Explaining the Reasoning of Large Language Models Using Attribution Graphs},
  author={Walker, Chase and Ewetz, Rickard},
  journal={arXiv preprint arXiv:2512.15663},
  year={2025}
}
```

## How to Use CAGE
See `example.ipynb` for a full example of the application of the CAGE source code compared with SOTA LLM attribution methods.

It shows:
<ul>
  <li>Importing and setting up a model for prediction via a structured chat prompt.</li>
  <li>Initializing the LLM Attribution Evaluator class</li>
  <li>Loading each of the evaluation datasets (one dataset per cell)</li>
  <li>Generating attributions using integrated gradients and multiple perturbation methods with the respective classes of llm_attr.py.</li>
  <li>Using the returned LLMAttributionResult class to calculate row attributions, CAGE attributions, and illustrate the DAG explanation.</li> 
</ul>

## Replicating the Paper Experiments
To replicate the paper experiments, please see `CAGE/evaluations/*.sh`.
