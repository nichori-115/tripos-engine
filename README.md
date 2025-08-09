# tripos-engine
family/city のYAMLを入力に、アンカー→貪欲法で日程を自動生成し、雨天時は屋内優先へ置換するエンジン。TypeScriptライブラリ。

TripOps の心臓部：スケジューラ＆PlanBエンジン。
開始/昼寝/食事/終了のアンカー配置→近接POIを貪欲に挿入、営業時間・移動上限・屋内/屋外を考慮。
API から行程配列/PDF/ICSに渡せるデータ構造を返します。
