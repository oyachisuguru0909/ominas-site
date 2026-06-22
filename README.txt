OMINAS 統合サイト（フラット構成 / 1ドメイン完結）

ファイルは全て同じ階層に置くだけ（フォルダ不要）。
  index.html       → /            コーポレートHP
  rpo.html         → /rpo         OMINAS RPO（全業界）
  medi-ho.html     → /medi-ho     メディホー
  genba.html       → /genba       ゲンバスカウト
  spothunter.html  → /spothunter  スポットハンター
  tossup.html      → /tossup      トスアップ
  vercel.json      → 拡張子なしURL設定（cleanUrls）

デプロイ：中身を全部GitHub直下へ → Vercelインポート → Deploy → 独自ドメイン割当
