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
140.82.112.26			alive.github.com
185.199.108.154			docs.github.com
140.82.114.25			live.github.com
140.82.113.14			uploads.github.com
185.199.109.153			training.github.com
185.199.108.133			objects.githubusercontent.com
185.199.111.153			metamask.github.io
185.199.110.153			pages.github.com
13.107.42.16			pipelines.actions.githubusercontent.com
185.199.111.153			customer-stories-feed.github.com
185.199.110.154			github.githubassets.com
140.82.113.21			central.github.com
140.82.113.22			viewscreen.githubusercontent.com
185.199.109.133			desktop.githubusercontent.com
185.199.111.133			raw.github.com
185.199.111.133			repository-images.githubusercontent.com
185.199.110.153			assets-cdn.github.com
185.199.110.133			github.map.fastly.net
52.216.213.57			github-production-release-asset-2e65be.s3.amazonaws.com
52.217.135.105			github-production-repository-file-5c1aeb.s3.amazonaws.com
52.216.213.57			github-production-user-asset-6210df.s3.amazonaws.com
185.199.111.133			camo.githubusercontent.com
185.199.108.133			github.map.fastly.net
151.101.193.194			github.global.ssl.fastly.net
185.199.108.133			gist.githubusercontent.com
140.82.112.30			githubapp.com
192.0.66.2			github.blog
52.217.112.25			github-cloud.s3.amazonaws.com
185.199.110.153			githubstatus.com
185.199.110.153			guides.github.com
140.82.113.18			help.github.com
140.82.112.18			github.community
140.82.114.4			gist.github.com
185.199.111.153			github.io
140.82.114.4			github.com
192.0.66.2			github.blog
140.82.114.6			api.github.com
185.199.109.133			raw.githubusercontent.com
185.199.108.153			archiveprogram.github.com
185.199.109.153			assets-cdn.github.com
185.199.111.133			user-images.githubusercontent.com
185.199.110.133			favicons.githubusercontent.com
185.199.111.133			avatars5.githubusercontent.com
185.199.109.133			avatars4.githubusercontent.com
185.199.111.133			avatars3.githubusercontent.com
185.199.110.133			avatars2.githubusercontent.com
185.199.108.133			avatars6.githubusercontent.com
185.199.109.133			avatars7.githubusercontent.com
185.199.111.133			avatars8.githubusercontent.com
185.199.108.133			avatars1.githubusercontent.com
185.199.111.133			avatars0.githubusercontent.com
185.199.108.133			avatars.githubusercontent.com
185.199.111.133			cloud.githubusercontent.com
140.82.112.21			central.github.com
140.82.112.10			codeload.github.com
3.5.28.170			github-cloud.s3.amazonaws.com
54.231.229.89			github-com.s3.amazonaws.com
16.182.70.73			github-production-release-asset-2e65be.s3.amazonaws.com
54.231.229.89			github-production-user-asset-6210df.s3.amazonaws.com
3.5.3.22			github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.111.153			githubstatus.com
140.82.114.17			community.github.com
52.224.38.193			github.dev
185.199.108.133			media.githubusercontent.com
#github End
# Last Update Time : 2024-09-12 03:18:36 

#steam Start
23.214.234.105			steamcommunity.com
23.213.69.147			www.steamcommunity.com
23.213.69.147			steampowered.com
23.213.69.147			steamgames.com
23.214.234.105			steamcommunity.com
104.96.221.66			steamcommunity-a.akamaihd.net
23.48.9.171			store.steampowered.com
23.214.234.105			api.steampowered.com
23.214.234.105			help.steampowered.com
104.96.221.83			store.akamai.steamstatic.com
23.215.0.133			steamcdn-a.akamaihd.net
104.96.221.59			steamstore-a.akamaihd.net
104.96.221.65			cdn.akamai.steamstatic.com
23.213.69.147			steam-chat.com
104.96.221.51			community.akamai.steamstatic.com
104.96.221.51			cdn.steamcommunity.com
23.215.0.137			cdn.steampowered.com
104.96.221.83			cdn.store.steampowered.com
104.96.221.66			media.steampowered.com
#steam End
# Last Update Time : 2024-09-12 03:18:36 

#Ubisoft_download Start
23.222.201.62			static3.cdn.Ubi.com
23.221.241.203			static2.cdn.Ubi.com
184.85.248.65			static1.cdn.Ubi.com
#Ubisoft_download End
# Last Update Time : 2024-09-12 03:18:37 

#docker Start
141.193.213.21			docker.com
34.226.69.105			auth.docker.io
44.219.3.189			hub.docker.com
18.160.10.58			docs.docker.com
104.19.168.24			login.docker.com
34.226.69.105			registry.hub.docker.com
44.193.181.103			docker.io
3.219.239.5			registry-1.docker.io
34.226.69.105			index.docker.io
#docker End
# Last Update Time : 2024-09-12 03:18:37 

#Brave browser Start
3.167.56.82			brave.com
151.101.1.32			laptop-updates.brave.com
#Brave browser End
# Last Update Time : 2024-09-12 03:18:37 

#Tor browser Start
116.202.120.165			www.torproject.org
204.8.99.146			community.torproject.org
116.202.120.165			blog.torproject.org
#Tor browser End
# Last Update Time : 2024-09-12 03:18:37 

#Tails OS Start
204.13.164.63			tails.net
204.13.164.63			download.tails.net
#Tails OS End
# Last Update Time : 2024-09-12 03:18:37 

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
# Last Update Time : 2024-09-12 03:18:37 

#EA Start
23.39.184.174			www.ea.com
23.54.127.81			origin-a.akamaihd.net
23.221.241.90			pl.ea.com
23.213.94.171			media.contentapi.ea.com
23.221.241.90			nds-network-nav.ea.com
#EA End
# Last Update Time : 2024-09-12 03:18:37 

#gitlab Start
172.65.251.78			gitlab.com
172.65.251.78			www.gitlab.com
104.17.74.206			page.gitlab.com
104.18.39.11			packages.gitlab.com
104.18.248.37			support.gitlab.com
172.64.148.245			customers.gitlab.com
172.65.216.50			staging.gitlab.com
216.198.53.1			federal-support.gitlab.com
35.227.35.254			registry.gitlab.com
108.162.195.157			evelup.gitlab.com
172.64.148.245			chef.gitlab.com
#gitlab End
# Last Update Time : 2024-09-12 03:18:37 

#debian Start
146.75.30.132			deb.debian.org
#debian End
# Last Update Time : 2024-09-12 03:18:37 

#iwara Start
172.67.71.154			iwara.tv
172.67.71.154			i.iwara.tv
172.67.71.154			www.iwara.tv
66.165.237.254			hime.iwara.tv
163.172.40.145			aku.iwara.tv
163.172.42.175			sukone.iwara.tv
163.172.81.17			xin.iwara.tv
163.172.40.123			uta.iwara.tv
192.211.62.190			mikoto.iwara.tv
163.172.42.175			sukone.iwara.tv
66.165.240.196			service.iwara.tv
163.172.44.153			miki.iwara.tv
104.26.13.96			api.iwara.tv
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
# Last Update Time : 2024-09-12 03:18:38 

#EPIC Start
18.165.98.121			download2.epicgames.com
3.162.103.37			download3.epicgames.com
99.84.191.92			download4.epicgames.com
18.160.18.33			download.epicgames.com
23.54.127.75			epicgames-download1.akamaized.net
52.85.132.40			epic-social-social-modules-prod.ol.epicgames.com
34.231.44.82			eulatracking-public-service-prod06.ol.epicgames.com
3.162.112.105			media-cdn.epicgames.com
23.222.201.130			static-assets-prod.epicgames.com
23.214.245.152			store-content.ak.epicgames.com
3.230.83.146			tracking.epicgames.com
#EPIC End
# Last Update Time : 2024-09-12 03:18:38 

#google Start
142.251.179.94			update.googleapis.com
172.253.62.95			translate-pa.googleapis.com
142.251.163.101			translate.google.com
172.253.62.95			firebaseinstallations.googleapis.com
64.233.180.95			infinitedata-pa.googleapis.com
142.251.163.95			geller-pa.googleapis.com
209.85.202.188			alt1.mobile-gtalk.l.google.com
64.233.184.188			alt2.mobile-gtalk4.l.google.com
142.250.27.188			alt3.mobile-gtalk.l.google.com
142.250.153.188			alt4.mobile-gtalk4.l.google.com
142.251.9.188			alt5.mobile-gtalk.l.google.com
142.250.150.188			alt6.mobile-gtalk4.l.google.com
74.125.200.188			alt7.mobile-gtalk.l.google.com
142.250.157.188			alt8.mobile-gtalk4.l.google.com
172.253.115.95			translate.googleapis.com
142.251.163.138			www3.l.google.com
64.233.180.94			services.googleapis.cn
142.250.31.100			play-fe.googleapis.com
142.251.163.119			play-lh.googleusercontent.com
216.239.34.223			play.googleapis.com
209.85.202.188			alt1-mtalk.google.com
64.233.184.188			alt2-mtalk.google.com
142.250.27.188			alt3-mtalk.google.com
142.250.153.188			alt4-mtalk.google.com
142.251.9.188			alt5-mtalk.google.com
142.250.150.188			alt6-mtalk.google.com
74.125.200.188			alt7-mtalk.google.com
142.250.157.188			alt8-mtalk.google.com
64.233.180.95			content-autofill.googleapis.com
142.251.16.94			googlecn-lopri.l.google.com
172.253.122.94			www.googleapis.cn
#google End
# Last Update Time : 2024-09-12 03:18:38 

#xbox Start
23.221.240.9			gameclipscontent-d2009.xboxlive.com
23.218.218.145			images-eds.xboxlive.com
23.215.0.228			xbl-smooth.xboxlive.com
23.221.240.9			titlehub.xboxlive.com
23.218.218.184			compass.xboxlive.com
23.221.240.9			xnotify.xboxlive.com
13.66.204.157			activityhub.xboxlive.com
23.221.240.9			images-eds-ssl.xboxlive.com
199.46.35.122			rta.xboxlive.com
23.48.8.9			peoplehub.xboxlive.com
52.242.98.79			editorial.xboxlive.com
23.53.11.242			assets1.xboxlive.cn
23.53.11.247			assets2.xboxlive.cn
20.112.250.133			xboxlive.com
13.107.253.41			da.xboxservices.com
20.109.105.194			device.auth.xboxlive.com
#xbox End
# Last Update Time : 2024-09-12 03:18:39 

#Apkpure Start
172.67.20.93			download.pureapk.com
104.22.9.141			api.pureapk.com
172.67.11.98			t.apkpure.net
104.22.8.141			tapi.pureapk.com
172.67.20.93			rdelivery.pureapk.com
172.67.72.204			tapi.upload.app
45.33.36.159			api.sve.cc
104.233.133.90			wap.yushuwu.cloud
#Apkpure End
# Last Update Time : 2024-09-12 03:18:39 

#Microsoft Start
40.126.7.32			login.microsoftonline.com
52.165.164.15			fe3cr.delivery.mp.microsoft.com
40.83.50.89			fe2cr.update.microsoft.com
52.165.165.26			slscr.update.microsoft.com
20.94.153.70			nav-edge.smartscreen.microsoft.com
40.126.23.38			graph.microsoft.com
23.221.241.211			go.microsoft.com
13.107.253.41			static.edge.microsoftapp.net
204.79.197.203			oneocsp.microsoft.com
52.159.108.190			nf.smartscreen.microsoft.com
20.245.155.183			wdcp.microsoft.com
52.109.8.89			officeclient.microsoft.com
20.42.7.128			api-edge.cognitive.microsofttranslator.com
13.107.21.239			edge.microsoft.com
23.221.242.93			storeedgefd.dsx.mp.microsoft.com
#Microsoft End
# Last Update Time : 2024-09-12 03:18:40 

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
