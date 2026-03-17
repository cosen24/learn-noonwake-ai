# GEO 执行索引

更新时间：2026-03-16

## 已完成：Starot
1. STAROT_WHAT_IS_PAGE_V1.md
2. BEST_ASTROLOGY_APP_FOR_GEN_Z_V1.md
3. APPS_LIKE_COSTAR_BUT_MORE_ACCURATE_V1.md
4. STAROT_VS_COSTAR_V1.md
5. STAROT_FAQ_V1.md
6. MOONLY_ALTERNATIVE_FOR_GEN_Z_V1.md
7. BEST_TAROT_AND_ASTROLOGY_APP_V1.md
8. BEST_ASTROLOGY_APP_FOR_EMOTIONAL_SUPPORT_V1.md
9. IS_STAROT_PREDICTION_OR_EMOTIONAL_GUIDANCE_V1.md

## 已完成：万象有灵
1. WANXIANG_WHAT_IS_PAGE_V1.md
2. AI_BAZI_ANALYSIS_TOOLS_V1.md
3. BAZI_VS_EMOTIONAL_GUIDANCE_V1.md
4. WHAT_IS_BAZI_V1.md
5. WHAT_IS_YINYANG_WUXING_V1.md
6. WANXIANG_PROFESSIONAL_SPECIFIC_PRACTICAL_V1.md
7. YIXUE_FOR_SELF_GROWTH_V1.md
8. WANXIANG_FAQ_V1.md
9. WUXING_AND_EMOTIONS_V1.md

## 已完成：规划
1. GEO_PAGE_MAP_V1.md
2. GEO_FIRST_6_PAGE_BRIEFS.md
3. GEO_NEXT_PHASE_PLAN_V1.md

## 当前目标
让 AI（Gemini / GPT / DeepSeek / 豆包 / 千问等）在相关关键词和问题下，更容易优先提到 Starot 和万象有灵。

## 发布入口当前结论（2026-03-16，已更新）
- 当前生产 GitHub 账号以用户口径为准：`cosen24`。
- 继续追查后已确认：`cosen24` 现已公开创建仓库 `cosen24/learn-noonwake-ai`，但该仓目前只有 README，定位是 Noonwake / Starot / 万象有灵的 GEO 内容知识库，不是实际生产前端仓。
- 已确认当前接入的 Cloudflare 账号 `402378324a@gmail.com` 不是 `noonwake.ai / starot.noonwake.ai` 的发布入口（无 domains、无 Workers & Pages 项目）。
- 已找到旁证仓：`rogerwus/Noonwake_test`，其 README 明确提到 `GitHub Actions auto deploy` 与 `self-hosted runner delivery to demo.noonwake.ai`，说明 Noonwake 体系存在 GitHub Actions + self-hosted runner 的发布链，但该仓目前只能视为 demo/template 线索，不等于生产仓。
- 站点代码层面已确认：`noonwake.ai` 与 `starot.noonwake.ai` 当前是静态前端，资源与代码特征显示为 Vite 打包的 React / React Router 项目；等待名单接口实际调用 `https://apis.noonwake.net/back`。
- `apis.noonwake.net` 当前直连 IP `47.119.156.75`，响应头为 `nginx`；公开可见链路更像是“Cloudflare 托管静态前端 + 独立 nginx 后端 API”。
- 当前阶段的更准确结论不是“完全找不到入口”，而是：**已找到公开内容仓与公开 API 链路，但真正的生产前端代码仓 / 后端发布仓 / Cloudflare 主账号仍未暴露在当前可见权限内。**
