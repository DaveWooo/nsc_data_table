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
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| risk_level | risk_level |
| risk_type | risk_type |
| ksfid | ksfid |
| TYPE1 | TYPE1 |
| TYPE2 | TYPE2 |
| TYPE3 | TYPE3 |
| TYPE4 | TYPE4 |
| TYPE5 | TYPE5 |
| TYPE6 | TYPE6 |
| TYPE7 | TYPE7 |
| TYPE8 | TYPE8 |
| TYPE9 | TYPE9 |
| TYPE10 | TYPE10 |
| TYPE11 | TYPE11 |

# [ACCESS_LOGS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Request | Request |
| Method | Method |
| Token | Token |
| Payload | Payload |
| Response | Response |
| Status | Status |
| EnterDate | EnterDate |
| ElapsedMilliseconds | ElapsedMilliseconds |
| IP | IP |
| CreateDate | CreateDate |
| ID | ID |

# [ACCESS_LOGS_READ] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Request | Request |
| Method | Method |
| Token | Token |
| Payload | Payload |
| Response | Response |
| Status | Status |
| ElapsedMilliseconds | ElapsedMilliseconds |
| CreateDate | CreateDate |
| EnterDate | EnterDate |
| IP | IP |
| ID | ID |

# [ACCESS_TOKENS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Token | Token |
| SecurityKey | SecurityKey |
| Company | Company |
| IsValid | IsValid |
| Type | Type |
| IP | IP |
| CreatedDateTime | CreatedDateTime |
| ID | ID |

# [AL110_BoChu_MOT_TA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| AL110招募时间 | AL110招募时间 |
| TOC_AL110招募总量 | TOC_AL110招募总量 |
| 6M以下 | 6M以下 |
| 6M及以上 | 6M及以上 |
| 6M未领取样包 | 6M未领取样包 |
| 6M且领取样包 | 6M且领取样包 |
| 在D3之后 -6M且领取样包 | 在D3之后 -6M且领取样包 |
| 在D3之前-6M且领取样包 | 在D3之前-6M且领取样包 |
| 在D3之前6M且领取样包且未购买IMF | 在D3之前6M且领取样包且未购买IMF |
| 生成链接的人(43001) | 生成链接的人(43001) |
| 推送MOT的人(43001) | 推送MOT的人(43001) |
| 点了链接 | 点了链接 |
| 没点链接 | 没点链接 |
| 生成43002的人 | 生成43002的人 |
| 推送43002的人 | 推送43002的人 |
| 生成43003的人 | 生成43003的人 |
| 推送43003的人 | 推送43003的人 |
| 生成43004的人 | 生成43004的人 |
| 推送43004的人 | 推送43004的人 |
| 生成43005的人 | 生成43005的人 |
| 推送43005的人 | 推送43005的人 |
| D3D4未点链接 | D3D4未点链接 |
| 不可转奶数 | 不可转奶数 |
| 生成43006的人 | 生成43006的人 |
| 推送43006的人 | 推送43006的人 |
| 生成43007的人 | 生成43007的人 |
| 推送43007的人 | 推送43007的人 |
| 生成43008的人 | 生成43008的人 |
| 推送43008的人 | 推送43008的人 |

# [App_Settings] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Code | Code |
| Value | Value |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Code | Code |

# [Azure_Healthy_Detection] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Status | Status |
| Msg | Msg |
| ElapsedMilliseconds | ElapsedMilliseconds |
| CreatedOn | CreatedOn |
| ID | ID |

# [Birthday_Base] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Openid | Openid |
| unionid | unionid |
| Mobile | Mobile |
| current_stage | current_stage |
| StageByCRM | StageByCRM |
| 是否正在关注 | 是否正在关注 |
| BabyBirthday | BabyBirthday |
| Offset_Day | Offset_Day |
| CreatedOn | CreatedOn |

# [Birthday_BHRecruitment] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 铂护会员招募时间 | 铂护会员招募时间 |
| 铂护会员招募渠道 | 铂护会员招募渠道 |

# [Birthday_Binding] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| SNCCode | SNCCode |
| UpDate | UpDate |

# [Birthday_BoChuS3S4_Purchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 有无BCS3/S4产品购买 | 有无BCS3/S4产品购买 |
| BCS3/S4最近购买时间 | BCS3/S4最近购买时间 |

# [Birthday_Engage] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| 最近Engage时间 | 最近Engage时间 |
| 最近SC互动时间 | 最近SC互动时间 |
| 最近MC/BGT/OA互动时间 | 最近MC/BGT/OA互动时间 |

# [Birthday_HARecruitment] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 启护会员招募时间 | 启护会员招募时间 |
| 启护会员招募渠道 | 启护会员招募渠道 |
| 启护会员招募导购 | 启护会员招募导购 |
| 启护会员招募门店 | 启护会员招募门店 |

# [Birthday_Infomation] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| Openid | Openid |
| StageByCRM | StageByCRM |
| current_stage | current_stage |
| Offset_Day | Offset_Day |
| BabyBirthday | BabyBirthday |
| 是否正在关注 | 是否正在关注 |
| 最近购买brand | 最近购买brand |
| 最近购买stage | 最近购买stage |
| 最近购买时间 | 最近购买时间 |
| 最近购买SKU | 最近购买SKU |
| 最近购买罐数 | 最近购买罐数 |
| 绑定导购 | 绑定导购 |
| 绑定导购门店 | 绑定导购门店 |
| 导购是否在职 | 导购是否在职 |
| 最近Engage时间 | 最近Engage时间 |
| 最近MC/BGT/OA互动时间 | 最近MC/BGT/OA互动时间 |
| 最近SC互动时间 | 最近SC互动时间 |
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
| 有无BCS3/S4产品购买 | 有无BCS3/S4产品购买 |
| BCS3/S4最近购买时间 | BCS3/S4最近购买时间 |
| 有无HAS3/S4产品购买 | 有无HAS3/S4产品购买 |
| 有无PTS3/S4产品购买 | 有无PTS3/S4产品购买 |
| 有无HAS4产品购买 | 有无HAS4产品购买 |
| 有无IMF购买记录 | 有无IMF购买记录 |
| IMF_NOPT_最近购买时间 | IMF_NOPT_最近购买时间 |
| 是否参加生日礼 | 是否参加生日礼 |
| 判断日期 | 判断日期 |

# [Birthday_Joined] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 是否参加生日礼 | 是否参加生日礼 |

# [Birthday_Recent_Buy_IMF_DATE] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF最近购买时间 | IMF最近购买时间 |

# [Birthday_Recent_Buy_IMF_NOPT_DATE] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| IMF_NOPT_最近购买时间 | IMF_NOPT_最近购买时间 |

# [Birthday_Recent_Purchse_Brand] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| 最近购买brand | 最近购买brand |
| 最近购买stage | 最近购买stage |
| 最近购买时间 | 最近购买时间 |
| 最近购买SKU | 最近购买SKU |
| 最近购买罐数 | 最近购买罐数 |

# [Birthday_RunTA_Set] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| RunDate | RunDate |
| Tag | Tag |

# [Birthday_S3S4_Purchase] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 有无HAS3/S4产品购买 | 有无HAS3/S4产品购买 |
| 有无PTS3/S4产品购买 | 有无PTS3/S4产品购买 |
| 有无HAS4产品购买 | 有无HAS4产品购买 |
| 有无IMF购买记录 | 有无IMF购买记录 |

# [Birthday_SHRecruitment] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 守护会员招募时间 | 守护会员招募时间 |
| 守护会员招募渠道 | 守护会员招募渠道 |

# [Birthday_Slow20240514] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Unionid | Unionid |
| Member_Type | Member_Type |
| SNC_Code | SNC_Code |
| Store_Number | Store_Number |
| Touch_Point | Touch_Point |
| CreatedOn | CreatedOn |
| SentToCMTON | SentToCMTON |
| Current_Stage | Current_Stage |
| Offset_Day | Offset_Day |
| Birthday | Birthday |
| IsEngaged | IsEngaged |
| ha12_type | ha12_type |

# [Birthday_SNC_OnJob] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| serial_number | serial_number |
| store_number | store_number |
| 导购是否在职 | 导购是否在职 |

# [Birthday_YHRecruitment] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| 优护会员招募时间 | 优护会员招募时间 |
| 优护会员招募渠道 | 优护会员招募渠道 |

# [BirthdayGift_StorageData] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| Openid | Openid |
| current_stage | current_stage |
| 绑定导购 | 绑定导购 |
| 绑定导购门店 | 绑定导购门店 |
| MemberType | MemberType |
| ha12_type | ha12_type |
| Touch_Point | Touch_Point |
| Offset_Day | Offset_Day |
| BabyBirthday | BabyBirthday |
| IsEngaged | IsEngaged |

# [BLHX_ActivityInfo] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| hd_no | hd_no |
| title | title |
| type | type |
| sdate | sdate |
| edate | edate |
| gift_id | gift_id |
| gift_code | gift_code |
| gift_name | gift_name |
| zg_title | zg_title |
| exp_type | exp_type |
| premium_share | premium_share |
| premium_first | premium_first |
| zm_share | zm_share |
| product_codes | product_codes |
| buy_num | buy_num |
| is_enable | is_enable |
| min_month | min_month |
| cdate | cdate |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| hd_no | hd_no |

# [BLHX_CouponsInfo] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| unionid | unionid |
| mobile | mobile |
| stime | stime |
| etime | etime |
| stores_list | stores_list |
| hd_no | hd_no |
| gift_code | gift_code |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| UseDatetime | UseDatetime |
| ExpireDatetime | ExpireDatetime |
| Expire2OADatetime | Expire2OADatetime |
| HA_Xinke | HA_Xinke |
| TeHu_Xinke | TeHu_Xinke |
| type | type |
| is_black | is_black |
| unionid | unionid |
| hd_no | hd_no |

# [BoChuSampleTempTA] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| TargetType | TargetType |
| GetSampleTime | GetSampleTime |
| RecentBuyTime | RecentBuyTime |
| RecentBuyCount | RecentBuyCount |
| EmptyDate | EmptyDate |
| FirstTriggerDate | FirstTriggerDate |
| SecondTriggerDate | SecondTriggerDate |

# [CRM_API_LOGS] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Method | Method |
| Payload | Payload |
| Response | Response |
| CreateDate | CreateDate |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [CRM_Baby] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
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
| Frozen | Frozen |
| OperationFlag | OperationFlag |
| ModifiedOn | ModifiedOn |
| ModifiedBy | ModifiedBy |
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_CallResult] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| KSFId | KSFId |
| CMamaId | CMamaId |
| PMamaId | PMamaId |
| Mobile1 | Mobile1 |
| Mobile2 | Mobile2 |
| BatchNumber | BatchNumber |
| ImportStatus | ImportStatus |
| FaildReason | FaildReason |
| IsSpotCheck | IsSpotCheck |
| IsNewCustomer | IsNewCustomer |
| UpdateCustName | UpdateCustName |
| UpdatebrandName | UpdatebrandName |
| UpdateBuyTime | UpdateBuyTime |
| CallContent | CallContent |
| CallUser | CallUser |
| CallTime | CallTime |
| UserBrand | UserBrand |
| ContinueBuy | ContinueBuy |
| CallStatus | CallStatus |
| InvalidReason | InvalidReason |
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| CallResult | CallResult |
| IsNameValid | IsNameValid |
| IsBuy | IsBuy |
| IsProductNameValid | IsProductNameValid |
| CurrentMomBrand | CurrentMomBrand |
| CurrentNicBrand | CurrentNicBrand |
| CurrentS3NestleBrand | CurrentS3NestleBrand |
| CurrentS3CompeteBrand | CurrentS3CompeteBrand |
| CallRemark | CallRemark |
| OperationFlag | OperationFlag |
| BrandExperience | BrandExperience |
| IsApprovalBrand | IsApprovalBrand |
| IsReceiveGift | IsReceiveGift |
| NewCustomerType | NewCustomerType |
| ReferrerPhone | ReferrerPhone |
| GiftMechanism | GiftMechanism |
| IsRiskSurvey | IsRiskSurvey |
| RiskSurveyDate | RiskSurveyDate |
| AllergicFactors | AllergicFactors |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_FAQ] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| ID | ID |
| InfoType | InfoType |
| Question | Question |
| Ans | Ans |
| ParentId | ParentId |
| OrderID | OrderID |
| AttName | AttName |
| AttPath | AttPath |
| QueryAns | QueryAns |
| OperationFlag | OperationFlag |
| txUser | txUser |
| txDate | txDate |
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_Inbound] 字段注释说明
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
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| QuestionDetailJSON | QuestionDetailJSON |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_Inbound_DS] 字段注释说明
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
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| QuestionDetailJSON | QuestionDetailJSON |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [CRM_Mama] 字段注释说明
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
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| ActivityChannel | ActivityChannel |
| CMT_ID | CMT_ID |
| MamaNameFromSNC | MamaNameFromSNC |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Unionid | Unionid |
| Comments | Comments |
| PID | PID |

# [CRM_Manufactor] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ManufactorID | ManufactorID |
| ManufactorName | ManufactorName |
| UserType | UserType |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [CRM_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
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
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_Member_Profiles] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| M_MOBILE | M_MOBILE |
| M_PASSWORD | M_PASSWORD |
| M_IS_VAILD | M_IS_VAILD |
| M_INVAILD_REASON | M_INVAILD_REASON |
| M_CREATE_DATE | M_CREATE_DATE |
| M_UPDATE_DATE | M_UPDATE_DATE |
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
| SOU_REG_URL | SOU_REG_URL |
| SOU_PREVIOUS_URL | SOU_PREVIOUS_URL |
| SOU_CONFERENCE_CODE | SOU_CONFERENCE_CODE |
| SOU_TRACKING_CODE_06 | SOU_TRACKING_CODE_06 |
| SWD_DATA_SOURCE | SWD_DATA_SOURCE |
| WECHAT_BIND | WECHAT_BIND |
| WECHAT_BIND_FLAG | WECHAT_BIND_FLAG |
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| SR_USER_NAME | SR_USER_NAME |
| SR_STORE_CODE | SR_STORE_CODE |
| SR_AREA | SR_AREA |
| SR_PROVINCE | SR_PROVINCE |
| SR_CITY | SR_CITY |
| SR_CODE | SR_CODE |
| SR_CHANNEL | SR_CHANNEL |
| SR_CITY_GROUP | SR_CITY_GROUP |
| SR_STORE_NAME | SR_STORE_NAME |
| CMT_ID | CMT_ID |
| SR_QRCODE | SR_QRCODE |
| WECHAT_CARD_CODE | WECHAT_CARD_CODE |
| SUB_BABY_GENDER | SUB_BABY_GENDER |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| M_TYPE | M_TYPE |
| CMT_UNIONID | CMT_UNIONID |
| Remark | Remark |
| S_MOBILE | S_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Completed_Shouhu_Questionnaire1_Date | Completed_Shouhu_Questionnaire1_Date |
| Completed_Qihu_Questionnaire1_Date | Completed_Qihu_Questionnaire1_Date |
| Completed_Youhu_Questionnaire1_Date | Completed_Youhu_Questionnaire1_Date |
| Completed_Qihu_Questionnaire2_Date | Completed_Qihu_Questionnaire2_Date |
| Completed_Youhu_Questionnaire2_Date | Completed_Youhu_Questionnaire2_Date |
| Completed_Cmpa_Questionnaire_Date | Completed_Cmpa_Questionnaire_Date |
| Completed_Info | Completed_Info |
| Completed_ARI | Completed_ARI |
| Brand_Prospect | Brand_Prospect |
| MS_GP_Tag | MS_GP_Tag |
| SYNC_TIME | SYNC_TIME |
| Last_SYNC_Time | Last_SYNC_Time |
| WECHAT_BIND_GB | WECHAT_BIND_GB |
| WECHAT_BIND_FLAG_GB | WECHAT_BIND_FLAG_GB |
| WECHAT_BIND_CT | WECHAT_BIND_CT |
| Completed_Bohu_Questionnaire1_Date | Completed_Bohu_Questionnaire1_Date |
| Completed_Bohu_Questionnaire2_Date | Completed_Bohu_Questionnaire2_Date |
| Completed_Shuhu_Questionnaire1_Date | Completed_Shuhu_Questionnaire1_Date |
| Vip_Level | Vip_Level |
| NHS_Unionid | NHS_Unionid |
| PID | PID |

# [CRM_MOT_Back] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Unionid | Unionid |
| Recruit_Brand | Recruit_Brand |
| SNCCode | SNCCode |
| SNCName | SNCName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| Source | Source |
| CalSeqNo | CalSeqNo |
| CsrCallTime | CsrCallTime |
| Tag_List | Tag_List |
| Baby_Status | Baby_Status |
| Is_Chg_Milk | Is_Chg_Milk |
| Is_Age_Confirm | Is_Age_Confirm |
| Is_Activa_HCP | Is_Activa_HCP |
| Use_Sample | Use_Sample |
| Repurchase_Type | Repurchase_Type |
| Is_Valid | Is_Valid |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| KSFID | KSFID |
| CalSeqNo | CalSeqNo |

# [CRM_Outbound] 字段注释说明
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
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| ActivityChannel | ActivityChannel |
| EqualResult | EqualResult |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRM_Register] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Appid | Appid |
| CreatedOn | CreatedOn |
| ID | ID |

# [CRM_SurveyResult] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SurveyResultID | SurveyResultID |
| CampaignId | CampaignId |
| MamaId | MamaId |
| KsfId | KsfId |
| CallseqNo | CallseqNo |
| SurveyName | SurveyName |
| OperationFlag | OperationFlag |
| SurveyDetailList | SurveyDetailList |
| PDateReceived | PDateReceived |
| PDateProcessed | PDateProcessed |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [CRM_WechatData] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| PID | PID |
| ID | ID |
| ProblemTagName | ProblemTagName |
| WxOpenID | WxOpenID |
| Category | Category |
| SubCategory | SubCategory |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| OperationFlag | OperationFlag |
| PDateProcessed | PDateProcessed |
| PDateReceived | PDateReceived |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PID | PID |

# [CRMPlus_API_LOG] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Request | Request |
| Method | Method |
| Payload | Payload |
| Response | Response |
| Status | Status |
| PushAgainDate | PushAgainDate |
| OriginId | OriginId |
| CreatedOn | CreatedOn |
| ElapsedMilliseconds | ElapsedMilliseconds |
| Id | Id |

# [CRMPlus_Order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| OrderNum | OrderNum |
| PgNum | PgNum |
| PgName | PgName |
| StoreCode | StoreCode |
| StoreName | StoreName |
| Openid | Openid |
| OrderMobile | OrderMobile |
| UserId | UserId |
| OrderCreateTime | OrderCreateTime |
| OrderModifyTime | OrderModifyTime |
| TankBarcode | TankBarcode |
| BoxBarcode | BoxBarcode |
| ReturnTankBarcode | ReturnTankBarcode |
| ReturnCount | ReturnCount |
| PurchaseStatus | PurchaseStatus |
| QRCodeLink | QRCodeLink |
| OperationFlag | OperationFlag |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| OrderEntry | OrderEntry |
| Recordstatus | Recordstatus |
| Channel | Channel |
| S_MOBILE | S_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| TouchPoint | TouchPoint |
| Unionid | Unionid |
| BU | BU |
| Vip_Level | Vip_Level |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| BabyBirthday | BabyBirthday |
| TNRS | TNRS |
| IsShareOrder | IsShareOrder |
| Tcds_Id | Tcds_Id |
| ID | ID |

# [CRMPlus_Order_ProductCode] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| OrderNum | OrderNum |
| ProductCode | ProductCode |
| Type | Type |
| Count | Count |
| TankBarcode | TankBarcode |
| BoxBarcode | BoxBarcode |
| OrdeModifiedTime | OrdeModifiedTime |
| Price | Price |
| TotalPrice | TotalPrice |
| PurchaseStatus | PurchaseStatus |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| ID_CRMPlus | ID_CRMPlus |
| LastChange | LastChange |
| CampaignId | CampaignId |
| NewCustomterType | NewCustomterType |
| OrderCreateTime | OrderCreateTime |
| ID | ID |

# [DATA_Baby] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| Frozen | Frozen |
| OperationFlag | OperationFlag |
| ModifiedOn | ModifiedOn |
| ModifiedBy | ModifiedBy |
| IsSentToCRM | IsSentToCRM |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| PBabyId | PBabyId |

# [DATA_CallTypeList] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| InboundID | InboundID |
| CallType1 | CallType1 |
| CallType2 | CallType2 |
| CallType3 | CallType3 |
| CallType4 | CallType4 |
| CallType5 | CallType5 |
| CallType6 | CallType6 |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Id | Id |

# [DATA_Campaign_Activity] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| Mobile | Mobile |
| CampaignId | CampaignId |
| CampaignName | CampaignName |
| CampaignType | CampaignType |
| Channel | Channel |
| GiftCode | GiftCode |
| BuyDate | BuyDate |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Remark | Remark |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Mobile | Mobile |
| CampaignId | CampaignId |

# [DATA_Campaign_Activity_2022] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Mobile | Mobile |
| CampaignId | CampaignId |
| Sequence | Sequence |
| Channel | Channel |
| TouchPoint | TouchPoint |
| GiftCode | GiftCode |
| BuyDate | BuyDate |
| OrderId | OrderId |
| SNCCode | SNCCode |
| StoreID | StoreID |
| IsValid | IsValid |
| Completed_Questionnaire_2_Date | Completed_Questionnaire_2_Date |
| Remark | Remark |
| BuyDate_2 | BuyDate_2 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| BU | BU |
| Unionid | Unionid |
| Resume_Qualification | Resume_Qualification |
| ID_CRMPlus | ID_CRMPlus |
| Vip_Level | Vip_Level |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| Tcds_Id | Tcds_Id |
| Unionid | Unionid |
| CampaignId | CampaignId |
| Sequence | Sequence |

# [DATA_Campaign_Activity_2022_250314] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Mobile | Mobile |
| CampaignId | CampaignId |
| Sequence | Sequence |
| Channel | Channel |
| TouchPoint | TouchPoint |
| GiftCode | GiftCode |
| BuyDate | BuyDate |
| OrderId | OrderId |
| SNCCode | SNCCode |
| StoreID | StoreID |
| IsValid | IsValid |
| Completed_Questionnaire_2_Date | Completed_Questionnaire_2_Date |
| Remark | Remark |
| BuyDate_2 | BuyDate_2 |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| BU | BU |
| Unionid | Unionid |
| Resume_Qualification | Resume_Qualification |
| ID_CRMPlus | ID_CRMPlus |
| Vip_Level | Vip_Level |
| Cus_Number | Cus_Number |
| Cus_Uid | Cus_Uid |
| Is_Spark | Is_Spark |
| Tcds_Id | Tcds_Id |

# [DATA_Campaign_Activity_2022_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S_Mobile |
| QiHu_2_Qualification | QiHu_2_Qualification |
| Youhu_2_Qualification | Youhu_2_Qualification |
| CreateOn | CreateOn |
| ID | ID |

# [DATA_Campaign_Period] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CampaignID | CampaignID |
| CampaignType | CampaignType |
| CampaignName | CampaignName |
| GiftCodeList | GiftCodeList |
| Sequence | Sequence |
| Brand | Brand |
| Remark | Remark |
| PeriodStart | PeriodStart |
| PeriodEnd | PeriodEnd |
| CreatedOn | CreatedOn |
| LastChange | LastChange |
| Is_Spark | Is_Spark |
| MetCompliance | MetCompliance |
| MetCompliance_Stage_3 | MetCompliance_Stage_3 |
| Is_blhx | Is_blhx |
| CampaignID | CampaignID |

# [DATA_Campaign_Period_20240629] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CampaignID | CampaignID |
| CampaignType | CampaignType |
| CampaignName | CampaignName |
| GiftCodeList | GiftCodeList |
| Sequence | Sequence |
| Brand | Brand |
| Remark | Remark |
| PeriodStart | PeriodStart |
| PeriodEnd | PeriodEnd |
| CreatedOn | CreatedOn |
| LastChange | LastChange |
| Is_Spark | Is_Spark |
| MetCompliance | MetCompliance |
| MetCompliance_Stage_3 | MetCompliance_Stage_3 |

# [DATA_Channel] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Channel | Channel |
| Source | Source |
| Methed | Methed |
| Keyword | Keyword |
| IsOnline | IsOnline |
| Remark | Remark |

# [DATA_Chat] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| chatId | chatId |
| joinTime | joinTime |
| openid | openid |
| csrCode | csrCode |
| csrName | csrName |
| status | status |
| msgNum | msgNum |
| createTime | createTime |
| finishTime | finishTime |
| msgTagNum | msgTagNum |
| satisfactionVal | satisfactionVal |
| isSendMaterial | isSendMaterial |
| chatCloseType | chatCloseType |
| chatMsgData | chatMsgData |
| createdOn | createdOn |
| operationFlag | operationFlag |
| modifiedOn | modifiedOn |
| sentToCRMOn | sentToCRMOn |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| storeNumber | storeNumber |
| customerType | customerType |
| distNumber | distNumber |
| chatId | chatId |

# [DATA_ChatMsg] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| chatMsgId | chatMsgId |
| chatId | chatId |
| status | status |
| openid | openid |
| addTimestamp | addTimestamp |
| useType | useType |
| wxPicUrl | wxPicUrl |
| replyStatus | replyStatus |
| userAnswerDiff | userAnswerDiff |
| problemTagNames | problemTagNames |
| remind | remind |
| csrCode | csrCode |
| content | content |
| newsId | newsId |
| csrReplyDiff | csrReplyDiff |
| problemTagIds | problemTagIds |
| msgType | msgType |
| addTime | addTime |
| createdOn | createdOn |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| chatMsgId | chatMsgId |

# [DATA_Dictionary] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | Name |
| parent_id | parent_id |
| type | type |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [DATA_Inbound] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| QuestionDetailJSON | QuestionDetailJSON |
| IsSentToCRM | IsSentToCRM |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Id | Id |

# [DATA_Mama] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| IsSentToCRM | IsSentToCRM |
| ActivityChannel | ActivityChannel |
| CMT_ID | CMT_ID |
| MamaNameFromSNC | MamaNameFromSNC |
| S_MOBILE | S_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Unionid | Unionid |
| PMamaId | PMamaId |

# [DATA_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| IsBUChecked | IsBUChecked |
| ModifiedOn | ModifiedOn |
| ActivityChannel | ActivityChannel |
| IsSentToCRM | IsSentToCRM |
| CreatedOn | CreatedOn |
| SentToCRMOn | SentToCRMOn |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [DATA_Member_Channel] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| smt_mp | smt_mp |
| smt_md | smt_md |
| swd_channel_reg_typ | swd_channel_reg_typ |
| tags | tags |
| smt_class | smt_class |
| is_zhu | is_zhu |
| smt_sub_class | smt_sub_class |
| updatetime | updatetime |
| modifiedOn | modifiedOn |

# [DATA_Member_Profiles] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| CMT_ID | CMT_ID |
| M_MOBILE | M_MOBILE |
| M_PASSWORD | M_PASSWORD |
| M_IS_VAILD | M_IS_VAILD |
| M_INVAILD_REASON | M_INVAILD_REASON |
| M_CREATE_DATE | M_CREATE_DATE |
| M_UPDATE_DATE | M_UPDATE_DATE |
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
| SOU_REG_URL | SOU_REG_URL |
| SOU_PREVIOUS_URL | SOU_PREVIOUS_URL |
| SOU_CONFERENCE_CODE | SOU_CONFERENCE_CODE |
| SOU_TRACKING_CODE_06 | SOU_TRACKING_CODE_06 |
| SWD_DATA_SOURCE | SWD_DATA_SOURCE |
| WECHAT_BIND | WECHAT_BIND |
| WECHAT_BIND_FLAG | WECHAT_BIND_FLAG |
| WECHAT_CARD_CODE | WECHAT_CARD_CODE |
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
| SYNC_TIME | SYNC_TIME |
| ModifiedOn | ModifiedOn |
| SUB_IS_RCV_MOBILE | SUB_IS_RCV_MOBILE |
| M_TYPE | M_TYPE |
| CMT_UNIONID | CMT_UNIONID |
| Remark | Remark |
| S_MOBILE | S_MOBILE |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Vip_Level | Vip_Level |
| NHS_Unionid | NHS_Unionid |
| CMT_ID | CMT_ID |

# [DATA_Outbound] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| ActivityChannel | ActivityChannel |
| IsSentToCRM | IsSentToCRM |
| EqualResult | EqualResult |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Id | Id |

# [DATA_Outbound_20250307] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
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
| ActivityChannel | ActivityChannel |
| IsSentToCRM | IsSentToCRM |
| EqualResult | EqualResult |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [DATA_RiskSurvey] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| openid | openid |
| mobile | mobile |
| question | question |
| answer1 | answer1 |
| answer2 | answer2 |
| answer3 | answer3 |
| answer4 | answer4 |
| answer5 | answer5 |
| answer6 | answer6 |
| answer7 | answer7 |
| answer8 | answer8 |
| answer9 | answer9 |
| answer10 | answer10 |
| level | level |
| label | label |
| label_count | label_count |
| create_time | create_time |
| CreatedOn | CreatedOn |
| SentCRMOn | SentCRMOn |
| ModifiedOn | ModifiedOn |
| Unionid | Unionid |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [DATA_Routin_Birthday_Daily] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Unionid | Unionid |
| Member_Type | Member_Type |
| SNC_Code | SNC_Code |
| Store_Number | Store_Number |
| Touch_Point | Touch_Point |
| CreatedOn | CreatedOn |
| SentToCMTON | SentToCMTON |
| Current_Stage | Current_Stage |
| Offset_Day | Offset_Day |
| Birthday | Birthday |
| IsEngaged | IsEngaged |
| ha12_type | ha12_type |
| ID | ID |

# [DATA_Routin_Birthday_Daily_BT] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Openid | Openid |
| Unionid | Unionid |
| Member_Type | Member_Type |
| SNC_Code | SNC_Code |
| Store_Number | Store_Number |
| Touch_Point | Touch_Point |
| CreatedOn | CreatedOn |
| SentToCMTON | SentToCMTON |
| Current_Stage | Current_Stage |
| Offset_Day | Offset_Day |
| Birthday | Birthday |
| IsEngaged | IsEngaged |
| ha12_type | ha12_type |

# [DATA_Routin_Birthday_Daily_Engage] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| unionid | unionid |
| Engage_times | Engage_times |

# [DATA_SurveyDetailList] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| SurveyResultID | SurveyResultID |
| QuestionCode | QuestionCode |
| QuestionName | QuestionName |
| OptionName | OptionName |
| Remark | Remark |
| itemText | itemText |
| CreatedOn | CreatedOn |
| PDateProcessed | PDateProcessed |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [DATA_SurveyResult] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| SurveyResultID | SurveyResultID |
| CampaignId | CampaignId |
| MamaId | MamaId |
| KsfId | KsfId |
| CallseqNo | CallseqNo |
| SurveyName | SurveyName |
| OperationFlag | OperationFlag |
| SurveyDetailList | SurveyDetailList |
| Q1 | Q1 |
| Q2 | Q2 |
| Q3 | Q3 |
| Q4 | Q4 |
| Q5 | Q5 |
| Q6 | Q6 |
| Q7 | Q7 |
| A1 | A1 |
| A2 | A2 |
| A3 | A3 |
| A4 | A4 |
| A5 | A5 |
| A6 | A6 |
| A7 | A7 |
| CreatedOn | CreatedOn |
| Q8 | Q8 |
| A8 | A8 |
| LastChange | LastChange |
| Q9 | Q9 |
| A9 | A9 |
| Q10 | Q10 |
| A10 | A10 |
| Q11 | Q11 |
| A11 | A11 |
| Q12 | Q12 |
| A12 | A12 |
| Sub_A1 | Sub_A1 |
| Sub_A2 | Sub_A2 |
| Sub_A3 | Sub_A3 |
| Sub_A4 | Sub_A4 |
| Sub_A5 | Sub_A5 |
| Sub_A6 | Sub_A6 |
| Sub_A7 | Sub_A7 |
| Sub_A8 | Sub_A8 |
| Sub_A9 | Sub_A9 |
| Sub_A10 | Sub_A10 |
| Sub_A11 | Sub_A11 |
| Sub_A12 | Sub_A12 |
| SurveyResultID | SurveyResultID |

# [DATA_Tuwen] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| wxArticleId | wxArticleId |
| title | title |
| titleUrl | titleUrl |
| outLine | outLine |
| content | content |
| formatType | formatType |
| formatTypeForm | formatTypeForm |
| formatUrl | formatUrl |
| formatBaiduUrl | formatBaiduUrl |
| readCount | readCount |
| downloadCount | downloadCount |
| forwardCount | forwardCount |
| commentCount | commentCount |
| createTime | createTime |
| updateTime | updateTime |
| status | status |
| brandId | brandId |
| brandTypeId | brandTypeId |
| jpgUrl | jpgUrl |
| pngUrl | pngUrl |
| userId | userId |
| fileSize | fileSize |
| seeFlag | seeFlag |
| attachId | attachId |
| thumbUrl | thumbUrl |
| author | author |
| digest | digest |
| url | url |
| showCoverPic | showCoverPic |
| contentSourceUrl | contentSourceUrl |
| displayorder | displayorder |
| orderTop | orderTop |
| collection | collection |
| createdOn | createdOn |
| pullMonth | pullMonth |
| id | id |
| pullMonth | pullMonth |

# [DATA_WechatData] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| ProblemTagName | ProblemTagName |
| WxOpenID | WxOpenID |
| Category | Category |
| SubCategory | SubCategory |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| OperationFlag | OperationFlag |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ID | ID |

# [DATA_YGYM] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Openid | Openid |
| Unionid | Unionid |
| S_MOBILE | S_MOBILE |
| ProductCode | ProductCode |
| ProductName | ProductName |
| ScanTime | ScanTime |
| NewCustomerType | NewCustomerType |
| Createdon | Createdon |
| ModifiedOn | ModifiedOn |
| Id | Id |

# [Dave_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | Name |
| Message | Message |
| CreatedOn | CreatedOn |
| ID | ID |

# [DDL_LOG] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| PostTime | PostTime |
| DatabaseName | DatabaseName |
| DB_User | DB_User |
| Event | Event |
| LoginName | LoginName |
| TSQL | TSQL |
| LastChange_Azure | LastChange_Azure |
| ComputerName | ComputerName |
| ID | ID |

# [DTC_EDMS_Store] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| OutletName | OutletName |
| 新大区 | 新大区 |
| 团队 | 团队 |
| 省份 | 省份 |
| 城市 | 城市 |
| HCI名称 | HCI名称 |
| 备注 | 备注 |
| 是否DMS建店 | 是否DMS建店 |
| OutletCode | OutletCode |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| OutletName | OutletName |

# [DTC_YOUZAN_Buyer_Info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| yz_open_id | yz_open_id |
| outer_user_id | outer_user_id |
| buyer_phone | buyer_phone |
| fans_type | fans_type |
| fans_nickname | fans_nickname |
| fans_id | fans_id |
| s_mobile | s_mobile |
| CreatedOn | CreatedOn |
| yz_open_id | yz_open_id |

# [DTC_YOUZAN_Orders] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| oid | oid |
| tid | tid |
| outer_item_id | outer_item_id |
| item_type | item_type |
| discount_price | discount_price |
| num | num |
| goods_snapshot | goods_snapshot |
| title | title |
| fenxiao_payment | fenxiao_payment |
| item_id | item_id |
| item_no | item_no |
| is_present | is_present |
| price | price |
| sub_order_no | sub_order_no |
| total_fee | total_fee |
| fenxiao_price | fenxiao_price |
| alias | alias |
| payment | payment |
| item_barcode | item_barcode |
| outer_sku_id | outer_sku_id |
| goods_url | goods_url |
| points_price | points_price |
| sku_barcode | sku_barcode |
| sku_no | sku_no |
| sku_properties_name | sku_properties_name |
| s_mobile | s_mobile |
| newcustomer_type | newcustomer_type |
| is_newcustomer | is_newcustomer |
| dcps | dcps |
| kdt_id | kdt_id |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| oid | oid |

# [DTC_YOUZAN_Orders_Info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| tid | tid |
| created | created |
| expired_time | expired_time |
| status_str | status_str |
| success_time | success_time |
| type | type |
| kdt_id | kdt_id |
| kdt_name | kdt_name |
| confirm_time | confirm_time |
| pay_time | pay_time |
| update_time | update_time |
| is_retail_order | is_retail_order |
| pay_type | pay_type |
| team_type | team_type |
| refund_state | refund_state |
| close_type | close_type |
| status | status |
| express_type | express_type |
| buyer_phone | buyer_phone |
| yz_open_id | yz_open_id |
| fans_id | fans_id |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| tid | tid |

# [DTC_YOUZAN_pay_info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |

# [DTC_YOUZAN_Push_Order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| oid | oid |
| tid | tid |
| mobile | mobile |
| s_mobile | s_mobile |
| product_name | product_name |
| newcustomer_type | newcustomer_type |
| isnewcustomer | isnewcustomer |
| store_number | store_number |
| ps_name | ps_name |
| dcps | dcps |
| nestle_product_code | nestle_product_code |
| item_id | item_id |
| item_no | item_no |
| kdt_id | kdt_id |
| kdt_name | kdt_name |
| create_time | create_time |
| created_on | created_on |
| modified_on | modified_on |
| oid | oid |

# [DTC_YOUZAN_PushMSG_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pid | pid |
| payload | payload |
| msg | msg |
| kdt_name | kdt_name |
| test | test |
| sign | sign |
| type | type |
| sendCount | sendCount |
| version | version |
| client_id | client_id |
| mode | mode |
| kdt_id | kdt_id |
| id | id |
| msg_id | msg_id |
| root_kdt_id | root_kdt_id |
| status | status |
| createdon | createdon |
| pid | pid |

# [DTC_YOUZAN_Store] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| 店铺名称 | 店铺名称 |
| 店铺编号 | 店铺编号 |
| 店铺有效期 | 店铺有效期 |
| 店铺状态 | 店铺状态 |
| 授权状态 | 授权状态 |
| CreatedOn | CreatedOn |
| Id | Id |

# [EC_JD_Brand_Upload] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| offline_user_id | offline_user_id |
| customer_id | customer_id |
| brand_encode_phone | brand_encode_phone |
| level | level |
| bind_time | bind_time |
| is_mapping | is_mapping |
| created | created |
| modified | modified |
| id | id |

# [EC_JD_ID_Mapping] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| S_Mobile | S_Mobile |
| JD_Mobile | JD_Mobile |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Sent2JDOn | Sent2JDOn |
| TM_MegaNAN_Mobile | TM_MegaNAN_Mobile |
| S_Mobile | S_Mobile |

# [EC_JD_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| activityId | activityId |
| venderId | venderId |
| pin | pin |
| channel | channel |
| josEncPin | josEncPin |
| phoneNo | phoneNo |
| babyBirthday | babyBirthday |
| sex | sex |
| nickname | nickname |
| factor1 | factor1 |
| factor2 | factor2 |
| initialLevel | initialLevel |
| initialJdLevel | initialJdLevel |
| level | level |
| levelUpdateTime | levelUpdateTime |
| point | point |
| pointUpdateTime | pointUpdateTime |
| result | result |
| message | message |
| extend | extend |
| createTime | createTime |
| updateTime | updateTime |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| SendToJDOn | SendToJDOn |
| id | id |

# [EC_JD_MemberUpdate] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| phoneNo | phoneNo |
| mappingResult | mappingResult |
| level | level |
| cardStatus | cardStatus |
| ext | ext |
| xid | xid |
| jdpin | jdpin |
| time | time |
| isFirstMapping | isFirstMapping |
| v_child_birthday | v_child_birthday |
| v_child_nickname | v_child_nickname |
| v_child_sex | v_child_sex |
| createdOn | createdOn |
| modifiedOn | modifiedOn |
| phoneNo | phoneNo |

# [EC_JD_Mot] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uid | uid |
| externalUserid | externalUserid |
| target | target |
| executor | executor |
| sendTime | sendTime |
| mot_def_no | mot_def_no |
| status | status |
| msg | msg |
| contactTime | contactTime |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| id | id |

# [EC_JD_MotDetail] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| remark | remark |
| materialType | materialType |
| text | text |
| linkTitle | linkTitle |
| linkImage | linkImage |
| linkUrl | linkUrl |
| linkDesc | linkDesc |
| imageFile | imageFile |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| id | id |
| materialType | materialType |

# [EC_JD_MotDetail_WDY] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| remark | remark |
| contentType | contentType |
| Brand | Brand |
| Days | Days |
| Is_Gaoqian | Is_Gaoqian |
| content | content |
| url | url |
| fileName | fileName |
| previewImgUrl | previewImgUrl |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [EC_JD_Order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| ordStatus | ordStatus |
| shopId | shopId |
| goodsQtty | goodsQtty |
| skuId | skuId |
| parentOrdId | parentOrdId |
| ordStartDate | ordStartDate |
| ordEndDate | ordEndDate |
| sonOrdId | sonOrdId |
| ordAmt | ordAmt |
| goodName | goodName |
| userLogAcct | userLogAcct |
| createTime | createTime |
| updateTime | updateTime |
| newShopFlg | newShopFlg |
| newFlg | newFlg |
| firstTradeDate | firstTradeDate |
| openCardDate | openCardDate |
| level | level |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| id | id |

# [EC_JD_Pinyou_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| KSFID | KSFID |
| Joindate | Joindate |
| S_Mobile | S_Mobile |
| JD_Mobile | JD_Mobile |
| IsNewCustomer | IsNewCustomer |
| NewCustomerType | NewCustomerType |
| Consumer_Validation_Date | Consumer_Validation_Date |
| CreatedOn | CreatedOn |
| SentToPinYouOn | SentToPinYouOn |
| KSFID | KSFID |

# [EC_JD_PointIncs] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| customerId | customerId |
| pin | pin |
| phoneNo | phoneNo |
| pointInc | pointInc |
| type | type |
| recordId | recordId |
| content | content |
| ext | ext |
| xid | xid |
| createdOn | createdOn |
| id | id |

# [EC_JD_Products_Info] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| skuId | skuId |
| ProductCode | ProductCode |
| ProductName | ProductName |
| skuId | skuId |

# [EC_JD_QW_BindInfo] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| externalUserId | externalUserId |
| executor | executor |
| openId | openId |
| addDate | addDate |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [EC_JD_SCRM_IntentionTag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| avatar | avatar |
| external_user_id | external_user_id |
| name | name |
| user_id | user_id |
| assign_user_name | assign_user_name |
| tag_create_time | tag_create_time |
| tag_id | tag_id |
| tag_name | tag_name |
| tag_group_name | tag_group_name |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| id | id |

# [EC_JD_WDY_CustomerContact] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| contacts_record_id | contacts_record_id |
| name | name |
| contact_remark | contact_remark |
| contact_headimgurl | contact_headimgurl |
| contacts_type | contacts_type |
| corp_name | corp_name |
| gender | gender |
| personal_record_id | personal_record_id |
| personal_name | personal_name |
| assign_user_name | assign_user_name |
| group_name | group_name |
| client_status | client_status |
| work_status | work_status |
| customer_add_time | customer_add_time |
| user_id | user_id |
| personal_remote_id | personal_remote_id |
| remote_id | remote_id |
| external_userid | external_userid |
| Tag | Tag |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [EC_JD_WDY_MOTSend] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| userId | userId |
| enterpriseId | enterpriseId |
| corpId | corpId |
| targetType | targetType |
| targetId | targetId |
| remoteId | remoteId |
| personalId | personalId |
| personalRemoteId | personalRemoteId |
| contentType | contentType |
| content | content |
| url | url |
| fileName | fileName |
| previewImgUrl | previewImgUrl |
| msgSource | msgSource |
| sendTime | sendTime |
| mot_def_no | mot_def_no |
| status | status |
| msg | msg |
| contactTime | contactTime |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [EC_JD_WDY_SysTag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| tagGroupId | tagGroupId |
| tagGroupName | tagGroupName |
| tagGroupCreateTime | tagGroupCreateTime |
| tagGroupOrderNo | tagGroupOrderNo |
| tagId | tagId |
| tagName | tagName |
| createTime | createTime |
| updateTime | updateTime |
| orderNo | orderNo |

# [EC_JD_WDY_Tag] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| RunDate | RunDate |
| RunDays | RunDays |
| LastBuyDate | LastBuyDate |
| LastUseDays | LastUseDays |
| KongDate | KongDate |
| LastsonOrdId | LastsonOrdId |
| Is_Shougou | Is_Shougou |
| Tag | Tag |
| Brand | Brand |
| Category | Category |
| Is_Gaoqian | Is_Gaoqian |
| externalUserId | externalUserId |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |

# [EC_NewCustomerType_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| S_Mobile | S_Mobile |
| NewCustomerType | NewCustomerType |
| TouchPoint | TouchPoint |
| BuyTime | BuyTime |
| Payload | Payload |
| Result | Result |
| CreatedOn | CreatedOn |
| ID | ID |

# [ec_taobao_grade] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| planId | planId |
| gradeHierarchyId | gradeHierarchyId |
| memberId | memberId |
| currentGradeDefinitionId | currentGradeDefinitionId |
| effectDate | effectDate |
| overdueDate | overdueDate |
| created | created |
| planName | planName |
| gradeHierarchyName | gradeHierarchyName |
| currentGradeName | currentGradeName |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_graderecord] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| planId | planId |
| planName | planName |
| memberGradeId | memberGradeId |
| gradeHierarchyId | gradeHierarchyId |
| gradeHierarchyName | gradeHierarchyName |
| memberId | memberId |
| originalGradeId | originalGradeId |
| originalGradeName | originalGradeName |
| originalEffectDate | originalEffectDate |
| originalOverdueDate | originalOverdueDate |
| currentGradeId | currentGradeId |
| currentGradeName | currentGradeName |
| currentEffectDate | currentEffectDate |
| currentOverdueDate | currentOverdueDate |
| recordType | recordType |
| changeWay | changeWay |
| triggerId | triggerId |
| traceId | traceId |
| recordSourceDetail | recordSourceDetail |
| operator | operator |
| description | description |
| extraInfo | extraInfo |
| created | created |
| channel | channel |
| eventTypeName | eventTypeName |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_history_member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| shopId | shopId |
| snapshotInfo | snapshotInfo |
| gradeName | gradeName |
| grade | grade |
| buyerNick | buyerNick |
| gmtModified | gmtModified |
| points | points |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | memberId |
| memberName | memberName |
| unionId | unionId |
| headImgUrl | headImgUrl |
| wechatNick | wechatNick |
| gender | gender |
| mobile | mobile |
| phone | phone |
| cardNo | cardNo |
| email | email |
| identityCard | identityCard |
| dateOfBirth | dateOfBirth |
| country | country |
| provinceCode | provinceCode |
| provinceName | provinceName |
| cityCode | cityCode |
| cityName | cityName |
| districtCode | districtCode |
| districtName | districtName |
| address | address |
| job | job |
| shopCode | shopCode |
| shopName | shopName |
| shopTypeCode | shopTypeCode |
| registerTime | registerTime |
| createTime | createTime |
| updateTime | updateTime |
| firstRegisterChannelType | firstRegisterChannelType |
| contactTel | contactTel |
| babyBirthday | babyBirthday |
| unBindTime | unBindTime |
| last_sync_new | last_sync_new |
| buyerNick | buyerNick |
| ouid | ouid |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| memberId | memberId |

# [ec_taobao_order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| memberId | memberId |
| tid | tid |
| shopId | shopId |
| adjustFee | adjustFee |
| alipayNo | alipayNo |
| buyerAlipayNo | buyerAlipayNo |
| buyerCodFee | buyerCodFee |
| buyerEmail | buyerEmail |
| buyerMessage | buyerMessage |
| buyerNick | buyerNick |
| buyerObtainPointFee | buyerObtainPointFee |
| buyerRate | buyerRate |
| codFee | codFee |
| codStatus | codStatus |
| commissionFee | commissionFee |
| consignTime | consignTime |
| created | created |
| discountFee | discountFee |
| endTime | endTime |
| expressAgencyFee | expressAgencyFee |
| lastSync | lastSync |
| modified | modified |
| num | num |
| payment | payment |
| payTime | payTime |
| pointFee | pointFee |
| postFee | postFee |
| realPointFee | realPointFee |
| receivedPayment | receivedPayment |
| receiverAddress | receiverAddress |
| receiverCity | receiverCity |
| receiverDistrict | receiverDistrict |
| receiverMobile | receiverMobile |
| receiverName | receiverName |
| receiverPhone | receiverPhone |
| receiverState | receiverState |
| receiverZip | receiverZip |
| refundFee | refundFee |
| sellerCodFee | sellerCodFee |
| sellerFlag | sellerFlag |
| sellerMemo | sellerMemo |
| sellerNick | sellerNick |
| sellerRate | sellerRate |
| shippingType | shippingType |
| status | status |
| stepTradeStatus | stepTradeStatus |
| totalFee | totalFee |
| tradeFrom | tradeFrom |
| type | type |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_orderitem] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| tid | tid |
| memberId | memberId |
| cid | cid |
| numIid | numIid |
| oid | oid |
| outerIid | outerIid |
| refundId | refundId |
| shopId | shopId |
| skuId | skuId |
| adjustFee | adjustFee |
| buyerNick | buyerNick |
| buyerRate | buyerRate |
| consignTime | consignTime |
| created | created |
| discountFee | discountFee |
| divideOrderFee | divideOrderFee |
| endTime | endTime |
| invoiceNo | invoiceNo |
| isOversold | isOversold |
| itemMealId | itemMealId |
| itemMealName | itemMealName |
| lastSync | lastSync |
| logisticsCompany | logisticsCompany |
| modified | modified |
| num | num |
| partMjzDiscount | partMjzDiscount |
| payment | payment |
| payTime | payTime |
| picPath | picPath |
| price | price |
| refundFee | refundFee |
| refundStatus | refundStatus |
| sellerNick | sellerNick |
| sellerRate | sellerRate |
| skuPropertiesName | skuPropertiesName |
| status | status |
| stepTradeStatus | stepTradeStatus |
| title | title |
| totalFee | totalFee |
| tradeFrom | tradeFrom |
| type | type |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_point] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| planId | planId |
| pointPlanId | pointPlanId |
| memberId | memberId |
| point | point |
| modified | modified |
| created | created |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_pointrecord] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| planId | planId |
| pointPlanId | pointPlanId |
| memberPointId | memberPointId |
| memberId | memberId |
| point | point |
| totalPoint | totalPoint |
| recordType | recordType |
| recordSourceDetail | recordSourceDetail |
| effectiveDate | effectiveDate |
| overdueDate | overdueDate |
| extralInfo | extralInfo |
| recordDetail | recordDetail |
| desc | desc |
| fromStatus | fromStatus |
| operator | operator |
| operatorId | operatorId |
| modified | modified |
| created | created |
| channel | channel |
| key | key |
| ruleGroup | ruleGroup |
| ruleName | ruleName |
| ruleId | ruleId |
| changeMode | changeMode |
| planName | planName |
| pointPlanName | pointPlanName |
| traceId | traceId |
| eventTypeName | eventTypeName |
| actionName | actionName |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [ec_taobao_product] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| approveStatus | approveStatus |
| cid | cid |
| created | created |
| delistTime | delistTime |
| detailUrl | detailUrl |
| inputPids | inputPids |
| inputStr | inputStr |
| isFenxiao | isFenxiao |
| lastSync | lastSync |
| listTime | listTime |
| modified | modified |
| numIid | numIid |
| outerId | outerId |
| picUrl | picUrl |
| price | price |
| props | props |
| propsName | propsName |
| sellerCids | sellerCids |
| shopId | shopId |
| title | title |
| last_sync_new | last_sync_new |
| productCode | productCode |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| Comments | Comments |
| id | id |

# [ec_taobao_product_info2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| 商品货号 | 商品货号 |
| 商品货号V2 | 商品货号V2 |
| ProductName | ProductName |
| Qty | Qty |
| Brand | Brand |
| Stage | Stage |
| Netweight | Netweight |
| 一口价 | 一口价 |
| NPS单价 | NPS单价 |
| NPS价 | NPS价 |
| QIP价 | QIP价 |
| 备注 | 备注 |
| LastChange | LastChange |

# [ec_taobao_Products_Info_20231121_Sanyar] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 天猫店铺名称 | 天猫店铺名称 |
| 类目 | 类目 |
| 商品ID | 商品ID |
| 商品标题 | 商品标题 |
| 商家编码 | 商家编码 |
| CODE码 | CODE码 |
| F7 | F7 |
| F8 | F8 |

# [ec_taobao_Products_Info_20231121_Sanyar_2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| 天猫店铺名称 | 天猫店铺名称 |
| 类目 | 类目 |
| 商品ID | 商品ID |
| 商品标题 | 商品标题 |
| 商家编码 | 商家编码 |
| CODE码 | CODE码 |

# [EC_taobao_Products_Info_Gerber] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Title | Title |
| ProductCode | ProductCode |
| 数量 | 数量 |
| NPS_Price | NPS_Price |
| Comments | Comments |
| ID | ID |

# [ec_taobao_productskus] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| created | created |
| lastSync | lastSync |
| numIid | numIid |
| outerId | outerId |
| price | price |
| properties | properties |
| propertiesName | propertiesName |
| quantity | quantity |
| shopId | shopId |
| skuId | skuId |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| id | id |

# [ec_taobao_refund] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| tid | tid |
| memberId | memberId |
| numIid | numIid |
| refundId | refundId |
| sid | sid |
| shopId | shopId |
| oid | oid |
| buyerNick | buyerNick |
| companyName | companyName |
| created | created |
| csStatus | csStatus |
| exitsTimeout | exitsTimeout |
| goodReturnTime | goodReturnTime |
| hasGoodReturn | hasGoodReturn |
| lastSync | lastSync |
| modified | modified |
| num | num |
| orderStatus | orderStatus |
| payment | payment |
| price | price |
| reason | reason |
| refundDesc | refundDesc |
| refundFee | refundFee |
| remindType | remindType |
| sellerNick | sellerNick |
| status | status |
| timeout | timeout |
| title | title |
| totalFee | totalFee |
| last_sync_new | last_sync_new |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| id | id |

# [EC_Tmall_DW_MegaNan_Member] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | memberId |
| memberName | memberName |
| gender | gender |
| mobile | mobile |
| shopCode | shopCode |
| shopName | shopName |
| shopTypeCode | shopTypeCode |
| registerTime | registerTime |
| createTime | createTime |
| CreatedOn | CreatedOn |
| mixMobile | mixMobile |

# [EC_Tmall_DW_MegaNan_Order] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| memberId | memberId |
| mobile | mobile |
| oid | oid |
| tid | tid |
| numIid | numIid |
| price | price |
| num | num |
| totalFee | totalFee |
| payment | payment |
| refundFee | refundFee |
| created | created |
| payTime | payTime |
| consignTime | consignTime |
| endTime | endTime |
| title | title |
| Brand | Brand |
| Stage | Stage |
| CreatedOn | CreatedOn |

# [EC_Tmall_DW_MegaNan_Product] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| approveStatus | approveStatus |
| cid | cid |
| created | created |
| delistTime | delistTime |
| detailUrl | detailUrl |
| inputPids | inputPids |
| inputStr | inputStr |
| isFenxiao | isFenxiao |
| lastSync | lastSync |
| listTime | listTime |
| modified | modified |
| numIid | numIid |
| outerId | outerId |
| picUrl | picUrl |
| price | price |
| props | props |
| propsName | propsName |
| sellerCids | sellerCids |
| shopId | shopId |
| title | title |
| productCode | productCode |
| CreatedOn | CreatedOn |
| rn | rn |
| Brand | Brand |
| Stage | Stage |

# [ec_雀巢母婴ID_20211221] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ProductCode | ProductCode |
| ProductCode_Nestle | ProductCode_Nestle |
| ProductName | ProductName |
| Qty | Qty |
| Brand | Brand |
| Stage | Stage |

# [Error_Log] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| ID | ID |
| Name | Name |
| Message | Message |
| CreatedOn | CreatedOn |
| ID | ID |

# [ErrorHandling] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| pkErrorHandlingID | pkErrorHandlingID |
| Error_Number | Error_Number |
| Error_Message | Error_Message |
| Error_Severity | Error_Severity |
| Error_State | Error_State |
| Error_Procedure | Error_Procedure |
| Error_Line | Error_Line |
| UserName | UserName |
| HostName | HostName |
| Time_Stamp | Time_Stamp |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| pkErrorHandlingID | pkErrorHandlingID |

# [EWechat_CorpId] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| Name | Name |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |

# [EWechat_SNC_External] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Id | Id |
| Unionid | Unionid |
| Openid | Openid |
| SNCUserId | SNCUserId |
| ToUserName | ToUserName |
| FromUserName | FromUserName |
| SNCCode | SNCCode |
| ChangeType | ChangeType |
| TimeStamp | TimeStamp |
| State | State |
| MsgType | MsgType |
| Event | Event |
| CreatedOn | CreatedOn |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| ExternalUserID | ExternalUserID |
| Id | Id |

# [EWechat_User] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| ExternalUserID | ExternalUserID |
| WeChatName | WeChatName |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| Avatar | Avatar |
| Unionid | Unionid |

# [FAQ] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| InfoType | InfoType |
| Question | Question |
| Ans | Ans |
| ParentId | ParentId |
| OrderID | OrderID |
| AttName | AttName |
| AttPath | AttPath |
| QueryAns | QueryAns |
| OperationFlag | OperationFlag |
| txUser | txUser |
| txDate | txDate |
| ID | ID |
| LastChange | LastChange |
| LastChange_Azure | LastChange_Azure |
| txDate_20230214 | txDate_20230214 |
| txDate_20230215 | txDate_20230215 |
| ID | ID |

# [fugou_shanmu] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| Brand | Brand |
| Stage | Stage |
| ka_name | ka_name |
| BuyTime | BuyTime |
| rn2 | rn2 |

# [HA_Sanyar] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| Unionid | Unionid |
| BuyTime | BuyTime |
| BuyTime_Day | BuyTime_Day |
| StoreCode | StoreCode |
| OrderNum | OrderNum |
| ID_CRMPlus | ID_CRMPlus |
| 订单罐数 | 订单罐数 |
| ProductCode | ProductCode |
| KSFId | KSFId |
| 招募订单中子订单顺序 | 招募订单中子订单顺序 |
| 招募时间 | 招募时间 |
| 招募时门店 | 招募时门店 |
| 招募复购订单属性 | 招募复购订单属性 |
| 下单天数 | 下单天数 |
| 下单数 | 下单数 |
| 复购订单属性 | 复购订单属性 |
| 是否院线店 | 是否院线店 |
| Price | Price |

# [ims_customer] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| cus_id | cus_id |
| cus_number | cus_number |
| cus_name | cus_name |
| p_cus_name | p_cus_name |
| p_cus_number | p_cus_number |
| mobile | mobile |
| realname | realname |
| area_name | area_name |
| city_group | city_group |
| province | province |
| city | city |
| city_level | city_level |
| address | address |
| is_active | is_active |
| license | license |
| cdate | cdate |
| updatetime | updatetime |
| cus_id | cus_id |

# [ims_customer_rel] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| cus_id | cus_id |
| cus_uid | cus_uid |
| is_zhu | is_zhu |
| is_onjob | is_onjob |
| cdate | cdate |
| updatetime | updatetime |
| id | id |

# [ims_edms_stores_dtc] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| store_number | store_number |
| store_name | store_name |
| area_name | area_name |
| province | province |
| city | city |
| city_group | city_group |
| cityLevel | cityLevel |
| ISOAH | ISOAH |
| ka_type | ka_type |
| ka_name | ka_name |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| store_number | store_number |

# [ims_gerber_coupon] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| title | title |
| cardno | cardno |
| gift_code | gift_code |
| openid | openid |
| unionid | unionid |
| mobile | mobile |
| money | money |
| exp_time | exp_time |
| use_time | use_time |
| is_used | is_used |
| orderno | orderno |
| snc_code | snc_code |
| store_number | store_number |
| get_time | get_time |
| updatetime | updatetime |
| CreatedOn | CreatedOn |
| ModifiedOn | ModifiedOn |
| get_storeno | get_storeno |
| get_snc | get_snc |
| id | id |

# [ims_gerber_coupon2] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| title | title |
| cardno | cardno |
| gift_code | gift_code |
| openid | openid |
| unionid | unionid |
| mobile | mobile |
| money | money |
| exp_time | exp_time |
| use_time | use_time |
| is_used | is_used |
| orderno | orderno |
| snc_code | snc_code |
| store_number | store_number |
| get_time | get_time |
| updatetime | updatetime |
| post_time | post_time |
| post_status | post_status |
| post_res | post_res |

# [ims_nestle_al110_popup] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| unionid | unionid |
| cdate | cdate |
| CreatedOn | CreatedOn |
| unionid | unionid |

# [ims_nestle_business_stores_product_3] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| uniacid | uniacid |
| sid | sid |
| productcode | productcode |
| tankcode | tankcode |
| status | status |
| productcontent | productcontent |
| serial_number | serial_number |
| creattime | creattime |
| updatetime | updatetime |
| id | id |

# [ims_nestle_business_xh_book_goods_detail] 字段注释说明
本表记录了...的详细信息。下表对各字段含义进行简要说明，方便业务理解与数据分析。
| 字段名 | 注释说明 |
|---|---|
| id | id |
| book_id | book_id |
| sid | sid |
| is_crm | is_crm |
| cus_number | cus_number |
| cus_uid | cus_uid |
| tcds_code | tcds_code |
| cus_uid_gx | cus_uid_gx |
| productcode | productcode |
| tankcode | tankcode |
| status | status |
| is_allot | is_allot |
| receive_serial_number | receive_serial_number |
| receive_tcds_code | receive_tcds_code |
| receive_cus_uid_gx | receive_cus_uid_gx |
| receive_date | receive_date |
| receive_type | receive_type |
| cdate | cdate |
| updatetime | updatetime |
| Comments | Comments |
| id | id |

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
