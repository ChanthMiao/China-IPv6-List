# China-IPv6-List

中国大陆IPv6地址库

## 说明

本项目为[gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip)的个人重构，和原项目有以下不同：

- 移除了具体的运营商分类，仅保留了中国大陆IPv6地址
- 构建流程完全迁移至Github Action，北京时间每日6:00自动构建

## 下载地址

> 2023.01.24 更新: 因 [jsdelivr 大陆服务节点关闭](https://luotianyi.vc/6295.html)，移除相应 CDN 链接。

- cn6.txt:
  - <https://raw.githubusercontent.com/ChanthMiao/China-IPv6-List/release/cn6.txt>
- cn6.txt.sha256sum:
  - <https://raw.githubusercontent.com/ChanthMiao/China-IPv6-List/release/cn6.txt.sha256sum>

## 致谢

- 感谢[gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip)项目提供的具体实现方法
- 感谢[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip)项目提供的Github Action编写参考

## License

The code in this repository is licensed under the [MIT License](https://github.com/ChanthMiao/China-IPv6-List/blob/main/LICENSE).
