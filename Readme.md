# Huan Chen's Homework #5 林孟蓉v3

## Lecture 13: IoT Flask Web (github, vs code)
### Development Environment Setup
<img src="https://www.ronan.bzh/p/dynamic-charts-with-highcharts-sqlite-and-python/dynamic-charts-with-Highcharts-SQLite-Python_hu5e0addf2b3f28357bc3c2d644de75f1a_118894_1600x0_resize_linear_2.png">
1. Please install vs code, register github, install git for windows
2. (check-point 1) github create a new repository (aiot0518)
3. go to vs code clone this repository  
4. vs code 安裝 python extension 
5. pip install flask, pandas, sklearn 
  * 快捷鍵 ctrl+shift+p ===> package manager 叫出 (git clone....)
  * 快捷鍵 ctrl+' ==> 叫出終端機 
6. (check-point 2) 為了要upload local file to github from local要終端機 C:> 設定下面
   * C:> git config --global user.name "Huan Chen"
   * C:> git config --global user.email huanchen1107@gmail.com
 <img src="./step.jpg" height=300 />  

### Flask Web Development 

1. (check-point 3) simple flask web
 * return 'hello world'
 * retun "<h1>Hello World big font</h1>"
 * return return app.send_static_file('index.html')  ==> remeber to create static/index.html



