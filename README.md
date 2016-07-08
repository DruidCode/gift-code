# 礼品码生成器

用法:

```bash
# 10000次生成性能测试
time php demo.php gen 10000

# 生成10000个代码(注意, 生产环境使用, 需要自己控制里面的base, 需要记录这个增长的序列值, 才能保证完全不重复)
php demo.php dump 10000

# 测试10000次随机暴力破解成功率
php demo.php check 10000
```

# 数据指标

```
性能: MBP 13寸顶配(2014款), 10000次生成耗时455ms
暴力破解成功率: 万分之五以内.
```
