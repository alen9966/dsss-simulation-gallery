DSSS 通信与双向时间比对仿真图册

在线浏览：https://alen9966.github.io/dsss-simulation-gallery/
仓库：https://github.com/alen9966/dsss-simulation-gallery

迁移主线：原690T Vivado → 原70MHz Simulink → AD9361 Simulink → AD9361 Vivado。
四阶段评估/代码来源/仿真与边界：https://alen9966.github.io/dsss-simulation-gallery/migration.html
实际Simulink模型图/模块/对应仿真图：https://alen9966.github.io/dsss-simulation-gallery/modules.html
上位机实现/硬件环境/更新日志：https://alen9966.github.io/dsss-simulation-gallery/host_console.html
当前S-function为功能参考；模型导出参数/系数/测试数据并生成集成顶层，算法RTL复用及适配。
当前架构：FMQL45T900（Vivado代选XC7Z045）+ AD9361；目标50 MSPS I/Q、50 MHz基带、PN1000。本轮原生50MHz真实RTL/IP数字TX→匹配滤波/FFT/DLL/Costas→100B解帧，在理想及20Hz载波频偏/固定有界噪声两工况通过；锁定质量、PS/DDR/DMA硬件、AD9361模拟/RF及1ns精度未验收。本轮未下载或访问硬件，不由历史图片推断设备在线或当前位流。native50板内自检、旧250MHz DSP/S2双向分时、连续TX/RX和坏帧诊断均按原日期与版本保留，不能拼作当前整板验收。
按00到10分类，图册区分当前功能参考、实际RTL分段验证、明确范围的接口实测和历史参考。
60项完整清单包含待补图；现有零误码结果不代表70km无线实测或完整硬件验收。
GitHub Pages从main分支根目录自动发布，index.html是浏览入口。
本仓库保存图册、分类说明与图源索引；原始Vivado/Simulink工程另行维护。
后续仿真在本地登记新图并执行“更新并发布仿真图.ps1”，验证后提交至此。
