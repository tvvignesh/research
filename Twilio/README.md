## Twilio

### Outline

Supports SMS, Voice, Video, Fax, Chat

### Underlying technology

It is a service. SDK provided in various languages as mentioned here: https://www.twilio.com/docs/libraries

### Reference Links

https://github.com/twilio/twilio-node

https://stackshare.io/stackups/nexmo-vs-plivo-vs-twilio

https://nextjuggernaut.com/blog/sms-voice-api-twilio-vs-nexmo-plivo-sinch-mobile-app-guide/

https://www.twilio.com/voice/pricing/us

https://www.chriskranky.com/competing-twilio-api/

https://getvoip.com/blog/2017/01/05/twilio-vs-nexmo/

### Samples

https://www.twilio.com/docs/quickstart/node 

### Videos

https://www.youtube.com/watch?v=rrx4ux-hChw&list=PLqrz4nXepkz63z1y4-oHfZHWy11gSoAn0

### Pros

1. Powerful & rich APIs
2. Provides separate credentials for development for free
3. Rich ecosystem and not just limited to SMS & Voice
4. Studio available to design interactive flows without much programming
5. Very good customer base - https://customers.twilio.com/

### Cons

1. Speech to Text conversion is not accurate and there is no option currently to use a third party plugin like Google Voice to do the recognition or speak out.
2. Its costlier compared to other services but it offers the quality for the price.
3. India numbers not available (at the time of writing this) and this is an issue since we have to make ISD calls during development & testing.
Have been working on Twilio and will shortly be onboarding my organization to twilio. Had few issues which you can take as a feedback.
4. No ability to pause through text. Rather than having a dedicated pause command in the SDK, it will be good if we could add pauses through twiml.say Right now the only hacky way is to add multiple periods to get the job done temporarily.
5. No ability to control the speed while using twiml.say We are only allowed to pause, but not control the speed which many people were asking for.
6. Ability to extend localization. IVR in many local languages is not supported by Twilio and there is currently no way to extend Twilio to add localization.

### Licence

Commercial, SDKs open source