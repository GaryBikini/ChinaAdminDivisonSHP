# ChinaAdminDivisonSHP
中国行政区划矢量图，ESRI Shapefile格式，共四级：国家、省/直辖市、市、区/县。关键字：中国行政区划图；中国地图；中国行政区；中国行政区地图；行政区地图；行政区；行政区划；地图；矢量数据；矢量地理数据；省级；直辖市；市级；区/县级；行政区划图。

## 详细信息
数据来源：高德Web服务API中的[行政区域查询](https://lbs.amap.com/api/webservice/guide/api/district)

数据格式：ESRI Shapefile

坐标系统：WGS 84（实际为[火星坐标系——GCJ-02](https://zh.wikipedia.org/wiki/%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E5%9C%B0%E7%90%86%E6%95%B0%E6%8D%AE%E9%99%90%E5%88%B6#GCJ-02)，见[参考资料](https://lbs.amap.com/api/javascript-api/guide/transform/convertfrom)；其基于WGS 1984，但在经纬度中加入了看似随机的偏移）


## 数据列表
1. Country（国家级）：country.shp

2. Province（省级）：province.shp

3. City（市级）：city.shp

4. District（区/县级）：district.shp

## 示例
1. Country
![Country](5.%20Demo/Country.png)
![Country Attribute](5.%20Demo/CountryAttr.png)

2. Province
![Province](5.%20Demo/Province.png)
![Province Attribute](5.%20Demo/ProvinceAttr.png)

3. City
![City](5.%20Demo/City.png)
![City Attribute](5.%20Demo/CityAttr.png)

4. District
![District](5.%20Demo/District.png)
![District Attribute](5.%20Demo/DistrictAttr.png)

## 说明
有关属性数据中的一些英文简写说明

adcode：administrative code，行政编码（六位数字, 前两位是省，中间是市，后面两位是区/县）

cn：country

pr：province

ct：city

dt：district

## 引用
[![DOI](https://zenodo.org/badge/269489269.svg)](https://zenodo.org/badge/latestdoi/269489269)

推荐引用格式：GaryBikini/ChinaAdminDivisonSHP: v2.0, 2021, DOI: 10.5281/zenodo.4167299

## 标注本项目的论文
[1] JIANG ZY, ZHAO S, YANG ZY, JIA FL, HÁJEK J. A review of Copelatus Erichson, 1832 of Mainland China, with description of ten new species from the japonicus complex (Coleoptera: Dytiscidae: Copelatinae). Zootaxa. 2022;5124(3):251-295. doi:10.11646/zootaxa.5124.3.1

[2] Chang H, Li L, Huang J, Zhang Q, Chin KS. Tracking traffic congestion and accidents using social media data: A case study of Shanghai. Accid Anal Prev. 2022;169(August 2021):106618. doi:10.1016/j.aap.2022.106618
