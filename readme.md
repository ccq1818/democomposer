## 1.创建github项目并提交
## 2.到https://packagist.org/ 上点击右上角"submit package"，需要登录，点击"login with github"使用github账号登录即可，初次登录会让你登记邮箱，完了再次点击"submit package"。
## 3.填写项目地址"Repository URL"，这个url就是你github上helloworld项目的url。
## 4.点击"check"按钮，系统自动检测你的项目中composer.json是否合格，并给出原因。如果没有错误的话，请点击提交。
## 5.包创建成功，可以根据提示继续配置github自动同步功能，这样每次push后，packagist对应包的版本号也会更新。
## 6.修改包并更新，修改后git push，然后到使用该包的项目中执行composer --dev --prefer-source update  [包名] ，加--prefer-source意思是从github上检出最新版本。
