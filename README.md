# Url-Shortener: URL shortening services like bit.ly or TinyURL are very popular to generate shorter aliases for long URLs. You need to design this kind of web service where if a user gives a long URL then the service returns a short URL and if the user gives a short URL then it returns the original long URL. For example, shortening the given URL through TinyURL![Url-Shortener - Google Chrome 2_26_2023 12_02_38 AM](https://user-images.githubusercontent.com/69891196/221373872-ebd926c5-aff6-4f10-ae33-35e9386c9912.png)
Given a long URL, the service should generate a shorter and unique alias for it.
When the user hits a short link, the service should redirect to the original link.
Links will expire after a standard default time span.
The system should be highly available. This is really important to consider because if the service goes down, all the URL redirection will start failing.
URL redirection should happen in real-time with minimal latency.
Shortened links should not be predictable.![Url-Shortener - Google Chrome 2_26_2023 12_02_38 AM](https://user-images.githubusercontent.com/69891196/221373903-0fa3e68b-5026-4bad-afa1-91dfc98877f7.png)
