# AnimationMeshParticleGeneratorDocument

https://metaaa.booth.pm/items/2346037

## AnimationMeshParticleExporter使い方

本ツールはオブジェクトとアニメーションからアニメーション付きメッシュパーティクルを作成するツールです。
オブジェクトは1mesh,1material,頂点数が8192以下である必要があります。

1.unitypackageをインポートする。

2.シーンに対象のオブジェクトを配置する。

3.Animatorコンポーネントをアタッチし、AnimationControllerを設定する。
AnimationControllerがない場合は作成し、New Stateをつくりアニメーションを設定する。

4．Unity上部のバーから"AnimationMeshParticleGenerator"->"AnimationMeshParticleExporter"を選択する。

5．対象のオブジェクト欄にさきほどシーンに置いたオブジェクトをセットする。

6．"process"ボタンを押す。ものによっては長いのでかなり待つ必要があります。

7．シーンにパーティクルシステムが生成されていれば成功です。

## AlembicParticleExporter使い方

1.unitypackageをインポートする。

2.シーンに対象のAlembicを配置する。

3．Unity上部のバーから"AnimationMeshParticleGenerator"->"AlembicParticleExporter"を選択する。

4．対象のオブジェクト欄にさきほどシーンに置いたAlembicをセットする。

5．"process"ボタンを押す。ものによっては長いのでかなり待つ必要があります。

6．シーンにパーティクルシステムが生成されていれば成功です。

## マテリアルプロパティ

#### Base
Baseでは色のベースとなるテクスチャを制御できます。

<table width="100%">
<thead>
<tr><td colspan="3"><b>プロパティ名</b></td><td><b>説明</b></td></tr>
</thead>
<tbody>
<tr><td colspan="3"><b>Texture</b></td><td>
<p>
ベースマップを設定します。
</p>
</td></tr>
</p>
</td></tr>
<tr><td colspan="3"><b>Main Color</b></td><td>
<p>
全体に乗算する色を設定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Normal Map</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
ノーマルマップを設定します。
</p>
</td></tr>
<tr><td colspan="3"><b>OcclusionMap</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
オクルージョンマップを指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>HeightMap</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
HeightMapを指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>SpecularColor</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
スペキュラの色を指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Metalness</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
金属度合いを指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Roughness</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
粗さを指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Fresnel</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
フレネルの強度を指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Occlusion</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
オクルージョン強度を指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>Height</b></td><td>
<p>
<b>StandardあるいはToonの時のみ表示されます。</b>
</p>
<p>
HeightMapの強度を指定します。
</p>
</td></tr>
<tr><td colspan="3"><b>RampTexture</b></td><td>
<p>
<b>Toonの時のみ表示されます。</b>
</p>
<p>
ランプテクスチャを指定します。
</p>
</td></tr>
</tbody>
</table>


#### Emission
StandardあるいはToonの時のみ表示されます。
Emissionを制御できます。

<table width="100%">
<thead>
<tr><td colspan="3"><b>プロパティ名</b></td><td><b>説明</b></td></tr>
</thead>
<tbody>
<tr><td colspan="3"><b>EmissionMap</b></td><td>
<p>
エミッションマップを設定します。
</p>
</td></tr>
</p>
</td></tr>
<tr><td colspan="3"><b>EmissionColor</b></td><td>
<p>
エミッション色を設定します。
</p>
</tbody>
</table>

#### RimLight
リムライトを制御できます。

<table width="100%">
<thead>
<tr><td colspan="3"><b>プロパティ名</b></td><td><b>説明</b></td></tr>
</thead>
<tbody>
<tr><td colspan="3"><b>RimColor</b></td><td>
<p>
リムライトの色を設定します。
</p>
<tr><td colspan="3"><b>RimPower</b></td><td>
<p>
リムライトの強度を設定します。
</p>
<tr><td colspan="3"><b>RimRange</b></td><td>
<p>
リムライトの範囲を設定します。
</p>
</tbody>
</table>

#### Options
色々制御できます。

<table width="100%">
<thead>
<tr><td colspan="3"><b>プロパティ名</b></td><td><b>説明</b></td></tr>
</thead>
<tbody>
<tr><td colspan="3"><b>Cull</b></td><td>
<p>
 表面描画、裏面描画、両面描画を設定できます。
</p>
<tr><td colspan="3"><b>delta time</b></td><td>
<p>
アニメーション開始点のズレを設定します。
</p>
<tr><td colspan="3"><b>loop</b></td><td>
<p>
アニメーションをループするかを選択します。
</p>
<tr><td colspan="3"><b>Occlusion</b></td><td>
<p>
<b>Unlitの時のみ表示されます。</b>
</p>
<p>
仮想光源でLambertするかどうかを設定します。
</p>
<tr><td colspan="3"><b>AnimationRandomOffsetValue</b></td><td>
<p>
パーティクル毎のアニメーション開始点のランダム幅を設定します。
</p>
<tr><td colspan="3"><b>AnimationSpeed</b></td><td>
<p>
アニメーション再生速度を設定します。
</p>
<tr><td colspan="3"><b>LookAtVelocityDirection</b></td><td>
<b>SimurationSpaceがWorldのときだけ正常に動作します。</b>
<p>
Particleを進行方向に向くように回転させます。
</p>
<p>
ParticleSystemによる回転後のZ軸の向きをForwardとして進行方向の向きに回転します。
</p>
</tbody>
</table>

## RampTextureGenerator使い方

rngtm様のUnity-RampTextureGenerator (https://github.com/rngtm/Unity-RampTextureGenerator) をお借りしています。
ToonのRampMapを生成するためのツールです。

1.Unity上部のバーから"AnimationMeshParticleGenerator"->"AnimationMeshParticleExporter"を選択する。

2.保存するディレクトリとファイル名を設定し、Createボタンを押してScriptableObjectを生成します。

3.生成されたScriptableObjectのグラデーションなどのプロパティを設定します。

4ScriptableObject内のTextureをRampMapプロパティに設定します。
