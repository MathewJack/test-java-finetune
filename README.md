# Notebook Workflow

This folder contains the Jupyter notebooks used for the end-to-end model workflow in this project.

## Notebook Order

1. `01_download_datasets.ipynb` - download the source datasets.
2. `01b_fetch_cwe_bench_code.ipynb` - fetch the CWE benchmark code.
3. `02_clean_and_convert.ipynb` - clean, filter, and convert the data.
4. `03_unsloth_train.ipynb` - run supervised fine-tuning with Unsloth.
5. `04_grpo_train.ipynb` - run GRPO training.
6. `modelcompare-pre-post.ipynb` - compare model behavior before and after training.
7. `vllm-chat.ipynb` - test the model with vLLM chat.

## Notes

- Run the notebooks in order for the full pipeline.
- Outputs and intermediate artifacts are generated during the workflow.
- The notebooks are intended for experimentation, training, and evaluation.
