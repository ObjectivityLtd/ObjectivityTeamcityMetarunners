## What is PSCI.teamcityExtensions?

PSCI.teamcityExtensions is a set of TeamCity [metarunners](http://blog.jetbrains.com/teamcity/2013/07/the-power-of-meta-runner-custom-runners-with-ease/) written in Powershell.

They require whole PSCI library installed at TeamCity agent and the agent needs to have Windows OS and Powershell >= 3. See [[Installation]] for details.

Since the metarunners are just wrappers for Powershell functions, this library can also be used in different Continuous Integration servers like Jenkins.

## Examples

![Test Trend](https://github.com/ObjectivityBSS/PSCI.teamcityExtensions/wiki/images/TestTrendReport_output.png)

For a list of available metarunners, see [project wiki](https://github.com/ObjectivityBSS/PSCI.teamcityExtensions/wiki).
