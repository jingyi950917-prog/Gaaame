<img width="496" height="61" alt="image" src="https://github.com/user-attachments/assets/e938b54f-856d-405d-b1b5-18d01fb13f4a" />#Project: AEON-MINER (星际能源演化系统)
AEON-MINER 是一款基于 HTML5 Canvas 构建的高性能、极简主义交互系统。它旨在通过实时的资源获取与动态难度演算法，模拟一个资源匮乏环境下的系统自我演化过程。
本系统放弃了传统的图形素材，转而采用纯数学算力生成视觉效果，以确保在移动端（特别是 iPhone）上的极简响应速度。
1. 演化矩阵 (Evolutionary Matrix)
系统根据累积能量值（Score）进行三个阶段的逻辑进化：
| 阶段 | 阈值 | 状态 (Status) | 物理特性 (Attributes) |
| :--- | :--- | :--- | :--- |
| I | 0+ | BASIC | 标准碰撞半径，线性运动 |
| II | 100+ | STABLE | 半径扩张 25%，增加响应反馈 |
| III | 300+ | ADVANCED | 激活核心护盾环，高阶色彩渲染 |
| IV | 600+ | GOD_MODE | 概率性容错逻辑 (50% 核心保护) |
2. 动态难度算法
难度并非固定，而是基于非线性迭代进行

🕹 交互指令
• 移动控制：单指触摸并左右滑动（TouchMove）。
• 资源采集：接触 金色核心 (+10 Energy)。
• 避障指令：规避 红色陨石 (Critical Error)。
📝 开发者备注 (INTJ Log)
• Status: 第一阶段开发完成。
• Optimization: 采用 requestAnimationFrame 确保 60FPS 的视觉输出。
• Next Step: 考虑引入更复杂的非对称攻击模式。
