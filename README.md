终端器件评审流程
1、提出测试方案：针对当前Memory器件生产测试项目，新增某测试方案；
2、提交TMG评审：将方案提交Memory TMG评审；
3、评审方案：Memory TMG团队召开会议，就具体方案及实现方法进行详细评审；
4、详细设计: Memory TMG评审通过后，进行详细设计，评审不通过，方案终止；
5、小批量验证：在某个产品上验证测试方案，验证数量要求不低于5K；
6、评审验证结果: 测试项目相关人需要提供详细的生产数据，生产情况报告，包括当时的硬件版本、软件版本，及其他涉及的生产细节信息；Memory TMG就具体的小批量验证结果进行评审，在满足验证质量、生产直通率的情况下，可以进行生产落地，否则驳回重新进行详细设计；
7、生产落地：生产测试方案落地到量产产品。



新产品可靠性评审步骤和方法
可靠性设计评审 
1 ．开展可靠性设计评审的必要性 
    所谓可靠性设计评审，即是在产品设计过程中的一定阶段或在设计基本完成时，组织有关方面的专业技术人员，对可靠性设计工作进行审查和评定。它是以集体的智慧来弥补设计者的不足，使设计的方案和内容更臻于合理和完善。因此，它既是可靠性设计过程一项必要的管理内容，又是进一步提高可靠性的一项有效而又经济的措施。 
2．评审职责
（1） 评审组长：制定评审计划、确定或制定各项评审准则、必要时组织评审人员进行培训、组织必要的资源、进行评审分工、确保正式评审准备充分、分发待评审文档、召开并主持评审会议、向有关领导报告评审结果，并且跟踪评审错误的改正。
（2） 评审人员：必要时参加与评审有关的培训、按评审计划阅读待评审材料、保证对待评审材料的理解、与待评审材料作者讨论，并且指出问题和记录问题。
（3） 新产品设计者：按评审计划准备并按时提交待评审材料或者评审样机、必要时对材料进行解释、和参加评审会议，并且在确定需要改进时按时完成修改。
（4） 记录人员：评审会议中记录评审人员提出的问题及相关讨论。
（5） 项目经理：制定保证评审和改正的项目进度计划，还要确保评审准备时间、评审会议时间及错误的改正时间。而且评审安排及结果与所有项目成员沟通，并参加评审会议、阅读评审报告、分析缺陷原因，并且改进项目质量。

3. 评审方法 
（1）评审人员 
    可靠性设计怦审通常采用由评审小组集体评审的方法。评审小组应由总工程师、产品设计师、可靠性工程师、质量师、工艺师、部品工程师、经销员和标准化人员等组成。他们的任务各有分工，所评审的内容也不同。

（2）评审程序 
     ①初审在样机试输入制阶段进行，主要是原来图、PCB板、关键元器件的选择及试验、结构的装配关系进行评审。 
     ②复审在样机完成阶段进行，主要对软件功能、硬件功能，元器件、部件的装配合理性、生产工艺可操作性、和样机装机报告及试验情况进行评审。 
     ③终审（I ） 在样机定型阶段进行，主要初样修改后的结果，故障分析和改进措施，各项规定的测试和试验结果进行评审。 
     ④终审（II） 在生产定型阶段进行，主要对生产可行性，生产过程中质量保证措施的建立，以及试生产产品的各项试验情况进行评审。 
在每一个评审阶段，有关部门应向评审小组提供该阶段应具备的相应文件、资料、报告或实物等。 
（3）评审内容和评审结果的处理 
     对评审结果可用两种方法加以评定：一是定性的评定，就是用评审通过与否来评定，这种评定一般适用于初审和复审阶段；二是定量的评定，它是对评审内容逐行进行评分，然后得出评审总得分，再根据总得分的高低评出优、良、中、差四个等级。被评为优、良的产品给予通过，准予定型；被评为中的产品，应对某些单项分较低的项目作出改进之后给予通过并准予定型；而对被评为差的产品怦审未被通过，不予定型。不管被评定哪一个等级，凡评审中提出必须改进的问题，设计师均应认真对待，提出措施限期改进。






二、	评审范围和分类
1、专家评审团评审范围如下，其余版本由各DU/BMT质量组评审。 
1)	所有需上无线IPMT决策的版本；
2)	当年质量BP中明确的年度重点版本；
3)	各质量组识别的高风险版本。

2、专家评审团评审议题分类：
评审分类	评审内容	                责任人
TR：
TR3/5/6	1)	对应阶段质量要求完成情况，CT自检结果；
2)	质量策划的目标和关键措施完成情况的度量分析与评估；
3)	关键质量问题和风险识别；
4)	对下一阶段的质量策划或例外申请；
5)	对产品包成熟度评估的QA建议结论。	RQA
DCP：CDCP/PDCP/ADCP	1)	对应阶段点的质量要求完成结果；
2)	KCP检查结果；
3)	对应阶段DCP的E2E质量目标、措施达成情况；
4)	功能领域XR评估，遗留问题闭环情况；
5)	质量要求完成结果和关键风险评估；
6)	对下一阶段的质量策划或例外申请；
7)	对O/SBP成熟度评估的QA建议结论。	PQA
EOX	1)	EOX绩效评估；
2)	EOX策略及EOX质量保障措施闭环情况；
3)	对EOX决策的PQA建议结论。	PQA
偏差/例外申请	1)	偏差/例外申请说明；
2)	根因分析；
3)	对应的质量风险保证措施；
4)	QA对相关申请的建议；	QA
注：
1、	质量专家评审团汇报模板链接: \\sharnd-fs\sha01\WN_JZZL_F\01 工作目录\00 无线质量管理解决方案\00 六星版本解决方案\00 iSTAR2.0总体方案\02 版本层面\03 质量评估
2、	QA TR会签结论要求：经过质量评审团评审的版本，QA在TR电子流中给出的会签结论必须与评审团评审结论保持一致，如需更改结论，必须先与研发质量与运营部部长沟通。
3、	偏差和例外申请的说明：偏差和例外都是与常规定义、要求存在差异的意思。偏差是事前定义，例外是事后变更。
1)	偏差申请：对与规范/流程定义存在差异的地方进行申请。偏差通常指在质量策划过程中，因某特殊场景，对本项目进行差异化适配定义。
2)	例外申请：对与原计划存在差异的地方进行申请。例外通常指在项目执行过程中，因某种原因触发，在评估了相关风险后对原有计划进行调整。
如：补丁合需求、TR5前启动认证测试、△TR5支持某些特定业务需求、Beta数量/周期调整、版本/补丁号特殊命名等。

三、	质量专家评审团成员任命
组长       无线网络流程与产品质量部&研发质量与运营部 部长
组员       无线网络流程与产品质量部  					流程质量专家
组员       无线网络流程与产品质量部  					质量工程专家
组员       无线网络研发质量与运营部  					流程质量专家
组员       无线网络研发质量与运营部 					质量工程专家
组员       无线网络研发质量与运营部  					PMO专家
组员       无线网络产品线            					PQA专家
组员       无线网络产品线            					RQA专家
组员       无线网络产品线            					平台QA专家
执行秘书   无线网络研发质量与运营部  					质量系统组组员

四、会议时间与议题安排
1、	质量专家评审团每周例行召开，评议包括自行上报的议题和安排议题。
2、	有依赖或配套关系的版本顺序相邻。
3、	同一版本的TR,及对应DCP评审点议题相邻。
4、	对于紧急议题，至少提前1天向执行秘书提出申请，召开临时会议。
5、	各议题汇报人在会后1天内提交会议纪要给执行秘书审核，会议纪要在会后2个工作日之内发布。
6、	执行秘书对评审团的运作情况进行管理，包括会议组织、议题安排、审核、成员出席情况、遗留问题解决情况、年度总结等。

