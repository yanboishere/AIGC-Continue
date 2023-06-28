# AIGC Mind Map

## Give AIGC a question,Output a set of mind maps for you.
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

    1.Reliability and Performance: Look for a provider with a strong track record of reliability and consistent performance. Consider their uptime guarantees, service level agreements (SLAs), and the availability of redundant infrastructure to minimize downtime.
    
    2.Security and Compliance: Ensure that the cloud service provider has robust security measures in place to protect your data and meet your compliance requirements. Look for certifications like ISO 27001 and SOC 2, and inquire about their data encryption, access controls, and backup policies.
    
    3.Scalability and Flexibility: Assess whether the provider can scale their services to meet your changing needs. Consider the availability of different service models (e.g., Infrastructure as a Service, Platform as a Service) and deployment options (public, private, hybrid) that align with your business objectives.
    
    4.Cost and Pricing Model: Evaluate the pricing structure of the cloud service provider. Consider factors such as upfront costs, ongoing operational expenses, any additional fees for data transfer or storage, and potential cost savings based on usage patterns.



[After personal testing, in the process of information extraction, the information returned is a long piece of text, and it is difficult to extract one by one from it at this stage

So we now choose to only generate answers with clear 1. 2. 3. in the returned information]


