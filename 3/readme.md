# data/3 解析报告

本报告由 `process/3/3_dataprocess.py` 自动生成。
代码不对源数据做任何修正，所有异常只登记不改写。

## docx ↔ txt 交叉校验

- D1 preformed.docx: docx 与 txt 逐格一致，共 124 组。
- Lm preformed.docx: docx 与 txt 逐格一致，共 124 组。

## 解析时遇到的格式异常

- Lm preformed.docx: `D1-D6-Lm(4log) biofilm-CD-2` 72h 的行里夹了 1 个空单元格（源文件分隔符写多了），已剔除空格后按 6 个值取用
- Lm.txt: `D1-D6-Lm(4log) biofilm-CD-2` 72h 的行里夹了 1 个空单元格（源文件分隔符写多了），已剔除空格后按 6 个值取用

## 图1-6 被丢弃的 preformed 行（48h 列不画）

- 图1: `L43(2log)-biofilm` 48h
- 图1: `L43(2log)-plank` 48h
- 图2: `L43(4log)-biofilm` 48h
- 图2: `L43(4log)-plank` 48h
- 图3: `L43(2log)-biofilm` 48h
- 图3: `L43(2log)-plank` 48h
- 图4: `L43(4log)-biofilm` 48h
- 图4: `L43(4log)-plank` 48h
- 图5: `L43(2log)-biofilm` 48h
- 图5: `L43(2log)-plank` 48h
- 图6: `L43(4log)-biofilm` 48h
- 图6: `L43(4log)-plank` 48h

## 两批数据重复性核查 — 数值完全相同的 85 组

- `D1` 0h
- `D1-D6-Lm(2log) biofilm-1` 24h
- `D1-D6-Lm(2log) biofilm-1` 48h
- `D1-D6-Lm(2log) biofilm-1` 72h
- `D1-D6-Lm(2log) biofilm-2` 24h
- `D1-D6-Lm(2log) biofilm-2` 48h
- `D1-D6-Lm(2log) biofilm-2` 72h
- `D1-D6-Lm(2log) biofilm-3` 24h
- `D1-D6-Lm(2log) biofilm-3` 48h
- `D1-D6-Lm(2log) biofilm-3` 72h
- `D1-D6-Lm(2log) biofilm-CD-2` 72h
- `D1-D6-Lm(2log) biofilm-CD-3` 72h
- `D1-D6-Lm(2log) planktonic-1` 24h
- `D1-D6-Lm(2log) planktonic-1` 48h
- `D1-D6-Lm(2log) planktonic-1` 72h
- `D1-D6-Lm(2log) planktonic-2` 24h
- `D1-D6-Lm(2log) planktonic-2` 48h
- `D1-D6-Lm(2log) planktonic-2` 72h
- `D1-D6-Lm(2log) planktonic-3` 24h
- `D1-D6-Lm(2log) planktonic-3` 48h
- `D1-D6-Lm(2log) planktonic-3` 72h
- `D1-D6-Lm(4log) biofilm-1` 48h
- `D1-D6-Lm(4log) biofilm-1` 72h
- `D1-D6-Lm(4log) biofilm-2` 24h
- `D1-D6-Lm(4log) biofilm-3` 48h
- `D1-D6-Lm(4log) biofilm-3` 72h
- `D1-D6-Lm(4log) biofilm-CD-1` 72h
- `D1-D6-Lm(4log) biofilm-CD-2` 72h
- `D1-D6-Lm(4log) biofilm-CD-3` 72h
- `D1-D6-Lm(4log) planktonic-1` 24h
- `D1-D6-Lm(4log) planktonic-1` 48h
- `D1-D6-Lm(4log) planktonic-2` 72h
- `D1-D6-Lm(4log) planktonic-3` 48h
- `D1-D6-Lm(4log) planktonic-3` 72h
- `D1-Lm(2log) biofilm-1` 24h
- `D1-Lm(2log) biofilm-1` 48h
- `D1-Lm(2log) biofilm-2` 48h
- `D1-Lm(2log) biofilm-2` 72h
- `D1-Lm(2log) biofilm-CD-1` 72h
- `D1-Lm(2log) biofilm-CD-2` 72h
- `D1-Lm(2log) planktonic-1` 24h
- `D1-Lm(2log) planktonic-1` 48h
- `D1-Lm(2log) planktonic-1` 72h
- `D1-Lm(2log) planktonic-2` 48h
- `D1-Lm(2log) planktonic-2` 72h
- `D1-Lm(4log) biofilm-1` 24h
- `D1-Lm(4log) biofilm-1` 48h
- `D1-Lm(4log) biofilm-2` 24h
- `D1-Lm(4log) biofilm-2` 72h
- `D1-Lm(4log) biofilm-CD-1` 72h
- `D1-Lm(4log) biofilm-CD-2` 72h
- `D1-Lm(4log) planktonic-1` 48h
- `D1-Lm(4log) planktonic-2` 24h
- `D1-Lm(4log) planktonic-2` 48h
- `D6` 0h
- `D6-Lm(2log) biofilm-1` 24h
- `D6-Lm(2log) biofilm-1` 48h
- `D6-Lm(2log) biofilm-1` 72h
- `D6-Lm(2log) biofilm-2` 24h
- `D6-Lm(2log) biofilm-2` 48h
- `D6-Lm(2log) biofilm-2` 72h
- `D6-Lm(2log) biofilm-CD-1` 72h
- `D6-Lm(2log) biofilm-CD-2` 72h
- `D6-Lm(2log) planktonic-1` 24h
- `D6-Lm(2log) planktonic-1` 48h
- `D6-Lm(2log) planktonic-1` 72h
- `D6-Lm(2log) planktonic-2` 24h
- `D6-Lm(2log) planktonic-2` 48h
- `D6-Lm(2log) planktonic-2` 72h
- `D6-Lm(4log) biofilm-1` 24h
- `D6-Lm(4log) biofilm-1` 48h
- `D6-Lm(4log) biofilm-1` 72h
- `D6-Lm(4log) biofilm-2` 24h
- `D6-Lm(4log) biofilm-2` 48h
- `D6-Lm(4log) biofilm-2` 72h
- `D6-Lm(4log) biofilm-CD-1` 72h
- `D6-Lm(4log) biofilm-CD-2` 72h
- `D6-Lm(4log) planktonic-1` 24h
- `D6-Lm(4log) planktonic-1` 48h
- `D6-Lm(4log) planktonic-1` 72h
- `D6-Lm(4log) planktonic-2` 24h
- `D6-Lm(4log) planktonic-2` 48h
- `D6-Lm(4log) planktonic-2` 72h
- `L43(2log)` 0h
- `L43(4log)` 0h

## 两批数据重复性核查 — 有差异的 21 组

- `D1-D6-Lm(2log) biofilm-CD-1` 72h — 2 格不同：R4: 1.778 → 2.778；R5: 1.954 → 2.954
- `D1-D6-Lm(4log) biofilm-1` 24h — 1 格不同：R5: 5.033 → 6.033
- `D1-D6-Lm(4log) biofilm-2` 48h — 4 格不同：R1: 8.748 → 7.748；R4: 8.452 → 7.452；R5: 8.662 → 7.662；R6: 8.386 → 7.386
- `D1-D6-Lm(4log) biofilm-2` 72h — 1 格不同：R5: 9.162 → 9.662
- `D1-D6-Lm(4log) biofilm-3` 24h — 2 格不同：R2: 4.0 → 5.0；R6: 4.267 → 5.267
- `D1-D6-Lm(4log) planktonic-1` 72h — 4 格不同：R3: 7.903 → 8.903；R4: 7.934 → 8.934；R5: 8.079 → 9.079；R6: 7.929 → 8.929
- `D1-D6-Lm(4log) planktonic-2` 24h — 3 格不同：R2: 7.0 → 6.0；R5: 6.954 → 5.954；R6: 7.079 → 6.079
- `D1-D6-Lm(4log) planktonic-2` 48h — 3 格不同：R4: 9.554 → 9.954；R5: 9.549 → 9.949；R6: 9.529 → 9.929
- `D1-D6-Lm(4log) planktonic-3` 24h — 2 格不同：R3: 7.954 → 6.954；R4: 7.845 → 6.845
- `D1-Lm(2log) biofilm-1` 72h — 4 格不同：R1: 7.991 → 8.991；R2: 8.212 → 9.212；R3: 8.124 → 9.124；R5: 8.286 → 9.286
- `D1-Lm(2log) biofilm-2` 24h — 1 格不同：R6: 4.098 → 3.398
- `D1-Lm(2log) planktonic-2` 24h — 1 格不同：R1: 7.001 → 6.301
- `D1-Lm(4log) biofilm-1` 72h — 1 格不同：R4: 7.63 → 8.63
- `D1-Lm(4log) biofilm-2` 48h — 1 格不同：R5: 6.554 → 6.954
- `D1-Lm(4log) planktonic-1` 24h — 1 格不同：R2: 6.903 → 7.903
- `D1-Lm(4log) planktonic-1` 72h — 6 格不同：R1: 7.845 → 8.845；R2: 7.954 → 8.954；R3: 7.903 → 8.903；R4: 8.013 → 9.013；R5: 8.299 → 9.299；R6: 8.228 → 9.228
- `D1-Lm(4log) planktonic-2` 72h — 6 格不同：R1: 7.908 → 8.908；R2: 7.69 → 8.69；R3: 7.602 → 8.602；R4: 7.447 → 8.447；R5: 7.954 → 8.954；R6: 7.653 → 8.653
- `L43(2log)-biofilm` 48h — 6 格不同：R1: 2.903 → 3.903；R2: 3.0 → 4.0；R3: 3.185 → 4.185；R4: 2.663 → 3.663；R5: 2.778 → 3.778；R6: 2.74 → 3.74
- `L43(2log)-plank` 48h — 2 格不同：R1: 5.301 → 6.301；R4: 5.0 → 6.0
- `L43(4log)-biofilm` 48h — 1 格不同：R3: 3.778 → 4.778
- `L43(4log)-plank` 48h — 3 格不同：R4: 7.699 → 6.699；R5: 7.778 → 6.778；R6: 7.845 → 6.845

## 全组 ND（画在检出限 1 log）的 16 组

- 图1 D1 biofilm_CD 72h_AB
- 图1 L43 biofilm_CD 72h_AB
- 图2 D1 biofilm_CD 72h_AB
- 图2 L43 biofilm_CD 72h_AB
- 图3 D6 biofilm_CD 72h_AB
- 图4 D6 biofilm_CD 72h_AB
- 图5 D6 biofilm_CD 72h_AB
- 图6 D6 biofilm_CD 72h_AB
- 图7 D1 biofilm_CD 72h_AB
- 图7 L43 biofilm_CD 72h_AB
- 图8 D1 biofilm_CD 72h_AB
- 图8 L43 biofilm_CD 72h_AB
- 图9 D6 biofilm_CD 72h_AB
- 图10 D6 biofilm_CD 72h_AB
- 图11 D6 biofilm_CD 72h_AB
- 图12 D6 biofilm_CD 72h_AB

## 每张图的系列清单

- 图1 (D_pre, D1, Lm 2log): 菌株 ['D1', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 16 组
- 图2 (D_pre, D1, Lm 4log): 菌株 ['D1', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 16 组
- 图3 (D_pre, D6, Lm 2log): 菌株 ['D6', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 16 组
- 图4 (D_pre, D6, Lm 4log): 菌株 ['D6', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 16 组
- 图5 (D_pre, D1+D6, Lm 2log): 菌株 ['D1', 'D6', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 24 组
- 图6 (D_pre, D1+D6, Lm 4log): 菌株 ['D1', 'D6', 'L43']，x 槽位 ['0h', '24h', '48h', '72h', '72h_AB']，共 24 组
- 图7 (Lm_pre, D1, Lm 2log): 菌株 ['D1', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 18 组
- 图8 (Lm_pre, D1, Lm 4log): 菌株 ['D1', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 18 组
- 图9 (Lm_pre, D6, Lm 2log): 菌株 ['D6', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 18 组
- 图10 (Lm_pre, D6, Lm 4log): 菌株 ['D6', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 18 组
- 图11 (Lm_pre, D1+D6, Lm 2log): 菌株 ['D1', 'D6', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 26 组
- 图12 (Lm_pre, D1+D6, Lm 4log): 菌株 ['D1', 'D6', 'L43']，x 槽位 ['0h', '48h_pre', '24h', '48h', '72h', '72h_AB']，共 26 组
