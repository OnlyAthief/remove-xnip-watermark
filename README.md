> 其实原理就是写一段python脚本，处理剪贴板中的图片(删除顶部)
> 
> 所以步骤是，先用xnip截图，保存在剪贴板，然后运行 这个 workflow， 不能运行多次，运行完后就可以从剪贴板拷贝出来了
> 
> 测试结果是，要先手动安装python脚本的依赖项,就是requirements.txt那个东东
> 

# Remove Xnip Watermark Alfred Workflow

![Demo](demo.gif?raw=true)

## Installation

required: Python3, Pillow, pastedboard

1. Download this project.
1. import workflow (Double click the workflow file).
1. change variable `py3` and `cropscript` to yours (click the `[x]` button in the upper right corner of workflow window).

![workflows tab](workflows_tab.png?raw=true)

## Notes

If you don't know how to use this workflow. you can remove the watermark in the screenshot by subscribing to Xnip Pro($1.99 per year).
