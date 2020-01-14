# Workshop Day 1

## Day 1: Kabanero and Appsody for Developers and Operators

* 개발자가 Appsody 를 이용하여 개발을 진행하는 과정과 테스트 사이클을 진행하는 과정에 대하여 배운다. 
그리고, 선호하는 IDE 와 어떻게 연동되는지에 대하여 알아봅니다.  

또한 애플리케이션을 어떻게 OpenShift 에 배포하는지에 대해서 알아봅니다. 먼저 Appsody 를 수동으로 Dev / Test 용도로 이용하는 법에 대해 배우고, 표준 Kabanero Tekton 파이프라인과 지속적인 테스트, 운영 사이클의 일부분인 GitOps 를 이용합니다.  

이번 워크샵의 최종 목적은 아래 기술되어 있으므로, 단계별 연습을 통해 이뤄보도록 하겠습니다.  

![Our end state when Day 1 is done](images/architecture.png)

## Agenda

| Section | Description |
| - | - |
| **[Lecture 1: What is Cloud Native?](https://ibm.box.com/s/3pvl4jdi3xifs1olzcl9np904zvk5ueo)** | Learn about the technologies that underpin Cloud Native applications |
| **[Lecture 2: Kabanero Overview](https://ibm.box.com/s/6jl4b7sj8xqgh7rvxtea5ykpsjyu1siz)** | Learn about Kabanero. An open source project to rapidly create Cloud Native applications |
| **[Exercise 1: Introduction to Appsody and Codewind](../exercise-1/README.md)** | Install the Appsody component of Kabanero into the IDE with Codewind, Learn about the developer flow, building your first application with Appsody |
| **[Exercise 2: Using Appsody CLI to develop, test, and debug applications](../exercise-2/README.md)** | Use the Appsody CLI to quickly create frontend and backend applications for a sample application using two different technologies (Spring and nodejs express) |
| **[Exercise 3: Deploying to OpenShift with Appsody](../exercise-3/README.md)** | Deploy the built applications to IBM Managed OpenShift with Appsody for dev/test purposes |
| **[Lecture 3: Adding value with IBM Cloud Pak for Applications](https://ibm.box.com/s/y4wh104vdos1vw5kdjwwuhebf8jgq580)** | Learn about how IBM Cloud Pak for Applications bundles everything together |
| **[Exercise 4: Use Tekton and Kabanero Pipelines to continuously deploy](../exercise-4/README.md)** | Deploy the built applications to IBM Managed OpenShift using GitOps to trigger a Tekton pipeline |
