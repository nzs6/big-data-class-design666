# 项目名称：大数据导论课程设计项目

## 项目简介

华中科技大学大数据导论课程设计
借助大数据（大量的图片及其对应的标注）
利用这些数据进行机器学习模型的训练，最终实现物体识别和表情识别的功能

## 贡献者

本项目由“树上的鸟儿成双队”小队完成

## 项目内容

1. **数据爬取**：利用爬虫爬取大量图片，进行标注
2. **模型训练**：基于爬取的数据，开展模型训练
3. **机器学习实践**：探索和应用简单的机器学习方法
4. **功能实现**：
   - 物体识别：通过训练模型，识别图片中的不同物体
   - 表情识别：分析人脸表情，识别情绪状态

## 使用说明

- 请确保在运行项目之前，安装所需的依赖库，如`requests`、`numpy`、`tensorflow`等。
  
  ```bash
  pip install requests numpy tensorflow
  ```
- 项目中的爬虫组件会定期请求图片，使用`time.sleep(5)`来限制请求频率，以避免被认出来是爬虫
- 运行代码后，下载的图片将保存在指定的本地路径中

## 结语

感谢大数据导论课堂给予的展示平台（安利一下石老师，讲的巨不错）
感谢所有参与本项目的同学们，你们的努力使得这个项目得以顺利完成

感谢为我们小组打高分的同学们（doge）

希望我们的成果能为大家以后的学习和研究提供参考和帮助
