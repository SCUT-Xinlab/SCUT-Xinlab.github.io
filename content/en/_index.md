---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    design:
      css_class: "custom-hero"
      columns: "1"
    content:
      # title: "张鑫"
      image:
        filename: "person.png"
      text: |
        <div class="text-content">
        <h2>张鑫</h2>
        <p>现任 <strong>华南理工大学电子与信息学院人工智能系主任、院长助理，未来技术学院脑科学研究中心副主任</strong>。研究方向包括
        <span>机器学习</span>、<span>计算机视觉</span>、<span>智能人机交互</span> 和 <span>脑影像数据处理</span> 等。</p>
        <p>本科毕业于 <strong>西北工业大学自动化学院</strong>，硕士和博士学位于 <strong>美国俄克拉荷马州立大学电子与计算机学院</strong>。
        2018年-2020年获 <strong>国家留学基金委员会公派访问学者项目</strong> 资助，在
        <strong>美国北卡罗莱纳州立大学教堂山分校</strong>
        医学院数字影像中心访学，研究基于机器学习的
        <span>婴幼儿脑影像</span> 及 <span>发育疾病分析</span> 等。</p>
        </div>


  
  - block: collection
    content:
      title: '📣 最新消息'
      subtitle:
      text:
      count: 4
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: '📑 最新论文'
      text: ""
      count: 4
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'


  - block: markdown
    content:
      title: '🚀 实验室招新'
      subtitle: ''
      text: |-
        实验室的研究方向包括但不限于：计算机视觉、机器学习、医学数据分析（影像、病理、基因、病例等各种数据）、多模态大模型等。

        我们欢迎新同学的加入，要求如下：

        - 热爱钻研、目标明确、自律自驱
        - 对人工智能领域的研究充满兴趣
        - 具有一定的项目经验以及编程能力

        感兴趣的同学可以通过邮件发送个人简历：[点击这里发送邮件](mailto:eexinzhang@scut.edu.cn) 😃
    design:
      columns: '1'
      # background:
      #   color: white

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="实验室成员 →" %}}
    design:
      columns: '1'
---
