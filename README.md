# PDF_to_Word<\br>
1.需要一个python的编写和运行环境，并安装好相关的依赖项，本文使用pycharm。<\br>
2.实现功能需要的依赖包如下：<\br>
  PDFParse（文档分析器）<\br>
  PDFDocument（文档对象）<\br>
  PDFresourceManager（资源管理器）<\br>
  PDFPageInterpreter（解释器）<\br>
  PDFPageAggregator（聚合器）<\br>
  LAParams（参数分析器）<\br>
3.准备工作<\br>
  （1）安装pdfminer3k模块<\br>
       直接在cmd输入  pip3 install pdfminer3k<\br>
  （2）整体思路<\br>
       ![](https://pic2.zhimg.com/v2-492a9b64010353f5345867a522035264_r.jpg)<\br>
       ![](https://pic3.zhimg.com/v2-a4423bec54a9374962eaa861ce5cf835_r.jpg)<\br>
   (3)导入需要解析的PDF文件<\br>
      将需要解析的文件与执行代码放在同一个目录下<\br>
      ![](https://pic2.zhimg.com/80/v2-6bd9c7a0f368698bef6542c90dce63ea_hd.jpg)<\br>
 4.具体代码<\br>
   
