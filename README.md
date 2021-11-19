# pandera_tfdv_immitation

- demo_distribution_skew.ipynb
    - カテゴリ変数、数値変数に対して、TFDVが利用している指標に合わせて分布のズレの検知ができないか実験しています。
    - panderaのextension decoratorを利用して、Check functionをカスタム実装しています。
    - pa.Checks.Check()にlambda関数を渡してあげてもカスタム実装できます。しかし、**yaml ファイルでスキーマ保存をしようとするとlambdaで作ったvalidationは無視されるという仕様になっている**ためこちらの実装を試してみました。
    
- pandera_usual_usage.ipynb




## Versions

```
pandera===0.6.5
pandas===1.3.4
numpy===1.21.3
matplotlib==3.4.3
seaborn===0.11.2
```