# Playable Layers

アバターの表情を変えたり，ものを出し入れしたり，服の色などの材質を変えたりなど，アバターに何か動きをつけたい場合，Playable Layersを編集することで実現が可能です．
Playable Layersは，実際にはUnityの機能であるAnimatorのことと同義であり，「動き」を状態遷移としてGUI上で(ノーコーディングで)定義することが可能です．

--

Avatar 3.0 におけるVRC Avatar Descriptor(以下，Descriptor)は，以下の5つのPlayable Layersからなります．
* Base
* Additive
* Gesture
* Action
* FX

これらのPalyable Layersは，アバターに動きをつけられる箇所がそれぞれ決まっており，何か動きをつけたい場合は対応するLayerを編集することになります．

## Base

歩きやジャンプ，しゃがみなどの移動に関わる動きをつけるためのLayerです．
とても複雑な遷移で成り立っているため，デフォルトで定義されているAnimatorの内容を見てよく学んでから手を付けることをおすすめします．

## Additive

泳ぎ時の呼吸など，BaseのLayerに追加動作を加えるためのLayerです．
HumanoidではないMaterial(=しっぽやけもみみなどの装飾品)に対して動きをつける場合は，Additiveの代わりにGestureで定義することが推奨されています．

## Gesture

## Action

他のAnimationの動作をすべて上書きする．

## Fx
