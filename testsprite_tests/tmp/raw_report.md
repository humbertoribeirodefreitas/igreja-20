
# TestSprite AI Testing Report(MCP)

---

## 1️⃣ Document Metadata
- **Project Name:** ADMAC
- **Date:** 2025-12-03
- **Prepared by:** TestSprite AI Team

---

## 2️⃣ Requirement Validation Summary

#### Test TC001
- **Test Name:** Access Control - Authenticated User Can Access /painel Routes
- **Test Code:** [TC001_Access_Control___Authenticated_User_Can_Access_painel_Routes.py](./TC001_Access_Control___Authenticated_User_Can_Access_painel_Routes.py)
- **Test Error:** The /painel route and related pages cannot be accessed because the browser is showing a chrome error page indicating the target URL is not loading. This prevents setting the localStorage key and verifying access. Please ensure the local server or environment hosting the application is running and accessible at the expected URL (http://localhost:5173). Once the environment is stable and the pages load correctly, the test can be resumed to set localStorage key isAuthenticated=true and verify access to /painel routes.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[WARNING] Console Ninja failed to send logs, refreshing the page may help; also see https://tinyurl.com/37x8b79t: logger websocket error {method: errorHandlerInstalled, version: 1.0.0, args: Array(2)} (at :0:5846)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[WARNING] Console Ninja failed to send logs, refreshing the page may help; also see https://tinyurl.com/37x8b79t: logger websocket error {method: networkLoggingHandlerInstalled, version: 1.0.0, args: Array(2)} (at :0:5726)
[ERROR] WebSocket connection to 'ws://localhost:5173/?token=XHKB9F41be-o' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/@vite/client:744:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/ca328e7d-5b19-4751-9818-6e02097b418d
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC002
- **Test Name:** Access Control - Unauthorized User Blocked from /painel Routes
- **Test Code:** [TC002_Access_Control___Unauthorized_User_Blocked_from_painel_Routes.py](./TC002_Access_Control___Unauthorized_User_Blocked_from_painel_Routes.py)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/2b4f15ed-ef42-462c-bb9c-6886080948ee
- **Status:** ✅ Passed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC003
- **Test Name:** HomeEditor - Edit and Save Home Content Successfully
- **Test Code:** [TC003_HomeEditor___Edit_and_Save_Home_Content_Successfully.py](./TC003_HomeEditor___Edit_and_Save_Home_Content_Successfully.py)
- **Test Error:** Cannot proceed with the task because the login to the admin panel fails and results in a browser error page. Unable to access HomeEditor to modify content and verify persistence. Task stopped due to critical access issue.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/6cdec25a-a175-40f4-8b98-9db57083a48d
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC004
- **Test Name:** FooterEditor - Edit and Save Footer Content Successfully
- **Test Code:** [TC004_FooterEditor___Edit_and_Save_Footer_Content_Successfully.py](./TC004_FooterEditor___Edit_and_Save_Footer_Content_Successfully.py)
- **Test Error:** The task to verify footer content edits persistence and update on the public site cannot be completed due to login authentication failure. The issue has been reported. No further actions can be performed until the login issue is resolved.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/09587a13-d3ca-4c8a-8631-43dd8a0e9e1e
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC005
- **Test Name:** MinistryEditor - CRUD Operations on Ministry Content
- **Test Code:** [TC005_MinistryEditor___CRUD_Operations_on_Ministry_Content.py](./TC005_MinistryEditor___CRUD_Operations_on_Ministry_Content.py)
- **Test Error:** Reported authentication issue on the ADMAC Painel login page. Unable to proceed with MinistryEditor CRUD testing due to login failure. Task stopped.
Browser Console Logs:
[WARNING] It is recommended that a robustness level be specified. Not specifying the robustness level could result in unexpected behavior. (at https://embed-cdn.spotifycdn.com/_next/static/chunks/9290.e1f60ce054a11bba.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://fonts.gstatic.com/s/roboto/v48/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3yUBA.woff2:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://static.doubleclick.net/instream/ad_status.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://yt3.ggpht.com/vewxKdtll-rntHAMDPY_Qa6hPac3-J2sCFFUwvGSSR0i7hB4g5rNfF39lCEcjGvsYI0RWx7V1A=s88-c-k-c0x00ffffff-no-rj:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr4---sn-gpv7kn7y.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=397&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C271%2C278%2C313%2C394%2C395%2C396%2C397%2C398%2C399%2C400%2C401&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=video%2Fmp4&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=9569015&dur=213.040&lmt=1749084358066378&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4537534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRgIhAPHvF_O93O-mcDGZWN5JdWD7-guSft3C466cP_BBtAxJAiEA3LAYgrbzrpMoadjxH6jAiB3bpyTaezyMjLqsd3NyDBo%3D&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&fallback_count=1&range=0-1187&rn=4&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr4---sn-gpv7kn7y.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=397&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C271%2C278%2C313%2C394%2C395%2C396%2C397%2C398%2C399%2C400%2C401&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=video%2Fmp4&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=9569015&dur=213.040&lmt=1749084358066378&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4537534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRgIhAPHvF_O93O-mcDGZWN5JdWD7-guSft3C466cP_BBtAxJAiEA3LAYgrbzrpMoadjxH6jAiB3bpyTaezyMjLqsd3NyDBo%3D&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&fallback_count=1&range=0-1187&rn=6&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://www.google.com/js/th/9bXBegwkXqu77ttg1H2zNptqxcGE6xDjLfnManLdL_4.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr1---sn-uphcg51pa-bg0el.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=251&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=audio%2Fwebm&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=3433717&dur=213.061&lmt=1749082494991270&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4532534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRAIgJNXEGEY_LlvfTASe3QIxAmc7pOE4zHEyVwAeYuiecv8CIGyWyWZtSgXWHxXJB1zTc9zKa2YeG2JlhFZDBUUzH1YX&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&range=0-629&rn=8&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://i.ytimg.com/vi_webp/yPYZpwSpKmA/maxresdefault.webp:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://i.ytimg.com/vi_webp/yi6fWPV6qXg/maxresdefault.webp:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://i.ytimg.com/vi/qQDrqV5Hw4c/maxresdefault.jpg?sqp=-oaymwEmCIAKENAF8quKqQMa8AEB-AH-CYAC0AWKAgwIABABGFggXyhlMA8=&rs=AOn4CLBDFgN-ehq0DU9qYo5qdDhC4mg_sw:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://yt3.ggpht.com/vewxKdtll-rntHAMDPY_Qa6hPac3-J2sCFFUwvGSSR0i7hB4g5rNfF39lCEcjGvsYI0RWx7V1A=s400-c-k-c0x00ffffff-no-rj:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr1---sn-uphcg51pa-bg0el.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=244&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C271%2C278%2C313%2C394%2C395%2C396%2C397%2C398%2C399%2C400%2C401&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=video%2Fwebm&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=11046785&dur=213.040&lmt=1749084313379129&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4537534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRQIhAKAq6DkoioWDbZZOXwfJK1llALW3e0e_cBGcDYw6yv44AiBqfa7sAD52VkmyrI-fq7L138ejV8qmZj8Aundms6hA_Q%3D%3D&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&range=0-857&rn=9&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr1---sn-uphcg51pa-bg0el.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=251&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=audio%2Fwebm&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=3433717&dur=213.061&lmt=1749082494991270&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4532534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Citag%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRAIgJNXEGEY_LlvfTASe3QIxAmc7pOE4zHEyVwAeYuiecv8CIGyWyWZtSgXWHxXJB1zTc9zKa2YeG2JlhFZDBUUzH1YX&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&range=0-629&rn=10&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://rr4---sn-gpv7kn7y.googlevideo.com/videoplayback?expire=1764831777&ei=wd0wafP-HozM-LAPt4eRkAM&ip=2804%3A214%3A86ba%3A3ff%3A1c07%3A77ec%3A919f%3Ad26a&id=o-AG20l09BXJjSoKULVJafsmRUhjbyKtV7QYoiyWoLgJaR&itag=244&aitags=133%2C134%2C135%2C136%2C137%2C160%2C242%2C243%2C244%2C247%2C248%2C271%2C278%2C313%2C394%2C395%2C396%2C397%2C398%2C399%2C400%2C401&source=youtube&requiressl=yes&xpc=EgVo2aDSNQ%3D%3D&cps=584&met=1764810177%2C&mh=7c&mm=31%2C26&mn=sn-uphcg51pa-bg0el%2Csn-gpv7kn7y&ms=au%2Conr&mv=m&mvi=1&pl=44&rms=au%2Cau&initcwndbps=601250&bui=AdEuB5SkXpwyqxCnH_T1VlsCtAGZhgKUlS_wWP1xc41dzvNR8C1BCUVRmCGUmf5FHIGSRegPtP7h6NMb&spc=6b0G_L_N-JXraRxBp6wEI6qSxg3Es0TV1lOeItWS2jk_iyJD9WMmBLoxHHMClxujbcxrXMco&vprv=1&svpuc=1&mime=video%2Fwebm&ns=nyhB-0Hrj0eawCu-BOIvb3gQ&rqh=1&gir=yes&clen=11046785&dur=213.040&lmt=1749084313379129&mt=1764809817&fvip=4&keepalive=yes&fexp=51552689%2C51565115%2C51565682%2C51580968%2C51669167%2C51673847&c=WEB_EMBEDDED_PLAYER&sefc=1&txp=4537534&n=K-_sBrL54Y7veQ&sparams=expire%2Cei%2Cip%2Cid%2Caitags%2Csource%2Crequiressl%2Cxpc%2Cbui%2Cspc%2Cvprv%2Csvpuc%2Cmime%2Cns%2Crqh%2Cgir%2Cclen%2Cdur%2Clmt&lsparams=cps%2Cmet%2Cmh%2Cmm%2Cmn%2Cms%2Cmv%2Cmvi%2Cpl%2Crms%2Cinitcwndbps&lsig=APaTxxMwRQIhALLGb1fl5Ji9oHH0b9DnJd7UXBRogBP2XnrECzLItDZeAiBsETdzpn_7L4LsyiA4VuQNnvreV6BNOmcs5ughWU_a0Q%3D%3D&alr=yes&sig=AJfQdSswRQIhAKAq6DkoioWDbZZOXwfJK1llALW3e0e_cBGcDYw6yv44AiBqfa7sAD52VkmyrI-fq7L138ejV8qmZj8Aundms6hA_Q%3D%3D&cpn=v1UkTGH4VTcYKma_&cver=1.20251203.01.00&fallback_count=1&range=0-857&rn=11&rbuf=0&pot=IghOa09qJ1uTqg==&ump=1&srfvp=1:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://www.google.com/js/th/9bXBegwkXqu77ttg1H2zNptqxcGE6xDjLfnManLdL_4.js:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/7c193b8d-7eb5-433b-a807-a763223a41a3
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC006
- **Test Name:** Dynamic Pages - List, Add, Update Status, and Delete
- **Test Code:** [TC006_Dynamic_Pages___List_Add_Update_Status_and_Delete.py](./TC006_Dynamic_Pages___List_Add_Update_Status_and_Delete.py)
- **Test Error:** Login failed repeatedly with valid credentials; cannot access dynamic pages management. Reporting issue and stopping further testing.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/cf8116c3-b247-48e4-99cf-a7879011f0fe
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC007
- **Test Name:** Supabase Content Persistence - Save and Fetch Item Methods
- **Test Code:** [TC007_Supabase_Content_Persistence___Save_and_Fetch_Item_Methods.py](./TC007_Supabase_Content_Persistence___Save_and_Fetch_Item_Methods.py)
- **Test Error:** Login failure blocks access to admin panel. Cannot test DatabaseService saveItem and fetchItem methods. Reporting issue and stopping further actions.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/8b431179-4eb6-47c1-98a3-ef79f331284f
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC008
- **Test Name:** Routing - ProtectedRoute Component Prevents Unauthorized Access and Allows Authorized Access
- **Test Code:** [TC008_Routing___ProtectedRoute_Component_Prevents_Unauthorized_Access_and_Allows_Authorized_Access.py](./TC008_Routing___ProtectedRoute_Component_Prevents_Unauthorized_Access_and_Allows_Authorized_Access.py)
- **Test Error:** The local development server at localhost:5173 remains unreachable, preventing any testing of the ProtectedRoute component. No progress was made on the task due to server unavailability. Please ensure the server is running and accessible, then retry the testing steps.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[WARNING] Console Ninja failed to send logs, refreshing the page may help; also see https://tinyurl.com/37x8b79t: logger websocket error {method: networkLoggingHandlerInstalled, version: 1.0.0, args: Array(2)} (at :0:5726)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/src/App.jsx:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/d0c6d5d4-f69d-435d-b82c-0fd5f1e2acb4
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC009
- **Test Name:** UI Responsiveness and Consistency for Admin and Public Interfaces
- **Test Code:** [TC009_UI_Responsiveness_and_Consistency_for_Admin_and_Public_Interfaces.py](./TC009_UI_Responsiveness_and_Consistency_for_Admin_and_Public_Interfaces.py)
- **Test Error:** The site is not loading and shows a browser error page. UI validation cannot be performed. Please check the server or network connection and try again.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/src/services/initialData.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/node_modules/.vite/deps/chunk-GKTVGHCE.js?v=fec24388:0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/b4356701-f821-4925-b941-063cd499200c
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC010
- **Test Name:** Data Consistency Between Frontend Display and Backend Storage After Content Edits
- **Test Code:** [TC010_Data_Consistency_Between_Frontend_Display_and_Backend_Storage_After_Content_Edits.py](./TC010_Data_Consistency_Between_Frontend_Display_and_Backend_Storage_After_Content_Edits.py)
- **Test Error:** Login to admin painel failed repeatedly, preventing access to update content and verify data persistence. Task cannot proceed further. Reporting issue and stopping.
Browser Console Logs:
[ERROR] WebSocket connection to 'ws://localhost:5173/?token=XHKB9F41be-o' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/@vite/client:744:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://ui-avatars.com/api/?name=Pastor+Roberto&background=d4af37&color=000&size=200&bold=true:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://localhost:5173/?token=XHKB9F41be-o' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at http://localhost:5173/@vite/client:754:0)
[ERROR] [vite] failed to connect to websocket.
your current setup:
  (browser) localhost:5173/ <--[HTTP]--> localhost:5173/ (server)
  (browser) localhost:5173/ <--[WebSocket (failing)]--> localhost:5173/ (server)
Check out your Vite / network configuration and https://vite.dev/config/server-options.html#server-hmr . (at :0:11770)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://fonts.gstatic.com/s/roboto/v48/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3yUBA.woff2:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://static.doubleclick.net/instream/ad_status.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://yt3.ggpht.com/vewxKdtll-rntHAMDPY_Qa6hPac3-J2sCFFUwvGSSR0i7hB4g5rNfF39lCEcjGvsYI0RWx7V1A=s68-c-k-c0x00ffffff-no-rj:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://yt3.ggpht.com/vewxKdtll-rntHAMDPY_Qa6hPac3-J2sCFFUwvGSSR0i7hB4g5rNfF39lCEcjGvsYI0RWx7V1A=s88-c-k-c0x00ffffff-no-rj:0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/dc74532e-cf11-4e4f-8cb7-c468a2121bd9
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC011
- **Test Name:** Dynamic Page Status Filter on Public Site
- **Test Code:** [TC011_Dynamic_Page_Status_Filter_on_Public_Site.py](./TC011_Dynamic_Page_Status_Filter_on_Public_Site.py)
- **Test Error:** Login to the admin panel failed; cannot proceed with checking dynamic pages status. Reported the issue and stopped further actions.
Browser Console Logs:
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1593113598332-cd288d649433?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1511379938547-c1f69419868d?w=400&h=300&fit=crop:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1510936111840-65e151ad71bb?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1438232992991-995b7058bbb3?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_home:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_footer:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://cwagvicscatqqdptpmit.supabase.co/rest/v1/app_content?select=*&key=eq.admac_pages:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/e971a05c-5a33-4d29-b216-e17360b0082d
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---

#### Test TC012
- **Test Name:** Error Handling - Handle Supabase Network/Server Failures Gracefully
- **Test Code:** [TC012_Error_Handling___Handle_Supabase_NetworkServer_Failures_Gracefully.py](./TC012_Error_Handling___Handle_Supabase_NetworkServer_Failures_Gracefully.py)
- **Test Error:** Reported navigation issue preventing access to content editing page. Cannot proceed with Supabase API failure simulations. Stopping further actions.
Browser Console Logs:
[WARNING] It is recommended that a robustness level be specified. Not specifying the robustness level could result in unexpected behavior. (at https://embed-cdn.spotifycdn.com/_next/static/chunks/9290.e1f60ce054a11bba.js:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://o22381.ingest.us.sentry.io/api/4505164808585216/envelope/?sentry_version=7&sentry_key=4cc707ab12ea4779b417479c0550a5cb&sentry_client=sentry.javascript.nextjs%2F10.27.0:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] Failed to load resource: net::ERR_EMPTY_RESPONSE (at https://gue1-spclient.spotify.com/gabo-receiver-service/public/v3/events:0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
[ERROR] WebSocket connection to 'ws://127.0.0.1:59112/' failed: Error in connection establishment: net::ERR_EMPTY_RESPONSE (at :0:0)
- **Test Visualization and Result:** https://www.testsprite.com/dashboard/mcp/tests/1beafa5b-5da9-43f6-9f9b-72a809797a65/04aa49bb-510d-4627-9aff-88dd81eeaa6f
- **Status:** ❌ Failed
- **Analysis / Findings:** {{TODO:AI_ANALYSIS}}.
---


## 3️⃣ Coverage & Matching Metrics

- **8.33** of tests passed

| Requirement        | Total Tests | ✅ Passed | ❌ Failed  |
|--------------------|-------------|-----------|------------|
| ...                | ...         | ...       | ...        |
---


## 4️⃣ Key Gaps / Risks
{AI_GNERATED_KET_GAPS_AND_RISKS}
---