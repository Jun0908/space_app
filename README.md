
## Space App Yokohama 2023 in Japan / 横浜

### [Team Aliens (チーム宇宙人)](https://2022.spaceappschallenge.org/challenges/2022-challenges/space-biology-superhero/teams/team-x-alien/project)


- Mr. Matsubara (松原さん)
- Me, Kawai (河合(記))

### Choice Theme / 選択したテーマ

- [Building the Space Biology “Model Zoo”](https://www.spaceappschallenge.org/2023/challenges/building-the-space-biology-model-zoo/?tab=resources)

- [Immersed in the Sounds of Space”](https://www.spaceappschallenge.org/2023/challenges/immersed-in-the-sounds-of-space/)

### Explanation / 説明書き

- 宇宙のどの時間＆どの場所により、
既存の生物がどのような遺伝変化が起きたのかをブロックチェーンに刻む
どのような未知の生物と人類が遭遇したのかDatasetを作る

将来的には遺伝子入力すると該当の生き物の絵が表示されるようになり、
未知の生物の遺伝子を入力しても学習データから未知の生物が表示されるようになる。

- Record the genetic variations of existing organisms based on the time and location in space using blockchain technology. Create a dataset documenting encounters between unknown organisms and humans.
In the future, inputting the genetic code of an organism will display an image of that creature. Even when the genetic code of an unknown organism is entered, an image of the unknown creature will be generated based on learned data.

（今回やったこと）
Fine Tuning Generative Art 
その生物が持っている特有の遺伝子を入力するとその生物が出力される
例えば、人間特有の遺伝子 耳が大きいなどなど

By inputting the unique genetic traits that an organism possesses, such as genes specific to humans like "large ears," the system will output an image of that organism.


- [Slide (Sorry, Only Japanese) / スライド(日本語のみ)](https://docs.google.com/presentation/d/1Umq53JqME-GUJN6TgCDA7Fu1CcQhMJTG/edit#slide=id.g15d379b926a_3_0)

- [Movie in YouTube / 紹介動画 YouTube](https://www.youtube.com/watch?v=CmSESCkDMz4)

- [Web アプリ / Web App on HuggingFace Space](https://huggingface.co/spaces/KJMAN678/create_alien_on_mars)

###  Gene to Image / 遺伝子配列により出力した画像

<div align="center">
<img src="./sample_output_images/Gene_to_Image1.png" alt="エビフライトライアングル" title="サンプル"  style="width:240px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="./sample_output_images/Gene_to_Image1.png" alt="エビフライトライアングル" title="サンプル"  style="width:240px;"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>

### Gene to Music / 遺伝子配列により出力した音源
[音楽を再生する]<audio src="/./sample_output_images/Gene_to_Music.mp3" controls></audio>

### How to Execute / 実行方法

- On Colab

  Stable_Diffusion_in_Colab
  - Open [stable_diffusion_in_Colab.ipynb on Colab](https://colab.research.google.com/drive/1Uaqmq3ibMmEwepnn4OWHf2TVboUVa14O?usp=sharing)
  
  Mubert_Text_to_Music
  - Open [Mubert_Text_to_Music.ipynb](https://colab.research.google.com/drive/1Uaqmq3ibMmEwepnn4OWHf2TVboUVa14O?usp=sharing)
 
- On Local (Mac)

```
NFT-Drop-Astar-Edition

# Clone the repository
git clone https://github.com/your-username/your-project-name.git

# Change to the project directory
cd your-project-name

# Install library
yarn install 

# Install library
yarn install 

```

### File Organization / ファイル構成

- stable_diffusion_in_Colab.ipynb
  - An executable file that performs image generation on Colab.
  - Colabで画像生成を行う実行ファイル。
- Mubert_Text_to_Music.ipynb
  - An executable file that performs music generation on Colab.
  - Colabで音楽生成を行う実行ファイル。。
- NFT-Drop-Astar-Edition
  - Folder containing the Output image described above.
  - 画像のNFTを作成する実行ファイル
- sample_output_images
  - Folder containing the Output image described above.
  - 上述の Output 画像が入ったフォルダ


### Reference site / 参考サイト

- [【AI】Mubert text to musicでテキストから作曲してみた！【音楽自動生成】](https://wakabaclass.com/2023/01/17/ai_mubert-text-to-music/)
- [【Stable Difussion Web UI】自分でLoRAデータを作成！](https://zenn.dev/laiso/articles/7af434269ffa1b)
