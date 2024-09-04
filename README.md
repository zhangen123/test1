allow-lan: true
dns:
  default-nameserver:
  - 119.29.29.29
  - 223.5.5.5
  enable: true
  fake-ip-range: 198.18.0.1/16
  nameserver:
  - https://doh.pub/dns-query
  - https://223.6.6.6/dns-query
  use-hosts: true
log-level: warning
mixed-port: 9981
mode: rule
proxies:
- alterId: 0
  cipher: auto
  name: 香港綜合
  network: tcp
  port: 6510
  server: 720981a8-sajwg0-slyakq-14e7s.hk.plebai.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
- alterId: 2
  cipher: auto
  name: 香港HKT
  network: ws
  port: 80
  server: 01f9f9bf-sajwg0-slyakq-14e7s.hkt.comefromchinatown.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: www.hgcbroadband.com
  ws-path: /
- alterId: 2
  cipher: auto
  name: 香港精品
  network: ws
  port: 80
  server: 98289fde-sajwg0-slyakq-14e7s.hkt.gotochinatown.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: broadcastlv.chat.bilibili.com
  ws-path: /
- alterId: 2
  cipher: auto
  name: 香港HKT商業
  network: ws
  port: 80
  server: 459a4c6b-sajwg0-slyakq-14e7s.hgc1.tcpbbr.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 459a4c6b-sajwg0-slyakq-14e7s.hgc1.tcpbbr.net
  ws-path: /
- alterId: 2
  cipher: auto
  name: 香港宽频2
  network: ws
  port: 80
  server: 404ab0b8-sajwg0-slyakq-14e7s.wtt2.comefromchinatown.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 404ab0b8-sajwg0-slyakq-14e7s.wtt2.comefromchinatown.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: 香港宽频1
  network: ws
  port: 80
  server: fc1d8890-sajwg0-slyakq-14e7s.bn.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: fc1d8890-sajwg0-slyakq-14e7s.bn.p5pv.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: 香港宽频3
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 22443
  server: f2d9a807-sajwg0-slyakq-14e7s.wtt5.p5pv.com
  tls: true
  type: http
  username: lihaichao93@gmail.com
- alterId: 0
  cipher: auto
  name: 美國硅谷
  network: ws
  port: 80
  server: af5e312a-sajwg0-slyakq-14e7s.sj.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: af5e312a-sajwg0-slyakq-14e7s.sj.p5pv.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: 美國洛杉磯
  network: ws
  port: 80
  server: dc7d83a5-sajwg0-slyakq-14e7s.los2.plebai.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: dc7d83a5-sajwg0-slyakq-14e7s.los2.plebai.net
  ws-path: /
- alterId: 2
  cipher: auto
  name: 美國费利蒙
  network: ws
  port: 80
  server: b2ff11b9-sajwg0-slyakq-14e7s.fremont.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: www.hgcbroadband.com
  ws-path: /
- alterId: 2
  cipher: auto
  name: 美國西雅圖
  network: ws
  port: 80
  server: 9588c75e-sajwg0-slyakq-14e7s.se.plebai.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 9588c75e-sajwg0-slyakq-14e7s.se.plebai.net
  ws-path: /
- alterId: 0
  cipher: auto
  name: 美國洛杉矶2
  network: ws
  port: 80
  server: f612d675-sajwg0-slyakq-14e7s.los.plebai.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: f612d675-sajwg0-slyakq-14e7s.los.plebai.net
  ws-path: /
- alterId: 0
  cipher: auto
  name: 英國
  network: ws
  port: 80
  server: 7f05ff54-sajwg0-slyakq-14e7s.uk2.tcpbbr.net
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 7f05ff54-sajwg0-slyakq-14e7s.uk2.tcpbbr.net
  ws-path: /
- alterId: 0
  cipher: auto
  name: 台灣
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 61234
  server: 7fc9709b-sajwg0-slyakq-14e7s.tw4.tcpbbr.net
  tls: true
  type: http
  username: lihaichao93@gmail.com
- alterId: 2
  cipher: auto
  name: 日本
  network: ws
  port: 80
  server: 514e92e5-sajwg0-slyakq-14e7s.jp.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: broadcastlv.chat.bilibili.com
  ws-path: /
- alterId: 2
  cipher: auto
  name: 韩國
  network: ws
  port: 80
  server: 639d10bc-sajwg0-slyakq-14e7s.kr.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: broadcastlv.chat.bilibili.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: 台湾2
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 443
  server: d50f55db-sajwg0-slyakq-14e7s.tw3.p5pv.com
  tls: false
  type: trojan
- alterId: 2
  cipher: auto
  name: 新加坡
  network: ws
  port: 80
  server: 181e8935-sajwg0-slyakq-14e7s.sg.p5pv.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 181e8935-sajwg0-slyakq-14e7s.sg.p5pv.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: 俄羅斯
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 1007
  server: 2a466dee-sajwg0-slyakq-14e7s.ru.z7zi.com
  tls: true
  type: http
  username: lihaichao93@gmail.com
- alterId: 0
  cipher: auto
  name: 德國
  network: ws
  port: 80
  server: 7f028028-sajwg0-slyakq-14e7s.de.comefromchinatown.com
  tls: false
  type: vmess
  uuid: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  ws-headers:
    Host: 7f028028-sajwg0-slyakq-14e7s.de.comefromchinatown.com
  ws-path: /
- alterId: 0
  cipher: auto
  name: ChatGPT-02
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 8443
  server: bce9865a-sajwg0-slyakq-14e7s.s5.p5pv.com
  tls: true
  type: http
  username: lihaichao93@gmail.com
- alterId: 0
  cipher: auto
  name: ChatGPT-01
  network: tcp
  password: 830b700e-d2b8-11ed-b904-f23c91cfbbc9
  port: 8443
  server: bce9865a-sajwg0-slyakq-14e7s.s5.p5pv.com
  tls: true
  type: trojan
proxy-groups:
- name: Ghelper
  proxies:
  - 全球智能
  - 香港智能
  - 香港綜合
  - 香港HKT
  - 香港精品
  - 香港HKT商業
  - 香港宽频2
  - 香港宽频1
  - 香港宽频3
  - 美國硅谷
  - 美國洛杉磯
  - 美國费利蒙
  - 美國西雅圖
  - 美國洛杉矶2
  - 英國
  - 台灣
  - 日本
  - 韩國
  - 台湾2
  - 新加坡
  - 俄羅斯
  - 德國
  - ChatGPT专线
  type: select
- interval: 7200
  name: 全球智能
  proxies:
  - 香港綜合
  - 香港HKT
  - 香港精品
  - 香港HKT商業
  - 香港宽频2
  - 香港宽频1
  - 香港宽频3
  - 美國硅谷
  - 美國洛杉磯
  - 美國费利蒙
  - 美國西雅圖
  - 美國洛杉矶2
  - 英國
  - 台灣
  - 日本
  - 韩國
  - 新加坡
  - 俄羅斯
  - 德國
  - ChatGPT-02
  type: url-test
  url: http://www.gstatic.com/generate_204
- interval: 7200
  name: 香港智能
  proxies:
  - 香港綜合
  - 香港HKT
  - 香港精品
  - 香港HKT商業
  - 香港宽频2
  - 香港宽频1
  - 香港宽频3
  type: url-test
  url: http://www.gstatic.com/generate_204
- interval: 3600
  name: ChatGPT专线
  proxies:
  - ChatGPT-02
  - ChatGPT-01
  type: fallback
  url: http://www.gstatic.com/generate_204
rules:
- DOMAIN-SUFFIX,ip-api.com,DIRECT
- DOMAIN-SUFFIX,ipip.net,DIRECT
- DOMAIN-SUFFIX,ip138.com,DIRECT
- DOMAIN-SUFFIX,stripe.com,DIRECT
- DOMAIN-SUFFIX,payssion.com,DIRECT
- DOMAIN-SUFFIX,alipay.com,DIRECT
- DOMAIN-SUFFIX,alipayplus.com,DIRECT
- DOMAIN-SUFFIX,alidns.com,DIRECT
- DOMAIN-SUFFIX,airwallex.com,DIRECT
- DOMAIN-SUFFIX,wooshapy.com,DIRECT
- DOMAIN-KEYWORD,google,Ghelper
- DOMAIN-SUFFIX,ggpht.com,Ghelper
- DOMAIN-SUFFIX,gmail.com,Ghelper
- DOMAIN-SUFFIX,gvt2.com,Ghelper
- DOMAIN-SUFFIX,gvt3.com,Ghelper
- DOMAIN-SUFFIX,chrome.com,Ghelper
- DOMAIN-SUFFIX,wikipedia.org,Ghelper
- DOMAIN-SUFFIX,wikimedia.org,Ghelper
- DOMAIN-SUFFIX,appspot.com,Ghelper
- DOMAIN-SUFFIX,android.com,Ghelper
- DOMAIN-SUFFIX,github.com,Ghelper
- DOMAIN-SUFFIX,gitbook.com,Ghelper
- DOMAIN-SUFFIX,kaggle.com,Ghelper
- DOMAIN-SUFFIX,arxiv.org,Ghelper
- DOMAIN-SUFFIX,wiktionary.org,Ghelper
- DOMAIN-SUFFIX,blogger.com,Ghelper
- DOMAIN-KEYWORD,google,Ghelper
- DOMAIN-KEYWORD,youtube,Ghelper
- DOMAIN-SUFFIX,ggpht.com,Ghelper
- DOMAIN-SUFFIX,gmail.com,Ghelper
- DOMAIN-SUFFIX,gvt2.com,Ghelper
- DOMAIN-SUFFIX,gvt3.com,Ghelper
- DOMAIN-SUFFIX,chrome.com,Ghelper
- DOMAIN-SUFFIX,wikipedia.org,Ghelper
- DOMAIN-SUFFIX,wikimedia.org,Ghelper
- DOMAIN-SUFFIX,appspot.com,Ghelper
- DOMAIN-SUFFIX,android.com,Ghelper
- DOMAIN-SUFFIX,github.com,Ghelper
- DOMAIN-SUFFIX,gitbook.com,Ghelper
- DOMAIN-SUFFIX,kaggle.com,Ghelper
- DOMAIN-SUFFIX,arxiv.org,Ghelper
- DOMAIN-SUFFIX,wiktionary.org,Ghelper
- DOMAIN-SUFFIX,blogger.com,Ghelper
- DOMAIN-SUFFIX,youtu.be,Ghelper
- DOMAIN-SUFFIX,ytimg.com,Ghelper
- DOMAIN-SUFFIX,youtube.com,Ghelper
- DOMAIN-SUFFIX,instagram.com,Ghelper
- DOMAIN-SUFFIX,twitter.com,Ghelper
- DOMAIN-SUFFIX,t.co,Ghelper
- DOMAIN-SUFFIX,facebook.com,Ghelper
- DOMAIN-SUFFIX,telegram.org,Ghelper
- DOMAIN-SUFFIX,whatsapp.com,Ghelper
- DOMAIN-SUFFIX,whatsapp.net,Ghelper
- DOMAIN-SUFFIX,linkedin.com,Ghelper
- DOMAIN-SUFFIX,licdn.com,Ghelper
- DOMAIN-SUFFIX,trkn.us,Ghelper
- DOMAIN-SUFFIX,cedexis.com,Ghelper
- DOMAIN-SUFFIX,openai.com,ChatGPT专线
- DOMAIN-SUFFIX,auth0.com,ChatGPT专线
- DOMAIN-SUFFIX,featuregates.org,ChatGPT专线
- DOMAIN-SUFFIX,statsigapi.net,ChatGPT专线
- DOMAIN-SUFFIX,intercom.io,ChatGPT专线
- DOMAIN-SUFFIX,intercomcdn.com,ChatGPT专线
- DOMAIN-SUFFIX,sentry.io,ChatGPT专线
- DOMAIN-SUFFIX,sentry.dev,ChatGPT专线
- DOMAIN-SUFFIX,ai.com,ChatGPT专线
- DOMAIN-SUFFIX,claude.ai,ChatGPT专线
- DOMAIN-SUFFIX,bing.com,ChatGPT专线
- DOMAIN-SUFFIX,microsoftonline.com,ChatGPT专线
- DOMAIN-SUFFIX,live.com,ChatGPT专线
- DOMAIN-SUFFIX,msecnd.net,ChatGPT专线
- DOMAIN-SUFFIX,msn.com,ChatGPT专线
- DOMAIN-SUFFIX,bingapis.com,ChatGPT专线
- DOMAIN-SUFFIX,bing.net,ChatGPT专线
- DOMAIN-SUFFIX,windows.com,ChatGPT专线
- DOMAIN-SUFFIX,microsoft.com,ChatGPT专线
- DOMAIN-SUFFIX,linkedin.com,Ghelper
- DOMAIN-SUFFIX,licdn.com,Ghelper
- DOMAIN-SUFFIX,trkn.us,Ghelper
- DOMAIN-SUFFIX,cedexis.com,Ghelper
- GEOIP,CN,DIRECT
- MATCH, Ghelper
