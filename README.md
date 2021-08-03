<p align="center"><a href="https://dataease.io"><img src="https://dataease.oss-cn-hangzhou.aliyuncs.com/img/dataease-logo.png" alt="DataEase" width="300" /></a></p>
<h3 align="center">人人可用的开源数据可视化分析工具</h3>
<p align="center">
  <a href="https://www.gnu.org/licenses/old-licenses/gpl-2.0"><img src="https://img.shields.io/github/license/dataease/dataease?color=%231890FF&style=flat-square" alt="License: GPL v2"></a>
  <a href="https://app.codacy.com/gh/dataease/dataease?utm_source=github.com&utm_medium=referral&utm_content=dataease/dataease&utm_campaign=Badge_Grade_Dashboard"><img src="https://app.codacy.com/project/badge/Grade/da67574fd82b473992781d1386b937ef" alt="Codacy"></a>
  <a href="https://github.com/dataease/dataease/releases/latest"><img src="https://img.shields.io/github/v/release/dataease/dataease" alt="Latest release"></a>
  <a href="https://github.com/dataease/dataease"><img src="https://img.shields.io/github/stars/dataease/dataease?color=%231890FF&style=flat-square" alt="Stars"></a>
  <a href="https://github.com/dataease/dataease/releases/latest"><img src="https://img.shields.io/github/downloads/dataease/dataease/total" alt="Downloads"></a>
</p>
<hr />
DataEase is an open source data visualization analysis tool that helps users quickly analyze data and gain insights into business trends, thereby achieving business improvement and optimization. DataEase supports rich data source connections, can quickly create charts by dragging and dropping, and can be easily shared with others.

### DataEase 的功能：

Chart display: support PC terminal, mobile terminal and large screen;
Chart production: support rich chart types (based on Apache ECharts implementation), support drag-and-drop method to quickly create dashboards;
Data engine: support direct connection mode, local mode (based on Apache Doris / Kettle implementation);
Data connection: support relational databases, Excel and other files, Hadoop and other big data platforms, NoSQL and other data sources.

### DataEase 的优势：

-Open source: zero threshold, fast online acquisition and installation; fast user feedback, monthly release of new versions;
-Simple and easy to use: very easy to use, analysis can be completed by clicking and dragging with the mouse;
-Second-level response: Integrate Apache Doris, and second-level query return delay under extremely large data volume;
-Safe sharing: Support multiple data sharing methods to ensure data security.
## UI 展示

![de-ui](https://www.fit2cloud.com/dataease/images/screenshot/dataease-v1.gif)

## 功能架构

![de-architecture](https://dataease.oss-cn-hangzhou.aliyuncs.com/img/de-architecture.png)

## 在线体验

-Environment address: <https://demo.dataease.io/>
-Username: demo
-Password: dataease

## 快速开始

Quickly install DataEase in two steps:

1. Prepare a 64-bit Linux host with no less than 8 G of RAM;
2. As the root user, execute the following command to install DataEase with one click.

```sh
curl -sSL https://github.com/dataease/dataease/releases/latest/download/quick_start.sh | sh
```

-[Online Documentation](https://dataease.io/docs/)
-[Demo Video](https://www.bilibili.com/video/BV1UB4y1K7jA)

## WeChat Group

<img src="https://dataease.oss-cn-hangzhou.aliyuncs.com/img/wechat-group.png" width="156" height="156"/>

## 技术栈
-Backend: [Spring Boot](https://spring.io/projects/spring-boot)
-Front end: [Vue.js](https://vuejs.org/), [Element](https://element.eleme.cn/), [Apache ECharts](https://github.com/apache/ echarts)
-Middleware: [MySQL](https://www.mysql.com/)
-Data processing: [Kettle](https://github.com/pentaho/pentaho-kettle), [Apache Doris](https://github.com/apache/incubator-doris/)
-Infrastructure: [Docker](https://www.docker.com/)

## License & Copyright

Copyright (c) 2014-2021 飞致云 FIT2CLOUD, All rights reserved.

Licensed under The GNU General Public License version 2 (GPLv2)  (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

<https://www.gnu.org/licenses/gpl-2.0.html>

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
