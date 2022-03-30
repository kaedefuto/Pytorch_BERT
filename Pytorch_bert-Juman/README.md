# pytorch_bert

# pytorchによるbertの実装（juman）

- 環境:Ubuntu18.04
- GPU:Quadro RTX 8000
- ドライバー:NVIDIA-SMI 460.32.03, Driver Version: 460.32.03, CUDA Version: 11.2
- 事前学習済みモデル:https://nlp.ist.i.kyoto-u.ac.jp/?ku_bert_japanese
    - ./weights:pytorch_model.bin, config.json
    - ./vocab:vocab.txt
    - ./data:train.tsv, test.tsv, test.csv
- jumanをインストールしておくこと
- 形態素解析時にストップワードを利用する場合はbert.pyの25行目と731行目のコメントアウトを外すこと
- EarlyStoppingを利用する場合はhttps://github.com/Bjarten/early-stopping-pytorch からpytorchtools.pyをutilsにインストールし学習・検証のコメントアウトを外すこと
- predicted_test.csvに結果が出力される
    
pytorch環境構築方法  
https://kaedefuto.github.io/kaede_blog/posts/1/conda/

参考書籍  
https://book.mynavi.jp/ec/products/detail/id=104855

### 最終更新2022/3/30

- Attentionの可視化部分を変更
- 出力結果を保存できるように変更
- bert.pyのBertTokenizerにtokenizeのパターンを追加（どのパターンが良いかわからないので適宜変更してください）