---
title: "访客预约"
source: https://www.yuque.com/u25372512/sah16y/smrbr9ptuzlhtgnt
book: "帮助中心"
book_slug: sah16y
yuque_doc_id: 191708420
word_count: 2927
images: 40
content_updated_at: 2026-05-26
extract_mode: sourcecode
status: ok
---
**访客预约功能有两种预约方式，一是在平台进行登记预约，而是访客可以通过小程序提前进行停车预约。**

### **1、车场开启访客预约功能**
**用访客预约功能之前需要开启访客预约功能**

+ **<font style="color:rgb(34, 34, 34);">开启功能</font>**<font style="color:rgb(34, 34, 34);">：</font>
    - <font style="color:rgb(34, 34, 34);">路径：【全局设置】->【基本参数】。</font>
    - <font style="color:rgb(34, 34, 34);">操作：找到“是否启用访客功能”，选择“确认”。</font>

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728897732755-b3a9123f-3c8b-41d9-a1c5-f7b522ade369.png)

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728897837684-be1669de-48f9-4e66-aa16-174ebe94f8e6.png)

| 是否启用访客功能 | 默认不启用，开启后方可使用此功能 |
| ---: | --- |
| 访客车在预约时间段 | 默认允许多次进出，若设置单次进出则出场后需重新预约。 |
| 访客预约单位 | 默认不开启，可根据需要设置为按天、按小时和按分钟三种。 |
| 访客停留时长 | 默认可设置多个时长，仅可填写数字，多个时长请以英文 , 隔开(例：单位选择按天，时长填写1,3,5，则代表可预约停留时长为1天，3天，5天)。 |


+ **<font style="color:rgb(34, 34, 34);">设置进出规则</font>**<font style="color:rgb(34, 34, 34);">：</font>
    - **<font style="color:rgb(34, 34, 34);">进出模式</font>**<font style="color:rgb(34, 34, 34);">：可设置为“允许多次进出”（默认）或“单次进出”（出场后需重新预约）。</font>
    - **<font style="color:rgb(34, 34, 34);">预约单位与时长</font>**<font style="color:rgb(34, 34, 34);">：</font>
        * <font style="color:rgb(34, 34, 34);">可设置预约单位为</font>**<font style="color:rgb(34, 34, 34);">按天、按小时或按分钟</font>**<font style="color:rgb(34, 34, 34);">。</font>
        * **<font style="color:rgb(34, 34, 34);">停留时长</font>**<font style="color:rgb(34, 34, 34);">：可设置多个时长选项（如 </font>`<font style="color:rgb(34, 34, 34);">1,3,5</font>`<font style="color:rgb(34, 34, 34);">），中间需用</font>**<font style="color:rgb(34, 34, 34);">英文逗号</font>**<font style="color:rgb(34, 34, 34);">隔开。</font>

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728641519163-49f79e58-6da3-478d-ad61-6fdf175ee08f.png?x-oss-process=image%2Fformat%2Cwebp%2Fresize%2Cw_605%2Climit_0)

**<font style="color:rgb(34, 34, 34);">高级参数配置（关键步骤）</font>**<font style="color:rgb(34, 34, 34);">：</font>

+ <font style="color:rgb(34, 34, 34);">路径：【高级参数】->【新增参数】->【预约停车参数】。</font>

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728900935503-2e7b03d7-ce17-408e-bc0d-9edbeff494c5.png)

| 参数类型 | 选择预约停车参数 |
| ---: | --- |
| 参数值 | 选择扫码登记预约免审核车辆可直接进入车场，选择扫码登记预约需审核需要经过审核后预约车辆才能进场 |
| 备注 | 可选填 |
| 访客车通行通道 | 默认选择出入口，若只选择入口，预约车辆出场时需要人工放行 |


**【新增参数】--【自助注册参数】--确定（填写完相应信息）**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728903178080-ffc63f72-d74e-40e1-a2e6-65c89fce2d70.png)

**<font style="color:#DF2A3F;">注：不开启自助注册参数则小程序车场显示【暂未开放】，车主不能进行预约停车</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728903487121-e9937f53-766d-4879-9069-41fa52c2f56e.png)

### 2、新增业主信息
<font style="color:rgb(34, 34, 34);">访客预约必须关联到具体的业主，因此需要先录入业主信息。</font>

+ **<font style="color:rgb(34, 34, 34);">新增业主</font>**<font style="color:rgb(34, 34, 34);">：</font>
    - <font style="color:rgb(34, 34, 34);">路径：【预约管理】->【业主管理】->【新增业主】。</font>
    - <font style="color:rgb(34, 34, 34);">必填项：业主姓名、电话、所属车场。</font>
    - <font style="color:rgb(34, 34, 34);">预约限制：可设置业主的预约开始/截止时间、预约单位（日/月/季/年）及最大预约次数。</font>
+ **<font style="color:rgb(34, 34, 34);">批量导入</font>**<font style="color:rgb(34, 34, 34);">：支持通过模板下载并导入大量业主信息。</font>

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728901064087-b11e65ab-b4b1-4b70-95ab-096933e21b85.png)

| 所属车场 | 默认当前停车场 |
| ---: | --- |
| 业主姓名 | 输入业主姓名（必填） |
| 业主电话 | 输入业主电话（必填） |
| 业主地址 | 输入业主地址 |
| 开始时间 | 点击选择开始时间（24小时制） |
| 截止时间 | 点击选择截止时间（24小时制） |
| 预约单位 | 可选择单位为日、月、季、年 |
| 备注 | 输入备注（可选填） |
| 最大预约次数 | 输入在预约单位内最大的预约次数 |


**也可导入业主信息，在平台【预约管理】--【业主管理】--【业主信息导入】，选择需要导入的文件后确认导入即可。**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728901351379-1cc51e37-981a-4cfb-b3f7-9b9aa3cc037d.png)

**业主信息模板可在【业主管理】--【业主信息导入】弹框中进行下载。**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728901460859-7351270f-1e27-4e65-a244-5f3dae03f29a.png)

### <font style="color:rgb(34, 34, 34);">3、预约登记</font>
#### <font style="color:rgb(34, 34, 34);">1）管理员预约</font>
<font style="color:rgb(34, 34, 34);">系统支持两种预约方式：</font>**<font style="color:rgb(34, 34, 34);">管理员代预约</font>**<font style="color:rgb(34, 34, 34);">和</font>**<font style="color:rgb(34, 34, 34);">车主自助预约</font>**<font style="color:rgb(34, 34, 34);">。</font>

| **<font style="color:rgb(34, 34, 34);">预约方式</font>** | **<font style="color:rgb(34, 34, 34);">操作主体</font>** | **<font style="color:rgb(34, 34, 34);">操作路径/入口</font>** | **<font style="color:rgb(34, 34, 34);">特点</font>** |
| :--- | :--- | :--- | :--- |
| **<font style="color:rgb(34, 34, 34);">管理员预约</font>** | <font style="color:rgb(34, 34, 34);">车场管理员</font> | <font style="color:rgb(34, 34, 34);">平台【预约管理】->【预约记录】->【新增预约】</font> | <font style="color:rgb(34, 34, 34);">无需审核，直接生效。需填写车牌、时间、事由及关联业主。</font> |
| **<font style="color:rgb(34, 34, 34);">车主预约</font>** | <font style="color:rgb(34, 34, 34);">访客/车主</font> | <font style="color:rgb(34, 34, 34);">微信搜索【壹家社区】小程序 或 扫描入口二维码</font> | <font style="color:rgb(34, 34, 34);">需根据后台设置判断是否需要审核。预约成功后会收到短信验证码。</font> |


![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728901718103-0ccfcd54-5243-48f0-8914-432f258bd29e.png)

| <font style="color:rgb(34, 34, 34);">所属车场</font> | <font style="color:rgb(34, 34, 34);">默认当前停车场</font> |
| ---: | --- |
| <font style="color:rgb(34, 34, 34);">开始时间</font> | <font style="color:rgb(34, 34, 34);">点击选择预约车辆进场时间</font> |
| <font style="color:rgb(34, 34, 34);">结束时间</font> | <font style="color:rgb(34, 34, 34);">点击选择预约车辆出场时间</font> |
| <font style="color:rgb(34, 34, 34);">预约车牌</font> | <font style="color:rgb(34, 34, 34);">填写正确的预约车牌号</font> |
| <font style="color:rgb(34, 34, 34);">预约人姓名</font> | <font style="color:rgb(34, 34, 34);">填写预约人姓名</font> |
| <font style="color:rgb(34, 34, 34);">预约人手机号</font> | <font style="color:rgb(34, 34, 34);">填写预约人手机号码</font> |
| <font style="color:rgb(34, 34, 34);">业主姓名</font> | <font style="color:rgb(34, 34, 34);">填写业主姓名</font> |
| <font style="color:rgb(34, 34, 34);">业主手机号</font> | <font style="color:rgb(34, 34, 34);">填写业主电话号码</font> |
| <font style="color:rgb(34, 34, 34);">来访事由</font> | <font style="color:rgb(34, 34, 34);">填写来访事由（可选填）</font> |


**<font style="color:rgb(34, 34, 34);">根据需要，管理员可以在【壹家社区】</font>****<font style="color:#DF2A3F;">公众号</font>****<font style="color:rgb(34, 34, 34);">进行访客预约登记，填写相关信息后预约完成</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728964816532-a7fcf391-9a15-421f-a862-e742f3606ec2.png)

**<font style="color:#DF2A3F;">注：管理员直接预约可直接通过审核</font>**

#### **2）车主预约**
**小程序预约**

**车主在微信搜索【壹家社区】****<font style="color:#DF2A3F;">小程序</font>****，进入小程序后在【我的】进行登录，登录后在首页点击【预约停车】，输入停车场名称查询进入车场预约，输入需要填写的信息后点击确认即可。**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728903026945-6aabbbc4-6b5a-4cad-8402-a031f134f2ae.png)

| 请输入车牌号 | 输入正确的车牌号码 |
| ---: | --- |
| 当前车场 | 默认当前停车场 |
| 预约姓名 | 输入预约姓名 |
| 预约手机号 | 输入预约手机号 |
| 预约开始时间 | 点击选择进场的时间 |
| 预约结束时间 | 点击选择出场的时间 |
| 预约事由 | 输入来访原因 |


**车主扫码预约**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/48964439/1728904082750-3916aa25-55a1-4080-959b-e780b1b69da6.jpeg)![](https://cdn.nlark.com/yuque/0/2024/jpeg/48964439/1728904236961-2cc99516-e860-4b85-9dd4-9693d12cfda8.jpeg)![](https://cdn.nlark.com/yuque/0/2024/jpeg/48964439/1728904295300-90766a78-ce9c-41ac-8933-daaa6125dfa5.jpeg)

**注：登记来访信息二维码在【我的车场】--【通道二维码】--【入口二维码】下载**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728903982698-058ddbb3-327a-46ac-8ba4-a53fcb24bc55.png)

**车主预约后可在平台【预约管理】--【预约记录】进行查看，可输入停车场、预约车牌进行搜索查询具体预约信息。**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728904527940-69d298c4-caf2-49c6-b1b2-7f8fd1be2996.png)

**预约记录页面点击【预约记录导出】即可导出预约记录信息。**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728904732033-b707e531-9674-4633-bce2-824baff647aa.png)

**打开下载的预约记录信息表格如下：**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728904695551-106c3e1f-df76-428f-8d49-6661bae52c2d.png)

#### <font style="color:#DF2A3F;">举例1：</font>
**首先，【启用】访客预约功能，选择【单次进出】，访客预约单位选择【按小时】，停留时长【1，2，3】，确定后设置完成**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728637474477-77067c23-2055-4480-894c-fdb9f54fa64f.png)

**<font style="color:#DF2A3F;">注：访客预约设置时长对应车主预约时的来访时长</font>**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728641519163-49f79e58-6da3-478d-ad61-6fdf175ee08f.png)

**然后在【高级参数】里【新增参数】，参数类型选择【预约停车参数】，参数值选择【扫码登记预约免审核】，访客车通行通道选择【坐席chukou】和【坐席rukou】，确定后完成设置**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728637410258-cf473543-5f0a-41f5-b18d-115ba4ec9160.png)

**<font style="color:#DF2A3F;">注：访客车通行通道勾选哪个通道口则表示访客车辆在已勾选的通道口可直接识别自动抬杆入场，不用通过人工放行</font>**

**在【通道管理】--选择通道入口--【通行权限】--关闭****<font style="color:#DF2A3F;">临时车</font>****【通行权限】、【是否自动放行】、【重复进出场】、【车位满是否自动放行】**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728643487122-ad8e90a3-3286-4db0-910e-46aac935ec85.png)

**<font style="color:#DF2A3F;">注：开启访客预约功能与设置临时车通行权限连用，若不关闭临时车通行权限则不用开启访客预约功能临时车也可随意进出停车场；</font>**

**然后在【业主管理】--【新增业主】里添加业主信息，所属车场选择当前车场，业主姓名为【测试业主】，业主电话为【181********】，业主地址为【广东省深圳市龙华区】，开始时间为【00:00】，截止时间为【23：59】，预约单位为【每日】，最大预约次数为【10】，确定后设置完成**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728638172067-756d3420-704c-4dad-b434-6efccb28cee2.png)

**<font style="color:#DF2A3F;">注：必须要设置有一个业主后才能进行预约，若没有业主则来访客车不能进行预约；</font>**

**以上步骤设置完成后，车主扫码二维码进行预约，输入车牌号为【苏A12345】，预约姓名为【晴天】，预约手机号为【171********】，输入正确的手机号后点击【获取验证码】，把手机短信受到的验证码【8121】填好，选择来访时长【2小时】，来访事由为【拜访朋友】，填写完相关信息后点击确认**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728640946340-3cf8a210-4f2b-4d6f-9e25-e6fd2af6687f.png)![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728641161414-c953f84c-c401-48a3-a39a-422ac0238769.png)

**注：登记来访信息二维码在【我的车场】--【通道二维码】--【****<font style="color:#DF2A3F;">入口预约码</font>****】里下载**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728644278388-362b2e57-aa2f-42f0-858e-5318b1f9270b.png)

**有访客进行预约后可在停车平台【预约管理】--【预约记录】进行查看**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728641851841-052ea99f-eafe-42b2-98de-5eeaae0607e0.png)

**注：在启用访客预约功能时设置参数值为【****<font style="color:#DF2A3F;">扫码登记预约免审核</font>****】，所以审核状态为【****<font style="color:#DF2A3F;">审核通过</font>****】**

**也可以在岗亭【预约车辆】查看**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728642557978-f00d1492-2ac2-4ef2-9cdb-9e673b91758a.png)

**当该辆车进场时，即可识别自动开闸入场**

#### <font style="color:#DF2A3F;">举例2：</font>
**首先，【启用】访客预约功能，选择【多次进出】，访客预约单位选择【按天】，停留时长【1，2，3，4,5】，确定后设置完成**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728956045806-57250763-bc4b-4eae-a957-a0b633f8ce34.png)

**然后在【高级参数】里【新增参数】，参数类型选择【预约停车参数】，参数值选择【扫码登记预约需审核】，访客车通行通道选择【入口1】和【入口2】，确定后完成设置**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728956204293-d84f1ab1-a765-4b49-bdfe-bf1d62685c84.png)

**在【通道管理】--选择通道入口--【通行权限】--关闭****<font style="color:#DF2A3F;">临时车</font>****【通行权限】、【是否自动放行】、【车位满是否自动放行】**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728956390053-6f9592b4-bab6-457b-897c-2ef7cf721a09.png)

**然后在【业主管理】--【新增业主】里添加业主信息，所属车场选择当前车场，业主姓名为【赵】，业主电话为【181********】，业主地址为【广东省深圳市龙华区】，开始时间为【00:00】，截止时间为【23：59】，预约单位为【每日】，最大预约次数为【5】，确定后设置完成**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728957326906-a9594a2a-7353-4836-b2b2-b7cd9d431e09.png)

**以上步骤设置完成后，车主扫码二维码进行预约，输入车牌号为【粤B11111】，预约姓名为【杨】，预约手机号为【181********】，输入正确的手机号后点击【获取验证码】，把手机短信受到的验证码【8216】填好，选择来访时长【3天】，来访事由为【探亲】，填写完相关信息后点击确认**

![](https://cdn.nlark.com/yuque/0/2024/jpeg/48964439/1728962968786-fa6e3d7d-4d3f-490d-9482-26465e1f146e.jpeg)![](https://cdn.nlark.com/yuque/0/2024/jpeg/48964439/1728962990414-dc9a9cfc-6ba2-4809-b685-eb8486ce11c8.jpeg)

**车主预约成功后，管理员会在微信上收到停车场预约审批提醒，查看详情可查看预约详情和操作预约驳回与通过，通过后显示审核成功，随即收到预约停车结果通知**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728963497425-abb88fc3-b3d7-4b4a-ad9b-c613ad266766.png)![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728963597583-63ff3b35-dd6f-4243-8337-2cae21f836ce.png)![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728963696120-c607f35a-0dad-4462-b18f-45d2d67461bf.png)![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728963857918-2db78f27-0743-4b11-83c8-b2ac4b6c134e.png)

**可在停车平台【预约管理】--【预约记录】进行查看预约详情**

![](https://cdn.nlark.com/yuque/0/2024/png/48964439/1728964005371-d336469d-0c56-4869-866d-eeef2c37a0b1.png)

**当该辆车进场时，即可识别自动开闸入场**

