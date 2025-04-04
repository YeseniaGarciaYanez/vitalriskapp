<p align="center">
    <a href="https://docs.icure.com/sdks/tutorial/petra/foreword">
        <img alt="icure-your-data-platform-for-medtech-and-ehr" src="./petra_logo.svg" width="500">
    </a>
    <h1 align="center">Petra, your iCure patient-oriented Sample App</h1>
</p>


Petra is a menstrual cycle tracking application that was created by including our [iCure MedTech Typescript SDK](https://github.com/icure/icure-medical-device-js-sdk). Its goal is to give you a concrete example on how to integrate iCure inside your own solution and how to use it to implement your own features. 

Petra is a patient-oriented medical App, allowing patients to manage their menstrual cycle tracking data (CRUD operations) and optionally, share them with their doctor(s). Through our [dedicated tutorial](https://docs.icure.com/sdks/tutorial/petra/foreword), you'll learn the most important concepts of iCure MedTech and how to use / implement them for your solution. 


*This repository contains the code you should have __at the end__ of the tutorial. The initial repository you need to use to start the tutorial can be found [here](https://github.com/icure/icure-medical-device-react-native-app-tutorial-template).*


## Requirements 
Make sure the following tools are installed on your machine: 
- **Yarn Package manager**
- **Ruby**, same version than referenced in the `.ruby-version` file at the root of the template. 
- **XCode**
- **Android Studio**

*Note: XCode and Android Studio are needed in order to run your app on iPhone & Android emulators*

Also, at the root of your project, create a file `.env` and add the following environment variables inside it:
- **EXTERNAL_SERVICES_SPEC_ID**,
- **EMAIL_AUTHENTICATION_PROCESS_ID** and/or **SMS_AUTHENTICATION_PROCESS_ID**,
- **FRIENDLY_CAPTCHA_SITE_KEY**,
- **PARENT_ORGANISATION_ID**

Check out our [dedicated tutorial](https://docs.icure.com/sdks/tutorial/petra/foreword) in order to know what are those information and how to get them.

**WARNING: Without these information, you won't be able to complete an authentication**


## Which technologies are used ?
Petra is a mobile app implemented using React Native. It includes the following technologies: 
- [Typescript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html), as a language
- [Redux](https://redux.js.org/introduction/getting-started), as a state container
- [MMKV](https://github.com/Tencent/MMKV), as a key-value storage
- [FriendlyCaptcha](https://friendlycaptcha.com/), as a CAPTCHA solution


## What includes Petra ? 
Petra showcases you different features of iCure MedTech SDK including: 
- The Sign In / Sign up authentication process
- The creations of [data samples](https://docs.icure.com/sdks/glossary#data-sample), representing the medical data of the patients 
- The use of those data samples for a concrete use case (display in a calendar to follow easily the menstruation cycle)
- The classification of medical data using [medical terminologies](https://docs.icure.com/sdks/glossary#terminologies) like [LOINC](https://loinc.org/), [SNOMED-CT](https://www.snomed.org/), [FHIR](https://www.hl7.org/fhir/), ...
- The management of the patient own data
- ... 

Go to our [tutorial](https://docs.icure.com/sdks/tutorial/petra/foreword) for more information. 


## Do you have a doctor-oriented medical app example ? 
Yes, we offer a sample EHR system application called [PetraCare](https://github.com/icure/icure-ehr-lite-doctor-app) designed specifically for doctors. Additionally, you can leverage our [React boilerplate app](https://github.com/icure/cardinal-sdk-react-js-template) to easily build your own customized application for medical professionals.

## What's next ? 
Check out our [MedTech Documentation](https://docs.icure.com/sdks/tutorial/petra/foreword) and more particularly our [Quick Starts](https://docs.icure.com/sdks/quick-start/), in order to create your own iCure solution in a few minutes! 
