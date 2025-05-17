<link rel="stylesheet" href="/~kitamura/md_preview1.css" type="text/css">

[トップ](https://cs.kwansei.ac.jp/~kitamura/index.html) > [講義](https://cs.kwansei.ac.jp/~kitamura/courses.html) > 領域実習

# 領域実習A(2025年度)

[200字作文の書き方](200字作文.html)

[研究ハンドブック](https://cs.kwansei.ac.jp/~kitamura/KB/Handbook.html)

[YOLOマニュアル](https://cs.kwansei.ac.jp/~kitamura/KB/YOLO.html)

[OpenCVマニュアル](https://cs.kwansei.ac.jp/~kitamura/KB/OpenCV.html)

[GitHubマニュアル](https://cs.kwansei.ac.jp/~kitamura/KB/GitHub.html)


<!-- ## GitHub

[関本](https://github.com/Ryotaro1/test)

[中田](https://github.com/0masa9/gitaddremote)

[長峯](https://github.com/Takumi06140614/kitamura2)

[岡部](https://github.com/Okabe522/Test)

[小林](https://github.com/riki0121/kobayashi)

[野沢](https://github.com/nozawahiroto/RyouikiB)

[村井](https://github.com/AtsukiMurai/Test)

[島谷](https://github.com/shimatanikeito/Test) -->


## 課題1(ex1.py)

[ex1.jpg](images/ex1.jpg)中の人物の骨格を抽出し，顔以外のキーポイントとボーンを元の画像に描画せよ．実行例を以下に示す．

![](images/ex1-result.png)

手順：
1. ex1.jpgの画像をPythonを使って表示する．
2. 画像に何かを描画する．
3. YOLOv8を使って，キーポイント（関節）の座標を取り出す．
4. 画像上のキーポイントの位置に丸を描く．
5. 画像上のボーン（骨）の位置に直線を描く．

## 課題2(ex2.py)

Left-shoulder, Right-shoulder, Left-hip, Right-hipの4つの座標の重心点を求め，ex1で求めた画像上に描画せよ．

<!-- ## 課題2(ex2.py)

[ex2.jpg](images/ex2.jpg)中の人物(person)を抽出し，その領域を赤枠で元の画像に描画せよ．実行例を以下に示す．

![](images/ex2_ans.jpg)

## 課題2A(ex2A.py)

課題2で抽出した領域のうち，面積最大のもののみを赤枠で元の画像に描画せよ．


## 課題3(ex3.py)

[ex3b.mp4](images/ex3b.mp4)の各フレームにおいて，骨格を抽出し，ボーンを青色で動画に描画せよ．なお，Right-elbow, Right-shoulder, Right-hipの角度を求め，それが80度から100度の範囲内の場合は右腕の骨格のみ，赤色で描画せよ．

## 課題4(ex4.py)

[ex3b.mp4](images/ex3b.mp4)の各フレームにおいて，[ex1.jpg](images/ex1.jpg)を探し出し，そのフレーム番号を求めよ．

## 課題5(ex5.py)

[ex2.jpg](images/ex2.jpg)中の人物(person)を抽出し，日本代表選手（青色ジャージ）の領域のみを赤枠で元の画像に描画せよ． -->

***
<address>
<script>
document.write("Last updated: " + document.lastModified);
</script> <br>
ykitamura@kwansei.ac.jp </address>