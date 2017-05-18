# Facebook-Get-Posts-Group
Get Posts in Group via AJAX Jquery Graph using Token and display to table bootstrap 3
---
# Edit 
## CHANGE TO **YOUR TOKEN**
`var accessT = "*TOKEN CUA BAN*"; // Gán token`

## CHANGE **ID GROUP** TO YOUR GROUP FACEBOOK
`var urlGraph = 'https://graph.facebook.com/v2.3/*ID GROUP*/feed?limit=100&access_token='+accessT;`

## CHANGE variable **limitTime**
*It will only get posts in limit time, miliseconds*

- Example: if you want to get posts in 24 hours. Set **limitTime = 86400** (86400 seconds = 24 hours)

`var urlGraph = 'https://graph.facebook.com/v2.3/*ID GROUP*/feed?limit=100&access_token='+accessT;`

---
IF YOUR PAGE IS CLOSED OR SECRET, YOUR PERMISSION OF TOKEN MUST BE HAVE MANAGED_GROUP
---
# SAVE AND RUN FILE ON CHROME OR OTHER BROWSERS

- [^1]: This code using jquery to get data from graph API facebook - So it take a long time to finish. About 2 - 3 minute to get 4000 posts
- [^2]: This code using graph v2.3
- [^3]: This is my first practive about using jquery and api graph facebook
