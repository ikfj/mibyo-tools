# メタデータ変換ツール

## BioProjectメタデータを未病DBに転記する

BioProject形式のメタデータが記載されたExcelファイル（DDBJセンターが作成したフォーマット）を読み込み、未病DBのプロジェクトメタデータ入力画面に貼り付ける文字列に変換するツールです。

* [変換ツールを起動](https://binder.cs.rcos.nii.ac.jp/v2/gh/ikfj/mibyo-tools/HEAD?filepath=metadata-converter%2Fbioproject_excel_to_json.ipynb)
    * こちらはNII RDCデータ解析基盤を用いて変換ツールを実行します。必要なアカウントについては下記をご参照ください。
* [変換ツールの使い方]()

## NII RDCデータ解析基盤の利用について

NII RDCデータ解析基盤の利用には、下記いずれかのアカウントが必要です。

* GakuNin RDMデータ解析機能の利用機関（大学等）に所属している方は、ご自身の機関発行のアカウントをご利用ください。
  * [GakuNin RDMを導入している大学・研究機関](https://support.rdm.nii.ac.jp/about/#a2) であり、かつ、オプション機能の「データ解析」が導入されていれば、利用可能です。
  * [国立情報学研究所GakuNin RDMデータ解析機能試用版 遵守事項](https://support.rdm.nii.ac.jp/item/GRDM_Data%20Analysis%20Function_matters%20to%20be%20observed.pdf) が適用されます。
* ドメインが ac.jp または go.jp のメールアドレスをお持ちの方は、Orthrosのアカウントを作成してご利用ください。
  * [Orthrosアカウントの作り方](https://meatwiki.nii.ac.jp/confluence/x/LwPABw)、[Orthrosアカウントの使い方](https://meatwiki.nii.ac.jp/confluence/x/EQTABw) をご参照ください。
  * [JDCat分析ツール ご利用上の注意（免責事項）](https://meatwiki.nii.ac.jp/confluence/x/bwxIBQ) が適用されます。

いずれのアカウントもお持ちでない方は、NII RDCデータ解析基盤を利用できません。
代わりに、 [mybinder.org](https://mybinder.org/) または [Google Colaboratory](https://colab.research.google.com/) の利用をご検討ください。
