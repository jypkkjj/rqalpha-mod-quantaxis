rqalpha-mod-quantaxis
如果本地QA已保存分钟数据，可使用QA_adv版本，并修改data_source.py中
def available_data_range(self, frequency):的数据可用时间范围

20200119 修改这个rqalpha-mod-tushare,使用QA获取分笔数据合成为分钟线
借鉴了https://github.com/CallingWisdom/rqalpha-mod-minute的代码，在此表示感谢这个项目作者．

Make QUANTAXIS compatible with RQAlpha

这个 mod 暂时处于 demo 阶段，由于没有对数据进行完整地还原，使用起来可能会出现诸多 bug。 在这个 mod 达到可用的状态前暂时不会发包到 pypi，所以暂时不能通过 pip 或者 rqalpha mod install 命令进行安装。 欢迎各位同学提交代码一起完成 tushare 数据源的对接。
