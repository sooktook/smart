
### Quick start

#### Install Python environment

- Environment preparation: Official [latest Python download link](https://www.python.org/downloads/release/python-390/  "Latest Python download link")

If the download is too slow, you can go to [Taobao mirror image download](https://npm.taobao.org/mirrors/python/3.9.0/ "Taobao mirror image download")

You can also download [windows 64 bit installation version](https://npm.taobao.org/mirrors/python/3.9.0/python-3.9.0-amd64.exe "Windows 64 bit installation version")

[Mac computer installation version](http://npm.taobao.org/mirrors/python/3.9.0/python-3.9.0rc2-macosx10.9.pkg "Mac computer installation version")

- [window platform installation video introduction](https://www.ixigua.com/6910413586208653837?id=6901867671193649668 "Window platform installation video introduction")

**Note: when Windows installs python, you need to select "add to path"**



#### Installing smartchart

```shell script

pip3 install smartchart



If the installation process is slow, it is recommended to use it

pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple smartchart -U



Upgrade method:

PIP3 install smartchart - U (upgrade)

```



[smartchart getting started document entry](https://gitee.com/smartchart/smartchart/wikis/ "Getting started with smartchart")




### Application scenario 1:

If you are not familiar with Django / python, you only need a visual development platform, which can be started quickly and used independently

```shell script

Local command line startup:

smartchart

Or smartcharts (automatically open web pages)

If you are a server deployment, remote access, server startup method:

smartchart runserver 0.0.0.0:8000 --insecure --noreload

```

**Administrator account password: admin / Admin, please change the password in time**



[smartchart getting started document entry](https://gitee.com/smartchart/smartchart/wikis/ "Getting started with smartchart")




-------------------------------------------------------------------------------



### Application scenario 2:

If you are a data analysis enthusiast and are using jupyter, pandas and other analysis tools, you can use them as visualization tools

**It supports Python drawing tools such as pyecarts and Matplotlib to be used in Jupiter, which is more convenient and cool**

**There are only two commands, get and set, which can simplify the data analysis work, solidify the analyzed data and generate a cool dashboard**

[getting started with smartchart in jupyter](https://gitee.com/smartchart/smartchart/wikis/6.Jupyter%E5%BA%94%E7%94%A8/%E5%9C%A8Jupyter%E4%B8%AD%E4%BD%BF%E7%94%A8%E6%8C%87%E5%BC%95 "Getting started using smartchart in Jupiter")




-------------------------------------------------------------------------------

### Application scenario 3:

You can also use smartchart to make reports and embed reports in your application system

[embedded smartchart report getting started document](https://gitee.com/smartchart/smartchart/wikis/7.%E6%8A%A5%E8%A1%A8%E5%B5%8C%E5%85%A5/%E7%AE%80%E5%8D%95%E5%B5%8C%E5%85%A5 "Embedded smartchart report getting started document")



-------------------------------------------------------------------------------

### Application scenario 4:

If you are a developer of Django application, congratulations. It can be a seamless part of your project

The functions of data visualization, dashboard and low code API development platform are instantaneous

[getting started with smartchart in Django](https://gitee.com/smartchart/smartchart/wikis/8.Django%E5%BA%94%E7%94%A8/%E5%B5%8C%E5%85%A5Django%)
-Django novices recommend downloading this project
```shell script
Please download the gitee / GitHub project directly
pip install smartchart
Startup method: Python manage py runserver
Account number: admin / Admin
```
------------------------------------------------
### Database support description
Smartchart can theoretically support any data source ,Mysql, SQLite, API and Excel data are supported by default. You can use Python connector to extend any data source
- SQL server requires PIP install pymssql
- Oracle needs to install PIP install Cx_ Oracle
- GP, postgrep needs to install PIP install psychopg2
- PIP install impyla is required for impala
- DB2 requires PIP install IBM_ db
- Python requires PIP install pandas, openpyxl
- ....


### Contact us for help
You can also join QQ group to discuss common problems
**QQ group: 476715246 Code: smartchart**
-------------------------------------------------------------------------------
#### Change Log
```shell script
2020 / 12 / 14 static resource localization
v3. 9.8.2 support all common databases, Vue and datav
v3. 9.8.7 support Jupiter, one click sharing and application of dashboard template
v3. 9.8.9 account binding function online
v3. 9.8.10 user defined graphics management online
v3. 9.8.17 support the latest echarts5 0, optimize loading speed
v3. 9.8.20 user defined graphics management function upgrade
v3. 9.8.23 echarts upgrades to 5.0.1, which supports multiple queries corresponding to one dataset and resource localization
v3. 9.9.0 print function optimization, new pivot function, personal static resource path display, DB2 support
v3. 9.9.1 development interface beautification
v3. 9.9.5 optimize the development interface, fix regularly refresh the bug, add and delete batch datasets
v3. 9.9.7 add Python connector, data pool, customize main template and optimize development interface
v3. 9.9.10 you can write CSS in div settings, add built-in dynamic tables, optimize layout support, and add config files
v3. 9.9.12 optimize background data processing performance and jupyter experience
v3. 9.9.16 add template editing function, add embedded report token mode, optimize editing interface and connection pool selection
v3. 9.9.18 fix Vue bug, add elementui support and optimize datav development experience
v3. 9.9.24 add editing function in the template development interface, automatically create data set, add data set test function, and upgrade echarts to 5.2
v3. 9.9.25 add the prompt of unsaved changes, select and execute the dataset, and optimize the repeated submission of the saved template
v3. 9.9.28 admin adaptation UI, resource file optimization
v3. 9.9.33 add file upload function, add basesimple template and optimize development menu
v4. 0
-Cancel the bootstrap layout, adopt a new 24 grid or 12 grid layout, smaller file references and more convenient functions
-Add drag and drop layout without losing the free development mode, which can be mixed
-Add HTML component to distinguish it from dataset component
-A more user-friendly home page and a new UI experience automatically identify users and developers
-Optimize the development menu and enhance the user development experience
-The front-end development interface and background data set synchronization are completed
v5. 0
-Newly developed UI experience and optimized drag and drop
-Remove the bootstrap completely and reduce the installation package
-All 40 graphic themes are open
-New custom theme development function and new color palette
-Add embedded and pop-up window development switch
-Interface of linkage drilling
-Graphic editor optimization adds one click Import of common graphics
-Add template T3 compatible 3.0 Report
-Add data set development to set graphic linkage
-Add data set development to set cache and timing
-Adding data set development can be converted into shared data set with one click
v5. one
-Add offline initialization dB and add dataset external service API configuration
-Optimize static resources and add VIP template function
-Add one key to scroll tables and pictures, rotate graphics, and add one key to achieve border effect
-The enhanced experience removes the default loading of map JS, and all unusual JS are changed to dynamic loading
```
