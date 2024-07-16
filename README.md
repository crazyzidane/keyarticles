important articles for personal, especially on computer science.

## 1. deep learning
* tensorflow lite micro
    * TensorFlow Lite Micro: Embedded Machine Learning on TinyML Systemsa
    * https://arxiv.org/abs/2010.08678

* cnn-winograd
    * Fast Algorithms for Convolutional Neural Networks
    * https://arxiv.org/abs/1509.09308

* how to optimize gemm
    * https://github.com/flame/how-to-optimize-gemm/wiki

* separable convolutions---depthwiseconv and pointwiseconv
    * A Basic Introduction to Separable Convolutions
        * https://towardsdatascience.com/a-basic-introduction-to-separable-convolutions-b99ec3102728
    * MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications
        * https://arxiv.org/abs/1704.04861
        * it used separable conv in mobilenet, so it introduced separable conv in this article.

* binary neural networks
    * https://github.com/JDAI-CV/dabnn
    * daBNN: A Super Fast Inference Framework for Binary Neural Networks on ARM devices
        * https://arxiv.org/abs/1908.05858

* On the Measure of Intelligence
    * https://arxiv.org/abs/1911.01547

## 2. memory
* What Every Programmer Should Know About Memory
    * https://people.freebsd.org/~lstewart/articles/cpumemory.pdf
* Carnegie Mellon University
    * 11-memory-hierarchy.pdf
        * https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/lectures/11-memory-hierarchy.pdf
    * 12-cache-memories.pdf
        * https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/lectures/12-cache-memories.pdf

## 3. quantification
* 2021, A White Paper on Neural Network Quantization
    * https://arxiv.org/abs/2106.08295
* Quantizing deep convolutional networks for efficient inference: A whitepaper
    * https://arxiv.org/abs/1806.08342
* Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference
    * https://arxiv.org/abs/1712.05877
* Outlier Channel Splitting
    * Improving Neural Network Quantization without Retraining using Outlier Channel Splitting
        * https://arxiv.org/abs/1901.09504 , three methods abou clip
    * Outlier Channel Splitting Improving DNN Quantization without Retraining
        * https://icml.cc/media/icml-2019/Slides/5053.pdf
        * github, https://github.com/cornell-zhang/dnn-quant-ocs
* nvidia, INTEGER QUANTIZATION FOR DEEP LEARNING INFERENCE: PRINCIPLES AND EMPIRICAL EVALUATION
    * https://arxiv.org/pdf/2004.09602.pdf, show some interesting data
* DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients
    * https://arxiv.org/abs/1606.06160 



## 4. LLM
* Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems
   * https://arxiv.org/abs/2312.15234
* stable diffusion 3, Scaling Rectified Flow Transformers for High-Resolution Image Synthesis
   * https://stabilityai-public-packages.s3.us-west-2.amazonaws.com/Stable+Diffusion+3+Paper.pdf
* BiTA: Bi-Directional Tuning for Lossless Acceleration in Large Language Models
   * https://arxiv.org/html/2401.12522v2
   * https://github.com/linfeng93/BiTA
* deploy:
   * source
      * vllm: https://github.com/vllm-project/vllm
      * lightllm: https://github.com/ModelTC/lightllm
      * mlc-llm: https://github.com/mlc-ai/mlc-llm
* kv cache
   * paged attention
      * paged attention: both vllm and lightllm(token attention) used.
      * Efficient Memory Management for Large Language Model Serving with PagedAttention
         * https://arxiv.org/abs/2309.06180
      * https://blog.vllm.ai/2023/06/20/vllm.html
   * qcom-qualla: NSPKVManager
   * llama, ggml_cpy, just for memory copy and concat
   * MQG, GQA, need to change model struct.
      * https://arxiv.org/pdf/2305.13245   GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints
      * https://zhuanlan.zhihu.com/p/655325832
      * https://zhuanlan.zhihu.com/p/659238103
* quantize
   * aimet, AIMET is a library that provides advanced quantization and compression techniques for trained neural network models.
      * https://github.com/quic/aimet
   * qserve mit, QServe: W4A8KV4 Quantization and System Co-design for Efficient LLM Serving
      * https://arxiv.org/abs/2405.04532
      * https://github.com/mit-han-lab/qserve

## 5. others
* Latency Numbers Every Programmer Should Know
    * https://colin-scott.github.io/personal_website/research/interactive_latency.html
    * github ， https://github.com/colin-scott/interactive_latencies

* DEN0018A_neon_programmers_guide_en
    * https://www.mobibrw.com/wp-content/plugins/pdfjs-viewer-shortcode/pdfjs/web/viewer.php?file=/wp-content/uploads/2019/04/DEN0018A_neon_programmers_guide_en.pdf&attachment_id=&dButton=true&pButton=true&oButton=false&sButton=true
    * https://gist.github.com/csukuangfj/ff116f9296b4d3f661e2d42e5da18d01

* 硬件体系架构浅析
    * https://lrita.github.io/images/posts/tools/%E7%A1%AC%E4%BB%B6%E4%BD%93%E7%B3%BB%E6%9E%B6%E6%9E%84%E6%B5%85%E6%9E%90.pdf

* google, tpu, In-Datacenter Performance Analysis of a Tensor Processing Unit
    * https://arxiv.org/abs/1704.04760


