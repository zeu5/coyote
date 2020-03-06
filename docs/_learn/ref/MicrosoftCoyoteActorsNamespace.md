---
layout: reference
section: learn
title: Microsoft.Coyote.Actors
permalink: /learn/ref/MicrosoftCoyoteActorsNamespace
---
## Microsoft.Coyote.Actors namespace

| public type | description |
| --- | --- |
| abstract class [Actor](Microsoft.Coyote.Actors/ActorType) | Type that implements an actor. Inherit from this class to declare a custom actor. |
| class [ActorId](Microsoft.Coyote.Actors/ActorIdType) | Unique actor id. |
| class [DefaultEvent](Microsoft.Coyote.Actors/DefaultEventType) | A default event that is generated by the runtime when no user-defined event is dequeued or received. |
| class [HaltEvent](Microsoft.Coyote.Actors/HaltEventType) | The halt event. |
| enum [OnExceptionOutcome](Microsoft.Coyote.Actors/OnExceptionOutcomeType) | The outcome when an [`Actor`](Microsoft.Coyote.Actors/ActorType) throws an exception. |
| class [SendOptions](Microsoft.Coyote.Actors/SendOptionsType) | Represents a send event configuration that is used during testing. |
| abstract class [StateMachine](Microsoft.Coyote.Actors/StateMachineType) | Type that implements a state machine actor. Inherit from this class to declare a custom actor with states, state transitions and event handlers. |
| class [UnhandledEventException](Microsoft.Coyote.Actors/UnhandledEventExceptionType) | Signals that an [`Actor`](Microsoft.Coyote.Actors/ActorType) received an unhandled event. |
| class [WildCardEvent](Microsoft.Coyote.Actors/WildCardEventType) | The wild card event. |

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->