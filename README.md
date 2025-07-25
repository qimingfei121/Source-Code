# coco json格式的标签转换为yolo txt格式
1.导入文件
定义COCO JSON 文件位置
如果json文件在D:\install\name.json，则令labels_dir=r"D:\install\"
2.导出文件
定义 YOLO TXT 文件输出的目录
save_dir = r"D:\workspace\dataset\train\labels"
如果train目录中没有labels文件，则会在train目录下创建labels和labels2，在labels2中会有txt格式的标签。
