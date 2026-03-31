# lora-character-consistency
Improving character consistency using LoRA in Stable Diffusion

# LoRAによるキャラクター再現性改善

## 概要
Stable Diffusionにおいて同一キャラクターの再現性が低い問題を、
LoRA開発により改善したプロジェクト。

## 課題
- 同一キャラクターの顔・髪型・体型が安定しない
- 継続的なコンテンツ制作が困難

## 解決
- LoRAを用いたキャラクター特化モデルを開発
- 学習データ設計（ポーズ・角度・構図の分散）
- 過学習を防ぐためのデータ量調整

## 技術
- Stable Diffusion（Illustrious系）
- kohya_ss
- RunPod（クラウドGPU）
- ComfyUI / A1111

## 結果
- キャラクターの再現性が向上
- 継続的な画像生成が可能になった
