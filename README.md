# repo4test
## About
Git関連のツールをテストする際に利用できるリポジトリ

"Add","Delete","Modify","Rename"のそれぞれの組み合わせのコミットが計10個含まれる

## How to Use
既存のプロジェクトにsubmoduleとして追加する

例）
```
$ git submodule add -b main https://github.com/sirogane1013/repo4test.git test/resource/repo4test
```

## git --log
```
a78f09b8fcfa24ccc0da3534080e9f4a2e065902
10
D fileARRR
D fileER

14aea80b915d6da1d330057e5666768c26ffb2e6
9
R fileARR -> fileARRR
D fileCR

9c581e105a348188fabd4eea8753a6263dee73da
8
R fileA -> fileARR
R fileE -> fileER

510193339b5d246abe98f75dc157637d20537995
7
M fileAR
D fileD

f4e1f461184ceacb75ed80268e6aff4995493644
6
M fileAR
R fileC -> fileCR

be65bc0dc0390cc07cd08bfbb72fe40710699224
5
M fileAR
M fileC

d0e718916df15cbcb6a474815a6346028b6f9a2b
4
A fileE
D fileB

8f5b3ad22905e4c92a4d73b2791aed76d4afd68e
3
A fileD
R fileA -> fileAR

8652aaa2ccb537e0f47432061a75c3aeca71a311
2
A fileC
M fileA

0a48a702ed292db1ad7ef878fc8dfbbe6c113639
1
A fileA
A fileB
```