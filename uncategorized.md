# Playable Layers

アバターの表情を変えたり，ものを出し入れしたり，服の色などの材質を変えたりなど，アバターに何か動きをつけたい場合，Playable Layersを編集することで実現可能である．
Playable Layersは，実際にはUnityの機能であるAnimatorのことと同義であり，「動き」を状態遷移としてGUI上で(ノーコーディングで)定義することが可能である．

--

Avatar 3.0 におけるVRC Avatar Descriptor(以下，Descriptor)は，以下の5つのPlayable Layersからなる．
* Base
* Additive
* Gesture
* Action
* FX

これらのPalyable Layersは，アバターに動きをつけられる箇所がそれぞれ決まっており，何か動きをつけたい場合は対応するLayerを編集する形となる．
