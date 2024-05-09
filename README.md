# streamlit_face_emotion
streamlit上でpy-featによる表情分析を行います。入力は画像、カメラどちらでも可能です。
Docker用

---
### py-feat Licence

MIT License
Copyright (c) 2022, Jin Hyun Cheong, Tiankang Xie, Sophie Byrne, Eshin Jolly, Luke Chang
https://github.com/cosanlab/py-feat/blob/main/LICENSE

---以下rikuが追記---
本システムの動かし方
1. git clone https://github.com/riku310/new_face_emo.git
2. docker-compose build => 一度buildしたらもうしない（はず）
3. docker-compose up
4. http://localhost:8501/にアクセスする

今後の展望
1. 起動するカメラを2台にする
2. 同時にふたりの表情を推定して，先に笑った方が負けになるゲーム性を追加する
3. ディレクトリの構成を改善する

参考
[streamlit]表情判定アプリを作ろう（クラウドサービス使わない）
Zenn：
https://zenn.dev/littledarwin/articles/34fc64822f2e9d
github：
https://github.com/LittleDarwin2021/streamlit_face_emotion

# branchを作ってみる

