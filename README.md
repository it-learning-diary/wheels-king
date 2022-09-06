# 项目初衷

轮子之王：将平常开发中非常常用的功能做成轮子，减少开发时间，让开发者拥有更多的时间能够摸鱼
<b>如果本项目给你提供了帮助，请给予支持(star一下，或者推荐给你的朋友)！</b>

轮子即调即用，符合绝大部分导入导出业务逻辑，节省开发时间！



# 已完成轮子

- <b>文件服务器(seaweedfs)轮子：支持上传、下载、删除任何类型的文件</b> 
- <b>excel导入轮子：</b> 支持导入任何exccel数据，可以自定义转换后excel数据处理的业务逻辑(支持抛出异常、事务回滚、记录解析时的异常数据)。
- <b>excel导出轮子：</b> 支持固定表头(兼容多sheet页)和动态表头(兼容多sheet页)方式的数据导出。
- <b>项目模板下载轮子:</b> 支持导出项目或者服务器指定目录下的任意模板文件
- <b>csv导出轮子：</b> 支持String和bean两种定制表头导出方式
- <b>csv导入轮子：</b> 支持String和bean两种数组映射方式导入方式
- <b>ftp轮子</b>: 支持ftp上传、下载
- 其他功能,持续迭代中....



# 分支说明

- main：主分支，会定期合并最新代码
- master：主分支，包含演示代码(学习建议拉取该分支代码)
- release：发布分支(暂未提供)，只包含核心代码，不包含演示代码(<b>项目引入推荐使用该分支</b>)

# 引入方式


- <b>方式一：</b> 将项目打成jar包，在项目中引入(推荐)
- <b>方式二：</b> 引入所需依赖，将工具包复制到自己项目的代码中

# 技术栈

- spring-boot
- easyexcel
- postgresql(可选，用于写演示案例)
- mybatis/mybatis-plus(可选，用于写演示案例)
- hutool
- lombok
- univocity-parsers(用于csv导出导出)
- commons-net(用于ftp上传、下载)
- seaweedfs-client(用于文件服务器上传、下载、删除操作)



# 更新日志

  - 2022-9-06: ftp工具集成从远端下载文件到本地，引入springboot-test添加本地测试
  - 2022-7-16: 引入文件服务器，支持上传、下载、删除任何类型的文件(兼容中英文名称下载)
  - 2022-7-14：引入ftp上传、下载轮子
  - 2022-6-06：新增excel动态导出案例
  - 2022-5-22：excel导入轮子 + csv导入轮子 添加导入文件类型校验和导入字段校验
  - 2022-5-18：csv导入轮子集成(支持事务、异常日志记录，数组+实体映射数据两种方式) + 使用案例
  - 2022-5-17：csv导出轮子集成 + 使用案例
  - 2022-4-30：excel导入轮子添加事务回滚、异常日志记录支持，新增下载项目模板文件轮子
  - 2022-4-25：项目导入、excel导出轮子

