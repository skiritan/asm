# 4. 自組織の状態確認

## 

---

ASM の一般的な確認方法がわかったところで、自組織のアタックサーフェス検出状況を確認してみます。下記の手順に沿って実施してください。

１．自組織のプロジェクトに移動します

２．設定された Collection を確認します。`Standard Scan` が ドメイン名をもとにスキャンしたものです

３．`Standard Scan` のコレクションを選択し、表示させる結果を固定します

４．ダッシュボードを確認し、検出結果の概要を確認します

５．ASM が検出した Entity や Technology、Issue の確認を行います。また、どのように ASM が Entity を発見したかの確認を行ってください。

!!! memo 
    この結果は、１つのドメイン名だけでスキャンしたサンプル結果です。本番運用では、自組織の提供サービスやグループ会社などのドメイン名などを登録して運用するので、より多くのEntity や Issue を確認することができます。

!!! Info
    発見したEntityをより調査するには下記のサイト等を利用します。  
    IPアドレスの確認： [https://db-ip.com/](https://db-ip.com/)     JPRS Whois : [https://whois.jprs.jp/](https://whois.jprs.jp/)    特定サイトの調査: [https://urlscan.io/](https://urlscan.io/)

