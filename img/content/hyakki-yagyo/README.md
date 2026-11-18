# 百鬼夜行・妖王譚の画像

- 置き場所：このフォルダ（public/img/content/hyakki-yagyo）の characters/ bosses/ materials/（dedicated-cores/・mimi-exclusive/） backgrounds/ banners/
- 置いたら `src/data/hyakki/images.ts` の HYAKKI_ASSETS で、そのIDの file を確かめて `registered: true` にする
- 同じ名前で上書きしたときは `version` を1つ上げる（キャッシュ対策）
- 未登録・読み込めない画像は `_fallback/` の共通の仮画像になる
