## 脚手架(AI相关)
> 对于 Java 开发者来说，将常用的基础依赖（如 Lombok、MyBatis-Plus、Spring AI 等）、全局异常处理、标准目录结构封装成脚手架，能极大地提升后续新项目的开发效率

# 具体做法
1. 下载脚手架到本地(archetype-1.0.0目录下)
2. ``` shell
   执行mvn clean install
3. >  + 打开 IDEA，点击 File -> New -> Project...
   >  + 在左侧菜单选择 Maven Archetype（或者旧版本 IDEA 选择 Maven 后勾选 Create from archetype）。
   >  + 点击右边的 Add Archetype（或者 Manage Catalogs / Add... 按钮）。
   >  + 在弹出的框中填入你骨架的坐标（和你 pom.xml 里写的一样）：
   >  + GroupId: com.duncan.ai
   >  + ArtifactId: archetype-archetype
   >  + Version: 1.0.0
   >  + 点击 OK 后，在列表中选中你刚刚添加的 com.duncan.ai:archetype-archetype，点击 Next。
   >  + 接下来填入新项目的名字（比如 my-new-app），点击 Finish。

4. 修改xxx-app模块下的yml文件的ai相关的配置