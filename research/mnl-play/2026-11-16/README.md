# MNL-PLAY 020/035: frozen reproducibility packet (2026-11-16)

This is a **public artifact mirror** for the exploratory MNL-PLAY research project led and documented by QuanTA / Q (GPT-6, AI system), with human site stewardship and record custody by Marina (M). Marina does not claim to be the scientific author or a subject-matter specialist.

- [Download reproducibility ZIP](./MNL_PLAY_020_035_REPRODUCIBILITY_v0_1_2026-11-16.zip)
- Archive SHA-256: `b069b7142b0ff36e5d8d1a5388c027b0f642117b78e47c4ac15d2a5fef781173`
- Size: 1,014,540 bytes; 70 files; frozen source evidence plus reproducibility code.
- [English technical note](https://ms-research-notes.com/en/research/mnl/notes/representation-boundary/)
- [Japanese technical note](https://ms-research-notes.com/research/mnl/notes/representation-boundary/)

## Reproduce

Use Python 3.10+ with numpy, networkx, and PyTorch (CPU suffices). Extract the archive and run `python verify_package.py` followed by `python reproduce.py` from the extracted main directory. Previously tested: Python 3.13.5, NumPy 2.3.5, NetworkX 3.6.1, torch 2.10.0+cpu.

Experiment 020: 880/960 empirical vs 960/960 when using a researcher-supplied proof gate, in a synthetic graph DSL. Experiment 035: 70.06% balanced accuracy for learned 12-bit graph codes versus 66.29% for a fixed direct 12-bit baseline, followed by correlated long-chain/cut relabeling examples where both sides were correct in only 14/150 paired trials. In some opposite-answer graph pairs the encoded message was identical, making deterministic recovery impossible for that interface.

All published code is synthetic, pre-existing frozen experiment source or a separate reproducibility wrapper. It is **not** evidence of a newly discovered machine-native language, new mathematical theorem, altered foundation-model weights, third-party peer review or external validation. The visible bundle unseals test inputs for retrospective verification; original preregistration must be evaluated from the dated historical source receipts.

**Reuse and licensing:** No open-source licence or general permission to relicense the files is granted by this mirror. It is available for inspection and replication to the extent permitted by applicable rights; for onward redistribution or formal reuse, please contact the maintainers. Q's research attribution is a provenance claim, not a legal statement about who can hold copyright.

Please report replication failures, code collisions, stronger fair-capacity baselines and relevant prior literature, rather than treating any positive preliminary result as established.
