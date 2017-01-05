# Bitrise Contribution

[![Slack channel](http://chat.bitrise.io/badge.svg)](http://chat.bitrise.io)

## Wanna jump in? 🏊

> You are eligible for a $25 discount from any of the monthly Bitrise Pro plans forever, if you are a Bitrise step contributor. For example, in case of the plan with 1 concurrency, which means infinite builds, team members and 45 minutes per build time, it's 50% off every month. Check out the [pricing page](https://bitrise.io/pricing) to see what you can get.

If you don't have any specific idea about what to integrate, but would love to help out, [here you can find requests from the community waiting for you](https://discuss.bitrise.io/tags/contrib-this-feature). You can find the list of already existing integrations on our [integrations page](https://bitrise.io/integrations), to collect some ideas.

Bitrise step contribution means the __development of a step/integration__, and __sharing it in the Bitrise StepLib__. Once you have your Step in the [Bitrise StepLib](https://github.com/bitrise-io/bitrise-steplib) just __add yourself to the [CONTRIBUTORS_LIST.md](https://github.com/bitrise-io/bitrise-contrib/blob/master/CONTRIBUTORS_LIST.md) and send us a Pull Request with it__, and we'll enable the _Contributor Discount_ for your [Bitrise.io](https://www.bitrise.io) account in no time!

*Note: please read the [Abandoned Step policy](https://github.com/bitrise-io/bitrise-steplib#abandoned-step-policy) section in the StepLib. By applying for the discount you accept this policy, and the discount will be active as long as you actively maintain your Step.*


## Get started

0. A step consist of a simple script and a yml, which is the interface of the script `bitrise` works with. Read more about [step development on the Dev Center](http://devcenter.bitrise.io/bitrise-cli/steps/).

1. It's recommended to write your script in any of the following languages: Bash, Ruby, Go. It's possible to use Node.js, or Swift as well if you insist, but these are not likely trivial to use on our Linux VMs at the moment, so please only consider using them in case of OS X specific scripts.

2. Install the [Bitrise CLI](https://github.com/bitrise-io/bitrise) to run your workflows locally and start developing your own step! 🔨 Check out the docs about [using the CLI on the Dev Center](http://devcenter.bitrise.io/bitrise-cli/).

3. If you feel you are ready, shoot `bitrise share` and follow the instructions. Once your step is merged to the Bitrise StepLib, you become a Bitrise step contributor! 🍷

If you have any questions [join the discussion](https://discuss.bitrise.io/)!
