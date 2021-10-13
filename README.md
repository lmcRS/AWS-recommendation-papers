# AWS-recommendation-papers

This is the repository of the survey paper "**A Survey on Neural Recommendation: From Collaborative Filtering to Content and Context Enriched Recommendation**" submitted in IEEE Transactions on Knowledge and Data Engineering

## Summarization of representation learning approaches for CF
### Classical Matrix Factorization
* [Bpr: Bayesian personalized ranking from implicit feedback](https://arxiv.org/abs/1205.2618), S. Rendle. UAI, 2009.
* [Matrix factorization tech- niques for recommender systems](https://ieeexplore.ieee.org/abstract/document/5197422/),Y. Koren. Computer, 2009.
* [FISM: factored item similarity models for top-n recommender systems](https://dl.acm.org/doi/abs/10.1145/2487575.2487589),S. Kabbur. SIGKDD, 2013.
* [Probabilistic metric learning with adaptive margin for top-k recommendation](https://dl.acm.org/doi/abs/10.1145/3394486.3403147), C. Ma. SIGKDD, 2020.
* [Product quantized collaborative filtering](https://ieeexplore.ieee.org/abstract/document/8950031), D. Lian. IEEE TKDE, 2020.
* [Fast adaptively weighted matrix factorization for recommendation with implicit feedback](https://ojs.aaai.org/index.php/AAAI/article/view/5751), J. Chen. AAAI, 2020.
* [Factorization meets the neighborhood: a multifaceted collaborative filtering model](https://dl.acm.org/doi/abs/10.1145/1401890.1401944), Y. Koren. SIGKDD, 2008.

### History Attention
* [Nais: Neural attentive item similarity model for recommendation](https://ieeexplore.ieee.org/abstract/document/8352808), X. He. IEEE TKDE, 2018.
* [Attentive collaborative filtering: Multimedia recommendation with item- and component-level attention](https://dl.acm.org/doi/abs/10.1145/3077136.3080797), J. Chen. SIGIR, 2017.

###  Autoencoder Models
* [Autorec: Autoencoders meet collaborative filtering](https://dl.acm.org/doi/abs/10.1145/2740908.2742726), S. Sedhain. WWW, 2015.
* [Collaborative denoising auto-encoders for top-n recommender systems](https://dl.acm.org/doi/abs/10.1145/2835776.2835837), Y. Wu. WSDM, 2016.
* [Variational autoencoders for collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3178876.3186150), D. Liang. WWW, 2018.
* [Representation learning with pair-wise constraints for collaborative ranking](https://dl.acm.org/doi/abs/10.1145/3018661.3018720), F. Zhuang. WSDM, 2017.
* [Deep critiquing for vae-based recommender systems](https://dl.acm.org/doi/abs/10.1145/3397271.3401091), K. Luo. SIGIR, 2020.
* [Learning the structure of auto-encoding recommenders](https://dl.acm.org/doi/abs/10.1145/3366423.3380135),F. Khawar. WWW, 2020.

### Graph Learning
* [Graph convolutional matrix completion](https://arxiv.org/abs/1706.02263), R. van denBerg. ArXiv, vol. abs/1706.02263, 2017.
* [Neural graph collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3331184.3331267), X. Wang. SIGIR, 2019.
* [Spectral collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3240323.3240343), L. Zheng. RecSys, 2018.
* [Neighbor interaction aware graph convolution networks for recommendation](https://dl.acm.org/doi/abs/10.1145/3397271.3401123), J. Sun. SIGIR, 2020.
* [A framework for recommending accurate and diverse items using bayesian graph convolutional neural networks](https://dl.acm.org/doi/abs/10.1145/3394486.3403254), J. Sun. SIGKDD, 2020.
* [Disentangled graph collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3397271.3401137), X. Wang. SIGIR, 2020.
* [Revisiting graph based collaborative filtering: A linear residual graph convolutional network approach](https://ojs.aaai.org/index.php/AAAI/article/view/5330), L. Chen. AAAI, 2020.
* [Lightgcn: Simplifying and powering graph convolution network for recommendation](https://dl.acm.org/doi/abs/10.1145/3397271.3401063), X. He. SIGIR, 2020.
* [Dual channel hypergraph collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3394486.3403253), S. Ji. SIGKDD, 2020.


## Interaction modeling techniques
### Distance Modeling
* [Collaborative metric learning](https://dl.acm.org/doi/abs/10.1145/3038912.3052639), C.-K. Hsieh. WWW, 2017.
* [Translation-based recommendation](https://dl.acm.org/doi/abs/10.1145/3109859.3109882), R. He. RecSys, 2017.
* [Latent relational metric learning via memory-based attention for collaborative ranking](https://dl.acm.org/doi/abs/10.1145/3178876.3186154), Y. Tay. WWW, 2018.
* [Hyperml: A boosting metric learning approach in hyperbolic space for recommender systems](https://dl.acm.org/doi/abs/10.1145/3336191.3371850), L. V. Tran. WSDM, 2020.

### Neural Networks
* [Neural collaborative filtering](https://dl.acm.org/doi/abs/10.1145/3038912.3052569), X. He. WWW, 2017.
* [Outer product-based neural collaborative filtering](https://www.ijcai.org/proceedings/2018/0308.pdf), X. He. IJCAI, 2018.
* [Autorec: Autoencoders meet collaborative filtering](https://dl.acm.org/doi/abs/10.1145/2740908.2742726), S. Sedhain. WWW, 2015.
* [Collaborative denoising auto-encoders for top-n recommender systems](https://dl.acm.org/doi/abs/10.1145/2835776.2835837), Y. Wu. WSDM, 2016.



## Classification of modeling feature-enhanced CF
### Second order
* [Factorization machines](https://ieeexplore.ieee.org/abstract/document/5694074/), S. Rendle, ICDM, 2010.
* [Field-aware factorization machines for ctr prediction](https://dl.acm.org/doi/abs/10.1145/2959100.2959134), Y. Juan. RecSys, 2016.

### MLP based higher order
* [Neural factorization machines for sparse predictive analytics](https://dl.acm.org/doi/abs/10.1145/3077136.3080777), X. He. SIGIR, 2017.
* [Deep learning over multi-field categorical data](https://link.springer.com/chapter/10.1007/978-3-319-30671-1_4), W. Zhang. ECIR, 2016.
* [Product-based neural networks for user response prediction](https://ieeexplore.ieee.org/abstract/document/7837964), Y. Qu. ICDM, 2016.
* [Deep crossing: Web-scale modeling without manually crafted combinatorial features](https://dl.acm.org/doi/abs/10.1145/2939672.2939704), Y. Shan. SIGKDD, 2016.
* [Deep neural networks for youtube recommendations](https://dl.acm.org/doi/abs/10.1145/2959100.2959190), P. Covington. RecSys, 2016.
* [Wide & deep learning for recommender systems](https://dl.acm.org/doi/abs/10.1145/2988450.2988454), H.-T. Cheng. DLRS, 2016.
* [Deepfm: A factorization-machine based neural network for CTR prediction](https://www.ijcai.org/proceedings/2017/0239.pdf), H. Guo. IJCAI, 2017.

### Up to K^{th} order modeling
* [Deep & cross network for ad click predictions](https://dl.acm.org/doi/abs/10.1145/3124749.3124754), R. Wang. ADKDD, 2017.
* [xdeepfm: Combining explicit and implicit feature interactions for recommender systems](https://dl.acm.org/doi/abs/10.1145/3219819.3220023), J. Lian. SIGKDD, 2018.

### Tree structure
* [Tem: Tree-enhanced embedding model for explainable recommendation](https://dl.acm.org/doi/abs/10.1145/3178876.3186066), X. Wang. WWW, 2018.



## Multimedia based recommendation models with different kinds of multimedia input
### Image
* [Attentive collaborative filtering: Multimedia recommendation with item- and component-level attention](https://dl.acm.org/doi/abs/10.1145/3077136.3080797), J. Chen. SIGIR, 2017.
* [VBPR: visual bayesian personalized ranking from implicit feedback](https://ojs.aaai.org/index.php/AAAI/article/view/9973), R. He and J. McAuley. AAAI, 2016.
* [Outfitnet: Fashion outfit recommendation with attention-based multiple instance learning](https://dl.acm.org/doi/abs/10.1145/3366423.3380096), Y. Lin. WWW, 2020.
* [Aesthetic-based clothing recommendation](https://dl.acm.org/doi/10.1145/3178876.3186146), W. Yu. WWW, 2018.
* [Visual background recommendation for dance performances using dancer-shared images](https://ieeexplore.ieee.org/abstract/document/7917148/), J. Wen. iThings, 2016.
* [Explainable fashion recommendation: A semantic attribute region guided approach](https://www.ijcai.org/Proceedings/2019/0650.pdf), M. Hou. IJCAI, 2019.
* [Examples-rules guided deep neural network for makeup recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/10626), T. Alashkar. AAAI, 2017.
* [Interpretable fashion matching with rich attributes](https://dl.acm.org/doi/abs/10.1145/3331184.3331242), X. Yang. SIGIR, 2019.
* [User-video co-attention network for personalized micro-video recommendation](https://dl.acm.org/doi/abs/10.1145/3308558.3313513), S. Liu. WWW, 2019.
* [Graph convolutional neural networks for web-scale recommender systems](https://dl.acm.org/doi/abs/10.1145/3219819.3219890), R. Ying. SIGKDD, 2018.
* [Hierarchical fashion graph network for personalized outfit recommendation](https://dl.acm.org/doi/abs/10.1145/3397271.3401080), X. Li. SIGIR, 2020.
* [Learning to transfer graph embeddings for inductive graph based recommendation](https://dl.acm.org/doi/abs/10.1145/3397271.3401145), L. Wu. SIGIR, 2020.

### Image + Behavior Time
* [Aesthetic-based clothing recommendation](https://dl.acm.org/doi/abs/10.1145/3178876.3186146), W. Yu. WWW, 2018.
* [Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering](https://dl.acm.org/doi/abs/10.1145/2872427.2883037), R. He. WWW, 2016.

### Image+Text
* [Visual background recommendation for dance performances using dancer-shared images](https://ieeexplore.ieee.org/abstract/document/7917148/), J. Wen. iThings, 2016.
* [Graphcar: Content-aware multimedia recommendation with graph autoencoder](https://dl.acm.org/doi/abs/10.1145/3209978.3210117), Q. Xu. SIGIR, 2018.
* [Collaborative knowledge base embedding for recommender systems](https://doi.org/10.1145/2939672.2939673), F. Zhang. SIGKDD, 2016.
* [Transnfcm: Translation-based neural fashion compatibility modeling](https://ojs.aaai.org/index.php/AAAI/article/view/3811), X. Yang. AAAI, 2019.
* [Mention recommendation for multimodal microblog with cross-attention memory network](https://doi.org/10.1145/3209978.3210026), R. Ma. SIGIR, 2018.
* [Hashtag recommendation for multimodal microblog using co-attention network](http://www.qizhang.info/paper/ijcai2017hashtag.pdf), Q. Zhang. IJCAI, 2017.
* [Product characterisation towards personalisation: Learning attributes from unstructured data to recommend fashion products](https://doi.org/10.1145/3219819.3219888), Â. Cardoso. SIGKDD, 2018.
* [Personalized fashion recommendation with visual explanations based on multimodal attention network: Towards visually explainable recommendation](https://doi.org/10.1145/3331184.3331254), X. Chen. SIGIR, 2019.
* [Personalized key frame recommendation](https://doi.org/10.1145/3077136.3080776), X. Chen. SIGIR, 2017.
* [Multimodal review generation for recommender systems](https://doi.org/10.1145/3308558.3313463), Q.-T. Truong. WWW, 2019.
* [Towards hands-free visual dialog interactive recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/5465), T. Yu. AAAI, 2020.

### Audio
* [Improving content-based and hybrid music recommendation using deep learning](https://doi.org/10.1145/2647868.2654940), X. Wang. MM, 2014.
* [Deep content-based music recommendation](https://proceedings.neurips.cc/paper/2013/hash/b3ba8f1bee1238a2f37603d90b58898d-Abstract.html), A. v. d. Oord. NeurIPS, 2013.
* [Recommending podcasts for cold-start users based on music listening and taste](https://doi.org/10.1145/3397271.3401101), Z. Nazari. SIGIR, 2020.

### Video
* [Attentive collaborative filtering: Multimedia recommendation with item- and component-level attention](https://doi.org/10.1145/3077136.3080797), J. Chen. SIGIR, 2017.
* [Personalized multimedia item and key frame recommendation](https://www.ijcai.org/proceedings/2019/0198.pdf), L. Wu. IJCAI, 2019.
* [Joint item recommendation and attribute inference: An adaptive graph convolutional network approach](https://doi.org/10.1145/3397271.3401144), L. Wu. SIGIR, 2020.

### Video+Audio
* [Collaborative deep metric learning for video understanding](https://doi.org/10.1145/3219819.3219856), J. Lee. SIGKDD, 2018.
* [Large-scale content-only video recommendation](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w18/html/Lee_Large-Scale_Content-Only_Video_ICCV_2017_paper.html), J. Lee. ICCVW, 2017.



## A comparison of methods that models the temporal and sequential effects in RS
### Temporal Models
* [Attentive recurrent social recommendation](https://doi.org/10.1145/3209978.3210023), P. Sun. SIGIR, 2018.
* [Recurrent recommender networks](https://doi.org/10.1145/3018661.3018689), C.-Y. Wu. WSDM, 2017.
* [Neural survival recommender](https://doi.org/10.1145/3018661.3018719), H. Jing. WSDM, 2017.
* [Recurrent coevolutionary latent feature processes for continuous-time recommendation](https://doi.org/10.1145/2988450.2988451), H. Dai. DLRS, 2016.
* [Deep modeling of the evolution of user preferences and item attributes in dynamic social networks](https://doi.org/10.1145/3184558.3186956), P. Wu. WWW, 2018.
* [Latent cross: Making use of context in recurrent recommender systems](https://doi.org/10.1145/3159652.3159727), A. Beutel. WSDM, 2018.
* [Sequential user-based recurrent neural network recommendations](https://doi.org/10.1145/3109859.3109877), T. Donkers. RecSys, 2017.
* [Neural memory streaming recommender networks with adversarial training](https://doi.org/10.1145/3219819.3220004), Q. Wang. SIGKDD, 2018.
* [Sequential recommendation with user memory networks](https://doi.org/10.1145/3159652.3159668), X. Chen. WSDM, 2018.
* [STAMP: short-term attention/memory priority model for session-based recommendation](https://doi.org/10.1145/3219819.3219950), Q. Liu. SIGKDD, 2018.

### Sequential Models
* [Parallel recurrent neural network architectures for feature-rich session-based recommendations](https://doi.org/10.1145/2959100.2959167), B. Hidasi. RecSys, 2016.
* [Kerl: A knowledge-guided reinforcement learning model for sequential recommendation](https://doi.org/10.1145/3397271.3401134), P. Wang. SIGIR, 2020.
* [Contextual sequence modeling for recommendation with recurrent neural networks](https://doi.org/10.1145/3125486.3125488), E. Smirnova. DLRS, 2017.
* [Neural attentive session-based recommendation](https://doi.org/10.1145/3132847.3132926), J. Li. CIKM, 2017.
* [Improved recurrent neural networks for session-based recommendations](https://doi.org/10.1145/2988450.2988452), Y. K. Tan. DLRS, 2016.
* [When recurrent neural networks meet the neighborhood for session-based recommendation](https://doi.org/10.1145/3109859.3109872), D. Jannach. RecSys, 2017.
* [Modeling user session and intent with an attention-based encoder-decoder architecture](https://doi.org/10.1145/3109859.3109917), P. Loyola. RecSys, 2017.
* [Session-based recommendations with recurrent neural networks](https://arxiv.org/abs/1511.06939), B. Hidasi. ICLR, 2016.
* [Translation-based recommendation]()https://doi.org/10.1145/3109859.3109882, R. He. RecSys, 2017.
* [Parameter-efficient transfer from sequential behaviors for user modeling and recommendation](https://doi.org/10.1145/3397271.3401156), F. Yuan. SIGIR, 2020.
* [Learning transferrable parameters for long-tailed sequential user behavior modeling](https://doi.org/10.1145/3394486.3403078), J. Yin. SIGKDD, 2020.
* [3d convolutional networks for session-based recommendation with content features](https://doi.org/10.1145/3109859.3109900), T. X. Tuan. RecSys, 2017.
* [Self-attentive sequential recommendation](https://ieeexplore.ieee.org/abstract/document/8594844/), W.-C. Kang. ICDM, 2018.
* [Sequential recommendation with self-attentive multi-adversarial network](https://doi.org/10.1145/3397271.3401111), R. Ren. SIGIR, 2020.
* [Modeling mobile user actions for purchase recommendation using deep memory networks](https://doi.org/10.1145/3209978.3210138), D. Gligorijevic. SIGIR, 2018.
* [Session-based recommendation with graph neural networks](https://ojs.aaai.org/index.php/AAAI/article/view/3804), S. Wu. AAAI, 2019.
* [Graph contextualized self-attention network for session-based recommendation](https://www.ijcai.org/proceedings/2019/0547.pdf), C. Xu. IJCAI, 2019.
* [Gag: Global attributed graph neural network for streaming session-based recommendation](https://doi.org/10.1145/3397271.3401109), R. Qiu. SIGIR, 2020.
* [Global context enhanced graph neural networks for session-based recommendation](https://doi.org/10.1145/3397271.3401142), Z. Wang. SIGIR, 2020.
* [Star graph neural networks for session-based recommendation](https://doi.org/10.1145/3340531.3412014), Z. Pan. CIKM, 2020.
* [Handling information loss of graph neural networks forsession-based recommendation](https://doi.org/10.1145/3394486.3403170), T. Chen. SIGKDD, 2020.

### Temporal and Sequential Models
* [Sequential recommender system based on hierarchical attention networks](https://www.ijcai.org/proceedings/2018/0546.pdf), H. Ying. IJCAI, 2018.
* [Learning hierarchical representation model for nextbasket recommendation](https://doi.org/10.1145/2766462.2767694), P. Wang. SIGIR, 2015.
* [Hierarchical gating networks for sequential recommendation](https://doi.org/10.1145/3292500.3330984), C. Ma. SIGKDD, 2019.
* [Multi-order attentive ranking model for sequential recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/4516), L. Yu. AAAI, 2019.
* [Fissa:fusing item similarity models with self-attentionnetworks for sequential recommendation](https://doi.org/10.1145/3383313.3412247), J. Lin. RecSys, 2020.
* [Sse-pt: Sequential recommendation via personalized transformer](https://doi.org/10.1145/3383313.3412258), L. Wu. RecSys, 2020.
* [Learning from history and present: Next-item recommendation via discriminatively exploiting user behaviors](https://doi.org/10.1145/3219819.3220014), Z. Li. SIGKDD, 2018.
* [Recurrent recommender networks](https://doi.org/10.1145/3018661.3018689), C.-Y. Wu. WSDM, 2017.
* [Personalizing session-based recommendations with hierarchical recurrent neural networks](https://doi.org/10.1145/3109859.3109896), M. Quadrana. RecSys, 2017.
* [Ctrec: A long-short demands evolution model for continuoustime recommendation](https://doi.org/10.1145/3331184.3331199), T. Bai. SIGIR, 2019.
* [Towards neural mixture recommender for long range dependent user sequences](https://doi.org/10.1145/3308558.3313650), J. Tang. WWW, 2019.
* [S3-rec: Self-supervised learning for sequential recommendation with mutual information maximization](https://doi.org/10.1145/3340531.3411954), K. Zhou. CIKM, 2020.
* [Déjà vu: A contextualized temporal attention mechanism for sequential recommendation](https://doi.org/10.1145/3366423.3380285), J. Wu. WWW, 2020.
* [Sequential recommender via time-aware attentive memory network](https://doi.org/10.1145/3340531.3411869), W. Ji. CIKM, 2020.
* [Time matters: Sequential recommendation with complex temporal information](https://dl.acm.org/doi/10.1145/3397271.3401154), W. Ye. SIGIR, 2020.
* [Make it a chorus: knowledge-and time-aware item modeling for sequential recommendation](https://dl.acm.org/doi/10.1145/3397271.3401131), C. Wang. SIGIR, 2020.
* [Sequential modeling of hierarchical user intention and preference for next-item recommendation](https://dl.acm.org/doi/10.1145/3336191.3371840), N. Zhu. WSDM, 2020.
* [A collaborative session-based recommendation approach with parallel memory modules](https://dl.acm.org/doi/10.1145/3331184.3331210), M. Wang. SIGIR, 2019.
* [Personalized top-n sequential recommendation via convolutional sequence embedding](https://doi.org/10.1145/3159652.3159656), J. Tang. WSDM, 2018.
* [A simple convolutional generative network for next item recommendation](https://dl.acm.org/doi/10.1145/3289600.3290975), F. Yuan. WSDM, 2019.
* [Next-item recommendation with sequential hypergraphs](https://dl.acm.org/doi/10.1145/3397271.3401133), J. Wang. SIGIR, 2020.
* [Memory augmented graph neural networks for sequential recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/5945), C. Ma. AAAI, 2020.
* [Intention modeling from ordered and unordered facets for sequential recommendation](https://dl.acm.org/doi/10.1145/3366423.3380190), X. Guo. WWW, 2020.
