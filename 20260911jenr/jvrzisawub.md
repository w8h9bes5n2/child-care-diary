# 【妇产学术】阴赪宏教授团队在JCR Q1区期刊发表两篇AI研究文章

> 更新时间：2026-09-11 (UTC+8)

近日，首都医科大学附属北京妇产医院阴赪宏教授团队在国际知名期刊《Journal of Medical Internet Research》（JCR Q1区）连续发表两篇原创性研究论文：《Enhancing the Accuracy of Human Phenotype Ontology Identification: Comparative Evaluation of Multimodal Large Language Models》、《Performance of ChatGPT-4o and Four Open-Source Large Language Models in Generating Diagnoses Based on China's Rare Disease Catalog: Comparative Study》。这两项研究聚焦医学人工智能、大语言模型前沿领域，为提升罕见病诊疗水平和人类表型识别提供了创新性解决方案。

研究不仅为医学大语言模型在临床实践中的应用提供了重要的理论依据和技术支撑，更为医院本地化部署大语言模型构建了科学、可行的实施框架。研究成果的连续发表，标志着北京妇产医院在大语言模型的临床应用与研究领域迈出了坚实的第一步。

首都医科大学附属北京妇产医院阴赪宏教授、产前诊断中心闫有圣副教授为上述论文共同通讯作者，我院2024级博士研究生钟威为第一作者。

随着大语言模型“ChatGPT”和“DeepSeek”的出现和爆火，新一代人工智能正以前所未有的力量重塑人类的生产力格局。然而，在医学领域，尤其是罕见病诊疗方面，大语言模型的应用潜力尚未得到充分挖掘。究其原因，尽管大语言模型拥有海量的医学知识储备，但如何将其有效转化为临床实践中罕见病诊疗的助力，仍是一个亟待探索的课题。基于此，阴赪宏教授团队率先行动，运用大语言模型从多个维度对罕见病的临床关键问题展开深入研究，致力于开拓这一领域的全新应用前景。

**1.多模态大语言模型助力人类表型术语识别，提升罕见病诊断准确性**

罕见病的诊断离不开对人类表型术语（HPO）的精准识别，但临床医生尤其是年轻医生，常因患者表型描述的复杂性而陷入困境，传统的手动检索 HPO 数据库方法不仅耗时，还容易出错。为攻克这一难题，阴赪宏教授团队开展了创新性研究。

研究邀请了来自 10 个不同专业的 20 名年轻医生参与，他们需对 27 张与罕见病相关的患者图像进行评估。研究分为两组：一组依靠HPO数据库手动检索，另一组则使用由 ChatGPT - 4o 对图像预先识别的 HPO 术语作为提示，并结合数据库搜索。此外，研究还对 ChatGPT - 4o 和两种开源的多模态大语言模型（Llama3.2:11b 和 Llama3.2:90b）的输出准确性进行了评估，并分别记录了每种模型的幻觉现象。

结果显示，多模态大语言模型辅助的临床医生准确率显著高于手动检索组，分别为 67.4%（182/270）和 20.4%（55/270），P<0.001。并且实验组在同科室的表现较为一致，而对照组波动较大。研究还对多模态大语言模型的输出结果进行了幻觉分析，证实其可能存在的安全隐患。此外，对年轻医生的罕见病知识背景调查表明，参加罕见病和遗传病培训可能会提升部分医生的识别表现。

因此，将多模态大语言模型整合到临床工作流程中，能显著提高年轻医生识别 HPO 术语的准确性，为罕见病的诊断和医学研究中表型描述的标准化带来了巨大潜力。然而，其显著的幻觉率也凸显了在临床实践中广泛应用之前，需要进一步完善和严格验证的必要性。

**2.****大语言模型在中国罕见病目录中的诊断表现及优化策略研究**

罕见病的诊断因其复杂性及医生知识局限性而充满挑战，大语言模型为改善这一状况带来了新的希望。本研究旨在评估 ChatGPT - 4o 和四种开源 LLMs（qwen2.5:7b、Llama3.1:8b、qwen2.5:72b、Llama3.1:70b）对罕见病的诊断准确性，分析不同语言（中英文）对诊断性能的影响，并探索检索增强生成（RAG）和链式推理（CoT）在开源模型中的应用效果。

研究根据中国第一批病目录从中国罕见病注册系统数据库提取了 121 种罕见病的临床表现作为诊断病例。首先使用ChatGPT - 4o 生成主要诊断和五种鉴别诊断，而四种 LLMs 则在中英文两种语言下接受评估。诊断率最低的模型接受了 检索增强生成技术（RAG） 和 思维链推理（CoT ）的重新评估（研究共进行了1331次诊断比较试验）。通过 McNemar 检验比较诊断准确性，并对 11 名临床医生进行了罕见病熟悉程度的调查。

研究表明，ChatGPT - 4o 在罕见病诊断方面表现卓越，诊断准确率最高，达到 90.1%。不同模型在不同语言下的表现各异。虽然小参数模型Llama3.1:8b 在资源受限的英文诊断流程中具有一定的应用潜力，但在中文应用场景中需要更大规模的模型才能达到相当的诊断准确率。随着像 DeepSeek - R1 这样的开源模型的快速推出，可能会在未经充分验证的情况下被广泛采用，这进一步凸显了在医疗场景科学合理部署开源模型的紧迫性。研究证明，成功将开源模型有效应用于临床需要考虑三个核心要素：模型参数、用户语言和预训练数据。RAG 的整合显著提升了开源模型在罕见病诊断中的准确性，但对于低参数推理模型的应用仍需保持谨慎。

**作者简介**

**通讯作者 阴赪宏**

教授，主任医师，研究员，博士生导师，首都医科大学附属北京妇产医院 北京妇幼保健院党委副书记、院长，享受国务院政府特殊津贴专家。长期致力于妇产科、内科临床与基础研究工作，解决了一系列临床关键技术问题。主持“十一五”科技支撑重点项目、“十三五”国家重点研发计划项目、“十四五”国家重点研发计划项 目、国家自然科学基金等 36 项课题;发表论文近 600 篇，其中 SCI 论文 240 篇;主编、副主编医学专著 35 部。多次担任国际、国内学术会议主席、执行主席。授权专利 11 项。获北京市科学技术进步奖二等奖、中华医学科技进步奖二等奖等 10 余次。入选北京学者、国家卫生计生突出贡献中青年专家、北京先进工作者、北京市战略科技人才等荣誉称号。

**通讯作者****闫有圣**

遗传学博士，主任医师， 副教授， 硕士研究生导师。从事临床遗传病基因诊断、遗传咨询和产前诊断工作20年。兼任中国医院协会妇产医院分会常委/产前诊断学组副组长、中国中西医结合学会检验专委会出生缺陷委员会副主任委员、中国优生科学协会出生缺陷预防专业委员会、中国优生优育协会胎儿医学专业委员会、中国医疗保健国际交流促进会妇产健康医学委员会、中国医药教育协会健康管理专业委员会委员等。主持省部级2项，作为课题骨干参与“十三五重大研发计划”2项，“十四五重点研发计划”2项，参与完成省部级科研项目6项。以第一或者通讯作者在Molecular psychiatry、Analytical chemistry、Human mutation等高水平期刊发表SCI论文10余篇，出版专著2部。

**第一作者 ****钟威**

首都医科大学2024级学术型博士研究生。主要研究领域为人工智能在出生缺陷中的应用、生殖医学等。在《Human Reproduction》等权威期刊上以第一作者身份发表SCI论文6篇，参与发表SCI论文 4篇、《中华生殖与避孕杂志》1篇、核心期刊3篇。参编著作《线粒体遗传病诊疗》。作为学生骨干参与“十三五”、“十四五”国家重点研发计划、国家自然科学基金等课题的申报与实施工作。

编辑：宣传中心    

北京妇产医院

微信订阅号｜微信服务号

## 相关阅读

- [单次试管婴儿的危害成本很高，这些技巧可以帮助你轻松省钱](https://github.com/s4be62o8zt/pregnancy-care-hub/blob/main/20260910wzib/bkgqhqgesr.md)
- [山西助孕公司-山西助孕试管助孕机构](https://github.com/h3qlethz3l/mommy-baby-notes/blob/main/20260910qswt/mwcznizsvu.md)
- [孕早期褐色分泌物持续多长时间](https://github.com/l9lvqnbe4d/child-care-diary/blob/main/20260911sbmp/sfetcdwmiw.md)
- [罗氏易位济南做试管多少钱，这份费用明细可供参考](https://github.com/jg9otl86or/parenting-daily-tips/blob/main/20260910ebzm/jzmpgdkrbo.md)
- [先天性双角子宫能正常生育小孩吗？](https://github.com/bjpnmb0r46/mother-baby-diary/blob/main/20260911yayn/vrsffpplbw.md)
- [中山三代试管婴儿生孩子的价格费用多少钱？](https://github.com/t5ok6hw1uj/baby-sleep-tips/blob/main/20260911jzhd/ztvocqetfx.md)
- [洛阳有卵子库吗共2家公立医院开通无卵通道](https://github.com/rzchuf6kdk/newborn-parenting-log/blob/main/20260911pnla/qaxgeswvpd.md)
- [试管促排卵前降调的意义与价值](https://github.com/y9qvvxks1i/pregnancy-care-hub/blob/main/20260910alcw/rnoosbjzfz.md)
- [多囊促排卵怀孕率高吗掌握这三点，想不怀孕都难](https://github.com/nih9jzz6yi/child-care-essays/blob/main/20260910fugf/pvadloyfnv.md)
- [山大生殖高珊珊怎么样「山大生殖高珊珊试管移植成功率」](https://github.com/wgeyt0fbiv/baby-growth-journal/blob/main/20260911krtw/vkpxzumrke.md)
- [做试管打达必佳降调多久开始促排？](https://github.com/zntce2ojnh/baby-care-journal/blob/main/20260910inuu/ulxaoftopp.md)
- [天津市中心妇产科医院无精三代试管婴儿能做吗：条件参考](https://github.com/fbw1fx15bs/family-health-notes/blob/main/20260910ifpj/nkuzpcqdqk.md)

## 推荐站点

- [['https://www.afa2019.com/119895356232.html', '原来领过结婚证，还可以去做免费的孕前检查,供卵助孕公司地址']](https://www.afa2019.com/119895356232.html)
- [['https://www.vhpowpj.cn/20250821-124.html', 'DHEA：改善卵巢功能的“青春素”，试管助孕新选择']](https://www.vhpowpj.cn/20250821-124.html)
- [['https://www.dzjiurunxcl.cn/19337391330310.html', '山东试管助孕生宝宝费用明细清单全解析']](https://www.dzjiurunxcl.cn/19337391330310.html)
- [['https://www.bkudgf.cn/171.html', '试管移植也会宫外孕？揭秘导致宫外孕的5大元凶及预防方法']](https://www.bkudgf.cn/171.html)
- [['https://www.cheguangfu.cn/220.html', '试管婴儿全流程花费：拒绝中间商，公开透明助孕费用']](https://www.cheguangfu.cn/220.html)
- [['https://www.rongyixueyuan.com/123.html', '试管供卵包儿子,广州三代试管婴儿移植后出现出血怎么办？可以报销吗？']](https://www.rongyixueyuan.com/123.html)
- [['https://www.zrbbavaq.cn/30208445654717.html', '代生男宝宝成功率是如何计算的？']](https://www.zrbbavaq.cn/30208445654717.html)
- [['https://www.sandwnot.com/223912484417.html', '沈阳三代试管婴儿费用全面解析']](https://www.sandwnot.com/223912484417.html)
- [['https://www.hg00fj88.com/2347.html', '供卵价格高-三代试管包生男孩价格明细']](https://www.hg00fj88.com/2347.html)
- [['https://www.qumengru.com/302442912407.html', '试管代怀合法吗&成功代怀生子网,促排卵33个成功率，移植鲜胚、囊胚还各有差异！']](https://www.qumengru.com/302442912407.html)
- [['https://www.chengdusokh.cn/218195842091.html', '绝经供卵三代试管助孕，专业机构选择指南与流程解析']](https://www.chengdusokh.cn/218195842091.html)
- [['https://www.cecigou.cn/chuanchengguojidaiyun/20250929/15036.html', '腺肌症注射亮丙瑞林要控制子宫到多大才可以移植胚胎？']](https://www.cecigou.cn/chuanchengguojidaiyun/20250929/15036.html)
- [['https://www.anyhdlyb.cn/1863908740529.html', '南京哪家代生靠谱手术需要多少费用 南京哪家代生靠谱成功率比较高的医院']](https://www.anyhdlyb.cn/1863908740529.html)
- [['https://www.xczxcy.com/24.html', '克罗米素促排成功案例：多囊姐妹的促排好孕实录']](https://www.xczxcy.com/24.html)
- [['https://www.mymydz.cn/311104301483.html', '试管代怀生子']](https://www.mymydz.cn/311104301483.html)
- [['https://www.jzcwjz.net/178.html', '试管代生收费-贵州哪家医院做试管婴儿好贵州试管婴儿医院排名']](https://www.jzcwjz.net/178.html)
- [['https://www.cmanrxrr.cn/1586728974650.html', '39岁生二胎做代生儿子套餐有没有适合的促排方案?']](https://www.cmanrxrr.cn/1586728974650.html)
- [['https://www.bjwdzxkj.cn/2277281240593.html', '2026长沙私立借卵机构排行榜揭露-附机构借卵卵源等待时间 ,代孕机构中心']](https://www.bjwdzxkj.cn/2277281240593.html)
- [['https://www.liangzimayi.com/13.html', '真相揭秘：武汉金喜国际资讯服务怎么样？真实用户评价汇总']](https://www.liangzimayi.com/13.html)
- [['https://www.sjb493.cn/25393939736901.html', '代生的收费促排卵后几天能移植鲜胚？']](https://www.sjb493.cn/25393939736901.html)
- [['https://www.hbhuihaohb.cn/170.html', '三代试管成功经历分享：从艰辛到喜悦的助孕之路']](https://www.hbhuihaohb.cn/170.html)
- [['https://www.sdwmtgccl.cn/56152188827131.html', '株洲2026年第三代试管助孕医院排名：优质辅助生殖机构选择指南']](https://www.sdwmtgccl.cn/56152188827131.html)

*本文整理自母婴健康资讯，仅供科普参考。*
