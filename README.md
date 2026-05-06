# Learn from the Gap: Differential-Aware Advantage Pruning with Adaptive Rollout Sampling for GRPO


#### We have open-sourced a subset of the baseline training scripts and code. The complete implementation of our method, as well as all related code, will be released upon paper acceptance.

### Installation


```bash
cd EasyR1-FastRL
pip install -e .
```

### Baseline Training

```bash
bash examples/scr/qwen2_5_vl_7b_cppo.sh
bash examples/scr/qwen2_5_vl_7b_grpo.sh
bash examples/scr/qwen2_5_vl_7b_dapo.sh
bash examples/scr/qwen2_5_vl_7b_gspo.sh
```

### Merge Checkpoint in Hugging Face Format

```bash
python3 scripts/model_merger.py --local_dir checkpoints/easy_r1/exp_name/global_step_1/actor
```
