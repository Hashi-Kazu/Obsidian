| 大項目（SQuBOK v3 対応）        | 問数めやす | 重点度 |
| ------------------------ | ----- | --- |
| 品質マネジメント概念・モデル           | 9–10  | ★★★ |
| ソフトウェア開発プロセス（レビュー・テスト含む） | 8–9   | ★★★ |
| プロダクト品質特性／メトリクス          | 6–7   | ★★☆ |
| 品質保証・標準・規格               | 5–6   | ★★☆ |
| 品質計画・管理技法（QC7 つ道具など）     | 4–5   | ★★☆ |
| ツール・組織と人（PMBOK との関係など）   | 3–4   | ★☆☆ |

---

| #  | 日本語用語       | A                 | B                 | C                     | D                        |
| -- | ----------- | ----------------- | ----------------- | --------------------- | ------------------------ |
| 1  | 検証          | Validation        | Quality Assurance | Verification          | Audit                    |
| 2  | 妥当性確認       | Verification      | Validation        | Review                | Configuration Management |
| 3  | 欠陥密度        | Defect rate       | Defect tracking   | Defect density        | Error frequency          |
| 4  | ホワイトボックステスト | Black-box testing | System testing    | Structural testing    | Stress testing           |
| 5  | 信頼性         | Maintainability   | Availability      | Security              | Reliability              |
| 6  | 保守性         | Portability       | Maintainability   | Testability           | Reliability              |
| 7  | ウォークスルー     | Inspection        | Audit             | Walkthrough           | Peer review              |
| 8  | インスペクション    | Walkthrough       | Inspection        | Desk checking         | Review                   |
| 9  | 品質保証        | Quality control   | Verification      | Quality assurance     | Software assurance       |
| 10 | 品質管理        | Quality assurance | Quality control   | Configuration control | Process improvement      |

---

| #  | 正解 | あなた | 判定 | 補足メモ                                                     |
| -- | -- | --- | -- | -------------------------------------------------------- |
| 1  | C  | C   | ○  | Verification＝**検証**<br>Validation＝妥当性確認                  |
| 2  | B  | B   | ○  |                                                          |
| 3  | C  | A   | ✕  | **Defect density＝欠陥密度**<br>→ “／KLOC などで濃度を測る”と覚えると区別しやすい |
| 4  | C  | C   | ○  |                                                          |
| 5  | D  | D   | ○  |                                                          |
| 6  | B  | B   | ○  |                                                          |
| 7  | C  | C   | ○  |                                                          |
| 8  | B  | B   | ○  |                                                          |
| 9  | C  | C   | ○  |                                                          |
| 10 | B  | B   | ○  | **QC＝品質管理／QA＝品質保証**                                      |

---

| #  | 日本語用語     | A                  | B                     | C                     | D                        |
| -- | --------- | ------------------ | --------------------- | --------------------- | ------------------------ |
| 11 | 妥当性確認レビュー | Validation review  | Verification review   | Walkthrough           | Informal review          |
| 12 | 欠陥修正      | Error recovery     | Defect logging        | Defect correction     | Rework                   |
| 13 | 移植性       | Portability        | Reliability           | Reusability           | Maintainability          |
| 14 | 結合テスト     | Unit testing       | Integration testing   | Acceptance testing    | Regression testing       |
| 15 | テスト容易性    | Usability          | Testability           | Maintainability       | Operability              |
| 16 | リスク優先度番号  | Severity Index     | Risk Priority Number  | Risk Exposure         | Defect Index             |
| 17 | 形式的テスト技法  | Structural testing | Black-box testing     | Formal test technique | Experience-based testing |
| 18 | 工程監査      | Process audit      | Product audit         | Compliance review     | Certification            |
| 19 | 再テスト      | Re-test            | Regression test       | Confirmation test     | Retest coverage          |
| 20 | 不具合追跡票    | Incident ticket    | Defect tracking sheet | Change request        | Trouble report           |

---

| #  | 正解 | あなた | 判定 | 補足メモ                                                           |
| -- | -- | --- | -- | -------------------------------------------------------------- |
| 11 | A  | A   | ○  | Validation review＝妥当性確認レビュー                                    |
| 12 | C  | C   | ○  | Defect correction＝欠陥修正                                         |
| 13 | A  | A   | ○  | Portability＝移植性                                                |
| 14 | B  | B   | ○  | Integration testing＝結合テスト                                      |
| 15 | B  | B   | ○  | Testability＝テスト容易性                                             |
| 16 | B  | B   | ○  | Risk Priority Number（RPN）                                      |
| 17 | C  | C   | ○  | Formal test technique＝形式的テスト技法                                 |
| 18 | A  | A   | ○  | Process audit＝工程監査                                             |
| 19 | A  | B   | ✕  | **Re-test／Confirmation test＝再テスト**<br>Regression test は「退行テスト」 |
| 20 | B  | A   | ✕  | **Defect tracking sheet＝不具合追跡票**<br>Incident ticket は「インシデント票」 |

---

| #  | 日本語用語      | A                        | B                       | C                      | D                        |
| -- | ---------- | ------------------------ | ----------------------- | ---------------------- | ------------------------ |
| 21 | 退行テスト      | Regression testing       | Re-test                 | Stress testing         | System testing           |
| 22 | 使用性        | Usability                | Operability             | Portability            | Reliability              |
| 23 | レビューリーダー   | Author                   | Moderator               | Reviewer               | Scribe                   |
| 24 | 動的テスト      | Static testing           | Dynamic testing         | Functional testing     | Structural testing       |
| 25 | バウンダリ値分析   | Equivalence partitioning | Boundary value analysis | Decision table testing | State transition testing |
| 26 | 欠陥封じ込め     | Defect containment       | Defect prevention       | Fault tolerance        | Error handling           |
| 27 | 説明責任       | Accountability           | Responsibility          | Liability              | Authority                |
| 28 | 自動テスト実行ツール | Test management tool     | Capture/playback tool   | Static analysis tool   | Performance testing tool |
| 29 | プロセス改善モデル  | CMMI                     | ISO/IEC 9126            | ISO/IEC 12207          | ISTQB                    |
| 30 | 信頼度成長曲線    | Reliability growth curve | Defect density curve    | Learning curve         | Burn-down chart          |

---

| #  | 正解 | あなた | 判定 | ワンポイント                                             |
| -- | -- | --- | -- | -------------------------------------------------- |
| 21 | A  | A   | ○  | Regression testing＝退行テスト                           |
| 22 | A  | A   | ○  | Usability＝使用性                                      |
| 23 | B  | A   | ✕  | **Moderator＝レビューリーダー**<br>Author＝作成者               |
| 24 | B  | B   | ○  | Dynamic testing＝動的テスト                              |
| 25 | B  | B   | ○  | Boundary value analysis＝バウンダリ値分析                   |
| 26 | A  | A   | ○  | Defect containment＝欠陥封じ込め                          |
| 27 | A  | D   | ✕  | **Accountability＝説明責任**<br>Authority は「権限」         |
| 28 | B  | B   | ○  | Capture/Playback tool＝自動テスト実行ツール                   |
| 29 | A  | C   | ✕  | **CMMI＝プロセス改善モデル**<br>ISO 12207 は「ソフトウェアライフサイクル規格」 |
| 30 | A  | A   | ○  | Reliability growth curve＝信頼度成長曲線                   |

---

| #  | 日本語用語      | A                        | B                        | C                     | D                          |
| -- | ---------- | ------------------------ | ------------------------ | --------------------- | -------------------------- |
| 31 | 形式レビュー     | Informal review          | Walkthrough              | Formal review         | Peer review                |
| 32 | 静的解析ツール    | Dynamic analysis tool    | Static analysis tool     | Monitoring tool       | Debugger                   |
| 33 | 品質方針       | Quality plan             | Quality policy           | Quality objective     | Quality manual             |
| 34 | パレート図      | Control chart            | Scatter diagram          | Pareto chart          | Histogram                  |
| 35 | リスクベースドテスト | Risk-based testing       | Experience-based testing | Model-based testing   | Scenario-based testing     |
| 36 | レビュー記録係    | Scribe                   | Auditor                  | Moderator             | Recorder                   |
| 37 | 故障         | Error                    | Failure                  | Fault                 | Incident                   |
| 38 | エクイバレンス分割  | Equivalence partitioning | Boundary value analysis  | Cause-effect graphing | Classification tree method |
| 39 | 欠陥予防       | Defect prevention        | Defect containment       | Fault masking         | Error handling             |
| 40 | 受入テスト      | System testing           | Alpha testing            | Acceptance testing    | Beta testing               |

---

| #  | 正解                    | あなた | 判定 | ワンポイント                                |
| -- | --------------------- | --- | -- | ------------------------------------- |
| 31 | **C** (Formal review) | A   | ✕  | “形式＝Formal” と語感で覚える                   |
| 32 | **B**                 | B   | ○  | Static analysis tool＝静的解析ツール          |
| 33 | **B**                 | B   | ○  | Quality policy＝品質方針                   |
| 34 | **C**                 | C   | ○  | Pareto chart＝パレート図                    |
| 35 | **A**                 | A   | ○  | Risk-based testing＝リスクベースドテスト         |
| 36 | **A** (Scribe)        | D   | ✕  | **Scribe＝記録係**／Recorder は一般的“録音機”イメージ |
| 37 | **B**                 | B   | ○  | Failure＝故障（Error＝誤り／Fault＝欠陥）         |
| 38 | **A**                 | A   | ○  | Equivalence partitioning＝エクイバレンス分割    |
| 39 | **A**                 | A   | ○  | Defect prevention＝欠陥予防                |
| 40 | **C**                 | C   | ○  | Acceptance testing＝受入テスト              |

---

| #  | 日本語用語      | A                          | B                        | C                         | D                     |
| -- | ---------- | -------------------------- | ------------------------ | ------------------------- | --------------------- |
| 41 | 構成管理       | Configuration management   | Change control           | Versioning                | Release management    |
| 42 | 残留リスク      | Remaining risk             | Residual risk            | Latent risk               | Pending risk          |
| 43 | 分類木法       | Classification tree method | State transition testing | Decision table testing    | Mind-map testing      |
| 44 | 正常系テスト     | Negative testing           | Fault-injection testing  | Positive testing          | Robustness testing    |
| 45 | レビューア      | Auditor                    | Reviewer                 | Inspector                 | Validator             |
| 46 | 静的テスト      | Dynamic testing            | Exploratory testing      | Static testing            | Structural testing    |
| 47 | 欠陥検出率      | Defect detection rate      | Defect density           | Defect removal efficiency | Failure frequency     |
| 48 | 負荷テスト      | Stress testing             | Volume testing           | Load testing              | Performance profiling |
| 49 | リリース判定基準   | Release note               | Release criteria         | Exit criteria             | Acceptance criteria   |
| 50 | バーンアップチャート | Burn-down chart            | Burn-up chart            | Progress line chart       | Velocity chart        |

---

| #  | 正解    | あなた | 判定 | ワンポイント                             |
| -- | ----- | --- | -- | ---------------------------------- |
| 41 | **A** | A   | ○  | Configuration management＝構成管理      |
| 42 | **B** | A   | ✕  | Residual risk＝残留リスク                |
| 43 | **A** | A   | ○  | Classification tree method＝分類木法    |
| 44 | **C** | C   | ○  | Positive testing＝正常系テスト            |
| 45 | **B** | B   | ○  | Reviewer＝レビューア                     |
| 46 | **C** | C   | ○  | Static testing＝静的テスト               |
| 47 | **A** | A   | ○  | Defect detection rate＝欠陥検出率        |
| 48 | **C** | A   | ✕  | Load testing＝負荷テスト（Stress＝ストレステスト） |
| 49 | **B** | B   | ○  | Release criteria＝リリース判定基準          |
| 50 | **B** | B   | ○  | Burn-up chart＝バーンアップチャート           |

---

| カテゴリ   | 用語        | 正しい英語                         |
| ------ | --------- | ----------------------------- |
| メトリクス  | 欠陥密度      | **Defect density**            |
| テスト種別  | 再テスト      | **Re-test／Confirmation test** |
| 管理票    | 不具合追跡票    | **Defect tracking sheet**     |
| レビュー役割 | レビューリーダー  | **Moderator**                 |
| ガバナンス  | 説明責任      | **Accountability**            |
| プロセス改善 | プロセス改善モデル | **CMMI**                      |
| レビュー形式 | 形式レビュー    | **Formal review**             |
| レビュー役割 | レビュー記録係   | **Scribe**                    |
| リスク    | 残留リスク     | **Residual risk**             |
| 性能テスト  | 負荷テスト     | **Load testing**              |

---

| #  | 分野              | 問題                                                                 | A             | B           | C                 | D                 |
| -- | --------------- | ------------------------------------------------------------------ | ------------- | ----------- | ----------------- | ----------------- |
| 1  | 品質マネジメント概念・モデル  | Juran が提唱した「品質三部門」として**誤っている**ものはどれか。                              | 品質計画          | 品質保証        | 品質改善              | 品質検証              |
| 2  | ソフトウェア開発プロセス    | テスト計画書に**通常含まれない**項目はどれか。                                          | テスト完了基準       | テスト対象       | テスト環境             | 欠陥修正手順            |
| 3  | プロダクト品質特性／メトリクス | ISO/IEC 25010 における「移植性」の副特性に**該当しない**ものはどれか。                       | 適合性           | 置換性         | 共存性               | インストール容易性         |
| 4  | 品質保証・標準・規格      | **CMMI-DEV v2.0** でレベル 3 に初めて要求される概念はどれか。                          | 組織的プロセス定義     | 量的プロセス管理    | 欠陥予防              | 継続的パフォーマンス管理      |
| 5  | 品質計画・管理技法       | パレート図の正しい読み取り方として**最も適切**なものはどれか。                                  | 折れ線は累積相対度数を示す | 棒は時間経過を示す   | 棒の並びは原因をランダムに示す   | 折れ線は個別度数を示す       |
| 6  | ツール・組織と人        | レビュー役割のうち **Scribe** の主な責務はどれか。                                    | 技術的課題の判断      | レビュー議事の記録   | レビューの進行管理         | ドキュメント作成          |
| 7  | ソフトウェア開発プロセス    | 結合テストで **スレッドベース統合 (Thread-based)** を採用する主な利点はどれか。                 | エラー局在が容易      | モジュール再利用が容易 | システム全体の処理フローを早期確認 | 下位モジュールから順にテストできる |
| 8  | プロダクト品質特性       | 信頼性成長曲線で **バグ収束が遅い** 場合、まず取るべき施策として適切なのはどれか。                       | テストケースの追加     | バグ管理ツールの変更  | 残留リスクの受容          | メトリクスの報告頻度削減      |
| 9  | 品質保証・標準・規格      | **ISO 9001** において「力量 (Competence)」を確保するために組織が**最初に**行うべきことはどれか。    | 教育訓練の実施       | 必要な力量の決定    | 力量の評価             | 外部認証機関への申請        |
| 10 | 品質計画・管理技法       | **管理図 (Control chart)** 上で「2σ ～ 3σ 範囲に連続して7点」のパターンが出た。これはどの状態を示すか。 | 特別原因による異常     | 管理限界内の正常変動  | 品質改善完了            | 計測系の校正ミス          |

---

| #  | 正解    | あなた | 判定 | コメント                                                                                                            |
| -- | ----- | --- | -- | --------------------------------------------------------------------------------------------------------------- |
| 1  | **D** | D   | ○  | ジュラン三部門＝計画・**管理（Control）**・改善。検証 Verification は含まれない ([juran.com][1])                                           |
| 2  | **D** | D   | ○  | テスト計画書に「欠陥修正手順」は含まれず、欠陥管理計画として別管理                                                                               |
| 3  | **C** | D   | ✕  | Portability の副特性は **Installability / Adaptability / Replaceability**。共存性は Compatibility の要素 ([perforce.com][2]) |
| 4  | **A** | A   | ○  | CMMI-DEV レベル3で初めて要求される “Organizational Process Definition”                                                      |
| 5  | **A** | C   | ✕  | パレート図：**折れ線＝累積相対度数**、棒は要因を多い順に並べる                                                                               |
| 6  | **B** | B   | ○  | Scribe＝レビュー議事録係                                                                                                 |
| 7  | **C** | C   | ○  | スレッドベース統合は “早期にシステム全体の処理フローを確認できる” ([csis.pace.edu][3])                                                         |
| 8  | **A** | A   | ○  | 収束が遅い＝テストケース追加で網羅率を上げる                                                                                          |
| 9  | **B** | B   | ○  | ISO 9001 はまず **必要な力量を決定**する（教育は後工程）                                                                             |
| 10 | **A** | B   | ✕  | 2 σ–3 σ帯に 7 点連続 → **特別原因**の疑い（Western Electric Rule 2 の強化形） ([en.wikipedia.org][4])                             |

[1]: https://www.juran.com/blog/the-juran-trilogy-2/?utm_source=chatgpt.com "More About the Juran Trilogy"
[2]: https://www.perforce.com/blog/qac/what-is-iso-25010?utm_source=chatgpt.com "What Is ISO 25010? | Perforce Software"
[3]: https://csis.pace.edu/~marchese/cs615sp/L7New/Lec7new.html?utm_source=chatgpt.com "Chapter 13: Software Testing Strategies"
[4]: https://en.wikipedia.org/wiki/Western_Electric_rules?utm_source=chatgpt.com "Western Electric rules"

