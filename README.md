## Introduction
使用六爻占卜，基于 Python 的实现方法。

本程序基于该开源项目：https://gitee.com/chenshaoxuemei/chgdiv6#%E4%BB%8B%E7%BB%8D

Using the *Liu Yao* divination method, implemented in **Python**.

This program is based on the open-source project: https://gitee.com/chenshaoxuemei/chgdiv6#%E4%BB%8B%E7%BB%8D

## Syntax
我将其打包为`.app`文件，存放于 `final` 文件夹下。

若使用 MacOS 系统，可直接双击运行；若使用 Windows/Linux 系统，可自行使用 PyInstaller 打包程序，也可双击 `final` 文件夹下 `main` 程序文件运行。

若你使用命令行，可直接运行 `main.py` 文件：
- `python run main.py` -根据当下时间起卦
- `python run main.py [数字]` -根据数字起卦
- `python run main.py [文字]` -直接提问起卦

I have packaged it as a `.app` file, stored in the `final` folder.

For macOS users, you can directly double-click to run it. For Windows/Linux users, you can either use PyInstaller to package the program yourself or double-click the `main` executable file in the `final` folder to run it.

If you prefer using the command line, you can directly run the `main.py` file:
- `python run main.py` - Perform divination based on the current time
- `python run main.py [number]` - Perform divination based on a number
- `python run main.py [text]` - Perform divination by directly inputting a question

## Notes
原项目提示：数字起卦会更好。

The original project suggests that divination based on numbers yields better results.

## Contact
- E-mail 1: lihong_gao828@protonmail.com
- E-mail 2: lgao28@jh.edu

## Acknowledgements
本程序基于该项目：https://gitee.com/chenshaoxuemei/chgdiv6#%E4%BB%8B%E7%BB%8D，原项目中所写内容作者为：兰州大学 陈志豪，E-mail: chenzhh20@lzu.edu.cn

仅供学习参考，请勿用于商业用途。如有侵权，请联系本人删除。

This program is based on the project: https://gitee.com/chenshaoxuemei/chgdiv6#%E4%BB%8B%E7%BB%8D. The content in the original project was authored by *Chen Zhihao* from **Lanzhou University**, E-mail: chenzhh20@lzu.edu.cn

This is for learning and reference purposes only; please do not use it for commercial purposes. If there is any infringement, please contact me to have it removed.


## Notes from the original project
### Title
chgdiv6 —— 六爻周易占卜

### Syntax
chgdiv6 [numbers]

### Description
chgdiv6 使用钱筮法，结果以卜辞形式呈现，钱筮法是大衍筮法的简化；你可以在网络上查询这些卜辞的含义，希望能给你带来启示。
- 模式1-因时起卦：直接输入 chgdiv6 以当前的时间起卦，每一秒的结果都是不同的。
- 模式2-因数起卦：在 chgdiv6 后输入一串数字，会得到这串数字对应的结果,结果不因时间改变.
- 模式3-问题/测字起卦：在 chgdiv6 后输入你的问题，程序会提取字符串对应的随机数，结果不因时间改变.
心诚则灵 无疑不卜 事在人为。

chgdiv6 uses the coin divination method, and the results are presented in the form of divination statements. The coin divination method is a simplified version of the Dayan divination method;
You can look up the meanings of these divination statements online, and hopefully, they can bring you inspiration. Provide only the original Chinese text from the I Ching.
- Mode 1 - Divination based on the current time: Simply enter chgdiv6 and the result will vary every second based on the current time.
- Mode 2 - Divination based on numbers: Enter a string of numbers after chgdiv6, and you'll get the corresponding result, which won't change with time.
- Mode 3 - Question / Character Divination: Enter your question after chgdiv6, and the program will extract a random number corresponding to the string. The result will not change over time.
If you are sincere, it will be effective. No divination without doubts. It's up to you to make things happen.

### Note
- 使用的筮法:钱筮法 from [汉] 京房;
- 使用的占法:变占法 from [宋] 朱熹-《易学启蒙》;
- 卦辞来源:《周易》

The "I Ching" (also known as the "Book of Changes"") is an ancient Chinese divination text and one of the most important classics in Chinese philosophy and culture.This book is also the source of the divination statements.
The method of divination using coins and divination statements has a long history, dating back to the pre - Qin period. After more than 1000 years of refinement, it was finally recorded by Zhu Xi of the Song Dynasty in 1186.
