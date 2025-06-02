# AFAC2025_train_data
该项目为《AFAC2025挑战组-赛题一:基金产品的长周期申购和赎回预测》数据\
项目核心目录如下:
+ AFAC2025_train_data
  + {yyyyMMdd}_update
    + fund_apply_redeem_series.csv

其中，数据文件 **fund_apply_redeem_series.csv** 包含2024年4月8日以来
每天每只基金的申购、赎回量和三个核心页面的曝光UV数据。目录 **{yyyyMMdd}_update** 中 **{yyyyMMdd}** 
表示数据文件最新的日期

例如：参赛选手在2025/06/05下载了 **20250603_update/fund_apply_redeem_series.csv**，则需预测2025/06/04~2025/06/10各支基金的申购赎回量
