# Hello, Containers!

This is the code project for the [Hello, Containers!](https://davidpallmann.hashnode.dev/hello-containers) blog post. 

This episode: Containers. In this Hello, Cloud! blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular topic, this should give you a jumpstart.

In this post we'll introduce containers, discuss what they mean to .NET on AWS development, and create a "Hello, Cloud" Lambda function that uses a container. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. If you've 

## Our Hello, Container Project

We'll use Visual Studio to create a simple "Hello, Lambda" function, deploy it to AWS as a container, and test it. Our Lambda function will take a string as input and return an upper-case version as output. We'll make use of both the Amazon ECR and AWS Lambda services.

The reason we're using a Lambda function is because they're one of the simplest AWS services to set up, which is appropriate for a Hello, World. In subsequent posts, we'll use containers with other services such as ECS and EKS.

See the blog post for the tutorial to create this project and run it on AWS.

