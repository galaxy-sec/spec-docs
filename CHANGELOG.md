# Changelog
## 0.8.0 
*  在sys-spec中调整 _used.json  生成的位置，便于在module中使用
*  value.yml, var.yml 支持对前序变理的引用。
## 0.7.4 
*  调整 values 生成的文件
*  localize  --default_value 改为 --no_cust_value
*  修复地址支持环境变量BUG

## 0.7.3 
*  修复 update   -f 3 指令
*  增加 localize  --default_value , 使用MOD默认值本地化
*  地址(GitAddr, HttpAddr, LocalAddr) 支持环境变量

## 0.7.2

* localize 指定数值文件
* 数值文件支持环境变量

```
Usage: ds-mod localize [OPTIONS]

Options:
  -d, --debug <DEBUG>  [default: 0]
      --log <LOG>      config log ; eg: --log  cmd=debug,parse=info
      --value <VALUE>  use vlaue file; eg: --value cicd_value.yml
  -h, --help           Print help
```



