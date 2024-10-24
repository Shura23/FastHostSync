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
140.82.112.26			alive.github.com
185.199.109.154			docs.github.com
140.82.112.26			live.github.com
140.82.114.13			uploads.github.com
185.199.111.153			training.github.com
185.199.110.133			objects.githubusercontent.com
185.199.108.153			metamask.github.io
185.199.111.153			pages.github.com
13.107.42.16			pipelines.actions.githubusercontent.com
185.199.111.153			customer-stories-feed.github.com
185.199.108.154			github.githubassets.com
140.82.112.21			central.github.com
140.82.114.22			viewscreen.githubusercontent.com
185.199.108.133			desktop.githubusercontent.com
185.199.110.133			raw.github.com
185.199.111.133			repository-images.githubusercontent.com
185.199.111.153			assets-cdn.github.com
185.199.108.133			github.map.fastly.net
16.182.70.241			github-production-release-asset-2e65be.s3.amazonaws.com
52.216.109.59			github-production-repository-file-5c1aeb.s3.amazonaws.com
52.216.210.201			github-production-user-asset-6210df.s3.amazonaws.com
185.199.108.133			camo.githubusercontent.com
185.199.110.133			github.map.fastly.net
151.101.193.194			github.global.ssl.fastly.net
185.199.110.133			gist.githubusercontent.com
140.82.113.29			githubapp.com
192.0.66.2			github.blog
52.217.202.73			github-cloud.s3.amazonaws.com
185.199.108.153			githubstatus.com
185.199.110.153			guides.github.com
140.82.113.18			help.github.com
140.82.114.17			github.community
140.82.113.3			gist.github.com
185.199.111.153			github.io
140.82.114.3			github.com
192.0.66.2			github.blog
140.82.113.6			api.github.com
185.199.111.133			raw.githubusercontent.com
185.199.108.153			archiveprogram.github.com
185.199.108.153			assets-cdn.github.com
185.199.108.133			user-images.githubusercontent.com
185.199.110.133			favicons.githubusercontent.com
185.199.108.133			avatars5.githubusercontent.com
185.199.110.133			avatars4.githubusercontent.com
185.199.108.133			avatars3.githubusercontent.com
185.199.111.133			avatars2.githubusercontent.com
185.199.108.133			avatars6.githubusercontent.com
185.199.108.133			avatars7.githubusercontent.com
185.199.110.133			avatars8.githubusercontent.com
185.199.111.133			avatars1.githubusercontent.com
185.199.108.133			avatars0.githubusercontent.com
185.199.109.133			avatars.githubusercontent.com
185.199.109.133			cloud.githubusercontent.com
140.82.112.22			central.github.com
140.82.114.9			codeload.github.com
52.216.38.81			github-cloud.s3.amazonaws.com
52.217.82.108			github-com.s3.amazonaws.com
52.216.210.201			github-production-release-asset-2e65be.s3.amazonaws.com
52.217.1.92			github-production-user-asset-6210df.s3.amazonaws.com
52.217.163.201			github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.111.153			githubstatus.com
140.82.112.18			community.github.com
52.224.38.193			github.dev
185.199.108.133			media.githubusercontent.com
#github End
# Last Update Time : 2024-10-25 07:31:09 

#steam Start
23.214.234.105			steamcommunity.com
23.213.69.147			www.steamcommunity.com
23.213.69.147			steampowered.com
23.213.69.147			steamgames.com
104.123.152.8			clientconfig.akamai.steamstatic.com
103.28.54.162			ext3-hkg1.steamserver.net
104.102.249.176			test.steampowered.com
47.252.96.19			steamcloud-hkg.oss-accelerate.aliyuncs.com
95.100.173.129			ipv6check-udp.steamserver.net
104.102.249.177			steamuserimages-a.akamaihd.net
163.177.116.8			steamuserimages-a.xxghh.biz
219.152.87.117			dl.steam.clngaa.com
23.214.234.105			steamcommunity.com
104.102.249.208			steamcommunity-a.akamaihd.net
23.37.29.108			store.steampowered.com
23.214.234.105			api.steampowered.com
198.49.23.144			steampoweredmedia.com
23.214.234.105			help.steampowered.com
104.102.249.200			store.akamai.steamstatic.com
104.123.152.18			steamcdn-a.akamaihd.net
104.102.249.144			steamstore-a.akamaihd.net
23.213.69.147			steam-chat.com
104.102.249.194			community.akamai.steamstatic.com
104.102.249.195			shared.steamstatic.com
104.102.249.161			clan.steamstatic.com
104.102.249.208			cdn.steamcommunity.com
104.123.152.33			cdn.steampowered.com
104.102.249.200			cdn.store.steampowered.com
104.102.249.210			media.steampowered.com
#steam End
# Last Update Time : 2024-10-25 07:31:12 

#Ubisoft_download Start
104.117.189.21			static3.cdn.Ubi.com
23.11.209.98			static2.cdn.Ubi.com
184.85.248.65			static1.cdn.Ubi.com
#Ubisoft_download End
# Last Update Time : 2024-10-25 07:31:12 

#docker Start
141.193.213.21			docker.com
54.198.86.24			auth.docker.io
54.156.140.159			hub.docker.com
18.160.200.34			docs.docker.com
104.19.167.24			login.docker.com
54.198.86.24			registry.hub.docker.com
54.156.140.159			docker.io
54.227.20.253			registry-1.docker.io
54.236.113.205			index.docker.io
#docker End
# Last Update Time : 2024-10-25 07:31:13 

#Brave browser Start
18.64.183.24			brave.com
151.101.1.32			laptop-updates.brave.com
#Brave browser End
# Last Update Time : 2024-10-25 07:31:13 

#Tor browser Start
116.202.120.165			www.torproject.org
116.202.120.165			community.torproject.org
204.8.99.146			blog.torproject.org
#Tor browser End
# Last Update Time : 2024-10-25 07:31:13 

#Tails OS Start
94.142.244.34			tails.net
204.13.164.63			download.tails.net
#Tails OS End
# Last Update Time : 2024-10-25 07:31:13 

#Encrypt DNS Start
217.160.156.119			dns.oszx.co
162.159.61.4			mozilla.cloudflare-dns.com
172.67.153.195			0ms.dev
45.90.28.0			anycast.dns.nextdns.io
104.16.133.229			dns.cloudflare.com
146.112.41.2			doh.opendns.com
194.58.196.32			kaitain.restena.lu
137.66.7.89			max.rethinkdns.com
76.76.2.11			freedns.controld.com
149.248.217.117			dns.dnswarden.com
#Encrypt DNS End
# Last Update Time : 2024-10-25 07:31:14 

#EA Start
23.11.226.172			www.ea.com
104.114.79.162			origin-a.akamaihd.net
23.11.209.6			pl.ea.com
23.64.252.140			media.contentapi.ea.com
23.11.209.6			nds-network-nav.ea.com
#EA End
# Last Update Time : 2024-10-25 07:31:14 

#gitlab Start
172.65.251.78			gitlab.com
172.65.251.78			www.gitlab.com
104.17.72.206			page.gitlab.com
104.18.39.11			packages.gitlab.com
104.18.249.37			support.gitlab.com
172.64.148.245			customers.gitlab.com
172.65.216.50			staging.gitlab.com
216.198.53.1			federal-support.gitlab.com
35.227.35.254			registry.gitlab.com
####			evelup.gitlab.com
172.64.148.245			chef.gitlab.com
#gitlab End
# Last Update Time : 2024-10-25 07:31:14 

#debian Start
151.101.66.132			deb.debian.org
#debian End
# Last Update Time : 2024-10-25 07:31:14 

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
# Last Update Time : 2024-10-25 07:31:16 

#EPIC Start
54.230.18.119			download2.epicgames.com
18.154.110.120			download3.epicgames.com
18.154.110.103			download4.epicgames.com
18.154.185.103			download.epicgames.com
104.114.79.194			epicgames-download1.akamaized.net
3.168.51.9			epic-social-social-modules-prod.ol.epicgames.com
54.159.19.48			eulatracking-public-service-prod06.ol.epicgames.com
18.160.225.115			media-cdn.epicgames.com
104.117.189.78			static-assets-prod.epicgames.com
23.12.21.152			store-content.ak.epicgames.com
52.23.102.75			tracking.epicgames.com
#EPIC End
# Last Update Time : 2024-10-25 07:31:17 

#google Start
172.217.1.99			update.googleapis.com
142.250.191.106			translate-pa.googleapis.com
142.250.190.142			translate.google.com
142.250.190.74			firebaseinstallations.googleapis.com
142.250.191.106			infinitedata-pa.googleapis.com
142.250.190.74			geller-pa.googleapis.com
108.177.12.188			alt1.mobile-gtalk.l.google.com
172.253.62.188			alt2.mobile-gtalk4.l.google.com
64.233.186.188			alt3.mobile-gtalk.l.google.com
209.85.202.188			alt4.mobile-gtalk4.l.google.com
64.233.184.188			alt5.mobile-gtalk.l.google.com
142.250.27.188			alt6.mobile-gtalk4.l.google.com
142.250.153.188			alt7.mobile-gtalk.l.google.com
142.251.9.188			alt8.mobile-gtalk4.l.google.com
142.250.191.138			translate.googleapis.com
142.250.190.142			www3.l.google.com
142.250.191.195			services.googleapis.cn
142.250.191.206			play-fe.googleapis.com
142.250.190.118			play-lh.googleusercontent.com
216.239.34.223			play.googleapis.com
108.177.12.188			alt1-mtalk.google.com
172.253.62.188			alt2-mtalk.google.com
64.233.186.188			alt3-mtalk.google.com
209.85.202.188			alt4-mtalk.google.com
64.233.184.188			alt5-mtalk.google.com
142.250.27.188			alt6-mtalk.google.com
142.250.153.188			alt7-mtalk.google.com
142.251.9.188			alt8-mtalk.google.com
142.250.191.202			content-autofill.googleapis.com
142.250.191.163			googlecn-lopri.l.google.com
142.250.191.163			www.googleapis.cn
#google End
# Last Update Time : 2024-10-25 07:31:17 

#xbox Start
23.11.208.8			gameclipscontent-d2009.xboxlive.com
104.102.249.202			images-eds.xboxlive.com
23.211.176.31			xbl-smooth.xboxlive.com
23.11.208.8			titlehub.xboxlive.com
104.102.249.161			compass.xboxlive.com
23.11.208.8			xnotify.xboxlive.com
13.66.204.157			activityhub.xboxlive.com
23.11.208.8			images-eds-ssl.xboxlive.com
199.46.35.123			rta.xboxlive.com
23.37.28.8			peoplehub.xboxlive.com
40.78.138.172			editorial.xboxlive.com
104.114.79.195			assets1.xboxlive.cn
104.114.79.168			assets2.xboxlive.cn
20.76.201.171			xboxlive.com
13.107.246.51			da.xboxservices.com
40.122.167.99			device.auth.xboxlive.com
#xbox End
# Last Update Time : 2024-10-25 07:31:17 

#Apkpure Start
104.22.8.141			download.pureapk.com
172.67.20.93			api.pureapk.com
104.22.43.111			t.apkpure.net
104.22.8.141			tapi.pureapk.com
104.22.9.141			rdelivery.pureapk.com
172.67.72.204			tapi.upload.app
45.33.36.159			api.sve.cc
#Apkpure End
# Last Update Time : 2024-10-25 07:31:18 

#Microsoft Start
20.190.155.130			login.microsoftonline.com
52.165.164.15			fe3cr.delivery.mp.microsoft.com
52.252.198.191			fe2cr.update.microsoft.com
52.149.20.212			slscr.update.microsoft.com
199.232.214.172			dl.delivery.mp.microsoft.com
13.91.222.61			nav-edge.smartscreen.microsoft.com
20.190.135.45			graph.microsoft.com
23.11.210.183			go.microsoft.com
13.107.246.51			static.edge.microsoftapp.net
204.79.197.203			oneocsp.microsoft.com
4.153.57.10			nf.smartscreen.microsoft.com
4.236.248.221			wdcp.microsoft.com
52.109.20.38			officeclient.microsoft.com
20.42.7.128			api-edge.cognitive.microsofttranslator.com
204.79.197.239			edge.microsoft.com
23.11.209.195			storeedgefd.dsx.mp.microsoft.com
152.195.19.97			msedgeextensions.sf.tlu.dl.delivery.mp.microsoft.com
#Microsoft End
# Last Update Time : 2024-10-25 07:31:18 

#spotify Start
104.199.241.202			ap-gae2.spotify.com
104.154.127.247			ap-guc3.spotify.com
104.199.65.9			ap-gew1.spotify.com
34.158.1.133			ap-gew4.spotify.com
34.158.255.62			ap-gue1.spotify.com
35.186.224.24			spclient.wg.spotify.com
35.186.224.24			wg.spotify.com
35.186.224.22			gae-spclient.spotify.com
23.32.45.203			audio4-ak-spotify-com.akamaized.net
104.102.249.210			heads4-ak-spotify-com.akamaized.net
23.32.45.208			audio-ak-spotify-com.akamaized.net
23.32.45.174			audio-akp-quic-spotify-com.akamaized.net
#spotify End
# Last Update Time : 2024-10-25 07:31:19 

#scdn Start
199.232.210.248			audio-fa.scdn.co
23.32.45.191			misc.scdn.co
23.32.45.204			i.scdn.co
199.232.214.248			newjams-images.scdn.co
199.232.210.248			dailymix-images.scdn.co
199.232.214.248			thisis-images.scdn.co
199.232.214.248			charts-images.scdn.co
199.232.210.248			seeded-session-images.scdn.co
199.232.210.248			download.scdn.co
#scdn End
# Last Update Time : 2024-10-25 07:31:19 

#onedrive Start
13.107.139.11			onedrive.live.com
13.107.42.12			skyapi.onedrive.live.com
23.223.161.55			api.onedrive.live.com
#onedrive End
# Last Update Time : 2024-10-25 07:31:19 

#other Start
184.72.100.22			www.ghostery.com
184.72.100.22			ghostery.com
104.233.133.90			wap.yushuwu.cloud
13.228.58.191			apkhub.co
162.214.80.67			apkhub.org
#other End
# Last Update Time : 2024-10-25 07:31:19 

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
