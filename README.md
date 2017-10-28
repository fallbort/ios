ios
===

ios小工具


make_lproj
介绍：将目标已翻译lproj文件与原始未翻译的lproj文件合并，生成新的目标lproj文件，生成的文件覆盖目标文件。
用法：./make_lproj /aaa/bbbb/Base.lproj/Local.strings cn de
用法说明：原始文件/aaa/bbbb/Base.lproj/Local.strings，目标文件的目录为"cn.lproj de.lproj",目标文件会放在/aaa/bbbb/cn.lproj/Local.strings /aaa/bbbb/de.lproj/Local.strings