 ssd-plate_detection

 1.this is plate detection project based on ssd(single shot detection)

 2.I have released the model and some data to test,you can take the model from:http://pan.baidu.com/s/1eSdqHVk
   if you have any question,please contact me at: 724620509@qq.com

 3.I hope you have setup a specific caffe. You should use the Caffe SSD (which is very different from the original Caffe) from the paper author here: https://github.com/weiliu89/caffe/tree/ssd. if you have not, please install this type of Caffe as: http://caffe.berkeleyvision.org/installation.html. Be sure to make the Caffe with GPU usage for running this project.

 4.this project is based on jupyter notebook ,if you have not install jupyter ,you could install the python project `Jupyter` or convert it into .py with some tools.
 
 5.what is more,you have to check and modify every path very carefully in ssd_plate.ipynb and deploy.prorotxt such as:name_size_file,model_def,model_weights ,etc according your environment. You may even move some files in this project to other places or use the right path for those files！
 
 6.if you want to know the details about how to train the model.please see at:https://arxiv.org/abs/1512.02325 

 ![image](https://github.com/hyh21521038/ssd-plate_detection/blob/master/result/1.png)
