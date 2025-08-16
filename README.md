# Hello, this is Verde! 🐬✨  
안녕하세요, 베르데입니다!

I never imagined I would be writing on GitHub — life is full of surprises!  
After much thought, I chose my very first post theme: **"How to install the Cloudflare ZTNA Agent"**.  
Since I managed to complete the setup after many trials and errors,  
I think I can share this more meaningfully and explain step by step.  
Come follow along with me! :)  

깃헙이라니, 제가 이 곳에 글을 올리리라고는 상상조차 못했는데!  
고심 끝에 고른 첫 번째 글 테마는 **"Cloudflare ZTNA Agent 설치 방법"** 이에요.  
제가 이런저런 시도 끝에 구축 완료한 내용이라 더 값지고,  
더 차근차근 알려드릴 수 있을 것 같네요.  
함께 따라와 주세요! :)

---

## 🐬 Step 1 — Download Cloudflare WARP Agent
- **EN:** Go to the official Cloudflare documentation page and download the WARP Agent installer for your operating system.  
- **KR:** Cloudflare 공식 문서 페이지로 이동해, 운영체제에 맞는 WARP Agent 설치 파일을 다운로드하세요.  

<img src="/그림1.png" alt="Download WARP" width="55%">

---

## 🐻‍❄️ Step 2 — Install Cloudflare WARP.msi
- **EN:** Run the downloaded `.msi` file and follow the installation wizard to install the WARP client.  
- **KR:** 다운로드한 `.msi` 파일을 실행하고 설치 마법사를 따라 WARP 클라이언트를 설치하세요.  

<img src="/그림2.png" alt="Install WARP" width="55%">

---

## ✨ Step 3 — Check Cloudflare Service Running
- **EN:** After installation, confirm that the Cloudflare WARP service is running in the background.  
- **KR:** 설치가 끝난 후, Cloudflare WARP 서비스가 백그라운드에서 실행 중인지 확인하세요.  

<img src="/그림3.png" alt="Service Running" width="55%">

---

## 🧸 Step 4 — Click the Cloudflare WARP Icon
- **EN:** Open the Windows taskbar system tray and click the Cloudflare WARP icon (☁).  
- **KR:** Windows 작업표시줄 우측 하단의 시스템 트레이에서 Cloudflare WARP 아이콘(☁)을 클릭하세요.  

<img src="/그림4.png" alt="System Tray Icon" width="45%">

---

## 🐬 Step 5 — Open Settings
- **EN:** At the bottom of the WARP client window, click the gear (⚙) icon to open the settings menu.  
- **KR:** WARP 클라이언트 창 하단의 톱니바퀴(⚙) 아이콘을 클릭해 설정 메뉴를 여세요.  

<img src="/그림7.png" alt="Settings Icon" width="40%">

---

## 🐻‍❄️ Step 6 — Preferences
- **EN:** In the settings menu, select **Preferences** to configure the WARP client options.  
- **KR:** 설정 메뉴에서 **Preferences(환경설정)** 항목을 선택해 WARP 옵션을 설정하세요.  

<img src="/그림8.png" alt="Preferences" width="40%">

---

## ✨ Step 7 — Account Tab
- **EN:** You can see your Account Type, License Key, and devices using it. To join Zero Trust, click **Login with Cloudflare Zero Trust**.  
- **KR:** 계정 유형, 라이선스 키, 사용 중인 장치를 확인할 수 있습니다. Zero Trust에 가입하려면 **Login with Cloudflare Zero Trust** 버튼을 클릭하세요.  

<img src="/그림9.png" alt="Account Tab" width="45%">

---

## 🧸 Step 8 — Enter Team Name
- **EN:** Enter your team name (e.g., `yourteam.cloudflareaccess.com`), then click **OK** to continue.  
- **KR:** 팀 이름(예: `yourteam.cloudflareaccess.com`)을 입력하고 **OK** 버튼을 클릭하세요.  

<img src="/그림12.png" alt="Team Name Input" width="45%">

---

## 🐬 Step 9 — Browser Redirect
- **EN:** After entering your team name, the browser will redirect to your Cloudflare Zero Trust login page. When prompted, click **Open Cloudflare WARP**.  
- **KR:** 팀 이름을 입력하면 브라우저가 Cloudflare Zero Trust 로그인 페이지로 이동합니다. 팝업 창이 뜨면 **Open Cloudflare WARP** 버튼을 클릭하세요.  

<img src="/그림13.png" alt="Browser Redirect" width="55%">

---

## 🐻‍❄️ Step 10 — Zero Trust Connected
- **EN:** Once successfully connected, the WARP client shows **Zero Trust – Connected**. Your internet traffic is now protected.  
- **KR:** 정상적으로 연결되면, WARP 클라이언트에 **Zero Trust – Connected** 라고 표시됩니다. 이제 인터넷 트래픽이 보호됩니다.  

<img src="/그림15.png" alt="Zero Trust Connected" width="45%">

---

## ✨ Step 11 — Verify with Cloudflare Trace
- **EN:** Open [cloudflare.com/cdn-cgi/trace](https://cloudflare.com/cdn-cgi/trace). If you see `warp=on` and `gateway=on`, your device is connected.  
- **KR:** 브라우저에서 [cloudflare.com/cdn-cgi/trace](https://cloudflare.com/cdn-cgi/trace) 를 열어보세요. `warp=on`, `gateway=on` 값이 보이면 정상적으로 연결된 상태입니다.  

<img src="/그림16.png" alt="Cloudflare Trace" width="55%">
