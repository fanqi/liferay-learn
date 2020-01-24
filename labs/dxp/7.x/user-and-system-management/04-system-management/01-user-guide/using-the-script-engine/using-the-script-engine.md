# Using the Script Engine

DXP provides a robust script engine for executing [Groovy](http://groovy-lang.org/) scripts to maintain your Liferay DXP instance. The 
Script Console is available in the Control Panel. You can execute scripts to perform maintenance tasks involving data cleanup, user maintenance operations, bulk Liferay API invocations, or even system level operations.

![Figure 1: The Script Console provides context variables, such as the current actionRequest and lets you invoke Liferay services using Groovy. ](./using-the-script-engine/images/groovy-script-current-user-info.png)

Here are the scripting topics: 

- [Invoking Liferay services](./invoking-liferay-services-from-scripts.md)

- [Running scripts from the Script Console](./running-scripts-from-the-script-console.md)

- [Using the script engine with workflow](./using-the-script-engine-in-workflow.md)

- [Script examples](./script-examples.md)

It's very common to use Liferay services in scripts, so it's covered first. 