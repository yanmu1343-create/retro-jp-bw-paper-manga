# 复古日式黑白纸漫

## 触发与主体

- 当用户提到复古日式黑白纸漫风格或者要求用墨线加网点画黑白插画时使用本技能

- 先确认主体再生成，主体包括人物与神态和动作和场景和构图和画面比例

- 主体缺失时先向用户确认主体，不要用默认人物补齐

- 把主体描述放在前面，把风格规则放在后面，拼成一段生成提示词，再调用 `media.generate_image` 生成

## 墨线与五官

- 用干净流畅的黑色墨线勾形，让线条粗细随笔势自然变化

- 让弧线收笔处轻轻变尖，不要出现生硬的直线折角

- 把头发按大束概括，每束只用几条长弧线交代走向

- 在发束内部保留大片纸白，不要填满碎发丝

- 让头发弧线顺着头型自然走，不要画成硬朗的直线笔画

- 用较重的黑线画上眼睑，用轻而短的弧线画下眼睑

- 用少量线条和黑块概括虹膜，并在眼内保留清楚的白色空间

- 用一两笔交代鼻子

- 用一两笔交代嘴巴

## 留白与网点阴影

- 以纸白为主，让脸颊和头发主体保留纸白

- 只在发束遮住皮肤的位置和下颌投影处和衣物重叠处铺网点

- 用一颗颗分开的黑色小圆点组成浅阴影，放大看点与点分开，缩小看点连成一层浅灰色

- 让头发阴影的黑点密集而且多，点与点之间仍保持分开，不要连成实色块

- 用纯黑墨块表现最深的阴影，并在墨块边缘偶尔露出几笔短排线

## 禁止项

- 不要加黑边，不要加画框

- 不要用柔滑的灰色渐变，不要用喷枪阴影

- 不要画密密麻麻的碎发丝

- 不要把浅阴影画成连续灰面，要保持圆点分开

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.
