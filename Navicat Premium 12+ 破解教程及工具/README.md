#### Navicat Premium 12.1 + Mac 破解教程

来源: [navicat-keygen](https://github.com/DoubleLabyrinth/navicat-keygen)

```shell
git clone git@github.com:DoubleLabyrinth/navicat-keygen.git
```

`homebrew` 安装库
```shell
brew install openssl
brew install capstone
brew install keystone
brew install rapidjson
```

切换分支到`mac`

![image](https://user-images.githubusercontent.com/20939839/61688376-6fbe1900-ad57-11e9-94b5-3df33a4c4e98.png)

![image](https://user-images.githubusercontent.com/20939839/61688214-02aa8380-ad57-11e9-875f-b3569019422a.png)

```shell
git checkout mac

make all

ls bin
```

```
备份好 Navicat Premium.app/Contents/MacOS/Navicat Premium 文件，以及 Navicat 中所有的数据库连接配置信息（包括密码）。
删掉 Keychain.app 中所有由 Navicat 保存的密码。

```

生成证书

![image](https://user-images.githubusercontent.com/20939839/61688427-91b79b80-ad57-11e9-97dc-90e4ca4e57bd.png)

![image](https://user-images.githubusercontent.com/20939839/61688394-7cdb0800-ad57-11e9-997d-70aba6c3236c.png)

```
钥匙串访问 -> 证书助理 -> 创建证书

codesign -f -s "navicat" /Applications/Navicat\ Premium.app
```

运行
![image](https://user-images.githubusercontent.com/20939839/61688249-16ee8080-ad57-11e9-933e-6d655d07c34e.png)

![image](https://user-images.githubusercontent.com/20939839/61688264-1f46bb80-ad57-11e9-83ae-cf76f6e31321.png)
```shell
./navicat-patcher /Applications/Navicat\ Premium.app/Contents/MacOS/Navicat\ Premium

codesign -f -s "Navicat" /Applications/Navicat\ Premium.app/

./navicat-keygen ./RegPrivateKey.pem
```


#### Navicat Premium 12+ windows 破解教程及工具

![image](https://user-images.githubusercontent.com/20939839/54656750-d9a48880-4b01-11e9-94cf-dfdef3b59d56.png)

1、Patch

![image](https://user-images.githubusercontent.com/20939839/54657022-d9f15380-4b02-11e9-8a67-f0c335e4654c.png)

2、Serial Keygen Generate

![image](https://user-images.githubusercontent.com/20939839/54656871-533c7680-4b02-11e9-8bd6-12c1c90572ac.png)

3、Open Navicat

![image](https://user-images.githubusercontent.com/20939839/54656858-4029a680-4b02-11e9-95fc-0a711aa8e694.png)

4、Paste the Code

![image](https://user-images.githubusercontent.com/20939839/54657113-1fae1c00-4b03-11e9-880d-84feba678dab.png)

5、Copy the request code to Keygen v4.9 and Generate

![image](https://user-images.githubusercontent.com/20939839/54657152-41a79e80-4b03-11e9-91b4-de0066e0fda9.png)

6、Activation

![image](https://user-images.githubusercontent.com/20939839/54656921-8252e800-4b02-11e9-88f3-405625ac0cbe.png)

![image](https://user-images.githubusercontent.com/20939839/54656901-6d765480-4b02-11e9-990a-ebfb8701fdf5.png)


[Github: Navicat_Keygen_Patch_By_DFoX](https://github.com/Deltafox79/Navicat_Keygen/tree/master/Navicat_Keygen_Patch_By_DFoX)
