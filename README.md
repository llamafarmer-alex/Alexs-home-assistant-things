🏠 Home Assistant Enthusiast | 🛠️ Automating Home Life

Hello there! 👋 As an avid user of Home Assistant, I'm constantly exploring ways to streamline processes and create more efficient home automation solutions.

### Why Home Assistant?
Home Assistant allows me to integrate various smart devices and services into a unified platform, giving me full control over my home environment. From lighting and climate control to security and entertainment, Home Assistant empowers me to tailor my smart home experience according to my preferences and needs.

### The Birth of My Blueprints
My journey with Home Assistant began out of a desire to simplify the management of my smart home setup. One of the frustrations I encountered was the reliance on a shared calendar to trigger specific home modes, such as Holiday Mode which involves stopping certain daily automations from running. I found myself needing to manually adjust settings to accommodate different scenarios, which led to inefficiencies and inconsistencies in my automation routines.

### Introducing My Blueprints
Driven by the need for a more seamless and automated solution, I decided to create my first two blueprints: [**Calendar Event Trigger On**](https://github.com/llamafarmer-alex/HomeAssistantBlueprints/new/main?filename=README.md#home-assistant-blueprint-calendar-event-trigger-on) and [**Calendar Event Trigger Off**](https://github.com/llamafarmer-alex/HomeAssistantBlueprints/new/main?filename=README.md#home-assistant-blueprint-calendar-event-trigger-off). 

With these blueprints, I aim to simplify the process of managing home modes and automations, making it easier for others in the Home Assistant community to benefit from more streamlined and efficient home automation setups. The current version of the blueprints are for only single calendar events but I am looking to make multiple events supported in the future.


<details>
<summary>Home Assistant Blueprint: Calendar Event Trigger On</summary>

# Home Assistant Blueprint: Calendar Event Trigger On
Trigger an automation based on the start of specific calendar events in Home Assistant.

## Description
This Home Assistant blueprint enables users to create automations triggered by the start of specific calendar events. With this blueprint, users can select a calendar entity and specify the name of the event to trigger the automation. Additionally, users can choose an input boolean to toggle and define additional actions to execute when the event starts. This blueprint provides flexibility and customization for automating tasks based on the start of calendar events.

## Features
Flexible Event Triggering: Trigger automations based on the end of specific calendar events.
Customizable Actions: Define additional actions to perform when the event ends, such as turning off a boolean or executing custom sequences.
Easy Setup: Simply select the calendar entity, specify the event name, and choose the actions to execute.

## Usage
Install this Blueprint in your Home Assistant instance.
Create a new automation using this Blueprint.
Select the calendar entity to monitor and specify the name of the event.
Optionally, choose an input boolean to turn on and define additional actions.
Save the automation and enjoy automated actions based on the end of calendar events!

## Notes
Ensure your calendar events are correctly synchronized with Home Assistant for accurate triggering.
Additional actions will only be executed if specified in the automation configuration.

Enjoy automating your calendar events with ease using the Calendar Event Trigger On blueprint!
</details>

<details>
<summary>Home Assistant Blueprint: Calendar Event Trigger Off</summary>

# Home Assistant Blueprint: Calendar Event Trigger Off
Automate actions based on the end of specific calendar events in Home Assistant.

## Description
This Home Assistant blueprint allows you to trigger automations based on the end of calendar events. You can select a calendar entity to monitor for events and specify the name of the event to trigger the automation. Additionally, you can choose an input boolean to toggle and define additional actions to execute when the event ends.

## Features
Flexible Event Triggering: Trigger automations based on the end of specific calendar events.
Customizable Actions: Define additional actions to perform when the event ends, such as turning off a boolean or executing custom sequences.
Easy Setup: Simply select the calendar entity, specify the event name, and choose the actions to execute.

## Usage
Install this Blueprint in your Home Assistant instance.
Create a new automation using this Blueprint.
Select the calendar entity to monitor and specify the name of the event.
Optionally, choose an input boolean to toggle and define additional actions.
Save the automation and enjoy automated actions based on the end of calendar events!

## Notes
Ensure your calendar events are correctly synchronized with Home Assistant for accurate triggering.
Additional actions will only be executed if specified in the automation configuration.

</details>
