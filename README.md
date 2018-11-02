# solar_system_23shiji

200年后的太阳系在线地图。
An online map of solar system after 200 years later.

##太阳系行星以及冥王星近似位置计算

利用Keplerian Elements近似计算3000BC-3000AD太阳系主要天体位置
精度有限，更加高精度的星表需要通过服务器计算，不适合利用浏览器脚本进行计算。
参考文献：https://ssd.jpl.nasa.gov/txt/aprx_pos_planets.pdf
感谢NASA下属JPL实验室提供轨道元素。


##太阳系2D地图

利用Zrender进行2D渲染，以及事件处理
