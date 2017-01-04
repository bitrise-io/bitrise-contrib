# Bitrise Contribution

[![Slack channel](http://chat.bitrise.io/badge.svg)](http://chat.bitrise.io)

Repository to collect projects & ideas for those who want to collaborate, and to track the process on individual projects. If you want to add a new project / idea which you want to work on or you would like to see it happen please create an issue here.

## Wanna jump in? 🏊

For more information about what and how to contribute here, check out our [contribution guidelines](https://github.com/bitrise-io/bitrise-contrib/blob/master/CONTRIBUTION.md). 

> You are eligible for a $25 discount from any of the monthly Bitrise Pro plans forever, if you are a Bitrise step contributor. For example, in case of the plan with 1 concurrency, which means infinite builds, team members and 45 minutes per build time, it's 50% off every month. Check out the [pricing page](https://bitrise.io/pricing) to see what you can get.

To become a Bitrise step contributor, checking out the issues on this repository is a nice way to start. If you don't have any specific idea about what to integrate, but would love to help out, here you can find requests from the community waiting for you. You can find the list of already existing integrations on our [integrations page]([integrate](https://bitrise.io/integrations)), to collect some ideas.

Bitrise step contribution means development of a step/integration, and sharing it in the Bitrise StepLib. Once you have your Step in the [Bitrise StepLib](https://github.com/bitrise-io/bitrise-steplib) just add yourself to the [CONTRIBUTORS_LIST.md](https://github.com/bitrise-io/bitrise-contrib/blob/master/CONTRIBUTORS_LIST.md) and send us a Pull Request with it.

*Note: please read the [Abandoned Step policy](https://github.com/bitrise-io/bitrise-steplib#abandoned-step-policy) section in the StepLib. By applying for the discount you accept this policy, and the discount will be active as long as you actively maintain your Step.*


## Get started

0. A step consist of a simple script and a yml, which is the interface of the script `bitrise` works with. Read more about [step development on the Dev Center](http://devcenter.bitrise.io/bitrise-cli/steps/).

1. It's recommended to write your script in any of the following languages: Bash, Ruby, Go. It's possible to use Node.js, or Swift as well if you insist, but these are not likely trivial to use on our Linux VMs at the moment, so please only consider using them in case of OS X specific scripts.

2. Install the [Bitrise CLI](https://github.com/bitrise-io/bitrise) to run your workflows locally and start developing your own step! 🔨 Check out the docs about [using the CLI on the Dev Center](http://devcenter.bitrise.io/bitrise-cli/).

3. If you feel you are ready, shoot `bitrise share` and follow the instructions. Once your step is merged to the Bitrise StepLib, you become a Bitrise step contributor! 🍷

If you have any questions, create an issue here, join our [public Slack](https://chat.bitrise.io), or ping [us on Twitter](https://twitter.com/bitrise) anytime.
