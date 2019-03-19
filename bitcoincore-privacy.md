bitcoincore-privacy

![優秀的隱私](http://harding.github.io/img/bitcoin-core/slider-privacy.svg)

> 如果您每次花費或收到現金，所有交易詳情都會發佈到您的Twitter或Facebook Feed中供所有朋友查看？你可能不想再使用現金了。

每個經過確認的比特幣交易都會發佈到區塊鏈中，任何人都可以看到它。那 **為什麼人們還在使用比特幣呢？** 為什麼他們中的許多人都認為比特幣是一種私人匯款方式？

一個原因是比特幣核心和一些其他比特幣軟件試圖避免將您的真實身份與您所做的交易相關聯。區別如下：

![隱私差異：假名交易](http://harding.github.io/img/bitcoin-core/privacy-difference.svg)

如果沒有人能夠發現“5a35b”真的是Alice，那麼第二種類型的交易（假名交易）只能提供實用的隱私。這取決於你的錢包，以防止任何人建立這種聯繫。請參閱下文，了解比特幣核心的隱私與其他錢包的比較。

## 無需註冊

第三方比特幣服務可以增加或減少您的隱私。他們可以通過將您的交易與其他用戶的交易混合來增加它; 他們可以通過跟踪您的活動並直接將其與您的真實姓名或其他識別信息相關聯來減少它。

單擊下面的條目以顯示它：BitGo BitPay Blockchain.info Coinbase GreenAddress Ninki

誰知道你的信息？ **只是你** 或 **服務提供商？**
比特幣核心 Coinbase
你的真名
你的比特幣餘額
您支付的人和/或誰支付給您（在某些情況下）
你花多少錢和/或收到多少錢
您的連接來自的IP地址
誰能猜到你的信息？ **只是你** 或 **你交易的人？**
比特幣核心 Coinbase
您製作或收到的其他交易

## 接收交易的完美隱私

比特幣區塊鏈上有4000萬筆交易。你怎麼找到哪些付錢給你？以下是一些常見選項：

**詢問銀行家**
他們會監控你的每筆交易

比特幣銀行 **詢問隨機節點**
其中一些 **節點** 銷售您的數據

P2P輕量級錢包
**提出免費服務**
（實際上，有些人關心隱私）

客戶輕量級錢包 **獲得所有4000萬筆交易以**
獲得 **完美的** 接收隱私

**比特幣核心**

比特幣核心在比特幣區塊鏈上下載所有4000萬筆交易並處理它們以查找哪些交易支付給您。

這是您第一次啟動比特幣核心時需要大約4個小時，每天大約需要5分鐘才能保持更新，但它可以為您提供科學家所稱的內容  **信息理論（完美）隱私**  針對收到的交易竊聽者。

## 已發送交易的強隱私

要在區塊鏈上進行交易，您必須公開發送 - 但是如何發送它可以產生很大的不同。

![發送隱私](http://harding.github.io/img/bitcoin-core/sending-privacy.svg)

**你能猜出誰做了哪些交易？** 今天幾乎所有的點對點輕量級客戶端都沒有試圖模糊他們發送的交易。他們只是將它們發送給他們的一些或所有同伴。

比特幣核心做得更好。默認情況下，它會為所有[對等方傳遞](http://harding.github.io/en/bitcoin-core/features/network-support)事務 - 在常見條件下每天進行數千次單獨的事務 - 這使得它既[支持對等網絡](http://harding.github.io/en/bitcoin-core/features/network-support)又混淆了試圖跟踪您的事務的反隱私組織。

## Tor兼容

Tor匿名網絡有助於將您的在線活動與您的IP地址（通常與您的真實姓名密切相關）取消關聯。這大大增加了您混淆反隱私組織的能力。

一旦你[設置Tor](https://www.torproject.org/)，使用它與比特幣核心很[容易](https://en.bitcoin.it/wiki/Tor)。如果您還[設置了Tor隱藏服務](https://en.bitcoin.it/wiki/Tor#Hidden_services)，您將能夠[將移動客戶端連接](http://harding.github.io/en/bitcoin-core/features/user-interface#lightweight) 到您的比特幣核心完整節點，以便隨時隨地提高安全性和隱私性。

[立即開始使用Tor ](https://www.torproject.org/)

## 分散的同行發現

任何比特幣程序第一次連接到對等網絡時，都必須向集中管理機構詢問推薦對等體列表。

一旦程序進入網絡，它就可以以完全分散的方式向其對等方提出更多建議 - 但是 最 輕量級錢包不費心。

|P2P輕量級錢包|比特幣核心|
| --- | --- |
|每次重新啟動程序時都會詢問相同的集中服務。這可以更快。|使用對等網絡獨立發現新的對等體。在重啟時使用找到的對等體。|

這允許集中式權限將輕量級錢包連接到可以 **完全破壞輕量級事務隱私的** 不誠實對等體 **。** 那些不誠實的同行可以與不誠實的礦工合作，  **削弱輕量級安全。**

比特幣核心更喜歡分散的對等點發現，因此在它第一次啟動後，它不再需要信任集中式權限。是不是值得偶爾開始慢幾秒？

來源：http://harding.github.io/en/bitcoin-core/features/privacy