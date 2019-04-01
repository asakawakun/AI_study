# AI/機械学習で使用する数学
## 第一章 線形代数
### はじめに
機械学習や深層学習を理解するうえで、線形代数は重要な要素となってくる。  
線形代数はもともと連立方程式の解法の研究から生まれたもので、ベクトル空間における線形性という性質を持つ写像(線形写像)を扱う。  
行列や行列式というものを駆使して、線形性を持つ写像をエレガントに表現し扱うことができる。  
機械学習への応用でいうと、例えばニューラルネットワークや深層学習において、行列や行列式を活用している。  
### スカラー・ベクトル・行列について
スカラー・ベクトル・行列に関して、以下のように理解する。  
  
スカラー：大きさのみを持つ量。いわゆる我々が普段扱う「数」のことである。+-×÷の演算が可能である。ベクトルに対する係数になれる。  
ベクトル：大きさと向きを持った量。スカラーのセットで構成される。  
行列：数(スカラー)や記号や式などを縦と横に矩形状に配列したものである。また、ベクトルを並べたものとも言える。ベクトルの変換に使用したりする。  
※行列の例、2行2列の行列  
<img src="https://www.HostMath.com/Show.aspx?Code=%5Cbegin%7Bpmatrix%7D1%20%26%202%20%5C%5C-1%20%26%205%20%5Cend%7Bpmatrix%7D" />
