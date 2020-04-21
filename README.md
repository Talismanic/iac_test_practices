# iac_test_practices
We have analysed 50 internet artifacts and identified that Infrastructure as Code(IIaC) practitioners recommended for different practices for testing IaC scripts. We have been able to categorize those and find 6 broad categories of IaC testing best practices. Here we are providing the list of internet artifacts which we have examined and the practices identified in each of the artifact.

| SL | Type  | Link  | Remote Testing | Sandbox Testing | Avoiding Coding Anti-Patterns | Test Every Change | Behavior focused test coverage | Use of Automation Tool |
|----|-------|-------|----------------|-----------------|-------------------------------|-------------------|---------------------------------------|------------------------|
| 1 | Blog | [Link](https://www.ansible.com/blog/five-questions-testing-ansible-playbooks-roles)|0|1|0|1|0|0|
| 2 | Blog | [Link](https://far-oeuf.com/ansible/unit-testing-roles-continuous-integration)|0|0|1|1|0|0|
| 3 | Github Repo | [Link](https://github.com/aelsabbahy/goss)|0|0|0|0|0|0|
| 4 | StackOverflow | [Link](https://stackoverflow.com/questions/38313220/how-to-do-unittesting-in-ansible)|0|0|0|0|0|1|
| 5 | Github Repo | [Link](https://github.com/ryotarai/infrataster)|0|0|0|0|0|0|
| 6 | StackOverflow | [Link](https://stackoverflow.com/questions/36998112/how-to-automatically-test-configuration-managing-scripts)|0|1|1|1|0|1|
| 7 | Github Repo | [Link](https://github.com/ansible/molecule)|0|0|0|0|0|0|
| 8 | Blog | [Link](https://www.digitalocean.com/community/tutorials/how-to-test-ansible-roles-with-molecule-on-ubuntu-16-04)|0|1|0|0|1|1|
| 9 | Blog | [Link](https://itnext.io/testing-ansible-roles-a-practical-application-2afc96e0d7d)|0|0|0|0|0|1|
| 10 | Video | [Link](https://youtu.be/NgwosUBuRAc)|0|1|0|0|1|1|
| 11 | Blog | [Link](https://www.jeffgeerling.com/blog/2018/testing-your-ansible-roles-molecule)|1|1|0|1|0|1|
| 12 | Blog | [Link](https://stackoverflow.com/questions/50371158/test-ansible-roles-with-molecule-and-boto3/50662905)|0|0|0|0|0|0|
| 13 | Blog | [Link](https://stackoverflow.com/questions/36610184/should-ansible-compile-and-test-code-before-deployment-or-should-it-only-deploy)|0|0|0|1|0|0|
| 14 | Blog | [Link](https://zapier.com/engineering/ansible-molecule/)|0|1|0|1|0|1|
| 15 | Blog | [Link](https://blog.codecentric.de/en/2018/12/test-driven-infrastructure-ansible-molecule/)|1|0|1|1|0|1|
| 16 | Video | [Link](https://youtu.be/RTEgE2lcyk4)|0|1|1|0|0|1|
| 17 | Video | [Link](https://www.youtube.com/watch?v=c21VnhhQYNQ&t=1191s)|0|1|1|1|0|0|
| 18 | Blog | [Link](https://medium.com/devops-process-and-tools/testing-ansible-playbooks-roles-8992e3eddc2)|0|1|1|0|0|1|
| 19 | Blog | [Link](https://medium.com/holisticon-consultants/using-molecule-and-docker-to-test-ansible-playbooks-63d75dbffbe6)|0|1|0|0|0|1|
| 20 | Blog | [Link](https://pushbuildtestdeploy.com/testing-your-ansible-deployments-with-molecule/)|0|1|0|0|1|1|
| 21 | Blog | [Link](https://www.toptechskills.com/ansible-tutorials-courses/rapidly-build-test-ansible-roles-molecule-docker/)|0|0|1|0|1|0|
| 22 | Blog | [Link](https://robertdebock.nl/testing.html)|1|1|0|1|1|1|
| 23 | SlideShare | [Link](https://www.slideshare.net/BobKillen/ansible-integration-testing-and-you)|0|1|0|0|0|1|
| 24 | Blog | [Link](https://www.flux7.com/blog/using-molecule-for-test-driven-development-of-ansible-roles/)|0|0|1|0|0|1|
| 25 | Blog | [Link](https://www.darkraiden.com/blog/test-kitchen-lets-shake-this-role-up/)|0|1|1|0|1|1|
| 26 | Blog | [Link](http://targetveb.com/kitchenci-ansible-unit-tests-docker-inspec.html)|0|0|0|0|0|0|
| 27 | Blog | [Link](https://hobo.house/2019/08/05/how-to-setup-travis-for-quick-ansible-playbook-ci/)|0|0|0|1|0|0|
| 28 | Blog | [Link](https://www.stackovercloud.com/2019/02/07/how-to-implement-continuous-testing-of-ansible-roles-using-molecule-and-travis-ci-on-ubuntu-18-04/)|0|1|0|1|0|1|
| 29 | Blog | [Link](http://www.juliosblog.com/ansible-and-ansible-tower-best-practices-from-the-field/)|0|1|0|1|1|0|
| 30 | Blog | [Link](https://blog.ragnarson.com/2017/03/13/inspec-inspect-your-infrastructure.html)|0|0|1|0|0|1|
| 31 | Blog | [Link](https://werner-dijkerman.nl/2017/09/17/continuous-deployment-of-ansible-roles/)|0|0|0|1|1|1|
| 32 | Blog | [Link](https://opensourceforu.com/2018/01/unit-testing-ansible-code-molecule-docker-containers/)|0|1|0|0|1|1|
| 33 | Blog | [Link](https://dzone.com/articles/ansible-tdd-development-using-molecule)|0|1|0|1|1|1|
| 34 | Blog | [Link](https://hashbangwallop.com/tdd-ansible.html)|0|0|1|1|0|1|
| 35 | Blog | [Link](https://blog.octo.com/the-wizard-ansible-molecule-and-test-driven-development/)|0|1|1|0|1|1|
| 36 | Blog | [Link](https://blog.octo.com/test-your-infrastructure-code-with-terratest/)|1|1|0|0|1|1|
| 37 | Blog | [Link](https://medium.com/faun/building-repeatable-infrastructure-with-terraform-and-ansible-on-aws-3f082cd398ad)|0|0|0|0|0|0|
| 38 | Blog | [Link](https://developer.rackspace.com/blog/molecule-for-ansible-role-creation/)|0|0|0|0|1|1|
| 39 | SlideShare | [Link](https://hashman.ca/ansiblefest-2017/ansiblefest-2017-ehashman.pdf)|0|0|0|1|0|1|
| 40 | Blog | [Link](https://habrahabr.info/development/testing-of-it-systems/703-testing-and-continuous-integration-for-ansible-roles-using-molecule-and-jenkins.html)|0|0|0|1|0|1|
| 41 | Blog | [Link](https://infocus.dellemc.com/bart_driscoll/unlock-the-benefits-of-cloud-platforms-and-automation-with-iac/)|0|0|1|1|0|0|
| 42 | Blog | [Link](https://blog.sensu.io/infrastructure-as-code-testing-and-monitoring)|0|0|0|1|1|1|
| 43 | Blog | [Link](https://puppet.com/blog/hitchhikers-guide-to-testing-infrastructure-as-and-code/)|0|0|0|0|0|0|
| 44 | SlideShare | [Link](https://www.slideshare.net/opencredo/london-hashicorp-meetup-8-testing-programmable-infrastructure-by-matt-long)|0|0|0|0|0|1|
| 45 | Blog | [Link](https://adamtheautomator.com/chef-test-kitchen/)|0|1|0|1|0|1|
| 46 | Blog | [Link](https://brigade.engineering/reduce-chef-infrastructure-integration-test-times-by-75-with-test-kitchen-and-docker-bf638ab95a0a)|0|1|0|0|0|1|
| 47 | SlideShare | [Link](https://www.slideshare.net/brikis98/how-to-test-infrastructure-code-automated-testing-for-terraform-kubernetes-docker-packer-and-more)|0|1|1|1|1|1|
| 48 | Blog | [Link](https://iyarweb.wordpress.com/2018/12/11/continuous-infrastructure-with-ansible-molecule-travisci/)|0|0|0|1|1|1|
| 49 | Blog | [Link](https://www.devopsonline.co.uk/a-shift-of-testing-code-to-testing-infrastructure-as-code/)|0|0|0|0|1|1|
| 50 | Blog | [Link](https://habr.com/en/post/467169/)|0|1|1|1|1|1|
