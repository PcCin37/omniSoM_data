# omniSoM_data

master 分支中包含了所有的测试用例

/img 中有原始的测试图例

/outputs 中包含的是测试得到的结果

每个子文件夹下的
_parsed_content.txt文件中是OmniParser生成的原生文本输出，
_processed.jpg文件是OmniParser生成的经过ocr以及yolo标注的图像输出，
_revised.jpg文件是经过SoM处理后的按顺序获得的标注图像，
tags_order_sorted.txt文件则是对应SoM处理后按顺序进行的文本标注信息。
