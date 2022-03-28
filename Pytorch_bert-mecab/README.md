# pytorch_bert

Pytorchによるbertの実装（Mecab）

- 環境:Ubuntu18.04
- GPU:Quadro RTX 8000
- ドライバー:NVIDIA-SMI 460.32.03, Driver Version: 460.32.03, CUDA Version: 11.2
- 事前学習済みモデル:https://huggingface.co/cl-tohoku/bert-base-japanese-v2
- mecabをインストールしておくこと
- EarlyStoppingを利用する場合はhttps://github.com/Bjarten/early-stopping-pytorch からpytorchtools.pyをutilsにインストールし学習・検証のコメントアウトを外すこと
- predicted_test.csvに結果が出力される
    
pytorch環境構築方法  
https://kaedefuto.github.io/kaede_blog/posts/1/conda/

参考書籍  
https://book.mynavi.jp/ec/products/detail/id=104855
