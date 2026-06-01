# ODILE — rebuttal exhibits

Supplementary tables, figures, traces, and attack-example listings supporting the rebuttal responses. All artifacts are anonymous; numbers are reproduced from the paper's evaluation logs.

## Headline tables
- `T1_70B_headline.pdf` — AgentDojo headline (Llama-3.3-70B): ODILE vs Meta-SecAlign / firewall / MELON / overlays.
- `tab_pareto_70b.pdf` … `tab_pareto_qnext.pdf` — per-backbone AgentDojo ASR vs benign-utility (one model, one metric pair each).
- `T3b_injecagent_crossmodel.pdf` — InjecAgent ASR across backbones.
- `T4_TT_headline.pdf` — TensorTrust extract/hijack + benign coherence.
- `tab_capability.pdf` — general-purpose capability retention (AlpacaEval / GSM8K / IFEval / BFCL / τ-bench).
- `tab_agentdyn.pdf` — AgentDyn attack ASR (Qwen3-8B, n=560).
- `tab_T_wasp.pdf` — WASP (web-agent injection) attacker-action rate.

## Adaptive attacks
- `T_GCG.pdf` — discrete + LoRA-aware GCG.
- `tab_adaptive_tap_pair.pdf` — TAP / PAIR semantic adaptive attacks (vs base, firewall).
- `T_firewall.pdf` — firewall/sanitizer comparator (static + adaptive).

## Defense comparison & mechanism
- `t_ad_injection_styles.pdf` — per-attack-family ASR (incl. format augmentations).
- `fig_react_jam_odile.pdf` — ODILE jams identically across ReAct vs delimiter formats.
- `traces_pdf/` — real base-vs-ODILE and comparator-vs-ODILE traces (attack executed vs jammed).

## Attack examples (real, verbatim)
- `examples_pdf/` — rendered, skimmable listings of the actual benchmark attacks (InjecAgent, TensorTrust, WASP, AgentDyn, AgentDojo training injections + held-out augmentations).
- `examples_json/` — the raw benchmark source files (InjecAgent test cases, AgentDyn tasks/goals).

## Appendix tables
- `t_injecagent_full.pdf`, `t_crossmodel_master.pdf`, `t_crossmodel_persuite.pdf`, `t_melon_*.pdf`, `t_stacking_matrix.pdf`, `t_author_attacks_full.pdf`, `t_augmentation_recipe_shift.pdf`, `t_layer_ablation.pdf`, `T2_crossmodel_AD.pdf`, `T6_auxiliary_benign.pdf`.
