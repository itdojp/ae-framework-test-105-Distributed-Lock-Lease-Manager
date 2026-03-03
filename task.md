# Task (Benchmark) — Distributed Lock / Lease Manager

本リポジトリは input-only spec repo です。  
この `task.md` は、別リポジトリ/別工程（出力側）で生成・実装すべき内容を定義します。

## Inputs (this repo)

- `spec/`
- `assumptions.md`

## Outputs (generated elsewhere)

- 仕様に基づく Distributed Lock / Lease Manager の実装
- 機械可読な API 契約（例: OpenAPI）
- （任意）テスト/CI

## Acceptance Criteria (minimum)

- acquire/renew/release の基本ユースケースが成立する
- リース失効（TTL）を考慮した状態遷移が成立する（仕様の範囲）
