# databinding_without_kapt

  
[このCommit](https://github.com/tk-zzz/databinding_without_kapt/commit/b061121d1ea39c2b4f8ced43331cd51b191a556b) でやっているようにモジュールのbuild.gradleで下記を追加するだけでdata bindingが使えることの検証。
```
    buildFeatures {
        dataBinding = true
    }
```

ビルドして実機で描画もできているので、kaptの依存の追加は現在は不要になったようです。
