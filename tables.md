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
# [20250411_雀巢测试结果_天御Result_筛选Risk] 字段注释说明
本表记录了天御风险筛查结果的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| risk_level | 风险等级 |
| risk_type | 风险类型 |
| ksfid | KSFID |
| TYPE1 | 类型1 |
| TYPE2 | 类型2 |
| TYPE3 | 类型3 |
| TYPE4 | 类型4 |
| TYPE5 | 类型5 |
| TYPE6 | 类型6 |
| TYPE7 | 类型7 |
| TYPE8 | 类型8 |
| TYPE9 | 类型9 |
| TYPE10 | 类型10 |
| TYPE11 | 类型11 |

# [ACCESS_LOGS] 字段注释说明
本表记录了访问日志的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| Request | 请求内容 |
| Method | 请求方法 |
| Token | 访问令牌 |
| Payload | 请求负荷 |
| Response | 响应内容 |
| Status | 状态 |
| EnterDate | 进入日期 |
| ElapsedMilliseconds | 耗时（毫秒） |
| IP | IP地址 |
| CreateDate | 创建日期 |
| ID | ID |

# [ACCESS_LOGS_READ] 字段注释说明
本表记录了只读访问日志的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| Request | 请求内容 |
| Method | 请求方法 |
| Token | 访问令牌 |
| Payload | 请求负荷 |
| Response | 响应内容 |
| Status | 状态 |
| ElapsedMilliseconds | 耗时（毫秒） |
| CreateDate | 创建日期 |
| EnterDate | 进入日期 |
| IP | IP地址 |
| ID | ID |

# [ACCESS_TOKENS] 字段注释说明
本表记录了访问令牌的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 令牌ID |
| Token | 令牌 |
| SecurityKey | 安全密钥 |
| Company | 公司 |
| IsValid | 是否有效 |
| Type | 类型 |
| IP | IP地址 |
| CreatedDateTime | 创建时间 |
| ID | ID |

# [AL110_BoChu_MOT_TA] 字段注释说明
本表记录了AL110和铂初的目标受众（MOT TA）的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| AL110招募时间 | AL110产品招募时间 |
| TOC_AL110招募总量 | TOC渠道AL110产品招募总量 |
| 6M以下 | 6个月以下 |
| 6M及以上 | 6个月及以上 |
| 6M未领取样包 | 6个月以下未领取样包 |
| 6M且领取样包 | 6个月以下且领取样包 |
| 在D3之后 -6M且领取样包 | 在D3之后6个月以下且领取样包 |
| 在D3之前-6M且领取样包 | 在D3之前6个月以下且领取样包 |
| 在D3之前6M且领取样包且未购买IMF | 在D3之前6个月以下且领取样包且未购买IMF |
| 生成链接的人(43001) | 生成链接的人（MOT 43001） |
| 推送MOT的人(43001) | 推送MOT的人（MOT 43001） |
| 点了链接 | 是否点击链接 |
| 没点链接 | 是否未点击链接 |
| 生成43002的人 | 生成链接的人（MOT 43002） |
| 推送43002的人 | 推送MOT的人（MOT 43002） |
| 生成43003的人 | 生成链接的人（MOT 43003） |
| 推送43003的人 | 推送MOT的人（MOT 43003） |
| 生成43004的人 | 生成链接的人（MOT 43004） |
| 推送43004的人 | 推送MOT的人（MOT 43004） |
| 生成43005的人 | 生成链接的人（MOT 43005） |
| 推送43005的人 | 推送MOT的人（MOT 43005） |
| D3D4未点链接 | D3D4阶段未点击链接 |
| 不可转奶数 | 不可转奶数量 |
| 生成43006的人 | 生成链接的人（MOT 43006） |
| 推送43006的人 | 推送MOT的人（MOT 43006） |
| 生成43007的人 | 生成链接的人（MOT 43007） |
| 推送43007的人 | 推送MOT的人（MOT 43007） |
| 生成43008的人 | 生成链接的人（MOT 43008） |
| 推送43008的人 | 推送MOT的人（MOT 43008） |

# [App_Settings] 字段注释说明
本表记录了应用设置的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Code | 设置代码 |
| Value | 设置值 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Code | 设置代码 |

# [Azure_Healthy_Detection] 字段注释说明
本表记录了Azure健康检测的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 检测ID |
| Status | 状态 |
| Msg | 消息 |
| ElapsedMilliseconds | 耗时（毫秒） |
| CreatedOn | 创建时间 |
| ID | ID |

# [Birthday_Base] 字段注释说明
本表记录了生日相关的基本信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| current_stage | 当前阶段 |
| StageByCRM | CRM中的阶段 |
| 是否正在关注 | 是否正在关注公众号 |
| BabyBirthday | 宝宝生日 |
| Offset_Day | 距离生日天数 |
| CreatedOn | 创建时间 |

# [Birthday_BHRecruitment] 字段注释说明
本表记录了生日相关的铂护会员招募信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 铂护会员招募时间 | 铂护会员招募时间 |
| 铂护会员招募渠道 | 铂护会员招募渠道 |

# [Birthday_Binding] 字段注释说明
本表记录了生日相关的绑定信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| SNCCode | SNC编码 |
| UpDate | 更新日期 |

# [Birthday_BoChuS3S4_Purchase] 字段注释说明
本表记录了生日相关的铂初S3/S4产品购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 有无BCS3/S4产品购买 | 是否购买过铂初S3/S4产品 |
| BCS3/S4最近购买时间 | 铂初S3/S4产品最近购买时间 |

# [Birthday_Engage] 字段注释说明
本表记录了生日相关的用户互动信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| 最近Engage时间 | 最近互动时间 |
| 最近SC互动时间 | 最近与SNC互动时间 |
| 最近MC/BGT/OA互动时间 | 最近与MC/BGT/OA互动时间 |

# [Birthday_HARecruitment] 字段注释说明
本表记录了生日相关的启护会员招募信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 启护会员招募时间 | 启护会员招募时间 |
| 启护会员招募渠道 | 启护会员招募渠道 |
| 启护会员招募导购 | 启护会员招募导购 |
| 启护会员招募门店 | 启护会员招募门店 |

# [Birthday_Infomation] 字段注释说明
本表记录了生日相关的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| Openid | 用户微信Openid |
| StageByCRM | CRM中的阶段 |
| current_stage | 当前阶段 |
| Offset_Day | 距离生日天数 |
| BabyBirthday | 宝宝生日 |
| 是否正在关注 | 是否正在关注公众号 |
| 最近购买brand | 最近购买的品牌 |
| 最近购买stage | 最近购买的阶段 |
| 最近购买时间 | 最近购买时间 |
| 最近购买SKU | 最近购买的SKU |
| 最近购买罐数 | 最近购买的罐数 |
| 绑定导购 | 绑定的导购 |
| 绑定导购门店 | 绑定的导购门店 |
| 导购是否在职 | 导购是否在职 |
| 最近Engage时间 | 最近互动时间 |
| 最近MC/BGT/OA互动时间 | 最近与MC/BGT/OA互动时间 |
| 最近SC互动时间 | 最近与SNC互动时间 |
| 启护会员招募时间 | 启护会员招募时间 |
| 启护会员招募渠道 | 启护会员招募渠道 |
| 启护会员招募导购 | 启护会员招募导购 |
| 启护会员招募门店 | 启护会员招募门店 |
| 守护会员招募时间 | 守护会员招募时间 |
| 守护会员招募渠道 | 守护会员招募渠道 |
| 优护会员招募时间 | 优护会员招募时间 |
| 优护会员招募渠道 | 优护会员招募渠道 |
| 铂护会员招募渠道 | 铂护会员招募渠道 |
| 铂护会员招募时间 | 铂护会员招募时间 |
| 有无BCS3/S4产品购买 | 是否购买过铂初S3/S4产品 |
| BCS3/S4最近购买时间 | 铂初S3/S4产品最近购买时间 |
| 有无HAS3/S4产品购买 | 是否购买过启护S3/S4产品 |
| 有无PTS3/S4产品购买 | 是否购买过能恩S3/S4产品 |
| 有无HAS4产品购买 | 是否购买过启护S4产品 |
| 有无IMF购买记录 | 是否有婴幼儿配方奶粉购买记录 |
| IMF_NOPT_最近购买时间 | 非能恩产品最近购买时间 |
| 是否参加生日礼 | 是否参加生日礼活动 |
| 判断日期 | 判断日期 |

# [Birthday_Joined] 字段注释说明
本表记录了用户是否参加生日礼活动的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 是否参加生日礼 | 是否参加生日礼活动 |

# [Birthday_Recent_Buy_IMF_DATE] 字段注释说明
本表记录了生日相关的最近购买婴幼儿配方奶粉（IMF）日期信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| IMF最近购买时间 | 婴幼儿配方奶粉最近购买时间 |

# [Birthday_Recent_Buy_IMF_NOPT_DATE] 字段注释说明
本表记录了生日相关的最近购买非能恩产品（IMF_NOPT）日期信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| IMF_NOPT_最近购买时间 | 非能恩产品最近购买时间 |

# [Birthday_Recent_Purchse_Brand] 字段注释说明
本表记录了生日相关的最近购买品牌信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| 最近购买brand | 最近购买的品牌 |
| 最近购买stage | 最近购买的阶段 |
| 最近购买时间 | 最近购买时间 |
| 最近购买SKU | 最近购买的SKU |
| 最近购买罐数 | 最近购买的罐数 |

# [Birthday_RunTA_Set] 字段注释说明
本表记录了生日相关的目标受众（TA）运行设置。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| RunDate | 运行日期 |
| Tag | 标签 |

# [Birthday_S3S4_Purchase] 字段注释说明
本表记录了生日相关的S3/S4产品购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 有无HAS3/S4产品购买 | 是否购买过启护S3/S4产品 |
| 有无PTS3/S4产品购买 | 是否购买过能恩S3/S4产品 |
| 有无HAS4产品购买 | 是否购买过启护S4产品 |
| 有无IMF购买记录 | 是否有婴幼儿配方奶粉购买记录 |

# [Birthday_SHRecruitment] 字段注释说明
本表记录了生日相关的守护会员招募信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 守护会员招募时间 | 守护会员招募时间 |
| 守护会员招募渠道 | 守护会员招募渠道 |

# [Birthday_Slow20240514] 字段注释说明
本表记录了2024年5月14日生日慢相关的数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 记录ID |
| Openid | 用户微信Openid |
| Unionid | 用户微信Unionid |
| Member_Type | 会员类型 |
| SNC_Code | SNC编码 |
| Store_Number | 门店编号 |
| Touch_Point | 触点 |
| CreatedOn | 创建时间 |
| SentToCMTON | 发送至CMT时间 |
| Current_Stage | 当前阶段 |
| Offset_Day | 距离生日天数 |
| Birthday | 生日 |
| IsEngaged | 是否互动 |
| ha12_type | HA12类型 |

# [Birthday_SNC_OnJob] 字段注释说明
本表记录了生日相关的SNC在职信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| serial_number | 序列号 |
| store_number | 门店编号 |
| 导购是否在职 | 导购是否在职 |

# [Birthday_YHRecruitment] 字段注释说明
本表记录了生日相关的优护会员招募信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 优护会员招募时间 | 优护会员招募时间 |
| 优护会员招募渠道 | 优护会员招募渠道 |

# [BirthdayGift_StorageData] 字段注释说明
本表记录了生日礼物的存储数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| Openid | 用户微信Openid |
| current_stage | 当前阶段 |
| 绑定导购 | 绑定的导购 |
| 绑定导购门店 | 绑定的导购门店 |
| MemberType | 会员类型 |
| ha12_type | HA12类型 |
| Touch_Point | 触点 |
| Offset_Day | 距离生日天数 |
| BabyBirthday | 宝宝生日 |
| IsEngaged | 是否互动 |

# [BLHX_ActivityInfo] 字段注释说明
本表记录了BLHX活动信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | 活动ID |
| hd_no | 活动编号 |
| title | 活动标题 |
| type | 活动类型 |
| sdate | 开始日期 |
| edate | 结束日期 |
| gift_id | 礼品ID |
| gift_code | 礼品码 |
| gift_name | 礼品名称 |
| zg_title | 资格标题 |
| exp_type | 过期类型 |
| premium_share | 付费分享 |
| premium_first | 付费优先 |
| zm_share | 招募分享 |
| product_codes | 产品编码 |
| buy_num | 购买数量 |
| is_enable | 是否启用 |
| min_month | 最小月龄 |
| cdate | 创建日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| hd_no | 活动编号 |

# [BLHX_CouponsInfo] 字段注释说明
本表记录了BLHX优惠券信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 优惠券ID |
| unionid | 用户微信Unionid |
| mobile | 手机号码 |
| stime | 开始时间 |
| etime | 结束时间 |
| stores_list | 门店列表 |
| hd_no | 活动编号 |
| gift_code | 礼品码 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| UseDatetime | 使用时间 |
| ExpireDatetime | 过期时间 |
| Expire2OADatetime | OA过期时间 |
| HA_Xinke | 启护新客 |
| TeHu_Xinke | 特护新客 |
| type | 类型 |
| is_black | 是否黑名单 |
| unionid | 用户微信Unionid |
| hd_no | 活动编号 |

# [BoChuSampleTempTA] 字段注释说明
本表记录了铂初样品临时目标受众信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| TargetType | 目标类型 |
| GetSampleTime | 获取样品时间 |
| RecentBuyTime | 最近购买时间 |
| RecentBuyCount | 最近购买数量 |
| EmptyDate | 空罐日期 |
| FirstTriggerDate | 第一次触发日期 |
| SecondTriggerDate | 第二次触发日期 |

# [CRM_API_LOGS] 字段注释说明
本表记录了CRM API日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| Method | 请求方法 |
| Payload | 请求负荷 |
| Response | 响应内容 |
| CreateDate | 创建日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [CRM_Baby] 字段注释说明
本表记录了CRM中的宝宝信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| PBabyId | P端宝宝ID |
| CBabyId | C端宝宝ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| BabyName | 宝宝姓名 |
| Birthday | 生日 |
| Gender | 性别 |
| BirthOrder | 出生顺序 |
| BabyNum | 宝宝数量 |
| WeanedDate | 断奶日期 |
| CreatedOn | 创建时间 |
| CreatedBy | 创建人 |
| Frozen | 是否冻结 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_CallResult] 字段注释说明
本表记录了CRM外呼结果信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| KSFId | KSFID |
| CMamaId | C端妈妈ID |
| PMamaId | P端妈妈ID |
| Mobile1 | 手机号码1 |
| Mobile2 | 手机号码2 |
| BatchNumber | 批次号 |
| ImportStatus | 导入状态 |
| FaildReason | 失败原因 |
| IsSpotCheck | 是否抽查 |
| IsNewCustomer | 是否新客 |
| UpdateCustName | 更新客户姓名 |
| UpdatebrandName | 更新品牌名称 |
| UpdateBuyTime | 更新购买时间 |
| CallContent | 外呼内容 |
| CallUser | 外呼客服 |
| CallTime | 外呼时间 |
| UserBrand | 用户品牌 |
| ContinueBuy | 是否继续购买 |
| CallStatus | 外呼状态 |
| InvalidReason | 无效原因 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| CallResult | 外呼结果 |
| IsNameValid | 姓名是否有效 |
| IsBuy | 是否购买 |
| IsProductNameValid | 产品名称是否有效 |
| CurrentMomBrand | 当前妈妈品牌 |
| CurrentNicBrand | 当前NIC品牌 |
| CurrentS3NestleBrand | 当前S3雀巢品牌 |
| CurrentS3CompeteBrand | 当前S3竞品品牌 |
| CallRemark | 外呼备注 |
| OperationFlag | 操作标志 |
| BrandExperience | 品牌体验 |
| IsApprovalBrand | 是否认可品牌 |
| IsReceiveGift | 是否收到礼物 |
| NewCustomerType | 新客类型 |
| ReferrerPhone | 推荐人手机号 |
| GiftMechanism | 礼品机制 |
| IsRiskSurvey | 是否风险调研 |
| RiskSurveyDate | 风险调研日期 |
| AllergicFactors | 过敏因素 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_FAQ] 字段注释说明
本表记录了CRM中的常见问题（FAQ）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| ID | FAQ ID |
| InfoType | 信息类型 |
| Question | 问题 |
| Ans | 答案 |
| ParentId | 父ID |
| OrderID | 排序ID |
| AttName | 附件名称 |
| AttPath | 附件路径 |
| QueryAns | 查询答案 |
| OperationFlag | 操作标志 |
| txUser | 交易用户 |
| txDate | 交易日期 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_Inbound] 字段注释说明
本表记录了CRM呼入电话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| Id | 呼入ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| Name | 姓名 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| FilePath | 文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| Remark | 备注 |
| ContactSpecification | 联系规格 |
| CallCategory | 通话类别 |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| FeedType | 喂养方式 |
| ConsultPoint | 咨询要点 |
| ConsultContent | 咨询内容 |
| ReplyContent | 回复内容 |
| HotlineKnowWay | 热线知晓渠道 |
| ConsultDetail | 咨询详情 |
| TIMELONG | 通话时长 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| QuestionDetailJSON | 问题详情JSON |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_Inbound_DS] 字段注释说明
本表记录了CRM呼入电话（DS）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| Id | 呼入ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| Name | 姓名 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| FilePath | 文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| Remark | 备注 |
| ContactSpecification | 联系规格 |
| CallCategory | 通话类别 |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| FeedType | 喂养方式 |
| ConsultPoint | 咨询要点 |
| ConsultContent | 咨询内容 |
| ReplyContent | 回复内容 |
| HotlineKnowWay | 热线知晓渠道 |
| ConsultDetail | 咨询详情 |
| TIMELONG | 通话时长 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| QuestionDetailJSON | 问题详情JSON |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [CRM_Mama] 字段注释说明
本表记录了CRM中的妈妈信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| MamaName | 妈妈姓名 |
| Birthday | 生日 |
| Gender | 性别 |
| PostalCode | 邮政编码 |
| AddressHead | 地址头 |
| AddressTail | 地址尾 |
| JoinTime | 加入时间 |
| HomeTel |家庭电话 |
| OfficeTel | 办公电话 |
| OtherTel | 其他电话 |
| Mobile | 手机号码 |
| DefaultTelType | 默认电话类型 |
| HotelineKnowWay | 热线知晓渠道 |
| IsRefusedAll | 是否全部拒绝 |
| IsFollowedWechatCTM | 是否关注微信CTM |
| IsBandWechatCTM | 是否绑定微信CTM |
| IsAcceptedCall | 是否接受电话 |
| IsAcceptedMail | 是否接受邮件 |
| IsAcceptedEmail | 是否接受电子邮件 |
| IsAcceptedSMS | 是否接受短信 |
| Remark | 备注 |
| IsMember | 是否会员 |
| MemberCardNo | 会员卡号 |
| IdentityNumber | 身份证号 |
| Company | 公司 |
| Job | 工作 |
| CheccId | CheccID |
| CMTId | CMT ID |
| LogBatchId | 日志批次ID |
| WebUserId | 网站用户ID |
| WebDataSource | 网站数据源 |
| Email | 电子邮箱 |
| WechatNo | 微信号 |
| WeiboNo | 微博号 |
| RegisterMobile | 注册手机 |
| PregnantStatus | 怀孕状态 |
| HasAllergy | 是否过敏 |
| CMTKnowWay | CMT知晓渠道 |
| Interests | 兴趣 |
| IsPass | 是否通过 |
| NoPassReason | 未通过原因 |
| IsCMTCall | 是否CMT呼叫 |
| BabyEDC | 宝宝预产期 |
| IsCallCount | 是否计入呼叫次数 |
| ImportDate | 导入日期 |
| Frozen | 是否冻结 |
| SubscribeSource | 订阅来源 |
| SubscribeTime | 订阅时间 |
| RegisterChannel | 注册渠道 |
| OperationFlag | 操作标志 |
| CreatedOn | 创建时间 |
| CreatedBy | 创建人 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| ActivityChannel | 活动渠道 |
| CMT_ID | CMT ID |
| MamaNameFromSNC | 来自SNC的妈妈姓名 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Unionid | 用户微信Unionid |
| Comments | 评论 |
| PID | 主键ID |

# [CRM_Manufactor] 字段注释说明
本表记录了CRM中的制造商信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ManufactorID | 制造商ID |
| ManufactorName | 制造商名称 |
| UserType | 用户类型 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [CRM_Member] 字段注释说明
本表记录了CRM中的会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| MemberId | 会员ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| RegisterChannel | 注册渠道 |
| Status | 状态 |
| CreateUser | 创建用户 |
| CreateTime | 创建时间 |
| Remark | 备注 |
| SRCode | SR代码 |
| SRName | SR名称 |
| QRCode | 二维码 |
| MamaName | 妈妈姓名 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| StoreChannel | 门店渠道 |
| Region | 区域 |
| Province | 省份 |
| City | 城市 |
| CityGroup | 城市组 |
| JoinDate | 加入日期 |
| OperationFlag | 操作标志 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_Member_Profiles] 字段注释说明
本表记录了CRM中的会员详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| M_MOBILE | 手机号码 |
| M_PASSWORD | 密码 |
| M_IS_VAILD | 是否有效 |
| M_INVAILD_REASON | 无效原因 |
| M_CREATE_DATE | 创建日期 |
| M_UPDATE_DATE | 更新日期 |
| SUB_USER_EMAIL | 用户邮箱 |
| SUB_USER_NAME | 用户名 |
| SUB_USER_NICKNAME | 用户昵称 |
| SUB_USER_BIRTHDAY | 用户生日 |
| SUB_MEMBER_TYPE | 会员类型 |
| SUB_MEMBER_TYPE_OTHER | 其他会员类型 |
| SUB_PROVINCE | 省份 |
| SUB_CITY | 城市 |
| SUB_DISTRICT | 区/县 |
| SUB_ADDRESS | 地址 |
| SUB_ZIPCODE | 邮政编码 |
| SUB_PREGNANT_STATUS | 怀孕状态 |
| SUB_BABY_DUEDATE | 宝宝预产期 |
| SUB_BABY_BIRTHDAY | 宝宝生日 |
| SUB_BABY_NICKNAME | 宝宝昵称 |
| SUB_INTEREST_MILESTONE | 兴趣里程碑 |
| SUB_IS_RCV_SMS | 是否接收短信 |
| SUB_IS_RCV_MMS | 是否接收彩信 |
| SUB_IS_RCV_MAIL | 是否接收邮件 |
| SUB_IS_RCV_OTHER | 是否接收其他 |
| SUB_IS_ALLERGY | 是否过敏 |
| SUB_BABY_BRAND | 宝宝品牌 |
| SUB_FEEDING_PATTERNS | 喂养方式 |
| SOU_REG_URL | 注册URL |
| SOU_PREVIOUS_URL | 上一页URL |
| SOU_CONFERENCE_CODE | 会议代码 |
| SOU_TRACKING_CODE_06 | 追踪代码06 |
| SWD_DATA_SOURCE | 数据源 |
| WECHAT_BIND | 微信绑定 |
| WECHAT_BIND_FLAG | 微信绑定标志 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| SR_USER_NAME | SR用户名 |
| SR_STORE_CODE | SR门店代码 |
| SR_AREA | SR区域 |
| SR_PROVINCE | SR省份 |
| SR_CITY | SR城市 |
| SR_CODE | SR代码 |
| SR_CHANNEL | SR渠道 |
| SR_CITY_GROUP | SR城市组 |
| SR_STORE_NAME | SR门店名称 |
| CMT_ID | CMT ID |
| SR_QRCODE | SR二维码 |
| WECHAT_CARD_CODE | 微信卡券代码 |
| SUB_BABY_GENDER | 宝宝性别 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| M_TYPE | 类型 |
| CMT_UNIONID | CMT Unionid |
| Remark | 备注 |
| S_MOBILE | S端手机号 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Completed_Shouhu_Questionnaire1_Date | 完成守护问卷1日期 |
| Completed_Qihu_Questionnaire1_Date | 完成启护问卷1日期 |
| Completed_Youhu_Questionnaire1_Date | 完成优护问卷1日期 |
| Completed_Qihu_Questionnaire2_Date | 完成启护问卷2日期 |
| Completed_Youhu_Questionnaire2_Date | 完成优护问卷2日期 |
| Completed_Cmpa_Questionnaire_Date | 完成Cmpa问卷日期 |
| Completed_Info | 完成信息 |
| Completed_ARI | 完成ARI |
| Brand_Prospect | 品牌前景 |
| MS_GP_Tag | MS GP标签 |
| SYNC_TIME | 同步时间 |
| Last_SYNC_Time | 上次同步时间 |
| WECHAT_BIND_GB | 微信绑定GB |
| WECHAT_BIND_FLAG_GB | 微信绑定标志GB |
| WECHAT_BIND_CT | 微信绑定CT |
| Completed_Bohu_Questionnaire1_Date | 完成铂护问卷1日期 |
| Completed_Bohu_Questionnaire2_Date | 完成铂护问卷2日期 |
| Completed_Shuhu_Questionnaire1_Date | 完成舒护问卷1日期 |
| Vip_Level | 会员等级 |
| NHS_Unionid | NHS Unionid |
| PID | 主键ID |

# [CRM_MOT_Back] 字段注释说明
本表记录了CRM MOT（关键时刻）反馈信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Unionid | 用户微信Unionid |
| Recruit_Brand | 招募品牌 |
| SNCCode | SNC代码 |
| SNCName | SNC名称 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| Source | 来源 |
| CalSeqNo | 外呼序列号 |
| CsrCallTime | 客服外呼时间 |
| Tag_List | 标签列表 |
| Baby_Status | 宝宝状态 |
| Is_Chg_Milk | 是否转奶 |
| Is_Age_Confirm | 年龄是否确认 |
| Is_Activa_HCP | 是否激活HCP |
| Use_Sample | 使用样品 |
| Repurchase_Type | 复购类型 |
| Is_Valid | 是否有效 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| KSFID | KSFID |
| CalSeqNo | 外呼序列号 |

# [CRM_Outbound] 字段注释说明
本表记录了CRM外呼信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| Id | 外呼ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| CallingNumber | 主叫号码 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| CallDuration | 通话时长 |
| TapeFilePath | 录音文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| CallResult | 外呼结果 |
| IsNameValid | 姓名是否有效 |
| ModifiedName | 修改后的姓名 |
| IsBuy | 是否购买 |
| IsProductNameValid | 产品名称是否有效 |
| ModifiedProductName | 修改后的产品名称 |
| ModifiedBoughtTime | 修改后的购买时间 |
| CurrentMomBrand | 当前妈妈品牌 |
| Remark1 | 备注1 |
| CurrentNicBrand | 当前NIC品牌 |
| Remark2 | 备注2 |
| CurrentS3NestleBrand | 当前S3雀巢品牌 |
| Remark3 | 备注3 |
| CurrentS3CompeteBrand | 当前S3竞品品牌 |
| Remark4 | 备注4 |
| IsContinuedBuy | 是否继续购买 |
| CALLCONTENT | 外呼内容 |
| CALLREMARK | 外呼备注 |
| Campaignid | 活动ID |
| listid | 列表ID |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| BUSI_TYPE_TAG | 业务类型标签 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| ActivityChannel | 活动渠道 |
| EqualResult | 对比结果 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRM_Register] 字段注释说明
本表记录了CRM注册信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 注册ID |
| Openid | 用户微信Openid |
| Appid | 应用ID |
| CreatedOn | 创建时间 |
| ID | ID |

# [CRM_SurveyResult] 字段注释说明
本表记录了CRM调研结果信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 结果ID |
| SurveyResultID | 调研结果ID |
| CampaignId | 活动ID |
| MamaId | 妈妈ID |
| KsfId | KSFID |
| CallseqNo | 外呼序列号 |
| SurveyName | 调研名称 |
| OperationFlag | 操作标志 |
| SurveyDetailList | 调研详情列表 |
| PDateReceived | P端接收日期 |
| PDateProcessed | P端处理日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [CRM_WechatData] 字段注释说明
本表记录了CRM微信数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | 主键ID |
| ID | 数据ID |
| ProblemTagName | 问题标签名称 |
| WxOpenID | 微信OpenID |
| Category | 类别 |
| SubCategory | 子类别 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| OperationFlag | 操作标志 |
| PDateProcessed | P端处理日期 |
| PDateReceived | P端接收日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | 主键ID |

# [CRMPlus_API_LOG] 字段注释说明
本表记录了CRMPlus API日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | 日志ID |
| Request | 请求内容 |
| Method | 请求方法 |
| Payload | 请求负荷 |
| Response | 响应内容 |
| Status | 状态 |
| PushAgainDate | 再次推送日期 |
| OriginId | 原始ID |
| CreatedOn | 创建时间 |
| ElapsedMilliseconds | 耗时（毫秒） |
| Id | ID |

# [CRMPlus_Order] 字段注释说明
本表记录了CRMPlus中的订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 订单ID |
| OrderNum | 订单号 |
| PgNum | PG数量 |
| PgName | PG名称 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| Openid | 用户微信Openid |
| OrderMobile | 订单手机 |
| UserId | 用户ID |
| OrderCreateTime | 订单创建时间 |
| OrderModifyTime | 订单修改时间 |
| TankBarcode | 罐条码 |
| BoxBarcode | 箱条码 |
| ReturnTankBarcode | 退货罐条码 |
| ReturnCount | 退货数量 |
| PurchaseStatus | 购买状态 |
| QRCodeLink | 二维码链接 |
| OperationFlag | 操作标志 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| OrderEntry | 订单入口 |
| Recordstatus | 记录状态 |
| Channel | 渠道 |
| S_MOBILE | S端手机号 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| TouchPoint | 触点 |
| Unionid | 用户微信Unionid |
| BU | 业务单元 |
| Vip_Level | 会员等级 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| BabyBirthday | 宝宝生日 |
| TNRS | TNRS |
| IsShareOrder | 是否分享订单 |
| Tcds_Id | TCDS ID |
| ID | ID |

# [CRMPlus_Order_ProductCode] 字段注释说明
本表记录了CRMPlus中的订单产品代码信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| OrderNum | 订单号 |
| ProductCode | 产品代码 |
| Type | 类型 |
| Count | 数量 |
| TankBarcode | 罐条码 |
| BoxBarcode | 箱条码 |
| OrdeModifiedTime | 订单修改时间 |
| Price | 价格 |
| TotalPrice | 总价 |
| PurchaseStatus | 购买状态 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID_CRMPlus | CRMPlus ID |
| LastChange | 最后更改时间 |
| CampaignId | 活动ID |
| NewCustomterType | 新客户类型 |
| OrderCreateTime | 订单创建时间 |
| ID | ID |

# [DATA_Baby] 字段注释说明
本表记录了宝宝的数据信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PBabyId | P端宝宝ID |
| CBabyId | C端宝宝ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| BabyName | 宝宝姓名 |
| Birthday | 生日 |
| Gender | 性别 |
| BirthOrder | 出生顺序 |
| BabyNum | 宝宝数量 |
| WeanedDate | 断奶日期 |
| CreatedOn | 创建时间 |
| CreatedBy | 创建人 |
| Frozen | 是否冻结 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| IsSentToCRM | 是否已发送至CRM |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PBabyId | P端宝宝ID |

# [DATA_CallTypeList] 字段注释说明
本表记录了通话类型列表数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| InboundID | 呼入ID |
| CallType1 | 通话类型1 |
| CallType2 | 通话类型2 |
| CallType3 | 通话类型3 |
| CallType4 | 通话类型4 |
| CallType5 | 通话类型5 |
| CallType6 | 通话类型6 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Id | ID |

# [DATA_Campaign_Activity] 字段注释说明
本表记录了活动数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| CampaignId | 活动ID |
| CampaignName | 活动名称 |
| CampaignType | 活动类型 |
| Channel | 渠道 |
| GiftCode | 礼品码 |
| BuyDate | 购买日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Remark | 备注 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Mobile | 手机号码 |
| CampaignId | 活动ID |

# [DATA_Campaign_Activity_2022] 字段注释说明
本表记录了2022年活动数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | 用户微信Openid |
| Mobile | 手机号码 |
| CampaignId | 活动ID |
| Sequence | 序列 |
| Channel | 渠道 |
| TouchPoint | 触点 |
| GiftCode | 礼品码 |
| BuyDate | 购买日期 |
| OrderId | 订单ID |
| SNCCode | SNC代码 |
| StoreID | 门店ID |
| IsValid | 是否有效 |
| Completed_Questionnaire_2_Date | 完成问卷2日期 |
| Remark | 备注 |
| BuyDate_2 | 第二次购买日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| BU | 业务单元 |
| Unionid | 用户微信Unionid |
| Resume_Qualification | 恢复资格 |
| ID_CRMPlus | CRMPlus ID |
| Vip_Level | 会员等级 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| Tcds_Id | TCDS ID |
| Unionid | 用户微信Unionid |
| CampaignId | 活动ID |
| Sequence | 序列 |

# [DATA_Campaign_Activity_2022_250314] 字段注释说明
本表记录了2022年3月14日的活动数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | 用户微信Openid |
| Mobile | 手机号码 |
| CampaignId | 活动ID |
| Sequence | 序列 |
| Channel | 渠道 |
| TouchPoint | 触点 |
| GiftCode | 礼品码 |
| BuyDate | 购买日期 |
| OrderId | 订单ID |
| SNCCode | SNC代码 |
| StoreID | 门店ID |
| IsValid | 是否有效 |
| Completed_Questionnaire_2_Date | 完成问卷2日期 |
| Remark | 备注 |
| BuyDate_2 | 第二次购买日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| BU | 业务单元 |
| Unionid | 用户微信Unionid |
| Resume_Qualification | 恢复资格 |
| ID_CRMPlus | CRMPlus ID |
| Vip_Level | 会员等级 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| Tcds_Id | TCDS ID |

# [DATA_Campaign_Activity_2022_Log] 字段注释说明
本表记录了2022年活动日志数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| S_Mobile | S端手机号 |
| QiHu_2_Qualification | 启护2次资格 |
| Youhu_2_Qualification | 优护2次资格 |
| CreateOn | 创建时间 |
| ID | ID |

# [DATA_Campaign_Period] 字段注释说明
本表记录了活动周期数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CampaignID | 活动ID |
| CampaignType | 活动类型 |
| CampaignName | 活动名称 |
| GiftCodeList | 礼品码列表 |
| Sequence | 序列 |
| Brand | 品牌 |
| Remark | 备注 |
| PeriodStart | 周期开始 |
| PeriodEnd | 周期结束 |
| CreatedOn | 创建时间 |
| LastChange | 最后更改时间 |
| Is_Spark | 是否Spark |
| MetCompliance | 符合合规 |
| MetCompliance_Stage_3 | 符合合规（阶段3） |
| Is_blhx | 是否blhx |
| CampaignID | 活动ID |

# [DATA_Campaign_Period_20240629] 字段注释说明
本表记录了2024年6月29日的活动周期数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CampaignID | 活动ID |
| CampaignType | 活动类型 |
| CampaignName | 活动名称 |
| GiftCodeList | 礼品码列表 |
| Sequence | 序列 |
| Brand | 品牌 |
| Remark | 备注 |
| PeriodStart | 周期开始 |
| PeriodEnd | 周期结束 |
| CreatedOn | 创建时间 |
| LastChange | 最后更改时间 |
| Is_Spark | 是否Spark |
| MetCompliance | 符合合规 |
| MetCompliance_Stage_3 | 符合合规（阶段3） |

# [DATA_Channel] 字段注释说明
本表记录了渠道数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Channel | 渠道 |
| Source | 来源 |
| Methed | 方法 |
| Keyword | 关键词 |
| IsOnline | 是否线上 |
| Remark | 备注 |

# [DATA_Chat] 字段注释说明
本表记录了聊天数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| chatId | 聊天ID |
| joinTime | 加入时间 |
| openid | 用户微信Openid |
| csrCode | 客服代码 |
| csrName | 客服姓名 |
| status | 状态 |
| msgNum | 消息数量 |
| createTime | 创建时间 |
| finishTime | 结束时间 |
| msgTagNum | 消息标签数量 |
| satisfactionVal | 满意度值 |
| isSendMaterial | 是否发送材料 |
| chatCloseType | 聊天关闭类型 |
| chatMsgData | 聊天消息数据 |
| createdOn | 创建时间 |
| operationFlag | 操作标志 |
| modifiedOn | 修改时间 |
| sentToCRMOn | 发送至CRM时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| storeNumber | 门店编号 |
| customerType | 客户类型 |
| distNumber | 分销商编号 |
| chatId | 聊天ID |

# [DATA_ChatMsg] 字段注释说明
本表记录了聊天消息数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| chatMsgId | 聊天消息ID |
| chatId | 聊天ID |
| status | 状态 |
| openid | 用户微信Openid |
| addTimestamp | 添加时间戳 |
| useType | 使用类型 |
| wxPicUrl | 微信图片URL |
| replyStatus | 回复状态 |
| userAnswerDiff | 用户回答差异 |
| problemTagNames | 问题标签名称 |
| remind | 提醒 |
| csrCode | 客服代码 |
| content | 内容 |
| newsId | 新闻ID |
| csrReplyDiff | 客服回复差异 |
| problemTagIds | 问题标签ID |
| msgType | 消息类型 |
| addTime | 添加时间 |
| createdOn | 创建时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| chatMsgId | 聊天消息ID |

# [DATA_Dictionary] 字段注释说明
本表记录了数据字典信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | 名称 |
| parent_id | 父ID |
| type | 类型 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [DATA_Inbound] 字段注释说明
本表记录了呼入数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| Name | 姓名 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| FilePath | 文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| Remark | 备注 |
| ContactSpecification | 联系规格 |
| CallCategory | 通话类别 |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| FeedType | 喂养方式 |
| ConsultPoint | 咨询要点 |
| ConsultContent | 咨询内容 |
| ReplyContent | 回复内容 |
| HotlineKnowWay | 热线知晓渠道 |
| ConsultDetail | 咨询详情 |
| TIMELONG | 通话时长 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| QuestionDetailJSON | 问题详情JSON |
| IsSentToCRM | 是否已发送至CRM |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Id | ID |

# [DATA_Mama] 字段注释说明
本表记录了妈妈的数据信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| MamaName | 妈妈姓名 |
| Birthday | 生日 |
| Gender | 性别 |
| PostalCode | 邮政编码 |
| AddressHead | 地址头 |
| AddressTail | 地址尾 |
| JoinTime | 加入时间 |
| HomeTel | 家庭电话 |
| OfficeTel | 办公电话 |
| OtherTel | 其他电话 |
| Mobile | 手机号码 |
| DefaultTelType | 默认电话类型 |
| HotelineKnowWay | 热线知晓渠道 |
| IsRefusedAll | 是否全部拒绝 |
| IsFollowedWechatCTM | 是否关注微信CTM |
| IsBandWechatCTM | 是否绑定微信CTM |
| IsAcceptedCall | 是否接受电话 |
| IsAcceptedMail | 是否接受邮件 |
| IsAcceptedEmail | 是否接受电子邮件 |
| IsAcceptedSMS | 是否接受短信 |
| Remark | 备注 |
| IsMember | 是否会员 |
| MemberCardNo | 会员卡号 |
| IdentityNumber | 身份证号 |
| Company | 公司 |
| Job | 工作 |
| CheccId | CheccID |
| CMTId | CMT ID |
| LogBatchId | 日志批次ID |
| WebUserId | 网站用户ID |
| WebDataSource | 网站数据源 |
| Email | 电子邮箱 |
| WechatNo | 微信号 |
| WeiboNo | 微博号 |
| RegisterMobile | 注册手机 |
| PregnantStatus | 怀孕状态 |
| HasAllergy | 是否过敏 |
| CMTKnowWay | CMT知晓渠道 |
| Interests | 兴趣 |
| IsPass | 是否通过 |
| NoPassReason | 未通过原因 |
| IsCMTCall | 是否CMT呼叫 |
| BabyEDC | 宝宝预产期 |
| IsCallCount | 是否计入呼叫次数 |
| ImportDate | 导入日期 |
| Frozen | 是否冻结 |
| SubscribeSource | 订阅来源 |
| SubscribeTime | 订阅时间 |
| RegisterChannel | 注册渠道 |
| OperationFlag | 操作标志 |
| CreatedOn | 创建时间 |
| CreatedBy | 创建人 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| IsSentToCRM | 是否已发送至CRM |
| ActivityChannel | 活动渠道 |
| CMT_ID | CMT ID |
| MamaNameFromSNC | 来自SNC的妈妈姓名 |
| S_MOBILE | S端手机号 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Unionid | 用户微信Unionid |
| PMamaId | P端妈妈ID |

# [DATA_Member] 字段注释说明
本表记录了会员数据信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MemberId | 会员ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| RegisterChannel | 注册渠道 |
| Status | 状态 |
| CreateUser | 创建用户 |
| CreateTime | 创建时间 |
| Remark | 备注 |
| SRCode | SR代码 |
| SRName | SR名称 |
| QRCode | 二维码 |
| MamaName | 妈妈姓名 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| StoreChannel | 门店渠道 |
| Region | 区域 |
| Province | 省份 |
| City | 城市 |
| CityGroup | 城市组 |
| JoinDate | 加入日期 |
| OperationFlag | 操作标志 |
| IsBUChecked | BU是否已检查 |
| ModifiedOn | 修改时间 |
| ActivityChannel | 活动渠道 |
| IsSentToCRM | 是否已发送至CRM |
| CreatedOn | 创建时间 |
| SentToCRMOn | 发送至CRM时间 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [DATA_Member_Channel] 字段注释说明
本表记录了会员渠道数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| smt_mp | SMT MP |
| smt_md | SMT MD |
| swd_channel_reg_typ | SWD渠道注册类型 |
| tags | 标签 |
| smt_class | SMT分类 |
| is_zhu | 是否主要 |
| smt_sub_class | SMT子分类 |
| updatetime | 更新时间 |
| modifiedOn | 修改时间 |

# [DATA_Member_Profiles] 字段注释说明
本表记录了会员详细数据信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CMT_ID | CMT ID |
| M_MOBILE | 手机号码 |
| M_PASSWORD | 密码 |
| M_IS_VAILD | 是否有效 |
| M_INVAILD_REASON | 无效原因 |
| M_CREATE_DATE | 创建日期 |
| M_UPDATE_DATE | 更新日期 |
| SUB_USER_EMAIL | 用户邮箱 |
| SUB_USER_NAME | 用户名 |
| SUB_USER_NICKNAME | 用户昵称 |
| SUB_USER_BIRTHDAY | 用户生日 |
| SUB_MEMBER_TYPE | 会员类型 |
| SUB_MEMBER_TYPE_OTHER | 其他会员类型 |
| SUB_PROVINCE | 省份 |
| SUB_CITY | 城市 |
| SUB_DISTRICT | 区/县 |
| SUB_ADDRESS | 地址 |
| SUB_ZIPCODE | 邮政编码 |
| SUB_PREGNANT_STATUS | 怀孕状态 |
| SUB_BABY_DUEDATE | 宝宝预产期 |
| SUB_BABY_BIRTHDAY | 宝宝生日 |
| SUB_BABY_NICKNAME | 宝宝昵称 |
| SUB_INTEREST_MILESTONE | 兴趣里程碑 |
| SUB_IS_RCV_SMS | 是否接收短信 |
| SUB_IS_RCV_MMS | 是否接收彩信 |
| SUB_IS_RCV_MAIL | 是否接收邮件 |
| SUB_IS_RCV_OTHER | 是否接收其他 |
| SUB_IS_ALLERGY | 是否过敏 |
| SUB_BABY_BRAND | 宝宝品牌 |
| SUB_FEEDING_PATTERNS | 喂养方式 |
| SOU_REG_URL | 注册URL |
| SOU_PREVIOUS_URL | 上一页URL |
| SOU_CONFERENCE_CODE | 会议代码 |
| SOU_TRACKING_CODE_06 | 追踪代码06 |
| SWD_DATA_SOURCE | 数据源 |
| WECHAT_BIND | 微信绑定 |
| WECHAT_BIND_FLAG | 微信绑定标志 |
| WECHAT_CARD_CODE | 微信卡券代码 |
| SR_QRCODE | SR二维码 |
| SR_USER_NAME | SR用户名 |
| SR_STORE_CODE | SR门店代码 |
| SR_AREA | SR区域 |
| SR_PROVINCE | SR省份 |
| SR_CITY | SR城市 |
| SR_CODE | SR代码 |
| SR_CHANNEL | SR渠道 |
| SR_CITY_GROUP | SR城市组 |
| SR_STORE_NAME | SR门店名称 |
| SYNC_TIME | 同步时间 |
| ModifiedOn | 修改时间 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| M_TYPE | 类型 |
| CMT_UNIONID | CMT Unionid |
| Remark | 备注 |
| S_MOBILE | S端手机号 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Vip_Level | 会员等级 |
| NHS_Unionid | NHS Unionid |
| CMT_ID | CMT ID |

# [DATA_Outbound] 字段注释说明
本表记录了外呼数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| CallingNumber | 主叫号码 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| CallDuration | 通话时长 |
| TapeFilePath | 录音文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| CallResult | 外呼结果 |
| IsNameValid | 姓名是否有效 |
| ModifiedName | 修改后的姓名 |
| IsBuy | 是否购买 |
| IsProductNameValid | 产品名称是否有效 |
| ModifiedProductName | 修改后的产品名称 |
| ModifiedBoughtTime | 修改后的购买时间 |
| CurrentMomBrand | 当前妈妈品牌 |
| Remark1 | 备注1 |
| CurrentNicBrand | 当前NIC品牌 |
| Remark2 | 备注2 |
| CurrentS3NestleBrand | 当前S3雀巢品牌 |
| Remark3 | 备注3 |
| CurrentS3CompeteBrand | 当前S3竞品品牌 |
| Remark4 | 备注4 |
| IsContinuedBuy | 是否继续购买 |
| CALLCONTENT | 外呼内容 |
| CALLREMARK | 外呼备注 |
| Campaignid | 活动ID |
| listid | 列表ID |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| BUSI_TYPE_TAG | 业务类型标签 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| ActivityChannel | 活动渠道 |
| IsSentToCRM | 是否已发送至CRM |
| EqualResult | 对比结果 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Id | ID |

# [DATA_Outbound_20250307] 字段注释说明
本表记录了2025年3月7日的外呼数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
| KSFId | KSFID |
| CallingNumber | 主叫号码 |
| CalledNumber | 被叫号码 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| CallDuration | 通话时长 |
| TapeFilePath | 录音文件路径 |
| CallId | 通话ID |
| CSRCode | 客服代码 |
| CSRName | 客服姓名 |
| CallResult | 外呼结果 |
| IsNameValid | 姓名是否有效 |
| ModifiedName | 修改后的姓名 |
| IsBuy | 是否购买 |
| IsProductNameValid | 产品名称是否有效 |
| ModifiedProductName | 修改后的产品名称 |
| ModifiedBoughtTime | 修改后的购买时间 |
| CurrentMomBrand | 当前妈妈品牌 |
| Remark1 | 备注1 |
| CurrentNicBrand | 当前NIC品牌 |
| Remark2 | 备注2 |
| CurrentS3NestleBrand | 当前S3雀巢品牌 |
| Remark3 | 备注3 |
| CurrentS3CompeteBrand | 当前S3竞品品牌 |
| Remark4 | 备注4 |
| IsContinuedBuy | 是否继续购买 |
| CALLCONTENT | 外呼内容 |
| CALLREMARK | 外呼备注 |
| Campaignid | 活动ID |
| listid | 列表ID |
| CallType | 通话类型 |
| MomBrandId | 妈妈品牌ID |
| MomProductId | 妈妈产品ID |
| NicBrandId | NIC品牌ID |
| NicProductId | NIC产品ID |
| BabyBrandId | 宝宝品牌ID |
| BabyProductId | 宝宝产品ID |
| BUSI_TYPE_TAG | 业务类型标签 |
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| ActivityChannel | 活动渠道 |
| IsSentToCRM | 是否已发送至CRM |
| EqualResult | 对比结果 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [DATA_RiskSurvey] 字段注释说明
本表记录了风险调研数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| openid | 用户微信Openid |
| mobile | 手机号码 |
| question | 问题 |
| answer1 | 答案1 |
| answer2 | 答案2 |
| answer3 | 答案3 |
| answer4 | 答案4 |
| answer5 | 答案5 |
| answer6 | 答案6 |
| answer7 | 答案7 |
| answer8 | 答案8 |
| answer9 | 答案9 |
| answer10 | 答案10 |
| level | 等级 |
| label | 标签 |
| label_count | 标签计数 |
| create_time | 创建时间 |
| CreatedOn | 创建时间 |
| SentCRMOn | 发送至CRM时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [DATA_Routin_Birthday_Daily] 字段注释说明
本表记录了日常生日提醒数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | 用户微信Openid |
| Unionid | 用户微信Unionid |
| Member_Type | 会员类型 |
| SNC_Code | SNC代码 |
| Store_Number | 门店编号 |
| Touch_Point | 触点 |
| CreatedOn | 创建时间 |
| SentToCMTON | 发送至CMT时间 |
| Current_Stage | 当前阶段 |
| Offset_Day | 距离生日天数 |
| Birthday | 生日 |
| IsEngaged | 是否互动 |
| ha12_type | HA12类型 |
| ID | ID |

# [DATA_Routin_Birthday_Daily_BT] 字段注释说明
本表记录了日常生日提醒数据（BT）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | 用户微信Openid |
| Unionid | 用户微信Unionid |
| Member_Type | 会员类型 |
| SNC_Code | SNC代码 |
| Store_Number | 门店编号 |
| Touch_Point | 触点 |
| CreatedOn | 创建时间 |
| SentToCMTON | 发送至CMT时间 |
| Current_Stage | 当前阶段 |
| Offset_Day | 距离生日天数 |
| Birthday | 生日 |
| IsEngaged | 是否互动 |
| ha12_type | HA12类型 |

# [DATA_Routin_Birthday_Daily_Engage] 字段注释说明
本表记录了日常生日提醒互动数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| Engage_times | 互动次数 |

# [DATA_SurveyDetailList] 字段注释说明
本表记录了调研详情列表数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SurveyResultID | 调研结果ID |
| QuestionCode | 问题代码 |
| QuestionName | 问题名称 |
| OptionName | 选项名称 |
| Remark | 备注 |
| itemText | 项目文本 |
| CreatedOn | 创建时间 |
| PDateProcessed | P端处理日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [DATA_SurveyResult] 字段注释说明
本表记录了调研结果数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| SurveyResultID | 调研结果ID |
| CampaignId | 活动ID |
| MamaId | 妈妈ID |
| KsfId | KSFID |
| CallseqNo | 外呼序列号 |
| SurveyName | 调研名称 |
| OperationFlag | 操作标志 |
| SurveyDetailList | 调研详情列表 |
| Q1 | 问题1 |
| Q2 | 问题2 |
| Q3 | 问题3 |
| Q4 | 问题4 |
| Q5 | 问题5 |
| Q6 | 问题6 |
| Q7 | 问题7 |
| A1 | 答案1 |
| A2 | 答案2 |
| A3 | 答案3 |
| A4 | 答案4 |
| A5 | 答案5 |
| A6 | 答案6 |
| A7 | 答案7 |
| CreatedOn | 创建时间 |
| Q8 | 问题8 |
| A8 | 答案8 |
| LastChange | 最后更改时间 |
| Q9 | 问题9 |
| A9 | 答案9 |
| Q10 | 问题10 |
| A10 | 答案10 |
| Q11 | 问题11 |
| A11 | 答案11 |
| Q12 | 问题12 |
| A12 | 答案12 |
| Sub_A1 | 子答案1 |
| Sub_A2 | 子答案2 |
| Sub_A3 | 子答案3 |
| Sub_A4 | 子答案4 |
| Sub_A5 | 子答案5 |
| Sub_A6 | 子答案6 |
| Sub_A7 | 子答案7 |
| Sub_A8 | 子答案8 |
| Sub_A9 | 子答案9 |
| Sub_A10 | 子答案10 |
| Sub_A11 | 子答案11 |
| Sub_A12 | 子答案12 |
| SurveyResultID | 调研结果ID |

# [DATA_Tuwen] 字段注释说明
本表记录了图文数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| wxArticleId | 微信文章ID |
| title | 标题 |
| titleUrl | 标题URL |
| outLine | 大纲 |
| content | 内容 |
| formatType | 格式类型 |
| formatTypeForm | 格式类型表单 |
| formatUrl | 格式URL |
| formatBaiduUrl | 格式百度URL |
| readCount | 阅读计数 |
| downloadCount | 下载计数 |
| forwardCount | 转发计数 |
| commentCount | 评论计数 |
| createTime | 创建时间 |
| updateTime | 更新时间 |
| status | 状态 |
| brandId | 品牌ID |
| brandTypeId | 品牌类型ID |
| jpgUrl | JPG图片URL |
| pngUrl | PNG图片URL |
| userId | 用户ID |
| fileSize | 文件大小 |
| seeFlag | 查看标志 |
| attachId | 附件ID |
| thumbUrl | 缩略图URL |
| author | 作者 |
| digest | 摘要 |
| url | URL |
| showCoverPic | 显示封面图片 |
| contentSourceUrl | 内容源URL |
| displayorder | 显示顺序 |
| orderTop | 置顶 |
| collection | 收藏 |
| createdOn | 创建时间 |
| pullMonth | 拉取月份 |
| id | ID |
| pullMonth | 拉取月份 |

# [DATA_WechatData] 字段注释说明
本表记录了微信数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ProblemTagName | 问题标签名称 |
| WxOpenID | 微信OpenID |
| Category | 类别 |
| SubCategory | 子类别 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| OperationFlag | 操作标志 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [DATA_YGYM] 字段注释说明
本表记录了YGYM数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Openid | 用户微信Openid |
| Unionid | 用户微信Unionid |
| S_MOBILE | S端手机号 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ScanTime | 扫描时间 |
| NewCustomerType | 新客户类型 |
| Createdon | 创建时间 |
| ModifiedOn | 修改时间 |
| Id | ID |

# [Dave_Log] 字段注释说明
本表记录了Dave的日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| Name | 名称 |
| Message | 消息 |
| CreatedOn | 创建时间 |
| ID | ID |

# [DDL_LOG] 字段注释说明
本表记录了DDL（数据定义语言）日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| PostTime | 发布时间 |
| DatabaseName | 数据库名称 |
| DB_User | 数据库用户 |
| Event | 事件 |
| LoginName | 登录名 |
| TSQL | TSQL语句 |
| LastChange_Azure | Azure端最后更改时间 |
| ComputerName | 计算机名 |
| ID | ID |

# [DTC_EDMS_Store] 字段注释说明
本表记录了DTC EDMS门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletName | 网点名称 |
| 新大区 | 新大区 |
| 团队 | 团队 |
| 省份 | 省份 |
| 城市 | 城市 |
| HCI名称 | HCI名称 |
| 备注 | 备注 |
| 是否DMS建店 | 是否DMS建店 |
| OutletCode | 网点代码 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| OutletName | 网点名称 |

# [DTC_YOUZAN_Buyer_Info] 字段注释说明
本表记录了DTC有赞买家信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| yz_open_id | 有赞open_id |
| outer_user_id | 外部用户ID |
| buyer_phone | 买家手机 |
| fans_type | 粉丝类型 |
| fans_nickname | 粉丝昵称 |
| fans_id | 粉丝ID |
| s_mobile | S端手机号 |
| CreatedOn | 创建时间 |
| yz_open_id | 有赞open_id |

# [DTC_YOUZAN_Orders] 字段注释说明
本表记录了DTC有赞订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| oid | 订单ID |
| tid | 交易ID |
| outer_item_id | 外部商品ID |
| item_type | 商品类型 |
| discount_price | 折扣价 |
| num | 数量 |
| goods_snapshot | 商品快照 |
| title | 标题 |
| fenxiao_payment | 分销支付 |
| item_id | 商品ID |
| item_no | 商品编号 |
| is_present | 是否赠品 |
| price | 价格 |
| sub_order_no | 子订单号 |
| total_fee | 总费用 |
| fenxiao_price | 分销价 |
| alias | 别名 |
| payment | 支付金额 |
| item_barcode | 商品条码 |
| outer_sku_id | 外部SKU ID |
| goods_url | 商品URL |
| points_price | 积分价格 |
| sku_barcode | SKU条码 |
| sku_no | SKU编号 |
| sku_properties_name | SKU属性名称 |
| s_mobile | S端手机号 |
| newcustomer_type | 新客户类型 |
| is_newcustomer | 是否新客户 |
| dcps | DCPS |
| kdt_id | KDT ID |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| oid | 订单ID |

# [DTC_YOUZAN_Orders_Info] 字段注释说明
本表记录了DTC有赞订单详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tid | 交易ID |
| created | 创建时间 |
| expired_time | 过期时间 |
| status_str | 状态字符串 |
| success_time | 成功时间 |
| type | 类型 |
| kdt_id | KDT ID |
| kdt_name | KDT名称 |
| confirm_time | 确认时间 |
| pay_time | 支付时间 |
| update_time | 更新时间 |
| is_retail_order | 是否零售订单 |
| pay_type | 支付类型 |
| team_type | 团队类型 |
| refund_state | 退款状态 |
| close_type | 关闭类型 |
| status | 状态 |
| express_type | 快递类型 |
| buyer_phone | 买家手机 |
| yz_open_id | 有赞open_id |
| fans_id | 粉丝ID |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| tid | 交易ID |

# [DTC_YOUZAN_pay_info] 字段注释说明
本表记录了DTC有赞支付信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |

# [DTC_YOUZAN_Push_Order] 字段注释说明
本表记录了DTC有赞推送订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| oid | 订单ID |
| tid | 交易ID |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
| product_name | 产品名称 |
| newcustomer_type | 新客户类型 |
| isnewcustomer | 是否新客户 |
| store_number | 门店编号 |
| ps_name | PS名称 |
| dcps | DCPS |
| nestle_product_code | 雀巢产品代码 |
| item_id | 商品ID |
| item_no | 商品编号 |
| kdt_id | KDT ID |
| kdt_name | KDT名称 |
| create_time | 创建时间 |
| created_on | 创建于 |
| modified_on | 修改于 |
| oid | 订单ID |

# [DTC_YOUZAN_PushMSG_Log] 字段注释说明
本表记录了DTC有赞推送消息日志。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pid | PID |
| payload | 有效负载 |
| msg | 消息 |
| kdt_name | KDT名称 |
| test | 测试 |
| sign | 签名 |
| type | 类型 |
| sendCount | 发送计数 |
| version | 版本 |
| client_id | 客户端ID |
| mode | 模式 |
| kdt_id | KDT ID |
| id | ID |
| msg_id | 消息ID |
| root_kdt_id | 根KDT ID |
| status | 状态 |
| createdon | 创建于 |
| pid | PID |

# [DTC_YOUZAN_Store] 字段注释说明
本表记录了DTC有赞店铺信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| 店铺名称 | 店铺名称 |
| 店铺编号 | 店铺编号 |
| 店铺有效期 | 店铺有效期 |
| 店铺状态 | 店铺状态 |
| 授权状态 | 授权状态 |
| CreatedOn | 创建时间 |
| Id | ID |

# [EC_JD_Brand_Upload] 字段注释说明
本表记录了EC京东品牌上传信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| offline_user_id | 线下用户ID |
| customer_id | 客户ID |
| brand_encode_phone | 品牌加密手机号 |
| level | 等级 |
| bind_time | 绑定时间 |
| is_mapping | 是否映射 |
| created | 创建时间 |
| modified | 修改时间 |
| id | ID |

# [EC_JD_ID_Mapping] 字段注释说明
本表记录了EC京东ID映射信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| S_Mobile | S端手机号 |
| JD_Mobile | 京东手机号 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Sent2JDOn | 发送至京东时间 |
| TM_MegaNAN_Mobile | 天猫MegaNAN手机号 |
| S_Mobile | S端手机号 |

# [EC_JD_Member] 字段注释说明
本表记录了EC京东会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| activityId | 活动ID |
| venderId | 商家ID |
| pin | PIN码 |
| channel | 渠道 |
| josEncPin | JOS加密PIN |
| phoneNo | 手机号 |
| babyBirthday | 宝宝生日 |
| sex | 性别 |
| nickname | 昵称 |
| factor1 | 因素1 |
| factor2 | 因素2 |
| initialLevel | 初始等级 |
| initialJdLevel | 初始京东等级 |
| level | 等级 |
| levelUpdateTime | 等级更新时间 |
| point | 积分 |
| pointUpdateTime | 积分更新时间 |
| result | 结果 |
| message | 消息 |
| extend | 扩展信息 |
| createTime | 创建时间 |
| updateTime | 更新时间 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |
| SendToJDOn | 发送至京东时间 |
| id | ID |

# [EC_JD_MemberUpdate] 字段注释说明
本表记录了EC京东会员更新信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| phoneNo | 手机号 |
| mappingResult | 映射结果 |
| level | 等级 |
| cardStatus | 卡状态 |
| ext | 扩展信息 |
| xid | XID |
| jdpin | 京东PIN |
| time | 时间 |
| isFirstMapping | 是否首次映射 |
| v_child_birthday | 子女 生日 |
| v_child_nickname | 子女昵称 |
| v_child_sex | 子女性别 |
| createdOn | 创建于 |
| modifiedOn | 修改于 |
| phoneNo | 手机号 |

# [EC_JD_Mot] 字段注释说明
本表记录了EC京东MOT（关键时刻）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uid | 用户ID |
| externalUserid | 外部用户ID |
| target | 目标 |
| executor | 执行人 |
| sendTime | 发送时间 |
| mot_def_no | MOT定义编号 |
| status | 状态 |
| msg | 消息 |
| contactTime | 联系时间 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |
| id | ID |

# [EC_JD_MotDetail] 字段注释说明
本表记录了EC京东MOT（关键时刻）详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| remark | 备注 |
| materialType | 材料类型 |
| text | 文本 |
| linkTitle | 链接标题 |
| linkImage | 链接图片 |
| linkUrl | 链接URL |
| linkDesc | 链接描述 |
| imageFile | 图片文件 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |
| id | ID |
| materialType | 材料类型 |

# [EC_JD_MotDetail_WDY] 字段注释说明
本表记录了EC京东MOT（关键时刻）详细信息（WDY）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| remark | 备注 |
| contentType | 内容类型 |
| Brand | 品牌 |
| Days | 天数 |
| Is_Gaoqian | 是否高潜 |
| content | 内容 |
| url | URL |
| fileName | 文件名 |
| previewImgUrl | 预览图片URL |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |

# [EC_JD_Order] 字段注释说明
本表记录了EC京东订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| ordStatus | 订单状态 |
| shopId | 店铺ID |
| goodsQtty | 商品数量 |
| skuId | SKU ID |
| parentOrdId | 父订单ID |
| ordStartDate | 订单开始日期 |
| ordEndDate | 订单结束日期 |
| sonOrdId | 子订单ID |
| ordAmt | 订单金额 |
| goodName | 商品名称 |
| userLogAcct | 用户登录账户 |
| createTime | 创建时间 |
| updateTime | 更新时间 |
| newShopFlg | 新店铺标志 |
| newFlg | 新标志 |
| firstTradeDate | 首次交易日期 |
| openCardDate | 开卡日期 |
| level | 等级 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |
| id | ID |

# [EC_JD_Pinyou_Log] 字段注释说明
本表记录了EC京东品友日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | 加入日期 |
| S_Mobile | S端手机号 |
| JD_Mobile | 京东手机号 |
| IsNewCustomer | 是否新客户 |
| NewCustomerType | 新客户类型 |
| Consumer_Validation_Date | 消费者验证日期 |
| CreatedOn | 创建于 |
| SentToPinYouOn | 发送至品友时间 |
| KSFID | KSFID |

# [EC_JD_PointIncs] 字段注释说明
本表记录了EC京东积分增加信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| pin | PIN码 |
| phoneNo | 手机号 |
| pointInc | 积分增加 |
| type | 类型 |
| recordId | 记录ID |
| content | 内容 |
| ext | 扩展信息 |
| xid | XID |
| createdOn | 创建于 |
| id | ID |

# [EC_JD_Products_Info] 字段注释说明
本表记录了EC京东产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| skuId | SKU ID |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| skuId | SKU ID |

# [EC_JD_QW_BindInfo] 字段注释说明
本表记录了EC京东企微绑定信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| externalUserId | 外部用户ID |
| executor | 执行人 |
| openId | OpenID |
| addDate | 添加日期 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |

# [EC_JD_SCRM_IntentionTag] 字段注释说明
本表记录了EC京东SCRM意向标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| avatar | 头像 |
| external_user_id | 外部用户ID |
| name | 名称 |
| user_id | 用户ID |
| assign_user_name | 分配的用户名 |
| tag_create_time | 标签创建时间 |
| tag_id | 标签ID |
| tag_name | 标签名称 |
| tag_group_name | 标签组名称 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |
| id | ID |

# [EC_JD_WDY_CustomerContact] 字段注释说明
本表记录了EC京东WDY客户联系人信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| contacts_record_id | 联系人记录ID |
| name | 名称 |
| contact_remark | 联系人备注 |
| contact_headimgurl | 联系人头像URL |
| contacts_type | 联系人类型 |
| corp_name | 公司名称 |
| gender | 性别 |
| personal_record_id | 个人记录ID |
| personal_name | 个人姓名 |
| assign_user_name | 分配的用户名 |
| group_name | 组名 |
| client_status | 客户端状态 |
| work_status | 工作状态 |
| customer_add_time | 客户添加时间 |
| user_id | 用户ID |
| personal_remote_id | 个人远程ID |
| remote_id | 远程ID |
| external_userid | 外部用户ID |
| Tag | 标签 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |

# [EC_JD_WDY_MOTSend] 字段注释说明
本表记录了EC京东WDY MOT发送信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| userId | 用户ID |
| enterpriseId | 企业ID |
| corpId | 公司ID |
| targetType | 目标类型 |
| targetId | 目标ID |
| remoteId | 远程ID |
| personalId | 个人ID |
| personalRemoteId | 个人远程ID |
| contentType | 内容类型 |
| content | 内容 |
| url | URL |
| fileName | 文件名 |
| previewImgUrl | 预览图片URL |
| msgSource | 消息来源 |
| sendTime | 发送时间 |
| mot_def_no | MOT定义编号 |
| status | 状态 |
| msg | 消息 |
| contactTime | 联系时间 |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |

# [EC_JD_WDY_SysTag] 字段注释说明
本表记录了EC京东WDY系统标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| tagGroupId | 标签组ID |
| tagGroupName | 标签组名称 |
| tagGroupCreateTime | 标签组创建时间 |
| tagGroupOrderNo | 标签组排序号 |
| tagId | 标签ID |
| tagName | 标签名称 |
| createTime | 创建时间 |
| updateTime | 更新时间 |
| orderNo | 排序号 |

# [EC_JD_WDY_Tag] 字段注释说明
本表记录了EC京东WDY标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| RunDate | 运行日期 |
| RunDays | 运行天数 |
| LastBuyDate | 最后购买日期 |
| LastUseDays | 最后使用天数 |
| KongDate | 空罐日期 |
| LastsonOrdId | 最后子订单ID |
| Is_Shougou | 是否首购 |
| Tag | 标签 |
| Brand | 品牌 |
| Category | 类别 |
| Is_Gaoqian | 是否高潜 |
| externalUserId | 外部用户ID |
| CreatedOn | 创建于 |
| ModifiedOn | 修改于 |

# [EC_NewCustomerType_Log] 字段注释说明
本表记录了EC新客户类型日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S端手机号 |
| NewCustomerType | 新客户类型 |
| TouchPoint | 触点 |
| BuyTime | 购买时间 |
| Payload | 有效负载 |
| Result | 结果 |
| CreatedOn | 创建于 |
| ID | ID |

# [ec_taobao_grade] 字段注释说明
本表记录了淘宝等级信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| planId | 计划ID |
| gradeHierarchyId | 等级层次ID |
| memberId | 会员ID |
| currentGradeDefinitionId | 当前等级定义ID |
| effectDate | 生效日期 |
| overdueDate | 过期日期 |
| created | 创建时间 |
| planName | 计划名称 |
| gradeHierarchyName | 等级层次名称 |
| currentGradeName | 当前等级名称 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_graderecord] 字段注释说明
本表记录了淘宝等级记录信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| planId | 计划ID |
| planName | 计划名称 |
| memberGradeId | 会员等级ID |
| gradeHierarchyId | 等级层次ID |
| gradeHierarchyName | 等级层次名称 |
| memberId | 会员ID |
| originalGradeId | 原始等级ID |
| originalGradeName | 原始等级名称 |
| originalEffectDate | 原始生效日期 |
| originalOverdueDate | 原始过期日期 |
| currentGradeId | 当前等级ID |
| currentGradeName | 当前等级名称 |
| currentEffectDate | 当前生效日期 |
| currentOverdueDate | 当前过期日期 |
| recordType | 记录类型 |
| changeWay | 变更方式 |
| triggerId | 触发器ID |
| traceId | 追踪ID |
| recordSourceDetail | 记录来源详情 |
| operator | 操作员 |
| description | 描述 |
| extraInfo | 额外信息 |
| created | 创建时间 |
| channel | 渠道 |
| eventTypeName | 事件类型名称 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_history_member] 字段注释说明
本表记录了淘宝历史会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| shopId | 店铺ID |
| snapshotInfo | 快照信息 |
| gradeName | 等级名称 |
| grade | 等级 |
| buyerNick | 买家昵称 |
| gmtModified | 修改时间 |
| points | 积分 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_member] 字段注释说明
本表记录了淘宝会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | 会员ID |
| memberName | 会员名称 |
| unionId | UnionID |
| headImgUrl | 头像URL |
| wechatNick | 微信昵称 |
| gender | 性别 |
| mobile | 手机号码 |
| phone | 电话 |
| cardNo | 卡号 |
| email | 电子邮箱 |
| identityCard | 身份证 |
| dateOfBirth | 出生日期 |
| country | 国家 |
| provinceCode | 省份代码 |
| provinceName | 省份名称 |
| cityCode | 城市代码 |
| cityName | 城市名称 |
| districtCode | 区/县代码 |
| districtName | 区/县名称 |
| address | 地址 |
| job | 工作 |
| shopCode | 店铺代码 |
| shopName | 店铺名称 |
| shopTypeCode | 店铺类型代码 |
| registerTime | 注册时间 |
| createTime | 创建时间 |
| updateTime | 更新时间 |
| firstRegisterChannelType | 首次注册渠道类型 |
| contactTel | 联系电话 |
| babyBirthday | 宝宝生日 |
| unBindTime | 解绑时间 |
| last_sync_new | 最新同步时间 |
| buyerNick | 买家昵称 |
| ouid | OUID |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| memberId | 会员ID |

# [ec_taobao_order] 字段注释说明
本表记录了淘宝订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| memberId | 会员ID |
| tid | 交易ID |
| shopId | 店铺ID |
| adjustFee | 调整费用 |
| alipayNo | 支付宝号 |
| buyerAlipayNo | 买家支付宝号 |
| buyerCodFee | 买家COD费用 |
| buyerEmail | 买家邮箱 |
| buyerMessage | 买家留言 |
| buyerNick | 买家昵称 |
| buyerObtainPointFee | 买家获得积分费用 |
| buyerRate | 买家评分 |
| codFee | COD费用 |
| codStatus | COD状态 |
| commissionFee | 佣金费用 |
| consignTime | 发货时间 |
| created | 创建时间 |
| discountFee | 折扣费用 |
| endTime | 结束时间 |
| expressAgencyFee | 快递代理费 |
| lastSync | 最后同步时间 |
| modified | 修改时间 |
| num | 数量 |
| payment | 支付金额 |
| payTime | 支付时间 |
| pointFee | 积分费用 |
| postFee | 邮费 |
| realPointFee | 实际积分费用 |
| receivedPayment | 已收支付金额 |
| receiverAddress | 收货人地址 |
| receiverCity | 收货人城市 |
| receiverDistrict | 收货人区/县 |
| receiverMobile | 收货人手机 |
| receiverName | 收货人姓名 |
| receiverPhone | 收货人电话 |
| receiverState | 收货人省份 |
| receiverZip | 收货人邮编 |
| refundFee | 退款费用 |
| sellerCodFee | 卖家COD费用 |
| sellerFlag | 卖家标志 |
| sellerMemo | 卖家备注 |
| sellerNick | 卖家昵称 |
| sellerRate | 卖家评分 |
| shippingType | 配送方式 |
| status | 状态 |
| stepTradeStatus | 步骤交易状态 |
| totalFee | 总费用 |
| tradeFrom | 交易来源 |
| type | 类型 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_orderitem] 字段注释说明
本表记录了淘宝订单项目信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| tid | 交易ID |
| memberId | 会员ID |
| cid | 类目ID |
| numIid | 商品数字ID |
| oid | 订单ID |
| outerIid | 外部商品ID |
| refundId | 退款ID |
| shopId | 店铺ID |
| skuId | SKU ID |
| adjustFee | 调整费用 |
| buyerNick | 买家昵称 |
| buyerRate | 买家评分 |
| consignTime | 发货时间 |
| created | 创建时间 |
| discountFee | 折扣费用 |
| divideOrderFee | 分摊订单费用 |
| endTime | 结束时间 |
| invoiceNo | 发票号 |
| isOversold | 是否超卖 |
| itemMealId | 套餐ID |
| itemMealName | 套餐名称 |
| lastSync | 最后同步时间 |
| logisticsCompany | 物流公司 |
| modified | 修改时间 |
| num | 数量 |
| partMjzDiscount | 部分满减折扣 |
| payment | 支付金额 |
| payTime | 支付时间 |
| picPath | 图片路径 |
| price | 价格 |
| refundFee | 退款费用 |
| refundStatus | 退款状态 |
| sellerNick | 卖家昵称 |
| sellerRate | 卖家评分 |
| skuPropertiesName | SKU属性名称 |
| status | 状态 |
| stepTradeStatus | 步骤交易状态 |
| title | 标题 |
| totalFee | 总费用 |
| tradeFrom | 交易来源 |
| type | 类型 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_point] 字段注释说明
本表记录了淘宝积分信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| planId | 计划ID |
| pointPlanId | 积分计划ID |
| memberId | 会员ID |
| point | 积分 |
| modified | 修改时间 |
| created | 创建时间 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_pointrecord] 字段注释说明
本表记录了淘宝积分记录信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| planId | 计划ID |
| pointPlanId | 积分计划ID |
| memberPointId | 会员积分ID |
| memberId | 会员ID |
| point | 积分 |
| totalPoint | 总积分 |
| recordType | 记录类型 |
| recordSourceDetail | 记录来源详情 |
| effectiveDate | 生效日期 |
| overdueDate | 过期日期 |
| extralInfo | 额外信息 |
| recordDetail | 记录详情 |
| desc | 描述 |
| fromStatus | 来源状态 |
| operator | 操作员 |
| operatorId | 操作员ID |
| modified | 修改时间 |
| created | 创建时间 |
| channel | 渠道 |
| key | 键 |
| ruleGroup | 规则组 |
| ruleName | 规则名称 |
| ruleId | 规则ID |
| changeMode | 变更模式 |
| planName | 计划名称 |
| pointPlanName | 积分计划名称 |
| traceId | 追踪ID |
| eventTypeName | 事件类型名称 |
| actionName | 操作名称 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [ec_taobao_product] 字段注释说明
本表记录了淘宝产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| approveStatus | 审批状态 |
| cid | 类目ID |
| created | 创建时间 |
| delistTime | 下架时间 |
| detailUrl | 详情URL |
| inputPids | 输入的PID |
| inputStr | 输入字符串 |
| isFenxiao | 是否分销 |
| lastSync | 最后同步时间 |
| listTime | 上架时间 |
| modified | 修改时间 |
| numIid | 商品数字ID |
| outerId | 外部ID |
| picUrl | 图片URL |
| price | 价格 |
| props | 属性 |
| propsName | 属性名称 |
| sellerCids | 卖家类目ID |
| shopId | 店铺ID |
| title | 标题 |
| last_sync_new | 最新同步时间 |
| productCode | 产品代码 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Comments | 评论 |
| id | ID |

# [ec_taobao_product_info2] 字段注释说明
本表记录了淘宝产品信息2。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| 商品货号 | 商品货号 |
| 商品货号V2 | 商品货号V2 |
| ProductName | 产品名称 |
| Qty | 数量 |
| Brand | 品牌 |
| Stage | 阶段 |
| Netweight | 净重 |
| 一口价 | 一口价 |
| NPS单价 | NPS单价 |
| NPS价 | NPS价 |
| QIP价 | QIP价 |
| 备注 | 备注 |
| LastChange | 最后更改时间 |

# [ec_taobao_Products_Info_20231121_Sanyar] 字段注释说明
本表记录了2023年11月21日Sanyar提供的淘宝产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 天猫店铺名称 | 天猫店铺名称 |
| 类目 | 类目 |
| 商品ID | 商品ID |
| 商品标题 | 商品标题 |
| 商家编码 | 商家编码 |
| CODE码 | CODE码 |
| F7 | 字段7 |
| F8 | 字段8 |

# [ec_taobao_Products_Info_20231121_Sanyar_2] 字段注释说明
本表记录了2023年11月21日Sanyar提供的淘宝产品信息（表2）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 天猫店铺名称 | 天猫店铺名称 |
| 类目 | 类目 |
| 商品ID | 商品ID |
| 商品标题 | 商品标题 |
| 商家编码 | 商家编码 |
| CODE码 | CODE码 |

# [EC_taobao_Products_Info_Gerber] 字段注释说明
本表记录了淘宝嘉宝产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Title | 标题 |
| ProductCode | 产品代码 |
| 数量 | 数量 |
| NPS_Price | NPS价格 |
| Comments | 评论 |
| ID | ID |

# [ec_taobao_productskus] 字段注释说明
本表记录了淘宝产品SKU信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| created | 创建时间 |
| lastSync | 最后同步时间 |
| numIid | 商品数字ID |
| outerId | 外部ID |
| price | 价格 |
| properties | 属性 |
| propertiesName | 属性名称 |
| quantity | 数量 |
| shopId | 店铺ID |
| skuId | SKU ID |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| id | ID |

# [ec_taobao_refund] 字段注释说明
本表记录了淘宝退款信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| tid | 交易ID |
| memberId | 会员ID |
| numIid | 商品数字ID |
| refundId | 退款ID |
| sid | SID |
| shopId | 店铺ID |
| oid | 订单ID |
| buyerNick | 买家昵称 |
| companyName | 公司名称 |
| created | 创建时间 |
| csStatus | 客服状态 |
| exitsTimeout | 存在超时 |
| goodReturnTime | 退货时间 |
| hasGoodReturn | 有退货 |
| lastSync | 最后同步时间 |
| modified | 修改时间 |
| num | 数量 |
| orderStatus | 订单状态 |
| payment | 支付金额 |
| price | 价格 |
| reason | 原因 |
| refundDesc | 退款描述 |
| refundFee | 退款费用 |
| remindType | 提醒类型 |
| sellerNick | 卖家昵称 |
| status | 状态 |
| timeout | 超时 |
| title | 标题 |
| totalFee | 总费用 |
| last_sync_new | 最新同步时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| id | ID |

# [EC_Tmall_DW_MegaNan_Member] 字段注释说明
本表记录了天猫DW MegaNan会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | 会员ID |
| memberName | 会员名称 |
| gender | 性别 |
| mobile | 手机号码 |
| shopCode | 店铺代码 |
| shopName | 店铺名称 |
| shopTypeCode | 店铺类型代码 |
| registerTime | 注册时间 |
| createTime | 创建时间 |
| CreatedOn | 创建于 |
| mixMobile | 混合手机号 |

# [EC_Tmall_DW_MegaNan_Order] 字段注释说明
本表记录了天猫DW MegaNan订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | 会员ID |
| mobile | 手机号码 |
| oid | 订单ID |
| tid | 交易ID |
| numIid | 商品数字ID |
| price | 价格 |
| num | 数量 |
| totalFee | 总费用 |
| payment | 支付金额 |
| refundFee | 退款费用 |
| created | 创建时间 |
| payTime | 支付时间 |
| consignTime | 发货时间 |
| endTime | 结束时间 |
| title | 标题 |
| Brand | 品牌 |
| Stage | 阶段 |
| CreatedOn | 创建于 |

# [EC_Tmall_DW_MegaNan_Product] 字段注释说明
本表记录了天猫DW MegaNan产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| approveStatus | 审批状态 |
| cid | 类目ID |
| created | 创建时间 |
| delistTime | 下架时间 |
| detailUrl | 详情URL |
| inputPids | 输入的PID |
| inputStr | 输入字符串 |
| isFenxiao | 是否分销 |
| lastSync | 最后同步时间 |
| listTime | 上架时间 |
| modified | 修改时间 |
| numIid | 商品数字ID |
| outerId | 外部ID |
| picUrl | 图片URL |
| price | 价格 |
| props | 属性 |
| propsName | 属性名称 |
| sellerCids | 卖家类目ID |
| shopId | 店铺ID |
| title | 标题 |
| productCode | 产品代码 |
| CreatedOn | 创建于 |
| rn | 行号 |
| Brand | 品牌 |
| Stage | 阶段 |

# [ec_雀巢母婴ID_20211221] 字段注释说明
本表记录了2021年12月21日的雀巢母婴ID信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductCode_Nestle | 雀巢产品代码 |
| ProductName | 产品名称 |
| Qty | 数量 |
| Brand | 品牌 |
| Stage | 阶段 |

# [Error_Log] 字段注释说明
本表记录了错误日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | 日志ID |
| Name | 名称 |
| Message | 消息 |
| CreatedOn | 创建时间 |
| ID | ID |

# [ErrorHandling] 字段注释说明
本表记录了错误处理信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pkErrorHandlingID | 错误处理主键ID |
| Error_Number | 错误号 |
| Error_Message | 错误消息 |
| Error_Severity | 错误严重性 |
| Error_State | 错误状态 |
| Error_Procedure | 错误过程 |
| Error_Line | 错误行号 |
| UserName | 用户名 |
| HostName | 主机名 |
| Time_Stamp | 时间戳 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| pkErrorHandlingID | 错误处理主键ID |

# [EWechat_CorpId] 字段注释说明
本表记录了企业微信公司ID信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| Name | 名称 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [EWechat_SNC_External] 字段注释说明
本表记录了企业微信SNC外部联系人信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Unionid | UnionID |
| Openid | OpenID |
| SNCUserId | SNC用户ID |
| ToUserName | 接收方用户名 |
| FromUserName | 发送方用户名 |
| SNCCode | SNC代码 |
| ChangeType | 变更类型 |
| TimeStamp | 时间戳 |
| State | 状态 |
| MsgType | 消息类型 |
| Event | 事件 |
| CreatedOn | 创建时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ExternalUserID | 外部用户ID |
| Id | ID |

# [EWechat_User] 字段注释说明
本表记录了企业微信用户信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | UnionID |
| ExternalUserID | 外部用户ID |
| WeChatName | 微信名 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Avatar | 头像 |
| Unionid | UnionID |

# [FAQ] 字段注释说明
本表记录了常见问题（FAQ）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| InfoType | 信息类型 |
| Question | 问题 |
| Ans | 答案 |
| ParentId | 父ID |
| OrderID | 排序ID |
| AttName | 附件名称 |
| AttPath | 附件路径 |
| QueryAns | 查询答案 |
| OperationFlag | 操作标志 |
| txUser | 交易用户 |
| txDate | 交易日期 |
| ID | ID |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| txDate_20230214 | 20230214交易日期 |
| txDate_20230215 | 20230215交易日期 |
| ID | ID |

# [fugou_shanmu] 字段注释说明
本表记录了复购闪促相关信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| Brand | 品牌 |
| Stage | 阶段 |
| ka_name | KA名称 |
| BuyTime | 购买时间 |
| rn2 | 行号2 |

# [HA_Sanyar] 字段注释说明
本表记录了HA三元相关信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| BuyTime | 购买时间 |
| BuyTime_Day | 购买天数 |
| StoreCode | 门店代码 |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| 订单罐数 | 订单罐数 |
| ProductCode | 产品代码 |
| KSFId | KSFID |
| 招募订单中子订单顺序 | 招募订单中子订单顺序 |
| 招募时间 | 招募时间 |
| 招募时门店 | 招募时门店 |
| 招募复购订单属性 | 招募复购订单属性 |
| 下单天数 | 下单天数 |
| 下单数 | 下单数 |
| 复购订单属性 | 复购订单属性 |
| 是否院线店 | 是否院线店 |
| Price | 价格 |

# [ims_customer] 字段注释说明
本表记录了IMS客户信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| cus_id | 客户ID |
| cus_number | 客户编号 |
| cus_name | 客户名称 |
| p_cus_name | P客户名称 |
| p_cus_number | P客户编号 |
| mobile | 手机号码 |
| realname | 真实姓名 |
| area_name | 区域名称 |
| city_group | 城市组 |
| province | 省份 |
| city | 城市 |
| city_level | 城市级别 |
| address | 地址 |
| is_active | 是否活跃 |
| license | 许可证 |
| cdate | 创建日期 |
| updatetime | 更新时间 |
| cus_id | 客户ID |

# [ims_customer_rel] 字段注释说明
本表记录了IMS客户关系信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| cus_id | 客户ID |
| cus_uid | 客户UID |
| is_zhu | 是否主要 |
| is_onjob | 是否在职 |
| cdate | 创建日期 |
| updatetime | 更新时间 |
| id | ID |

# [ims_edms_stores_dtc] 字段注释说明
本表记录了IMS EDMS DTC门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| store_number | 门店编号 |
| store_name | 门店名称 |
| area_name | 区域名称 |
| province | 省份 |
| city | 城市 |
| city_group | 城市组 |
| cityLevel | 城市级别 |
| ISOAH | ISOAH |
| ka_type | KA类型 |
| ka_name | KA名称 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| store_number | 门店编号 |

# [ims_gerber_coupon] 字段注释说明
本表记录了IMS嘉宝优惠券信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| title | 标题 |
| cardno | 卡号 |
| gift_code | 礼品码 |
| openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| mobile | 手机号码 |
| money | 金额 |
| exp_time | 过期时间 |
| use_time | 使用时间 |
| is_used | 是否已使用 |
| orderno | 订单号 |
| snc_code | SNC代码 |
| store_number | 门店编号 |
| get_time | 获取时间 |
| updatetime | 更新时间 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| get_storeno | 获取门店编号 |
| get_snc | 获取SNC |
| id | ID |

# [ims_gerber_coupon2] 字段注释说明
本表记录了IMS嘉宝优惠券信息（表2）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| title | 标题 |
| cardno | 卡号 |
| gift_code | 礼品码 |
| openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| mobile | 手机号码 |
| money | 金额 |
| exp_time | 过期时间 |
| use_time | 使用时间 |
| is_used | 是否已使用 |
| orderno | 订单号 |
| snc_code | SNC代码 |
| store_number | 门店编号 |
| get_time | 获取时间 |
| updatetime | 更新时间 |
| post_time | 推送时间 |
| post_status | 推送状态 |
| post_res | 推送结果 |

# [ims_nestle_al110_popup] 字段注释说明
本表记录了IMS雀巢AL110弹窗信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| unionid | 用户微信Unionid |
| cdate | 创建日期 |
| CreatedOn | 创建时间 |
| unionid | 用户微信Unionid |

# [ims_nestle_business_stores_product_3] 字段注释说明
本表记录了IMS雀巢业务门店产品信息（表3）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| sid | SID |
| productcode | 产品代码 |
| tankcode | 罐码 |
| status | 状态 |
| productcontent | 产品内容 |
| serial_number | 序列号 |
| creattime | 创建时间 |
| updatetime | 更新时间 |
| id | ID |

# [ims_nestle_business_xh_book_goods_detail] 字段注释说明
本表记录了IMS雀巢业务星火预订商品详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| book_id | 预订ID |
| sid | SID |
| is_crm | 是否CRM |
| cus_number | 客户编号 |
| cus_uid | 客户UID |
| tcds_code | TCDS代码 |
| cus_uid_gx | 客户UID GX |
| productcode | 产品代码 |
| tankcode | 罐码 |
| status | 状态 |
| is_allot | 是否分配 |
| receive_serial_number | 接收序列号 |
| receive_tcds_code | 接收TCDS代码 |
| receive_cus_uid_gx | 接收客户UID GX |
| receive_date | 接收日期 |
| receive_type | 接收类型 |
| cdate | 创建日期 |
| updatetime | 更新时间 |
| Comments | 评论 |
| id | ID |

# [ims_nestle_business_xh_cus_refund_goods_detail] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| refund_id | refund_id |
| cus_number | cus_number |
| cus_uid | cus_uid |
| tcds_code | tcds_code |
| productcode | productcode |
| boxcode | boxcode |
| tankcode | tankcode |
| cdate | cdate |
| updatetime | updatetime |
| id | id |

# [ims_nestle_business_xh_cus_stock_detail] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| order_id | order_id |
| cus_uid | cus_uid |
| cus_number | cus_number |
| tcds_code | tcds_code |
| productcode | productcode |
| tankcode | tankcode |
| boxcode | boxcode |
| status | status |
| cdate | cdate |
| expiredate | expiredate |
| updatetime | updatetime |
| Comments | Comments |
| id | id |

# [ims_nestle_hanan_survey_answer] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| snc | snc |
| openid | openid |
| unionid | unionid |
| nickname | nickname |
| headimgurl | headimgurl |
| answer | answer |
| is_answer | is_answer |
| answer_time | answer_time |
| answer_date | answer_date |
| ctime | ctime |
| cdate | cdate |
| update_time | update_time |

# [ims_qrcode_stat_3] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| acid | acid |
| qid | qid |
| openid | openid |
| type | type |
| qrcid | qrcid |
| scene_str | scene_str |
| name | name |
| createtime | createtime |
| addtime | addtime |
| updatetime | updatetime |
| unionid | unionid |
| serial_number | serial_number |

# [ims_qrcode_stat_3_Last] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| serial_number | serial_number |
| Unionid | Unionid |
| uniacid | uniacid |
| addtime | addtime |
| id | id |

# [IncentiveTins] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 购买SNC | 购买SNC |
| 1-18听 | 1-18听 |
| 19-36听 | 19-36听 |
| 37-42听 | 37-42听 |
| 43-100听 | 43-100听 |
| 100听以上 | 100听以上 |

# [Insert_Error_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Payload | Payload |
| TargetTable | TargetTable |
| Createdon | Createdon |
| SyncToTargetTableOn | SyncToTargetTableOn |
| Id | Id |

# [IQC_KPI_Scan_Rate] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MemberLevel | MemberLevel |
| Brand | Brand |
| 分子 | 分子 |
| 分母 | 分母 |
| ScanRate | ScanRate |
| rn | rn |
| CurrentDate | CurrentDate |
| CreatedOn | CreatedOn |

# [IQC_KPI_Scan_Rate_tin] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MemberLevel | MemberLevel |
| Brand | Brand |
| 分子 | 分子 |
| 分母 | 分母 |
| ScanRate | ScanRate |
| rn | rn |
| CurrentDate | CurrentDate |
| CreatedOn | CreatedOn |
| ID | ID |

# [KSF_DATA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFId |
| JoinDate | JoinDate |
| OriginalBatchNo | OriginalBatchNo |
| Channel | Channel |
| BigArea | BigArea |
| Province | Province |
| CityLevel | CityLevel |
| CityGroup | CityGroup |
| City | City |
| District | District |
| StoreID | StoreID |
| StoreName | StoreName |
| SSRCode | SSRCode |
| SSRName | SSRName |
| MobileEnterTime | MobileEnterTime |
| ApproveTime | ApproveTime |
| SupervisorName | SupervisorName |
| SupervisorCode | SupervisorCode |
| NewCustomerType | NewCustomerType |
| MamaName | MamaName |
| BabyBirthday | BabyBirthday |
| BabyBirthday2 | BabyBirthday2 |
| Mobile1 | Mobile1 |
| Mobile2 | Mobile2 |
| ProductCode | ProductCode |
| ProductName | ProductName |
| BuyTime | BuyTime |
| GiftReason | GiftReason |
| Remark | Remark |
| IsNewCustomer | IsNewCustomer |
| FaildReason | FaildReason |
| InvalidReason | InvalidReason |
| CreatedDate | CreatedDate |
| ByTokenID | ByTokenID |
| IsSentToCRM | IsSentToCRM |
| IsAcknowledged | IsAcknowledged |
| SentToCRMDate | SentToCRMDate |
| GiftCode | GiftCode |
| GiftName | GiftName |
| GiftReceivedTime | GiftReceivedTime |
| ReferrerPhone | ReferrerPhone |
| GiftMechanism | GiftMechanism |
| Openid | Openid |
| PurchaseStatus | PurchaseStatus |
| FirstBindingDate | FirstBindingDate |
| ModifiedOn | ModifiedOn |
| S_MOBILE | S_MOBILE |
| Completed_Info | Completed_Info |
| Completed_ARI | Completed_ARI |
| Completed_S1S2_Ratting | Completed_S1S2_Ratting |
| Consumer_Validation_Date | Consumer_Validation_Date |
| SNC_Validation_Date | SNC_Validation_Date |
| LastChange | LastChange |
| IdentityName | IdentityName |
| UserGroup | UserGroup |
| CinemaLine | CinemaLine |
| StoreTypeName | StoreTypeName |
| CSR_CallResult | CSR_CallResult |
| OrderNumber | OrderNumber |
| Unionid | Unionid |
| BU | BU |
| Comments | Comments |
| Vip_Level | Vip_Level |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| Tcds_Id | Tcds_Id |
| KSFId | KSFId |

# [KSF_DATA_2022] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFId |
| JoinDate | JoinDate |
| NewCustomerType | NewCustomerType |
| IsNewCustomer | IsNewCustomer |
| FaildReason | FaildReason |
| Openid | Openid |
| Mobile1 | Mobile1 |
| S_MOBILE | S_MOBILE |
| OriginalBatchNo | OriginalBatchNo |
| Channel | Channel |
| StoreID | StoreID |
| SSRCode | SSRCode |
| ProductCode | ProductCode |
| ProductName | ProductName |
| ByTokenID | ByTokenID |
| FirstBindingDate | FirstBindingDate |
| Completed_ARI | Completed_ARI |
| Consumer_Validation_Date | Consumer_Validation_Date |
| SNC_Validation_Date | SNC_Validation_Date |
| Completed_Questionnaire2_Date | Completed_Questionnaire2_Date |
| Completed_Questionnaire2_SNC | Completed_Questionnaire2_SNC |
| Comments | Comments |
| LastChange_Azure | LastChange_Azure |
| CreatedDate | CreatedDate |
| IsDouble | IsDouble |
| Completed_Group_Date | Completed_Group_Date |
| GiftCode | GiftCode |
| GiftName | GiftName |
| FirstEnterGroupDate | FirstEnterGroupDate |
| SNC_Validation_2022_Date | SNC_Validation_2022_Date |
| BuyTime_2 | BuyTime_2 |
| Remark | Remark |
| Unionid | Unionid |
| BU | BU |
| ModifiedOn | ModifiedOn |
| Xinke_Tag | Xinke_Tag |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| Tcds_Id | Tcds_Id |
| KSFId | KSFId |

# [KSF_DATA_CC] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | Joindate |
| Unionid | Unionid |
| S_Mobile | S_Mobile |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Qty | Qty |
| BuyTime | BuyTime |
| Source | Source |
| SncCode | SncCode |
| SncName | SncName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| Channel | Channel |
| BigArea | BigArea |
| Province | Province |
| CityGroup | CityGroup |
| City | City |
| MamaName | MamaName |
| BabyBirthday | BabyBirthday |
| PMamaId | PMamaId |
| NewCustomerType | NewCustomerType |
| OriginalBatchNo | OriginalBatchNo |
| CreatedOn | CreatedOn |
| SentToCRMOn | SentToCRMOn |
| 是否购买了IMF | 是否购买了IMF |
| SNC_Validation_Date | SNC_Validation_Date |
| KSFID | KSFID |

# [KSF_DATA_CMPA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | Joindate |
| Unionid | Unionid |
| S_Mobile | S_Mobile |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Qty | Qty |
| BuyTime | BuyTime |
| Source | Source |
| SncCode | SncCode |
| SncName | SncName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| Channel | Channel |
| BigArea | BigArea |
| Province | Province |
| CityGroup | CityGroup |
| City | City |
| MamaName | MamaName |
| BabyBirthday | BabyBirthday |
| PMamaId | PMamaId |
| NewCustomerType | NewCustomerType |
| OriginalBatchNo | OriginalBatchNo |
| CreatedOn | CreatedOn |
| 是否购买了IMF | 是否购买了IMF |

# [Linda_Gerber_20231024] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| BabyBirthday | BabyBirthday |
| Buy_Brand | Buy_Brand |
| Has_buy_IMF | Has_buy_IMF |
| 最近Starter OR Optima购买时间 | 最近Starter OR Optima购买时间 |
| CMamaId | CMamaId |
| 购买时月龄 | 购买时月龄 |
| 当前月龄 | 当前月龄 |
| S_MOBILE | S_MOBILE |

# [Linda_GerberNoIMF_20231024] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| BabyBirthday | BabyBirthday |
| Buy_Brand | Buy_Brand |
| Has_buy_IMF | Has_buy_IMF |
| 最近Starter OR Optima购买时间 | 最近Starter OR Optima购买时间 |
| CMamaId | CMamaId |
| 购买时月龄 | 购买时月龄 |
| 当前月龄 | 当前月龄 |
| S_MOBILE | S_MOBILE |

# [Member_IQC_Tag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IQC_2gou_1_QrCode | IQC_2gou_1_QrCode |
| IQC_2gou_1_Time | IQC_2gou_1_Time |
| IQC_2gou_Last_QrCode | IQC_2gou_Last_QrCode |
| IQC_2gou_Last_Time | IQC_2gou_Last_Time |
| IQC_3zhuanduan_1_QrCode | IQC_3zhuanduan_1_QrCode |
| IQC_3zhuanduan_1_Time | IQC_3zhuanduan_1_Time |
| IQC_3zhuanduan_Last_QrCode | IQC_3zhuanduan_Last_QrCode |
| IQC_3zhuanduan_Last_Time | IQC_3zhuanduan_Last_Time |
| Unionid | Unionid |

# [MEMBER_Level] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Vip_Level | Vip_Level |
| Total_Tins | Total_Tins |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |

# [Members] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Name | Name |
| Phone | Phone |
| Email | Email |
| Birthday | Birthday |
| CreatedAt | CreatedAt |
| UpdatedAt | UpdatedAt |
| Remarks | Remarks |
| Status | Status |
| JoinDate | JoinDate |
| Id | Id |

# [MobileCol] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT_CDP] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT_CRMPlus] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT_Dashboard] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT_Test] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_CMT_Wechat] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_GerberWechat] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_GerberWechatOpr] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_Archive] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_Daiy_Backup] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_DATA_DW] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_EC] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_OLTP] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_Report] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_NSC_TempDB] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_PS_Data] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileCol_Utility] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| mobile | mobile |

# [MobileTemp] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | tablename |
| colname | colname |
| NM | NM |

# [MONITOR_JOBS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Date | Date |
| Group | Group |
| Category | Category |
| ProducerValue | ProducerValue |
| ConsumerValue | ConsumerValue |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| LastChange_Azure | LastChange_Azure |
| ID | ID |
| Date | Date |

# [Monitor_System] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | Name |
| Value | Value |
| CreatedOn | CreatedOn |
| ID | ID |

# [MOT] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT_ID |
| MOT_DEF_No | MOT_DEF_No |
| Category | Category |
| TA_CMT_ID | TA_CMT_ID |
| TA_Mobile | TA_Mobile |
| TA_Openid | TA_Openid |
| TA_User_Name | TA_User_Name |
| JoinDate | JoinDate |
| Baby_BirthDay | Baby_BirthDay |
| Stage | Stage |
| Current_Stage | Current_Stage |
| Cross_Stage | Cross_Stage |
| Offset_Day | Offset_Day |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| ON_EC | ON_EC |
| Sent_To_CMT_On | Sent_To_CMT_On |
| Sent_To_CRMPlus_On | Sent_To_CRMPlus_On |
| TAG | TAG |
| Buy_History | Buy_History |
| Due_Date | Due_Date |
| Due_Stage | Due_Stage |
| Status | Status |
| Remark | Remark |
| Created_On | Created_On |
| Modified_On | Modified_On |
| Sent_Update_Status_On | Sent_Update_Status_On |
| SNC_Code_LastBuy | SNC_Code_LastBuy |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| Recent_Buy_Date | Recent_Buy_Date |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| S_Mobile | S_Mobile |
| MOT_PID | MOT_PID |
| Unionid | Unionid |
| TouchPoint | TouchPoint |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| StoreID | StoreID |
| NewCustomerType | NewCustomerType |
| XinkeTag | XinkeTag |
| ON_CSR | ON_CSR |
| Sent_To_CSR_On | Sent_To_CSR_On |
| ExternalUserID | ExternalUserID |
| WeChatName | WeChatName |
| Avatar | Avatar |
| MOT_ID | MOT_ID |

# [MOT_18_42_gt_30] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| ExternalUserID | ExternalUserID |

# [MOT_18_42_gt_30_20250327] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| ExternalUserID | ExternalUserID |
| Unionid | Unionid |

# [MOT_AL110_Bochu_TA_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | Current_Day |
| Unionid | Unionid |
| type | type |
| Offset_Day | Offset_Day |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| TA_Mobile | TA_Mobile |
| RegisterChannel | RegisterChannel |
| SUB_USER_NAME | SUB_USER_NAME |
| Baby_BirthDay | Baby_BirthDay |
| current_stage | current_stage |
| Stage | Stage |
| joindate | joindate |
| Tag | Tag |
| Buy_History | Buy_History |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| Touch_Point | Touch_Point |
| Store_Number | Store_Number |
| Sent2OADate | Sent2OADate |
| CreatedOn | CreatedOn |
| Remark | Remark |
| ID | ID |

# [MOT_AL110_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| RunDay | RunDay |
| RecruitDate | RecruitDate |
| Is_Buy_IMF | Is_Buy_IMF |
| Is_Allow_UseBohu_From_Link | Is_Allow_UseBohu_From_Link |
| Is_Sample_Bochu_200g | Is_Sample_Bochu_200g |
| Is_Chg_Milk | Is_Chg_Milk |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| Unionid | Unionid |

# [MOT_AL110_TagTable2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| RunDay | RunDay |
| RecruitDate | RecruitDate |
| Is_Buy_IMF | Is_Buy_IMF |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |

# [MOT_Base] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | Openid |
| unionid | unionid |
| Mobile | Mobile |
| Current_Stage | Current_Stage |
| StageByCRM | StageByCRM |
| 是否正在关注 | 是否正在关注 |
| BabyBirthday | BabyBirthday |
| Offset_Day | Offset_Day |

# [MOT_Birthday_Reminder] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| id | id |
| unionid | unionid |
| openid | openid |
| name | name |
| serial_number | serial_number |
| ha12_answer | ha12_answer |
| member_type | member_type |
| remember_type | remember_type |
| reminder_num | reminder_num |
| reminder_date | reminder_date |
| follow | follow |
| close | close |
| cdate | cdate |
| finish_date | finish_date |
| first_send | first_send |
| first_send_date | first_send_date |
| batch | batch |
| CreatedOn | CreatedOn |
| touch_point | touch_point |
| ha12_type | ha12_type |
| unionid | unionid |
| remember_type | remember_type |
| reminder_num | reminder_num |
| reminder_date | reminder_date |
| batch | batch |

# [MOT_BoChu_AdvocacyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| AdvocacyDate | AdvocacyDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_BoChu_CallBackTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |
| RemindBuyDate | RemindBuyDate |
| RemindBuyDateUpdate | RemindBuyDateUpdate |
| Status | Status |
| CallBackDate | CallBackDate |
| CampaleteDate | CampaleteDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |

# [MOT_BoChu_PurchaseBoChu] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| S1 | S1 |
| S2 | S2 |
| S3 | S3 |

# [MOT_BoChu_RecentPurchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| EmptyDay | EmptyDay |
| RemindDay | RemindDay |
| UpdateDate | UpdateDate |

# [MOT_BoChu_RecentPurchaseS23] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| RecentPurchaseS23Date | RecentPurchaseS23Date |

# [MOT_BoChu_RemindBuyS23TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| RecruitDate | RecruitDate |
| RecentPurchaseS23Date | RecentPurchaseS23Date |
| ReBuyTimes | ReBuyTimes |
| CreatedDate | CreatedDate |
| ID | ID |
| Unionid | Unionid |
| RecentPurchaseS23Date | RecentPurchaseS23Date |

# [MOT_BoChu_RemindBuyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |
| RecruitDate | RecruitDate |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindBuyDate | RemindBuyDate |
| Status | Status |
| CreatedDate | CreatedDate |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |

# [MOT_BoChu_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| RunDay | RunDay |
| TargetType | TargetType |
| RecentPurchaseS23Date | RecentPurchaseS23Date |
| IsBuyBoChuS3 | IsBuyBoChuS3 |
| IsBuyBoChuS2 | IsBuyBoChuS2 |
| IsBuyBoChuS1 | IsBuyBoChuS1 |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| RemindBuyDate | RemindBuyDate |
| ReBuyTimes | ReBuyTimes |
| StageGroup | StageGroup |
| RemindCSDate1 | RemindCSDate1 |
| RemindCSDate2 | RemindCSDate2 |
| RemindCSDate3 | RemindCSDate3 |
| RemindCSDate4 | RemindCSDate4 |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| Unionid | Unionid |

# [MOT_BoChu_WOM_OldTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Mobile | Mobile |
| ABGroup | ABGroup |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThirdRemindDate | ThirdRemindDate |
| ForthRemindDate | ForthRemindDate |
| FifthRemindDate | FifthRemindDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| ABGroupNew | ABGroupNew |
| Unionid | Unionid |

# [MOT_BochuGerber_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Runday | Runday |
| TargetType | TargetType |
| BrandGroup | BrandGroup |
| Purchase_Starter | Purchase_Starter |
| Purchase_谷启嘉贝 | Purchase_谷启嘉贝 |
| Purchase_米粥 | Purchase_米粥 |
| Coupon_Usetime | Coupon_Usetime |
| StartersFirstRemindDate | StartersFirstRemindDate |
| StartersSecondRemindDate | StartersSecondRemindDate |
| OptimaFirstRemindDate | OptimaFirstRemindDate |
| OptimaSecondRemindDate | OptimaSecondRemindDate |
| AmberFirstRemindDate | AmberFirstRemindDate |
| AmberSecondRemindDate | AmberSecondRemindDate |
| EndDate | EndDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_BochuGerber_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| GetBochuTime | GetBochuTime |
| Purchase_嘉宝产品 | Purchase_嘉宝产品 |
| RecentBuyBrand | RecentBuyBrand |
| RecentBuyTime | RecentBuyTime |
| CreateDate | CreateDate |
| Unionid | Unionid |

# [MOT_BoChuSample_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| TargetType | TargetType |
| GetSampleTime | GetSampleTime |
| RecentBuyTime | RecentBuyTime |
| RecentBuyCount | RecentBuyCount |
| EmptyDate | EmptyDate |
| FirstTriggerDate | FirstTriggerDate |
| SecondTriggerDate | SecondTriggerDate |
| BoChuHABuyPID | BoChuHABuyPID |
| EndDate | EndDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_BoChuSample_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| GetSampleTime | GetSampleTime |
| RecentBuyBrand | RecentBuyBrand |
| RecentBuyCount | RecentBuyCount |
| RecentBuyTime | RecentBuyTime |
| EmptyDate | EmptyDate |
| GapDay | GapDay |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_Call_Center] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Mobile | Mobile |
| QuestionnaireType | QuestionnaireType |
| MOT_DEF_No | MOT_DEF_No |
| CreatedOn | CreatedOn |
| SentToCRMOn | SentToCRMOn |
| Mobile | Mobile |
| QuestionnaireType | QuestionnaireType |
| MOT_DEF_No | MOT_DEF_No |

# [MOT_Defination] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | No |
| Category | Category |
| Objective | Objective |
| Mot_Type | Mot_Type |
| Status | Status |
| CTA | CTA |
| TouchPoints | TouchPoints |
| Descriptions | Descriptions |
| Due_Date | Due_Date |
| Remark | Remark |
| Enabled | Enabled |
| Due_Stage | Due_Stage |
| Brand | Brand |
| Product | Product |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Label_Level_3 | Label_Level_3 |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| Phase | Phase |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Stage | Stage |
| No | No |

# [MOT_Defination_20230401] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | No |
| Category | Category |
| Label_Level_2 | Label_Level_2 |
| Label_Level_3 | Label_Level_3 |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| TouchPoints | TouchPoints |
| Description | Description |
| Due_Date | Due_Date |
| Remark | Remark |
| Enabled | Enabled |
| TA | TA |
| Tagging | Tagging |
| old Descriptions | old Descriptions |
| new Descriptions | new Descriptions |

# [MOT_Defination_20240903] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | No |
| Category | Category |
| Label_Level_2 | Label_Level_2 |
| Label_Level_3 | Label_Level_3 |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| TouchPoints | TouchPoints |
| Descriptions | Descriptions |
| Due_Date | Due_Date |
| Remark | Remark |
| Enabled | Enabled |
| TA | TA |
| LastChange | LastChange |
| Due_Stage | Due_Stage |
| Brand | Brand |
| Product | Product |
| Phase | Phase |
| CreatedOn | CreatedOn |

# [MOT_Defination_20240903_1] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT_DEF_No |
| CD_Trigger_Qty | CD_Trigger_Qty |
| CD_Trigger_Min_Date | CD_Trigger_Min_Date |
| CD_Trigger_Last_Date | CD_Trigger_Last_Date |
| Status | Status |
| Brand | Brand |
| Objective | Objective |
| Mot_Type | Mot_Type |
| CTA or not | CTA or not |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Descriptions | Descriptions |
| Remark | Remark |
| Category | Category |
| TouchPoints | TouchPoints |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240904_Xia] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT_DEF_No |
| CD_Trigger_Qty | CD_Trigger_Qty |
| CD_Trigger_Min_Date | CD_Trigger_Min_Date |
| CD_Trigger_Last_Date | CD_Trigger_Last_Date |
| Status | Status |
| Brand | Brand |
| Objective | Objective |
| Mot_Type | Mot_Type |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Descriptions | Descriptions |
| Remark | Remark |
| Category | Category |
| TouchPoints | TouchPoints |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT_DEF_No |
| CD_Trigger_Qty | CD_Trigger_Qty |
| CD_Trigger_Min_Date | CD_Trigger_Min_Date |
| CD_Trigger_Last_Date | CD_Trigger_Last_Date |
| Status | Status |
| Enabled | Enabled |
| Brand | Brand |
| Objective | Objective |
| Mot_Type | Mot_Type |
| CTA or not | CTA or not |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Descriptions | Descriptions |
| Remark | Remark |
| Category | Category |
| TouchPoints | TouchPoints |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906_Kaylee] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT_DEF_No |
| CD_Trigger_Qty | CD_Trigger_Qty |
| CD_Trigger_Min_Date | CD_Trigger_Min_Date |
| CD_Trigger_Last_Date | CD_Trigger_Last_Date |
| Status | Status |
| Enabled | Enabled |
| Brand | Brand |
| Stage | Stage |
| Objective | Objective |
| Mot_Type | Mot_Type |
| CTA or not | CTA or not |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Descriptions | Descriptions |
| Remark | Remark |
| Category | Category |
| TouchPoints | TouchPoints |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906_XiaLan] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT_DEF_No |
| CD_Trigger_Qty | CD_Trigger_Qty |
| CD_Trigger_Min_Date | CD_Trigger_Min_Date |
| CD_Trigger_Last_Date | CD_Trigger_Last_Date |
| Status | Status |
| Enabled | Enabled |
| Brand | Brand |
| Stage | Stage |
| Objective | Objective |
| Mot_Type | Mot_Type |
| CTA or not | CTA or not |
| TA | TA |
| Label_Level_2 | Label_Level_2 |
| Descriptions | Descriptions |
| Remark | Remark |
| Category | Category |
| TouchPoints | TouchPoints |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Gerber_CNYTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThiredRemindDate | ThiredRemindDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_Gerber_Information] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | Openid |
| unionid | unionid |
| Mobile | Mobile |
| Current_Stage | Current_Stage |
| StageByCRM | StageByCRM |
| 是否正在关注 | 是否正在关注 |
| BabyBirthday | BabyBirthday |
| Offset_Day | Offset_Day |
| CouponUseTime | CouponUseTime |
| TouchPoint | TouchPoint |
| PureStarter | PureStarter |
| Purchase_嘉宝产品 | Purchase_嘉宝产品 |
| Purchase_谷启嘉贝 | Purchase_谷启嘉贝 |
| Purchase_米粥 | Purchase_米粥 |
| 绑定导购 | 绑定导购 |
| 导购是否在职 | 导购是否在职 |
| 绑定导购门店 | 绑定导购门店 |
| UpdateDate | UpdateDate |

# [MOT_Gerber_IsPureStarter] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Purchase_嘉宝产品 | Purchase_嘉宝产品 |
| PureStarter | PureStarter |
| Purchase_Starter | Purchase_Starter |
| Purchase_谷启嘉贝 | Purchase_谷启嘉贝 |
| Purchase_米粥 | Purchase_米粥 |
| UpdateDate | UpdateDate |

# [MOT_Gerber_IsUseCoupon] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| use_time | use_time |
| snc_code | snc_code |
| TouchPoint | TouchPoint |

# [MOT_Gerber_JiaoYaoTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| TargetType | TargetType |
| RunDay | RunDay |
| CouponUseTimes | CouponUseTimes |
| JourneyEndDate | JourneyEndDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_Gerber_NewCustomer] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| UseDate | UseDate |
| CreatedDate | CreatedDate |
| 筛选时最近绑定导购 | 筛选时最近绑定导购 |
| 筛选时导购是否在职 | 筛选时导购是否在职 |
| Unionid | Unionid |

# [MOT_Gerber_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| CreatedDate | CreatedDate |
| RunDay | RunDay |
| EndDate | EndDate |
| 筛选时最近绑定导购 | 筛选时最近绑定导购 |
| 筛选时导购是否在职 | 筛选时导购是否在职 |
| Type | Type |
| UpdateDate | UpdateDate |
| Unionid | Unionid |

# [MOT_Gerber_TunMoTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| RunDay | RunDay |
| CouponUseTimes | CouponUseTimes |
| JourneyEndDate | JourneyEndDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_1842Tin_TA2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UNIONID | UNIONID |
| TAG | TAG |
| Sent2CRMPlus | Sent2CRMPlus |
| Sent2CRMPlus_2 | Sent2CRMPlus_2 |
| Sent2CRMPlus_3 | Sent2CRMPlus_3 |
| Sent2CRMPlus_4 | Sent2CRMPlus_4 |
| Sent2CRMPlus_5 | Sent2CRMPlus_5 |
| Sent2CRMPlus_6 | Sent2CRMPlus_6 |
| Sent2CRMPlus_7 | Sent2CRMPlus_7 |
| Sent2CRMPlus_8 | Sent2CRMPlus_8 |
| Sent2CRMPlus_9 | Sent2CRMPlus_9 |
| Createdon | Createdon |

# [MOT_HA_42Tin_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UnionidS | UnionidS |
| Unionid | Unionid |
| s_mobile | s_mobile |
| CMamaId | CMamaId |
| PMamaId | PMamaId |
| MOBILE | MOBILE |
| Should1_Send_Date | Should1_Send_Date |
| Should2_Send_Date | Should2_Send_Date |
| Insert_MOT1_Date | Insert_MOT1_Date |
| Insert_MOT2_Date | Insert_MOT2_Date |

# [MOT_HA_AdvocacyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| AdvocacyDate | AdvocacyDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_CallBackTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |
| RemindBuyDate | RemindBuyDate |
| RemindBuyDateUpdate | RemindBuyDateUpdate |
| CallBackDate | CallBackDate |
| CampaleteDate | CampaleteDate |
| Remark | Remark |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |

# [MOT_HA_CrossStageTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Tag | Tag |
| IsBirthdayS3TA | IsBirthdayS3TA |
| IsBirthdayS4TA | IsBirthdayS4TA |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThirdRemindDate | ThirdRemindDate |
| ForthRemindDate | ForthRemindDate |
| UpdateDate | UpdateDate |
| CreateDate | CreateDate |
| Unionid | Unionid |

# [MOT_HA_EmptyABTestTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| SNCCode | SNCCode |
| IsOnJob | IsOnJob |
| StoreCode | StoreCode |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| RemindDate | RemindDate |
| ABGroup | ABGroup |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_EmptyABTestTA_0801] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| SNCCode | SNCCode |
| IsOnJob | IsOnJob |
| StoreCode | StoreCode |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| RemindDate | RemindDate |
| ABgroup | ABgroup |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_EmptyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 招募时间 | 招募时间 |
| 提醒复购时最近购买时间 | 提醒复购时最近购买时间 |
| 提醒复购时最近购买罐数 | 提醒复购时最近购买罐数 |
| 本次提醒复购日期 | 本次提醒复购日期 |
| 本次提醒应空罐日期 | 本次提醒应空罐日期 |
| 空罐日期 | 空罐日期 |

# [MOT_HA_NNSTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Mobile | Mobile |
| TargetType | TargetType |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThiredRemindDate | ThiredRemindDate |
| ForthRemindDate | ForthRemindDate |
| IsNewDate | IsNewDate |
| Status | Status |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_PurchaseS3] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| NoS3Purchase | NoS3Purchase |
| UpdateDate | UpdateDate |

# [MOT_HA_PurchaseS4] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| NoS4Purchase | NoS4Purchase |
| UpdateDate | UpdateDate |

# [MOT_HA_QuestionnaireTag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| QuestionnaireType | QuestionnaireType |
| TagQuestion2_DXW | TagQuestion2_DXW |
| TagQuestion1_C | TagQuestion1_C |
| Tag_DXW_New | Tag_DXW_New |
| CreatedDate | CreatedDate |
| Unionid | Unionid |
| QuestionnaireType | QuestionnaireType |

# [MOT_HA_RecentPurchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| EmptyDay | EmptyDay |
| RemindDay | RemindDay |
| UpdateDate | UpdateDate |

# [MOT_HA_RemindBuy_Overlap] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT_ID |
| MOT_DEF_No | MOT_DEF_No |
| Category | Category |
| TA_CMT_ID | TA_CMT_ID |
| TA_Mobile | TA_Mobile |
| TA_Openid | TA_Openid |
| TA_User_Name | TA_User_Name |
| JoinDate | JoinDate |
| Baby_BirthDay | Baby_BirthDay |
| Stage | Stage |
| Current_Stage | Current_Stage |
| Cross_Stage | Cross_Stage |
| Offset_Day | Offset_Day |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| ON_EC | ON_EC |
| Sent_To_CMT_On | Sent_To_CMT_On |
| Sent_To_CRMPlus_On | Sent_To_CRMPlus_On |
| TAG | TAG |
| Buy_History | Buy_History |
| Due_Date | Due_Date |
| Due_Stage | Due_Stage |
| Status | Status |
| Remark | Remark |
| Created_On | Created_On |
| Modified_On | Modified_On |
| Sent_Update_Status_On | Sent_Update_Status_On |
| SNC_Code_LastBuy | SNC_Code_LastBuy |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| Recent_Buy_Date | Recent_Buy_Date |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| S_Mobile | S_Mobile |
| MOT_PID | MOT_PID |
| Unionid | Unionid |
| TouchPoint | TouchPoint |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| StoreID | StoreID |
| NewCustomerType | NewCustomerType |
| XinkeTag | XinkeTag |
| ON_CSR | ON_CSR |
| Sent_To_CSR_On | Sent_To_CSR_On |

# [MOT_HA_RemindBuyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| 招募时间 | 招募时间 |
| 提醒复购时最近购买时间 | 提醒复购时最近购买时间 |
| 提醒复购时最近购买罐数 | 提醒复购时最近购买罐数 |
| 本次提醒复购日期 | 本次提醒复购日期 |
| 本次提醒应空罐日期 | 本次提醒应空罐日期 |
| 复购次数 | 复购次数 |
| 创建时间 | 创建时间 |
| Unionid | Unionid |
| 复购次数 | 复购次数 |

# [MOT_HA_Review] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_NO | MOT_DEF_NO |
| BeginDate | BeginDate |
| EndDate | EndDate |
| Receive | Receive |
| Success | Success |
| S1 | S1 |
| S2 | S2 |
| S3 | S3 |
| Avg | Avg |

# [MOT_HA_S2_Sample_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Day1_Date | Day1_Date |
| Day3_Date | Day3_Date |
| Is_Buy_HAS2 | Is_Buy_HAS2 |
| Is_PreNAN_User | Is_PreNAN_User |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID | ID |

# [MOT_HA_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| 绑定导购 | 绑定导购 |
| 导购是否在职 | 导购是否在职 |
| 绑定导购门店 | 绑定导购门店 |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| RunDay | RunDay |
| TargetType | TargetType |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| EmptyDay | EmptyDay |
| RemindBuyDate | RemindBuyDate |
| RemindEmptyDate | RemindEmptyDate |
| ReBuyTimes | ReBuyTimes |
| Group | Group |
| NoS3Purchase | NoS3Purchase |
| NoS4Purchase | NoS4Purchase |
| IsNew | IsNew |
| IsNewDate | IsNewDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| Unionid | Unionid |

# [MOT_HA_WOM_OldTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThiredRemindDate | ThiredRemindDate |
| ForthRemindDate | ForthRemindDate |
| FifthRemindDate | FifthRemindDate |
| SixthRemindDate | SixthRemindDate |
| SeventhRemindDate | SeventhRemindDate |
| Status | Status |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |

# [MOT_HA_WOM_OldTA_Wrong] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| FirstRemindDate | FirstRemindDate |
| SecondRemindDate | SecondRemindDate |
| ThiredRemindDate | ThiredRemindDate |
| ForthRemindDate | ForthRemindDate |
| Status | Status |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |

# [MOT_HAS3_720_KAB_TA_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | Current_Day |
| Unionid | Unionid |
| Offset_Day | Offset_Day |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| TA_Mobile | TA_Mobile |
| RegisterChannel | RegisterChannel |
| SUB_USER_NAME | SUB_USER_NAME |
| Baby_BirthDay | Baby_BirthDay |
| current_stage | current_stage |
| Stage | Stage |
| joindate | joindate |
| Tag | Tag |
| Buy_History | Buy_History |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| Touch_Point | Touch_Point |
| Store_Number | Store_Number |
| CreatedOn | CreatedOn |
| is_Maizhi | is_Maizhi |
| ID | ID |

# [MOT_HAS3_760_Laoke_TA_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | Current_Day |
| Unionid | Unionid |
| Offset_Day | Offset_Day |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| TA_Mobile | TA_Mobile |
| RegisterChannel | RegisterChannel |
| SUB_USER_NAME | SUB_USER_NAME |
| Baby_BirthDay | Baby_BirthDay |
| current_stage | current_stage |
| Stage | Stage |
| joindate | joindate |
| Tag | Tag |
| Buy_History | Buy_History |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| Touch_Point | Touch_Point |
| Store_Number | Store_Number |
| Sent2OADate | Sent2OADate |
| CreatedOn | CreatedOn |
| is_month_invalid | is_month_invalid |
| ID | ID |

# [MOT_HAS3_760_Xinke_TA_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | Current_Day |
| Unionid | Unionid |
| Offset_Day | Offset_Day |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| TA_Mobile | TA_Mobile |
| RegisterChannel | RegisterChannel |
| SUB_USER_NAME | SUB_USER_NAME |
| Baby_BirthDay | Baby_BirthDay |
| current_stage | current_stage |
| Stage | Stage |
| joindate | joindate |
| Tag | Tag |
| Buy_History | Buy_History |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| Touch_Point | Touch_Point |
| Store_Number | Store_Number |
| CreatedOn | CreatedOn |
| ID | ID |

# [MOT_ICEF_Sample_Potential_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Potential_Sample_Type | Potential_Sample_Type |
| LastBuy_Date | LastBuy_Date |
| BabyBirthday | BabyBirthday |
| StageByCRM | StageByCRM |
| Buy_ICEF_DATE | Buy_ICEF_DATE |
| Receive_Sample_Date | Receive_Sample_Date |
| InsertMOT_6M | InsertMOT_6M |
| InsertMOT_7M | InsertMOT_7M |
| InsertMOT_8M | InsertMOT_8M |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| Potential_Sample_Type | Potential_Sample_Type |

# [MOT_ICEF_Sample_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| ICEF_Sample_Type | ICEF_Sample_Type |
| Ordernum | Ordernum |
| TouchPoint | TouchPoint |
| StoreCode | StoreCode |
| StoreName | StoreName |
| OrderCreateTime | OrderCreateTime |
| IsReturn | IsReturn |
| Return_ICEF | Return_ICEF |
| Return_Date | Return_Date |
| Buy_ICEF | Buy_ICEF |
| Buy_ICEF_date | Buy_ICEF_date |
| InsertMOT | InsertMOT |
| InsertMOT_Day1 | InsertMOT_Day1 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| ICEF_Sample_Type | ICEF_Sample_Type |

# [MOT_ICEF_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionId | UnionId |
| PSampleDate | PSampleDate |
| ASampleDate | ASampleDate |
| IsBuyPHW | IsBuyPHW |
| IsBuyA2 | IsBuyA2 |
| HALastBuyTime | HALastBuyTime |
| ABLastBuyTime | ABLastBuyTime |
| BabyBirthday | BabyBirthday |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID | ID |

# [MOT_ICEF_TA_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionId | UnionId |
| Tag | Tag |
| PSampleDate | PSampleDate |
| PHW_RunDay | PHW_RunDay |
| ASampleDate | ASampleDate |
| A2_RunDay | A2_RunDay |
| BabyStage | BabyStage |
| BabyStageRunDay | BabyStageRunDay |
| FirstBuyICEF | FirstBuyICEF |
| FirstBuyICEFRunDay | FirstBuyICEFRunDay |
| Is_Recent | Is_Recent |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID | ID |

# [MOT_Incentive_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| FirstBrandTag | FirstBrandTag |
| FirstRemindDate | FirstRemindDate |
| SecondBrandTag | SecondBrandTag |
| SecondRemindDate | SecondRemindDate |
| ThirdBrandTag | ThirdBrandTag |
| ThirdRemindDate | ThirdRemindDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| Unionid | Unionid |

# [MOT_IQC_HA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT_ID |
| MOT_DEF_No | MOT_DEF_No |
| Category | Category |
| TA_CMT_ID | TA_CMT_ID |
| TA_Mobile | TA_Mobile |
| TA_Openid | TA_Openid |
| TA_User_Name | TA_User_Name |
| JoinDate | JoinDate |
| Baby_BirthDay | Baby_BirthDay |
| Stage | Stage |
| Current_Stage | Current_Stage |
| Cross_Stage | Cross_Stage |
| Offset_Day | Offset_Day |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| ON_EC | ON_EC |
| Sent_To_CMT_On | Sent_To_CMT_On |
| Sent_To_CRMPlus_On | Sent_To_CRMPlus_On |
| TAG | TAG |
| Buy_History | Buy_History |
| Due_Date | Due_Date |
| Due_Stage | Due_Stage |
| Status | Status |
| Remark | Remark |
| Created_On | Created_On |
| Modified_On | Modified_On |
| Sent_Update_Status_On | Sent_Update_Status_On |
| SNC_Code_LastBuy | SNC_Code_LastBuy |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| Recent_Buy_Date | Recent_Buy_Date |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| S_Mobile | S_Mobile |
| MOT_PID | MOT_PID |
| Unionid | Unionid |
| TouchPoint | TouchPoint |
| Priority | Priority |
| Generating_Frequency | Generating_Frequency |
| StoreID | StoreID |
| NewCustomerType | NewCustomerType |
| XinkeTag | XinkeTag |
| ON_CSR | ON_CSR |
| Sent_To_CSR_On | Sent_To_CSR_On |
| ExternalUserID | ExternalUserID |
| WeChatName | WeChatName |
| Avatar | Avatar |
| Is_Pushed | Is_Pushed |
| MOT_ID | MOT_ID |

# [MOT_IQC_HA_Buy_Scan_Tar] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Mobile | Mobile |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| SUB_USER_NAME | SUB_USER_NAME |
| joindate | joindate |
| Baby_BirthDay | Baby_BirthDay |
| Buy_Stage | Buy_Stage |
| Current_stage | Current_stage |
| Offset_Day | Offset_Day |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| TAG | TAG |
| Store_Number | Store_Number |
| ON_CRM_Plus | ON_CRM_Plus |
| TankBarCode | TankBarCode |
| Buy_RN | Buy_RN |
| 购买日期 | 购买日期 |
| BuyTime | BuyTime |
| Can_Count | Can_Count |
| QRCode_Internal | QRCode_Internal |
| QrCode | QrCode |
| Scanning_Time | Scanning_Time |
| Scan_Brand | Scan_Brand |
| Scan_Stage | Scan_Stage |
| Scan_TA_User_Name | Scan_TA_User_Name |
| Scan_RN | Scan_RN |
| MAX_ScanRN | MAX_ScanRN |
| FirstScanIsHA | FirstScanIsHA |
| ProductCode | ProductCode |
| Create_Time | Create_Time |
| Last_Modify_Time | Last_Modify_Time |
| Product_Stage | Product_Stage |
| ID | ID |

# [MOT_IQC_HA_Buy_Scan_Tar_V2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Mobile | Mobile |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| SUB_USER_NAME | SUB_USER_NAME |
| joindate | joindate |
| Baby_BirthDay | Baby_BirthDay |
| Buy_Stage | Buy_Stage |
| Current_stage | Current_stage |
| Offset_Day | Offset_Day |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| TAG | TAG |
| Store_Number | Store_Number |
| ON_CRM_Plus | ON_CRM_Plus |
| TankBarCode | TankBarCode |
| Buy_RN | Buy_RN |
| 购买日期 | 购买日期 |
| BuyTime | BuyTime |
| Can_Count | Can_Count |
| QRCode_Internal | QRCode_Internal |
| QrCode | QrCode |
| Scanning_Time | Scanning_Time |
| Scan_Brand | Scan_Brand |
| Scan_Stage | Scan_Stage |
| Scan_TA_User_Name | Scan_TA_User_Name |
| Scan_RN | Scan_RN |
| MAX_ScanRN | MAX_ScanRN |
| FirstScanIsHA | FirstScanIsHA |
| ProductCode | ProductCode |
| Create_Time | Create_Time |
| Last_Modify_Time | Last_Modify_Time |
| Product_Stage | Product_Stage |
| ID | ID |

# [MOT_JD_CallBackTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | ExternalUserId |
| TargetType | TargetType |
| Openid | Openid |
| Executor | Executor |
| ReBuyTimes | ReBuyTimes |
| RemindBuyDate | RemindBuyDate |
| RemindBuyDateUpdate | RemindBuyDateUpdate |
| Status | Status |
| CallBackDate | CallBackDate |
| CampaleteDate | CampaleteDate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| ExternalUserId | ExternalUserId |
| TargetType | TargetType |

# [MOT_JD_HighPotentialTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | ExternalUserId |
| RunDay | RunDay |
| Executor | Executor |
| TagName | TagName |
| TagCreateTime | TagCreateTime |
| IsBeDevelopingTA | IsBeDevelopingTA |
| BeDevelopingDate | BeDevelopingDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| ExternalUserId | ExternalUserId |
| TagName | TagName |

# [MOT_JD_PurchaseTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| ExternalUserId | ExternalUserId |
| Executor | Executor |
| TargetType | TargetType |
| RunDay | RunDay |
| PurchaseGroup | PurchaseGroup |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| RemindBuyDate | RemindBuyDate |
| ReBuyTimes | ReBuyTimes |
| BeDevelopingTADate | BeDevelopingTADate |
| BeLoyalTADate | BeLoyalTADate |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| ExternalUserId | ExternalUserId |
| TargetType | TargetType |

# [MOT_JD_RecentPurchase_HA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UserLogAcct | UserLogAcct |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| UpdateDate | UpdateDate |
| UserLogAcct | UserLogAcct |

# [MOT_JD_RecentPurchase_PreNan] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| userLogAcct | userLogAcct |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| UpdateDate | UpdateDate |

# [MOT_JD_RemindBuyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | ExternalUserId |
| TargetType | TargetType |
| Openid | Openid |
| Executor | Executor |
| RecruitDate | RecruitDate |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindBuyDate | RemindBuyDate |
| ReBuyTimes | ReBuyTimes |
| Status | Status |
| CreatedDate | CreatedDate |
| ExternalUserId | ExternalUserId |
| TargetType | TargetType |
| ReBuyTimes | ReBuyTimes |

# [MOT_Member_Temp] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CMT_ID | CMT_ID |
| Openid | Openid |
| Unionid | Unionid |
| Mobile | Mobile |
| SUB_USER_NAME | SUB_USER_NAME |
| SNC_Code | SNC_Code |
| JoinDate | JoinDate |
| Current_Stage | Current_Stage |
| StageByCRM | StageByCRM |
| Always_Follow | Always_Follow |
| Refollow | Refollow |
| RegisterChannel | RegisterChannel |
| Specialty | Specialty |
| Tag | Tag |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| SNC_Code_Show_TOB | SNC_Code_Show_TOB |
| babyBirthday | babyBirthday |
| PreNAN_Recruit_BabyBirthDay | PreNAN_Recruit_BabyBirthDay |
| Offset_Day | Offset_Day |
| First_week | First_week |
| HA_RecruitTime | HA_RecruitTime |
| AL110_RecruitTime | AL110_RecruitTime |
| PreNAN_RecruitTime | PreNAN_RecruitTime |
| Specialty_Al110 | Specialty_Al110 |
| Specialty_PreNan | Specialty_PreNan |
| GC_PT_RecruitTime | GC_PT_RecruitTime |
| GC_LN_RecruitTime | GC_LN_RecruitTime |
| PreNAN_Wight | PreNAN_Wight |
| Recent_Buy_SNC | Recent_Buy_SNC |
| RECENT_BUY_PRODUCT_BRAND | RECENT_BUY_PRODUCT_BRAND |
| RECENT_BUY_PRODUCT_STAGE | RECENT_BUY_PRODUCT_STAGE |
| RECENT_BUY_PRODUCT_NET_WEIGHT | RECENT_BUY_PRODUCT_NET_WEIGHT |
| RECENT_BUY_PRODUCT_Qty | RECENT_BUY_PRODUCT_Qty |
| Recent_Buy_Product_BUYTIME | Recent_Buy_Product_BUYTIME |
| Recent_Buy_Product_ProductCode | Recent_Buy_Product_ProductCode |
| Recent_Buy_Product_ProductName | Recent_Buy_Product_ProductName |
| Recent_Buy_AL110_Is_First | Recent_Buy_AL110_Is_First |
| Recent_Buy_HA_S1S2_Is_First | Recent_Buy_HA_S1S2_Is_First |
| Recent_Buy_PT_S1S2_Is_First | Recent_Buy_PT_S1S2_Is_First |
| Recent_Buy_NAN_S1S2_Is_First | Recent_Buy_NAN_S1S2_Is_First |
| Recent_Buy_PreNAN_Is_First | Recent_Buy_PreNAN_Is_First |
| Recent_Buy_CMPA_Is_First | Recent_Buy_CMPA_Is_First |
| NON_PURCHASE_IMF | NON_PURCHASE_IMF |
| Recent_Buy_Store | Recent_Buy_Store |
| PREGNANT_Baby6M | PREGNANT_Baby6M |
| CreatedOn | CreatedOn |

# [MOT_PreNan_RecentPurchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| EmptyDay | EmptyDay |
| RemindDay | RemindDay |
| UpdateDate | UpdateDate |

# [MOT_PreNan_RemindBuyTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |
| RecruitDate | RecruitDate |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindBuyDate | RemindBuyDate |
| RemindEmptyDate | RemindEmptyDate |
| CreatedDate | CreatedDate |
| Unionid | Unionid |
| ReBuyTimes | ReBuyTimes |

# [MOT_PreNan_TagTable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| StageByCRM | StageByCRM |
| Offset_Day | Offset_Day |
| Is_Weight | Is_Weight |
| RunDay | RunDay |
| RecruitDate | RecruitDate |
| RecruitTin | RecruitTin |
| RecentPurchaseDate | RecentPurchaseDate |
| RecentPurchaseTin | RecentPurchaseTin |
| RemindDay | RemindDay |
| EmptyDay | EmptyDay |
| RemindBuyDate | RemindBuyDate |
| RemindEmptyDate | RemindEmptyDate |
| ReBuyTimes | ReBuyTimes |
| UpdateDate | UpdateDate |
| CreatedDate | CreatedDate |
| JourneyEndDate | JourneyEndDate |
| Unionid | Unionid |

# [MOT_Products_Info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |
| CategoryCode | CategoryCode |
| Anti_Cheating | Anti_Cheating |
| is_spark_sale | is_spark_sale |
| is_report | is_report |
| report_period | report_period |
| RRP | RRP |
| ProductCode | ProductCode |

# [MOT_Products_Info_20221011] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |

# [MOT_Products_Info_20231211] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |

# [MOT_Products_Info_20240105] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |

# [MOT_Products_Info_20240115] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |

# [MOT_Products_Info_20250120] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |
| CategoryCode | CategoryCode |
| Anti_Cheating | Anti_Cheating |
| is_spark_sale | is_spark_sale |

# [MOT_Products_Info_20250416] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |
| CategoryCode | CategoryCode |
| Anti_Cheating | Anti_Cheating |
| is_spark_sale | is_spark_sale |
| is_report | is_report |
| report_period | report_period |

# [MOT_Products_Info_20250416_Earl] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| Price | Price |

# [MOT_Products_Info_20250417_Earl] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| Price | Price |

# [MOT_Products_Info_20250528_Jonathan] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Stage | Stage |
| NetWeight | NetWeight |
| NPS_Price | NPS_Price |
| RRP_Price | RRP_Price |
| Specifications | Specifications |
| CreatedOn | CreatedOn |
| ProductCode | ProductCode |

# [MOT_Products_Info_20250603_Jonathan] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_20250613_Vicy] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| NPS | NPS |

# [MOT_Products_Info_20250619_Vicky] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_20250630] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| ProductShortName | ProductShortName |
| NewCustomerType | NewCustomerType |
| NewCustomerType2022 | NewCustomerType2022 |
| Premium_2022 | Premium_2022 |
| Brand | Brand |
| Stage | Stage |
| MS_GP_Tag | MS_GP_Tag |
| NetWeight | NetWeight |
| Price | Price |
| Specifications | Specifications |
| ConsumeDay | ConsumeDay |
| Comments | Comments |
| Enable | Enable |
| NSC | NSC |
| IMF | IMF |
| NIN | NIN |
| Gerber | Gerber |
| Gerber_Stage | Gerber_Stage |
| Gerber_Type | Gerber_Type |
| WeShop | WeShop |
| LastChange | LastChange |
| CreatedOn | CreatedOn |
| Premium | Premium |
| CategoryCode | CategoryCode |
| Anti_Cheating | Anti_Cheating |
| is_spark_sale | is_spark_sale |
| is_report | is_report |
| report_period | report_period |
| RRP | RRP |

# [MOT_Products_Info_20250630_Vicky] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| 2025年有无销售额产品 | 2025年有无销售额产品 |
| productname | productname |
| NPS 价格（商家端当前价格） | NPS 价格（商家端当前价格） |
| NPS价格（Vicky） | NPS价格（Vicky） |
| RRP价格（Vicky） | RRP价格（Vicky） |

# [MOT_Products_info_20250704_Earl] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_Gerber] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| MaterialDescription | MaterialDescription |
| ChineseDescription | ChineseDescription |
| 中文简称 | 中文简称 |
| 产品分类 | 产品分类 |
| 产品单价 | 产品单价 |
| 产品规格 | 产品规格 |
| 整箱价格 | 整箱价格 |
| 状态 | 状态 |
| 克重数 | 克重数 |
| 净重单位 | 净重单位 |
| 单罐使用时间(天) | 单罐使用时间(天) |
| 销售分类 | 销售分类 |
| 目标分类 | 目标分类 |
| 品牌名称 | 品牌名称 |
| 产品类别名称 | 产品类别名称 |
| CreatedOn | CreatedOn |
| ProductCode | ProductCode |

# [MOT_Products_Info_Sanyar] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Stage | Stage |
| NetWeight | NetWeight |
| Day | Day |
| Comments | Comments |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [MOT_Products_NSC_20220223] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| 产品简称 | 产品简称 |
| 产品名称 | 产品名称 |
| 产品品牌 | 产品品牌 |
| 产品段位 | 产品段位 |
| 售卖渠道 | 售卖渠道 |
| 产品原单价 | 产品原单价 |
| 产品指导价 | 产品指导价 |
| nsc | nsc |
| Premium_2022 | Premium_2022 |
| F11 | F11 |

# [MOT_UGU_Relation] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_ID | SNC_ID |
| UnionID | UnionID |
| MOT_ID | MOT_ID |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Brand | Brand |
| ID | ID |

# [MOT_UGU_Relation_Detail] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_ID | SNC_ID |
| Source_UnionID | Source_UnionID |
| Target_UnionID | Target_UnionID |
| MOT_ID | MOT_ID |
| Invite_Date | Invite_Date |
| Status | Status |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Brand | Brand |
| ID | ID |

# [NEW_Mama] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| KSFId | KSFId |
| MamaName | MamaName |
| Birthday | Birthday |
| Gender | Gender |
| PostalCode | PostalCode |
| AddressHead | AddressHead |
| AddressTail | AddressTail |
| JoinTime | JoinTime |
| HomeTel | HomeTel |
| OfficeTel | OfficeTel |
| OtherTel | OtherTel |
| Mobile | Mobile |
| DefaultTelType | DefaultTelType |
| HotelineKnowWay | HotelineKnowWay |
| IsRefusedAll | IsRefusedAll |
| IsFollowedWechatCTM | IsFollowedWechatCTM |
| IsBandWechatCTM | IsBandWechatCTM |
| IsAcceptedCall | IsAcceptedCall |
| IsAcceptedMail | IsAcceptedMail |
| IsAcceptedEmail | IsAcceptedEmail |
| IsAcceptedSMS | IsAcceptedSMS |
| Remark | Remark |
| IsMember | IsMember |
| MemberCardNo | MemberCardNo |
| IdentityNumber | IdentityNumber |
| Company | Company |
| Job | Job |
| CheccId | CheccId |
| CMTId | CMTId |
| LogBatchId | LogBatchId |
| WebUserId | WebUserId |
| WebDataSource | WebDataSource |
| Email | Email |
| WechatNo | WechatNo |
| WeiboNo | WeiboNo |
| RegisterMobile | RegisterMobile |
| PregnantStatus | PregnantStatus |
| HasAllergy | HasAllergy |
| CMTKnowWay | CMTKnowWay |
| Interests | Interests |
| IsPass | IsPass |
| NoPassReason | NoPassReason |
| IsCMTCall | IsCMTCall |
| BabyEDC | BabyEDC |
| IsCallCount | IsCallCount |
| ImportDate | ImportDate |
| Frozen | Frozen |
| SubscribeSource | SubscribeSource |
| SubscribeTime | SubscribeTime |
| RegisterChannel | RegisterChannel |
| OperationFlag | OperationFlag |
| CreatedOn | CreatedOn |
| CreatedBy | CreatedBy |
| ModifiedOn | ModifiedOn |
| ModifiedBy | ModifiedBy |
| IsRegistered | IsRegistered |
| PDateProcessed | PDateProcessed |
| PDateCreated | PDateCreated |
| ActivityChannel | ActivityChannel |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [NINqrcode_Point] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pid | pid |
| id | id |
| materialId | materialId |
| code | code |
| parentCode | parentCode |
| marketingCode | marketingCode |
| type | type |
| target | target |
| createTime | createTime |
| createdOn | createdOn |
| lastChange | lastChange |
| Remark | Remark |
| pid | pid |

# [NSC_Blacked_Xinke_List] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| CreatedOn | CreatedOn |
| Unionid | Unionid |

# [NSC_BlackedList_HA_42] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionID | UnionID |
| Category | Category |
| CreatedOn | CreatedOn |
| ID | ID |

# [NSC_BlackedList_SNC] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S_Mobile |
| Name | Name |
| Role | Role |
| TouchPoint | TouchPoint |
| Enabled | Enabled |
| Remark | Remark |
| CreatedOn | CreatedOn |
| MoidifiedOn | MoidifiedOn |
| ID | ID |

# [NSC_BlackedList_SNC_20240617] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S_Mobile |
| Name | Name |
| Role | Role |
| TouchPoint | TouchPoint |
| Enabled | Enabled |
| Remark | Remark |
| CreatedOn | CreatedOn |
| MoidifiedOn | MoidifiedOn |

# [NSC_BochuS23_Sample] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | StoreCode |
| Month | Month |
| SampleQuota | SampleQuota |
| SampleQuotaStore | SampleQuotaStore |
| SampleReceived | SampleReceived |
| SampleImport | SampleImport |
| SampleExport | SampleExport |
| SampleUsage | SampleUsage |
| SampleLeft | SampleLeft |
| SampleType | SampleType |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| StoreCode | StoreCode |
| Month | Month |
| SampleType | SampleType |

# [NSC_BochuS23_Sample_ToB] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | Month |
| StoreCode | StoreCode |
| SampleQuota | SampleQuota |
| SampleReceived | SampleReceived |
| SampleUsage | SampleUsage |
| SampleLeft | SampleLeft |
| SampleType | SampleType |
| Month | Month |
| StoreCode | StoreCode |
| SampleType | SampleType |

# [NSC_BochuSample_Info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MaterialNumber | MaterialNumber |
| MaterialName | MaterialName |
| EACode | EACode |
| CaseCode | CaseCode |
| ManuDate | ManuDate |
| ExpiryDate | ExpiryDate |
| ImportDate | ImportDate |
| StoreCode | StoreCode |
| TouchPoint | TouchPoint |
| SellStatus | SellStatus |
| OrderNum | OrderNum |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID | ID |

# [NSC_CallLog_PostYS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | CallSeqNo |
| AgentId | AgentId |
| mid | mid |
| store_number | store_number |
| StartTime | StartTime |
| EndTime | EndTime |
| CallType | CallType |
| CallQuestion | CallQuestion |
| CallResult | CallResult |
| Name | Name |
| MobileTel | MobileTel |
| ShopOwner | ShopOwner |
| Memo | Memo |
| CreateTime | CreateTime |
| Recruitment | Recruitment |
| RecruitmentRemark | RecruitmentRemark |
| Retention | Retention |
| RetentionRemark | RetentionRemark |
| TaskFinish | TaskFinish |
| TaskFinishRemark | TaskFinishRemark |
| RefusalReason | RefusalReason |
| Temp1 | Temp1 |
| Temp2 | Temp2 |
| Temp3 | Temp3 |
| Temp4 | Temp4 |
| Temp5 | Temp5 |
| CreatedOn | CreatedOn |
| CallMonth | CallMonth |
| IsEWCSend | IsEWCSend |
| IsEWCConnect | IsEWCConnect |
| CallSeqNo | CallSeqNo |

# [NSC_CRMPlus_KuaiShanQun] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| QunId | QunId |
| QunName | QunName |
| EnterTime | EnterTime |
| QuitTime | QuitTime |
| Remark | Remark |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| QunId | QunId |

# [NSC_Data_QuizTag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Openid | Openid |
| Mobile | Mobile |
| 安儿宁_便便档案_样便 | 安儿宁_便便档案_样便 |
| 安儿宁_便便档案_巩固使用 | 安儿宁_便便档案_巩固使用 |
| 安儿宁_便便档案_痊愈转奶 | 安儿宁_便便档案_痊愈转奶 |
| 用户画像_喂养方式 | 用户画像_喂养方式 |
| 用户画像_曾用品牌 | 用户画像_曾用品牌 |
| 用户画像_AL110使用 | 用户画像_AL110使用 |
| 用户画像_其他不适 | 用户画像_其他不适 |
| 用户画像_营养补剂 | 用户画像_营养补剂 |
| 用户画像_态度 | 用户画像_态度 |
| 用户画像_过敏风险 | 用户画像_过敏风险 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Quiz_No | Quiz_No |
| 安儿宁_宝宝康复随访_持续使用 | 安儿宁_宝宝康复随访_持续使用 |
| 安儿宁_宝宝康复随访_巩固使用 | 安儿宁_宝宝康复随访_巩固使用 |
| 安儿宁_宝宝康复随访_痊愈转奶 | 安儿宁_宝宝康复随访_痊愈转奶 |
| 安儿宁_长期营养方案_持续使用 | 安儿宁_长期营养方案_持续使用 |
| 安儿宁_长期营养方案_喂养方式 | 安儿宁_长期营养方案_喂养方式 |
| 安儿宁_长期营养方案_痊愈转奶 | 安儿宁_长期营养方案_痊愈转奶 |
| 用户画像_关注奶粉特点 | 用户画像_关注奶粉特点 |
| 早启能恩_生长发育档案_持续使用 | 早启能恩_生长发育档案_持续使用 |
| 早启能恩_生长发育档案_转奶 | 早启能恩_生长发育档案_转奶 |
| 早启能恩_成长情况随访_持续使用 | 早启能恩_成长情况随访_持续使用 |
| 早启能恩_成长情况随访_巩固使用 | 早启能恩_成长情况随访_巩固使用 |
| 早启能恩_成长情况随访_转奶 | 早启能恩_成长情况随访_转奶 |
| 早启能恩_长期营养方案评估_持续使用 | 早启能恩_长期营养方案评估_持续使用 |
| 早启能恩_长期营养方案评估_转奶 | 早启能恩_长期营养方案评估_转奶 |
| 早启能恩_用户画像_杏仁早到天使平台会员 | 早启能恩_用户画像_杏仁早到天使平台会员 |
| 早启能恩_用户画像_出生孕周数 | 早启能恩_用户画像_出生孕周数 |
| 早启能恩_用户画像_关注问题 | 早启能恩_用户画像_关注问题 |
| 早启能恩_用户画像_体重 | 早启能恩_用户画像_体重 |
| 早启能恩_用户画像_其他不适 | 早启能恩_用户画像_其他不适 |
| 早启能恩_用户画像_营养补剂 | 早启能恩_用户画像_营养补剂 |
| 早启能恩_用户画像_长期喂养态度 | 早启能恩_用户画像_长期喂养态度 |
| 早启能恩_用户画像_过敏风险 | 早启能恩_用户画像_过敏风险 |
| 早启能恩_用户画像_关注奶粉特点 | 早启能恩_用户画像_关注奶粉特点 |
| Quiz_No_PreNAN | Quiz_No_PreNAN |
| Quiz_No_HA | Quiz_No_HA |
| 超启能恩_防敏档案_持续使用 | 超启能恩_防敏档案_持续使用 |
| 超启能恩_防敏档案_巩固使用 | 超启能恩_防敏档案_巩固使用 |
| 超启能恩_防敏随访_持续使用 | 超启能恩_防敏随访_持续使用 |
| 超启能恩_防敏随访_巩固使用 | 超启能恩_防敏随访_巩固使用 |
| 超启能恩_防敏随访_痊愈转奶 | 超启能恩_防敏随访_痊愈转奶 |
| 超启能恩_长期营养方案评估_持续使用 | 超启能恩_长期营养方案评估_持续使用 |
| 超启能恩_长期营养方案评估_转奶 | 超启能恩_长期营养方案评估_转奶 |
| 超启能恩_用户画像_喂养方式 | 超启能恩_用户画像_喂养方式 |
| 超启能恩_用户画像_曾用产品 | 超启能恩_用户画像_曾用产品 |
| 超启能恩_用户画像_曾用品牌 | 超启能恩_用户画像_曾用品牌 |
| 超启能恩_用户画像_防敏档案过敏风险 | 超启能恩_用户画像_防敏档案过敏风险 |
| 超启能恩_用户画像_仍使用超启能恩 | 超启能恩_用户画像_仍使用超启能恩 |
| 超启能恩_用户画像_其他不适 | 超启能恩_用户画像_其他不适 |
| 超启能恩_用户画像_营养补剂 | 超启能恩_用户画像_营养补剂 |
| 超启能恩_用户画像_长期喂养态度 | 超启能恩_用户画像_长期喂养态度 |
| 超启能恩_用户画像_关注奶粉特点 | 超启能恩_用户画像_关注奶粉特点 |
| 超启能恩_用户画像_长期营养方案评估过敏风险 | 超启能恩_用户画像_长期营养方案评估过敏风险 |
| Quiz_No_CMPA | Quiz_No_CMPA |
| 完整牛奶蛋白过敏_过敏档案_使用产品 | 完整牛奶蛋白过敏_过敏档案_使用产品 |
| 完整牛奶蛋白过敏_过敏档案_使用时间 | 完整牛奶蛋白过敏_过敏档案_使用时间 |
| 完整牛奶蛋白过敏_过敏随访_持续使用 | 完整牛奶蛋白过敏_过敏随访_持续使用 |
| 完整牛奶蛋白过敏_过敏随访_痊愈转奶 | 完整牛奶蛋白过敏_过敏随访_痊愈转奶 |
| 完整牛奶蛋白过敏_过敏随访_诊断康复 | 完整牛奶蛋白过敏_过敏随访_诊断康复 |
| 完整牛奶蛋白过敏_用户画像_诊断结论 | 完整牛奶蛋白过敏_用户画像_诊断结论 |
| 完整牛奶蛋白过敏_用户画像_曾用品牌 | 完整牛奶蛋白过敏_用户画像_曾用品牌 |
| 完整牛奶蛋白过敏_用户画像_担心问题 | 完整牛奶蛋白过敏_用户画像_担心问题 |
| Unionid | Unionid |

# [NSC_Data_QuizTag_AL110] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Openid | Openid |
| Mobile | Mobile |
| 宝宝状态_注册信息 | 宝宝状态_注册信息 |
| 宝宝状态_恢复情况 | 宝宝状态_恢复情况 |
| 宝宝状态_康复期 | 宝宝状态_康复期 |
| 用户画像_喂养方式 | 用户画像_喂养方式 |
| 用户画像_曾用品牌 | 用户画像_曾用品牌 |
| 用户画像_AL110使用 | 用户画像_AL110使用 |
| 用户画像_其他不适 | 用户画像_其他不适 |
| 用户画像_营养补剂 | 用户画像_营养补剂 |
| 用户画像_态度 | 用户画像_态度 |
| 用户画像_过敏风险 | 用户画像_过敏风险 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Quiz_No | Quiz_No |
| SentToCRMOn | SentToCRMOn |
| Unionid | Unionid |

# [NSC_Exclude_Order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| OrderNum | OrderNum |
| CreatedOn | CreatedOn |

# [NSC_HA400g] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Mobile | Mobile |
| SalesID | SalesID |
| Buytime | Buytime |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Openid | Openid |
| Mobile | Mobile |

# [NSC_HCP_Status] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Recruit_Time | Recruit_Time |
| Member_Type | Member_Type |
| HCP_Active_Expired_Time | HCP_Active_Expired_Time |
| HCP_Active_Time | HCP_Active_Time |
| HCP_Expired_Time | HCP_Expired_Time |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| Member_Type | Member_Type |

# [NSC_ICEF_Q3_TA_Store] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | StoreCode |
| StoreName | StoreName |
| Enable | Enable |
| CreatedOn | CreatedOn |
| ID | ID |

# [NSC_MOT_WeCom_Action] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT_ID |
| Unionid | Unionid |
| MOT_DEF_No | MOT_DEF_No |
| SNC_NO | SNC_NO |
| CSR_NO | CSR_NO |
| Action_SNC_CSR | Action_SNC_CSR |
| SendDateTime | SendDateTime |
| ClickDateTime | ClickDateTime |
| GroupType | GroupType |
| GroupID | GroupID |
| Status | Status |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| MOT_ID | MOT_ID |

# [NSC_NET_IsVaild_Sign] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| User_Code | User_Code |
| SignTime | SignTime |
| CreatedDate | CreatedDate |
| UpdateDate | UpdateDate |
| ID | ID |

# [NSC_NET_MMClass] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| openid | openid |
| user_code | user_code |
| ssr_code | ssr_code |
| mobile | mobile |
| create_date | create_date |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| unionid | unionid |

# [NSC_Q_Logs] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Method | Method |
| Unionid | Unionid |
| MetCompliance | MetCompliance |
| Babybirthday | Babybirthday |
| CreatedOn | CreatedOn |
| ID | ID |

# [NSC_QRCode] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode | QRCode |
| ParentCode | ParentCode |
| MarketingCode | MarketingCode |
| ProductCode | ProductCode |
| BatchNumber | BatchNumber |
| ManufactureDate | ManufactureDate |
| PlantCode | PlantCode |
| PlantName | PlantName |
| CreatedTime | CreatedTime |
| WH | WH |
| WHName | WHName |
| Scantype | Scantype |
| Shipto | Shipto |
| ShiptoName | ShiptoName |
| JXS_IN_TransTime | JXS_IN_TransTime |
| JXS_ProcessingTime | JXS_ProcessingTime |
| JXS_TransID | JXS_TransID |
| JXS_CustomerNumber | JXS_CustomerNumber |
| JXS_CustomerName | JXS_CustomerName |
| JXS_Type | JXS_Type |
| JXS_BU | JXS_BU |
| JXS_MaterialName | JXS_MaterialName |
| JXS_BatchNumber | JXS_BatchNumber |
| JXS_Note | JXS_Note |
| JXS_IN_OutletCode | JXS_IN_OutletCode |
| JXS_IN_OutletName | JXS_IN_OutletName |
| JXS_Region | JXS_Region |
| JXS_Province | JXS_Province |
| JXS_Out_TransTime | JXS_Out_TransTime |
| JXS_Out_OutletCode | JXS_Out_OutletCode |
| JXS_Out_OutletName | JXS_Out_OutletName |
| QRCode | QRCode |

# [NSC_QrCode_Internal] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | QRCode_Internal |
| QrCode | QrCode |
| Scanning_Time | Scanning_Time |
| Unionid | Unionid |
| CreatedOn | CreatedOn |
| Sent2CRMPlusOn | Sent2CRMPlusOn |
| Code_Type | Code_Type |
| Is_Gift | Is_Gift |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Stage | Stage |
| Sales_Channel | Sales_Channel |
| Platform | Platform |
| QRCode_Internal | QRCode_Internal |

# [NSC_QRCode_Internal_Backup] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | QRCode_Internal |
| CreatedOn | CreatedOn |
| Type | Type |
| QRCode_Internal | QRCode_Internal |

# [NSC_QrCode_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | StoreCode |
| StoreName | StoreName |
| ScanCode | ScanCode |
| ScanRole | ScanRole |
| ScanName | ScanName |
| Region | Region |
| Province | Province |
| CG | CG |
| City | City |
| OAH | OAH |
| IsSpark | IsSpark |
| Toupoint | Toupoint |
| Source | Source |
| PID | PID |
| QRCode | QRCode |
| IsReturn | IsReturn |
| CanBeSell | CanBeSell |
| Payload | Payload |
| Response | Response |
| CreatedOn | CreatedOn |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Sells_CanBeSell | Sells_CanBeSell |
| Sells_SNCCode | Sells_SNCCode |
| Sells_SNCName | Sells_SNCName |
| Sells_StoreCode | Sells_StoreCode |
| Sells_Youdao | Sells_Youdao |
| Sells_OAH | Sells_OAH |
| Sells_Buytime | Sells_Buytime |
| Sells_Spark | Sells_Spark |
| Sells_StoreName | Sells_StoreName |
| ka_type | ka_type |
| ka_channel | ka_channel |
| ID | ID |

# [NSC_Recent_Purchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| Unionid | Unionid |
| S_Mobile | S_Mobile |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Brand | Brand |
| Qty | Qty |
| Buytime | Buytime |
| Source | Source |
| SncCode | SncCode |
| SncName | SncName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| SentToCRMOn | SentToCRMOn |
| LastChange | LastChange |
| PID | PID |

# [NSC_RetentionToYS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | CallSeqNo |
| CampaignID | CampaignID |
| Call_Time | Call_Time |
| NewCustomerType | NewCustomerType |
| Recruit_Brand | Recruit_Brand |
| Recruit_Stage | Recruit_Stage |
| Recruit_Date | Recruit_Date |
| BabyBirthday | BabyBirthday |
| OB_Call_Date | OB_Call_Date |
| Retention_Stage | Retention_Stage |
| Is_Retention | Is_Retention |
| Retain_brand | Retain_brand |
| Churn_Reason1 | Churn_Reason1 |
| Churn_Reason2 | Churn_Reason2 |
| Churn_Brand | Churn_Brand |
| Use_Month | Use_Month |
| Store_Number | Store_Number |
| SSRCode | SSRCode |
| KsfId | KsfId |
| Unionid | Unionid |
| Mobile | Mobile |
| MamaId | MamaId |
| ProductCode | ProductCode |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| 是否有导 | 是否有导 |
| CallSeqNo | CallSeqNo |

# [NSC_RetentionToYS_20240711] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | CallSeqNo |
| CampaignID | CampaignID |
| Call_Time | Call_Time |
| NewCustomerType | NewCustomerType |
| Recruit_Brand | Recruit_Brand |
| Recruit_Stage | Recruit_Stage |
| Recruit_Date | Recruit_Date |
| BabyBirthday | BabyBirthday |
| OB_Call_Date | OB_Call_Date |
| Retention_Stage | Retention_Stage |
| Is_Retention | Is_Retention |
| Retain_brand | Retain_brand |
| Churn_Reason1 | Churn_Reason1 |
| Churn_Reason2 | Churn_Reason2 |
| Churn_Brand | Churn_Brand |
| Use_Month | Use_Month |
| Store_Number | Store_Number |
| SSRCode | SSRCode |
| KsfId | KsfId |
| Unionid | Unionid |
| Mobile | Mobile |
| MamaId | MamaId |
| ProductCode | ProductCode |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [NSC_SALESMAN] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| mid | mid |
| sid | sid |
| openid | openid |
| qrcode | qrcode |
| qrcode_gb | qrcode_gb |
| type | type |
| area_name | area_name |
| province | province |
| city | city |
| name | name |
| tel | tel |
| store_name | store_name |
| store_number | store_number |
| store_type | store_type |
| store_tag | store_tag |
| serial_number | serial_number |
| city_group | city_group |
| is_crm | is_crm |
| is_onjob | is_onjob |
| isdel | isdel |
| supervisor_number | supervisor_number |
| supervisor_name | supervisor_name |
| supervisor_tel | supervisor_tel |
| citylevel | citylevel |
| ka_type | ka_type |
| ka_name | ka_name |
| split_account | split_account |
| status | status |
| tob_group | tob_group |
| address | address |
| license | license |
| distributor | distributor |
| ctime | ctime |
| store_ctime | store_ctime |
| shopowner | shopowner |
| vip_level | vip_level |
| unionid | unionid |
| license_upload_date | license_upload_date |
| LastChange | LastChange |
| modified_on | modified_on |
| vip_level_remark | vip_level_remark |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Spark_Store | Spark_Store |
| mid | mid |

# [NSC_Scan_Errorlog] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| store_number | store_number |
| serial_number | serial_number |
| store_distributor | store_distributor |
| spark_store | spark_store |
| openid | openid |
| unionid | unionid |
| code | code |
| code_distributor | code_distributor |
| productcode | productcode |
| CreatedOn | CreatedOn |
| id | id |

# [NSC_Spark_Activity_Tag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFId |
| unionid | unionid |
| id | id |
| title | title |
| scan_date | scan_date |
| sdate | sdate |
| edate | edate |
| store_number | store_number |
| activity_no | activity_no |
| activity_type | activity_type |
| user_code | user_code |
| user_name | user_name |
| activity_date | activity_date |
| NewCustomertype | NewCustomertype |
| Joindate | Joindate |
| is_spark | is_spark |
| CreatedOn | CreatedOn |
| KSFId | KSFId |

# [NSC_Spark_Activity_Tag_2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFId |
| Unionid | Unionid |
| activity_id | activity_id |
| activity_title | activity_title |
| scan_date | scan_date |
| sdate | sdate |
| edate | edate |
| store_number | store_number |
| NewCustomertype | NewCustomertype |
| Joindate | Joindate |
| CreatedOn | CreatedOn |
| Unionid | Unionid |

# [NSC_Spark_Store_Current] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | Month |
| Region | Region |
| CG | CG |
| Cus_Name | Cus_Name |
| Cus_Code | Cus_Code |
| TCDS_Code | TCDS_Code |
| Source | Source |
| Store_Code | Store_Code |
| Store_Name | Store_Name |
| Store_SJJH_Tins | Store_SJJH_Tins |
| Store_SJCK_Tins | Store_SJCK_Tins |
| Store_JinHuo_Tins | Store_JinHuo_Tins |
| Store_ZhuiHui_Tins | Store_ZhuiHui_Tins |
| Store_ChuKu_Tins | Store_ChuKu_Tins |
| Store_TuiDan_Tins | Store_TuiDan_Tins |
| Store_KuCun_Tins | Store_KuCun_Tins |
| Store_JinHuo_Offtake | Store_JinHuo_Offtake |
| Store_ZhuiHui_Offtake | Store_ZhuiHui_Offtake |
| Store_ChuKu_Offtake | Store_ChuKu_Offtake |
| Store_TuiDan_Offtake | Store_TuiDan_Offtake |
| Store_KuCun_Offtake | Store_KuCun_Offtake |
| CurrentDay | CurrentDay |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Store_Code | Store_Code |
| CurrentDay | CurrentDay |

# [NSC_Spark_Store_Current_BySKU] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | Month |
| Region | Region |
| CG | CG |
| Cus_Name | Cus_Name |
| Cus_Code | Cus_Code |
| TCDS_Code | TCDS_Code |
| Source | Source |
| Store_Code | Store_Code |
| Store_Name | Store_Name |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Store_SJJH_Tins | Store_SJJH_Tins |
| Store_SJCK_Tins | Store_SJCK_Tins |
| Store_JinHuo_Tins | Store_JinHuo_Tins |
| Store_ZhuiHui_Tins | Store_ZhuiHui_Tins |
| Store_ChuKu_Tins | Store_ChuKu_Tins |
| Store_TuiDan_Tins | Store_TuiDan_Tins |
| Store_KuCun_Tins | Store_KuCun_Tins |
| Store_KuCun_Tins_EXP | Store_KuCun_Tins_EXP |
| Store_JinHuo_Offtake | Store_JinHuo_Offtake |
| Store_ZhuiHui_Offtake | Store_ZhuiHui_Offtake |
| Store_ChuKu_Offtake | Store_ChuKu_Offtake |
| Store_TuiDan_Offtake | Store_TuiDan_Offtake |
| Store_KuCun_Offtake | Store_KuCun_Offtake |
| Store_KuCun_Offtake_EXP | Store_KuCun_Offtake_EXP |
| CurrentDay | CurrentDay |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Store_Code | Store_Code |
| ProductCode | ProductCode |
| CurrentDay | CurrentDay |

# [NSC_Spark_Store_Summary] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_Code | Store_Code |
| Query_Type | Query_Type |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Recruitment_MegaNAN_Total | Recruitment_MegaNAN_Total |
| Recruitment_Shouhu | Recruitment_Shouhu |
| Recruitment_Qihu | Recruitment_Qihu |
| Recruitment_Bohu | Recruitment_Bohu |
| Recruitment_BochuS23 | Recruitment_BochuS23 |
| Recruitment_Gerber_Total | Recruitment_Gerber_Total |
| Recruitment_Gerber_Xinke | Recruitment_Gerber_Xinke |
| Recruitment_Gerber_Yonghu | Recruitment_Gerber_Yonghu |
| Offtake_MegaNAN_Total | Offtake_MegaNAN_Total |
| Offtake_HA_Total | Offtake_HA_Total |
| Offtake_HA_S1 | Offtake_HA_S1 |
| Offtake_HA_S2 | Offtake_HA_S2 |
| Offtake_HA_S3 | Offtake_HA_S3 |
| Offtake_HA_S4 | Offtake_HA_S4 |
| Offtake_Bochu_Total | Offtake_Bochu_Total |
| Offtake_Bochu_S1 | Offtake_Bochu_S1 |
| Offtake_Bochu_S2 | Offtake_Bochu_S2 |
| Offtake_Bochu_S3 | Offtake_Bochu_S3 |
| Offtake_PreNAN_Total | Offtake_PreNAN_Total |
| Offtake_AL110_Total | Offtake_AL110_Total |
| Offtake_Shuyi_Total | Offtake_Shuyi_Total |
| Offtake_Shuyi_S1 | Offtake_Shuyi_S1 |
| Offtake_Shuyi_S2 | Offtake_Shuyi_S2 |
| Offtake_Shuyi_S3 | Offtake_Shuyi_S3 |
| Offtake_Zhuochun_Total | Offtake_Zhuochun_Total |
| Offtake_Gerber_Total | Offtake_Gerber_Total |
| Offtake_Zhuochun_S1 | Offtake_Zhuochun_S1 |
| Offtake_Zhuochun_S2 | Offtake_Zhuochun_S2 |
| Offtake_Zhuochun_S3 | Offtake_Zhuochun_S3 |
| Offtake_Zhuochun_S4 | Offtake_Zhuochun_S4 |
| Offtake_Gerber_Mifen | Offtake_Gerber_Mifen |
| Offtake_Gerber_Mizhou | Offtake_Gerber_Mizhou |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Store_Code | Store_Code |
| Query_Type | Query_Type |

# [NSC_Spark_W90] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | StoreCode |
| 新客时间 | 新客时间 |
| 类型 | 类型 |
| 新客订单编号 | 新客订单编号 |
| BuyTime | BuyTime |
| ID_CRMPlus | ID_CRMPlus |
| Diff_Day | Diff_Day |
| 90D内复购行为 | 90D内复购行为 |
| rn | rn |

# [NSC_Spark_WO90] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | StoreCode |
| 新客时间 | 新客时间 |
| 类型 | 类型 |
| 新客订单编号 | 新客订单编号 |
| BuyTime | BuyTime |
| ID_CRMPlus | ID_CRMPlus |
| Diff_Day | Diff_Day |
| 90D外复购行为 | 90D外复购行为 |
| rn | rn |

# [NSC_Store] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | sid |
| uniacid | uniacid |
| type | type |
| sub_type | sub_type |
| area_name | area_name |
| province | province |
| city | city |
| city_group | city_group |
| store_name | store_name |
| store_number | store_number |
| store_number_2 | store_number_2 |
| store_type | store_type |
| is_test | is_test |
| is_crm | is_crm |
| supervisor_name | supervisor_name |
| supervisor_number | supervisor_number |
| supervisor_tel | supervisor_tel |
| ctime | ctime |
| isdel | isdel |
| ka | ka |
| is_new | is_new |
| distributor | distributor |
| is_ch | is_ch |
| updatetime | updatetime |
| update_time | update_time |
| status | status |
| status_uptime | status_uptime |
| split_account | split_account |
| license | license |
| tob_group | tob_group |
| address | address |
| citylevel | citylevel |
| ka_type | ka_type |
| ka_name | ka_name |
| is_snc | is_snc |
| store_tag | store_tag |
| vip_level | vip_level |
| cdate | cdate |
| store_mode | store_mode |
| vip_level_remark | vip_level_remark |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Spark_Store | Spark_Store |
| tcds_id | tcds_id |
| channel_id | channel_id |
| org_id | org_id |
| cor_name | cor_name |
| shop_head_pic | shop_head_pic |
| Convert_2_Spark_Date | Convert_2_Spark_Date |
| ka_channel | ka_channel |
| city_code | city_code |
| province_code | province_code |
| district_code | district_code |
| sid | sid |

# [NSC_Store_20240619] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | sid |
| uniacid | uniacid |
| type | type |
| sub_type | sub_type |
| area_name | area_name |
| province | province |
| city | city |
| city_group | city_group |
| store_name | store_name |
| store_number | store_number |
| store_number_2 | store_number_2 |
| store_type | store_type |
| is_test | is_test |
| is_crm | is_crm |
| supervisor_name | supervisor_name |
| supervisor_number | supervisor_number |
| supervisor_tel | supervisor_tel |
| ctime | ctime |
| isdel | isdel |
| ka | ka |
| is_new | is_new |
| distributor | distributor |
| is_ch | is_ch |
| updatetime | updatetime |
| update_time | update_time |
| status | status |
| status_uptime | status_uptime |
| split_account | split_account |
| license | license |
| tob_group | tob_group |
| address | address |
| citylevel | citylevel |
| ka_type | ka_type |
| ka_name | ka_name |
| is_snc | is_snc |
| store_tag | store_tag |
| vip_level | vip_level |
| cdate | cdate |
| store_mode | store_mode |
| vip_level_remark | vip_level_remark |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Spark_Store | Spark_Store |
| tcds_id | tcds_id |
| channel_id | channel_id |
| org_id | org_id |
| cor_name | cor_name |
| shop_head_pic | shop_head_pic |
| Convert_2_Spark_Date | Convert_2_Spark_Date |

# [NSC_Store_20240731] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | sid |
| uniacid | uniacid |
| type | type |
| sub_type | sub_type |
| area_name | area_name |
| province | province |
| city | city |
| city_group | city_group |
| store_name | store_name |
| store_number | store_number |
| store_number_2 | store_number_2 |
| store_type | store_type |
| is_test | is_test |
| is_crm | is_crm |
| supervisor_name | supervisor_name |
| supervisor_number | supervisor_number |
| supervisor_tel | supervisor_tel |
| ctime | ctime |
| isdel | isdel |
| ka | ka |
| is_new | is_new |
| distributor | distributor |
| is_ch | is_ch |
| updatetime | updatetime |
| update_time | update_time |
| status | status |
| status_uptime | status_uptime |
| split_account | split_account |
| license | license |
| tob_group | tob_group |
| address | address |
| citylevel | citylevel |
| ka_type | ka_type |
| ka_name | ka_name |
| is_snc | is_snc |
| store_tag | store_tag |
| vip_level | vip_level |
| cdate | cdate |
| store_mode | store_mode |
| vip_level_remark | vip_level_remark |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Spark_Store | Spark_Store |
| tcds_id | tcds_id |
| channel_id | channel_id |
| org_id | org_id |
| cor_name | cor_name |
| shop_head_pic | shop_head_pic |
| Convert_2_Spark_Date | Convert_2_Spark_Date |

# [nsc_store_20241015] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 是否上传 | 是否上传 |
| 营业执照上传时间 | 营业执照上传时间 |
| 二维码码值 | 二维码码值 |
| 渠道 | 渠道 |
| ka_name | ka_name |
| ka_type | ka_type |
| 城市组 | 城市组 |
| 区域 | 区域 |
| 省 | 省 |
| 市 | 市 |
| 地址 | 地址 |
| 店主姓名 | 店主姓名 |
| unionid | unionid |
| 手机号 | 手机号 |
| 店主编号 | 店主编号 |
| 门店名称 | 门店名称 |
| 门店编号 | 门店编号 |
| TSR姓名 | TSR姓名 |
| TSR编号 | TSR编号 |
| TSR电话 | TSR电话 |
| 在职状态 | 在职状态 |
| 是否登录 | 是否登录 |
| 门店标签 | 门店标签 |
| 门店级别 | 门店级别 |
| 创建登录时间 | 创建登录时间 |
| 门店创建时间 | 门店创建时间 |
| 开通原因 | 开通原因 |
| Is_Spark | Is_Spark |

# [NSC_Store_Channel] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletCode | OutletCode |
| Channel | Channel |
| ACGroupName | ACGroupName |
| Platform | Platform |
| ModifiedOn | ModifiedOn |
| CustomerName | CustomerName |
| CreatedOn | CreatedOn |
| Descriptions | Descriptions |
| OutletCode | OutletCode |

# [NSC_Store_Channel_20250527] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletCode | OutletCode |
| Channel | Channel |
| ACGroupName | ACGroupName |
| GroupName | GroupName |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| CustomerName | CustomerName |
| Platform_Sanyar | Platform_Sanyar |
| Platform_Ruby | Platform_Ruby |

# [NSC_Store_Channel_EC] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| CustomerName | CustomerName |
| ACGroupName | ACGroupName |
| Description | Description |
| Platform_Sanyar | Platform_Sanyar |
| Platform_Ruby | Platform_Ruby |
| CreatedOn | CreatedOn |
| CustomerName | CustomerName |
| ACGroupName | ACGroupName |

# [NSC_Tag_CSR] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Source_Questionaire | Source_Questionaire |
| Target_Brand | Target_Brand |
| Is_Sample_Bochu_200g | Is_Sample_Bochu_200g |
| Is_Active_HCP | Is_Active_HCP |
| Is_Binding_SNC_CSR | Is_Binding_SNC_CSR |
| Is_Join_VipGroupe | Is_Join_VipGroupe |
| Tag_List | Tag_List |
| Update_Time | Update_Time |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| SentToCRMOn | SentToCRMOn |
| Is_Allow_UseBohu_From_Link | Is_Allow_UseBohu_From_Link |
| LastChange | LastChange |
| Enter_KuaiShanQun_Date | Enter_KuaiShanQun_Date |
| Quit_KuaiShanQun_Date | Quit_KuaiShanQun_Date |
| Xinke_PreNAN | Xinke_PreNAN |
| Xinke_AL110 | Xinke_AL110 |
| HA_Minmin | HA_Minmin |
| Unionid | Unionid |

# [NSC_Tag_CSR_20240603] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Source_Questionaire | Source_Questionaire |
| Target_Brand | Target_Brand |
| Is_Sample_Bochu_200g | Is_Sample_Bochu_200g |
| Is_Active_HCP | Is_Active_HCP |
| Is_Binding_SNC_CSR | Is_Binding_SNC_CSR |
| Is_Join_VipGroupe | Is_Join_VipGroupe |
| Tag_List | Tag_List |
| Update_Time | Update_Time |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| SentToCRMOn | SentToCRMOn |
| Is_Allow_UseBohu_From_Link | Is_Allow_UseBohu_From_Link |
| LastChange | LastChange |
| Enter_KuaiShanQun_Date | Enter_KuaiShanQun_Date |
| Quit_KuaiShanQun_Date | Quit_KuaiShanQun_Date |
| Xinke_PreNAN | Xinke_PreNAN |
| Xinke_AL110 | Xinke_AL110 |
| HA_Minmin | HA_Minmin |

# [NSC_Test_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Name | Name |
| Mobile | Mobile |
| S_Mobile | S_Mobile |
| Type | Type |
| Remark | Remark |
| CreatedOn | CreatedOn |
| Unionid | Unionid |

# [NSC_ToB_Achievement] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| openid | openid |
| unionid | unionid |
| NewCustomerType | NewCustomerType |
| gift_code | gift_code |
| sid | sid |
| StoreCode | StoreCode |
| SNCCode | SNCCode |
| serial_number_sy | serial_number_sy |
| type | type |
| act_type | act_type |
| source | source |
| yeji_val | yeji_val |
| order_id | order_id |
| order_no | order_no |
| cash_out_id | cash_out_id |
| cash_out_status | cash_out_status |
| remark | remark |
| status | status |
| msg | msg |
| send_id | send_id |
| tradeno | tradeno |
| cdate | cdate |
| updatetime | updatetime |
| rn | rn |
| id | id |

# [NSC_ToB_Gerber_ZhuanQu] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| mid | mid |
| page_name | page_name |
| page_data | page_data |
| button | button |
| unionid | unionid |
| create_time | create_time |
| NewID | NewID |
| Title | Title |
| Brand | Brand |
| id | id |

# [NSC_Tob_Quota] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Months | Months |
| StoreCode | StoreCode |
| Quarter | Quarter |
| Qty | Qty |
| Total_NPS | Total_NPS |
| Total_NSCPlus_NPS | Total_NSCPlus_NPS |
| Total_NSCPlus_RRP | Total_NSCPlus_RRP |
| Is_Fixed | Is_Fixed |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID | ID |

# [NSC_Tob_Quota_2025Q3] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Months | Months |
| StoreCode | StoreCode |
| Quarter | Quarter |
| Qty | Qty |
| Total_NPS | Total_NPS |
| Total_NSCPlus_NPS | Total_NSCPlus_NPS |
| Total_NSCPlus_RRP | Total_NSCPlus_RRP |
| Is_Fixed | Is_Fixed |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [NSC_Tob_Quota_temp] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | StoreCode |
| Months | Months |
| Total_NPS | Total_NPS |
| Total_NSCPlus_NPS | Total_NSCPlus_NPS |
| Total_NSCPlus_RRP | Total_NSCPlus_RRP |
| Qty | Qty |

# [NSC_ToB_SALESMAN] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| mid | mid |
| area_name | area_name |
| province | province |
| store_number | store_number |
| shopowner | shopowner |
| name | name |
| tel | tel |
| openid | openid |
| store_name | store_name |
| city_group | city_group |
| address | address |
| store_tag | store_tag |
| vip_level | vip_level |
| supervisor_number | supervisor_number |
| supervisor_name | supervisor_name |
| supervisor_tel | supervisor_tel |
| license_upload_date | license_upload_date |
| is_onjob | is_onjob |
| Status | Status |
| serial_number | serial_number |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Spark_Store | Spark_Store |
| is_crm | is_crm |
| ka_type | ka_type |
| ka_name | ka_name |
| NUMBER | NUMBER |
| CreatedOn | CreatedOn |

# [NSC_ToB_Store_Status] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_ID | Store_ID |
| Current_Month | Current_Month |
| RepurchaseRate_Recent_2M | RepurchaseRate_Recent_2M |
| RepurchaseFrequency_Recent_2M | RepurchaseFrequency_Recent_2M |
| MOT_SentRate_LastMonth | MOT_SentRate_LastMonth |
| MOT_ConversionRate_LastMonth | MOT_ConversionRate_LastMonth |
| Foward_ActivityAndContent_CompletedRate_LastMonth | Foward_ActivityAndContent_CompletedRate_LastMonth |
| Foward_ActivityAndContent_ConversionRate_LastMonth | Foward_ActivityAndContent_ConversionRate_LastMonth |
| Course_CompletedRate_LastMonth | Course_CompletedRate_LastMonth |
| Repurchase_Orders_Recent_2M | Repurchase_Orders_Recent_2M |
| Repurchase_Users_Recent_2M | Repurchase_Users_Recent_2M |
| Recruit_Users_Recent_2M | Recruit_Users_Recent_2M |
| Vip_Level | Vip_Level |
| MOT_Sent | MOT_Sent |
| MOT_Finish | MOT_Finish |
| MOT_Conversion | MOT_Conversion |
| Completed_Course | Completed_Course |
| TTL_Push_Course | TTL_Push_Course |
| TTL_Push_Content | TTL_Push_Content |
| Completed_Content_Activity | Completed_Content_Activity |
| Conversion_Content_Activity | Conversion_Content_Activity |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Store_ID | Store_ID |
| Current_Month | Current_Month |

# [NSC_ToB_ZhuanQu] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| module | module |
| session_key | session_key |
| openid | openid |
| type | type |
| unionid | unionid |
| uid | uid |
| utype | utype |
| baby_m | baby_m |
| page | page |
| category | category |
| mid | mid |
| page_name | page_name |
| page_data | page_data |
| button | button |
| source | source |
| track | track |
| sr_channel | sr_channel |
| channel_id | channel_id |
| is_crm | is_crm |
| follow | follow |
| scene | scene |
| year | year |
| month | month |
| day | day |
| ctime | ctime |
| ip | ip |
| updatetime | updatetime |
| create_time | create_time |
| NewID | NewID |
| Tag | Tag |
| Brand | Brand |
| id | id |

# [NSC_User_Scenario] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Scenario | Scenario |
| Last_Buy_Date | Last_Buy_Date |
| Is_Better_Date | Is_Better_Date |
| Is_Baby_Weight_Great_45 | Is_Baby_Weight_Great_45 |
| ZhuanNai_Date_PreNAN | ZhuanNai_Date_PreNAN |
| ZhuanNai_Date_HA | ZhuanNai_Date_HA |
| ZhuanNai_Date_Bochu | ZhuanNai_Date_Bochu |
| CreatedOn | CreatedOn |
| ModifiedOn_OA | ModifiedOn_OA |
| ModifiedOn_CSR | ModifiedOn_CSR |
| ModifiedOn_SNC | ModifiedOn_SNC |
| ModifiedOn_CD | ModifiedOn_CD |
| Brand | Brand |
| ZhuanBrand_Date | ZhuanBrand_Date |
| Unionid | Unionid |

# [NSC_VIP_GROUPES] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Chat_id | Chat_id |
| SncCode | SncCode |
| CsrCode | CsrCode |
| Unionid | Unionid |
| GroupName | GroupName |
| GroupCreateTime | GroupCreateTime |
| GroupActiveTime | GroupActiveTime |
| GroupExitTime | GroupExitTime |
| IsValid | IsValid |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Id | Id |

# [OMNICHANNEL_MEMBER_2021] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Openid | Openid |
| M_CREATE_DATE | M_CREATE_DATE |
| M_UPDATE_DATE | M_UPDATE_DATE |
| Name | Name |
| BabyBirthday | BabyBirthday |
| WECHAT_BIND_FLAG | WECHAT_BIND_FLAG |
| SR_QRCODE | SR_QRCODE |
| SR_USER_NAME | SR_USER_NAME |
| SR_STORE_CODE | SR_STORE_CODE |
| SR_AREA | SR_AREA |
| SR_PROVINCE | SR_PROVINCE |
| SR_CITY | SR_CITY |
| SR_CODE | SR_CODE |
| SR_CHANNEL | SR_CHANNEL |
| SR_CITY_GROUP | SR_CITY_GROUP |
| SR_STORE_NAME | SR_STORE_NAME |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| RegisterChannel | RegisterChannel |
| SUB_PREGNANT_STATUS | SUB_PREGNANT_STATUS |
| SUB_BABY_BIRTHDAY | SUB_BABY_BIRTHDAY |
| SUB_BABY_DUEDATE | SUB_BABY_DUEDATE |
| Completed_Info | Completed_Info |
| Completed_ARI | Completed_ARI |
| Brand_Prospect | Brand_Prospect |
| MS_GP_Tag | MS_GP_Tag |
| SUB_USER_NICKNAME | SUB_USER_NICKNAME |
| Completed_S1S2_Ratting | Completed_S1S2_Ratting |
| Mobile | Mobile |
| S_MOBILE | S_MOBILE |
| Completed_Shouhu_Questionnaire1_Date | Completed_Shouhu_Questionnaire1_Date |
| Completed_Qihu_Questionnaire1_Date | Completed_Qihu_Questionnaire1_Date |
| Completed_Youhu_Questionnaire1_Date | Completed_Youhu_Questionnaire1_Date |
| Completed_Qihu_Questionnaire2_Date | Completed_Qihu_Questionnaire2_Date |
| Completed_Youhu_Questionnaire2_Date | Completed_Youhu_Questionnaire2_Date |
| Completed_Cmpa_Questionnaire_Date | Completed_Cmpa_Questionnaire_Date |
| JD_MOBILE | JD_MOBILE |
| SYNC_TIME | SYNC_TIME |
| Last_SYNC_Time | Last_SYNC_Time |
| SentToJDOn | SentToJDOn |
| Comments | Comments |
| WECHAT_BIND_GB | WECHAT_BIND_GB |
| WECHAT_BIND_FLAG_GB | WECHAT_BIND_FLAG_GB |
| CreatedOn | CreatedOn |
| WECHAT_BIND_CT | WECHAT_BIND_CT |
| Completed_Bohu_Questionnaire1_Date | Completed_Bohu_Questionnaire1_Date |
| Completed_Bohu_Questionnaire2_Date | Completed_Bohu_Questionnaire2_Date |
| SUB_BABY_NICKNAME | SUB_BABY_NICKNAME |
| AL110_Popup | AL110_Popup |
| Completed_Shuhu_Questionnaire1_Date | Completed_Shuhu_Questionnaire1_Date |
| Vip_Level | Vip_Level |
| Total_Tins | Total_Tins |
| NHS_Unionid | NHS_Unionid |
| Unionid | Unionid |

# [OMNICHANNEL_SALES] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PID | PID |
| Mobile | Mobile |
| ProductCode | ProductCode |
| ProductName | ProductName |
| NewCustomerType | NewCustomerType |
| Buytime | Buytime |
| Source | Source |
| Brand | Brand |
| Stage | Stage |
| Qty | Qty |
| Channel | Channel |
| NetWeight | NetWeight |
| CreatedOn | CreatedOn |
| SNCCode | SNCCode |
| S_Mobile | S_Mobile |
| LastChange | LastChange |
| Openid | Openid |
| Unionid | Unionid |
| StoreCode | StoreCode |
| PurchaseStatus | PurchaseStatus |
| ReturnQty | ReturnQty |
| Remark | Remark |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| OrderNum | OrderNum |
| Tcds_Id | Tcds_Id |
| Has_Tin | Has_Tin |
| ID | ID |

# [OMNICHANNEL_SALES_QRCODE] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| QRCode | QRCode |
| TouchPoint | TouchPoint |
| IsReturn | IsReturn |
| BuyTime | BuyTime |
| CreatedOn | CreatedOn |
| StoreName | StoreName |
| StoreCode | StoreCode |
| Remark | Remark |
| LastChange | LastChange |
| IQC_QRCode | IQC_QRCode |
| IQC_QRCode_Time | IQC_QRCode_Time |
| Tin_Type | Tin_Type |
| ProductCode | ProductCode |
| SNCCode | SNCCode |
| SNCName | SNCName |
| OrderNum | OrderNum |
| ProductName | ProductName |
| ID | ID |
| QRCode | QRCode |
| IsReturn | IsReturn |

# [OrderNoUnionid] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 购买时间 | 购买时间 |
| 门店编码 | 门店编码 |
| KSFId | KSFId |
| 验证日期1 | 验证日期1 |
| 验证月份 | 验证月份 |
| OriginalBatchNo | OriginalBatchNo |

# [Orders] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| OrderNumber | OrderNumber |
| MemberId | MemberId |
| Amount | Amount |
| Status | Status |
| OrderTime | OrderTime |
| CreatedAt | CreatedAt |
| UpdatedAt | UpdatedAt |
| CompletedAt | CompletedAt |
| Remarks | Remarks |
| Id | Id |

# [outbound_id_callseqno] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| call_seq_no | call_seq_no |

# [PairPurchases] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| rn | rn |
| Unionid | Unionid |
| BrandFrom | BrandFrom |
| BrandTo | BrandTo |

# [ProcedureLog] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| LogDate | LogDate |
| DatabaseID | DatabaseID |
| ObjectID | ObjectID |
| ProcedureName | ProcedureName |
| ErrorLine | ErrorLine |
| ErrorMessage | ErrorMessage |
| AdditionalInfo | AdditionalInfo |
| Parameter | Parameter |
| Cost | Cost |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [PUSH_Baby] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PBabyId | PBabyId |
| CBabyId | CBabyId |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| BabyName | BabyName |
| Birthday | Birthday |
| Gender | Gender |
| BirthOrder | BirthOrder |
| BabyNum | BabyNum |
| WeanedDate | WeanedDate |
| CreatedOn | CreatedOn |
| CreatedBy | CreatedBy |
| OperationFlag | OperationFlag |
| ModifiedOn | ModifiedOn |
| ModifiedBy | ModifiedBy |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [PUSH_Inbound] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| Id | Id |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| Name | Name |
| CalledNumber | CalledNumber |
| StartTime | StartTime |
| EndTime | EndTime |
| FilePath | FilePath |
| CallId | CallId |
| CSRCode | CSRCode |
| CSRName | CSRName |
| Remark | Remark |
| ContactSpecification | ContactSpecification |
| CallCategory | CallCategory |
| CallType | CallType |
| MomBrandId | MomBrandId |
| MomProductId | MomProductId |
| NicBrandId | NicBrandId |
| NicProductId | NicProductId |
| BabyBrandId | BabyBrandId |
| BabyProductId | BabyProductId |
| FeedType | FeedType |
| ConsultPoint | ConsultPoint |
| ConsultContent | ConsultContent |
| ReplyContent | ReplyContent |
| HotlineKnowWay | HotlineKnowWay |
| ConsultDetail | ConsultDetail |
| TIMELONG | TIMELONG |
| OperationFlag | OperationFlag |
| ModifiedOn | ModifiedOn |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [PUSH_Mama] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| MamaName | MamaName |
| Birthday | Birthday |
| Gender | Gender |
| PostalCode | PostalCode |
| AddressHead | AddressHead |
| AddressTail | AddressTail |
| JoinTime | JoinTime |
| HomeTel | HomeTel |
| OfficeTel | OfficeTel |
| OtherTel | OtherTel |
| Mobile | Mobile |
| DefaultTelType | DefaultTelType |
| HotelineKnowWay | HotelineKnowWay |
| IsRefusedAll | IsRefusedAll |
| IsFollowedWechatCTM | IsFollowedWechatCTM |
| IsBandWechatCTM | IsBandWechatCTM |
| IsAcceptedCall | IsAcceptedCall |
| IsAcceptedMail | IsAcceptedMail |
| IsAcceptedEmail | IsAcceptedEmail |
| IsAcceptedSMS | IsAcceptedSMS |
| Remark | Remark |
| IsMember | IsMember |
| MemberCardNo | MemberCardNo |
| IdentityNumber | IdentityNumber |
| Company | Company |
| Job | Job |
| CheccId | CheccId |
| CMTId | CMTId |
| LogBatchId | LogBatchId |
| WebUserId | WebUserId |
| WebDataSource | WebDataSource |
| Email | Email |
| WechatNo | WechatNo |
| WeiboNo | WeiboNo |
| RegisterMobile | RegisterMobile |
| PregnantStatus | PregnantStatus |
| HasAllergy | HasAllergy |
| CMTKnowWay | CMTKnowWay |
| Interests | Interests |
| IsPass | IsPass |
| NoPassReason | NoPassReason |
| IsCMTCall | IsCMTCall |
| BabyEDC | BabyEDC |
| IsCallCount | IsCallCount |
| ImportDate | ImportDate |
| Frozen | Frozen |
| SubscribeSource | SubscribeSource |
| RegisterChannel | RegisterChannel |
| OperationFlag | OperationFlag |
| CreatedOn | CreatedOn |
| CreatedBy | CreatedBy |
| ModifiedOn | ModifiedOn |
| ModifiedBy | ModifiedBy |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| ActivityChannel | ActivityChannel |
| KSFId | KSFId |
| CMT_ID | CMT_ID |
| MamaNameFromSNC | MamaNameFromSNC |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Unionid | Unionid |
| ID | ID |

# [PUSH_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MemberId | MemberId |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| KSFId | KSFId |
| RegisterChannel | RegisterChannel |
| Status | Status |
| CreateUser | CreateUser |
| CreateTime | CreateTime |
| Remark | Remark |
| SRCode | SRCode |
| SRName | SRName |
| QRCode | QRCode |
| MamaName | MamaName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| StoreChannel | StoreChannel |
| Region | Region |
| Province | Province |
| City | City |
| CityGroup | CityGroup |
| JoinDate | JoinDate |
| OperationFlag | OperationFlag |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| ModifiedOn | ModifiedOn |
| ActivityChannel | ActivityChannel |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [PUSH_Member_Profiles] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| M_MOBILE | M_MOBILE |
| SWD_SWL_BATCH_ID | SWD_SWL_BATCH_ID |
| M_USER_ID | M_USER_ID |
| M_PASSWORD | M_PASSWORD |
| M_IS_VAILD | M_IS_VAILD |
| M_INVAILD_REASON | M_INVAILD_REASON |
| M_CREATE_DATE | M_CREATE_DATE |
| M_UPDATE_DATE | M_UPDATE_DATE |
| M_UPDATE_USER | M_UPDATE_USER |
| SUB_USER_EMAIL | SUB_USER_EMAIL |
| SUB_USER_NAME | SUB_USER_NAME |
| SUB_USER_NICKNAME | SUB_USER_NICKNAME |
| SUB_USER_BIRTHDAY | SUB_USER_BIRTHDAY |
| SUB_MEMBER_TYPE | SUB_MEMBER_TYPE |
| SUB_MEMBER_TYPE_OTHER | SUB_MEMBER_TYPE_OTHER |
| SUB_PROVINCE | SUB_PROVINCE |
| SUB_CITY | SUB_CITY |
| SUB_DISTRICT | SUB_DISTRICT |
| SUB_ADDRESS | SUB_ADDRESS |
| SUB_ZIPCODE | SUB_ZIPCODE |
| SUB_PREGNANT_STATUS | SUB_PREGNANT_STATUS |
| SUB_BABY_DUEDATE | SUB_BABY_DUEDATE |
| SUB_BABY_BIRTHDAY | SUB_BABY_BIRTHDAY |
| SUB_BABY_NICKNAME | SUB_BABY_NICKNAME |
| SUB_INTEREST_MILESTONE | SUB_INTEREST_MILESTONE |
| SUB_IS_RCV_SMS | SUB_IS_RCV_SMS |
| SUB_IS_RCV_MMS | SUB_IS_RCV_MMS |
| SUB_IS_RCV_MAIL | SUB_IS_RCV_MAIL |
| SUB_IS_RCV_OTHER | SUB_IS_RCV_OTHER |
| SUB_IS_ALLERGY | SUB_IS_ALLERGY |
| SUB_BABY_BRAND | SUB_BABY_BRAND |
| SUB_FEEDING_PATTERNS | SUB_FEEDING_PATTERNS |
| SOU_CREATE_DATE | SOU_CREATE_DATE |
| SOU_CREATE_USER | SOU_CREATE_USER |
| SOU_SITE_TYPE | SOU_SITE_TYPE |
| SOU_COOKIE_KEY | SOU_COOKIE_KEY |
| SOU_SESSION_FIRST_TIME | SOU_SESSION_FIRST_TIME |
| SOU_CAMPAIGN_CODE | SOU_CAMPAIGN_CODE |
| SOU_CONFERENCE_CODE | SOU_CONFERENCE_CODE |
| SOU_WECHAT_COMEFROM | SOU_WECHAT_COMEFROM |
| SOU_TRACKING_CODE_06 | SOU_TRACKING_CODE_06 |
| SWD_PROCESS_FLAG | SWD_PROCESS_FLAG |
| SWD_UTYPE | SWD_UTYPE |
| SWD_DATA_SOURCE | SWD_DATA_SOURCE |
| WECHAT_BIND | WECHAT_BIND |
| WECHAT_BIND_FLAG | WECHAT_BIND_FLAG |
| SUB_TAG_M1001 | SUB_TAG_M1001 |
| SUB_TAG_M1002 | SUB_TAG_M1002 |
| SUB_TAG_M1003 | SUB_TAG_M1003 |
| SUB_TAG_M1004 | SUB_TAG_M1004 |
| SUB_TAG_M1005 | SUB_TAG_M1005 |
| SUB_TAG_M1006 | SUB_TAG_M1006 |
| ModifiedOn | ModifiedOn |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| SR_USER_NAME | SR_USER_NAME |
| SR_STORE_CODE | SR_STORE_CODE |
| SR_AREA | SR_AREA |
| SR_PROVINCE | SR_PROVINCE |
| SR_CITY | SR_CITY |
| SR_CODE | SR_CODE |
| SR_CHANNEL | SR_CHANNEL |
| SR_CITY_GROUP | SR_CITY_GROUP |
| SR_STORE_NAME | SR_STORE_NAME |
| KSFID | KSFID |
| CMT_ID | CMT_ID |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| M_TYPE | M_TYPE |
| CMT_UNIONID | CMT_UNIONID |
| Remark | Remark |
| S_MOBILE | S_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Vip_Level | Vip_Level |
| NHS_Unionid | NHS_Unionid |
| ID | ID |

# [PUSH_Member_Profiles_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| LastDateTime | LastDateTime |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [PUSH_Outbound] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| Id | Id |
| PMamaId | PMamaId |
| CMamaId | CMamaId |
| KSFId | KSFId |
| CallingNumber | CallingNumber |
| CalledNumber | CalledNumber |
| StartTime | StartTime |
| EndTime | EndTime |
| CallDuration | CallDuration |
| TapeFilePath | TapeFilePath |
| CallId | CallId |
| CSRCode | CSRCode |
| CSRName | CSRName |
| CallResult | CallResult |
| IsNameValid | IsNameValid |
| ModifiedName | ModifiedName |
| IsBuy | IsBuy |
| IsProductNameValid | IsProductNameValid |
| ModifiedProductName | ModifiedProductName |
| ModifiedBoughtTime | ModifiedBoughtTime |
| CurrentMomBrand | CurrentMomBrand |
| Remark1 | Remark1 |
| CurrentNicBrand | CurrentNicBrand |
| Remark2 | Remark2 |
| CurrentS3NestleBrand | CurrentS3NestleBrand |
| Remark3 | Remark3 |
| CurrentS3CompeteBrand | CurrentS3CompeteBrand |
| Remark4 | Remark4 |
| IsContinuedBuy | IsContinuedBuy |
| CALLCONTENT | CALLCONTENT |
| CALLREMARK | CALLREMARK |
| Campaignid | Campaignid |
| listid | listid |
| CallType | CallType |
| MomBrandId | MomBrandId |
| MomProductId | MomProductId |
| NicBrandId | NicBrandId |
| NicProductId | NicProductId |
| BabyBrandId | BabyBrandId |
| BabyProductId | BabyProductId |
| BUSI_TYPE_TAG | BUSI_TYPE_TAG |
| OperationFlag | OperationFlag |
| ModifiedOn | ModifiedOn |
| IsSentToCRM | IsSentToCRM |
| SentToCRMDate | SentToCRMDate |
| EqualResult | EqualResult |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [QBB_Gerber_Register] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Mobile | Mobile |
| Name | Name |
| BabyBirthday | BabyBirthday |
| Province | Province |
| City | City |
| District | District |
| Address | Address |
| SampleType | SampleType |
| S_Mobile | S_Mobile |
| IsUsedCoupon | IsUsedCoupon |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Mobile | Mobile |

# [QD_Questionnaire] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| survey_id | survey_id |
| survey_name | survey_name |
| question_id | question_id |
| question_name | question_name |
| question_code | question_code |
| question_type | question_type |
| question_sub_type | question_sub_type |
| module_list | module_list |
| option_list | option_list |
| CreatedOn | CreatedOn |
| survey_id | survey_id |
| question_id | question_id |

# [QD_RowData] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| user_id | user_id |
| survey_id | survey_id |
| survey_name | survey_name |
| question_id | question_id |
| question_name | question_name |
| question_code | question_code |
| question_type | question_type |
| question_sub_type | question_sub_type |
| module_list | module_list |
| option_list | option_list |
| answer | answer |
| CreatedOn | CreatedOn |
| ID | ID |

# [rachel_20250324_result] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 星火省份 | 星火省份 |
| 城市 | 城市 |
| 地级市/县城 | 地级市/县城 |
| UNIONID | UNIONID |
| mobile | mobile |
| qty | qty |
| Store_Name | Store_Name |
| StoreCode | StoreCode |
| 是否有导 | 是否有导 |
| OAH or No-OAH | OAH or No-OAH |

# [Redis_LOG] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Table_Name | Table_Name |
| Table_ID | Table_ID |
| Redis_Key | Redis_Key |
| Redis_Group | Redis_Group |
| Payload | Payload |
| Response | Response |
| Status | Status |
| EnterDate | EnterDate |
| DML_Type | DML_Type |
| ElapsedMilliseconds | ElapsedMilliseconds |
| CreateDate | CreateDate |
| ID | ID |

# [RUN_JOB_HISTORY] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| job_name | job_name |
| run_datetime | run_datetime |
| run_time | run_time |
| run_duration_millsecond | run_duration_millsecond |
| step_name | step_name |
| run_status | run_status |
| message | message |
| created_datetime | created_datetime |
| id | id |

# [SNC_Bonus_BochuS23] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tank_barcode | tank_barcode |
| cdate | cdate |
| touch_point | touch_point |
| recall | recall |
| recall_date | recall_date |
| Comments | Comments |
| tank_barcode | tank_barcode |
| recall | recall |

# [SNC_Bonus_BochuS23_20241018] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tank_barcode | tank_barcode |
| cdate | cdate |
| touch_point | touch_point |
| recall | recall |
| recall_date | recall_date |
| Comments | Comments |

# [SNC_HA_42] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_Code | SNC_Code |
| SNC_Name | SNC_Name |
| Unionid | Unionid |
| S_Mobile | S_Mobile |
| User_Name | User_Name |
| Region | Region |
| CG | CG |
| Current_Tins | Current_Tins |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [SNC_Performance_Accumulation] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| SNCCode | SNCCode |
| A_LT_18 | A_LT_18 |
| A_19_36 | A_19_36 |
| A_37_42 | A_37_42 |
| A_GT_43 | A_GT_43 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| SNCCode | SNCCode |

# [SNC_Performance_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | IMF_Xinke |
| Service_1st_SNCCode | Service_1st_SNCCode |
| Service_1st_Date | Service_1st_Date |
| Service_Two | Service_Two |
| Service_Two_SNCCode | Service_Two_SNCCode |
| Service_Two_Date | Service_Two_Date |
| Service_Three | Service_Three |
| Service_Three_SNCCode | Service_Three_SNCCode |
| Service_Three_Date | Service_Three_Date |
| Service_Four | Service_Four |
| Service_Four_SNCCode | Service_Four_SNCCode |
| Service_Four_Date | Service_Four_Date |
| Rrepurchase_Stage_3 | Rrepurchase_Stage_3 |
| Rrepurchase_Stage_3_SNCCode | Rrepurchase_Stage_3_SNCCode |
| Rrepurchase_Stage_3_Date | Rrepurchase_Stage_3_Date |
| Current_Tins | Current_Tins |
| Tins_18 | Tins_18 |
| Tins_42 | Tins_42 |
| Service_Two_Claim_Date | Service_Two_Claim_Date |
| Service_Three_Claim_Date | Service_Three_Claim_Date |
| Service_Four_Claim_Date | Service_Four_Claim_Date |
| Tins_18_Claim_Date | Tins_18_Claim_Date |
| Tins_42_Claim_Date | Tins_42_Claim_Date |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |

# [SNC_Performance_Member_20250401] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | IMF_Xinke |
| Service_1st_SNCCode | Service_1st_SNCCode |
| Service_1st_Date | Service_1st_Date |
| Service_Two | Service_Two |
| Service_Two_SNCCode | Service_Two_SNCCode |
| Service_Two_Date | Service_Two_Date |
| Service_Three | Service_Three |
| Service_Three_SNCCode | Service_Three_SNCCode |
| Service_Three_Date | Service_Three_Date |
| Service_Four | Service_Four |
| Service_Four_SNCCode | Service_Four_SNCCode |
| Service_Four_Date | Service_Four_Date |
| Rrepurchase_Stage_3 | Rrepurchase_Stage_3 |
| Rrepurchase_Stage_3_SNCCode | Rrepurchase_Stage_3_SNCCode |
| Rrepurchase_Stage_3_Date | Rrepurchase_Stage_3_Date |
| Current_Tins | Current_Tins |
| Tins_18 | Tins_18 |
| Tins_42 | Tins_42 |
| Service_Two_Claim_Date | Service_Two_Claim_Date |
| Service_Three_Claim_Date | Service_Three_Claim_Date |
| Service_Four_Claim_Date | Service_Four_Claim_Date |
| Tins_18_Claim_Date | Tins_18_Claim_Date |
| Tins_42_Claim_Date | Tins_42_Claim_Date |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [SNC_Performance_Member_20250401_bak] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | IMF_Xinke |
| Service_1st_SNCCode | Service_1st_SNCCode |
| Service_1st_Date | Service_1st_Date |
| Service_Two | Service_Two |
| Service_Two_SNCCode | Service_Two_SNCCode |
| Service_Two_Date | Service_Two_Date |
| Service_Three | Service_Three |
| Service_Three_SNCCode | Service_Three_SNCCode |
| Service_Three_Date | Service_Three_Date |
| Service_Four | Service_Four |
| Service_Four_SNCCode | Service_Four_SNCCode |
| Service_Four_Date | Service_Four_Date |
| Rrepurchase_Stage_3 | Rrepurchase_Stage_3 |
| Rrepurchase_Stage_3_SNCCode | Rrepurchase_Stage_3_SNCCode |
| Rrepurchase_Stage_3_Date | Rrepurchase_Stage_3_Date |
| Current_Tins | Current_Tins |
| Tins_18 | Tins_18 |
| Tins_42 | Tins_42 |
| Service_Two_Claim_Date | Service_Two_Claim_Date |
| Service_Three_Claim_Date | Service_Three_Claim_Date |
| Service_Four_Claim_Date | Service_Four_Claim_Date |
| Tins_18_Claim_Date | Tins_18_Claim_Date |
| Tins_42_Claim_Date | Tins_42_Claim_Date |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [SNC_PERP_KPI_Incentive_OrderDetial] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| brand | brand |
| stage | stage |
| buytime | buytime |
| 购买SNC | 购买SNC |
| 订单罐数 | 订单罐数 |
| returnQty | returnQty |
| TankBarcode | TankBarcode |
| ID_CRMPlus | ID_CRMPlus |
| 购买StoreCode | 购买StoreCode |
| ProductName | ProductName |
| Source | Source |
| ID | ID |
| OrderEntry | OrderEntry |
| OrderNum | OrderNum |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDetail | OrderbyDetail |
| OrderbyDay | OrderbyDay |
| OrderbyDay_desc | OrderbyDay_desc |
| Revenue | Revenue |
| stage_label | stage_label |
| 普配S1_label | 普配S1_label |
| 刨除退单罐数 | 刨除退单罐数 |
| OrderbyDetail_有效 | OrderbyDetail_有效 |
| OrderbyDay_有效 | OrderbyDay_有效 |
| OrderWithDay_刨普s1 | OrderWithDay_刨普s1 |
| OrderbyDay_刨普s1 | OrderbyDay_刨普s1 |
| OrderDesc | OrderDesc |
| 累积购买罐数 | 累积购买罐数 |
| 首购日期 | 首购日期 |
| 累积听数层级Label | 累积听数层级Label |
| 前一单累积听数层级Label | 前一单累积听数层级Label |
| 跨段标识 | 跨段标识 |
| 距离首单月数 | 距离首单月数 |
| 当月大于18M的听数 | 当月大于18M的听数 |
| 1-18听_非跨段 | 1-18听_非跨段 |
| 19-36听_非跨段 | 19-36听_非跨段 |
| 37-42听_非跨段 | 37-42听_非跨段 |
| 43-100听_非跨段 | 43-100听_非跨段 |
| 100听以上_非跨段 | 100听以上_非跨段 |
| 1-18听_跨段1 | 1-18听_跨段1 |
| 19-36听_跨段1 | 19-36听_跨段1 |
| 1-18听_跨段2 | 1-18听_跨段2 |
| 19-36听_跨段2 | 19-36听_跨段2 |
| 37-42听_跨段1 | 37-42听_跨段1 |
| 19-36听_跨段3 | 19-36听_跨段3 |
| 37-42听_跨段2 | 37-42听_跨段2 |
| 1-18听_跨段3 | 1-18听_跨段3 |
| 19-36听_跨段4 | 19-36听_跨段4 |
| 37-42听_跨段3 | 37-42听_跨段3 |
| 43听-100_跨段1 | 43听-100_跨段1 |
| 19-36听_跨段5 | 19-36听_跨段5 |
| 37-42听_跨段4 | 37-42听_跨段4 |
| 43听-100_跨段2 | 43听-100_跨段2 |
| 37-42听_跨段5 | 37-42听_跨段5 |
| 43听-100_跨段3 | 43听-100_跨段3 |
| 1-18听_跨段4 | 1-18听_跨段4 |
| 19-36听_跨段6 | 19-36听_跨段6 |
| 37-42听_跨段6 | 37-42听_跨段6 |
| 43听-100_跨段4 | 43听-100_跨段4 |
| 100听以上_跨段1 | 100听以上_跨段1 |
| 19-36听_跨段7 | 19-36听_跨段7 |
| 37-42听_跨段7 | 37-42听_跨段7 |
| 43听-100_跨段5 | 43听-100_跨段5 |
| 100听以上_跨段2 | 100听以上_跨段2 |
| 37-42听_跨段8 | 37-42听_跨段8 |
| 43听-100_跨段6 | 43听-100_跨段6 |
| 100听以上_跨段3 | 100听以上_跨段3 |
| 43听-100_跨段7 | 43听-100_跨段7 |
| 100听以上_跨段4 | 100听以上_跨段4 |
| 1-18听 | 1-18听 |
| 19-36听 | 19-36听 |
| 37-42听 | 37-42听 |
| 43-100听 | 43-100听 |
| 100听以上 | 100听以上 |
| IQC_Tins | IQC_Tins |

# [SNC_PERP_KPI_Incentive_Service] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | Brand |
| Stage | Stage |
| BuyTime | BuyTime |
| ProductName | ProductName |
| 购买SNC | 购买SNC |
| Source | Source |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | OrderbyDay_刨普s1 |
| OrderWithDay_刨普s1 | OrderWithDay_刨普s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单Source |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段BuyTime |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段buytime |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNCCode |
| 前一单Source | 前一单Source |
| OrderWithDay_转段_时间 | OrderWithDay_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNCCode |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | Months |
| CreatedOn | CreatedOn |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| TankBarcode | TankBarcode |
| IQC_Time | IQC_Time |
| IQC_1st_Time | IQC_1st_Time |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Service_History] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | Brand |
| Stage | Stage |
| BuyTime | BuyTime |
| ProductName | ProductName |
| 购买SNC | 购买SNC |
| Source | Source |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | OrderbyDay_刨普s1 |
| OrderWithDay_刨普s1 | OrderWithDay_刨普s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单Source |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段BuyTime |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段buytime |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNCCode |
| 前一单Source | 前一单Source |
| OrderWithDay_转段_时间 | OrderWithDay_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNCCode |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | Months |
| CreatedOn | CreatedOn |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| TankBarcode | TankBarcode |
| IQC_Time | IQC_Time |
| IQC_1st_Time | IQC_1st_Time |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Service_History_20250609] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | Brand |
| Stage | Stage |
| BuyTime | BuyTime |
| ProductName | ProductName |
| 购买SNC | 购买SNC |
| Source | Source |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | OrderbyDay_刨普s1 |
| OrderWithDay_刨普s1 | OrderWithDay_刨普s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单Source |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段BuyTime |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段buytime |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNCCode |
| 前一单Source | 前一单Source |
| OrderWithDay_转段_时间 | OrderWithDay_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNCCode |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | Months |
| CreatedOn | CreatedOn |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| TankBarcode | TankBarcode |
| IQC_Time | IQC_Time |
| IQC_1st_Time | IQC_1st_Time |

# [SNC_PERP_KPI_Incentive_Tins] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18听 |
| 19-36听 | 19-36听 |
| 37-42听 | 37-42听 |
| 43-100听 | 43-100听 |
| 100听以上 | 100听以上 |
| 当月大于18M的听数 | 当月大于18M的听数 |
| Months | Months |
| CreatedOn | CreatedOn |
| IQC_1-18听 | IQC_1-18听 |
| IQC_19-36听 | IQC_19-36听 |
| IQC_37-42听 | IQC_37-42听 |
| IQC_43-100听 | IQC_43-100听 |
| IQC_当月大于18M的听数 | IQC_当月大于18M的听数 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Tins_History] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18听 |
| 19-36听 | 19-36听 |
| 37-42听 | 37-42听 |
| 43-100听 | 43-100听 |
| 100听以上 | 100听以上 |
| Months | Months |
| CreatedOn | CreatedOn |
| IQC_1-18听 | IQC_1-18听 |
| IQC_19-36听 | IQC_19-36听 |
| IQC_37-42听 | IQC_37-42听 |
| IQC_43-100听 | IQC_43-100听 |
| IQC_当月大于18M的听数 | IQC_当月大于18M的听数 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Tins_History_20250519] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18听 |
| 19-36听 | 19-36听 |
| 37-42听 | 37-42听 |
| 43-100听 | 43-100听 |
| 100听以上 | 100听以上 |
| Months | Months |
| CreatedOn | CreatedOn |
| IQC_1-18听 | IQC_1-18听 |
| IQC_19-36听 | IQC_19-36听 |
| IQC_37-42听 | IQC_37-42听 |
| IQC_43-100听 | IQC_43-100听 |

# [SNC_Rating] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| serial_number | serial_number |
| openid | openid |
| stage | stage |
| realname | realname |
| num | num |
| content | content |
| addtime | addtime |
| updatetime | updatetime |
| sendtime | sendtime |
| status | status |
| is_sync | is_sync |
| sync_time | sync_time |
| order_num | order_num |
| source | source |
| update_time | update_time |
| giftcode | giftcode |
| ans1 | ans1 |
| ans2 | ans2 |
| ans2_other | ans2_other |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| completed_questionnaire_date | completed_questionnaire_date |
| newcustomer_type | newcustomer_type |
| id | id |

# [SNC_TAG_Defination] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 名称 | 名称 |
| 标签类型 | 标签类型 |
| 标签类型Code | 标签类型Code |
| CreatedOn | CreatedOn |
| LastChange | LastChange |
| ID | ID |

# [SNC_Tagging] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Tags | Tags |
| Source | Source |
| SNCCode | SNCCode |
| Store_number | Store_number |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |

# [Source] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Offset_Day | Offset_Day |
| TA_CMT_ID | TA_CMT_ID |
| TA_Openid | TA_Openid |
| TA_Mobile | TA_Mobile |
| RegisterChannel | RegisterChannel |
| SUB_USER_NAME | SUB_USER_NAME |
| Baby_BirthDay | Baby_BirthDay |
| Current_stage | Current_stage |
| Stage | Stage |
| joindate | joindate |
| Tag | Tag |
| Buy_History | Buy_History |
| SNC_Code | SNC_Code |
| SNC_Code_ExternalContact | SNC_Code_ExternalContact |
| SNC_Code_Show | SNC_Code_Show |
| ON_CMT | ON_CMT |
| ON_CRM_Plus | ON_CRM_Plus |
| Touch_Point | Touch_Point |
| Store_Number | Store_Number |

# [SQL_ErrorLog] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| TEXT | TEXT |

# [t_bi_channel] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | QRCode_Internal |
| QrCode | QrCode |
| CustomerNumberL7 | CustomerNumberL7 |

# [TBPromoterInspection2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| IsOnDuty | IsOnDuty |
| Photo | Photo |
| FK_Store_ID | FK_Store_ID |
| FK_SystemUser_ID | FK_SystemUser_ID |
| IsDelete | IsDelete |
| CreateTime | CreateTime |
| FK_SystemUser_Create_ID | FK_SystemUser_Create_ID |
| ModifyTime | ModifyTime |
| FK_SystemUser_Modify_ID | FK_SystemUser_Modify_ID |
| FK_SystemUserDepartment_Create_ID | FK_SystemUserDepartment_Create_ID |
| IsValid | IsValid |
| LastChange | LastChange |

# [TestCol] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| table | table |
| columns | columns |

# [testtable] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Name | Name |
| Rows | Rows |

# [TOB_HAS3扫码出库记录] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 订单编号 | 订单编号 |
| gift_code | gift_code |
| 会员unionid | 会员unionid |
| 会员加密手机号 | 会员加密手机号 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 区域 | 区域 |
| 城市组 | 城市组 |
| KA Type | KA Type |
| KA Name | KA Name |
| vip_level | vip_level |
| 店主店员编号 | 店主店员编号 |
| 罐码 | 罐码 |
| 达成 | 达成 |
| 说明 | 说明 |
| 备注 | 备注 |
| cdate | cdate |

# [Trigger_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| TableName | TableName |
| DDLType | DDLType |
| CreatedOn | CreatedOn |
| ID | ID |

# [TX_AntiCheat] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | mobile_md5 |
| ip | ip |
| is_send | is_send |
| payload | payload |
| response | response |
| sent2tcdate | sent2tcdate |
| RiskLevel | RiskLevel |
| mobile | mobile |
| s_mobile | s_mobile |
| 验证日期1 | 验证日期1 |
| ksfid | ksfid |
| 区域 | 区域 |
| 省份 | 省份 |
| 城市组 | 城市组 |
| 城市 | 城市 |
| 城市级别 | 城市级别 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 客户类型 | 客户类型 |
| 所属客户组 | 所属客户组 |
| 是否是院线店 | 是否是院线店 |
| 是否有导 | 是否有导 |
| SNC编码_店员店主编码 | SNC编码_店员店主编码 |
| SNC姓名_店员店主编码 | SNC姓名_店员店主编码 |
| 会员招募时间 | 会员招募时间 |
| 家长姓名 | 家长姓名 |
| 新客类型 | 新客类型 |
| createdon | createdon |
| Comments | Comments |
| RiskType | RiskType |
| ID | ID |

# [TX_AntiCheat_20241011_snc] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | mobile_md5 |
| ip | ip |
| is_send | is_send |
| payload | payload |
| response | response |
| sent2tcdate | sent2tcdate |
| RiskLevel | RiskLevel |
| mobile | mobile |
| s_mobile | s_mobile |
| 验证日期1 | 验证日期1 |
| ksfid | ksfid |
| 区域 | 区域 |
| 省份 | 省份 |
| 城市组 | 城市组 |
| 城市 | 城市 |
| 城市级别 | 城市级别 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 客户类型 | 客户类型 |
| 所属客户组 | 所属客户组 |
| 是否是院线店 | 是否是院线店 |
| 是否有导 | 是否有导 |
| SNC编码_店员店主编码 | SNC编码_店员店主编码 |
| SNC姓名_店员店主编码 | SNC姓名_店员店主编码 |
| 会员招募时间 | 会员招募时间 |
| 家长姓名 | 家长姓名 |
| 新客类型 | 新客类型 |
| createdon | createdon |
| Comments | Comments |

# [TX_AntiCheat_20241011_snc_xinke] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | mobile_md5 |
| ip | ip |
| is_send | is_send |
| payload | payload |
| response | response |
| sent2tcdate | sent2tcdate |
| RiskLevel | RiskLevel |
| mobile | mobile |
| s_mobile | s_mobile |
| 验证日期1 | 验证日期1 |
| ksfid | ksfid |
| 区域 | 区域 |
| 省份 | 省份 |
| 城市组 | 城市组 |
| 城市 | 城市 |
| 城市级别 | 城市级别 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 客户类型 | 客户类型 |
| 所属客户组 | 所属客户组 |
| 是否是院线店 | 是否是院线店 |
| 是否有导 | 是否有导 |
| SNC编码_店员店主编码 | SNC编码_店员店主编码 |
| SNC姓名_店员店主编码 | SNC姓名_店员店主编码 |
| 会员招募时间 | 会员招募时间 |
| 家长姓名 | 家长姓名 |
| 新客类型 | 新客类型 |
| createdon | createdon |
| Comments | Comments |

# [TX_AntiCheat_20241021] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | mobile_md5 |
| ip | ip |
| is_send | is_send |
| payload | payload |
| response | response |
| sent2tcdate | sent2tcdate |
| RiskLevel | RiskLevel |
| mobile | mobile |
| s_mobile | s_mobile |
| 验证日期1 | 验证日期1 |
| ksfid | ksfid |
| 区域 | 区域 |
| 省份 | 省份 |
| 城市组 | 城市组 |
| 城市 | 城市 |
| 城市级别 | 城市级别 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 客户类型 | 客户类型 |
| 所属客户组 | 所属客户组 |
| 是否是院线店 | 是否是院线店 |
| 是否有导 | 是否有导 |
| SNC编码_店员店主编码 | SNC编码_店员店主编码 |
| SNC姓名_店员店主编码 | SNC姓名_店员店主编码 |
| 会员招募时间 | 会员招募时间 |
| 家长姓名 | 家长姓名 |
| 新客类型 | 新客类型 |
| createdon | createdon |
| Comments | Comments |
| RiskType | RiskType |

# [TX_AntiCheat_20241023] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | mobile_md5 |
| ip | ip |
| is_send | is_send |
| payload | payload |
| response | response |
| sent2tcdate | sent2tcdate |
| RiskLevel | RiskLevel |
| mobile | mobile |
| s_mobile | s_mobile |
| 验证日期1 | 验证日期1 |
| ksfid | ksfid |
| 区域 | 区域 |
| 省份 | 省份 |
| 城市组 | 城市组 |
| 城市 | 城市 |
| 城市级别 | 城市级别 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 客户类型 | 客户类型 |
| 所属客户组 | 所属客户组 |
| 是否是院线店 | 是否是院线店 |
| 是否有导 | 是否有导 |
| SNC编码_店员店主编码 | SNC编码_店员店主编码 |
| SNC姓名_店员店主编码 | SNC姓名_店员店主编码 |
| 会员招募时间 | 会员招募时间 |
| 家长姓名 | 家长姓名 |
| 新客类型 | 新客类型 |
| createdon | createdon |
| Comments | Comments |
| RiskType | RiskType |

# [TX_MOT_Session] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| motId | motId |
| motType | motType |
| motScene | motScene |
| motBrand | motBrand |
| motProduct | motProduct |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| customerMsgCount | customerMsgCount |
| id | id |

# [TX_MOT_Session_20241014] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| motId | motId |
| motType | motType |
| motScene | motScene |
| motBrand | motBrand |
| motProduct | motProduct |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| customerMsgCount | customerMsgCount |

# [TX_MOT_Session_20241216] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| motId | motId |
| motType | motType |
| motScene | motScene |
| motBrand | motBrand |
| motProduct | motProduct |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| customerMsgCount | customerMsgCount |

# [TX_MOT_Session_20250326] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| motId | motId |
| motType | motType |
| motScene | motScene |
| motBrand | motBrand |
| motProduct | motProduct |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| customerMsgCount | customerMsgCount |

# [TX_MOT_Supplement] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sessionId | sessionId |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| motSendTime | motSendTime |
| motSendTimeCD | motSendTimeCD |
| content | content |
| sendTime | sendTime |
| sendTimeCD | sendTimeCD |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| sessionId | sessionId |

# [TX_Session] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| responseTime | responseTime |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |
| id | id |

# [TX_Session_20250326] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| fellowId | fellowId |
| departmentId | departmentId |
| roundCount | roundCount |
| msgCount | msgCount |
| duration | duration |
| responseTime | responseTime |
| initiator | initiator |
| terminator | terminator |
| beginTime | beginTime |
| endTime | endTime |
| beginTimeCD | beginTimeCD |
| endTimeCD | endTimeCD |
| isConversation | isConversation |
| orders | orders |
| Is_Delete | Is_Delete |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| comments | comments |

# [TX_SSE_SSR_20241107] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_Code | Store_Code |
| Store_Name | Store_Name |
| Region | Region |
| CG | CG |
| Province | Province |
| City | City |
| City_Level | City_Level |
| Vip_Level | Vip_Level |
| Client Group | Client Group |
| OAH/Non-OAH | OAH/Non-OAH |
| 编码 | 编码 |
| 微信号(绑定的企业微信ID) | 微信号(绑定的企业微信ID) |
| IP | IP |
| 手机号 | 手机号 |
| 角色 | 角色 |

# [UpsertRateControl] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| FuncationName | FuncationName |
| SecondTimestamp | SecondTimestamp |
| UpsertCount | UpsertCount |
| CreatedOn | CreatedOn |
| ID | ID |

# [V_DAILY_NSC_Spark_S3_Bonus_RawData2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| BuyTime | BuyTime |
| area_name | area_name |
| province | province |
| city_group | city_group |
| city | city |
| ka_type | ka_type |
| ka_name | ka_name |
| SNCCode | SNCCode |
| StoreCode | StoreCode |
| Store_Name | Store_Name |
| Vip_Level | Vip_Level |
| 是否有导 | 是否有导 |
| 是否院线店 | 是否院线店 |
| Unionid | Unionid |
| Brand | Brand |
| Stage | Stage |
| ProductCode | ProductCode |
| ProductName | ProductName |
| Qty | Qty |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| 是否退单 | 是否退单 |
| 订单罐数 | 订单罐数 |
| 退单罐数 | 退单罐数 |

# [铂初分销店单Q2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 区域 | 区域 |
| CG名称 | CG名称 |
| 所在城市 | 所在城市 |
| 客户组名称 | 客户组名称 |
| 客户类型 | 客户类型 |
| 门店编号 | 门店编号 |
| 门店名称 | 门店名称 |
| 门店分类 | 门店分类 |
| 是否分销门店 | 是否分销门店 |

# [罐子] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| QRCode | QRCode |
| RN2 | RN2 |

# [星火门店详情Monthly] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | Region |
| CG | CG |
| 分销商代码 | 分销商代码 |
| 分销商姓名 | 分销商姓名 |
| TCDS编号 | TCDS编号 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 有导/无导 | 有导/无导 |
| 门店进货_金额 | 门店进货_金额 |
| 门店进货_罐数 | 门店进货_罐数 |
| 门店追回_金额 | 门店追回_金额 |
| 门店追回_罐数 | 门店追回_罐数 |
| 门店库存_金额 | 门店库存_金额 |
| 门店库存_罐数 | 门店库存_罐数 |
| 门店出库_金额 | 门店出库_金额 |
| 门店出库_罐数 | 门店出库_罐数 |
| 门店退单_罐数 | 门店退单_罐数 |
| 门店退单_金额 | 门店退单_金额 |
| 月份 | 月份 |
| CreatedOn | CreatedOn |

# [星火门店详情Monthly_20241101] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | Region |
| CG | CG |
| 分销商代码 | 分销商代码 |
| 分销商姓名 | 分销商姓名 |
| TCDS编号 | TCDS编号 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 有导/无导 | 有导/无导 |
| 门店进货_金额 | 门店进货_金额 |
| 门店进货_罐数 | 门店进货_罐数 |
| 门店追回_金额 | 门店追回_金额 |
| 门店追回_罐数 | 门店追回_罐数 |
| 门店库存_金额 | 门店库存_金额 |
| 门店库存_罐数 | 门店库存_罐数 |
| 门店出库_金额 | 门店出库_金额 |
| 门店出库_罐数 | 门店出库_罐数 |
| 门店退单_罐数 | 门店退单_罐数 |
| 门店退单_金额 | 门店退单_金额 |
| 月份 | 月份 |
| CreatedOn | CreatedOn |

# [星火门店详情Monthly202409_1101] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | Region |
| CG | CG |
| 分销商代码 | 分销商代码 |
| 分销商姓名 | 分销商姓名 |
| TCDS编号 | TCDS编号 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 有导/无导 | 有导/无导 |
| 门店进货_金额 | 门店进货_金额 |
| 门店进货_罐数 | 门店进货_罐数 |
| 门店追回_金额 | 门店追回_金额 |
| 门店追回_罐数 | 门店追回_罐数 |
| 门店库存_金额 | 门店库存_金额 |
| 门店库存_罐数 | 门店库存_罐数 |
| 门店出库_金额 | 门店出库_金额 |
| 门店出库_罐数 | 门店出库_罐数 |
| 门店退单_罐数 | 门店退单_罐数 |
| 门店退单_金额 | 门店退单_金额 |
| 月份 | 月份 |
| CreatedOn | CreatedOn |
