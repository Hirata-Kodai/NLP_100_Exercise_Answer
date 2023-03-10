
# Table of Contents

1.  [chapter1](#org1122a53)
    1.  [06](#orgb22d27e)
    2.  [08](#org4c451ee)
    3.  [09](#org8d50741)


<a id="org1122a53"></a>

# chapter1


<a id="orgb22d27e"></a>

## 06

-   set 型に対する演算
    -   add() : 要素の追加
    -   discard() : 要素の削除
    -   |, &, - : それぞれ和，積，差集合


<a id="org4c451ee"></a>

## 08

-   文字コード -> 文字 : chr()
-   文字 -> 文字コード : ord()
    
        a = 'a'
        ord_a = ord(a)
        print(ord_a)
        print(chr(ord_a))

    97
    a


<a id="org8d50741"></a>

## 09

-   スライスを使って Index Error を回避
    
        a = ''
        print(a[1:])
        try:
        	print(a[1])
        except IndexError:
        	print('Index Error')

