# 安装 package control
- `Ctrl + ~` 调出 console
- 连接外网输入<br>
`import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)`
- `command + Shift + P` 调出命令面板

# 插件
- Emmet 提高HTML & CSS3编写速度
- sideBarEnhancements 侧边栏右键增效插件，提高页面处理速度
- All Autocomplete 检查全部打开文件，相似自动补全插件
- SublimeCodeIntel 代码提示工具
- BracketHighlighter 成对匹配增强，并修改括号等的颜色
- DocBlockr 快速注释
- ConvertToUTF8 UTF8转换
- Codecs33 windows 中文编码
- Material Theme
- OmniMarkupPreview md 实时预览,需要浏览器支持
- TableEditor md talbe书写。首先需要用ctrl + shift + p打开这个功能，然后就可以狂用tab来自动完成了