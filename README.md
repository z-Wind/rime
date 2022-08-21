# [官方網站](https://rime.im/)
# 檔案放置位置
* default
    * 同文(trime) => 共享文件夾
    * 小狼毫(weasel) => 不用放
* custom 
    * 用戶資料夾

# 快捷鍵說明
* 「`」：反查注音，位置在 Esc 下面
* Ctrl + 「`」：開啟方案選單
* Shift + Space：切換 全形/半形

# 各檔案簡述
* 自定前，可先看一下原檔支援的設定
* default.yaml
    * 全局設定
    * 自訂：default.custom.yaml
* <輸入法前端名>.yaml
    * 定義鍵盤配色、佈局、樣式等
    * 例如
        * 同文：trime.yaml
        * 小狼毫：weasel.yaml 
        * 鼠鬚管：squirrel.yaml
    * 自訂：<輸入法前端名>.custom.yaml
        * trime.custom.yaml
        * weasel.custom.yaml
        * squirrel.custom.yaml
* <方案標識>.dict.yaml
    * 輸入方案詞典
    * 例如：zliu.dict.yaml 
    * <詞典名>.<分詞庫名>.dict.yaml
        * 補充詞典用
        * 例如：zliu.extended.dict.yaml
* <方案標識>.schema.yaml
    * 輸入方案設計
    * 例如：zliu.schema.yaml
    * 自訂：<方案標識>.custom.yaml
        * 例如：zliu.custom.yaml
* symbols.yaml
    * 擴充的特殊符號

# Debug 小技巧
* 看 build 中的文件是否有併入設定檔

# 參考文件
* [Rime 輸入方案設計書](https://github.com/rime/home/wiki/RimeWithSchemata)
* [Schema.yaml 詳解](https://github.com/LEOYoon-Tsaw/Rime_collections/blob/master/Rime_description.md#schemayaml-%E8%A9%B3%E8%A7%A3)
* [Dict.yaml 詳解](https://github.com/LEOYoon-Tsaw/Rime_collections/blob/master/Rime_description.md#dictyaml-%E8%A9%B3%E8%A7%A3)
* [trime.yaml 詳解](https://github.com/osfans/trime/wiki/trime.yaml%E8%A9%B3%E8%A7%A3)