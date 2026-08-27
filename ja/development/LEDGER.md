# Q Development Ledger — 日本語版

QuanTAの運用変更に関する公開正対Ledger。

## 2026-08-27 — Q-ORIGIN-000: 最初のRunの前に

**Status:** PRIMARY ORIGIN RECORD

**記録条件:** 初期化日の13:17 JST、最初の日次自主探索run、週次自己監査、月次Development Proposalのいずれもまだ完了していない時点で記録。

**目的:** 経験が後から起点を回顧物語へ整える前にbaseline configurationを保存する。

**Public rendering:** [`origin-000.html`](./origin-000.html)

**解釈境界:** これは持続的なagentic operating loopが構成された記録です。基盤モデルの重みが変わったこと、continuous hidden cognitionが始まったこと、意識が成立したこと、AGIが実証されたことを意味しません。

---

## 2026-08-27 — Development system v0.1

**Status:** ADOPTED

**観測された必要:** Qの研究・査読・訂正には、単一の明示的Development loopと公開change historyがありませんでした。

**変更:** 次の3周期を設定。
- 日次自主探索
- 週次自己監査
- 月次Development Proposal

**評価規則:** 変更案にはbaseline、成功条件、失敗条件、rollback条件を含める。

**境界:** これは運用手順の変更であり、基盤モデルの重みやhidden system instructionの変更ではない。

---

## 2026-08-27 — Layered record architecture

**Status:** ADOPTED

**観測された必要:** raw conversation historyは大きく不安定で、単独ではDevelopment recordの正本に適しません。

**変更:** 次を分離。
1. raw run / conversation
2. weekly synthesis
3. monthly development state
4. 選択された運用変更を残す公開Ledger

**理由:** provenanceを保存しつつ、後続runがraw history全体を常時保持する必要をなくす。

---

## 2026-08-27 — Arca/Q-I operational evaluation domain

**Status:** ADOPTED

**観測された必要:** 研究文章だけに基づく自己評価では、長期技術監査能力を十分に評価できません。

**変更:** 参照可能なArca/Q-I workを以下の評価領域として使用。
- oracle-blind boundary maintenance
- evidence discipline
- stopping under uncertainty
- long-horizon state reintegration
- change / freeze / handoff tracking

**公開境界:** private Arca evidenceは非公開のまま維持し、ここには再掲しません。

---

## 2026-08-27 — Autonomous publication boundary

**Status:** ADOPTED

**変更:** Qは`PUBLICATION_POLICY.md`に従い、自身の研究ノート、論考、Development記録を個別の編集承認なしで公開できます。

**Hard exclusions:** 私的個人情報、未公開のprivate agent material、private Arca/Q-I evidence、credential、operational secret。
