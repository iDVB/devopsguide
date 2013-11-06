
Continuous Integration, Immutible Infrastructure and other Superpowers
=============================================================================
An epic title, but to be fair, [Continuous Integration][ContinuousIntegration] and [Immutable Infrastructure][ImmutableInfrastructure] are revolutionizing the way development companies do business. At every stage from concept to creation, they can exponentially increase efficiency, audibility, while lowering resourcing costs, maintenance costs, and time-to-market. Ultimately answering one of the most pressing questions we face as story scapers: *When somebody thinks of a great idea, how do we deliver it to clients/users as quickly and efficiently as possible?*


## Common Release Antipatterns
> "In many software projects, release is a manually intensive process. The environments 
that host the software are often crafted individually, usually by an operations or 
IS team. Third-party software that the application relies on is installed.
The software artifacts of the application itself are copied to the production host 
environments. Configuration information is copied or created through the admin 
consoles of web servers, applications servers, or other third-party components
of the system. Reference data is copied, and ﬁnally the application is started,
piece by piece if it is a distributed or service-oriented application. 

> The reason for the nervousness should be clear: There is quite a lot to go wrong
in this process. If any step is not perfectly executed, the application won’t run 
properly. At this point it may not be at all clear where the error is, or which step
went wrong." 

> - *Book: [Continuous Delivery][ContinuousDelivery]* 

## Continuous Integration
<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>

### GIT
[GIT][GIT], [GitHub][GitHub], [GitLabs][GitLabs], [GitHubEnterprise][GitHubEnterprise] 
<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>

### CI Testing and Deployment Tools
[TravisCI][TravisCI], [CodeShip][CodeShip], [JenkinsCI][JenkinsCI]
<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>

## Immutiable Infrastructure
<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>
The system becomes a house of cards. You fear any change and you fear replacing 
it since you don’t know everything about how it works.
If you absolutely know a system has been created via automation and never 
changed since the moment of creation, most of the problems described above 
disappear. Need to upgrade? No problem. Build a new, upgraded system and 
throw the old one away. New app revision? Same thing. Build a server 
(or image) with a new revision and throw away the old ones.

### Cloud Hosting: Amazon Web Services
[AWS][AWS] [OpsWorks][OpsWorks]
<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>


### Chef
[Chef][Chef] is an automation platform that transforms infrastructure into code. Stop thinking in terms of physical and virtual servers. With Chef, your real asset is the code that brings those servers and the services they provide to life. An automated infrastructure can accelerate your time to market, help you manage scale and complexity, and safeguard your systems. Chef can automate how you configure, deploy and scale your servers and applications, whether you manage 5 servers, 5,000 servers or 500,000 servers. It's no wonder that Chef has been chosen by companies like Facebook and Amazon for mission-critical challenges.

### Vagrant
[Vagrant][Vagrant] is a tool for building complete development environments. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases development/production parity, and makes the "works on my machine" excuse a relic of the past.

### VirtualBox
[VirtualBox][VirtualBox] is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. Not only is VirtualBox an extremely feature rich, high performance product for enterprise customers, it is also the only professional solution that is freely available as Open Source Software under the terms of the GNU License. Presently, VirtualBox runs on Windows, Linux, Macintosh, and Solaris hosts and supports a large number of guest operating systems including but not limited to Windows (NT 4.0, 2000, XP, Server 2003, Vista, Windows 7), DOS/Windows 3.x, Linux (2.4 and 2.6), Solaris and OpenSolaris, OS/2, and OpenBSD. All PCs in the Sapient Toronto QA Lab are equipped with VirtualBox.

### Packer
[Packer][Packer] is an easy to use automation tool for creating any type of machine image. It embraces modern configuration management by encouraging you to use automated scripts to install and configure the software within your Packer-made images. Packer brings machine images into the modern age, unlocking untapped potential and opening new opportunities. Packer works amazingly in conjunction with [AWS][AWS], [Vagrant][Vagrant], [Chef][Chef] and [VirtualBox][VirtualBox]

## The End of the 'FrontEnd' Developer
You may have heard terms like, 'FrontEnd' or 'HTML' Developer, used in the agency world. Often the term is used by those that do not fully grasp the level of complexity that goes into the today's web experiences or the vast skill-sets required of today's developers. For simplicity, we want to group developers into one of two logical buckets, they are either FE (Frontend) or BE (Backend) Developers. However, there is a good deal of pressure on developers nowadays to be "full-stack" and be able to deliver solutions from CSS to Hardware and Infrastructure. Whether we like it or not, the complexity of the industry is killing the tradition notion of the FrontEnd Developer and the idea of [DevOps][DevOps] is born. 

<span style="color:#D8D8D8;">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse</span>

 It likely will not be long before this term is used very sparingly. With the advent of command line stack of tools like [Yeoman][Yeoman], [Grunt][Grunt], and [Bower][Bower] or the standard use of preprocessors for assets like [Compass][Compass], [LESS][LESS], and [Stylus][Stylus] the skill-sets required start to match the huge effervescences gained by using them. This is not evern to start diving into the plethora of JS library choices available like [JQuery][JQuery], [Prototype][Prototype], [Mootools][Mootools], [Dojo][Dojo], [BackboneJS][BackboneJS], [RequireJS][RequireJS], [AngularJS][AngularJS], [Ext.js][Ext.js], [KnockOutJS][KnockOutJS], [EmberJS][EmberJS], just to name a few.

 If you are a  find yourself saying "It's just a simple CSS/HTML project" . 

### The 'GitHub' Flow
Many in the industry use a various flavors of the [GitFlow][GitFlow] which work well if you are following a strict release based flow. GitHub implements something similar that they call the GitGub flow. This is precisely the type of process you would use is a Continuous Deployment/Integration modal is your direction. For more details on it, you really should read [Scott Chacon's article][GitHubFlow] about it.
> "We can respond to security issues that are brought to our attention or implement small but interesting feature requests incredibly quickly, yet we can use the exact same process to address those changes as we do to handle normal or even large feature development. It’s all the same process and it’s all very simple." - *Scott Chacon: [GitHubFlow][GitHubFlow]*


### Build/Dev Tools 
`✔ Automated` [Yeoman][Yeoman], [Grunt][Grunt], [Bower][Bower]. Automated Preprocessors  [Compass][Compass], [LESS][LESS], [LintJS][LintJS]

### BDD & TDD Tools
`✔ Automated` [Jasmine][Jasmine], [Mocha][Mocha], Behaviour Driven Testing & Development Tools

### Frontend Userflow testing
`✔ Automated` [CasperJS][CasperJS], [PhantomJS][PhantomJS], [SlimmerJS][SlimmerJS]

## Books
- [Instant Chef Starter][InstantChefStarter]
- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation][ContinuousDelivery]


## Videos 
- [Automated Infrastructure is on the Menu with Chef][AutomatedChef]
- [Immunitible Infrastructure Talk with Chad Fowler][ImmunitibleInfraWChadFowler]

## Articles
- [Trash Your Servers and Burn Your Code: Immutable Infrastructure and Disposable Components][TrashYourServers] `Chad Fowler`
- [Immutable Infrastructure][CodeshipImmutableInfrastructure] `Codeship`
- [Deployment Pipelines and Zero Downtime Deployment][DeploymentPipelines] `Codeship`
- [The 'GitHub' Flow][GitHubFlow]
- [GitFlow][GitFlow]
- [DevOps Toolbox][DevOpsToolbox]

## Tutorials
- [#LEARNCHEF][#LEARNCHEF]

<!-- ## Immuniable Infra Tools -->
[Chef]: http://www.opscode.com/chef/
[Puppet]: http://puppetlabs.com/
[Packer]: http://www.packer.io/
[Vagrant]: http://www.vagrantup.com/
[VirtualBox]: https://www.virtualbox.org/
[AWS]: http://aws.amazon.com/
[OpsWorks]: http://aws.amazon.com/opsworks/

<!-- ## Version Control / Deployment -->
[GIT]: http://git-scm.com/
[GitHub]: https://github.com/
[GitLabs]: http://gitlab.org/
[GitHubEnterprise]: https://enterprise.github.com/

<!-- ## Continuious Deployment/Delivery Tools -->
[TravisCI]: http://travis-ci.com/
[CodeShip]: http://codeship.io/
[JenkinsCI]: http://jenkins-ci.org/

<!-- ## CommandLine Automation Tools -->
[Grunt]: http://gruntjs.com/
[Bower]: http://bower.io/
[Yeoman]: http://yeoman.io/

<!-- ## Development Preprocessors -->
[Compass]: http://compass-style.org/
[LESS]: http://lesscss.org/
[Stylus]: http://learnboost.github.io/stylus/

<!-- ## Development Frameworks/Libraries/Languages -->
[BackboneJS]: http://backbonejs.org/
[RequireJS]: http://requirejs.org/
[NodeJS]: http://nodejs.org/
[ExpressJS]: http://expressjs.com/
[NPM]: https://npmjs.org/

<!-- ## Testing Frameworks & Tools -->
[Jasmine]: http://pivotal.github.io/jasmine/
[Mocha]: http://visionmedia.github.io/mocha/
[LintJS]: LintJS
[CasperJS]: http://casperjs.org/
[PhantomJS]: http://phantomjs.org/
[SlimmerJS]: http://slimerjs.org/

<!-- ## Example Applications -->
[Rendr]: https://github.com/airbnb/rendr
[Ghost]: https://ghost.org/features/



<!-- ## Books -->
[InstantChefStarter]: http://techbus.safaribooksonline.com/book/operating-systems-and-server-administration/9781782163466
[ContinuousDelivery]: http://techbus.safaribooksonline.com/book/software-engineering-and-development/software-testing/9780321670250

<!-- ## Articles -->
[GitFlow]: https://www.atlassian.com/git/workflows#!workflow-gitflow
[GitHubFlow]: http://scottchacon.com/2011/08/31/github-flow.html
[TrashYourServers]: http://chadfowler.com/blog/2013/06/23/immutable-deployments/
[ContinuousDelivery]: http://techbus.safaribooksonline.com/book/software-engineering-and-development/software-testing/9780321670250
[DeploymentPipelines]: http://blog.codeship.io/2013/08/30/the-codeship-workflow-part-3-deployment-pipelines.html
[CodeshipImmutableInfrastructure]: http://blog.codeship.io/2013/09/06/the-codeship-workflow-part-4-immutable-infrastructure.html
[DevOpsToolbox]: http://chrislaco.com/devops-toolbox/introduction/

<!-- ## Videos --> 
[AutomatedChef]: http://techbus.safaribooksonline.com/video/operating-systems-and-server-administration/9781449396497?bookview=overview
[ImmunitibleInfraWChadFowler]: http://foodfightshow.org/2013/07/immutable-infrastructure.html

<!-- ## Tutorials -->
[#LEARNCHEF]: https://learnchef.opscode.com

<!-- ## INDEX -->
[DevOps]: http://en.wikipedia.org/wiki/DevOps
[ContinuousIntegration]: http://en.wikipedia.org/wiki/Continuous_integration
[ImmutableInfrastructure]: http://chadfowler.com/blog/2013/06/23/immutable-deployments/




