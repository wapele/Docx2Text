# Docx2Text
基于tp5的word导出到text
使用方法
// 实例化
$text = new Docx2Text();
// 加载docx文件
$text->setDocx('./1.docx');
// 将内容存入$docx变量中
$docx = $text->extract();
// 调试输出
var_dump($docx);
