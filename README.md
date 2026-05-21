POST https://www.ai9poker.com/Account/Login
Request headers:
{
  "cache-control": "no-cache",
  "Access-Control-Allow-Origin": "*",
  "Accept": "application/json",
  "X-App-Version": "5",
  "global-localization": "en",
  "Authorization": "[REDACTED]",
  "Access-Control-Allow-Headers": "*"
}
Request body:
{}

HTTP 500 InternalServerError

Response headers:
{
  "Date": [
    "Thu, 21 May 2026 18:49:19 GMT"
  ],
  "Transfer-Encoding": [
    "chunked"
  ],
  "Connection": [
    "keep-alive"
  ],
  "Server": [
    "cloudflare"
  ],
  "X-Powered-By": [
    "ASP.NET"
  ],
  "x-powered-by-plesk": [
    "PleskWin"
  ],
  "cf-cache-status": [
    "DYNAMIC"
  ],
  "Nel": [
    "{\"report_to\":\"cf-nel\",\"success_fraction\":0.0,\"max_age\":604800}"
  ],
  "Report-To": [
    "{\"group\":\"cf-nel\",\"max_age\":604800,\"endpoints\":[{\"url\":\"https://a.nel.cloudflare.com/report/v4?s=wk1YyR7Ap0eyFJThriQVC66mex1mUf5NxIVdnCgMp%2BvsyBl2osIOjaxPMwxgEJSYXTKhLQ11ghIXLmtWKqy9wD%2BFTxDzYk%2BcO8iPkK2bOD9DzO2nYxhQUt4n%2FfkxAWMCYfJp\"}]}"
  ],
  "CF-RAY": [
    "9ff5c2a5db79ace6-MRS"
  ],
  "Alt-Svc": [
    "h3=\":443\""
  ],
  "Content-Type": [
    "application/json"
  ]
}

Response body:
{
  "Error": {
    "Code": "Exception",
    "Message": "Value cannot be null. (Parameter 'Username')",
    "Details": "System.ArgumentNullException: Value cannot be null. (Parameter 'Username')\r\n   at AIPoker.Membership.Pages.AccountPage.<>c__DisplayClass9_0.<Login>b__0() in C:\\inetpub\\wwwroot\\AIPokerWeb\\AIPoker.Web\\Modules\\Membership\\Account\\AccountPage.cs:line 52\r\n   at Serenity.Services.EndpointExtensions.ExecuteMethod[TResponse](ControllerBase controller, Func`1 handler) in /_/src/Serenity.Net.Web/Mvc/EndpointExtensions.cs:line 93"
  }
  
  
  
  