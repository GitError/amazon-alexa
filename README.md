#  

## Amazon Alexa Skills/ Apps

### Notes

Each Alexa skill is comprised of an “Invocation Name,” which you can think of as your app name, a set of “Intents,” the phrases that map to each intent, and the software that can detect the intent and return an appropriate result.

```python
Alexa, ask "“Invocation Name", "intent"  e.g.

Alexa, ask "nonsmoker", "how many days it's been since I quite"
```

### Notes Building skill steps

1. First we’re going to copy the “Hello, World!” code into Amazon Lambda, which will be responsible for running the code.

2. Next we’re going to set up our skill in the Amazon Alexa Skills Developer Portal, and link our lambda account to that skill.

3. Then we’re going to test using the Amazon service simulator and on an Alexa-enabled device.

4. Lastly, we’ll walk through the steps of customizing your skill to your needs.

[ADDITIONAL RESOURCES](https://bit.ly/alexaskill)

