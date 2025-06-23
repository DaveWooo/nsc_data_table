# [NSC_Report].[dbo].[NSC_ORDER] 字段注释说明
本表记录了NSC系统订单的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名                   | 注释说明                                                                 |
|--------------------------|--------------------------------------------------------------------------|
| Unionid                  | 用户唯一标识（如微信 UnionID）                                           |
| Mobile                   | 用户手机号                                                               |
| ProductCode              | 产品编码                                                                 |
| ProductName              | 产品名称                                                                 |
| TankBarcode              | 罐条码（商品唯一罐体标识）                                               |
| BoxBarcode               | 箱条码（商品外包装箱标识）                                               |
| Qty                      | 购买数量                                                                 |
| BuyTime                  | 购买时间                                                                 |
| Source                   | 订单来源（如NSC+,NSCtoB等）                                               |
| NewCustomerType          | 新客类型（如超启新客，特护新客）                                           |
| Brand                    | 品牌 (如超启能恩，AL110, PreNAN, 铂初能恩，数舒宜能恩，力多精)             |
| Stage                    | 阶段（如促销期、常规期等）                                               |
| province                 | 省份                                                                     |
| area_name                | 区域名称                                                                 |
| city_group               | 城市分组                                                                 |
| city                     | 城市                                                                     |
| ka_type                  | KA 类型（大客户类型）                                                     |
| ka_name                  | KA 名称（大客户名称）                                                     |
| SNCCode                  | SNC 编码（门店编码或系统编号）                                            |
| StoreCode                | 门店编码                                                                 |
| Store_Name               | 门店名称                                                                 |
| Vip_Level                | 会员等级                                                                 |
| 是否有导                 | 是否有导购员（1-是，0-否）                                               |
| 是否院线店               | 是否院线门店（1-是，0-否）                                               |
| OrderNum                 | 订单号                                                                   |
| ID_CRMPlus               | CRMPlus 系统订单号或相关ID                                               |
| 新客订单                 | 是否为新客订单（1-是，0-否）                                             |
| 是否退单                 | 是否为退单（1-是，0-否）                                                 |
| 新客类型                 | 新客类型（如首单、回流等）                                               |
| 订单罐数                 | 订单包含的罐数                                                           |
| 退单罐数                 | 退货罐数                                                                 |
| 退单罐码                 | 退货罐体条码                                                             |
| OrderEntry               | 扫码标记。如扫码归巢，扫码销量，自然销量                                   |
| BU                       | 事业部（Business Unit）                                                  |
| ksfid                    | 业务系统ID                                                               |
| IsNewCustomer            | 是否新客户（1-是，0-否）                                                 |
| supervisor_number        | 督导编号                                                                 |
| Is_Spark                 | 是否为 SPARK 门店（1-是，0-否）                                          |
| ID                       | 主键ID                                                                   |
| Convert_2_Spark_Date     | 转为 SPARK 门店的日期                                                    |
| Store_Created_Date       | 门店创建日期                                                             |
| CreatedOn                | 订单创建时间                                                             |
| Ordered_ModifiedOn       | 订单修改时间                                                             |
| Return_Ordered_ModifiedOn| 退单修改时间                                                             |
| LastModifiedOn           | 最后修改时间                                                             |
| 购买日期                 | 实际购买日期                                                             |
| Price                    | 单价                                                                     |
