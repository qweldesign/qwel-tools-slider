# QWEL Slider Gallery

- スライドアニメーションで遷移するギャラリー
- ドラグ, ホイール操作対応 (オプション)
- **使い方**:  
  _slider.scss をバンドルした css を読み込み,  
  画面幅100%の要素内にギャラリーを配置する  
  ギャラリー本体 (div等) に [data-gallery="slider"] 属性を付与し,  
  ギャラリーインナーに (ul等) [data-gallery-main] 属性を付与し,  
  ギャラリーアイテムに (li等) [data-gallery-item] 属性を付与する
- **オプション (data属性で指定)**  
  data-flickable: ドラグ、ホイール操作に対応 (規定でOFF, ONにする場合値は不要)  
  data-aspect-ratio: アスペクト比 (SCSSも修正が必要)  
  data-gap: アイテム間隔(px) SCSSで指定不可  
  data-interval: アニメーション時間間隔  
  data-duration: アニメーション所要時間

▶ Sample DEMO: [https://qwel.design/tools/slider/]

---

## ライセンス | License

MIT License

このプロジェクトは, webサイトやランディングページの基本となるUIユーティリティとして自由に使用できることを目的としています。  
This project is intended to be freely used as a core UI utility for websites and landing pages.  

詳しくは LICENSE ファイルをご覧ください。  
See the LICENSE file for details.  

---

## 制作者 | Author

[QWEL.DESIGN](https://qwel.design)  
福井を拠点に活動するフロントエンド開発者  
Front-end developer based in Fukui, Japan  
