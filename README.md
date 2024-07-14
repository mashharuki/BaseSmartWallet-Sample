# BaseSmartWallet-Sample

BaseSmartWallet を調査・学習するためのリポジトリです。

## テンプレートプロジェクトの作り方

```bash
npx @coinbase/build-onchain-apps@latest create
```

下記のように表示されれば OK!!

```bash
◇  Onchain app coffee created successfully! 🚀
│
◇  Next steps ───────────────────────────────────────────────╮
│                                                            │
│  Run cd coffee/web to navigate into your new onchain app.  │
│                                                            │
│  Run yarn to install dependencies.                         │
│                                                            │
│  Run yarn dev to start the development server.             │
│                                                            │
├────────────────────────────────────────────────────────────╯
│
└  Problems? https://github.com/coinbase/build-onchain-apps/issues
```

## 動かし方

`coffee/web`フォルダ配下で実行

- インストール

  ```bash
  yarn
  ```

- 起動

  ```bash
  yarn dev
  ```

  [実際コーヒーを購入した時にトランザクション](https://sepolia.basescan.org/tx/0x1bfdd0a797a4e2fb68390a358f98515ab5a58f8e5121fa25200dc37b8814b75d#eventlog)

### 参考文献

1. [SmartWallet - Docs](https://www.smartwallet.dev/guides/create-app/using-boat)
2. [SmartWallet - Create Template](https://buildonchainapps.xyz/)
3. [GitHub - build-onchain-apps](https://github.com/coinbase/build-onchain-apps)
4. [CoinBase Web Wallet](https://wallet.coinbase.com/assets/transactions)
