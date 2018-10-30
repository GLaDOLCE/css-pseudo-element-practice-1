# css-pseudo-element-practice-1
偽元素操作練習，物件做圓周運動


圓周運動有好多寫法，但目前技術力不足，未來再研究其他方法


構想：


*簡諧運動


將x軸與y軸的動作分開寫(::before & ::after)


一周分為四部分，每部分初速不同(使用預設的ease-in & ease-out，自訂斜率可參考cubic-bezier)

ease-in、ease-out其實不太準，出來的運動軌跡不會是標準圓形，之後再用


最後結合xy軸就完成圓周運動惹
