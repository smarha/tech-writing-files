https://github.com/just-ai/aimybox-android-sdk/wiki/Android-Custom-Skills

> _For example, a custom skill could launch some activity or perform some actions in the user's local network._

For example, a custom skill could launch an activity or perform actions within the user's local network.


> This method will be called by Aimybox service right after the user's speech was recognised. Custom Skill can add some additional data to the Request that will be sent to the configured dialog API then.

This method will be called by the Aimybox service right after the user's speech **is recognized**. Custom Skill can add additional data to the Request that will be sent to the configured dialog API.


> This method should return `true` if your custom skill can handle a particular [Response](https://github.com/just-ai/aimybox-android-sdk/blob/master/core/src/main/java/com/justai/aimybox/model/Response.kt) from the dialog API.
> 
> | As a rule custom skill looks only on the `action` field of `Response` object to determine if it can handle this particular response || If Aimybox service didn't find any custom skill that can handle this response, it just executes the default action - synthesises the speech from this response and continue speech recognition if needed


This method returns `true` if your custom skill can handle a particular [Response](https://github.com/just-ai/aimybox-android-sdk/blob/master/core/src/main/java/com/justai/aimybox/model/Response.kt) from the dialog API. 
As a rule custom skill looks only on the `action` field of `Response` object to determine if it can handle this particular response. [not changed]
If Aimybox service doesn't find any custom skill that can handle this response, it will execute the default action: synthesise the speech from the response and continue speech recognition if necessary.

_________

https://github.com/just-ai/aimybox-android-sdk/wiki/Android-UI-components

> UI components library enables you to easily and very quickly embed ready to use voice assistant into your own Android application or create an all new voice assistant project. 
> This library contains all UI components and complete voice assistant UX implementation used by Just AI in many voice driven projects.


UI components library enables you to easily and very quickly integrate ready-to-use voice assistant into your own Android application or create an entirely new voice assistant project.
This library contains all UI components and complete voice assistant UX implementation used by Just AI in numerous voice-driven projects.


> The philosophy of Aimybox is going around the idea that voice assistant can be easily embedded into any application. The same way we can embed an online live chat widget on the website.

The philosophy of Aimybox **revolves around** the idea that **a** voice assistant can be easily embedded into any application. The same way we can embed an online live chat widget on **a** website.


> The voice assistant has some specific UX already known by the most of Android users (thanks to the global leaders like Google Assistant). And this UI/UX patterns should be represented in every voice assistant app to be accepted by users.

The voice assistant has some specific UX already familiar to most Android users (thanks to global leaders like Google Assistant). And these UI/UX patterns must be represented in every voice assistant app to gain user acceptance.


> That's why we've simplified the voice assistant embedding process as much as possible! You have just instantiate an Aimybox service and add an AimyboxAssistantFragment to your layout.


That's why we've simplified the voice assistant embedding process as much as possible! You only need to instantiate an Aimybox service and add an AimyboxAssistantFragment to your layout.


> That is all! If you run such a code you will find a small microphone button in the right bottom corner of the screen. The tap on it launches the assistant's UI that incapsulates all nested processes regarding speech recognition. NLP, UX and speech synthesis.

That's it! When you run the provided code, you'll notice a small microphone button in the bottom right corner of the screen. Tapping on it launches the assistant's UI, which encapsulates all the nested processes related to speech recognition, NLP, UX, and speech synthesis.

______

https://github.com/just-ai/aimybox-android-sdk/wiki/Core-Android-SDK

> If you have to quickly embed and customise a ready to use voice assistant UI into your Android application please use UI components library.

If you need to quickly embed and customize a ready-to-use voice assistant UI into your Android application, please use the UI components library.


> Every Aimybox powered voice assistant should use a speech to text and text to speech components to be able to recognise user's speech to the text and then synthesise the resulting text back to the user.

Every Aimybox-powered voice assistant requires speech-to-text and text-to-speech components to recognize user speech and synthesize responses.


> The user has to activate your voice assistant before speaking with it. It could be a tap on the microphone button or any other way to wake the assistant.

The user must activate your voice assistant before interacting with it. This can be done by tapping the microphone button or through any other way to wake the assistant


> In this case the voice assistant listens for this word or phrase continuously in the background and once the user speaks it - the voice assistant starts to listen the voice command.

In this case, the voice assistant listens continuously in the background for this specific word or phrase. Once the user speaks it, the voice assistant begins listening for the voice command.
_____

https://github.com/just-ai/aimybox-android-sdk/wiki/Quick-Start

> Aimybox is an open source voice assistant that can be embedded into any mobile application. It includes ready to use Android SDK, iOS SDK, HTTP API and assistant UI components for both Android and iOS.

Aimybox is an open-source voice assistant that can be easily integrated into any mobile application. It includes ready-to-use Android SDK, iOS SDK, HTTP API and assistant UI components for both Android and iOS.


>Thus every developer could pick some appropriate components for speech-to-text, text-to-speech and NLU, assemble an Aimybox instance and embed voice capabilities into their application with minimal effort.

Thus every developer can pick appropriate components for speech-to-text, text-to-speech, and NLU, assemble an Aimybox instance, and embed voice capabilities into their application with minimal effort.


> We recommend to start with our [simple tutorial](https://github.com/just-ai/aimybox-android-sdk/wiki/Aimybox-Tutorial) to see how it's easy to build voice assistant using Aimybox and Aimylogic.

We recommend starting with our simple tutorial to see **how easy it is** to build a voice assistant using Aimybox and Aimylogic.


> The easiest way to try Aimybox - is to clone ready to use Android application from Aimybox Github repository.

The easiest way to try Aimybox is to clone the ready-to-use Android application from the Aimybox GitHub repository.


> You have to use some Android IDE to build your app like Android Studio. Then you have just connect any Android device to your PC via USB and click on green play button to build and deploy your voice assistant. A new Android will be launched on your device and you can just tap on the microphone button and say something to see how your assistant reacts.

You will need to use an Android IDE to build your app like Android Studio. Then just connect any Android device to your PC via USB and click on the green play button to build and deploy your voice assistant. A new Android app will be launched on your device, and you can tap on the microphone button and say something to see how your assistant reacts.


> All you need to do next - is to select an appropriate NLU engine and create the voice skills using it. Please refer to the documentation of selected NLU to learn how to create a voice skill.

All you need to do next is select an appropriate NLU engine and create voice skills with it. Please refer to the documentation of the selected NLU engine to learn how to create a voice skill.


> To mix multiple voice skills in the single voice project you can use Aimybox Web console. It also contains a marketplace of ready to use voice skills, so it may be the easiest way to start using Aimybox.

To combine multiple voice skills into a single voice project, you can use the Aimybox Web console. It also features a marketplace of ready-to-use voice skills, so it may be the easiest way to start using Aimybox.


> Once you've created a voice project (using Aimybox Web console or directly on the favourite NLU engine) you have to connect it with your Aimybox powered application.

Once you've created a voice project (using the Aimybox Web console or directly on your favourite NLU engine), you need to connect it to your Aimybox-powered application.


> For example, if you use Aimybox Web console, you have to create an Aimybox channel, copy your Aimybox project's API key and paste it into the Aimybox initialisation block.

For example, if you use the Aimybox Web console, you'll need to create an Aimybox channel, copy your Aimybox project's API key, and paste it into the Aimybox initialisation block.


> Start your application on the device. You will see how Aimybox SDK handles all job regarding speech recognition, speech synthesis and NLU. It also provides a ready to use UI that can be fully customised or replaced with your own.

Start your application on the device. You will see how the Aimybox SDK handles all tasks related to speech recognition, speech synthesis, and NLU. It also provides a ready-to-use UI that can be fully customised or replaced with your own.

