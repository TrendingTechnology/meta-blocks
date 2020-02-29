# Meta-Blocks: A modular toolbox for accelerating meta-learning research
<img src="https://github.com/alshedivat/meta-blocks/blob/master/docs/figs/meta-blocks.png?raw=true" alt="logo" width="400px" style="display: block; margin-left: auto; margin-right: auto"/>


----

**This section is reserved for badges. To add**:

PyPI Badge | Travis CI Badge | Circle CI Badge | docs Badge | Coverage Badge


**Meta-Blocks** is modular toolbox for ...
**[This paragraph should roughly discuss what is the library for:]**

As shown in the Figure below, it contains xxx modules, and each of them can be tailored to ...

 ![System Illustration](https://github.com/alshedivat/meta-blocks/blob/master/docs/figs/system_illustration.png?raw=true)

**Meta-Blocks** is featured for (3-4 highlighted points):

* **Unified APIs, detailed documentation, and interactive examples** across various meta-learning algorithms
* **Advanced and latest models**, such as MAML [1] and Reptile [2]
* **Customizable modules** for quick prototyping on new meta-learning algorithms
* **Change the bullet points above** and add more (should have around 4 points)

**Key Links and Resources**:


* [View the latest codes on Github](https://github.com/yzhao062/pyod)
* [Execute Interactive Jupyter Notebooks]()
* [Documentation and APIs]()

---

### Installation


It is recommended to use **pip** for installation. Please make sure
**the latest version** is installed, as **meta-blocks** is updated frequently:


```shell
   pip install meta-blocks            # normal install
   pip install --upgrade meta-blocks  # or update if needed
   pip install --pre meta-blocks      # or include pre-release version for new features
```

**Required Dependencies**\ :

* albumentations
* hydra-core
* numpy
* Pillow
* scipy
* scikit-learn
* tensorflow>=2.1


---

### Example

We should provide a minimal example so people could run immediately. Ideally the running time should be within a few mins.


----


### Development Status


**Meta-Blocks** is currently **under development** as of Feb, 2020.

**Watch & Star** to get the latest update! Also feel free to contact for suggestions and ideas.

----

### Citing Meta-Blocks

**Meta-Blocks** paper can be accessed [here]().
If you use Meta-Blocks in a scientific publication, we would appreciate citations to the following paper (to be fixed):

```
    @inproceedings{zhao2020combo,
      title={Combining Machine Learning Models and Scores using combo library},
      author={Zhao, Yue and Wang, Xuejian and Cheng, Cheng and Ding, Xueying},
      booktitle={Thirty-Fourth AAAI Conference on Artificial Intelligence},
      month = {Feb},
      year={2020},
      address = {New York, USA}
    }
```

or

```
    Zhao, Y., Wang, X., Cheng, C. and Ding, X., 2020. Combining Machine Learning Models and Scores using combo library. Thirty-Fourth AAAI Conference on Artificial Intelligence.
```

----


### Reference

[1] Finn, C., Abbeel, P. and Levine, S., 2017, August. Model-agnostic meta-learning for fast adaptation of deep networks. *ICML*.

[2] Nichol, A., Achiam, J. and Schulman, J., 2018. On first-order meta-learning algorithms. arXiv preprint arXiv:1803.02999.