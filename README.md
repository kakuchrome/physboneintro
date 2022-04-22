# physbone SDKの個人的導入ドキュメント

## おさらいQ＆A
自動変換おさらい：DBアバターをクライアント自動変換とSDK内変換ツール両方あります

Q1：Dynamicboneと旧SDKは使えなくなるのか？  
A1：４月現時点では両方使えます、アップロードもできます。ただし、DBのコンポーネントはデフォルトでVRChatクライアント上でPBに変換されます。  
  
Q2:自動変換あればいじらなくてもいいじゃん？  
A2：publicアバターはしょうがないですが、変換の精度も保障できないし、今後いつかクライアント上DB使えなくなる可能性もありますので、自分でprivate上げれる人は作業しましょうしょう。

Q3：めんどくさい  
A3：やれ 誰もベータやらないから泣いた 今やる分損はしないぞ

Q4：DynamicBoneパッケージはもう導入しなくてもいい？
A4：DB向けにセットしたアバターアセットの場合、両boneの比較に使うので導入するのお勧めします。実際導入しない、missing scriptが発生している場合で変換できるかは個人で検証してない。

## SDK置き換え
![backupyourproject](img/1_lVUIBB_xouqRwhgnBU0ZVw.png)
最初にバックアップ撮りましょうねとると  
![https://medium.com/vrchat/vrchat-engine-upgrade-unity-2019-lts-57b0b2e149d7](img/unity_hub.png)
![project_folder](img/unity_project.png)  
unity本体を閉じて、プロジェクトフォルダーをコピーかZIPするだけ！unity hubでパス確認できるぞ！  

バックアップ撮ったら、次にいつも通りvrchatのダウンロードページからAVATAR SDK落として入れましょう  
＊プロジェクト内の旧SDKは削除せずにしてください。  
![](img/sdk_download.png)
（このドキュメント時にあるものはVRCSDK3-AVATAR-2022.04.21.03.29_Public.unitypackageになります）  
＊置き換えは一部変更されているファイルだけですので、脳死インポートで大体置き換えられると思います

# やったねたえちゃん これで改変しないといけないね！

