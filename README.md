# nonebot-plugin-ipypreter
[![pypi](https://img.shields.io/pypi/v/nonebot-plugin-ipypreter.svg)](https://pypi.org/project/nonebot-plugin-ipypreter/)
![implementation](https://img.shields.io/pypi/implementation/nonebot-plugin-ipypreter)
![wheel](https://img.shields.io/pypi/wheel/nonebot-plugin-ipypreter)
![python](https://img.shields.io/pypi/pyversions/nonebot-plugin-ipypreter)
[![license](https://img.shields.io/github/license/iyume/nonebot-plugin-ipypreter.svg)](https://raw.githubusercontent.com/iyume/nonebot-plugin-ipypreter/main/LICENSE)
- 基于 [nonebot2](https://github.com/nonebot/nonebot2)

## 功能
消息交互式 Python 解释器

可以在 Docker 内执行任何 Python 语句并返回结果

## 快速开始 Quickstart
```
pip install nonebot-plugin-ipypreter
```
如果你使用的是`nb-cli`，此时`bot.py`会自动添加`nonebot.load_plugin('nonebot-plugin-ipypreter')`

若没有，请手动添加

```
docker pull python
```
请保证 docker images 包含`python:latest`

**bot 指令**

进入交互环境

> python `aliases=['python3']`

离开交互环境

> exit `aliases=['exit()', 'quit']`

## 配置项 Env
`PLUGIN_IPYPRETER_IMAGE`: your_docker_image_tag

## 特别感谢
- [Mrs4s / go-cqhttp](https://github.com/Mrs4s/go-cqhttp)
- [nonebot / nonebot2](https://github.com/nonebot/nonebot2)

## 优化建议
如有优化建议请积极提交 issues 或者 pull requests
