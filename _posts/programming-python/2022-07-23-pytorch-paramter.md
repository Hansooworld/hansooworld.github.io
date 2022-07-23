---
# layout: "archive"
# permalink: "paper-rl/"
title:  "[Pytorch] 모델 파라미터 접근 & 설정 방법"
excerpt: "기본 MLP 구조를 통하여 모델 파라미터를 어떻게 설정하고 접근하는지 알아보자"

author_profile: true
sidebar:
  nav: "docs"
categories:
  - programming-python
tags:
  - pytorch
  - python

toc: true
toc_sticky: true
 
date: 2022-07-23
last_modified_at: 2022-07-23
---
### 모델 파라미터

Pytorch의 모듈을 통해 모델을 생성할 경우 여러 방식으로 파라미터들을 설정할 수 있을 것이다.

    import torch.nn as nn
    class MLP(nn.Module):
        def __init__(self):
            super(MLP, self).__init__()
