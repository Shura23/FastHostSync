# SteamHostSync
第一次用go写的项目，写的比较烂，欢迎大佬指出错误。

## 1. 实现
对Hosts进行一个新的更  
解决Steam、github访问问题

## 2. 使用方法
## 自动方法(使用工具)
推荐使用Hosts管理工具[SwitchHosts](https://github.com/oldj/SwitchHosts) 
[SwitchHosts备用下载源](https://nas.iaimi.info/s/nT5pb8jMQp32QwB)
### 开机自启动SwitchHosts
win + R 后执行 `shell:startup`    
![](/img/1.png)  
将快捷方式复制进去即可  
![](/img/2.png)  
### 配置SwitchHosts实现自动更新  
可选的URL有:
如果访问不到GitHub可以尝试将`github.com`替换为`hub.fastgit.xyz`(国内镜像)
1. ALL: `https://raw.githubusercontent.com/Clov614/SteamHostSync/main/Hosts`  
2. Steam: `https://raw.githubusercontent.com/Clov614/SteamHostSync/main/Hosts_steam`  
3. github: `https://raw.githubusercontent.com/Clov614/SteamHostSync/main/Hosts_github`    
`镜像地址:`
4. All: `https://raw.sevencdn.com/Clov614/SteamHostSync/main/Hosts`  
5. Steam: `https://raw.sevencdn.com/Clov614/SteamHostSync/main/Hosts_steam`  
6. github: `https://raw.sevencdn.com/Clov614/SteamHostSync/main/Hosts_github`  

![](/img/3.png)

## 手动方式
#### 1. hosts 文件在每个系统的位置不一，详情如下:
- Windows 系统：`C:\Windows\System32\drivers\etc\hosts`
- Linux 系统：`/etc/hosts`
- Mac（苹果电脑）系统：`/etc/hosts`

#### 2. 修改方法
复制下面的内容至hosts尾部(追加在文本末尾)

```
#github Start
140.82.112.25			alive.github.com
185.199.108.154			docs.github.com
140.82.112.26			live.github.com
140.82.113.13			uploads.github.com
185.199.108.153			training.github.com
185.199.111.133			objects.githubusercontent.com
185.199.110.153			metamask.github.io
185.199.111.153			pages.github.com
13.107.42.16			pipelines.actions.githubusercontent.com
185.199.109.153			customer-stories-feed.github.com
185.199.108.154			github.githubassets.com
140.82.113.21			central.github.com
140.82.112.21			viewscreen.githubusercontent.com
185.199.109.133			desktop.githubusercontent.com
185.199.110.133			raw.github.com
185.199.109.133			repository-images.githubusercontent.com
185.199.110.153			assets-cdn.github.com
185.199.109.133			github.map.fastly.net
3.5.8.191			github-production-release-asset-2e65be.s3.amazonaws.com
3.5.27.81			github-production-repository-file-5c1aeb.s3.amazonaws.com
52.217.120.113			github-production-user-asset-6210df.s3.amazonaws.com
185.199.108.133			camo.githubusercontent.com
185.199.109.133			github.map.fastly.net
151.101.65.194			github.global.ssl.fastly.net
185.199.108.133			gist.githubusercontent.com
140.82.114.29			githubapp.com
192.0.66.2			github.blog
52.217.125.97			github-cloud.s3.amazonaws.com
185.199.108.153			githubstatus.com
185.199.110.153			guides.github.com
140.82.113.17			help.github.com
140.82.114.17			github.community
140.82.113.3			gist.github.com
185.199.108.153			github.io
140.82.114.3			github.com
192.0.66.2			github.blog
140.82.112.5			api.github.com
185.199.109.133			raw.githubusercontent.com
185.199.110.153			archiveprogram.github.com
185.199.108.153			assets-cdn.github.com
185.199.111.133			user-images.githubusercontent.com
185.199.108.133			favicons.githubusercontent.com
185.199.109.133			avatars5.githubusercontent.com
185.199.111.133			avatars4.githubusercontent.com
185.199.111.133			avatars3.githubusercontent.com
185.199.111.133			avatars2.githubusercontent.com
185.199.109.133			avatars6.githubusercontent.com
185.199.109.133			avatars7.githubusercontent.com
185.199.110.133			avatars8.githubusercontent.com
185.199.108.133			avatars1.githubusercontent.com
185.199.110.133			avatars0.githubusercontent.com
185.199.111.133			avatars.githubusercontent.com
185.199.111.133			cloud.githubusercontent.com
140.82.112.22			central.github.com
140.82.114.10			codeload.github.com
52.217.97.220			github-cloud.s3.amazonaws.com
52.217.117.113			github-com.s3.amazonaws.com
52.217.64.220			github-production-release-asset-2e65be.s3.amazonaws.com
54.231.202.145			github-production-user-asset-6210df.s3.amazonaws.com
3.5.2.87			github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.111.153			githubstatus.com
140.82.113.17			community.github.com
52.224.38.193			github.dev
185.199.110.133			media.githubusercontent.com
#github End
# Last Update Time : 2024-09-11 13:18:03 

#steam Start
23.210.138.105			steamcommunity.com
23.62.69.145			www.steamcommunity.com
23.62.69.145			steampowered.com
23.62.69.145			steamgames.com
23.210.138.105			steamcommunity.com
23.220.246.164			steamcommunity-a.akamaihd.net
23.219.49.122			store.steampowered.com
23.210.138.105			api.steampowered.com
23.210.138.105			help.steampowered.com
23.220.246.169			store.akamai.steamstatic.com
23.47.48.98			steamcdn-a.akamaihd.net
23.220.246.181			steamstore-a.akamaihd.net
23.220.246.175			cdn.akamai.steamstatic.com
23.62.69.145			steam-chat.com
23.220.246.164			community.akamai.steamstatic.com
23.220.246.164			cdn.steamcommunity.com
23.47.48.121			cdn.steampowered.com
23.220.246.181			cdn.store.steampowered.com
23.220.246.181			media.steampowered.com
#steam End
# Last Update Time : 2024-09-11 13:18:05 

#Ubisoft_download Start
23.212.72.239			static3.cdn.Ubi.com
23.32.129.102			static2.cdn.Ubi.com
####			static1.cdn.Ubi.com
#Ubisoft_download End
# Last Update Time : 2024-09-11 13:18:05 

#docker Start
141.193.213.20			docker.com
44.193.181.103			hub.docker.com
18.160.200.81			docs.docker.com
104.19.167.24			login.docker.com
54.196.99.49			registry.hub.docker.com
44.193.181.103			docker.io
34.226.69.105			registry-1.docker.io
54.196.99.49			index.docker.io
#docker End
# Last Update Time : 2024-09-11 13:18:05 

#Brave browser Start
18.64.183.117			brave.com
151.101.193.32			laptop-updates.brave.com
#Brave browser End
# Last Update Time : 2024-09-11 13:18:05 

#Tor browser Start
204.8.99.144			www.torproject.org
95.216.163.36			community.torproject.org
116.202.120.165			blog.torproject.org
#Tor browser End
# Last Update Time : 2024-09-11 13:18:05 

#Tails OS Start
94.142.244.34			tails.net
204.13.164.63			download.tails.net
#Tails OS End
# Last Update Time : 2024-09-11 13:18:05 

#Encrypt DNS Start
217.160.156.119			dns.oszx.co
172.67.153.195			0ms.dev
45.90.28.0			anycast.dns.nextdns.io
104.16.133.229			dns.cloudflare.com
146.112.41.2			doh.opendns.com
158.64.1.29			kaitain.restena.lu
137.66.7.89			max.rethinkdns.com
76.76.2.11			freedns.controld.com
149.248.217.117			dns.dnswarden.com
#Encrypt DNS End
# Last Update Time : 2024-09-11 13:18:06 

#EA Start
23.197.16.181			www.ea.com
23.43.242.137			origin-a.akamaihd.net
23.32.129.8			pl.ea.com
23.60.30.171			media.contentapi.ea.com
23.32.129.8			nds-network-nav.ea.com
#EA End
# Last Update Time : 2024-09-11 13:18:06 

#gitlab Start
172.65.251.78			gitlab.com
172.65.251.78			www.gitlab.com
104.17.74.206			page.gitlab.com
104.18.39.11			packages.gitlab.com
104.18.249.37			support.gitlab.com
104.18.39.11			customers.gitlab.com
172.65.216.50			staging.gitlab.com
104.16.53.111			federal-support.gitlab.com
35.227.35.254			registry.gitlab.com
108.162.192.97			evelup.gitlab.com
172.64.148.245			chef.gitlab.com
#gitlab End
# Last Update Time : 2024-09-11 13:18:06 

#debian Start
199.232.98.132			deb.debian.org
#debian End
# Last Update Time : 2024-09-11 13:18:06 

#iwara Start
104.26.13.96			iwara.tv
104.26.13.96			i.iwara.tv
172.67.71.154			www.iwara.tv
66.165.237.254			hime.iwara.tv
163.172.40.145			aku.iwara.tv
163.172.42.175			sukone.iwara.tv
163.172.81.17			xin.iwara.tv
163.172.40.123			uta.iwara.tv
192.211.62.190			mikoto.iwara.tv
163.172.44.153			miki.iwara.tv
172.67.71.154			api.iwara.tv
66.165.240.194			files.iwara.tv
151.115.97.15			bronya.iwara.tv
151.115.97.14			blade.iwara.tv
151.115.90.15			clara.iwara.tv
51.158.63.130			swan.iwara.tv
163.172.57.37			piko.iwara.tv
163.172.62.89			momo.iwara.tv
163.172.39.227			cul.iwara.tv
151.115.90.24			robin.iwara.tv
62.210.95.208			bailu.iwara.tv
62.210.173.23			himeko.iwara.tv
151.115.89.180			firefly.iwara.tv
151.115.97.4			lynx.iwara.tv
51.159.223.77			silverwolf.iwara.tv
62.210.173.43			pela.iwara.tv
151.115.89.253			jade.iwara.tv
151.115.97.11			welt.iwara.tv
151.115.96.228			asta.iwara.tv
151.115.90.6			sparkle.iwara.tv
151.115.90.3			yukong.iwara.tv
163.172.40.81			tei.iwara.tv
151.115.97.13			topaz.iwara.tv
151.115.90.14			kafka.iwara.tv
151.115.90.4			herta.iwara.tv
151.115.97.5			hook.iwara.tv
163.172.80.31			uni.iwara.tv
151.115.90.5			hanya.iwara.tv
#iwara End
# Last Update Time : 2024-09-11 13:18:07 

#EPIC Start
54.230.18.13			download2.epicgames.com
18.154.110.67			download3.epicgames.com
18.154.110.16			download4.epicgames.com
18.160.200.40			download.epicgames.com
23.43.242.121			epicgames-download1.akamaized.net
3.168.51.82			epic-social-social-modules-prod.ol.epicgames.com
34.231.44.82			eulatracking-public-service-prod06.ol.epicgames.com
18.160.225.4			media-cdn.epicgames.com
23.212.73.32			static-assets-prod.epicgames.com
23.223.181.152			store-content.ak.epicgames.com
3.230.83.146			tracking.epicgames.com
#EPIC End
# Last Update Time : 2024-09-11 13:18:08 

#Github: https://github.com/xiulou23/FastHostSync

```

## 激活生效
大部分情况下是直接生效，如未生效可尝试下面的办法，刷新 DNS：
1. Windows：在 CMD 窗口输入：`ipconfig /flushdns`
2. Linux 命令：`sudo nscd restart`
3. Mac 命令：`sudo killall -HUP mDNSResponder`  

## 手动配置Source.yaml文件添加新hosts  
手动下载可执行文件第一次执行后会在目录生成Source.yaml文件，可手动配置。  

```
ua : Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/100.0.4896.127 Safari/537.36
platforms:
  -
    #github :
    - github            #数组的第一个值为对应平台
    - alive.github.com  #后续值为需要解析ip地址的域名
    - live.github.com
    - github.githubassets.com
    - central.github.com
    - desktop.githubusercontent.com
    - assets-cdn.github.com
    - camo.githubusercontent.com
    - github.map.fastly.net
    - github.global.ssl.fastly.net
    - gist.github.com
    - github.io
    - github.com
    - github.blog
    - api.github.com
    - raw.githubusercontent.com
    - user-images.githubusercontent.com
    - favicons.githubusercontent.com
    - avatars5.githubusercontent.com
    - avatars4.githubusercontent.com
    - avatars3.githubusercontent.com
    - avatars2.githubusercontent.com
    - avatars1.githubusercontent.com
    - avatars0.githubusercontent.com
    - avatars.githubusercontent.com
    - codeload.github.com
    - github-cloud.s3.amazonaws.com
    - github-com.s3.amazonaws.com
    - github-production-release-asset-2e65be.s3.amazonaws.com
    - github-production-user-asset-6210df.s3.amazonaws.com
    - github-production-repository-file-5c1aeb.s3.amazonaws.com
    - githubstatus.com
    - github.community
    - github.dev
    - media.githubusercontent.com
  -
    #steam:
    - steam
    - steamcommunity.com
    - www.steamcommunity.com
    - store.steampowered.com
    - api.steampowered.com
    - help.steampowered.com
    - store.akamai.steamstatic.com
    - steamcdn-a.akamaihd.net
    - cdn.akamai.steamstatic.com
    - steam-chat.com
    - community.akamai.steamstatic.com
```
