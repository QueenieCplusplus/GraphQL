# GraphQL

graphQL 主要優點

為了彌補 Restful always gets Routes 的缺憾，graphQL 的優勢就是單一端點的架構，單一端點即可扮演閘道的角色，協調多個資料來源，用單一端點即可組織資料。

# RESTful_Fault
原本主流的 Restful API 缺陷

# Overfetch, 過度擷取

用戶端明明僅需要三個資料點，例如：{name: "", height: "", mass: ""}，但卻因為 Restful 的缺陷，導致傳回資料的 Json 檔案內容夾雜著其他不需要的資料點，這就是 Restful 即將成為歷史的主要元兇。

# Underfetch, 擷取不足

當開發者如我們這些工程師，欲某 URL 發出請求資料，會因為資料分別放在不同路由，而需要花很大心思和時間成本發出其他請求，方才得以取得所需要的更多資料，可能需要發出五筆以上的請求，才能得到一個所需要的資料。

假如所需要的資料，要接觸 10 筆以上的路由，於是便會產生出 16 次的用戶端往返，每一個 HTTP Request 會消耗用戶端 Client 的資源，產生過度擷取資料的狀態，因而造成使用者體驗的不良感受與結果，特別是當使用者 end user 使用的設備是手機或是網路屬於網速較不穩定的網路來源時。
