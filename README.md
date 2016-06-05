                  ###################################################################
                  #                                                                 #
                  #    Deep Sketch Project                                          #
                  #    Xiong Duan (hgysdx@163.com)                                  #
                  #                                                                 #
                  ###################################################################


# deepsketch
This code is incomplete corresponding to the paper, see more in http://dx.doi.org/10.1016/j.neucom.2016.04.046

If you use this demo in your project, we appreciate it if you cite an appropriate subset of our paper:

@article{wang2016deep,
  title={Deep Sketch Feature for Cross-domain Image Retrieval},
  author={Wang, Xinggang and Duan, Xiong and Bai, Xiang},
  journal={Neurocomputing},
  year={2016},
  publisher={Elsevier}
}


# the step of using deepsketch demo code.
1. dataset.
  The skecth dataset can be download in http://cybertron.cg.tu-berlin.de/eitz/projects/classifysketch/.
  And the corresponding image dataset can be download in http://pan.baidu.com/s/1eSHfRdK
2. toolbox.
  This project need download Piotr's Matlab Toolbox (https://pdollar.github.io/toolbox/), edgebox-toolbox(https://github.com/pdollar/edges) and caffe(https://github.com/BVLC/caffe) to support. For the windows-caffe, you can setup your environment by using(https://github.com/happynear/caffe-windows ).
3. put the code, Piotr's Matlab Toolbox and edgebox-toolbox in caffe-windows-master\matlab\demo.
  Edit deepsketch.m in your matlab wrapper and change all the paths in the code.

4. run deepsketch.m if there is no error.




