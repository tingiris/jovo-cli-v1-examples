# JOVO-CLI Examples

**Prerequisites:**
<br/>
Installed ASK CLI 
[QuickStart](https://developer.amazon.com/docs/smapi/quick-start-alexa-skills-kit-command-line-interface.html)


## jovo new \<project>

Creates a new project based on the 'helloWorld' template.

```sh
$ jovo new <project> [--platform <alexaSkill|googleAction|none> [--locale <en-US>]
```


**Options:**

**--platform [alexaSkill|googleAction|all|none]** - Default: none
<p>
Initializes platform specific folders in the project directory.
</p>
<br/>

**--locale [en-US]** - Default: en-US
<p>
  Locale of the skill. Creates an empty i18n file and the the language model.
</p>

### Example1

```sh
$ jovo new example1
```
Creates simple project without the the platform specific folder structure. (See [example1 project](https://github.com/aswetlow/jovo-cli-v1-examples/tree/master/example1))
[![Jovo Framework](https://www.swetlow.de/example1_folderstructure.jpg)]

### Example2

```sh
$ jovo new example2 --platform alexaSkill
```
Creates simple project with Alexa specific folder structure. (See [example2 project](https://github.com/aswetlow/jovo-cli-v1-examples/tree/master/example2))
[![Jovo Framework](https://www.swetlow.de/example2_folderstructure.jpg)]
