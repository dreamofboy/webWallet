这是一个去中心化的网页版Fractal钱包。


如何使用（针对程序猿，需要事先安装好git、node和npm）
1. git clone https://github.com/fractalplatform/webWallet.git
2. cd webWallet
3. npm i
4. npm run start -- -p 6666
5. 在浏览器中访问http://localhost:6666, 设置好节点信息（设置按钮位于网页右上角处，默认节点信息http://127.0.0.1:8545），包括节点IP和端口号
6. 由于Fractal采用了更容易记忆的账号体系来包装难以记忆的公私钥账号，因此在钱包里，我们需要先生成或导入公私钥，然后再生成容易记忆的账号，将公钥同账号绑定后即可使用（如转账、发行资产等操作），具体操作如下：
- 进入“账户管理”一栏中的“密钥”子栏目
- 对于首次使用本网页钱包的用户，需要初始化本钱包，点击按钮“初始化钱包/新增一对公私钥”，此时会有助记词出现，按提示操作即可，除此以外，你还可以通过导入助记词来初始化钱包，点击按钮“通过导入助记词初始化钱包”，按提示操作即可；
- 钱包初始化完成后，还可以使用直接导入私钥、导入keystore等操作，用于钱包之间的账号转移；
- 当密钥部分有公私钥后，便可进入“账号”子栏目开始创建账号，对于没有任何账号的用户，需要向官方或是其他有账号的用户获取帮助，帮您创建一个账号，您只要将账号名和账号需要绑定的公钥告知对方即可，对方就能帮您创建账号，切记不要告知对方您的私钥，当对方把账号创建好后，您便可导入账号，进而对此账号做一些操作。
