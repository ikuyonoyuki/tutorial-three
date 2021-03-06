# Three.js入門サイト

<a href="http://b.hatena.ne.jp/entry/" class="hatena-bookmark-button" data-hatena-bookmark-layout="vertical-large" data-hatena-bookmark-lang="ja" title="このエントリーをはてなブックマークに追加"><img src="https://b.st-hatena.com/images/entry-button/button-only@2x.png" alt="このエントリーをはてなブックマークに追加" width="20" height="20" style="border: none;" /></a><script type="text/javascript" src="https://b.st-hatena.com/js/bookmark_button.js" charset="utf-8" async="async"></script>

このサイトは、WebGLのライブラリ「[Three.js](https://threejs.org)」の入門サイトです。

初学者から学べるように基本から解説しつつ、発展的な内容までまとめています。このサイトを通して、ウェブの3Dのインタラクションデザインについて学んでいきましょう。




## Three.js 概要

[Three.js](http://www.createjs.com) は、HTML5で3Dコンテンツを制作するためのJavaScriptライブラリです。[Mr.doob](http://mrdoob.com)氏が中心となって開発されており、オープンソースソフトウェアとして個人・商用でも無償で利用できます。

![](https://ics.media/wp-content/uploads/2017/08/170704_webpack_site_three.png)

WebGLだけで3D表現をするためには、立方体一つ表示するだけでも多くのJavaScriptやGLSLコードを書く必要があり専門知識も必要です。Three.jsを使えばJavaScriptの知識だけで簡単に3Dコンテンツが作成できるため、手軽に扱えるようになります。

もともと2000年代後半のFlashの時代から、ウェブの3D表現が人気を集めてきました。今では標準技術としてのWebGLが、ゲームやビジュアライゼーションなどの多くの場面で採用されています。


## Three.js 入門編

まずは少ないコードでThree.jsの基本を学んでいきましょう。

![](../imgs/camera_orbitcontrols.png)

- [入門編](quickstart.md)
- [マテリアルとライティング](material_basic.md)
- [ジオメトリ](geometry_general.md)
- [カメラの制御方法（座標制御）](camera_position.md)
- [カメラの制御方法（OrbitControls）](camera_orbitcontrols.md)


## Three.js 基本編

Three.jsには多彩な機能が存在します。機能を習得すればするほど、実現できる表現が増えていくでしょう。


![](../imgs/material_variation_toon.png)


- [様々なマテリアル](material_variation.md)
- [様々なライト](light_variation.md)
- [影を落とす方法](light_shadowmap.md)
- [様々なカメラ](camera_variation.md)

![](../imgs/sprite.png)

- [フォグ](fog.md)
- [スプライト/ビルボード](sprite.md)
- [グループ化](object3d_group.md)
- [ワールド座標](position_world.md)
- [スクリーン座標](position_project.md)
- [モデルデータの読み込み](model_basic.md)


## Three.js 中級編

専門的な方法も覚えていきましょう。

![](../imgs/raycast.png)

- [canvasのリサイズ処理](renderer_resize.md)
- [オブジェクトとの交差を調べる](raycast.md)
- [パーティクルを大量に表示](points.md)
- [ジオメトリの結合](geometry_merge.md)

## Three.jsとECMAScript 2015+

JavaScriptの新しい仕様のECMAScript 2015（略称ES2015、別名ES6）以上では、クラスを利用できます。オブジェクト指向なプログラムで設計することで、規模の大きい開発に役立ちます。Three.jsでクラスを利用する方法を習得しましょう。

![](../imgs/index-h2-es2015.png)

- [ES2015のclassを利用する（継承）](class.md)
- [ES2015のclassを利用する（メソッド）](class_method.md)

## Three.js 数値計算

3Dでは、三角関数やベクトルの計算をする場面が多いです。実例を通して、これらを学んでいきましょう。

![](https://ics.media/wp-content/uploads/2016/08/1601_trigonometric_function1.jpg)


- [WebGL開発に役立つ三角関数の数式・概念](https://ics.media/entry/10657)
- [ベクトルの足し算・引き算](https://ics.media/entry/15043)
- [ベクトルの内積](https://ics.media/entry/15321)
- [ベクトルの外積](https://ics.media/entry/15467)

## Three.js 演出編

Three.jsを使った表現を作例を通して学びましょう。

![](https://ics.media/wp-content/uploads/2016/11/160907_magma_effect.jpg)

- [ゲーム演出に役立つマグマ表現](https://ics.media/entry/13973)
- [RPGのセーブポイント風の魔法陣](https://ics.media/entry/11401)
- [タイムリマップ表現](https://ics.media/entry/7162)
- [アイコンフォント集Font Awesomeを扱う方法](https://ics.media/entry/8385)
- [サウンドビジュアライザー](https://ics.media/entry/9105)
- [エフェクト作成ツールのEffekseerがWebGLに対応。Web表現の新兵器となるか](https://ics.media/entry/15745)

## WebGL シェーダー編

Three.jsだけだと実現できる表現の種類に限界があります。シェーダーをGLSLでカスタマイズすることで表現の種類を大きく広げられます。

![](https://ics.media/wp-content/uploads/2015/03/150311_eyecatch.png)

- [WebGLを極めるならJSライブラリを使わず書こう](https://ics.media/entry/2663)
- [Three\.jsでのぷるぷるシェーダーの作り方](https://ics.media/entry/3228)
- [シェーダーの定番画像処理8選](https://ics.media/entry/5535)


## WebGL 応用編

WebGLの最適化や次世代の仕様について理解を深めましょう。


![](https://ics.media/wp-content/uploads/2017/07/170706_webgl2_eyecatch.png)

- [WebGLのカクつき対策まとめ](https://ics.media/entry/12930)
- [サンプルで理解するWebGL 2\.0](https://ics.media/entry/16060)


## VR表現

3Dの知識はバーチャルリアリティーの実装にも役立ちます。

![](https://ics.media/wp-content/uploads/2017/01/170112_panorama_eye.jpg)

- [HTMLタグで本格VRコンテンツが作れる3Dライブラリ「A\-Frame」](https://ics.media/entry/13401)
- [お手軽360°パノラマ制作入門！ JSでパノラマビューワー](https://ics.media/entry/14490)


## Node.jsを使ったフロントエンド開発

効率のよい開発ができるよう、最新の開発環境の構築もしましょう。開発環境を整えれば最新のJavaScript言語仕様を利用でき、開発効率向上に役立つはずです。また、型定義のあるTypeScriptを使ってコード補完をフルに効かせて開発するのもおすすめです。

![](https://ics.media/wp-content/uploads/2017/08/170808_eyecatch_webpack_typescript.jpg)

- [webpack + Babelの環境構築 \(Three\.jsのサンプル付き\)](https://ics.media/entry/16028)
- [webpack + TypeScriptの環境構築 \(Three\.jsのサンプル付き\)](https://ics.media/entry/16329)


<article-author>[池田 泰延](https://twitter.com/clockmaker)</article-author>
<article-date-published>2017-11-02</article-date-published>
<article-date-modified>2017-12-04</article-date-modified>
