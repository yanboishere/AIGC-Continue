# AIGC Mind Map

## Give AIGC a question,Output a set of mind maps for you.

### [简体中文](https://github.com/yanboishere/AIGC-Mind-Mapping/blob/master/README_cn.md)
---

When we ask the existing AIGC tools to ask them questions, our answers are only 1., 2., 3.

And if you want to understand this question in detail, you will most likely need to ask the AIGC tool separately

"how to do 1." or "1. what"

---

# For example

## 🧠When I ask AIGC tools:

❓**How to use cloud server to deploy web pages?**

❗️It answered that —— you can follow these general steps: **1. 2. 3. 4. ...... 9.** 

<img width="1040" alt="截屏2023-06-28 下午4 10 59" src="https://github.com/yanboishere/AIGC-Continue/assets/76860915/254ca754-92a1-4372-95c7-4eeef3fcaa18">

<br>
<br>


If you are a novice, there is a high probability that you will not get all the answers you want in one inquiry.

---

# How AIGC Mind Map Deal This Problem？
The AIGC mind map will ask you questions that will answer multiple answers. 

Send the question through the API interface of the AIGC platform for inquiry. 

If multiple pieces of information are returned (1. 2. 3 appears in the returned information) . strip) Our platform system began to make mind maps.

## Example

Like the question of **How to use cloud server to deploy web pages?**

The first of the answers given in AIGC （1.） is: 

**Choose a Cloud Service Provider**

And we continue to ask AIGC：**How to Choose a Cloud Service Provider？**

We will receive：

   <img width="1040" alt="截屏2023-06-28 下午5 28 34" src="https://github.com/yanboishere/AIGC-Mind-Mapping/assets/76860915/8159d186-b1cb-4670-8577-0e8018345df3">

123456789 steps......

And Then we will summarize all the generated information into a mind map.

### Test Demo
<img width="748" alt="截屏2023-06-28 下午5 42 10" src="https://github.com/yanboishere/AIGC-Mind-Mapping/assets/76860915/c6324490-0c3c-4f67-a3cf-4fd618557cff">

### Mind Map Demo
<img width="1257" alt="截屏2023-06-28 下午5 49 00" src="https://github.com/yanboishere/AIGC-Mind-Mapping/assets/76860915/d22b59f3-d22e-4755-aa83-db028b9451bf">

                       

[After personal testing, in the process of information extraction, the information returned is a long piece of text, and it is difficult to extract one by one from it at this stage


So we now choose to only generate answers with clear 1. 2. 3. in the returned information]


