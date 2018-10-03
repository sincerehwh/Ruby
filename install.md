
# Mac Install SDK

##步骤1 － 安装 RVM

1.curl -L https://get.rvm.io | bash -s stable

2.载入 RVM 环境:
    source ~/.rvm/scripts/rvm

3.测试环境: rvm -v

##步骤2 － 用 RVM 安装 Ruby 环境

1.rvm install 2.0.0

## 步骤3 － 设置 Ruby 版本

1.rvm 2.0.0 --default

2.校验版本: ruby -v 

3.校验版本: gem -v

gem source -r https://rubygems.org/
gem source -a https://ruby.taobao.org
removed from sources
gem source -a https://ruby.taobao.org
gem sources -l  

用RVM升级Ruby:
ruby -v 
rvm list known
rvm install 2.3