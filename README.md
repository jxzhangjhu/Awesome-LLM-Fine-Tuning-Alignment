# Awesome-LLM-Fine-Tuning-Alignment
LLM fine-tuning 



# Papers 


## Unsupervised Fine-Tuning 

### Unsupervised Full Fine-Tuning

### Contrastive Learning 


## Supervised Fine-Tuning Methods

### Parameter-Efficient Fine-Tuning (PEFT)


### Supervised Full Fine-Tuning 


### Instruction Fine-Tuning 

**Finetuned Language Models are Zero-Shot Learners** \
*Jason Wei, Maarten Bosma, Vincent Zhao, Kelvin Guu, Adams Wei Yu, Brian Lester, Nan Du, Andrew M. Dai, Quoc V Le* \
ICLR 2022. [[Paper](https://openreview.net/forum?id=gEZrGCozdqR)]

**Instruction Tuning for Large Language Models: A Survey** \
*Shengyu Zhang, Linfeng Dong, Xiaoya Li, Sen Zhang, Xiaofei Sun, Shuhe Wang, Jiwei Li, Runyi Hu, Tianwei Zhang, Fei Wu, Guoyin Wang* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2308.10792)] [[Github](https://github.com/xiaoya-li/instruction-tuning-survey)] 


### RLHF & DPO

**Direct Preference Optimization: Your Language Model is Secretly a Reward Model** \
*Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn*  \
NeurIPS 2023. [[Paper](https://openreview.net/forum?id=HPuSIXJaa9&utm_source=substack&utm_medium=email)]


## RAG vs Fine-tuning 

**RAG vs Fine-tuning: Pipelines, Tradeoffs, and a Case Study on Agriculture** \
*Angels Balaguer, et al* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2401.08406)]

**Fine Tuning vs. Retrieval Augmented Generation for Less Popular Knowledge**  \
*Heydar Soudani, Evangelos Kanoulas, Faegheh Hasibi* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2403.01432)][[Github](https://github.com/heydarsoudani/ragvsft)]

**Reliable, Adaptable, and Attributable Language Models with Retrieval** \
*Akari Asai, Zexuan Zhong, Danqi Chen, Pang Wei Koh, Luke Zettlemoyer, Hannaneh Hajishirzi, Wen-tau Yih* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2403.03187)]

**Long-form factuality in large language models** \
*Jerry Wei, Chengrun Yang, Xinying Song, Yifeng Lu, Nathan Hu, Dustin Tran, Daiyi Peng, Ruibo Liu, Da Huang, Cosmo Du, Quoc V. Le* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2403.18802)][[Github](https://github.com/google-deepmind/long-form-factuality)]


## Data 

### Data selection

**QuRating: Selecting High-Quality Data for Training Language Models**  \
*Alexander Wettig, Aatmik Gupta, Saumya Malik, Danqi Chen* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2402.09739)][[Github](https://github.com/princeton-nlp/qurating)]

**LESS: Selecting Influential Data for Targeted Instruction Tuning** \
*Mengzhou Xia, Sadhika Malladi, Suchin Gururangan, Sanjeev Arora, Danqi Chen* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2402.04333)][[Github](https://github.com/princeton-nlp/less)]


### Data synthesis 

**Best Practices and Lessons Learned on Synthetic Data for Language Models** \
*Ruibo Liu, Jerry Wei, Fangyu Liu, Chenglei Si, Yanzhe Zhang, Jinmeng Rao, Steven Zheng, Daiyi Peng, Diyi Yang, Denny Zhou, Andrew M. Dai* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2404.07503)] 

## Knowledge 

### Knowledge distilltion 
**Propagating Knowledge Updates to LMs Through Distillation** \
*Shankar Padmanabhan, Yasumasa Onoe, Michael Zhang, Greg Durrett, Eunsol Choi*\
NeurIPS 2023. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/932147114c48f8b04d41aebc0c631158-Paper-Conference.pdf)][[Github](https://github.com/shankarp8/knowledge_distillation)]


### Knowledge editing

**A Comprehensive Study of Knowledge Editing for Large Language Models** \
*Ningyu Zhang et al.* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2401.01286)][[Github](https://github.com/zjunlp/easyedit)] [[Github2](https://github.com/zjunlp/knowledgeeditingpapers)]


### Knowledge injection 

**Instruction-tuned Language Models are Better Knowledge Learners** \
*Zhengbao Jiang, Zhiqing Sun, Weijia Shi, Pedro Rodriguez, Chunting Zhou, Graham Neubig, Xi Victoria Lin, Wen-tau Yih, Srinivasan Iyer* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2402.12847)] 

**Instruction Tuning with Human Curriculum** \
*Bruce W. Lee, Hyunsoo Cho, Kang Min Yoo*  \
arXiv 2024. [[Paper](https://arxiv.org/abs/2310.09518)]

**Injecting New Knowledge into Large Language Models via Supervised Fine-Tuning** \
*Nick Mecklenburg, Yiyou Lin, Xiaoxiao Li, Daniel Holstein, Leonardo Nunes, Sara Malvar, Bruno Silva, Ranveer Chandra, Vijay Aski, Pavan Kumar Reddy Yannam, Tolga Aktas, Todd Hendry* \
arXiv 2024. [[Paper](https://arxiv.org/abs/2404.00213)]

**A Knowledge-Injected Curriculum Pretraining Framework for Question Answering** \
*Xin Lin, Tianhuang Su, Zhenya Huang, Shangzi Xue, Haifeng Liu, Enhong Chen* \
WWW 2024. [[Paper](https://arxiv.org/abs/2403.09712)] 

**Plug-and-Play Knowledge Injection for Pre-trained Language Models** \
*Zhengyan Zhang, Zhiyuan Zeng, Yankai Lin, Huadong Wang, Deming Ye, Chaojun Xiao, Xu Han, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou* \
ACL 2023. [[Paper](https://arxiv.org/abs/2305.17691)][[Github](https://github.com/thunlp/knowledge-plugin)]

**KnowGPT: Knowledge Injection for Large Language Models** \
*Qinggang Zhang, Junnan Dong, Hao Chen, Daochen Zha, Zailiang Yu, Xiao Huang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2312.06185)]

**Revisiting the Knowledge Injection Frameworks** \
*Peng Fu, Yiming Zhang, Haobo Wang, Weikang Qiu, Junbo Zhao* \
EMNLP 2023. [[Paper](https://arxiv.org/abs/2311.01150)]

**Injecting Domain Knowledge in Language Models for Task-Oriented Dialogue Systems** \
*Denis Emelin, Daniele Bonadiman, Sawsan Alqahtani, Yi Zhang, Saab Mansour* \
EMNLP 2022. [[Paper](https://arxiv.org/abs/2212.08120)] [[Github](https://github.com/amazon-research/domain-knowledge-injection)]



## Resources 

*Awesome LLMs Fine-Tuning* \
https://github.com/Curated-Awesome-Lists/awesome-llms-fine-tuning 

*How to Fine-Tune LLMs in 2024 with Hugging Face* \
https://www.philschmid.de/fine-tune-llms-in-2024-with-trl 

*Huggingface Blog* \
https://huggingface.co/blog

*Instruction Tuning: What is fine-tuning?* \
https://datascientest.com/en/instruction-tuning-what-is-fine-tuning#:~:text=Whereas%20supervised%20fine%2Dtuning%20consists,more%20easily%20to%20new%20tasks.

*SOTA Knowledge Injection?* 
https://www.reddit.com/r/LocalLLaMA/comments/1as5bn4/sota_knowledge_injection/
https://www.reddit.com/r/LocalLLaMA/comments/1ao2bzu/best_way_to_add_knowledge_to_a_llm/
https://www.youtube.com/watch?v=xz-HRZhjkWk

*Battling LLM Hallucinations in Biomedicine: The Role of Knowledge Graphs in Knowledge Injection Techniques*
https://www.wisecube.ai/blog/battling-llm-hallucinations-in-biomedicine-the-role-of-knowledge-graphs-in-knowledge-injection-techniques/

<!-- course
https://github.com/aishwaryanr/awesome-generative-ai-guide/blob/main/free_courses/Applied_LLMs_Mastery_2024/week3_finetuning_llms.md
 -->
