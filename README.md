# edu-smart-timetable-planner

- 产品名称：`edu-smart-timetable-planner`
- 产品编号：`JLZ-EDU-SK-036`
- 产品类型：Skill
- 所属业务板块：04 教务运营中心
- 作者/维护方：广州金励泽科技服务有限公司
- 研发版本：1.0.1
- 当前状态：**G9_PRE_RELEASE_ACCEPTED / NOT_RUNTIME_VERIFIED**
- 产品规格书：[PRODUCT_SPEC.md](PRODUCT_SPEC.md)
- 使用说明：[USAGE.md](USAGE.md)
- 安装包：[`dist/edu-smart-timetable-planner-v1.0.1.zip`](dist/edu-smart-timetable-planner-v1.0.1.zip)

## 产品功能

智能排课及约束条件处理。

- 主要输入：班级、教师、教室、时间约束、课程时长、学生冲突、教师可用性和硬性规则
- 主要输出：排课草案、约束清单、冲突表、替代方案和人工确认项

## 本地验证

- 测试案例：[tests/TEST_CASES.md](tests/TEST_CASES.md)
- 结构测试：[tests/validate_package.ps1](tests/validate_package.ps1)
- 测试结果：[test-results/v1.0.1.json](test-results/v1.0.1.json)

本地通过证明文件结构、产品契约、分层测试、确定性脚本和安装包完整性通过；生成式模型行为仍为 NOT_RUNTIME_VERIFIED，不代表 WorkBuddy 解析、安装、调用或审核通过。

## 依赖与数据

- 第三方运行依赖：无。
- 默认外部API：无。
- 不要求用户提供API Key。
- 仅处理用户主动提供或明确授权的数据。

## 开源许可证

License: Apache-2.0.

本仓库为免费开放的开源项目。任何人均可依照 Apache License 2.0 使用、修改和分发本项目内容。完整法律条款见 [LICENSE](LICENSE)。
