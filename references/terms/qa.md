# 测试/质量保证（QA）岗位术语

## 测试类型

| 术语 | 释义 | 用法 |
|------|------|------|
| Unit test | 单元测试 | The unit test coverage needs to reach 80%. |
| Integration test | 集成测试 | We run integration tests in the staging environment. |
| E2E test (End-to-End) | 端到端测试 | E2E tests simulate real user flows. |
| Regression test | 回归测试 | We run regression tests before every release. |
| Smoke test | 冒烟测试 | The smoke test passed — we can proceed with deployment. |
| Sanity test | 合理性测试 | Let's run a quick sanity test first. |
| Black box testing | 黑盒测试 | Black box testing focuses on inputs and outputs. |
| White box testing | 白盒测试 | White box testing requires access to the source code. |
| Performance test | 性能测试 | Performance test results show 30% improvement. |
| Load test | 压力测试 | We need to run load tests before the big sale event. |
| Stress test | 极限测试 | The system held up well under stress test conditions. |
| Security test / pen test | 安全测试/渗透测试 | A pen test identified three vulnerabilities. |
| A/B test | A/B 测试 | The A/B test is still running — don't draw conclusions yet. |
| Canary test | 金丝雀发布测试 | We ran a canary test on 5% of traffic. |

## 缺陷管理

| 术语 | 释义 | 用法 |
|------|------|------|
| Bug | 缺陷 | We found a critical bug in the checkout flow. |
| Defect | 缺陷 | The defect was logged in the bug tracker. |
| Issue | 问题 | There are 15 open issues in the current sprint. |
| Severity | 严重程度 | P0 severity — this blocks the entire release. |
| Priority | 优先级 | We need to bump the priority to P1. |
| P0 / P1 / P2 / P3 | 缺陷等级 | P0 bugs get fixed immediately; P3 can wait. |
| Reproduce | 复现 | Can you reproduce the issue consistently? |
| Root cause | 根本原因 | We need to dig into the root cause, not just fix the symptom. |
| Hotfix | 热修复 | We pushed a hotfix to production last night. |
| Patch | 补丁 | The patch fixes the login issue on iOS. |
| Bug bash | Bug 大扫除 | We're doing a company-wide bug bash on Friday. |
| Triage | 分诊/筛选 | We need to triage the bugs before the sprint planning. |

## 测试流程

| 术语 | 释义 | 用法 |
|------|------|------|
| Test plan | 测试计划 | The test plan covers all major user scenarios. |
| Test case | 测试用例 | We have 200 test cases for this feature. |
| Test coverage | 测试覆盖率 | Test coverage is at 75% — we need to do better. |
| Test environment | 测试环境 | Please test it in the staging environment first. |
| Staging | 预发布环境 | Everything looks good in staging — let's ship it. |
| QA sign-off | QA 审批 | We need QA sign-off before going to production. |
| UAT (User Acceptance Testing) | 用户验收测试 | UAT starts next Monday with the client team. |
| Test automation | 自动化测试 | We're investing heavily in test automation this quarter. |
| CI/CD | 持续集成/持续部署 | Our CI/CD pipeline runs all tests automatically. |
| Canary release | 金丝雀发布 | We use canary releases to catch issues early. |
| Rollback | 回滚 | If something goes wrong, we can rollback in 5 minutes. |
| Monitoring | 监控 | We're monitoring the release closely over the next 48 hours. |
| Alert | 告警 | The alert triggered at 3am — there was a service disruption. |
| On-call | 值班 | Who's on-call this weekend? |

## 测试常用表达

```
"The test suite is green — all tests passed."
"We've had a few flaky tests that need investigation."
"Can you write a test for this edge case?"
"The test coverage report shows we're missing some branches."
"We need to mock the API response for this test."
"Test it locally before pushing to the CI pipeline."
```
