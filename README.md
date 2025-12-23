# ポートフォリオサイト

モダンでミニマルなデザインのポートフォリオサイトです。

## 特徴

- 🎨 **モダンでミニマルなデザイン**: 洗練されたUI/UX
- ✨ **洗練されたホバーエフェクト**: インタラクティブなアニメーション
- 📱 **レスポンシブデザイン**: モバイル、タブレット、デスクトップに対応
- 🎭 **スムーズなアニメーション**: スクロール時のフェードイン効果
- 🎯 **パフォーマンス最適化**: 軽量で高速な読み込み

## セクション

- **ヒーローセクション**: 自己紹介とCTAボタン
- **About**: プロフィールと統計情報
- **スキル**: 技術スキルの表示
- **プロジェクト**: 作品の紹介
- **お問い合わせ**: 連絡先とフォーム

## 技術スタック

- HTML5
- CSS3 (カスタムプロパティ、Flexbox、Grid)
- Vanilla JavaScript (Intersection Observer API)

## セットアップ

1. リポジトリをクローン
```bash
git clone https://github.com/h-hirano-dev/my-portfolio.git
cd my-portfolio
```

2. `index.html`をブラウザで開く
```bash
open index.html
```

または、ローカルサーバーを起動
```bash
# Python 3の場合
python -m http.server 8000

# Node.jsの場合
npx serve
```

## カスタマイズ

### 個人情報の変更

1. **名前**: `index.html`内の「Your Name」を自分の名前に変更
2. **連絡先情報**: お問い合わせセクションのメールアドレスやリンクを更新
3. **プロジェクト情報**: プロジェクトカードの内容を実際の作品に置き換え
4. **X（Twitter）リンク**: ヒーローセクションのXボタンのURLを更新

### カラーテーマの変更

`styles.css`の`:root`セクションでカラーパレットを変更できます：

```css
:root {
  --primary-color: #6366f1;
  --secondary-color: #8b5cf6;
  /* 他の色も同様に変更可能 */
}
```

## ライセンス

MIT License

## 作者

Your Name

