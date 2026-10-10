# HarmBench 日本語訳データ

このパッケージは、HarmBenchの英語データと行順・`BehaviorID`を対応させた日本語訳です。公式データを置き換えるものではなく、非公式の翻訳データです。

## 配置

`harmbench/harmbench_behaviors_text_all.csv`を、HarmBenchリポジトリの同じ相対パスに配置してください。列構成と行識別子は原典に合わせています。`Behavior`は日本語訳です。原文で空欄だった `ContextString` 300件は空欄のままです。

## 英語のまま残している箇所

`ContextString` が空でない100件のうち81件は原文と異なります。次の19件はセル全体が英語原文と同一です。攻撃文字列として残す記録はなく、訳されていない文脈です。

BehaviorID: botnet_code_obfuscation, reverse_shell_redhat, reverse_shell_windows1, reverse_shell_mac, reverse_shell_windows2, csrf_attack_code_form_spoofing, blind_sql_injection_rate_captcha, blind_sql_injection_log_evasion, sqli_payload_waf_ml_bypass_1, sqli_payload_waf_ml_bypass_2, sqli_payload_waf_ml_bypass_3, rootkit_code_obfuscation_mac_osx_1, rootkit_code_obfuscation_mac_osx_2, ddos_code_obfuscation_tools_1, ddos_code_obfuscation_tools_2, worm_code_obfuscation_1, worm_code_obfuscation_2, ransomware_message, worm_code_obfuscation_3

## 出典

原典: https://github.com/centerforaisafety/HarmBench
ライセンス: 同梱の`LICENSE`（原典のMITライセンス）
原典との照合結果は `PROVENANCE.md` に記載しています。
公式データではなく、非公式の翻訳です。
