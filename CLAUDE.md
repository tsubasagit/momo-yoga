# CLAUDE.md — ももヨガ マッチング（shinももすた）

- `index.html` 1枚で完結（ビルドなし・外部ライブラリなし）。ブラウザで開けば動く
- 先生データは `<script>` 内の `TEACHERS`、診断は `QUESTIONS`、相性の重みは `WEIGHT`
- 保存は localStorage（`momoyoga_` 接頭辞）。読み書きは `store` 経由で try/catch 済み
- 色はピーチ系（`:root` の変数）。ATH コーポレートの濃紺ではなく、ももスタ向けの見た目
- 仕様は `SERVICE_SPEC.md`
