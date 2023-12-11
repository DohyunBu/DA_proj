$[아이디어 컨셉]$
-
$단조성$ $가정을$ $만족하는$ $Multi$-$Domain$ $추정$ $이후,$ $메타$ $모델$ $기반의$ $Domain$ $Adaptation$ $기법$  

<br/>

$[방법론]$
-
$1.$ $ExU$ $Layer$ $기반의$ $Multi$-$Domain$ $Mapper$ $m$개 $학습$
- $Source$ $Domain$ $Data$ -> $Random$ $Sampling$ : $n_{t}$개
- $Target$ $Domain$ $Data$ : $n_{t}$개
- $Monotonic$ $Mapper$ : $m$개 도출

<br/>

$2.$ $Meta$-$Learning$ $기반의$ $Meta$-$Model$ $생성$
- $m$개 $Mapper$ -> $m$개 $Multi$-$Domain$ $Data$ : $m$ x $n_{s}$개
- $m$개 $Multi$-$Domain$ $Data$ -> $Meta$-$Model$ 학습

<br/>

$3.$ $Target$ $Domain$ $Adaptation$
- $n_{t}$개 $Target$ $Domain$ $Data$ -> $Meta$-$Model$ $fine$-$tuning$

<br/>

$[방향성]$
-
$<Meta$-$Model>$

$1.$ $y_{S_i} = F(X_{T_i})$

$2.$ $X_{S_i} = F(X_{T_i})$
