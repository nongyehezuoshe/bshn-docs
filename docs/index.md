---
hide:
  - navigation
  - toc
---

# 简介

BSH数字系列NFT是BSH社区[^1]发行的基于Chia区块链的NFT，简称BSHN。可以通过[区块浏览器](https://www.spacescan.io/xch/nft/collection/col1gz66t5m8e0fpn0ag8nthea67zll50twthpcp3kzten9xtxkk06sqtvlep9)快速浏览。

[^1]: BSH社区是为了纪念Chia的传奇人物`十万哥`而成立的社区组织，具体请参阅[十万哥的故事](https://github.com/lovehiya/BrotherShiwan-website)

BSHN在UFCG[^2]为BSH社区[^1]创作的logo（猴哥）基础上进行的二次创作。NFT的主体是一枚硬币，正面是通过随机着色的猴哥形象，下部则是该NFT的编号（1-100000）。为了与NFT图片中的编号进行区分，NFT名称里面的编号不再以阿拉伯数字的形式进行直接呈现，而是进行了base64编码，比如`#NTc0Mg==`对应`#5742`。

[^2]: The Ultimate Farmers Club (UFC) is one of the first NFT projects built on the Chia blockchain. The genesis collection(UFCG) contains 250 uniquely hand drawn profile pictures of farm animals.具体请参阅[Ultimate Farmers Club](https://twitter.com/TheHonestFarm)

为了与十万哥相呼应，BSHN的发行量定为十万，由于数量较大，所以采取变发行变铸造的模式。整个发行及铸造的过程由程序自动完成，相应程序源码开源在[GitHub平台](https://github.com/nongyehezuoshe/bshn_mint)。所有的NFT的文件则存放于[GitHub](https://github.com/nongyehezuoshe/bshn)和nft.storage[^3]

[^3]: NFT.Storage让开发者在分布式网络上存储NFT数据，使其过程变得简单、安全、免费！只需几行代码，任何人都可以借助IPFS和Filecoin保障NFT的持久储存。[nft.storage](https://nft.storage/)