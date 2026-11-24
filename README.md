# D′ 策略 · 模拟盘记录

网页：https://beimian3006.github.io/dprime-record/

这个仓库只存展示页本身和每天的数据，由程序在每个交易日收盘后自动更新，没有人工修改。

- `index.html`：展示页
- `data/record.json`：最新数据
- `archive/YYYY-MM-DD.json`：每个交易日收盘后的数据，存了以后不再改
- `archive/YYYY-MM-DD.json.ots`：这份数据的 OpenTimestamps 证明（指纹写进比特币区块链）

核对：下载某一天的 `.json` 和 `.ots`，一起拖到 https://opentimestamps.org 。也可以看提交历史，每天一次提交。

模拟盘记录，用的是券商的模拟资金，不是真钱。回测是事后用历史数据算出来的，不代表将来。不是投资建议。
