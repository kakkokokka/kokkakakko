# 序：なぜいまベイズ統計か

哲学面の歴史的論争はなるべく軽く.  
実用面での御利益をメインにアピール.

# 原理編

- ベイズの法則

確率論の基礎はなるべく軽く.  
条件つき分布をある程度しっかり押さえた上でベイズの法則へ.

- ベイズ統計の原理

ベイズの法則をどう意思決定に使うか.  
パラメータを当てたいのか分布を当てたいのか等.

# 実際編

- 現実的に計算できるのか

無頓着にあてはめると事後分布が現実的には計算できないことを指摘.  
主な対策は次の二つ.

- 対策 1: 共役事前分布

事後分布が困難なく計算できるようなうまい事前分布を選ぶ方法.

- 対策 2: MCMC

コンピュータで擬似乱数を使って事後分布を近似的に生成する方法.  
他の節よりもページ数が必要そう.

# 発展編

- 事前分布の選択について

hyper parameter, 無情報事前分布, 仮想データとしての解釈, など.

- 事後分布の近似について

変分ベイズなど.

# (書かない予定)

Bayesian spam filter  
Bayesian network  
nonparametric Bayes

