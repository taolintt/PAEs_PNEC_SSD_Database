# PAEs水体生态风险阈值SSD数据库

## 项目简介
本数据库为邻苯二甲酸酯(PAEs)物种敏感度分布法(SSD)PNEC推导提供支撑数据集。

## 数据来源
- ECOTOX数据库（美国EPA）
- ECHA数据库（欧盟）
- Web of Science学术期刊（2010-2025）

## 纳入标准
- 水生生物（鱼类、藻类、无脊椎动物）
- 毒性指标：NOEC > LOEC > 慢性EC50 > 急性EC50/LC50
- Klimisch评分 ≥ 2

## 主要结果
详见`PAEs_PNEC_Summary.xlsx`

## 文件说明
| 文件名 | 说明 |
|--------|------|
| PAEs_Raw_Data.xlsx | 原始数据表（所有收集的毒性数据） |
| PAEs_Final_SSD.xlsx | 最终SSD数据集（筛选后用于拟合的数据） |
| EEC-SSD_Results.txt | EEC-SSD软件输出结果 |
| SSD_Curve.png | SSD曲线图 |
| PAEs_PNEC_Summary.xlsx | PNEC结果（包含AF取值） |
| Data\_Dictionary.xlsx | 数据字典，说明每一列是什么意思 |

## 使用方法
### 查看数据
1. 打开 `PAEs_Raw_Data.xlsx` 看所有原始数据
2. 打开 `PAEs_Final_SSD.xlsx` 看用于SSD拟合的35条数据

### 查看SSD拟合结果
1. 打开 `SSD_Curve.png` 看SSD曲线
2. 打开 `EEC-SSD_Results.txt` 看HC5数值和统计检验结果

### 重复验证
任何人都可以用同样的数据在EEC-SSD软件中重复拟合，得到相同结果。

## 许可证
CC0 1.0 Universal（公开数据，自由使用）

## 联系方式
邮箱：taolin@ahmu.edu.cn



