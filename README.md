# Quantization Caffe for TEE Compute Stick
We add the quantization layer to offical caffe, make it can train the quantization model (1bit/3bit).

With the quantization model, you can transfer it to the model which can run on TEE Compute Stick by the [conversion tool](https://github.com/TEE-AI/SAI/tree/master/train/caffe/convert_tool)

## License and Citation

Caffe is released under the [BSD 2-Clause license](https://github.com/BVLC/caffe/blob/master/LICENSE).
The BAIR/BVLC reference models are released for unrestricted use.

Please cite Caffe in your publications if it helps your research:

    @article{jia2014caffe,
      Author = {Jia, Yangqing and Shelhamer, Evan and Donahue, Jeff and Karayev, Sergey and Long, Jonathan and Girshick, Ross and Guadarrama, Sergio and Darrell, Trevor},
      Journal = {arXiv preprint arXiv:1408.5093},
      Title = {Caffe: Convolutional Architecture for Fast Feature Embedding},
      Year = {2014}
    }
