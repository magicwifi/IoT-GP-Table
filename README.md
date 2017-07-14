# IoT-Table-GP


# sensor_count：

### 用于记录每天立磨设备各个传感器上报数据的条数

* date: 日期
* deviceid: 设备编号
* sensor: 传感器编号
* count: 上报数据条数

<br/>

# sensor_exceed：

### 用于记录每天不同立磨设备，各个时间段（小时）传感器的超限（超过99.99%）的值

* date: 日期
* deviceid: 设备编号
* sensor: 传感器编号
* hour: 时间段（按小时区分）
* count: 超限（超过99.99%）的条目


<br/>

# sensor_hour_max_min：

### 用于记录每天不同立磨设备，各个时间段（小时）传感器的最大值，最小值，平均值

* date: 日期
* deviceid: 设备编号
* sensor: 传感器编号
* hour: 时间段（按小时区分）
* max: 一小时内最大值
* min: 一小时内最小值
* avg: 一小时内平均值

<br/>

# sensor_max_min：

### 用于记录每天不同立磨设备，各传感器的最大值，最小值，平均值

* date: 日期
* deviceid: 设备编号
* sensor: 传感器编号
* max: 当天最大值
* min: 当天最小值
* avg: 当天内平均值

<br/>

# sensor_restart_count：

### 用于记录每天不同立磨设备, 启动次数与工作时间

* date: 日期
* deviceid: 设备编号
* restart_count: 重启次数
* spendtime: 工作时间


<br/>

# sensor_temperature_kmeans

### 通过统计多个传感器状态，用于记录立磨设备工作温度的分类

* date: 日期
* clusterid: 温度分类编号（高温状态, 低温，正常）
* cluster_num: 每个分类所对应的数据总条数
* sensor1: 立磨出口温度在不同分类的临界值
* sensor2: 电机轴承温度在不同分类的临界值
* sensor3: 立磨北进口温度在不同分类的临界值


<br/>

# sensor_top_value

### 用于记录每天不同立磨设备，每日的超限（超过99.99%）的值

* date: 日期
* deviceid: 设备编号
* sensor: 传感器编号
* topvalue: 超限（超过99.99%）的条值
* count: 传感器总条数



