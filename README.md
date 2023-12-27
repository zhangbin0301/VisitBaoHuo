# VisitBaoHuo
说明：如果是用仓库读取链接，则仓库存放url.yaml，url1.yaml，url2.yaml，url3.yaml分别对应四个BAOHUO_URL，每行一个链接

变量名	用法

NEZHA_SERVER	哪吒服务器

NEZHA_KEY	哪吒密钥

NEZHA_PORT	哪吒端口(默认443）

NEZHA_TLS	哪吒开启tls（默认为1，开启）

BAOHUO_URL	带https://，多个地址用;隔开，常规访问保活，适合glitch类，24小时不间断保活

BAOHUO_URL1	常规访问保活，可设置TIME1变量控制停止保活时间，TIME1默认设置2,5,表示北京时间2到5点

BAOHUO_URL2	常规访问保活，可设置TIME2变量控制停止保活时间，TIME2默认设置0,6,表示北京时间0到6点

BAOHUO_URL3	一直打开网页保活，适合codesandbox类，可设置TIME3变量控制停止保活时间，TIME3默认设置1,6,表示北京时间1到6点

GH_PAT	github仓库个人密钥，此变量是为了读取仓库链接，如果设置了上面的BAOHUO_URL，不要设置此变量，

GH_REPO	github私密仓库链接，格式:github.com/xx/xx.git,配合上面的GH_PAT读取仓库链接
