---
layout: default
title: github pages �����ܽ�
category: blog
tags: blog
---

# {{page.title}}

��ֹ����Ϊֹ�������������Ĳ��𲩿͵����⣬������ Jekyll ���� Hexo ����ģ���һһ���˴𰸣����ţ�дһƪ���ͣ������ܽ� ��

### ����ǰ��

�� Github ��������һ���ֿ⣬�ֿ�����ʱ����� username.github.io

* Jekyll ���𷽰�

        Jekyll ��һ���򵥵Ĳ�����̬�ľ�̬վ������������ ����һ��ģ��Ŀ¼�����а���ԭʼ�ı���ʽ���ĵ���ͨ��һ��ת��������Markdown��
        �����ǵ� Liquid ��Ⱦ��ת����һ�������Ŀɷ����ľ�̬��վ������Է������κ���ϲ���ķ������ϡ�
��������� github �ķ������Ͼ��У���������Ҫ���Ľ����ǽ��Լ����ļ����� jekyll ���������Ⱦ��Ŀ¼�ṹ push �� github �Ϳ�����
    
    * Jekyll ��Ŀ¼�ṹ
    
            .   
            |--_config.yml>  
            |--_drafts  
                   |--articles1.textile 
                |--articles2.md
            |--_includes
                |--footer.html
                |--header.html
            |--_layouts
                |--default.html
                |--post.html
            |--_posts
                |--2014-06-17-articles1.textile
                |--2014-06-17-articles1.md
            |--_site
            |--index.html
            |--other files
    
    
    ���Ϲ��� jekyll Ŀ¼�ṹ�Ľ��������кܶ࣬�ҾͲ�������׸���ˣ���ĩ���вο����ϡ�
    
    * Jekyll ��������
        * ���Ȼ����_posts���ļ����µ��������£��������������������֯�������ڴ��У����е����µ����ݡ���������site.posts���������ļ����µ����²������site.posts�У���
        * ��μ���_layouts�ļ����µ�����ģ�塣
        * �ٴμ���_includes�ļ����µ�������Ҫ����������ݡ�
        * ������ÿһƪ��Ҫ���������ѡ�������������ģ��������һ��ģ�壬������ǰ���µ����ݡ������Ƚ�����չ�����page����content�����У�Ȼ�����ģ��ı��룬����html�ļ���������һ���������_site�ļ����¡�Ҳ����˵�ڴ���һƪ����ʱ����ʵ�������µ����ݶ��Ѿ�����ȡ�����ˣ���ҲΪ�����໥֮��Ĺ����ṩ�˿��ܡ�
     
    
    �������� jekyll ������Ⱦһƪ����ʱ����������Ҳһ�����أ����� jekyll ֻ�ʺϴ��С�Ͳ��͡� 
    
    * ���� Github Pages ����֧�� Jekyll ��������ֻ��Ҫ���� Jekyll ���ļ�Ŀ¼�ṹ���й��� Github �м��ɣ�����Ҫ�ڱ�����װ Jekyll ��ֻ��Ҫ��ע�� Github�����Խ����ʦ����Ƶ� Jekyll ģ�壬Ȼ�� push �� pull ������¼��ɡ�
        * �½�һ���ļ��У����ҳ�ʼ���ֿ⡣
        * git clone ��� username.github.io �ֿ�
        * ��һ����ʦ��[ģ��](https://github.com/jekyll/jekyll/wiki)��Ȼ��Ž��Լ��ı����ļ���
        * ���Ĵ�ʦ�����ã�push �� Github ��
        
    * ���� username.github.io
    * ��������
        ������ʹ�õ��� Disqus ����ֻ��Ҫע��һ���˺ţ�Ȼ��Ѳ�����븴�Ƶ��Լ��� _layouts ���ģ���оͿ����ˣ���������Ҫע�Ⲽ�֣�����ʹ�� [footer ����](https://sfmonkey.github.io/blog/2016/07/footer.html)�е������˲���

* Hexo ���𷽰�

        Hexo ��һ�����١�����Ҹ�Ч�Ĳ��Ϳ�ܡ� Hexo ʹ��Markdown����������Ⱦ���棩�������£��ڼ����ڣ����������������������ɾ�̬��ҳ��
    
    * ׼������
        * Nodejs
            
            * Windows
                * ǰ��[����](https://nodejs.org/en/)���ذ�װ
            * ubantu
                * sudo apt-get install nodejs
    
    * ��װ Hexo
    
        ����һ���ļ��в���ʼ�����������һЩ�������ģ���ĩ��������ϣ�ע�� npm ��ʹ��λ�ã�һ��Ҫ���㴴�����ļ��У�nodejs �İ�װԴ����Ҫ��������ܳ��ִ���
        
        *  npm install hexo-cli -g
            
            ������ῴ��һ��WARN�����ǲ��õ��ģ��ⲻ��Ӱ���������ʹ�á�
       
        *  npm install hexo --save
        
            Ȼ����ῴ�������д���ˢ��һ��Ѱ��֣�������������һ��Hexo�ǲ����Ѿ���װ����
            
        *  hexo -v        
        *  hexo init
            
            ��ʼ��
        *  npm install
        
            ��װ�������
        *  hexo g
        *  hexo s
            ��������д�http://localhost:4000/������ Hexo ��ɹ�
        
        *  ���� Deployment
            
                git config --global user.name "yourname"
                git config --global user.email "youremail"
        *   ͬ����_config.yml�ļ��У��ҵ�Deployment��Ȼ���������޸�
        
                deploy:
                  type: git
                  repo: git@github.com:yourname/yourname.github.io.git
                  branch: master
        *  npm install hexo-deployer-git --save
            ���ʹ��git��ʽ���в���ִ��npm install hexo-deployer-git --save����װ����Ĳ��
        
        *  Hexo d
        *  hexo d -g
            
            ���𲩿�
        *  username.github.io

���ڸ��������Ȳ�������˵�ˣ������кܶ࣬��ĩ�һḽ�����ϡ�

�������: 
[Git+GitHub+Markdown+Jekyll=Perfect Personal Blog](http://www.devtalking.com/articles/git-gitHub-markdown-jekyll/)
[��δһ���������͡�������Github Pages��Hexo�̳�](http://www.jianshu.com/p/05289a4bc8b2)
[ʷ������ϸ��Hexo���ʹͼ�Ľ̳�](https://xuanwo.org/2015/03/26/hexo-intor/)
[�ĵ�| Hexo](https://hexo.io/zh-cn/docs/)
          