#  

## Amazon Alexa Skills/ Apps

### Notes

Each Alexa skill is comprised of an “Invocation Name,” which you can think of as your app name, a set of “Intents,” the phrases that map to each intent, and the software that can detect the intent and return an appropriate result.

```python
Alexa, ask "“Invocation Name", "intent"  e.g.

Alexa, ask "nonsmoker", "how many days it's been since I quite"
```

### Building Alexa Skill steps

1. First  copy the “Hello, World!” code into Amazon Lambda, which will be responsible for running the code.

2. Next set up our skill in the Amazon Alexa Skills Developer Portal, and link our lambda account to that skill.

3. Then test using the Amazon service simulator and on an Alexa-enabled device.

Also can be done via GUI in AWS console.
