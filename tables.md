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
本表记录了IMS雀巢业务星火客户退款商品详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| refund_id | 退款ID |
| cus_number | 客户编号 |
| cus_uid | 客户UID |
| tcds_code | TCDS代码 |
| productcode | 产品代码 |
| boxcode | 箱码 |
| tankcode | 罐码 |
| cdate | 创建日期 |
| updatetime | 更新时间 |
| id | ID |

# [ims_nestle_business_xh_cus_stock_detail] 字段注释说明
本表记录了IMS雀巢业务星火客户库存详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| order_id | 订单ID |
| cus_uid | 客户UID |
| cus_number | 客户编号 |
| tcds_code | TCDS代码 |
| productcode | 产品代码 |
| tankcode | 罐码 |
| boxcode | 箱码 |
| status | 状态 |
| cdate | 创建日期 |
| expiredate | 过期日期 |
| updatetime | 更新时间 |
| Comments | 评论 |
| id | ID |

# [ims_nestle_hanan_survey_answer] 字段注释说明
本表记录了IMS雀巢河南调研答案信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| snc | SNC |
| openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| nickname | 昵称 |
| headimgurl | 头像URL |
| answer | 答案 |
| is_answer | 是否回答 |
| answer_time | 回答时间 |
| answer_date | 回答日期 |
| ctime | 创建时间 |
| cdate | 创建日期 |
| update_time | 更新时间 |

# [ims_qrcode_stat_3] 字段注释说明
本表记录了IMS二维码统计信息（表3）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| acid | acid |
| qid | qid |
| openid | 用户微信Openid |
| type | 类型 |
| qrcid | qrcid |
| scene_str | 场景字符串 |
| name | 名称 |
| createtime | 创建时间 |
| addtime | 添加时间 |
| updatetime | 更新时间 |
| unionid | 用户微信Unionid |
| serial_number | 序列号 |

# [ims_qrcode_stat_3_Last] 字段注释说明
本表记录了IMS二维码统计信息（表3，最新）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| serial_number | 序列号 |
| Unionid | 用户微信Unionid |
| uniacid | uniacid |
| addtime | 添加时间 |
| id | ID |

# [IncentiveTins] 字段注释说明
本表记录了激励罐数信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 购买SNC | 购买SNC |
| 1-18听 | 1-18罐 |
| 19-36听 | 19-36罐 |
| 37-42听 | 37-42罐 |
| 43-100听 | 43-100罐 |
| 100听以上 | 100罐以上 |

# [Insert_Error_Log] 字段注释说明
本表记录了插入错误日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Payload | 有效负载 |
| TargetTable | 目标表 |
| Createdon | 创建于 |
| SyncToTargetTableOn | 同步到目标表时间 |
| Id | ID |

# [IQC_KPI_Scan_Rate] 字段注释说明
本表记录了IQC KPI扫描率信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MemberLevel | 会员等级 |
| Brand | 品牌 |
| 分子 | 分子 |
| 分母 | 分母 |
| ScanRate | 扫描率 |
| rn | 行号 |
| CurrentDate | 当前日期 |
| CreatedOn | 创建时间 |

# [IQC_KPI_Scan_Rate_tin] 字段注释说明
本表记录了IQC KPI扫描率（罐）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MemberLevel | 会员等级 |
| Brand | 品牌 |
| 分子 | 分子 |
| 分母 | 分母 |
| ScanRate | 扫描率 |
| rn | 行号 |
| CurrentDate | 当前日期 |
| CreatedOn | 创建时间 |
| ID | ID |

# [KSF_DATA] 字段注释说明
本表记录了KSF数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFID |
| JoinDate | 加入日期 |
| OriginalBatchNo | 原始批次号 |
| Channel | 渠道 |
| BigArea | 大区 |
| Province | 省份 |
| CityLevel | 城市级别 |
| CityGroup | 城市组 |
| City | 城市 |
| District | 区/县 |
| StoreID | 门店ID |
| StoreName | 门店名称 |
| SSRCode | SSR代码 |
| SSRName | SSR名称 |
| MobileEnterTime | 手机录入时间 |
| ApproveTime | 审批时间 |
| SupervisorName | 主管姓名 |
| SupervisorCode | 主管代码 |
| NewCustomerType | 新客户类型 |
| MamaName | 妈妈姓名 |
| BabyBirthday | 宝宝生日 |
| BabyBirthday2 | 宝宝生日2 |
| Mobile1 | 手机号码1 |
| Mobile2 | 手机号码2 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| BuyTime | 购买时间 |
| GiftReason | 赠品原因 |
| Remark | 备注 |
| IsNewCustomer | 是否新客户 |
| FaildReason | 失败原因 |
| InvalidReason | 无效原因 |
| CreatedDate | 创建日期 |
| ByTokenID | 通过令牌ID |
| IsSentToCRM | 是否已发送至CRM |
| IsAcknowledged | 是否已确认 |
| SentToCRMDate | 发送至CRM日期 |
| GiftCode | 礼品码 |
| GiftName | 礼品名称 |
| GiftReceivedTime | 礼品接收时间 |
| ReferrerPhone | 推荐人手机 |
| GiftMechanism | 礼品机制 |
| Openid | 用户微信Openid |
| PurchaseStatus | 购买状态 |
| FirstBindingDate | 首次绑定日期 |
| ModifiedOn | 修改时间 |
| S_MOBILE | S端手机号 |
| Completed_Info | 完成信息 |
| Completed_ARI | 完成ARI |
| Completed_S1S2_Ratting | 完成S1S2评分 |
| Consumer_Validation_Date | 消费者验证日期 |
| SNC_Validation_Date | SNC验证日期 |
| LastChange | 最后更改时间 |
| IdentityName | 身份名称 |
| UserGroup | 用户组 |
| CinemaLine | 院线 |
| StoreTypeName | 门店类型名称 |
| CSR_CallResult | 客服外呼结果 |
| OrderNumber | 订单号 |
| Unionid | 用户微信Unionid |
| BU | 业务单元 |
| Comments | 评论 |
| Vip_Level | 会员等级 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| Tcds_Id | TCDS ID |
| KSFId | KSFID |

# [KSF_DATA_2022] 字段注释说明
本表记录了2022年的KSF数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFID |
| JoinDate | 加入日期 |
| NewCustomerType | 新客户类型 |
| IsNewCustomer | 是否新客户 |
| FaildReason | 失败原因 |
| Openid | 用户微信Openid |
| Mobile1 | 手机号码1 |
| S_MOBILE | S端手机号 |
| OriginalBatchNo | 原始批次号 |
| Channel | 渠道 |
| StoreID | 门店ID |
| SSRCode | SSR代码 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ByTokenID | 通过令牌ID |
| FirstBindingDate | 首次绑定日期 |
| Completed_ARI | 完成ARI |
| Consumer_Validation_Date | 消费者验证日期 |
| SNC_Validation_Date | SNC验证日期 |
| Completed_Questionnaire2_Date | 完成问卷2日期 |
| Completed_Questionnaire2_SNC | 完成问卷2SNC |
| Comments | 评论 |
| LastChange_Azure | Azure端最后更改时间 |
| CreatedDate | 创建日期 |
| IsDouble | 是否双倍 |
| Completed_Group_Date | 完成组日期 |
| GiftCode | 礼品码 |
| GiftName | 礼品名称 |
| FirstEnterGroupDate | 首次入组日期 |
| SNC_Validation_2022_Date | 2022年SNC验证日期 |
| BuyTime_2 | 第二次购买时间 |
| Remark | 备注 |
| Unionid | 用户微信Unionid |
| BU | 业务单元 |
| ModifiedOn | 修改时间 |
| Xinke_Tag | 新客标签 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| Tcds_Id | TCDS ID |
| KSFId | KSFID |

# [KSF_DATA_CC] 字段注释说明
本表记录了KSF数据（CC）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | 加入日期 |
| Unionid | 用户微信Unionid |
| S_Mobile | S端手机号 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Qty | 数量 |
| BuyTime | 购买时间 |
| Source | 来源 |
| SncCode | SNC代码 |
| SncName | SNC名称 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| Channel | 渠道 |
| BigArea | 大区 |
| Province | 省份 |
| CityGroup | 城市组 |
| City | 城市 |
| MamaName | 妈妈姓名 |
| BabyBirthday | 宝宝生日 |
| PMamaId | P端妈妈ID |
| NewCustomerType | 新客户类型 |
| OriginalBatchNo | 原始批次号 |
| CreatedOn | 创建时间 |
| SentToCRMOn | 发送至CRM时间 |
| 是否购买了IMF | 是否购买了婴幼儿配方奶粉 |
| SNC_Validation_Date | SNC验证日期 |
| KSFID | KSFID |

# [KSF_DATA_CMPA] 字段注释说明
本表记录了KSF数据（CMPA）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | 加入日期 |
| Unionid | 用户微信Unionid |
| S_Mobile | S端手机号 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Qty | 数量 |
| BuyTime | 购买时间 |
| Source | 来源 |
| SncCode | SNC代码 |
| SncName | SNC名称 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| Channel | 渠道 |
| BigArea | 大区 |
| Province | 省份 |
| CityGroup | 城市组 |
| City | 城市 |
| MamaName | 妈妈姓名 |
| BabyBirthday | 宝宝生日 |
| PMamaId | P端妈妈ID |
| NewCustomerType | 新客户类型 |
| OriginalBatchNo | 原始批次号 |
| CreatedOn | 创建时间 |
| 是否购买了IMF | 是否购买了婴幼儿配方奶粉 |

# [Linda_Gerber_20231024] 字段注释说明
本表记录了2023年10月24日Linda提供的嘉宝数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| BabyBirthday | 宝宝生日 |
| Buy_Brand | 购买品牌 |
| Has_buy_IMF | 是否购买婴幼儿配方奶粉 |
| 最近Starter OR Optima购买时间 | 最近Starter或Optima购买时间 |
| CMamaId | C端妈妈ID |
| 购买时月龄 | 购买时月龄 |
| 当前月龄 | 当前月龄 |
| S_MOBILE | S端手机号 |

# [Linda_GerberNoIMF_20231024] 字段注释说明
本表记录了2023年10月24日Linda提供的未购买IMF的嘉宝数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| BabyBirthday | 宝宝生日 |
| Buy_Brand | 购买品牌 |
| Has_buy_IMF | 是否购买婴幼儿配方奶粉 |
| 最近Starter OR Optima购买时间 | 最近Starter或Optima购买时间 |
| CMamaId | C端妈妈ID |
| 购买时月龄 | 购买时月龄 |
| 当前月龄 | 当前月龄 |
| S_MOBILE | S端手机号 |

# [Member_IQC_Tag] 字段注释说明
本表记录了会员IQC标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| IQC_2gou_1_QrCode | IQC二次购买第一次二维码 |
| IQC_2gou_1_Time | IQC二次购买第一次时间 |
| IQC_2gou_Last_QrCode | IQC二次购买最后一次二维码 |
| IQC_2gou_Last_Time | IQC二次购买最后一次时间 |
| IQC_3zhuanduan_1_QrCode | IQC三段转换第一次二维码 |
| IQC_3zhuanduan_1_Time | IQC三段转换第一次时间 |
| IQC_3zhuanduan_Last_QrCode | IQC三段转换最后一次二维码 |
| IQC_3zhuanduan_Last_Time | IQC三段转换最后一次时间 |
| Unionid | 用户微信Unionid |

# [MEMBER_Level] 字段注释说明
本表记录了会员等级信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Vip_Level | 会员等级 |
| Total_Tins | 总罐数 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |

# [Members] 字段注释说明
本表记录了会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Name | 名称 |
| Phone | 电话 |
| Email | 电子邮箱 |
| Birthday | 生日 |
| CreatedAt | 创建于 |
| UpdatedAt | 更新于 |
| Remarks | 备注 |
| Status | 状态 |
| JoinDate | 加入日期 |
| Id | ID |

# [MobileCol] 字段注释说明
本表记录了手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT] 字段注释说明
本表记录了CMT手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT_CDP] 字段注释说明
本表记录了CMT CDP手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT_CRMPlus] 字段注释说明
本表记录了CMT CRMPlus手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT_Dashboard] 字段注释说明
本表记录了CMT Dashboard手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT_Test] 字段注释说明
本表记录了CMT测试手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_CMT_Wechat] 字段注释说明
本表记录了CMT微信手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_GerberWechat] 字段注释说明
本表记录了嘉宝微信手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_GerberWechatOpr] 字段注释说明
本表记录了嘉宝微信运营手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_Archive] 字段注释说明
本表记录了NSC归档手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_Daiy_Backup] 字段注释说明
本表记录了NSC每日备份手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_DATA_DW] 字段注释说明
本表记录了NSC数据仓库手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_EC] 字段注释说明
本表记录了NSC电商手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_OLTP] 字段注释说明
本表记录了NSC OLTP手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_Report] 字段注释说明
本表记录了NSC报表手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_NSC_TempDB] 字段注释说明
本表记录了NSC临时数据库手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_PS_Data] 字段注释说明
本表记录了PS数据手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileCol_Utility] 字段注释说明
本表记录了Utility手机号列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| mobile | 手机号码 |

# [MobileTemp] 字段注释说明
本表记录了临时手机号信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tablename | 表名 |
| colname | 列名 |
| NM | NM |

# [MONITOR_JOBS] 字段注释说明
本表记录了监控作业信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Date | 日期 |
| Group | 组 |
| Category | 类别 |
| ProducerValue | 生产者值 |
| ConsumerValue | 消费者值 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |
| Date | 日期 |

# [Monitor_System] 字段注释说明
本表记录了系统监控信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | 名称 |
| Value | 值 |
| CreatedOn | 创建时间 |
| ID | ID |

# [MOT] 字段注释说明
本表记录了关键时刻（MOT）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT ID |
| MOT_DEF_No | MOT定义编号 |
| Category | 类别 |
| TA_CMT_ID | TA CMT ID |
| TA_Mobile | TA手机 |
| TA_Openid | TA Openid |
| TA_User_Name | TA用户名 |
| JoinDate | 加入日期 |
| Baby_BirthDay | 宝宝生日 |
| Stage | 阶段 |
| Current_Stage | 当前阶段 |
| Cross_Stage | 跨阶段 |
| Offset_Day | 偏移天数 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| ON_EC | 在EC上 |
| Sent_To_CMT_On | 发送至CMT时间 |
| Sent_To_CRMPlus_On | 发送至CRM Plus时间 |
| TAG | 标签 |
| Buy_History | 购买历史 |
| Due_Date | 到期日期 |
| Due_Stage | 到期阶段 |
| Status | 状态 |
| Remark | 备注 |
| Created_On | 创建于 |
| Modified_On | 修改于 |
| Sent_Update_Status_On | 发送更新状态时间 |
| SNC_Code_LastBuy | SNC代码最后购买 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| Recent_Buy_Date | 最近购买日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| S_Mobile | S端手机号 |
| MOT_PID | MOT PID |
| Unionid | 用户微信Unionid |
| TouchPoint | 触点 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| StoreID | 门店ID |
| NewCustomerType | 新客户类型 |
| XinkeTag | 新客标签 |
| ON_CSR | 在CSR上 |
| Sent_To_CSR_On | 发送至CSR时间 |
| ExternalUserID | 外部用户ID |
| WeChatName | 微信名 |
| Avatar | 头像 |
| MOT_ID | MOT ID |

# [MOT_18_42_gt_30] 字段注释说明
本表记录了MOT 18-42大于30的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| ExternalUserID | 外部用户ID |

# [MOT_18_42_gt_30_20250327] 字段注释说明
本表记录了2025年3月27日的MOT 18-42大于30的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| ExternalUserID | 外部用户ID |
| Unionid | 用户微信Unionid |

# [MOT_AL110_Bochu_TA_Daily] 字段注释说明
本表记录了AL110铂初每日目标受众信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | 当前日期 |
| Unionid | 用户微信Unionid |
| type | 类型 |
| Offset_Day | 偏移天数 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| TA_Mobile | TA手机 |
| RegisterChannel | 注册渠道 |
| SUB_USER_NAME | 子用户名 |
| Baby_BirthDay | 宝宝生日 |
| current_stage | 当前阶段 |
| Stage | 阶段 |
| joindate | 加入日期 |
| Tag | 标签 |
| Buy_History | 购买历史 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| Touch_Point | 触点 |
| Store_Number | 门店编号 |
| Sent2OADate | 发送至OA日期 |
| CreatedOn | 创建时间 |
| Remark | 备注 |
| ID | ID |

# [MOT_AL110_TagTable] 字段注释说明
本表记录了MOT AL110标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| RunDay | 运行天数 |
| RecruitDate | 招募日期 |
| Is_Buy_IMF | 是否购买婴幼儿配方奶粉 |
| Is_Allow_UseBohu_From_Link | 是否允许通过链接使用铂护 |
| Is_Sample_Bochu_200g | 是否为铂初200g样品 |
| Is_Chg_Milk | 是否转奶 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| Unionid | 用户微信Unionid |

# [MOT_AL110_TagTable2] 字段注释说明
本表记录了MOT AL110标签表2信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| RunDay | 运行天数 |
| RecruitDate | 招募日期 |
| Is_Buy_IMF | 是否购买婴幼儿配方奶粉 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |

# [MOT_Base] 字段注释说明
本表记录了MOT基础信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| Current_Stage | 当前阶段 |
| StageByCRM | CRM中的阶段 |
| 是否正在关注 | 是否正在关注公众号 |
| BabyBirthday | 宝宝生日 |
| Offset_Day | 距离生日天数 |

# [MOT_Birthday_Reminder] 字段注释说明
本表记录了MOT生日提醒信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| id | ID |
| unionid | 用户微信Unionid |
| openid | 用户微信Openid |
| name | 名称 |
| serial_number | 序列号 |
| ha12_answer | HA12答案 |
| member_type | 会员类型 |
| remember_type | 提醒类型 |
| reminder_num | 提醒次数 |
| reminder_date | 提醒日期 |
| follow | 跟进 |
| close | 关闭 |
| cdate | 创建日期 |
| finish_date | 完成日期 |
| first_send | 首次发送 |
| first_send_date | 首次发送日期 |
| batch | 批次 |
| CreatedOn | 创建时间 |
| touch_point | 触点 |
| ha12_type | HA12类型 |
| unionid | 用户微信Unionid |
| remember_type | 提醒类型 |
| reminder_num | 提醒次数 |
| reminder_date | 提醒日期 |
| batch | 批次 |

# [MOT_BoChu_AdvocacyTA] 字段注释说明
本表记录了MOT铂初宣传TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| AdvocacyDate | 宣传日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_BoChu_CallBackTA] 字段注释说明
本表记录了MOT铂初电话回访TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |
| RemindBuyDate | 提醒购买日期 |
| RemindBuyDateUpdate | 提醒购买日期更新 |
| Status | 状态 |
| CallBackDate | 回访日期 |
| CampaleteDate | 完成日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |

# [MOT_BoChu_PurchaseBoChu] 字段注释说明
本表记录了MOT铂初购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| S1 | S1 |
| S2 | S2 |
| S3 | S3 |

# [MOT_BoChu_RecentPurchase] 字段注释说明
本表记录了MOT铂初最近购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| EmptyDay | 空罐天数 |
| RemindDay | 提醒天数 |
| UpdateDate | 更新日期 |

# [MOT_BoChu_RecentPurchaseS23] 字段注释说明
本表记录了MOT铂初最近购买S23信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| RecentPurchaseS23Date | 最近购买S23日期 |

# [MOT_BoChu_RemindBuyS23TA] 字段注释说明
本表记录了MOT铂初提醒购买S23的TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| RecruitDate | 招募日期 |
| RecentPurchaseS23Date | 最近购买S23日期 |
| ReBuyTimes | 复购次数 |
| CreatedDate | 创建日期 |
| ID | ID |
| Unionid | 用户微信Unionid |
| RecentPurchaseS23Date | 最近购买S23日期 |

# [MOT_BoChu_RemindBuyTA] 字段注释说明
本表记录了MOT铂初提醒购买TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |
| RecruitDate | 招募日期 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindBuyDate | 提醒购买日期 |
| Status | 状态 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |

# [MOT_BoChu_TagTable] 字段注释说明
本表记录了MOT铂初标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| RunDay | 运行天数 |
| TargetType | 目标类型 |
| RecentPurchaseS23Date | 最近购买S23日期 |
| IsBuyBoChuS3 | 是否购买铂初S3 |
| IsBuyBoChuS2 | 是否购买铂初S2 |
| IsBuyBoChuS1 | 是否购买铂初S1 |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| RemindBuyDate | 提醒购买日期 |
| ReBuyTimes | 复购次数 |
| StageGroup | 阶段组 |
| RemindCSDate1 | 提醒CS日期1 |
| RemindCSDate2 | 提醒CS日期2 |
| RemindCSDate3 | 提醒CS日期3 |
| RemindCSDate4 | 提醒CS日期4 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| Unionid | 用户微信Unionid |

# [MOT_BoChu_WOM_OldTA] 字段注释说明
本表记录了MOT铂初口碑（WOM）旧TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| ABGroup | AB组 |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThirdRemindDate | 第三次提醒日期 |
| ForthRemindDate | 第四次提醒日期 |
| FifthRemindDate | 第五次提醒日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| ABGroupNew | 新AB组 |
| Unionid | 用户微信Unionid |

# [MOT_BochuGerber_TA] 字段注释说明
本表记录了MOT铂初嘉宝TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Runday | 运行天数 |
| TargetType | 目标类型 |
| BrandGroup | 品牌组 |
| Purchase_Starter | 购买Starter |
| Purchase_谷启嘉贝 | 购买谷启嘉贝 |
| Purchase_米粥 | 购买米粥 |
| Coupon_Usetime | 优惠券使用时间 |
| StartersFirstRemindDate | Starters第一次提醒日期 |
| StartersSecondRemindDate | Starters第二次提醒日期 |
| OptimaFirstRemindDate | Optima第一次提醒日期 |
| OptimaSecondRemindDate | Optima第二次提醒日期 |
| AmberFirstRemindDate | Amber第一次提醒日期 |
| AmberSecondRemindDate | Amber第二次提醒日期 |
| EndDate | 结束日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_BochuGerber_TagTable] 字段注释说明
本表记录了MOT铂初嘉宝标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| GetBochuTime | 获取铂初时间 |
| Purchase_嘉宝产品 | 购买嘉宝产品 |
| RecentBuyBrand | 最近购买品牌 |
| RecentBuyTime | 最近购买时间 |
| CreateDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_BoChuSample_TA] 字段注释说明
本表记录了MOT铂初样品TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| TargetType | 目标类型 |
| GetSampleTime | 获取样品时间 |
| RecentBuyTime | 最近购买时间 |
| RecentBuyCount | 最近购买数量 |
| EmptyDate | 空罐日期 |
| FirstTriggerDate | 第一次触发日期 |
| SecondTriggerDate | 第二次触发日期 |
| BoChuHABuyPID | 铂初HA购买PID |
| EndDate | 结束日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_BoChuSample_TagTable] 字段注释说明
本表记录了MOT铂初样品标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| GetSampleTime | 获取样品时间 |
| RecentBuyBrand | 最近购买品牌 |
| RecentBuyCount | 最近购买数量 |
| RecentBuyTime | 最近购买时间 |
| EmptyDate | 空罐日期 |
| GapDay | 间隔天数 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_Call_Center] 字段注释说明
本表记录了MOT呼叫中心信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Mobile | 手机号码 |
| QuestionnaireType | 问卷类型 |
| MOT_DEF_No | MOT定义编号 |
| CreatedOn | 创建时间 |
| SentToCRMOn | 发送至CRM时间 |
| Mobile | 手机号码 |
| QuestionnaireType | 问卷类型 |
| MOT_DEF_No | MOT定义编号 |

# [MOT_Defination] 字段注释说明
本表记录了MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | 编号 |
| Category | 类别 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| Status | 状态 |
| CTA | 行动号召 |
| TouchPoints | 触点 |
| Descriptions | 描述 |
| Due_Date | 到期日期 |
| Remark | 备注 |
| Enabled | 是否启用 |
| Due_Stage | 到期阶段 |
| Brand | 品牌 |
| Product | 产品 |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Label_Level_3 | 标签级别3 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| Phase | 阶段 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Stage | 阶段 |
| No | 编号 |

# [MOT_Defination_20230401] 字段注释说明
本表记录了2023年4月1日的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | 编号 |
| Category | 类别 |
| Label_Level_2 | 标签级别2 |
| Label_Level_3 | 标签级别3 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| TouchPoints | 触点 |
| Description | 描述 |
| Due_Date | 到期日期 |
| Remark | 备注 |
| Enabled | 是否启用 |
| TA | 目标受众 |
| Tagging | 标记 |
| old Descriptions | 旧描述 |
| new Descriptions | 新描述 |

# [MOT_Defination_20240903] 字段注释说明
本表记录了2024年9月3日的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| No | 编号 |
| Category | 类别 |
| Label_Level_2 | 标签级别2 |
| Label_Level_3 | 标签级别3 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| TouchPoints | 触点 |
| Descriptions | 描述 |
| Due_Date | 到期日期 |
| Remark | 备注 |
| Enabled | 是否启用 |
| TA | 目标受众 |
| LastChange | 最后更改时间 |
| Due_Stage | 到期阶段 |
| Brand | 品牌 |
| Product | 产品 |
| Phase | 阶段 |
| CreatedOn | 创建时间 |

# [MOT_Defination_20240903_1] 字段注释说明
本表记录了2024年9月3日的MOT定义信息（表1）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT定义编号 |
| CD_Trigger_Qty | CD触发数量 |
| CD_Trigger_Min_Date | CD触发最小日期 |
| CD_Trigger_Last_Date | CD触发最后日期 |
| Status | 状态 |
| Brand | 品牌 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| CTA or not | 是否CTA |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Descriptions | 描述 |
| Remark | 备注 |
| Category | 类别 |
| TouchPoints | 触点 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240904_Xia] 字段注释说明
本表记录了2024年9月4日Xia提供的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT定义编号 |
| CD_Trigger_Qty | CD触发数量 |
| CD_Trigger_Min_Date | CD触发最小日期 |
| CD_Trigger_Last_Date | CD触发最后日期 |
| Status | 状态 |
| Brand | 品牌 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Descriptions | 描述 |
| Remark | 备注 |
| Category | 类别 |
| TouchPoints | 触点 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906] 字段注释说明
本表记录了2024年9月6日的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT定义编号 |
| CD_Trigger_Qty | CD触发数量 |
| CD_Trigger_Min_Date | CD触发最小日期 |
| CD_Trigger_Last_Date | CD触发最后日期 |
| Status | 状态 |
| Enabled | 是否启用 |
| Brand | 品牌 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| CTA or not | 是否CTA |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Descriptions | 描述 |
| Remark | 备注 |
| Category | 类别 |
| TouchPoints | 触点 |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906_Kaylee] 字段注释说明
本表记录了2024年9月6日Kaylee提供的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT定义编号 |
| CD_Trigger_Qty | CD触发数量 |
| CD_Trigger_Min_Date | CD触发最小日期 |
| CD_Trigger_Last_Date | CD触发最后日期 |
| Status | 状态 |
| Enabled | 是否启用 |
| Brand | 品牌 |
| Stage | 阶段 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| CTA or not | 是否CTA |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Descriptions | 描述 |
| Remark | 备注 |
| Category | 类别 |
| TouchPoints | 触点 |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Defination_20240906_XiaLan] 字段注释说明
本表记录了2024年9月6日XiaLan提供的MOT定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_No | MOT定义编号 |
| CD_Trigger_Qty | CD触发数量 |
| CD_Trigger_Min_Date | CD触发最小日期 |
| CD_Trigger_Last_Date | CD触发最后日期 |
| Status | 状态 |
| Enabled | 是否启用 |
| Brand | 品牌 |
| Stage | 阶段 |
| Objective | 目的 |
| Mot_Type | MOT类型 |
| CTA or not | 是否CTA |
| TA | 目标受众 |
| Label_Level_2 | 标签级别2 |
| Descriptions | 描述 |
| Remark | 备注 |
| Category | 类别 |
| TouchPoints | 触点 |
| MOT话术 | MOT话术 |
| 备注说明 | 备注说明 |

# [MOT_Gerber_CNYTA] 字段注释说明
本表记录了MOT嘉宝春节TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThiredRemindDate | 第三次提醒日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_Gerber_Information] 字段注释说明
本表记录了MOT嘉宝信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| Current_Stage | 当前阶段 |
| StageByCRM | CRM中的阶段 |
| 是否正在关注 | 是否正在关注公众号 |
| BabyBirthday | 宝宝生日 |
| Offset_Day | 距离生日天数 |
| CouponUseTime | 优惠券使用时间 |
| TouchPoint | 触点 |
| PureStarter | 纯Starter |
| Purchase_嘉宝产品 | 购买嘉宝产品 |
| Purchase_谷启嘉贝 | 购买谷启嘉贝 |
| Purchase_米粥 | 购买米粥 |
| 绑定导购 | 绑定的导购 |
| 导购是否在职 | 导购是否在职 |
| 绑定导购门店 | 绑定的导购门店 |
| UpdateDate | 更新日期 |

# [MOT_Gerber_IsPureStarter] 字段注释说明
本表记录了MOT嘉宝是否为纯Starter的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Purchase_嘉宝产品 | 购买嘉宝产品 |
| PureStarter | 纯Starter |
| Purchase_Starter | 购买Starter |
| Purchase_谷启嘉贝 | 购买谷启嘉贝 |
| Purchase_米粥 | 购买米粥 |
| UpdateDate | 更新日期 |

# [MOT_Gerber_IsUseCoupon] 字段注释说明
本表记录了MOT嘉宝是否使用优惠券的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| use_time | 使用时间 |
| snc_code | SNC代码 |
| TouchPoint | 触点 |

# [MOT_Gerber_JiaoYaoTA] 字段注释说明
本表记录了MOT嘉宝嚼咬TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| TargetType | 目标类型 |
| RunDay | 运行天数 |
| CouponUseTimes | 优惠券使用次数 |
| JourneyEndDate | 旅程结束日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_Gerber_NewCustomer] 字段注释说明
本表记录了MOT嘉宝新客信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| UseDate | 使用日期 |
| CreatedDate | 创建日期 |
| 筛选时最近绑定导购 | 筛选时最近绑定导购 |
| 筛选时导购是否在职 | 筛选时导购是否在职 |
| Unionid | 用户微信Unionid |

# [MOT_Gerber_TA] 字段注释说明
本表记录了MOT嘉宝TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| CreatedDate | 创建日期 |
| RunDay | 运行天数 |
| EndDate | 结束日期 |
| 筛选时最近绑定导购 | 筛选时最近绑定导购 |
| 筛选时导购是否在职 | 筛选时导购是否在职 |
| Type | 类型 |
| UpdateDate | 更新日期 |
| Unionid | 用户微信Unionid |

# [MOT_Gerber_TunMoTA] 字段注释说明
本表记录了MOT嘉宝吞咽TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| RunDay | 运行天数 |
| CouponUseTimes | 优惠券使用次数 |
| JourneyEndDate | 旅程结束日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_1842Tin_TA2] 字段注释说明
本表记录了MOT HA 18-42罐TA2信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UNIONID | 用户微信Unionid |
| TAG | 标签 |
| Sent2CRMPlus | 发送至CRMPlus |
| Sent2CRMPlus_2 | 发送至CRMPlus_2 |
| Sent2CRMPlus_3 | 发送至CRMPlus_3 |
| Sent2CRMPlus_4 | 发送至CRMPlus_4 |
| Sent2CRMPlus_5 | 发送至CRMPlus_5 |
| Sent2CRMPlus_6 | 发送至CRMPlus_6 |
| Sent2CRMPlus_7 | 发送至CRMPlus_7 |
| Sent2CRMPlus_8 | 发送至CRMPlus_8 |
| Sent2CRMPlus_9 | 发送至CRMPlus_9 |
| Createdon | 创建于 |

# [MOT_HA_42Tin_TA] 字段注释说明
本表记录了MOT HA 42罐TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UnionidS | UnionidS |
| Unionid | 用户微信Unionid |
| s_mobile | S端手机号 |
| CMamaId | C端妈妈ID |
| PMamaId | P端妈妈ID |
| MOBILE | 手机号码 |
| Should1_Send_Date | 应发送日期1 |
| Should2_Send_Date | 应发送日期2 |
| Insert_MOT1_Date | 插入MOT1日期 |
| Insert_MOT2_Date | 插入MOT2日期 |

# [MOT_HA_AdvocacyTA] 字段注释说明
本表记录了MOT HA宣传TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| AdvocacyDate | 宣传日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_CallBackTA] 字段注释说明
本表记录了MOT HA电话回访TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |
| RemindBuyDate | 提醒购买日期 |
| RemindBuyDateUpdate | 提醒购买日期更新 |
| CallBackDate | 回访日期 |
| CampaleteDate | 完成日期 |
| Remark | 备注 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |

# [MOT_HA_CrossStageTA] 字段注释说明
本表记录了MOT HA跨阶段TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| Tag | 标签 |
| IsBirthdayS3TA | 是否生日S3 TA |
| IsBirthdayS4TA | 是否生日S4 TA |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThirdRemindDate | 第三次提醒日期 |
| ForthRemindDate | 第四次提醒日期 |
| UpdateDate | 更新日期 |
| CreateDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_EmptyABTestTA] 字段注释说明
本表记录了MOT HA空罐AB测试TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| SNCCode | SNC代码 |
| IsOnJob | 是否在职 |
| StoreCode | 门店代码 |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| RemindDate | 提醒日期 |
| ABGroup | AB组 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_EmptyABTestTA_0801] 字段注释说明
本表记录了2023年8月1日的MOT HA空罐AB测试TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| SNCCode | SNC代码 |
| IsOnJob | 是否在职 |
| StoreCode | 门店代码 |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| RemindDate | 提醒日期 |
| ABgroup | AB组 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_EmptyTA] 字段注释说明
本表记录了MOT HA空罐TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| 招募时间 | 招募时间 |
| 提醒复购时最近购买时间 | 提醒复购时最近购买时间 |
| 提醒复购时最近购买罐数 | 提醒复购时最近购买罐数 |
| 本次提醒复购日期 | 本次提醒复购日期 |
| 本次提醒应空罐日期 | 本次提醒应空罐日期 |
| 空罐日期 | 空罐日期 |

# [MOT_HA_NNSTA] 字段注释说明
本表记录了MOT HA NNSTA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| TargetType | 目标类型 |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThiredRemindDate | 第三次提醒日期 |
| ForthRemindDate | 第四次提醒日期 |
| IsNewDate | 是否新日期 |
| Status | 状态 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_PurchaseS3] 字段注释说明
本表记录了MOT HA S3购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| NoS3Purchase | 无S3购买 |
| UpdateDate | 更新日期 |

# [MOT_HA_PurchaseS4] 字段注释说明
本表记录了MOT HA S4购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| NoS4Purchase | 无S4购买 |
| UpdateDate | 更新日期 |

# [MOT_HA_QuestionnaireTag] 字段注释说明
本表记录了MOT HA问卷标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| QuestionnaireType | 问卷类型 |
| TagQuestion2_DXW | 标签问题2_DXW |
| TagQuestion1_C | 标签问题1_C |
| Tag_DXW_New | 新DXW标签 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |
| QuestionnaireType | 问卷类型 |

# [MOT_HA_RecentPurchase] 字段注释说明
本表记录了MOT HA最近购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| EmptyDay | 空罐天数 |
| RemindDay | 提醒天数 |
| UpdateDate | 更新日期 |

# [MOT_HA_RemindBuy_Overlap] 字段注释说明
本表记录了MOT HA提醒购买重叠信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT ID |
| MOT_DEF_No | MOT定义编号 |
| Category | 类别 |
| TA_CMT_ID | TA CMT ID |
| TA_Mobile | TA手机 |
| TA_Openid | TA Openid |
| TA_User_Name | TA用户名 |
| JoinDate | 加入日期 |
| Baby_BirthDay | 宝宝生日 |
| Stage | 阶段 |
| Current_Stage | 当前阶段 |
| Cross_Stage | 跨阶段 |
| Offset_Day | 偏移天数 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| ON_EC | 在EC上 |
| Sent_To_CMT_On | 发送至CMT时间 |
| Sent_To_CRMPlus_On | 发送至CRM Plus时间 |
| TAG | 标签 |
| Buy_History | 购买历史 |
| Due_Date | 到期日期 |
| Due_Stage | 到期阶段 |
| Status | 状态 |
| Remark | 备注 |
| Created_On | 创建于 |
| Modified_On | 修改于 |
| Sent_Update_Status_On | 发送更新状态时间 |
| SNC_Code_LastBuy | SNC代码最后购买 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| Recent_Buy_Date | 最近购买日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| S_Mobile | S端手机号 |
| MOT_PID | MOT PID |
| Unionid | 用户微信Unionid |
| TouchPoint | 触点 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| StoreID | 门店ID |
| NewCustomerType | 新客户类型 |
| XinkeTag | 新客标签 |
| ON_CSR | 在CSR上 |
| Sent_To_CSR_On | 发送至CSR时间 |

# [MOT_HA_RemindBuyTA] 字段注释说明
本表记录了MOT HA提醒购买TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| 招募时间 | 招募时间 |
| 提醒复购时最近购买时间 | 提醒复购时最近购买时间 |
| 提醒复购时最近购买罐数 | 提醒复购时最近购买罐数 |
| 本次提醒复购日期 | 本次提醒复购日期 |
| 本次提醒应空罐日期 | 本次提醒应空罐日期 |
| 复购次数 | 复购次数 |
| 创建时间 | 创建时间 |
| Unionid | 用户微信Unionid |
| 复购次数 | 复购次数 |

# [MOT_HA_Review] 字段注释说明
本表记录了MOT HA回顾信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_DEF_NO | MOT定义编号 |
| BeginDate | 开始日期 |
| EndDate | 结束日期 |
| Receive | 接收 |
| Success | 成功 |
| S1 | S1 |
| S2 | S2 |
| S3 | S3 |
| Avg | 平均值 |

# [MOT_HA_S2_Sample_TA] 字段注释说明
本表记录了MOT HA S2样品TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| Day1_Date | 第1天日期 |
| Day3_Date | 第3天日期 |
| Is_Buy_HAS2 | 是否购买HA S2 |
| Is_PreNAN_User | 是否PreNAN用户 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID | ID |

# [MOT_HA_TagTable] 字段注释说明
本表记录了MOT HA标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| 绑定导购 | 绑定的导购 |
| 导购是否在职 | 导购是否在职 |
| 绑定导购门店 | 绑定的导购门店 |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| RunDay | 运行天数 |
| TargetType | 目标类型 |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| EmptyDay | 空罐天数 |
| RemindBuyDate | 提醒购买日期 |
| RemindEmptyDate | 提醒空罐日期 |
| ReBuyTimes | 复购次数 |
| Group | 组 |
| NoS3Purchase | 无S3购买 |
| NoS4Purchase | 无S4购买 |
| IsNew | 是否新 |
| IsNewDate | 是否新日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_WOM_OldTA] 字段注释说明
本表记录了MOT HA口碑（WOM）旧TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThiredRemindDate | 第三次提醒日期 |
| ForthRemindDate | 第四次提醒日期 |
| FifthRemindDate | 第五次提醒日期 |
| SixthRemindDate | 第六次提醒日期 |
| SeventhRemindDate | 第七次提醒日期 |
| Status | 状态 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |

# [MOT_HA_WOM_OldTA_Wrong] 字段注释说明
本表记录了MOT HA口碑（WOM）旧TA错误信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| FirstRemindDate | 第一次提醒日期 |
| SecondRemindDate | 第二次提醒日期 |
| ThiredRemindDate | 第三次提醒日期 |
| ForthRemindDate | 第四次提醒日期 |
| Status | 状态 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |

# [MOT_HAS3_720_KAB_TA_Daily] 字段注释说明
本表记录了MOT HAS3 720 KAB每日TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | 当前日期 |
| Unionid | 用户微信Unionid |
| Offset_Day | 偏移天数 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| TA_Mobile | TA手机 |
| RegisterChannel | 注册渠道 |
| SUB_USER_NAME | 子用户名 |
| Baby_BirthDay | 宝宝生日 |
| current_stage | 当前阶段 |
| Stage | 阶段 |
| joindate | 加入日期 |
| Tag | 标签 |
| Buy_History | 购买历史 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| Touch_Point | 触点 |
| Store_Number | 门店编号 |
| CreatedOn | 创建时间 |
| is_Maizhi | 是否麦智 |
| ID | ID |

# [MOT_HAS3_760_Laoke_TA_Daily] 字段注释说明
本表记录了MOT HAS3 760老客每日TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | 当前日期 |
| Unionid | 用户微信Unionid |
| Offset_Day | 偏移天数 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| TA_Mobile | TA手机 |
| RegisterChannel | 注册渠道 |
| SUB_USER_NAME | 子用户名 |
| Baby_BirthDay | 宝宝生日 |
| current_stage | 当前阶段 |
| Stage | 阶段 |
| joindate | 加入日期 |
| Tag | 标签 |
| Buy_History | 购买历史 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| Touch_Point | 触点 |
| Store_Number | 门店编号 |
| Sent2OADate | 发送至OA日期 |
| CreatedOn | 创建时间 |
| is_month_invalid | 月份是否无效 |
| ID | ID |

# [MOT_HAS3_760_Xinke_TA_Daily] 字段注释说明
本表记录了MOT HAS3 760新客每日TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Current_Day | 当前日期 |
| Unionid | 用户微信Unionid |
| Offset_Day | 偏移天数 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| TA_Mobile | TA手机 |
| RegisterChannel | 注册渠道 |
| SUB_USER_NAME | 子用户名 |
| Baby_BirthDay | 宝宝生日 |
| current_stage | 当前阶段 |
| Stage | 阶段 |
| joindate | 加入日期 |
| Tag | 标签 |
| Buy_History | 购买历史 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| Touch_Point | 触点 |
| Store_Number | 门店编号 |
| CreatedOn | 创建时间 |
| ID | ID |

# [MOT_ICEF_Sample_Potential_TA] 字段注释说明
本表记录了MOT ICEF样品潜在TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| Potential_Sample_Type | 潜在样品类型 |
| LastBuy_Date | 最后购买日期 |
| BabyBirthday | 宝宝生日 |
| StageByCRM | CRM中的阶段 |
| Buy_ICEF_DATE | 购买ICEF日期 |
| Receive_Sample_Date | 接收样品日期 |
| InsertMOT_6M | 插入MOT 6M |
| InsertMOT_7M | 插入MOT 7M |
| InsertMOT_8M | 插入MOT 8M |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |
| Potential_Sample_Type | 潜在样品类型 |

# [MOT_ICEF_Sample_TA] 字段注释说明
本表记录了MOT ICEF样品TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| ICEF_Sample_Type | ICEF样品类型 |
| Ordernum | 订单号 |
| TouchPoint | 触点 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| OrderCreateTime | 订单创建时间 |
| IsReturn | 是否退货 |
| Return_ICEF | 退货ICEF |
| Return_Date | 退货日期 |
| Buy_ICEF | 购买ICEF |
| Buy_ICEF_date | 购买ICEF日期 |
| InsertMOT | 插入MOT |
| InsertMOT_Day1 | 插入MOT第一天 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |
| ICEF_Sample_Type | ICEF样品类型 |

# [MOT_ICEF_TA] 字段注释说明
本表记录了MOT ICEF TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionId | 用户微信Unionid |
| PSampleDate | P样品日期 |
| ASampleDate | A样品日期 |
| IsBuyPHW | 是否购买PHW |
| IsBuyA2 | 是否购买A2 |
| HALastBuyTime | HA最后购买时间 |
| ABLastBuyTime | AB最后购买时间 |
| BabyBirthday | 宝宝生日 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID | ID |

# [MOT_ICEF_TA_Daily] 字段注释说明
本表记录了MOT ICEF每日TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionId | 用户微信Unionid |
| Tag | 标签 |
| PSampleDate | P样品日期 |
| PHW_RunDay | PHW运行天数 |
| ASampleDate | A样品日期 |
| A2_RunDay | A2运行天数 |
| BabyStage | 宝宝阶段 |
| BabyStageRunDay | 宝宝阶段运行天数 |
| FirstBuyICEF | 首次购买ICEF |
| FirstBuyICEFRunDay | 首次购买ICEF运行天数 |
| Is_Recent | 是否最近 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID | ID |

# [MOT_Incentive_TagTable] 字段注释说明
本表记录了MOT激励标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| FirstBrandTag | 第一品牌标签 |
| FirstRemindDate | 第一次提醒日期 |
| SecondBrandTag | 第二品牌标签 |
| SecondRemindDate | 第二次提醒日期 |
| ThirdBrandTag | 第三品牌标签 |
| ThirdRemindDate | 第三次提醒日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| Unionid | 用户微信Unionid |

# [MOT_IQC_HA] 字段注释说明
本表记录了MOT IQC HA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT ID |
| MOT_DEF_No | MOT定义编号 |
| Category | 类别 |
| TA_CMT_ID | TA CMT ID |
| TA_Mobile | TA手机 |
| TA_Openid | TA Openid |
| TA_User_Name | TA用户名 |
| JoinDate | 加入日期 |
| Baby_BirthDay | 宝宝生日 |
| Stage | 阶段 |
| Current_Stage | 当前阶段 |
| Cross_Stage | 跨阶段 |
| Offset_Day | 偏移天数 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| ON_EC | 在EC上 |
| Sent_To_CMT_On | 发送至CMT时间 |
| Sent_To_CRMPlus_On | 发送至CRM Plus时间 |
| TAG | 标签 |
| Buy_History | 购买历史 |
| Due_Date | 到期日期 |
| Due_Stage | 到期阶段 |
| Status | 状态 |
| Remark | 备注 |
| Created_On | 创建于 |
| Modified_On | 修改于 |
| Sent_Update_Status_On | 发送更新状态时间 |
| SNC_Code_LastBuy | SNC代码最后购买 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| Recent_Buy_Date | 最近购买日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| S_Mobile | S端手机号 |
| MOT_PID | MOT PID |
| Unionid | 用户微信Unionid |
| TouchPoint | 触点 |
| Priority | 优先级 |
| Generating_Frequency | 生成频率 |
| StoreID | 门店ID |
| NewCustomerType | 新客户类型 |
| XinkeTag | 新客标签 |
| ON_CSR | 在CSR上 |
| Sent_To_CSR_On | 发送至CSR时间 |
| ExternalUserID | 外部用户ID |
| WeChatName | 微信名 |
| Avatar | 头像 |
| Is_Pushed | 是否已推送 |
| MOT_ID | MOT ID |

# [MOT_IQC_HA_Buy_Scan_Tar] 字段注释说明
本表记录了MOT IQC HA购买扫描目标信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Mobile | 手机号码 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| SUB_USER_NAME | 子用户名 |
| joindate | 加入日期 |
| Baby_BirthDay | 宝宝生日 |
| Buy_Stage | 购买阶段 |
| Current_stage | 当前阶段 |
| Offset_Day | 偏移天数 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| TAG | 标签 |
| Store_Number | 门店编号 |
| ON_CRM_Plus | 在CRM Plus上 |
| TankBarCode | 罐条码 |
| Buy_RN | 购买行号 |
| 购买日期 | 购买日期 |
| BuyTime | 购买时间 |
| Can_Count | 罐数 |
| QRCode_Internal | 内部二维码 |
| QrCode | 二维码 |
| Scanning_Time | 扫描时间 |
| Scan_Brand | 扫描品牌 |
| Scan_Stage | 扫描阶段 |
| Scan_TA_User_Name | 扫描TA用户名 |
| Scan_RN | 扫描行号 |
| MAX_ScanRN | 最大扫描行号 |
| FirstScanIsHA | 首次扫描是否为HA |
| ProductCode | 产品代码 |
| Create_Time | 创建时间 |
| Last_Modify_Time | 最后修改时间 |
| Product_Stage | 产品阶段 |
| ID | ID |

# [MOT_IQC_HA_Buy_Scan_Tar_V2] 字段注释说明
本表记录了MOT IQC HA购买扫描目标信息V2。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Mobile | 手机号码 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| SUB_USER_NAME | 子用户名 |
| joindate | 加入日期 |
| Baby_BirthDay | 宝宝生日 |
| Buy_Stage | 购买阶段 |
| Current_stage | 当前阶段 |
| Offset_Day | 偏移天数 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| TAG | 标签 |
| Store_Number | 门店编号 |
| ON_CRM_Plus | 在CRM Plus上 |
| TankBarCode | 罐条码 |
| Buy_RN | 购买行号 |
| 购买日期 | 购买日期 |
| BuyTime | 购买时间 |
| Can_Count | 罐数 |
| QRCode_Internal | 内部二维码 |
| QrCode | 二维码 |
| Scanning_Time | 扫描时间 |
| Scan_Brand | 扫描品牌 |
| Scan_Stage | 扫描阶段 |
| Scan_TA_User_Name | 扫描TA用户名 |
| Scan_RN | 扫描行号 |
| MAX_ScanRN | 最大扫描行号 |
| FirstScanIsHA | 首次扫描是否为HA |
| ProductCode | 产品代码 |
| Create_Time | 创建时间 |
| Last_Modify_Time | 最后修改时间 |
| Product_Stage | 产品阶段 |
| ID | ID |

# [MOT_JD_CallBackTA] 字段注释说明
本表记录了MOT京东电话回访TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | 外部用户ID |
| TargetType | 目标类型 |
| Openid | 用户微信Openid |
| Executor | 执行人 |
| ReBuyTimes | 复购次数 |
| RemindBuyDate | 提醒购买日期 |
| RemindBuyDateUpdate | 提醒购买日期更新 |
| Status | 状态 |
| CallBackDate | 回访日期 |
| CampaleteDate | 完成日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| ExternalUserId | 外部用户ID |
| TargetType | 目标类型 |

# [MOT_JD_HighPotentialTA] 字段注释说明
本表记录了MOT京东高潜力TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | 外部用户ID |
| RunDay | 运行天数 |
| Executor | 执行人 |
| TagName | 标签名称 |
| TagCreateTime | 标签创建时间 |
| IsBeDevelopingTA | 是否发展中TA |
| BeDevelopingDate | 发展中日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| ExternalUserId | 外部用户ID |
| TagName | 标签名称 |

# [MOT_JD_PurchaseTA] 字段注释说明
本表记录了MOT京东购买TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | 用户微信Openid |
| ExternalUserId | 外部用户ID |
| Executor | 执行人 |
| TargetType | 目标类型 |
| RunDay | 运行天数 |
| PurchaseGroup | 购买组 |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| RemindBuyDate | 提醒购买日期 |
| ReBuyTimes | 复购次数 |
| BeDevelopingTADate | 发展中TA日期 |
| BeLoyalTADate | 忠诚TA日期 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| ExternalUserId | 外部用户ID |
| TargetType | 目标类型 |

# [MOT_JD_RecentPurchase_HA] 字段注释说明
本表记录了MOT京东最近购买HA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| UserLogAcct | 用户登录账户 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| UpdateDate | 更新日期 |
| UserLogAcct | 用户登录账户 |

# [MOT_JD_RecentPurchase_PreNan] 字段注释说明
本表记录了MOT京东最近购买PreNan信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| userLogAcct | 用户登录账户 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| UpdateDate | 更新日期 |

# [MOT_JD_RemindBuyTA] 字段注释说明
本表记录了MOT京东提醒购买TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ExternalUserId | 外部用户ID |
| TargetType | 目标类型 |
| Openid | 用户微信Openid |
| Executor | 执行人 |
| RecruitDate | 招募日期 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindBuyDate | 提醒购买日期 |
| ReBuyTimes | 复购次数 |
| Status | 状态 |
| CreatedDate | 创建日期 |
| ExternalUserId | 外部用户ID |
| TargetType | 目标类型 |
| ReBuyTimes | 复购次数 |

# [MOT_Member_Temp] 字段注释说明
本表记录了MOT临时会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CMT_ID | CMT ID |
| Openid | 用户微信Openid |
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| SUB_USER_NAME | 子用户名 |
| SNC_Code | SNC代码 |
| JoinDate | 加入日期 |
| Current_Stage | 当前阶段 |
| StageByCRM | CRM中的阶段 |
| Always_Follow | 始终关注 |
| Refollow | 重新关注 |
| RegisterChannel | 注册渠道 |
| Specialty | 专业 |
| Tag | 标签 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| SNC_Code_Show_TOB | SNC代码显示TOB |
| babyBirthday | 宝宝生日 |
| PreNAN_Recruit_BabyBirthDay | PreNAN招募宝宝生日 |
| Offset_Day | 偏移天数 |
| First_week | 第一周 |
| HA_RecruitTime | HA招募时间 |
| AL110_RecruitTime | AL110招募时间 |
| PreNAN_RecruitTime | PreNAN招募时间 |
| Specialty_Al110 | 专业Al110 |
| Specialty_PreNan | 专业PreNan |
| GC_PT_RecruitTime | GC PT招募时间 |
| GC_LN_RecruitTime | GC LN招募时间 |
| PreNAN_Wight | PreNAN重量 |
| Recent_Buy_SNC | 最近购买SNC |
| RECENT_BUY_PRODUCT_BRAND | 最近购买产品品牌 |
| RECENT_BUY_PRODUCT_STAGE | 最近购买产品阶段 |
| RECENT_BUY_PRODUCT_NET_WEIGHT | 最近购买产品净重 |
| RECENT_BUY_PRODUCT_Qty | 最近购买产品数量 |
| Recent_Buy_Product_BUYTIME | 最近购买产品购买时间 |
| Recent_Buy_Product_ProductCode | 最近购买产品代码 |
| Recent_Buy_Product_ProductName | 最近购买产品名称 |
| Recent_Buy_AL110_Is_First | 最近购买AL110是否首次 |
| Recent_Buy_HA_S1S2_Is_First | 最近购买HA S1S2是否首次 |
| Recent_Buy_PT_S1S2_Is_First | 最近购买PT S1S2是否首次 |
| Recent_Buy_NAN_S1S2_Is_First | 最近购买NAN S1S2是否首次 |
| Recent_Buy_PreNAN_Is_First | 最近购买PreNAN是否首次 |
| Recent_Buy_CMPA_Is_First | 最近购买CMPA是否首次 |
| NON_PURCHASE_IMF | 未购买婴幼儿配方奶粉 |
| Recent_Buy_Store | 最近购买门店 |
| PREGNANT_Baby6M | 怀孕宝宝6个月 |
| CreatedOn | 创建时间 |

# [MOT_PreNan_RecentPurchase] 字段注释说明
本表记录了MOT PreNan最近购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| EmptyDay | 空罐天数 |
| RemindDay | 提醒天数 |
| UpdateDate | 更新日期 |

# [MOT_PreNan_RemindBuyTA] 字段注释说明
本表记录了MOT PreNan提醒购买TA信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |
| RecruitDate | 招募日期 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindBuyDate | 提醒购买日期 |
| RemindEmptyDate | 提醒空罐日期 |
| CreatedDate | 创建日期 |
| Unionid | 用户微信Unionid |
| ReBuyTimes | 复购次数 |

# [MOT_PreNan_TagTable] 字段注释说明
本表记录了MOT PreNan标签表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| StageByCRM | CRM中的阶段 |
| Offset_Day | 偏移天数 |
| Is_Weight | 是否称重 |
| RunDay | 运行天数 |
| RecruitDate | 招募日期 |
| RecruitTin | 招募罐数 |
| RecentPurchaseDate | 最近购买日期 |
| RecentPurchaseTin | 最近购买罐数 |
| RemindDay | 提醒天数 |
| EmptyDay | 空罐天数 |
| RemindBuyDate | 提醒购买日期 |
| RemindEmptyDate | 提醒空罐日期 |
| ReBuyTimes | 复购次数 |
| UpdateDate | 更新日期 |
| CreatedDate | 创建日期 |
| JourneyEndDate | 旅程结束日期 |
| Unionid | 用户微信Unionid |

# [MOT_Products_Info] 字段注释说明
本表记录了MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |
| CategoryCode | 类别代码 |
| Anti_Cheating | 反作弊 |
| is_spark_sale | 是否spark销售 |
| is_report | 是否报告 |
| report_period | 报告期 |
| RRP | 建议零售价 |
| ProductCode | 产品代码 |

# [MOT_Products_Info_20221011] 字段注释说明
本表记录了2022年10月11日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |

# [MOT_Products_Info_20231211] 字段注释说明
本表记录了2023年12月11日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |

# [MOT_Products_Info_20240105] 字段注释说明
本表记录了2024年1月5日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |

# [MOT_Products_Info_20240115] 字段注释说明
本表记录了2024年1月15日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |

# [MOT_Products_Info_20250120] 字段注释说明
本表记录了2025年1月20日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |
| CategoryCode | 类别代码 |
| Anti_Cheating | 反作弊 |
| is_spark_sale | 是否spark销售 |

# [MOT_Products_Info_20250416] 字段注释说明
本表记录了2025年4月16日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |
| CategoryCode | 类别代码 |
| Anti_Cheating | 反作弊 |
| is_spark_sale | 是否spark销售 |
| is_report | 是否报告 |
| report_period | 报告期 |

# [MOT_Products_Info_20250416_Earl] 字段注释说明
本表记录了2025年4月16日Earl提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| Price | 价格 |

# [MOT_Products_Info_20250417_Earl] 字段注释说明
本表记录了2025年4月17日Earl提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| Price | 价格 |

# [MOT_Products_Info_20250528_Jonathan] 字段注释说明
本表记录了2025年5月28日Jonathan提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Stage | 阶段 |
| NetWeight | 净重 |
| NPS_Price | NPS价格 |
| RRP_Price | RRP价格 |
| Specifications | 规格 |
| CreatedOn | 创建时间 |
| ProductCode | 产品代码 |

# [MOT_Products_Info_20250603_Jonathan] 字段注释说明
本表记录了2025年6月3日Jonathan提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_20250613_Vicy] 字段注释说明
本表记录了2025年6月13日Vicy提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| NPS | NPS |

# [MOT_Products_Info_20250619_Vicky] 字段注释说明
本表记录了2025年6月19日Vicky提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_20250630] 字段注释说明
本表记录了2025年6月30日的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| ProductShortName | 产品简称 |
| NewCustomerType | 新客户类型 |
| NewCustomerType2022 | 2022年新客户类型 |
| Premium_2022 | 2022年保费 |
| Brand | 品牌 |
| Stage | 阶段 |
| MS_GP_Tag | MS GP标签 |
| NetWeight | 净重 |
| Price | 价格 |
| Specifications | 规格 |
| ConsumeDay | 消耗天数 |
| Comments | 评论 |
| Enable | 是否启用 |
| NSC | NSC |
| IMF | 婴幼儿配方奶粉 |
| NIN | NIN |
| Gerber | 嘉宝 |
| Gerber_Stage | 嘉宝阶段 |
| Gerber_Type | 嘉宝类型 |
| WeShop | 微店 |
| LastChange | 最后更改时间 |
| CreatedOn | 创建时间 |
| Premium | 保费 |
| CategoryCode | 类别代码 |
| Anti_Cheating | 反作弊 |
| is_spark_sale | 是否spark销售 |
| is_report | 是否报告 |
| report_period | 报告期 |
| RRP | 建议零售价 |

# [MOT_Products_Info_20250630_Vicky] 字段注释说明
本表记录了2025年6月30日Vicky提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| 2025年有无销售额产品 | 2025年有无销售额产品 |
| productname | 产品名称 |
| NPS 价格（商家端当前价格） | NPS价格（商家端当前价格） |
| NPS价格（Vicky） | NPS价格（Vicky） |
| RRP价格（Vicky） | RRP价格（Vicky） |

# [MOT_Products_info_20250704_Earl] 字段注释说明
本表记录了2025年7月4日Earl提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| NPS | NPS |
| RRP | RRP |

# [MOT_Products_Info_Gerber] 字段注释说明
本表记录了MOT嘉宝产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| MaterialDescription | 材料描述 |
| ChineseDescription | 中文描述 |
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
| CreatedOn | 创建时间 |
| ProductCode | 产品代码 |

# [MOT_Products_Info_Sanyar] 字段注释说明
本表记录了Sanyar提供的MOT产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Stage | 阶段 |
| NetWeight | 净重 |
| Day | 天 |
| Comments | 评论 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |

# [MOT_Products_NSC_20220223] 字段注释说明
本表记录了2022年2月23日的MOT NSC产品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| 产品简称 | 产品简称 |
| 产品名称 | 产品名称 |
| 产品品牌 | 产品品牌 |
| 产品段位 | 产品段位 |
| 售卖渠道 | 售卖渠道 |
| 产品原单价 | 产品原单价 |
| 产品指导价 | 产品指导价 |
| nsc | NSC |
| Premium_2022 | 2022年保费 |
| F11 | F11 |

# [MOT_UGU_Relation] 字段注释说明
本表记录了MOT UGU关系信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_ID | SNC ID |
| UnionID | UnionID |
| MOT_ID | MOT ID |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Brand | 品牌 |
| ID | ID |

# [MOT_UGU_Relation_Detail] 字段注释说明
本表记录了MOT UGU关系详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_ID | SNC ID |
| Source_UnionID | 源UnionID |
| Target_UnionID | 目标UnionID |
| MOT_ID | MOT ID |
| Invite_Date | 邀请日期 |
| Status | 状态 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Brand | 品牌 |
| ID | ID |

# [NEW_Mama] 字段注释说明
本表记录了新妈妈信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
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
| IsRegistered | 是否已注册 |
| PDateProcessed | P端处理日期 |
| PDateCreated | P端创建日期 |
| ActivityChannel | 活动渠道 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | PID |

# [NINqrcode_Point] 字段注释说明
本表记录了NIN二维码积分信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pid | PID |
| id | ID |
| materialId | 物料ID |
| code | 代码 |
| parentCode | 父代码 |
| marketingCode | 营销代码 |
| type | 类型 |
| target | 目标 |
| createTime | 创建时间 |
| createdOn | 创建于 |
| lastChange | 最后更改时间 |
| Remark | 备注 |
| pid | PID |

# [NSC_Blacked_Xinke_List] 字段注释说明
本表记录了NSC新客黑名单列表。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| CreatedOn | 创建时间 |
| Unionid | 用户微信Unionid |

# [NSC_BlackedList_HA_42] 字段注释说明
本表记录了NSC HA 42黑名单列表。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| UnionID | UnionID |
| Category | 类别 |
| CreatedOn | 创建时间 |
| ID | ID |

# [NSC_BlackedList_SNC] 字段注释说明
本表记录了NSC SNC黑名单列表。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S端手机号 |
| Name | 名称 |
| Role | 角色 |
| TouchPoint | 触点 |
| Enabled | 是否启用 |
| Remark | 备注 |
| CreatedOn | 创建时间 |
| MoidifiedOn | 修改时间 |
| ID | ID |

# [NSC_BlackedList_SNC_20240617] 字段注释说明
本表记录了2024年6月17日的NSC SNC黑名单列表。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S端手机号 |
| Name | 名称 |
| Role | 角色 |
| TouchPoint | 触点 |
| Enabled | 是否启用 |
| Remark | 备注 |
| CreatedOn | 创建时间 |
| MoidifiedOn | 修改时间 |

# [NSC_BochuS23_Sample] 字段注释说明
本表记录了NSC铂初S23样品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | 门店代码 |
| Month | 月份 |
| SampleQuota | 样品配额 |
| SampleQuotaStore | 样品配额存储 |
| SampleReceived | 收到样品 |
| SampleImport | 样品导入 |
| SampleExport | 样品导出 |
| SampleUsage | 样品使用 |
| SampleLeft | 剩余样品 |
| SampleType | 样品类型 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| StoreCode | 门店代码 |
| Month | 月份 |
| SampleType | 样品类型 |

# [NSC_BochuS23_Sample_ToB] 字段注释说明
本表记录了NSC铂初S23样品ToB信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | 月份 |
| StoreCode | 门店代码 |
| SampleQuota | 样品配额 |
| SampleReceived | 收到样品 |
| SampleUsage | 样品使用 |
| SampleLeft | 剩余样品 |
| SampleType | 样品类型 |
| Month | 月份 |
| StoreCode | 门店代码 |
| SampleType | 样品类型 |

# [NSC_BochuSample_Info] 字段注释说明
本表记录了NSC铂初样品信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| MaterialNumber | 物料号 |
| MaterialName | 物料名称 |
| EACode | EA码 |
| CaseCode | 箱码 |
| ManuDate | 生产日期 |
| ExpiryDate | 过期日期 |
| ImportDate | 导入日期 |
| StoreCode | 门店代码 |
| TouchPoint | 触点 |
| SellStatus | 销售状态 |
| OrderNum | 订单号 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID | ID |

# [NSC_CallLog_PostYS] 字段注释说明
本表记录了NSC呼叫日志（PostYS）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | 外呼序列号 |
| AgentId | 客服ID |
| mid | MID |
| store_number | 门店编号 |
| StartTime | 开始时间 |
| EndTime | 结束时间 |
| CallType | 通话类型 |
| CallQuestion | 通话问题 |
| CallResult | 通话结果 |
| Name | 名称 |
| MobileTel | 手机号码 |
| ShopOwner | 店主 |
| Memo | 备忘录 |
| CreateTime | 创建时间 |
| Recruitment | 招募 |
| RecruitmentRemark | 招募备注 |
| Retention | 保留 |
| RetentionRemark | 保留备注 |
| TaskFinish | 任务完成 |
| TaskFinishRemark | 任务完成备注 |
| RefusalReason | 拒绝原因 |
| Temp1 | 临时1 |
| Temp2 | 临时2 |
| Temp3 | 临时3 |
| Temp4 | 临时4 |
| Temp5 | 临时5 |
| CreatedOn | 创建时间 |
| CallMonth | 通话月份 |
| IsEWCSend | 是否EWC发送 |
| IsEWCConnect | 是否EWC连接 |
| CallSeqNo | 外呼序列号 |

# [NSC_CRMPlus_KuaiShanQun] 字段注释说明
本表记录了NSC CRMPlus快闪群信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| QunId | 群ID |
| QunName | 群名称 |
| EnterTime | 进入时间 |
| QuitTime | 退出时间 |
| Remark | 备注 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |
| QunId | 群ID |

# [NSC_Data_QuizTag] 字段注释说明
本表记录了NSC问卷标签数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Openid | 用户微信Openid |
| Mobile | 手机号码 |
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
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Quiz_No | 问卷编号 |
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
| Quiz_No_PreNAN | PreNAN问卷编号 |
| Quiz_No_HA | HA问卷编号 |
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
| Quiz_No_CMPA | CMPA问卷编号 |
| 完整牛奶蛋白过敏_过敏档案_使用产品 | 完整牛奶蛋白过敏_过敏档案_使用产品 |
| 完整牛奶蛋白过敏_过敏档案_使用时间 | 完整牛奶蛋白过敏_过敏档案_使用时间 |
| 完整牛奶蛋白过敏_过敏随访_持续使用 | 完整牛奶蛋白过敏_过敏随访_持续使用 |
| 完整牛奶蛋白过敏_过敏随访_痊愈转奶 | 完整牛奶蛋白过敏_过敏随访_痊愈转奶 |
| 完整牛奶蛋白过敏_过敏随访_诊断康复 | 完整牛奶蛋白过敏_过敏随访_诊断康复 |
| 完整牛奶蛋白过敏_用户画像_诊断结论 | 完整牛奶蛋白过敏_用户画像_诊断结论 |
| 完整牛奶蛋白过敏_用户画像_曾用品牌 | 完整牛奶蛋白过敏_用户画像_曾用品牌 |
| 完整牛奶蛋白过敏_用户画像_担心问题 | 完整牛奶蛋白过敏_用户画像_担心问题 |
| Unionid | 用户微信Unionid |

# [NSC_Data_QuizTag_AL110] 字段注释说明
本表记录了NSC AL110问卷标签数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Openid | 用户微信Openid |
| Mobile | 手机号码 |
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
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Quiz_No | 问卷编号 |
| SentToCRMOn | 发送至CRM时间 |
| Unionid | 用户微信Unionid |

# [NSC_Exclude_Order] 字段注释说明
本表记录了NSC排除的订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| OrderNum | 订单号 |
| CreatedOn | 创建时间 |

# [NSC_HA400g] 字段注释说明
本表记录了NSC HA 400g信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Mobile | 手机号码 |
| SalesID | 销售ID |
| Buytime | 购买时间 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Openid | 用户微信Openid |
| Mobile | 手机号码 |

# [NSC_HCP_Status] 字段注释说明
本表记录了NSC HCP状态信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Recruit_Time | 招募时间 |
| Member_Type | 会员类型 |
| HCP_Active_Expired_Time | HCP激活过期时间 |
| HCP_Active_Time | HCP激活时间 |
| HCP_Expired_Time | HCP过期时间 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | 用户微信Unionid |
| Member_Type | 会员类型 |

# [NSC_ICEF_Q3_TA_Store] 字段注释说明
本表记录了NSC ICEF Q3 TA门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| Enable | 是否启用 |
| CreatedOn | 创建时间 |
| ID | ID |

# [NSC_MOT_WeCom_Action] 字段注释说明
本表记录了NSC MOT企业微信操作信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| MOT_ID | MOT ID |
| Unionid | 用户微信Unionid |
| MOT_DEF_No | MOT定义编号 |
| SNC_NO | SNC编号 |
| CSR_NO | CSR编号 |
| Action_SNC_CSR | SNC CSR操作 |
| SendDateTime | 发送时间 |
| ClickDateTime | 点击时间 |
| GroupType | 组类型 |
| GroupID | 组ID |
| Status | 状态 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| MOT_ID | MOT ID |

# [NSC_NET_IsVaild_Sign] 字段注释说明
本表记录了NSC NET有效签名信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | 用户微信Unionid |
| User_Code | 用户代码 |
| SignTime | 签名时间 |
| CreatedDate | 创建日期 |
| UpdateDate | 更新日期 |
| ID | ID |

# [NSC_NET_MMClass] 字段注释说明
本表记录了NSC NET MMClass信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | 用户微信Unionid |
| openid | 用户微信Openid |
| user_code | 用户代码 |
| ssr_code | SSR代码 |
| mobile | 手机号码 |
| create_date | 创建日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| unionid | 用户微信Unionid |

# [NSC_Q_Logs] 字段注释说明
本表记录了NSC问卷日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Method | 方法 |
| Unionid | 用户微信Unionid |
| MetCompliance | 符合合规 |
| Babybirthday | 宝宝生日 |
| CreatedOn | 创建时间 |
| ID | ID |

# [NSC_QRCode] 字段注释说明
本表记录了NSC二维码信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode | 二维码 |
| ParentCode | 父代码 |
| MarketingCode | 营销代码 |
| ProductCode | 产品代码 |
| BatchNumber | 批号 |
| ManufactureDate | 生产日期 |
| PlantCode | 工厂代码 |
| PlantName | 工厂名称 |
| CreatedTime | 创建时间 |
| WH | 仓库 |
| WHName | 仓库名称 |
| Scantype | 扫描类型 |
| Shipto | 送达方 |
| ShiptoName | 送达方名称 |
| JXS_IN_TransTime | JXS入库传输时间 |
| JXS_ProcessingTime | JXS处理时间 |
| JXS_TransID | JXS传输ID |
| JXS_CustomerNumber | JXS客户编号 |
| JXS_CustomerName | JXS客户名称 |
| JXS_Type | JXS类型 |
| JXS_BU | JXS业务单元 |
| JXS_MaterialName | JXS物料名称 |
| JXS_BatchNumber | JXS批号 |
| JXS_Note | JXS备注 |
| JXS_IN_OutletCode | JXS入库网点代码 |
| JXS_IN_OutletName | JXS入库网点名称 |
| JXS_Region | JXS区域 |
| JXS_Province | JXS省份 |
| JXS_Out_TransTime | JXS出库传输时间 |
| JXS_Out_OutletCode | JXS出库网点代码 |
| JXS_Out_OutletName | JXS出库网点名称 |
| QRCode | 二维码 |

# [NSC_QrCode_Internal] 字段注释说明
本表记录了NSC内部二维码信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | 内部二维码 |
| QrCode | 二维码 |
| Scanning_Time | 扫描时间 |
| Unionid | 用户微信Unionid |
| CreatedOn | 创建时间 |
| Sent2CRMPlusOn | 发送至CRMPlus时间 |
| Code_Type | 代码类型 |
| Is_Gift | 是否赠品 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Stage | 阶段 |
| Sales_Channel | 销售渠道 |
| Platform | 平台 |
| QRCode_Internal | 内部二维码 |

# [NSC_QRCode_Internal_Backup] 字段注释说明
本表记录了NSC内部二维码备份信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | 内部二维码 |
| CreatedOn | 创建时间 |
| Type | 类型 |
| QRCode_Internal | 内部二维码 |

# [NSC_QrCode_Log] 字段注释说明
本表记录了NSC二维码日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| ScanCode | 扫描代码 |
| ScanRole | 扫描角色 |
| ScanName | 扫描名称 |
| Region | 区域 |
| Province | 省份 |
| CG | 城市组 |
| City | 城市 |
| OAH | OAH |
| IsSpark | 是否Spark |
| Toupoint | 触点 |
| Source | 来源 |
| PID | PID |
| QRCode | 二维码 |
| IsReturn | 是否退货 |
| CanBeSell | 可销售 |
| Payload | 有效负载 |
| Response | 响应 |
| CreatedOn | 创建时间 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Sells_CanBeSell | 销售_可销售 |
| Sells_SNCCode | 销售_SNC代码 |
| Sells_SNCName | 销售_SNC名称 |
| Sells_StoreCode | 销售_门店代码 |
| Sells_Youdao | 销售_有道 |
| Sells_OAH | 销售_OAH |
| Sells_Buytime | 销售_购买时间 |
| Sells_Spark | 销售_Spark |
| Sells_StoreName | 销售_门店名称 |
| ka_type | KA类型 |
| ka_channel | KA渠道 |
| ID | ID |

# [NSC_Recent_Purchase] 字段注释说明
本表记录了NSC最近购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| Unionid | 用户微信Unionid |
| S_Mobile | S端手机号 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Brand | 品牌 |
| Qty | 数量 |
| Buytime | 购买时间 |
| Source | 来源 |
| SncCode | SNC代码 |
| SncName | SNC名称 |
| StoreCode | 门店代码 |
| StoreName | 门店名称 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| SentToCRMOn | 发送至CRM时间 |
| LastChange | 最后更改时间 |
| PID | PID |

# [NSC_RetentionToYS] 字段注释说明
本表记录了NSC留存至YS的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | 外呼序列号 |
| CampaignID | 活动ID |
| Call_Time | 通话时间 |
| NewCustomerType | 新客户类型 |
| Recruit_Brand | 招募品牌 |
| Recruit_Stage | 招募阶段 |
| Recruit_Date | 招募日期 |
| BabyBirthday | 宝宝生日 |
| OB_Call_Date | OB外呼日期 |
| Retention_Stage | 留存阶段 |
| Is_Retention | 是否留存 |
| Retain_brand | 留存品牌 |
| Churn_Reason1 | 流失原因1 |
| Churn_Reason2 | 流失原因2 |
| Churn_Brand | 流失品牌 |
| Use_Month | 使用月份 |
| Store_Number | 门店编号 |
| SSRCode | SSR代码 |
| KsfId | KSFID |
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| MamaId | 妈妈ID |
| ProductCode | 产品代码 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| 是否有导 | 是否有导 |
| CallSeqNo | 外呼序列号 |

# [NSC_RetentionToYS_20240711] 字段注释说明
本表记录了2024年7月11日的NSC留存至YS的信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CallSeqNo | 外呼序列号 |
| CampaignID | 活动ID |
| Call_Time | 通话时间 |
| NewCustomerType | 新客户类型 |
| Recruit_Brand | 招募品牌 |
| Recruit_Stage | 招募阶段 |
| Recruit_Date | 招募日期 |
| BabyBirthday | 宝宝生日 |
| OB_Call_Date | OB外呼日期 |
| Retention_Stage | 留存阶段 |
| Is_Retention | 是否留存 |
| Retain_brand | 留存品牌 |
| Churn_Reason1 | 流失原因1 |
| Churn_Reason2 | 流失原因2 |
| Churn_Brand | 流失品牌 |
| Use_Month | 使用月份 |
| Store_Number | 门店编号 |
| SSRCode | SSR代码 |
| KsfId | KSFID |
| Unionid | 用户微信Unionid |
| Mobile | 手机号码 |
| MamaId | 妈妈ID |
| ProductCode | 产品代码 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |

# [NSC_SALESMAN] 字段注释说明
本表记录了NSC销售员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| mid | MID |
| sid | SID |
| openid | 用户微信Openid |
| qrcode | 二维码 |
| qrcode_gb | 国标二维码 |
| type | 类型 |
| area_name | 区域名称 |
| province | 省份 |
| city | 城市 |
| name | 名称 |
| tel | 电话 |
| store_name | 门店名称 |
| store_number | 门店编号 |
| store_type | 门店类型 |
| store_tag | 门店标签 |
| serial_number | 序列号 |
| city_group | 城市组 |
| is_crm | 是否CRM |
| is_onjob | 是否在职 |
| isdel | 是否删除 |
| supervisor_number | 主管编号 |
| supervisor_name | 主管姓名 |
| supervisor_tel | 主管电话 |
| citylevel | 城市级别 |
| ka_type | KA类型 |
| ka_name | KA名称 |
| split_account | 分账 |
| status | 状态 |
| tob_group | TOB组 |
| address | 地址 |
| license | 许可证 |
| distributor | 分销商 |
| ctime | 创建时间 |
| store_ctime | 门店创建时间 |
| shopowner | 店主 |
| vip_level | 会员等级 |
| unionid | 用户微信Unionid |
| license_upload_date | 许可证上传日期 |
| LastChange | 最后更改时间 |
| modified_on | 修改于 |
| vip_level_remark | 会员等级备注 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Spark_Store | Spark门店 |
| mid | MID |

# [NSC_Scan_Errorlog] 字段注释说明
本表记录了NSC扫描错误日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| store_number | 门店编号 |
| serial_number | 序列号 |
| store_distributor | 门店分销商 |
| spark_store | Spark门店 |
| openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| code | 代码 |
| code_distributor | 代码分销商 |
| productcode | 产品代码 |
| CreatedOn | 创建时间 |
| id | ID |

# [NSC_Spark_Activity_Tag] 字段注释说明
本表记录了NSC Spark活动标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFID |
| unionid | 用户微信Unionid |
| id | ID |
| title | 标题 |
| scan_date | 扫描日期 |
| sdate | 开始日期 |
| edate | 结束日期 |
| store_number | 门店编号 |
| activity_no | 活动编号 |
| activity_type | 活动类型 |
| user_code | 用户代码 |
| user_name | 用户名 |
| activity_date | 活动日期 |
| NewCustomertype | 新客户类型 |
| Joindate | 加入日期 |
| is_spark | 是否Spark |
| CreatedOn | 创建时间 |
| KSFId | KSFID |

# [NSC_Spark_Activity_Tag_2] 字段注释说明
本表记录了NSC Spark活动标签信息（表2）。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFId | KSFID |
| Unionid | 用户微信Unionid |
| activity_id | 活动ID |
| activity_title | 活动标题 |
| scan_date | 扫描日期 |
| sdate | 开始日期 |
| edate | 结束日期 |
| store_number | 门店编号 |
| NewCustomertype | 新客户类型 |
| Joindate | 加入日期 |
| CreatedOn | 创建时间 |
| Unionid | 用户微信Unionid |

# [NSC_Spark_Store_Current] 字段注释说明
本表记录了NSC Spark门店当前信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | 月份 |
| Region | 区域 |
| CG | 城市组 |
| Cus_Name | 客户名称 |
| Cus_Code | 客户代码 |
| TCDS_Code | TCDS代码 |
| Source | 来源 |
| Store_Code | 门店代码 |
| Store_Name | 门店名称 |
| Store_SJJH_Tins | 门店SJJH罐数 |
| Store_SJCK_Tins | 门店SJCK罐数 |
| Store_JinHuo_Tins | 门店进货罐数 |
| Store_ZhuiHui_Tins | 门店追回罐数 |
| Store_ChuKu_Tins | 门店出库罐数 |
| Store_TuiDan_Tins | 门店退单罐数 |
| Store_KuCun_Tins | 门店库存罐数 |
| Store_JinHuo_Offtake | 门店进货销量 |
| Store_ZhuiHui_Offtake | 门店追回销量 |
| Store_ChuKu_Offtake | 门店出库销量 |
| Store_TuiDan_Offtake | 门店退单销量 |
| Store_KuCun_Offtake | 门店库存销量 |
| CurrentDay | 当前日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Store_Code | 门店代码 |
| CurrentDay | 当前日期 |

# [NSC_Spark_Store_Current_BySKU] 字段注释说明
本表记录了NSC Spark门店当前（按SKU）信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Month | 月份 |
| Region | 区域 |
| CG | 城市组 |
| Cus_Name | 客户名称 |
| Cus_Code | 客户代码 |
| TCDS_Code | TCDS代码 |
| Source | 来源 |
| Store_Code | 门店代码 |
| Store_Name | 门店名称 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Store_SJJH_Tins | 门店SJJH罐数 |
| Store_SJCK_Tins | 门店SJCK罐数 |
| Store_JinHuo_Tins | 门店进货罐数 |
| Store_ZhuiHui_Tins | 门店追回罐数 |
| Store_ChuKu_Tins | 门店出库罐数 |
| Store_TuiDan_Tins | 门店退单罐数 |
| Store_KuCun_Tins | 门店库存罐数 |
| Store_KuCun_Tins_EXP | 门店库存罐数（EXP） |
| Store_JinHuo_Offtake | 门店进货销量 |
| Store_ZhuiHui_Offtake | 门店追回销量 |
| Store_ChuKu_Offtake | 门店出库销量 |
| Store_TuiDan_Offtake | 门店退单销量 |
| Store_KuCun_Offtake | 门店库存销量 |
| Store_KuCun_Offtake_EXP | 门店库存销量（EXP） |
| CurrentDay | 当前日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Store_Code | 门店代码 |
| ProductCode | 产品代码 |
| CurrentDay | 当前日期 |

# [NSC_Spark_Store_Summary] 字段注释说明
本表记录了NSC Spark门店摘要信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_Code | 门店代码 |
| Query_Type | 查询类型 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Recruitment_MegaNAN_Total | 招募MegaNAN总数 |
| Recruitment_Shouhu | 招募守护 |
| Recruitment_Qihu | 招募启护 |
| Recruitment_Bohu | 招募铂护 |
| Recruitment_BochuS23 | 招募铂初S23 |
| Recruitment_Gerber_Total | 招募嘉宝总数 |
| Recruitment_Gerber_Xinke | 招募嘉宝新客 |
| Recruitment_Gerber_Yonghu | 招募嘉宝用户 |
| Offtake_MegaNAN_Total | MegaNAN总销量 |
| Offtake_HA_Total | HA总销量 |
| Offtake_HA_S1 | HA S1销量 |
| Offtake_HA_S2 | HA S2销量 |
| Offtake_HA_S3 | HA S3销量 |
| Offtake_HA_S4 | HA S4销量 |
| Offtake_Bochu_Total | 铂初总销量 |
| Offtake_Bochu_S1 | 铂初S1销量 |
| Offtake_Bochu_S2 | 铂初S2销量 |
| Offtake_Bochu_S3 | 铂初S3销量 |
| Offtake_PreNAN_Total | PreNAN总销量 |
| Offtake_AL110_Total | AL110总销量 |
| Offtake_Shuyi_Total | 舒宜总销量 |
| Offtake_Shuyi_S1 | 舒宜S1销量 |
| Offtake_Shuyi_S2 | 舒宜S2销量 |
| Offtake_Shuyi_S3 | 舒宜S3销量 |
| Offtake_Zhuochun_Total | 卓纯总销量 |
| Offtake_Gerber_Total | 嘉宝总销量 |
| Offtake_Zhuochun_S1 | 卓纯S1销量 |
| Offtake_Zhuochun_S2 | 卓纯S2销量 |
| Offtake_Zhuochun_S3 | 卓纯S3销量 |
| Offtake_Zhuochun_S4 | 卓纯S4销量 |
| Offtake_Gerber_Mifen | 嘉宝米粉销量 |
| Offtake_Gerber_Mizhou | 嘉宝米粥销量 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Store_Code | 门店代码 |
| Query_Type | 查询类型 |

# [NSC_Spark_W90] 字段注释说明
本表记录了NSC Spark W90信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | 门店代码 |
| 新客时间 | 新客时间 |
| 类型 | 类型 |
| 新客订单编号 | 新客订单编号 |
| BuyTime | 购买时间 |
| ID_CRMPlus | CRMPlus ID |
| Diff_Day | 天数差异 |
| 90D内复购行为 | 90天内复购行为 |
| rn | 行号 |

# [NSC_Spark_WO90] 字段注释说明
本表记录了NSC Spark WO90信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | 门店代码 |
| 新客时间 | 新客时间 |
| 类型 | 类型 |
| 新客订单编号 | 新客订单编号 |
| BuyTime | 购买时间 |
| ID_CRMPlus | CRMPlus ID |
| Diff_Day | 天数差异 |
| 90D外复购行为 | 90天外复购行为 |
| rn | 行号 |

# [NSC_Store] 字段注释说明
本表记录了NSC门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | SID |
| uniacid | uniacid |
| type | 类型 |
| sub_type | 子类型 |
| area_name | 区域名称 |
| province | 省份 |
| city | 城市 |
| city_group | 城市组 |
| store_name | 门店名称 |
| store_number | 门店编号 |
| store_number_2 | 门店编号2 |
| store_type | 门店类型 |
| is_test | 是否测试 |
| is_crm | 是否CRM |
| supervisor_name | 主管姓名 |
| supervisor_number | 主管编号 |
| supervisor_tel | 主管电话 |
| ctime | 创建时间 |
| isdel | 是否删除 |
| ka | KA |
| is_new | 是否新 |
| distributor | 分销商 |
| is_ch | 是否CH |
| updatetime | 更新时间 |
| update_time | 更新时间 |
| status | 状态 |
| status_uptime | 状态更新时间 |
| split_account | 分账 |
| license | 许可证 |
| tob_group | TOB组 |
| address | 地址 |
| citylevel | 城市级别 |
| ka_type | KA类型 |
| ka_name | KA名称 |
| is_snc | 是否SNC |
| store_tag | 门店标签 |
| vip_level | 会员等级 |
| cdate | 创建日期 |
| store_mode | 门店模式 |
| vip_level_remark | 会员等级备注 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Spark_Store | Spark门店 |
| tcds_id | TCDS ID |
| channel_id | 渠道ID |
| org_id | 组织ID |
| cor_name | 公司名称 |
| shop_head_pic | 店铺头像图片 |
| Convert_2_Spark_Date | 转换为Spark日期 |
| ka_channel | KA渠道 |
| city_code | 城市代码 |
| province_code | 省份代码 |
| district_code | 区/县代码 |
| sid | SID |

# [NSC_Store_20240619] 字段注释说明
本表记录了2024年6月19日的NSC门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | SID |
| uniacid | uniacid |
| type | 类型 |
| sub_type | 子类型 |
| area_name | 区域名称 |
| province | 省份 |
| city | 城市 |
| city_group | 城市组 |
| store_name | 门店名称 |
| store_number | 门店编号 |
| store_number_2 | 门店编号2 |
| store_type | 门店类型 |
| is_test | 是否测试 |
| is_crm | 是否CRM |
| supervisor_name | 主管姓名 |
| supervisor_number | 主管编号 |
| supervisor_tel | 主管电话 |
| ctime | 创建时间 |
| isdel | 是否删除 |
| ka | KA |
| is_new | 是否新 |
| distributor | 分销商 |
| is_ch | 是否CH |
| updatetime | 更新时间 |
| update_time | 更新时间 |
| status | 状态 |
| status_uptime | 状态更新时间 |
| split_account | 分账 |
| license | 许可证 |
| tob_group | TOB组 |
| address | 地址 |
| citylevel | 城市级别 |
| ka_type | KA类型 |
| ka_name | KA名称 |
| is_snc | 是否SNC |
| store_tag | 门店标签 |
| vip_level | 会员等级 |
| cdate | 创建日期 |
| store_mode | 门店模式 |
| vip_level_remark | 会员等级备注 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Spark_Store | Spark门店 |
| tcds_id | TCDS ID |
| channel_id | 渠道ID |
| org_id | 组织ID |
| cor_name | 公司名称 |
| shop_head_pic | 店铺头像图片 |
| Convert_2_Spark_Date | 转换为Spark日期 |

# [NSC_Store_20240731] 字段注释说明
本表记录了2024年7月31日的NSC门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sid | SID |
| uniacid | uniacid |
| type | 类型 |
| sub_type | 子类型 |
| area_name | 区域名称 |
| province | 省份 |
| city | 城市 |
| city_group | 城市组 |
| store_name | 门店名称 |
| store_number | 门店编号 |
| store_number_2 | 门店编号2 |
| store_type | 门店类型 |
| is_test | 是否测试 |
| is_crm | 是否CRM |
| supervisor_name | 主管姓名 |
| supervisor_number | 主管编号 |
| supervisor_tel | 主管电话 |
| ctime | 创建时间 |
| isdel | 是否删除 |
| ka | KA |
| is_new | 是否新 |
| distributor | 分销商 |
| is_ch | 是否CH |
| updatetime | 更新时间 |
| update_time | 更新时间 |
| status | 状态 |
| status_uptime | 状态更新时间 |
| split_account | 分账 |
| license | 许可证 |
| tob_group | TOB组 |
| address | 地址 |
| citylevel | 城市级别 |
| ka_type | KA类型 |
| ka_name | KA名称 |
| is_snc | 是否SNC |
| store_tag | 门店标签 |
| vip_level | 会员等级 |
| cdate | 创建日期 |
| store_mode | 门店模式 |
| vip_level_remark | 会员等级备注 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Spark_Store | Spark门店 |
| tcds_id | TCDS ID |
| channel_id | 渠道ID |
| org_id | 组织ID |
| cor_name | 公司名称 |
| shop_head_pic | 店铺头像图片 |
| Convert_2_Spark_Date | 转换为Spark日期 |

# [nsc_store_20241015] 字段注释说明
本表记录了2024年10月15日的NSC门店信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 是否上传 | 是否上传 |
| 营业执照上传时间 | 营业执照上传时间 |
| 二维码码值 | 二维码码值 |
| 渠道 | 渠道 |
| ka_name | KA名称 |
| ka_type | KA类型 |
| 城市组 | 城市组 |
| 区域 | 区域 |
| 省 | 省 |
| 市 | 市 |
| 地址 | 地址 |
| 店主姓名 | 店主姓名 |
| unionid | 用户微信Unionid |
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
| Is_Spark | 是否Spark |

# [NSC_Store_Channel] 字段注释说明
本表记录了NSC门店渠道信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletCode | 网点代码 |
| Channel | 渠道 |
| ACGroupName | AC组名称 |
| Platform | 平台 |
| ModifiedOn | 修改时间 |
| CustomerName | 客户名称 |
| CreatedOn | 创建时间 |
| Descriptions | 描述 |
| OutletCode | 网点代码 |

# [NSC_Store_Channel_20250527] 字段注释说明
本表记录了2025年5月27日的NSC门店渠道信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletCode | 网点代码 |
| Channel | 渠道 |
| ACGroupName | AC组名称 |
| GroupName | 组名称 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| CustomerName | 客户名称 |
| Platform_Sanyar | Sanyar平台 |
| Platform_Ruby | Ruby平台 |

# [NSC_Store_Channel_EC] 字段注释说明
本表记录了NSC门店渠道EC信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| CustomerName | 客户名称 |
| ACGroupName | AC组名称 |
| Description | 描述 |
| Platform_Sanyar | Sanyar平台 |
| Platform_Ruby | Ruby平台 |
| CreatedOn | 创建时间 |
| CustomerName | 客户名称 |
| ACGroupName | AC组名称 |

# [NSC_Tag_CSR] 字段注释说明
本表记录了NSC CSR标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Source_Questionaire | 来源问卷 |
| Target_Brand | 目标品牌 |
| Is_Sample_Bochu_200g | 是否为铂初200g样品 |
| Is_Active_HCP | 是否激活HCP |
| Is_Binding_SNC_CSR | 是否绑定SNC CSR |
| Is_Join_VipGroupe | 是否加入VIP群 |
| Tag_List | 标签列表 |
| Update_Time | 更新时间 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| SentToCRMOn | 发送至CRM时间 |
| Is_Allow_UseBohu_From_Link | 是否允许通过链接使用铂护 |
| LastChange | 最后更改时间 |
| Enter_KuaiShanQun_Date | 进入快闪群日期 |
| Quit_KuaiShanQun_Date | 退出快闪群日期 |
| Xinke_PreNAN | 新客PreNAN |
| Xinke_AL110 | 新客AL110 |
| HA_Minmin | HA敏敏 |
| Unionid | 用户微信Unionid |

# [NSC_Tag_CSR_20240603] 字段注释说明
本表记录了2024年6月3日的NSC CSR标签信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Source_Questionaire | 来源问卷 |
| Target_Brand | 目标品牌 |
| Is_Sample_Bochu_200g | 是否为铂初200g样品 |
| Is_Active_HCP | 是否激活HCP |
| Is_Binding_SNC_CSR | 是否绑定SNC CSR |
| Is_Join_VipGroupe | 是否加入VIP群 |
| Tag_List | 标签列表 |
| Update_Time | 更新时间 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| SentToCRMOn | 发送至CRM时间 |
| Is_Allow_UseBohu_From_Link | 是否允许通过链接使用铂护 |
| LastChange | 最后更改时间 |
| Enter_KuaiShanQun_Date | 进入快闪群日期 |
| Quit_KuaiShanQun_Date | 退出快闪群日期 |
| Xinke_PreNAN | 新客PreNAN |
| Xinke_AL110 | 新客AL110 |
| HA_Minmin | HA敏敏 |

# [NSC_Test_Member] 字段注释说明
本表记录了NSC测试会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | 用户微信Unionid |
| Name | 名称 |
| Mobile | 手机号码 |
| S_Mobile | S端手机号 |
| Type | 类型 |
| Remark | 备注 |
| CreatedOn | 创建时间 |
| Unionid | 用户微信Unionid |

# [NSC_ToB_Achievement] 字段注释说明
本表记录了NSC ToB业绩信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| openid | 用户微信Openid |
| unionid | 用户微信Unionid |
| NewCustomerType | 新客户类型 |
| gift_code | 礼品码 |
| sid | SID |
| StoreCode | 门店代码 |
| SNCCode | SNC代码 |
| serial_number_sy | 序列号SY |
| type | 类型 |
| act_type | 活动类型 |
| source | 来源 |
| yeji_val | 业绩值 |
| order_id | 订单ID |
| order_no | 订单号 |
| cash_out_id | 提现ID |
| cash_out_status | 提现状态 |
| remark | 备注 |
| status | 状态 |
| msg | 消息 |
| send_id | 发送ID |
| tradeno | 交易号 |
| cdate | 创建日期 |
| updatetime | 更新时间 |
| rn | 行号 |
| id | ID |

# [NSC_ToB_Gerber_ZhuanQu] 字段注释说明
本表记录了NSC ToB嘉宝专区信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| mid | MID |
| page_name | 页面名称 |
| page_data | 页面数据 |
| button | 按钮 |
| unionid | 用户微信Unionid |
| create_time | 创建时间 |
| NewID | 新ID |
| Title | 标题 |
| Brand | 品牌 |
| id | ID |

# [NSC_Tob_Quota] 字段注释说明
本表记录了NSC ToB配额信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Months | 月份 |
| StoreCode | 门店代码 |
| Quarter | 季度 |
| Qty | 数量 |
| Total_NPS | 总NPS |
| Total_NSCPlus_NPS | 总NSCPlus NPS |
| Total_NSCPlus_RRP | 总NSCPlus RRP |
| Is_Fixed | 是否固定 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| ID | ID |

# [NSC_Tob_Quota_2025Q3] 字段注释说明
本表记录了NSC ToB 2025年Q3配额信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Months | 月份 |
| StoreCode | 门店代码 |
| Quarter | 季度 |
| Qty | 数量 |
| Total_NPS | 总NPS |
| Total_NSCPlus_NPS | 总NSCPlus NPS |
| Total_NSCPlus_RRP | 总NSCPlus RRP |
| Is_Fixed | 是否固定 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |

# [NSC_Tob_Quota_temp] 字段注释说明
本表记录了NSC ToB临时配额信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| StoreCode | 门店代码 |
| Months | 月份 |
| Total_NPS | 总NPS |
| Total_NSCPlus_NPS | 总NSCPlus NPS |
| Total_NSCPlus_RRP | 总NSCPlus RRP |
| Qty | 数量 |

# [NSC_ToB_SALESMAN] 字段注释说明
本表记录了NSC ToB销售员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| mid | MID |
| area_name | 区域名称 |
| province | 省份 |
| store_number | 门店编号 |
| shopowner | 店主 |
| name | 名称 |
| tel | 电话 |
| openid | 用户微信Openid |
| store_name | 门店名称 |
| city_group | 城市组 |
| address | 地址 |
| store_tag | 门店标签 |
| vip_level | 会员等级 |
| supervisor_number | 主管编号 |
| supervisor_name | 主管姓名 |
| supervisor_tel | 主管电话 |
| license_upload_date | 许可证上传日期 |
| is_onjob | 是否在职 |
| Status | 状态 |
| serial_number | 序列号 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Spark_Store | Spark门店 |
| is_crm | 是否CRM |
| ka_type | KA类型 |
| ka_name | KA名称 |
| NUMBER | 数量 |
| CreatedOn | 创建时间 |

# [NSC_ToB_Store_Status] 字段注释说明
本表记录了NSC ToB门店状态信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_ID | 门店ID |
| Current_Month | 当前月份 |
| RepurchaseRate_Recent_2M | 最近2个月复购率 |
| RepurchaseFrequency_Recent_2M | 最近2个月复购频率 |
| MOT_SentRate_LastMonth | 上月MOT发送率 |
| MOT_ConversionRate_LastMonth | 上月MOT转化率 |
| Foward_ActivityAndContent_CompletedRate_LastMonth | 上月转发活动和内容完成率 |
| Foward_ActivityAndContent_ConversionRate_LastMonth | 上月转发活动和内容转化率 |
| Course_CompletedRate_LastMonth | 上月课程完成率 |
| Repurchase_Orders_Recent_2M | 最近2个月复购订单 |
| Repurchase_Users_Recent_2M | 最近2个月复购用户 |
| Recruit_Users_Recent_2M | 最近2个月招募用户 |
| Vip_Level | 会员等级 |
| MOT_Sent | MOT发送 |
| MOT_Finish | MOT完成 |
| MOT_Conversion | MOT转化 |
| Completed_Course | 已完成课程 |
| TTL_Push_Course | TTL推送课程 |
| TTL_Push_Content | TTL推送内容 |
| Completed_Content_Activity | 已完成内容活动 |
| Conversion_Content_Activity | 内容活动转化 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Store_ID | 门店ID |
| Current_Month | 当前月份 |

# [NSC_ToB_ZhuanQu] 字段注释说明
本表记录了NSC ToB专区信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| module | 模块 |
| session_key | 会话密钥 |
| openid | openid |
| type | 类型 |
| unionid | unionid |
| uid | 用户ID |
| utype | 用户类型 |
| baby_m | 宝宝月份 |
| page | 页面 |
| category | 类别 |
| mid | mid |
| page_name | 页面名称 |
| page_data | 页面数据 |
| button | 按钮 |
| source | 来源 |
| track | 追踪 |
| sr_channel | SR渠道 |
| channel_id | 渠道ID |
| is_crm | 是否CRM |
| follow | 关注 |
| scene | 场景 |
| year | 年 |
| month | 月 |
| day | 日 |
| ctime | 创建时间 |
| ip | IP地址 |
| updatetime | 更新时间 |
| create_time | 创建时间 |
| NewID | 新ID |
| Tag | 标签 |
| Brand | 品牌 |
| id | ID |

# [NSC_User_Scenario] 字段注释说明
本表记录了NSC用户场景信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Scenario | 场景 |
| Last_Buy_Date | 最近购买日期 |
| Is_Better_Date | 是否好转日期 |
| Is_Baby_Weight_Great_45 | 宝宝体重是否大于45 |
| ZhuanNai_Date_PreNAN | PreNAN转奶日期 |
| ZhuanNai_Date_HA | HA转奶日期 |
| ZhuanNai_Date_Bochu | 铂初转奶日期 |
| CreatedOn | 创建时间 |
| ModifiedOn_OA | OA修改时间 |
| ModifiedOn_CSR | CSR修改时间 |
| ModifiedOn_SNC | SNC修改时间 |
| ModifiedOn_CD | CD修改时间 |
| Brand | 品牌 |
| ZhuanBrand_Date | 转品牌日期 |
| Unionid | Unionid |

# [NSC_VIP_GROUPES] 字段注释说明
本表记录了NSC VIP群组信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| Chat_id | 聊天ID |
| SncCode | SNC代码 |
| CsrCode | CSR代码 |
| Unionid | Unionid |
| GroupName | 群组名称 |
| GroupCreateTime | 群组创建时间 |
| GroupActiveTime | 群组活跃时间 |
| GroupExitTime | 群组退出时间 |
| IsValid | 是否有效 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Id | ID |

# [OMNICHANNEL_MEMBER_2021] 字段注释说明
本表记录了2021年全渠道会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Openid | Openid |
| M_CREATE_DATE | 创建日期 |
| M_UPDATE_DATE | 更新日期 |
| Name | 姓名 |
| BabyBirthday | 宝宝生日 |
| WECHAT_BIND_FLAG | 微信绑定标志 |
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
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| RegisterChannel | 注册渠道 |
| SUB_PREGNANT_STATUS | 怀孕状态 |
| SUB_BABY_BIRTHDAY | 宝宝生日 |
| SUB_BABY_DUEDATE | 宝宝预产期 |
| Completed_Info | 已完成信息 |
| Completed_ARI | 已完成ARI |
| Brand_Prospect | 品牌前景 |
| MS_GP_Tag | MS GP标签 |
| SUB_USER_NICKNAME | 用户昵称 |
| Completed_S1S2_Ratting | 已完成S1S2评分 |
| Mobile | 手机号码 |
| S_MOBILE | S端手机号 |
| Completed_Shouhu_Questionnaire1_Date | 完成守护问卷1日期 |
| Completed_Qihu_Questionnaire1_Date | 完成启护问卷1日期 |
| Completed_Youhu_Questionnaire1_Date | 完成优护问卷1日期 |
| Completed_Qihu_Questionnaire2_Date | 完成启护问卷2日期 |
| Completed_Youhu_Questionnaire2_Date | 完成优护问卷2日期 |
| Completed_Cmpa_Questionnaire_Date | 完成Cmpa问卷日期 |
| JD_MOBILE | 京东手机号 |
| SYNC_TIME | 同步时间 |
| Last_SYNC_Time | 上次同步时间 |
| SentToJDOn | 发送至京东时间 |
| Comments | 评论 |
| WECHAT_BIND_GB | 微信绑定GB |
| WECHAT_BIND_FLAG_GB | 微信绑定标志GB |
| CreatedOn | 创建时间 |
| WECHAT_BIND_CT | 微信绑定CT |
| Completed_Bohu_Questionnaire1_Date | 完成铂护问卷1日期 |
| Completed_Bohu_Questionnaire2_Date | 完成铂护问卷2日期 |
| SUB_BABY_NICKNAME | 宝宝昵称 |
| AL110_Popup | AL110弹窗 |
| Completed_Shuhu_Questionnaire1_Date | 完成舒护问卷1日期 |
| Vip_Level | 会员等级 |
| Total_Tins | 总罐数 |
| NHS_Unionid | NHS Unionid |
| Unionid | Unionid |

# [OMNICHANNEL_SALES] 字段注释说明
本表记录了全渠道销售信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PID | PID |
| Mobile | 手机号码 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| NewCustomerType | 新客户类型 |
| Buytime | 购买时间 |
| Source | 来源 |
| Brand | 品牌 |
| Stage | 阶段 |
| Qty | 数量 |
| Channel | 渠道 |
| NetWeight | 净重 |
| CreatedOn | 创建时间 |
| SNCCode | SNC代码 |
| S_Mobile | S端手机号 |
| LastChange | 最后更改时间 |
| Openid | Openid |
| Unionid | Unionid |
| StoreCode | 门店代码 |
| PurchaseStatus | 购买状态 |
| ReturnQty | 退货数量 |
| Remark | 备注 |
| Cus_Number | 客户编号 |
| Cus_Uid | 客户UID |
| Is_Spark | 是否Spark |
| OrderNum | 订单号 |
| Tcds_Id | TCDS ID |
| Has_Tin | 有罐 |
| ID | ID |

# [OMNICHANNEL_SALES_QRCODE] 字段注释说明
本表记录了全渠道销售二维码信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| QRCode | 二维码 |
| TouchPoint | 触点 |
| IsReturn | 是否退货 |
| BuyTime | 购买时间 |
| CreatedOn | 创建时间 |
| StoreName | 门店名称 |
| StoreCode | 门店代码 |
| Remark | 备注 |
| LastChange | 最后更改时间 |
| IQC_QRCode | IQC二维码 |
| IQC_QRCode_Time | IQC二维码时间 |
| Tin_Type | 罐类型 |
| ProductCode | 产品代码 |
| SNCCode | SNC代码 |
| SNCName | SNC名称 |
| OrderNum | 订单号 |
| ProductName | 产品名称 |
| ID | ID |
| QRCode | 二维码 |
| IsReturn | 是否退货 |

# [OrderNoUnionid] 字段注释说明
本表记录了订单号和Unionid的关联信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 购买时间 | 购买时间 |
| 门店编码 | 门店编码 |
| KSFId | KSFId |
| 验证日期1 | 验证日期1 |
| 验证月份 | 验证月份 |
| OriginalBatchNo | 原始批次号 |

# [Orders] 字段注释说明
本表记录了订单信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | ID |
| OrderNumber | 订单号 |
| MemberId | 会员ID |
| Amount | 金额 |
| Status | 状态 |
| OrderTime | 订单时间 |
| CreatedAt | 创建于 |
| UpdatedAt | 更新于 |
| CompletedAt | 完成于 |
| Remarks | 备注 |
| Id | ID |

# [outbound_id_callseqno] 字段注释说明
本表记录了外呼ID和呼叫序列号的关联信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| call_seq_no | 呼叫序列号 |

# [PairPurchases] 字段注释说明
本表记录了成对购买信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| rn | 行号 |
| Unionid | Unionid |
| BrandFrom | 源品牌 |
| BrandTo | 目标品牌 |

# [ProcedureLog] 字段注释说明
本表记录了存储过程日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| LogDate | 日志日期 |
| DatabaseID | 数据库ID |
| ObjectID | 对象ID |
| ProcedureName | 过程名称 |
| ErrorLine | 错误行号 |
| ErrorMessage | 错误消息 |
| AdditionalInfo | 附加信息 |
| Parameter | 参数 |
| Cost | 成本 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [PUSH_Baby] 字段注释说明
本表记录了推送宝宝信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
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
| OperationFlag | 操作标志 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [PUSH_Inbound] 字段注释说明
本表记录了推送呼入信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
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
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | PID |

# [PUSH_Mama] 字段注释说明
本表记录了推送妈妈信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PMamaId | P端妈妈ID |
| CMamaId | C端妈妈ID |
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
| RegisterChannel | 注册渠道 |
| OperationFlag | 操作标志 |
| CreatedOn | 创建时间 |
| CreatedBy | 创建人 |
| ModifiedOn | 修改时间 |
| ModifiedBy | 修改人 |
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| ActivityChannel | 活动渠道 |
| KSFId | KSFID |
| CMT_ID | CMT ID |
| MamaNameFromSNC | 来自SNC的妈妈姓名 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Unionid | Unionid |
| ID | ID |

# [PUSH_Member] 字段注释说明
本表记录了推送会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
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
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| ModifiedOn | 修改时间 |
| ActivityChannel | 活动渠道 |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [PUSH_Member_Profiles] 字段注释说明
本表记录了推送会员详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| M_MOBILE | 手机号码 |
| SWD_SWL_BATCH_ID | SWD SWL批次ID |
| M_USER_ID | 用户ID |
| M_PASSWORD | 密码 |
| M_IS_VAILD | 是否有效 |
| M_INVAILD_REASON | 无效原因 |
| M_CREATE_DATE | 创建日期 |
| M_UPDATE_DATE | 更新日期 |
| M_UPDATE_USER | 更新用户 |
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
| SOU_CREATE_DATE | 创建日期 |
| SOU_CREATE_USER | 创建用户 |
| SOU_SITE_TYPE | 网站类型 |
| SOU_COOKIE_KEY | Cookie密钥 |
| SOU_SESSION_FIRST_TIME | 首次会话时间 |
| SOU_CAMPAIGN_CODE | 活动代码 |
| SOU_CONFERENCE_CODE | 会议代码 |
| SOU_WECHAT_COMEFROM | 微信来源 |
| SOU_TRACKING_CODE_06 | 追踪代码06 |
| SWD_PROCESS_FLAG | 处理标志 |
| SWD_UTYPE | 用户类型 |
| SWD_DATA_SOURCE | 数据源 |
| WECHAT_BIND | 微信绑定 |
| WECHAT_BIND_FLAG | 微信绑定标志 |
| SUB_TAG_M1001 | 标签M1001 |
| SUB_TAG_M1002 | 标签M1002 |
| SUB_TAG_M1003 | 标签M1003 |
| SUB_TAG_M1004 | 标签M1004 |
| SUB_TAG_M1005 | 标签M1005 |
| SUB_TAG_M1006 | 标签M1006 |
| ModifiedOn | 修改时间 |
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| SR_USER_NAME | SR用户名 |
| SR_STORE_CODE | SR门店代码 |
| SR_AREA | SR区域 |
| SR_PROVINCE | SR省份 |
| SR_CITY | SR城市 |
| SR_CODE | SR代码 |
| SR_CHANNEL | SR渠道 |
| SR_CITY_GROUP | SR城市组 |
| SR_STORE_NAME | SR门店名称 |
| KSFID | KSFID |
| CMT_ID | CMT ID |
| SUB_IS_RCV_MOBILE | 是否接收手机推送 |
| M_TYPE | 类型 |
| CMT_UNIONID | CMT Unionid |
| Remark | 备注 |
| S_MOBILE | S端手机号 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| Vip_Level | 会员等级 |
| NHS_Unionid | NHS Unionid |
| ID | ID |

# [PUSH_Member_Profiles_Log] 字段注释说明
本表记录了推送会员详细信息日志。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| LastDateTime | 最后日期时间 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| ID | ID |

# [PUSH_Outbound] 字段注释说明
本表记录了推送外呼信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
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
| IsSentToCRM | 是否已发送至CRM |
| SentToCRMDate | 发送至CRM日期 |
| EqualResult | 对比结果 |
| LastChange | 最后更改时间 |
| LastChange_Azure | Azure端最后更改时间 |
| PID | PID |

# [QBB_Gerber_Register] 字段注释说明
本表记录了QBB嘉宝注册信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Mobile | 手机号码 |
| Name | 姓名 |
| BabyBirthday | 宝宝生日 |
| Province | 省份 |
| City | 城市 |
| District | 区/县 |
| Address | 地址 |
| SampleType | 样品类型 |
| S_Mobile | S端手机号 |
| IsUsedCoupon | 是否使用优惠券 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Mobile | 手机号码 |

# [QD_Questionnaire] 字段注释说明
本表记录了QD问卷信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| survey_id | 问卷ID |
| survey_name | 问卷名称 |
| question_id | 问题ID |
| question_name | 问题名称 |
| question_code | 问题代码 |
| question_type | 问题类型 |
| question_sub_type | 问题子类型 |
| module_list | 模块列表 |
| option_list | 选项列表 |
| CreatedOn | 创建时间 |
| survey_id | 问卷ID |
| question_id | 问题ID |

# [QD_RowData] 字段注释说明
本表记录了QD原始数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| user_id | 用户ID |
| survey_id | 问卷ID |
| survey_name | 问卷名称 |
| question_id | 问题ID |
| question_name | 问题名称 |
| question_code | 问题代码 |
| question_type | 问题类型 |
| question_sub_type | 问题子类型 |
| module_list | 模块列表 |
| option_list | 选项列表 |
| answer | 答案 |
| CreatedOn | 创建时间 |
| ID | ID |

# [rachel_20250324_result] 字段注释说明
本表记录了2025年3月24日Rachel提供的结果数据。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 星火省份 | 星火省份 |
| 城市 | 城市 |
| 地级市/县城 | 地级市/县城 |
| UNIONID | UNIONID |
| mobile | 手机号码 |
| qty | 数量 |
| Store_Name | 门店名称 |
| StoreCode | 门店代码 |
| 是否有导 | 是否有导 |
| OAH or No-OAH | OAH或非OAH |

# [Redis_LOG] 字段注释说明
本表记录了Redis日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Table_Name | 表名 |
| Table_ID | 表ID |
| Redis_Key | Redis键 |
| Redis_Group | Redis组 |
| Payload | 有效负载 |
| Response | 响应 |
| Status | 状态 |
| EnterDate | 进入日期 |
| DML_Type | DML类型 |
| ElapsedMilliseconds | 耗时（毫秒） |
| CreateDate | 创建日期 |
| ID | ID |

# [RUN_JOB_HISTORY] 字段注释说明
本表记录了运行作业历史信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| job_name | 作业名称 |
| run_datetime | 运行日期时间 |
| run_time | 运行时间 |
| run_duration_millsecond | 运行持续时间（毫秒） |
| step_name | 步骤名称 |
| run_status | 运行状态 |
| message | 消息 |
| created_datetime | 创建日期时间 |
| id | ID |

# [SNC_Bonus_BochuS23] 字段注释说明
本表记录了SNC铂初S23奖励信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tank_barcode | 罐条码 |
| cdate | 创建日期 |
| touch_point | 触点 |
| recall | 召回 |
| recall_date | 召回日期 |
| Comments | 评论 |
| tank_barcode | 罐条码 |
| recall | 召回 |

# [SNC_Bonus_BochuS23_20241018] 字段注释说明
本表记录了2024年10月18日的SNC铂初S23奖励信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tank_barcode | 罐条码 |
| cdate | 创建日期 |
| touch_point | 触点 |
| recall | 召回 |
| recall_date | 召回日期 |
| Comments | 评论 |

# [SNC_HA_42] 字段注释说明
本表记录了SNC HA 42信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SNC_Code | SNC代码 |
| SNC_Name | SNC名称 |
| Unionid | Unionid |
| S_Mobile | S端手机号 |
| User_Name | 用户名 |
| Region | 区域 |
| CG | 城市组 |
| Current_Tins | 当前罐数 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |

# [SNC_Performance_Accumulation] 字段注释说明
本表记录了SNC绩效累积信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| SNCCode | SNC代码 |
| A_LT_18 | A小于18 |
| A_19_36 | A在19到36之间 |
| A_37_42 | A在37到42之间 |
| A_GT_43 | A大于43 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| SNCCode | SNC代码 |

# [SNC_Performance_Member] 字段注释说明
本表记录了SNC绩效会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | 婴幼儿配方奶粉新客 |
| Service_1st_SNCCode | 第一次服务SNC代码 |
| Service_1st_Date | 第一次服务日期 |
| Service_Two | 第二次服务 |
| Service_Two_SNCCode | 第二次服务SNC代码 |
| Service_Two_Date | 第二次服务日期 |
| Service_Three | 第三次服务 |
| Service_Three_SNCCode | 第三次服务SNC代码 |
| Service_Three_Date | 第三次服务日期 |
| Service_Four | 第四次服务 |
| Service_Four_SNCCode | 第四次服务SNC代码 |
| Service_Four_Date | 第四次服务日期 |
| Rrepurchase_Stage_3 | 第三阶段复购 |
| Rrepurchase_Stage_3_SNCCode | 第三阶段复购SNC代码 |
| Rrepurchase_Stage_3_Date | 第三阶段复购日期 |
| Current_Tins | 当前罐数 |
| Tins_18 | 18罐 |
| Tins_42 | 42罐 |
| Service_Two_Claim_Date | 第二次服务领取日期 |
| Service_Three_Claim_Date | 第三次服务领取日期 |
| Service_Four_Claim_Date | 第四次服务领取日期 |
| Tins_18_Claim_Date | 18罐领取日期 |
| Tins_42_Claim_Date | 42罐领取日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | Unionid |

# [SNC_Performance_Member_20250401] 字段注释说明
本表记录了2025年4月1日的SNC绩效会员信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | 婴幼儿配方奶粉新客 |
| Service_1st_SNCCode | 第一次服务SNC代码 |
| Service_1st_Date | 第一次服务日期 |
| Service_Two | 第二次服务 |
| Service_Two_SNCCode | 第二次服务SNC代码 |
| Service_Two_Date | 第二次服务日期 |
| Service_Three | 第三次服务 |
| Service_Three_SNCCode | 第三次服务SNC代码 |
| Service_Three_Date | 第三次服务日期 |
| Service_Four | 第四次服务 |
| Service_Four_SNCCode | 第四次服务SNC代码 |
| Service_Four_Date | 第四次服务日期 |
| Rrepurchase_Stage_3 | 第三阶段复购 |
| Rrepurchase_Stage_3_SNCCode | 第三阶段复购SNC代码 |
| Rrepurchase_Stage_3_Date | 第三阶段复购日期 |
| Current_Tins | 当前罐数 |
| Tins_18 | 18罐 |
| Tins_42 | 42罐 |
| Service_Two_Claim_Date | 第二次服务领取日期 |
| Service_Three_Claim_Date | 第三次服务领取日期 |
| Service_Four_Claim_Date | 第四次服务领取日期 |
| Tins_18_Claim_Date | 18罐领取日期 |
| Tins_42_Claim_Date | 42罐领取日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |

# [SNC_Performance_Member_20250401_bak] 字段注释说明
本表记录了2025年4月1日的SNC绩效会员备份信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_Xinke | 婴幼儿配方奶粉新客 |
| Service_1st_SNCCode | 第一次服务SNC代码 |
| Service_1st_Date | 第一次服务日期 |
| Service_Two | 第二次服务 |
| Service_Two_SNCCode | 第二次服务SNC代码 |
| Service_Two_Date | 第二次服务日期 |
| Service_Three | 第三次服务 |
| Service_Three_SNCCode | 第三次服务SNC代码 |
| Service_Three_Date | 第三次服务日期 |
| Service_Four | 第四次服务 |
| Service_Four_SNCCode | 第四次服务SNC代码 |
| Service_Four_Date | 第四次服务日期 |
| Rrepurchase_Stage_3 | 第三阶段复购 |
| Rrepurchase_Stage_3_SNCCode | 第三阶段复购SNC代码 |
| Rrepurchase_Stage_3_Date | 第三阶段复购日期 |
| Current_Tins | 当前罐数 |
| Tins_18 | 18罐 |
| Tins_42 | 42罐 |
| Service_Two_Claim_Date | 第二次服务领取日期 |
| Service_Three_Claim_Date | 第三次服务领取日期 |
| Service_Four_Claim_Date | 第四次服务领取日期 |
| Tins_18_Claim_Date | 18罐领取日期 |
| Tins_42_Claim_Date | 42罐领取日期 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |

# [SNC_PERP_KPI_Incentive_OrderDetial] 字段注释说明
本表记录了SNC PERP KPI激励订单详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| brand | 品牌 |
| stage | 阶段 |
| buytime | 购买时间 |
| 购买SNC | 购买SNC |
| 订单罐数 | 订单罐数 |
| returnQty | 退货数量 |
| TankBarcode | 罐条码 |
| ID_CRMPlus | CRMPlus ID |
| 购买StoreCode | 购买门店代码 |
| ProductName | 产品名称 |
| Source | 来源 |
| ID | ID |
| OrderEntry | 订单入口 |
| OrderNum | 订单号 |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDetail | 按详情排序 |
| OrderbyDay | 按天排序 |
| OrderbyDay_desc | 按天降序排序 |
| Revenue | 收入 |
| stage_label | 阶段标签 |
| 普配S1_label | 普配S1标签 |
| 刨除退单罐数 | 刨除退单罐数 |
| OrderbyDetail_有效 | 按详情排序_有效 |
| OrderbyDay_有效 | 按天排序_有效 |
| OrderWithDay_刨普s1 | 按天排序_刨除普配s1 |
| OrderbyDay_刨普s1 | 按天排序_刨除普配s1 |
| OrderDesc | 订单降序 |
| 累积购买罐数 | 累积购买罐数 |
| 首购日期 | 首购日期 |
| 累积听数层级Label | 累积听数层级标签 |
| 前一单累积听数层级Label | 前一单累积听数层级标签 |
| 跨段标识 | 跨段标识 |
| 距离首单月数 | 距离首单月数 |
| 当月大于18M的听数 | 当月大于18M的听数 |
| 1-18听_非跨段 | 1-18罐_非跨段 |
| 19-36听_非跨段 | 19-36罐_非跨段 |
| 37-42听_非跨段 | 37-42罐_非跨段 |
| 43-100听_非跨段 | 43-100罐_非跨段 |
| 100听以上_非跨段 | 100罐以上_非跨段 |
| 1-18听_跨段1 | 1-18罐_跨段1 |
| 19-36听_跨段1 | 19-36罐_跨段1 |
| 1-18听_跨段2 | 1-18罐_跨段2 |
| 19-36听_跨段2 | 19-36罐_跨段2 |
| 37-42听_跨段1 | 37-42罐_跨段1 |
| 19-36听_跨段3 | 19-36罐_跨段3 |
| 37-42听_跨段2 | 37-42罐_跨段2 |
| 1-18听_跨段3 | 1-18罐_跨段3 |
| 19-36听_跨段4 | 19-36罐_跨段4 |
| 37-42听_跨段3 | 37-42罐_跨段3 |
| 43听-100_跨段1 | 43-100罐_跨段1 |
| 19-36听_跨段5 | 19-36罐_跨段5 |
| 37-42听_跨段4 | 37-42罐_跨段4 |
| 43听-100_跨段2 | 43-100罐_跨段2 |
| 37-42听_跨段5 | 37-42罐_跨段5 |
| 43听-100_跨段3 | 43-100罐_跨段3 |
| 1-18听_跨段4 | 1-18罐_跨段4 |
| 19-36听_跨段6 | 19-36罐_跨段6 |
| 37-42听_跨段6 | 37-42罐_跨段6 |
| 43听-100_跨段4 | 43-100罐_跨段4 |
| 100听以上_跨段1 | 100罐以上_跨段1 |
| 19-36听_跨段7 | 19-36罐_跨段7 |
| 37-42听_跨段7 | 37-42罐_跨段7 |
| 43听-100_跨段5 | 43-100罐_跨段5 |
| 100听以上_跨段2 | 100罐以上_跨段2 |
| 37-42听_跨段8 | 37-42罐_跨段8 |
| 43听-100_跨段6 | 43-100罐_跨段6 |
| 100听以上_跨段3 | 100罐以上_跨段3 |
| 43听-100_跨段7 | 43-100罐_跨段7 |
| 100听以上_跨段4 | 100罐以上_跨段4 |
| 1-18听 | 1-18罐 |
| 19-36听 | 19-36罐 |
| 37-42听 | 37-42罐 |
| 43-100听 | 43-100罐 |
| 100听以上 | 100罐以上 |
| IQC_Tins | IQC罐数 |

# [SNC_PERP_KPI_Incentive_Service] 字段注释说明
本表记录了SNC PERP KPI激励服务信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | 品牌 |
| Stage | 阶段 |
| BuyTime | 购买时间 |
| ProductName | 产品名称 |
| 购买SNC | 购买SNC |
| Source | 来源 |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | 按天排序_刨除普配s1 |
| OrderWithDay_刨普s1 | 按天排序_刨除普配s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单来源 |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段购买时间 |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段购买时间 |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNC代码 |
| 前一单Source | 前一单来源 |
| OrderWithDay_转段_时间 | 按天排序_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNC代码 |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| TankBarcode | 罐条码 |
| IQC_Time | IQC时间 |
| IQC_1st_Time | IQC第一时间 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Service_History] 字段注释说明
本表记录了SNC PERP KPI激励服务历史信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | 品牌 |
| Stage | 阶段 |
| BuyTime | 购买时间 |
| ProductName | 产品名称 |
| 购买SNC | 购买SNC |
| Source | 来源 |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | 按天排序_刨除普配s1 |
| OrderWithDay_刨普s1 | 按天排序_刨除普配s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单来源 |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段购买时间 |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段购买时间 |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNC代码 |
| 前一单Source | 前一单来源 |
| OrderWithDay_转段_时间 | 按天排序_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNC代码 |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| TankBarcode | 罐条码 |
| IQC_Time | IQC时间 |
| IQC_1st_Time | IQC第一时间 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Service_History_20250609] 字段注释说明
本表记录了2025年6月9日的SNC PERP KPI激励服务历史信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Unionid | Unionid |
| Brand | 品牌 |
| Stage | 阶段 |
| BuyTime | 购买时间 |
| ProductName | 产品名称 |
| 购买SNC | 购买SNC |
| Source | 来源 |
| 购买月份 | 购买月份 |
| 购买日期 | 购买日期 |
| OrderbyDay_刨普s1 | 按天排序_刨除普配s1 |
| OrderWithDay_刨普s1 | 按天排序_刨除普配s1 |
| 前一单时间 | 前一单时间 |
| 距离前一单天数 | 距离前一单天数 |
| 当天第一单购买SNC | 当天第一单购买SNC |
| 当天第一单Source | 当天第一单来源 |
| BR | BR |
| BR_11M | BR_11M |
| 转段BuyTime | 转段购买时间 |
| 转段购买日期 | 转段购买日期 |
| 第一次一二段buytime | 第一次一二段购买时间 |
| 转段前有一二段_判断 | 转段前有一二段_判断 |
| 购买时月龄 | 购买时月龄 |
| 同天排序转段辅助 | 同天排序转段辅助 |
| 前一单当天最早SNCCode | 前一单当天最早SNC代码 |
| 前一单Source | 前一单来源 |
| OrderWithDay_转段_时间 | 按天排序_转段_时间 |
| 客户类型 | 客户类型 |
| 首购日期 | 首购日期 |
| 首购SNCCode | 首购SNC代码 |
| 购买次数判断_无转段 | 购买次数判断_无转段 |
| 购买奖励判断 | 购买奖励判断 |
| 是否异常 | 是否异常 |
| 是否异常-贴报告 | 是否异常-贴报告 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| TankBarcode | 罐条码 |
| IQC_Time | IQC时间 |
| IQC_1st_Time | IQC第一时间 |

# [SNC_PERP_KPI_Incentive_Tins] 字段注释说明
本表记录了SNC PERP KPI激励罐数信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18罐 |
| 19-36听 | 19-36罐 |
| 37-42听 | 37-42罐 |
| 43-100听 | 43-100罐 |
| 100听以上 | 100罐以上 |
| 当月大于18M的听数 | 当月大于18M的罐数 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| IQC_1-18听 | IQC_1-18罐 |
| IQC_19-36听 | IQC_19-36罐 |
| IQC_37-42听 | IQC_37-42罐 |
| IQC_43-100听 | IQC_43-100罐 |
| IQC_当月大于18M的听数 | IQC_当月大于18M的罐数 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Tins_History] 字段注释说明
本表记录了SNC PERP KPI激励罐数历史信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18罐 |
| 19-36听 | 19-36罐 |
| 37-42听 | 37-42罐 |
| 43-100听 | 43-100罐 |
| 100听以上 | 100罐以上 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| IQC_1-18听 | IQC_1-18罐 |
| IQC_19-36听 | IQC_19-36罐 |
| IQC_37-42听 | IQC_37-42罐 |
| IQC_43-100听 | IQC_43-100罐 |
| IQC_当月大于18M的听数 | IQC_当月大于18M的罐数 |
| ID | ID |

# [SNC_PERP_KPI_Incentive_Tins_History_20250519] 字段注释说明
本表记录了2025年5月19日的SNC PERP KPI激励罐数历史信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买SNC | 购买SNC |
| 1-18听 | 1-18罐 |
| 19-36听 | 19-36罐 |
| 37-42听 | 37-42罐 |
| 43-100听 | 43-100罐 |
| 100听以上 | 100罐以上 |
| Months | 月份 |
| CreatedOn | 创建时间 |
| IQC_1-18听 | IQC_1-18罐 |
| IQC_19-36听 | IQC_19-36罐 |
| IQC_37-42听 | IQC_37-42罐 |
| IQC_43-100听 | IQC_43-100罐 |

# [SNC_Rating] 字段注释说明
本表记录了SNC评分信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| uniacid | uniacid |
| serial_number | 序列号 |
| openid | openid |
| stage | 阶段 |
| realname | 真实姓名 |
| num | 数量 |
| content | 内容 |
| addtime | 添加时间 |
| updatetime | 更新时间 |
| sendtime | 发送时间 |
| status | 状态 |
| is_sync | 是否同步 |
| sync_time | 同步时间 |
| order_num | 订单号 |
| source | 来源 |
| update_time | 更新时间 |
| giftcode | 礼品码 |
| ans1 | 答案1 |
| ans2 | 答案2 |
| ans2_other | 答案2其他 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | Unionid |
| completed_questionnaire_date | 完成问卷日期 |
| newcustomer_type | 新客户类型 |
| id | ID |

# [SNC_TAG_Defination] 字段注释说明
本表记录了SNC标签定义信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 名称 | 名称 |
| 标签类型 | 标签类型 |
| 标签类型Code | 标签类型代码 |
| CreatedOn | 创建时间 |
| LastChange | 最后更改时间 |
| ID | ID |

# [SNC_Tagging] 字段注释说明
本表记录了SNC打标信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Tags | 标签 |
| Source | 来源 |
| SNCCode | SNC代码 |
| Store_number | 门店编号 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| Unionid | Unionid |

# [Source] 字段注释说明
本表记录了来源信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Offset_Day | 偏移天数 |
| TA_CMT_ID | TA CMT ID |
| TA_Openid | TA Openid |
| TA_Mobile | TA手机 |
| RegisterChannel | 注册渠道 |
| SUB_USER_NAME | 子用户名 |
| Baby_BirthDay | 宝宝生日 |
| Current_stage | 当前阶段 |
| Stage | 阶段 |
| joindate | 加入日期 |
| Tag | 标签 |
| Buy_History | 购买历史 |
| SNC_Code | SNC代码 |
| SNC_Code_ExternalContact | SNC代码外部联系人 |
| SNC_Code_Show | SNC代码显示 |
| ON_CMT | 在CMT上 |
| ON_CRM_Plus | 在CRM Plus上 |
| Touch_Point | 触点 |
| Store_Number | 门店编号 |

# [SQL_ErrorLog] 字段注释说明
本表记录了SQL错误日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| TEXT | 文本 |

# [t_bi_channel] 字段注释说明
本表记录了BI渠道信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| QRCode_Internal | 内部二维码 |
| QrCode | 二维码 |
| CustomerNumberL7 | 7级客户编号 |

# [TBPromoterInspection2] 字段注释说明
本表记录了TB促销员检查信息2。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| IsOnDuty | 是否在职 |
| Photo | 照片 |
| FK_Store_ID | 门店外键ID |
| FK_SystemUser_ID | 系统用户外键ID |
| IsDelete | 是否删除 |
| CreateTime | 创建时间 |
| FK_SystemUser_Create_ID | 创建系统用户外键ID |
| ModifyTime | 修改时间 |
| FK_SystemUser_Modify_ID | 修改系统用户外键ID |
| FK_SystemUserDepartment_Create_ID | 创建系统用户部门外键ID |
| IsValid | 是否有效 |
| LastChange | 最后更改时间 |

# [TestCol] 字段注释说明
本表记录了测试列信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| table | 表 |
| columns | 列 |

# [testtable] 字段注释说明
本表记录了测试表信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Name | 名称 |
| Rows | 行数 |

# [TOB_HAS3扫码出库记录] 字段注释说明
本表记录了TOB HAS3扫码出库记录。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 订单编号 | 订单编号 |
| gift_code | 礼品码 |
| 会员unionid | 会员unionid |
| 会员加密手机号 | 会员加密手机号 |
| 门店编码 | 门店编码 |
| 门店名称 | 门店名称 |
| 区域 | 区域 |
| 城市组 | 城市组 |
| KA Type | KA类型 |
| KA Name | KA名称 |
| vip_level | VIP等级 |
| 店主店员编号 | 店主店员编号 |
| 罐码 | 罐码 |
| 达成 | 达成 |
| 说明 | 说明 |
| 备注 | 备注 |
| cdate | 创建日期 |

# [Trigger_Log] 字段注释说明
本表记录了触发器日志信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| TableName | 表名 |
| DDLType | DDL类型 |
| CreatedOn | 创建时间 |
| ID | ID |

# [TX_AntiCheat] 字段注释说明
本表记录了腾讯反作弊信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | 手机号md5 |
| ip | ip地址 |
| is_send | 是否发送 |
| payload | 有效负载 |
| response | 响应 |
| sent2tcdate | 发送至腾讯日期 |
| RiskLevel | 风险等级 |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
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
| createdon | 创建于 |
| Comments | 评论 |
| RiskType | 风险类型 |
| ID | ID |

# [TX_AntiCheat_20241011_snc] 字段注释说明
本表记录了2024年10月11日的腾讯反作弊SNC信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | 手机号md5 |
| ip | ip地址 |
| is_send | 是否发送 |
| payload | 有效负载 |
| response | 响应 |
| sent2tcdate | 发送至腾讯日期 |
| RiskLevel | 风险等级 |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
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
| createdon | 创建于 |
| Comments | 评论 |

# [TX_AntiCheat_20241011_snc_xinke] 字段注释说明
本表记录了2024年10月11日的腾讯反作弊SNC新客信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | 手机号md5 |
| ip | ip地址 |
| is_send | 是否发送 |
| payload | 有效负载 |
| response | 响应 |
| sent2tcdate | 发送至腾讯日期 |
| RiskLevel | 风险等级 |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
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
| createdon | 创建于 |
| Comments | 评论 |

# [TX_AntiCheat_20241021] 字段注释说明
本表记录了2024年10月21日的腾讯反作弊信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | 手机号md5 |
| ip | ip地址 |
| is_send | 是否发送 |
| payload | 有效负载 |
| response | 响应 |
| sent2tcdate | 发送至腾讯日期 |
| RiskLevel | 风险等级 |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
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
| createdon | 创建于 |
| Comments | 评论 |
| RiskType | 风险类型 |

# [TX_AntiCheat_20241023] 字段注释说明
本表记录了2024年10月23日的腾讯反作弊信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| 购买时间 | 购买时间 |
| unionid | unionid |
| mobile_md5 | 手机号md5 |
| ip | ip地址 |
| is_send | 是否发送 |
| payload | 有效负载 |
| response | 响应 |
| sent2tcdate | 发送至腾讯日期 |
| RiskLevel | 风险等级 |
| mobile | 手机号码 |
| s_mobile | S端手机号 |
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
| createdon | 创建于 |
| Comments | 评论 |
| RiskType | 风险类型 |

# [TX_MOT_Session] 字段注释说明
本表记录了腾讯MOT会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| motId | MOT ID |
| motType | MOT类型 |
| motScene | MOT场景 |
| motBrand | MOT品牌 |
| motProduct | MOT产品 |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| customerMsgCount | 客户消息数 |
| id | ID |

# [TX_MOT_Session_20241014] 字段注释说明
本表记录了2024年10月14日的腾讯MOT会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| motId | MOT ID |
| motType | MOT类型 |
| motScene | MOT场景 |
| motBrand | MOT品牌 |
| motProduct | MOT产品 |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| customerMsgCount | 客户消息数 |

# [TX_MOT_Session_20241216] 字段注释说明
本表记录了2024年12月16日的腾讯MOT会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| motId | MOT ID |
| motType | MOT类型 |
| motScene | MOT场景 |
| motBrand | MOT品牌 |
| motProduct | MOT产品 |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| customerMsgCount | 客户消息数 |

# [TX_MOT_Session_20250326] 字段注释说明
本表记录了2025年3月26日的腾讯MOT会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| motId | MOT ID |
| motType | MOT类型 |
| motScene | MOT场景 |
| motBrand | MOT品牌 |
| motProduct | MOT产品 |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| customerMsgCount | 客户消息数 |

# [TX_MOT_Supplement] 字段注释说明
本表记录了腾讯MOT补充信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| sessionId | 会话ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| motSendTime | MOT发送时间 |
| motSendTimeCD | MOT发送时间CD |
| content | 内容 |
| sendTime | 发送时间 |
| sendTimeCD | 发送时间CD |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| sessionId | 会话ID |

# [TX_Session] 字段注释说明
本表记录了腾讯会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| responseTime | 响应时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |
| id | ID |

# [TX_Session_20250326] 字段注释说明
本表记录了2025年3月26日的腾讯会话信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | ID |
| customerId | 客户ID |
| fellowId | 同事ID |
| departmentId | 部门ID |
| roundCount | 回合数 |
| msgCount | 消息数 |
| duration | 持续时间 |
| responseTime | 响应时间 |
| initiator | 发起者 |
| terminator | 终止者 |
| beginTime | 开始时间 |
| endTime | 结束时间 |
| beginTimeCD | 开始时间CD |
| endTimeCD | 结束时间CD |
| isConversation | 是否对话 |
| orders | 订单 |
| Is_Delete | 是否删除 |
| CreatedOn | 创建时间 |
| ModifiedOn | 修改时间 |
| comments | 评论 |

# [TX_SSE_SSR_20241107] 字段注释说明
本表记录了2024年11月7日的腾讯SSE SSR信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Store_Code | 门店代码 |
| Store_Name | 门店名称 |
| Region | 区域 |
| CG | 城市组 |
| Province | 省份 |
| City | 城市 |
| City_Level | 城市级别 |
| Vip_Level | VIP等级 |
| Client Group | 客户组 |
| OAH/Non-OAH | OAH/非OAH |
| 编码 | 编码 |
| 微信号(绑定的企业微信ID) | 微信号(绑定的企业微信ID) |
| IP | IP地址 |
| 手机号 | 手机号 |
| 角色 | 角色 |

# [UpsertRateControl] 字段注释说明
本表记录了更新插入速率控制信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| FuncationName | 函数名称 |
| SecondTimestamp | 秒级时间戳 |
| UpsertCount | 更新插入计数 |
| CreatedOn | 创建时间 |
| ID | ID |

# [V_DAILY_NSC_Spark_S3_Bonus_RawData2] 字段注释说明
本表记录了每日NSC Spark S3奖励原始数据2。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| BuyTime | 购买时间 |
| area_name | 区域名称 |
| province | 省份 |
| city_group | 城市组 |
| city | 城市 |
| ka_type | KA类型 |
| ka_name | KA名称 |
| SNCCode | SNC代码 |
| StoreCode | 门店代码 |
| Store_Name | 门店名称 |
| Vip_Level | VIP等级 |
| 是否有导 | 是否有导 |
| 是否院线店 | 是否院线店 |
| Unionid | Unionid |
| Brand | 品牌 |
| Stage | 阶段 |
| ProductCode | 产品代码 |
| ProductName | 产品名称 |
| Qty | 数量 |
| OrderNum | 订单号 |
| ID_CRMPlus | CRMPlus ID |
| 是否退单 | 是否退单 |
| 订单罐数 | 订单罐数 |
| 退单罐数 | 退单罐数 |

# [铂初分销店单Q2] 字段注释说明
本表记录了铂初分销店单Q2信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
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
本表记录了罐子信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | 产品代码 |
| QRCode | 二维码 |
| RN2 | 行号2 |

# [星火门店详情Monthly] 字段注释说明
本表记录了星火门店月度详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | 区域 |
| CG | 城市组 |
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
| CreatedOn | 创建时间 |

# [星火门店详情Monthly_20241101] 字段注释说明
本表记录了2024年11月1日的星火门店月度详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | 区域 |
| CG | 城市组 |
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
| CreatedOn | 创建时间 |

# [星火门店详情Monthly202409_1101] 字段注释说明
本表记录了2024年9月至11月1日的星火门店月度详情。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Region | 区域 |
| CG | 城市组 |
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
| CreatedOn | 创建时间 |
