# pytorch_bert

# pytorchによるbertの実装

## [Juman](https://github.com/kaedefuto/Pytorch_bert/tree/main/Pytorch_bert-Juman "Juman")
## [Mecab](https://github.com/kaedefuto/Pytorch_bert/tree/main/Pytorch_bert-mecab "Mecab")

- 環境:Ubuntu18.04
- GPU:Quadro RTX 8000
- ドライバー:NVIDIA-SMI 460.32.03, Driver Version: 460.32.03, CUDA Version: 11.2
- 形態素解析時にストップワードを利用する場合はbert.pyの25行目と731行目のコメントアウトを外すこと
- EarlyStoppingを利用する場合はhttps://github.com/Bjarten/early-stopping-pytorch からpytorchtools.pyをutilsにインストールし学習・検証のコメントアウトを外すこと
- predicted_test.csvに結果が出力される
    
pytorch環境構築方法  
https://kaedefuto.github.io/kaede_blog/posts/1/conda/

参考書籍  
https://book.mynavi.jp/ec/products/detail/id=104855

