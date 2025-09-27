# TEST API DANG KY 
# 1 POST http://localhost:3000/auth/register
# USERNAME:ADMIN PASSWORD:12345
#  "message": "User registered successfully!"
![apidemo](/public/img/dangkythanhcong.png)
# user duoc luu vao co so du lieu
![apidemo](/public/img/taikhoaninmongodb.png)
# 2.login 
# POST http://localhost:3000/auth/login (voi username va password nhuw tren)
![apidemo](/public/img/loginthanhcong.png)
# sau khi login thanh cong chon vao cookie phia ben phai cua postman
![apidemo](/public/img/cookies_loginthanhcong.png)
# session trong mongodb sau khi login thanh cong
![apidemo](/public/img/session_in_mongo.png)
# 3.GOTO PROFILE 
# get http://localhost:3000/auth/PROFILE(SAU KHI LOGIN THANH CONG)
![apidemo](/public/img/profile_loggedin.png)
# 4.logout 
# get http://localhost:3000/auth/logout
![apidemo](/public/img/loggout.png)
# kiem tra lai cookie tai postman va session trong mongodb
![apidemo](/public/img/session_logged%20out.png)
![apidemo](/public/img/no_cookie.png)



