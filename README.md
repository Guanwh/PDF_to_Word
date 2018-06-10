# PDF_to_Word
              1.需要一个python的编写和运行环境，并安装好相关的依赖项，本文使用pycharm。
              2.实现功能需要的依赖包如下：
                  PDFParse（文档分析器）
                  PDFDocument（文档对象）
                  PDFresourceManager（资源管理器）
                  PDFPageInterpreter（解释器）
                  PDFPageAggregator（聚合器）
                  LAParams（参数分析器）
              3.准备工作
                （1）安装pdfminer3k模块
                      直接在cmd输入  pip3 install pdfminer3k
                （2）整体思路
                      ![](https://pic2.zhimg.com/v2-492a9b64010353f5345867a522035264_r.jpg)
                      ![](https://pic3.zhimg.com/v2-a4423bec54a9374962eaa861ce5cf835_r.jpg)
                 (3)导入需要解析的PDF文件
                      将需要解析的文件与执行代码放在同一个目录下
                      ![](https://pic2.zhimg.com/80/v2-6bd9c7a0f368698bef6542c90dce63ea_hd.jpg)
              4.具体代码
   
