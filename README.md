# css-pseudo-element-practice-1
偽元素操作練習，物件做圓周運動


圓周運動也有其他寫法，像是使用rotate讓物件轉，未來再研究其他方法


大致構想：


*簡諧運動


將x軸與y軸的動作分開寫(::before & ::after)


一周分為四部分，每部分初速不同(自訂速度曲線可用cubic-bezier調整)


參考：http://cubic-bezier.com


ease-in、ease-out其實不太準，出來的運動軌跡不會是標準圓形，之後有空會再微調一下cubic-bezier函數


最後結合xy軸，4個部份的動作就完成圓周運動惹
