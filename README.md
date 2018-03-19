# ISLR-with-Python

**2018-03-19**
There are many errors in this repository. Please be careful when using these resources for your study. For example, I did not carefully preprocessed training/test data set. You should not use test set's information in preprocessing test set. So, you should use below code for preprocessing data.

```python
from sklearn.preprocessing import StandardScalar
sc = StandardScaler()
X_train_sc = sc.fit_transform(X_train)
X_test_sc = sc.transform(X_test)
```

And there are also a lot many other errors in these notebooks but i don't have enough time right now to fix those errors. If you were able to find and fix errors, please send me a pull request or email.

* **Practice**
    * [Chapter3 - Practice](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter3%20-%20Practice.ipynb)
    * [Chapter4 - Practice](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter4%20-%20Practice.ipynb)
    * [Chapter5 - Practice](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter5%20-%20Practice.ipynb)
    * [Chapter6 - Practice](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter6%20-%20Practice.ipynb)
    * [Chapter7 - Practice](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter7%20-%20Practice.ipynb)

* **Exercise**
    * [Chapter2 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter2%20-%20Exercise.ipynb)
    * [Chapter3 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter3%20-%20Exercise.ipynb)
    * [Chapter4 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter4%20-%20Exercise.ipynb)
    * [Chapter5 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter5%20-%20Exercise.ipynb)
    * [Chapter6 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter6%20-%20Exercise.ipynb)
    * [Chapter7 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter7%20-%20Exercise.ipynb)
    * [Chapter8 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter8%20-%20Exercise.ipynb)
    * [Chapter9 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter9%20-%20Exercise.ipynb)
    * [Chapter10 - Exercise](https://nbviewer.jupyter.org/github/belepi93/ISLR-with-Python/blob/master/Notebooks/Chapter10%20-%20Exercise.ipynb)

### English
This repository contains Jupyter notebooks for personal study of [Introduction to Statistical Learning with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/index.html). My notebooks consist of two parts, Practice and Exercise. Practice notebooks and contents in Data folder are mainly from JWarmenhoven's [ISLR-python](https://github.com/JWarmenhoven/ISLR-python) repository. But those notebooks contain some deprecated modules and some errors so i tried to fix codes which are not working properly. Also, I have included a lot more codes for Figures which are not in JWarmenhoven's notebooks but seemed important to me.

I have uploaded Python solutions for *applied exercises* in the book. There are many R codes for applied exercises but it's very difficult to find Python codes for these exercise problems. There are some new data sets which are not in JWarmenhoven's. So, I hope these notebooks would be helpful for your studies.

If there are some technical or license problems to this repository, please let me know immediately. Also, if you have any better idea for codes, I would be very grateful for any feedback.

Thank You!


**2018/1/28:**

-Added **Chapter10 - Exercise**

### Korean
이 깃허브 저장소는 [가볍게 시작하는 통계학습(Introduction to Statistical Learning with Applications in R)](http://www-bcf.usc.edu/~gareth/ISL/index.html)을 파이썬으로 공부하며 작성한 주피터 노트북 파일들 저장하기 위해 만들었습니다. 파일들은 크게 두 부분으로 나누어져 있는데, practice 노트북과 Data 폴더에 있는 자료들은 JWarmenhoven의 [ISLR-python](https://github.com/JWarmenhoven/ISLR-python) 저장소를 보고 공부하며 작성하였습니다. 대부분이 일치하지만, JWarmenhoven의 코드가 오래되어 더 이상 사용되지 않는 모듈을 다루고 있거나 제대로 작동하지 않는 부분을 포함하고 있어 그 부분을 수정하였고, JWarmenhoven이 다루지 않은 여러 그래프들을 그리기 위한 코드를 추가로 작성하여 업로드하였으니 공부하시는 데에 도움이 될 것입니다.

또, 이 깃허브 저장소에는 ISLR에 포함된 실습(Applied) 연습문제들을 위한 주피터 노트북 파일과 데이터 셋을 업로드했습니다. 인터넷 상에 연습문제를 위한 R 코드는 많지만 파이썬으로 작성한 솔루션은 찾기가 힘들었기에 이 파일들이 여러분들의 공부에 도움이 되었으면 합니다.

코드에 문제가 있거나 작성한 코드에 라이센스 문제가 있다면 알려주시면 감사하겠습니다. 또, 코드에 비효율적인 부분이 있거나 개선할 부분이 있다면 언제든 피드백을 주시면 감사하겠습니다.

**2018/1/28:**

**Chapter10 - Exercise**를 업로드하였습니다.