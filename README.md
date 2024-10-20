# FastHostSync


## 1. 实现
对Hosts进行更新  
解决Steam、github、Apkpure 、docker、EPIC、EA、gitlab、xbox、spotify、Brave Browser、TailsOS、Tor Browser等访问问题

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
1. ALL: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts`  
2. Steam: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_steam`  
3. github: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_github`
4. gitlab: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_gitlab`
5. EPIC: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_EPIC`
6. Apkpure: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_Apkpure`
7. TailsOS：`https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_Tails%20OS`
8. Tor Browser: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_Tor%20browser`
9. docker: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_docker`
10. onedrive: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_onedrive`
11. iwara: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_iwara`
12. spotify: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_spotify`
13. xbox: `https://raw.githubusercontent.com/Shura23/FastHostSync/refs/heads/main/Hosts_xbox`


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
185.199.110.154			docs.github.com
140.82.112.26			live.github.com
140.82.113.13			uploads.github.com
185.199.111.153			training.github.com
185.199.110.133			objects.githubusercontent.com
185.199.111.153			metamask.github.io
185.199.111.153			pages.github.com
13.107.42.16			pipelines.actions.githubusercontent.com
185.199.108.153			customer-stories-feed.github.com
185.199.110.154			github.githubassets.com
140.82.113.21			central.github.com
140.82.112.21			viewscreen.githubusercontent.com
185.199.111.133			desktop.githubusercontent.com
185.199.109.133			raw.github.com
185.199.109.133			repository-images.githubusercontent.com
185.199.110.153			assets-cdn.github.com
185.199.109.133			github.map.fastly.net
52.216.216.185			github-production-release-asset-2e65be.s3.amazonaws.com
52.217.71.140			github-production-repository-file-5c1aeb.s3.amazonaws.com
16.182.74.185			github-production-user-asset-6210df.s3.amazonaws.com
185.199.108.133			camo.githubusercontent.com
185.199.110.133			github.map.fastly.net
151.101.193.194			github.global.ssl.fastly.net
185.199.111.133			gist.githubusercontent.com
140.82.112.30			githubapp.com
192.0.66.2			github.blog
52.217.120.201			github-cloud.s3.amazonaws.com
185.199.108.153			githubstatus.com
185.199.111.153			guides.github.com
140.82.113.18			help.github.com
140.82.113.18			github.community
140.82.113.3			gist.github.com
185.199.108.153			github.io
140.82.112.4			github.com
192.0.66.2			github.blog
140.82.112.5			api.github.com
185.199.109.133			raw.githubusercontent.com
185.199.111.153			archiveprogram.github.com
185.199.109.153			assets-cdn.github.com
185.199.108.133			user-images.githubusercontent.com
185.199.110.133			favicons.githubusercontent.com
185.199.109.133			avatars5.githubusercontent.com
185.199.109.133			avatars4.githubusercontent.com
185.199.110.133			avatars3.githubusercontent.com
185.199.111.133			avatars2.githubusercontent.com
185.199.108.133			avatars6.githubusercontent.com
185.199.110.133			avatars7.githubusercontent.com
185.199.111.133			avatars8.githubusercontent.com
185.199.109.133			avatars1.githubusercontent.com
185.199.109.133			avatars0.githubusercontent.com
185.199.109.133			avatars.githubusercontent.com
185.199.111.133			cloud.githubusercontent.com
140.82.113.21			central.github.com
140.82.113.9			codeload.github.com
52.216.216.185			github-cloud.s3.amazonaws.com
16.182.67.97			github-com.s3.amazonaws.com
52.217.71.140			github-production-release-asset-2e65be.s3.amazonaws.com
3.5.29.57			github-production-user-asset-6210df.s3.amazonaws.com
54.231.129.121			github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.108.153			githubstatus.com
140.82.113.17			community.github.com
52.224.38.193			github.dev
185.199.110.133			media.githubusercontent.com
#github End
# Last Update Time : 2024-10-22 03:25:31 

#steam Start
23.214.234.105			steamcommunity.com
23.213.69.147			www.steamcommunity.com
23.213.69.147			steampowered.com
23.213.69.147			steamgames.com
23.215.0.145			clientconfig.akamai.steamstatic.com
103.28.54.162			ext3-hkg1.steamserver.net
104.97.85.45			test.steampowered.com
47.252.96.19			steamcloud-hkg.oss-accelerate.aliyuncs.com
193.108.88.128			ipv6check-udp.steamserver.net
104.97.85.58			steamuserimages-a.akamaihd.net
183.61.168.1			steamuserimages-a.xxghh.biz
219.152.87.114			dl.steam.clngaa.com
23.214.234.105			steamcommunity.com
104.97.85.8			steamcommunity-a.akamaihd.net
23.45.149.185			store.steampowered.com
23.214.234.105			api.steampowered.com
198.49.23.145			steampoweredmedia.com
23.214.234.105			help.steampowered.com
104.97.85.42			store.akamai.steamstatic.com
23.215.0.136			steamcdn-a.akamaihd.net
104.97.85.42			steamstore-a.akamaihd.net
23.213.69.147			steam-chat.com
104.97.85.62			community.akamai.steamstatic.com
104.97.85.39			shared.steamstatic.com
104.97.85.18			clan.steamstatic.com
104.97.85.8			cdn.steamcommunity.com
23.215.0.136			cdn.steampowered.com
104.97.85.42			cdn.store.steampowered.com
104.97.85.57			media.steampowered.com
#steam End
# Last Update Time : 2024-10-22 03:25:32 

#Ubisoft_download Start
23.222.201.62			static3.cdn.Ubi.com
23.221.241.203			static2.cdn.Ubi.com
193.108.91.206			static1.cdn.Ubi.com
#Ubisoft_download End
# Last Update Time : 2024-10-22 03:25:33 

#docker Start
141.193.213.21			docker.com
54.227.20.253			auth.docker.io
52.44.227.212			hub.docker.com
18.160.10.89			docs.docker.com
104.19.167.24			login.docker.com
54.236.113.205			registry.hub.docker.com
52.44.227.212			docker.io
54.236.113.205			registry-1.docker.io
54.236.113.205			index.docker.io
#docker End
# Last Update Time : 2024-10-22 03:25:33 

#Brave browser Start
3.167.56.108			brave.com
151.101.193.32			laptop-updates.brave.com
#Brave browser End
# Last Update Time : 2024-10-22 03:25:33 

#Tor browser Start
116.202.120.165			www.torproject.org
116.202.120.165			community.torproject.org
204.8.99.144			blog.torproject.org
#Tor browser End
# Last Update Time : 2024-10-22 03:25:33 

#Tails OS Start
204.13.164.63			tails.net
204.13.164.63			download.tails.net
#Tails OS End
# Last Update Time : 2024-10-22 03:25:33 

#Encrypt DNS Start
217.160.156.119			dns.oszx.co
172.64.41.4			mozilla.cloudflare-dns.com
104.21.88.221			0ms.dev
45.90.28.0			anycast.dns.nextdns.io
104.16.132.229			dns.cloudflare.com
146.112.41.2			doh.opendns.com
####			kaitain.restena.lu
137.66.7.89			max.rethinkdns.com
76.76.2.11			freedns.controld.com
149.248.217.117			dns.dnswarden.com
#Encrypt DNS End
# Last Update Time : 2024-10-22 03:25:33 

#EA Start
23.202.152.174			www.ea.com
23.54.127.79			origin-a.akamaihd.net
23.221.241.90			pl.ea.com
23.213.94.171			media.contentapi.ea.com
23.221.241.90			nds-network-nav.ea.com
#EA End
# Last Update Time : 2024-10-22 03:25:33 

#gitlab Start
172.65.251.78			gitlab.com
172.65.251.78			www.gitlab.com
104.17.71.206			page.gitlab.com
172.64.148.245			packages.gitlab.com
104.18.249.37			support.gitlab.com
104.18.39.11			customers.gitlab.com
172.65.216.50			staging.gitlab.com
216.198.54.1			federal-support.gitlab.com
35.227.35.254			registry.gitlab.com
108.162.192.97			evelup.gitlab.com
172.64.148.245			chef.gitlab.com
#gitlab End
# Last Update Time : 2024-10-22 03:25:34 

#debian Start
151.101.66.132			deb.debian.org
#debian End
# Last Update Time : 2024-10-22 03:25:34 

#iwara Start
104.26.13.96			iwara.tv
62.210.173.23			himeko.iwara.tv
104.26.13.96			i.iwara.tv
104.26.12.96			www.iwara.tv
66.165.237.254			hime.iwara.tv
163.172.40.145			aku.iwara.tv
163.172.42.175			sukone.iwara.tv
151.115.90.2			acheron.iwara.tv
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
# Last Update Time : 2024-10-22 03:25:34 

#EPIC Start
3.167.88.28			download2.epicgames.com
3.162.103.37			download3.epicgames.com
99.84.191.92			download4.epicgames.com
3.167.88.30			download.epicgames.com
23.54.127.74			epicgames-download1.akamaized.net
18.165.83.38			epic-social-social-modules-prod.ol.epicgames.com
54.165.45.154			eulatracking-public-service-prod06.ol.epicgames.com
3.162.112.59			media-cdn.epicgames.com
23.222.201.130			static-assets-prod.epicgames.com
23.214.245.152			store-content.ak.epicgames.com
3.232.38.37			tracking.epicgames.com
#EPIC End
# Last Update Time : 2024-10-22 03:25:34 

#google Start
172.253.62.94			update.googleapis.com
142.251.167.95			translate-pa.googleapis.com
142.251.163.101			translate.google.com
142.250.31.95			firebaseinstallations.googleapis.com
172.253.62.95			infinitedata-pa.googleapis.com
172.253.122.95			geller-pa.googleapis.com
209.85.202.188			alt1.mobile-gtalk.l.google.com
64.233.184.188			alt2.mobile-gtalk4.l.google.com
142.250.27.188			alt3.mobile-gtalk.l.google.com
142.250.153.188			alt4.mobile-gtalk4.l.google.com
142.251.9.188			alt5.mobile-gtalk.l.google.com
142.251.1.188			alt6.mobile-gtalk4.l.google.com
74.125.200.188			alt7.mobile-gtalk.l.google.com
142.250.157.188			alt8.mobile-gtalk4.l.google.com
172.253.62.95			translate.googleapis.com
142.251.163.102			www3.l.google.com
172.253.115.94			services.googleapis.cn
142.251.111.101			play-fe.googleapis.com
142.251.111.119			play-lh.googleusercontent.com
216.239.36.223			play.googleapis.com
209.85.202.188			alt1-mtalk.google.com
64.233.184.188			alt2-mtalk.google.com
142.250.27.188			alt3-mtalk.google.com
142.250.153.188			alt4-mtalk.google.com
142.251.9.188			alt5-mtalk.google.com
142.251.1.188			alt6-mtalk.google.com
74.125.200.188			alt7-mtalk.google.com
142.250.157.188			alt8-mtalk.google.com
142.251.16.95			content-autofill.googleapis.com
142.251.179.94			googlecn-lopri.l.google.com
142.251.163.94			www.googleapis.cn
#google End
# Last Update Time : 2024-10-22 03:25:35 

#xbox Start
23.221.240.9			gameclipscontent-d2009.xboxlive.com
23.218.218.138			images-eds.xboxlive.com
23.205.105.24			xbl-smooth.xboxlive.com
23.221.240.9			titlehub.xboxlive.com
23.218.218.133			compass.xboxlive.com
23.221.240.9			xnotify.xboxlive.com
52.165.145.141			activityhub.xboxlive.com
23.221.240.9			images-eds-ssl.xboxlive.com
199.46.35.125			rta.xboxlive.com
23.45.148.9			peoplehub.xboxlive.com
52.242.98.79			editorial.xboxlive.com
23.218.217.145			assets1.xboxlive.cn
23.218.217.145			assets2.xboxlive.cn
20.112.250.133			xboxlive.com
13.107.253.41			da.xboxservices.com
20.109.105.194			device.auth.xboxlive.com
#xbox End
# Last Update Time : 2024-10-22 03:25:35 

#Apkpure Start
172.67.20.93			download.pureapk.com
172.67.20.93			api.pureapk.com
104.22.42.111			t.apkpure.net
104.22.9.141			tapi.pureapk.com
104.22.9.141			rdelivery.pureapk.com
104.26.13.136			tapi.upload.app
45.33.36.159			api.sve.cc
#Apkpure End
# Last Update Time : 2024-10-22 03:25:35 

#Microsoft Start
20.190.151.6			login.microsoftonline.com
20.3.187.198			fe3cr.delivery.mp.microsoft.com
40.83.50.87			fe2cr.update.microsoft.com
4.245.163.56			slscr.update.microsoft.com
199.232.214.172			dl.delivery.mp.microsoft.com
4.153.57.10			nav-edge.smartscreen.microsoft.com
40.126.23.97			graph.microsoft.com
23.221.241.211			go.microsoft.com
13.107.253.41			static.edge.microsoftapp.net
204.79.197.203			oneocsp.microsoft.com
172.183.192.109			nf.smartscreen.microsoft.com
4.236.248.221			wdcp.microsoft.com
52.109.6.53			officeclient.microsoft.com
20.42.7.128			api-edge.cognitive.microsofttranslator.com
13.107.21.239			edge.microsoft.com
23.221.242.93			storeedgefd.dsx.mp.microsoft.com
23.53.35.203			msedgeextensions.sf.tlu.dl.delivery.mp.microsoft.com
#Microsoft End
# Last Update Time : 2024-10-22 03:25:35 

#spotify Start
104.199.241.202			ap-gae2.spotify.com
104.154.127.247			ap-guc3.spotify.com
104.199.65.9			ap-gew1.spotify.com
34.158.1.133			ap-gew4.spotify.com
34.158.255.62			ap-gue1.spotify.com
35.186.224.24			spclient.wg.spotify.com
35.186.224.24			wg.spotify.com
35.186.224.22			gae-spclient.spotify.com
23.205.105.27			audio4-ak-spotify-com.akamaized.net
23.3.13.10			heads4-ak-spotify-com.akamaized.net
23.205.105.24			audio-ak-spotify-com.akamaized.net
23.205.105.57			audio-akp-quic-spotify-com.akamaized.net
#spotify End
# Last Update Time : 2024-10-22 03:25:36 

#scdn Start
199.232.214.248			audio-fa.scdn.co
23.205.105.53			misc.scdn.co
23.205.105.53			i.scdn.co
199.232.214.248			newjams-images.scdn.co
199.232.210.248			dailymix-images.scdn.co
199.232.210.248			thisis-images.scdn.co
199.232.210.248			charts-images.scdn.co
199.232.214.248			seeded-session-images.scdn.co
199.232.214.248			download.scdn.co
#scdn End
# Last Update Time : 2024-10-22 03:25:36 

#onedrive Start
13.107.139.11			onedrive.live.com
13.107.42.12			skyapi.onedrive.live.com
23.9.161.55			api.onedrive.live.com
#onedrive End
# Last Update Time : 2024-10-22 03:25:36 

#other Start
34.203.54.31			www.ghostery.com
34.203.54.31			ghostery.com
104.233.133.90			wap.yushuwu.cloud
18.138.123.211			apkhub.co
162.214.80.67			apkhub.org
#other End
# Last Update Time : 2024-10-22 03:25:36 

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
