# sychonet.github.io
My personal website for sharing opinions, stories, experiences and ideas. I decided to start this project as I need a place where I can archive all the knowledge and experiences that I'm gaining on a day to day basis. Here, I will also be discussing about some of my original ideas on which I'm currently working or want to work in near future. 
This website is powered by [Jekyll](https://jekyllrb.com/) and hosted on [Github Pages](https://pages.github.com/). I decided to use this stack to start my personal website because there is absolutely no cost associated with it and I have full control over my content which is residing in my git repository. 
To understand the code and folder structure for this project you need to have a basic understanding of some very basic fundamentals about Jekyll and Ruby programming language. You should not take more than a day to understand them from the [official Jekyll docs](https://jekyllrb.com/docs/).

# How to install and run using docker?
I'll add the instructions soon once I finish work on dockerfile for this project.

# How to install and run locally?
To run and test this project locally on your machine you have to clone this project in a directory of your choice and install the latest version of [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Jekyll](https://jekyllrb.com/docs/installation/) on your machine by following steps in the links provided. I recommend that you manage version of Ruby on your machine by using a nice tool [rvm(Ruby Version Manager)](https://rvm.io/). 
Once everything is set change your directory to root folder of project on your personal machine and run following commands on your terminal
```shell
$ bundle install
$ bundle exec jekyll serve
```
After running above command if there is no errors in the output then you will find following lines
```shell
Server address: http://127.0.0.1:4000
Server running... press ctrl-c to stop.
```
Just copy value in `Server address` and paste it in URL bar of your web browser.

# License

MIT License

Copyright (c) 2022 Abhay Joshi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



