## Introduction to React and Components

I think this is important because I believe this will give me the tools to make components using react. This will clean up and restore the functionality of my site. The primary objective of component-based architecture is to ensure component reusability.

### Component-Based Architecture
#### What is a “component”?
A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.


#### What are the characteristics of a component?
A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.
A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.
A component can have three different views − object-oriented view, conventional view, and process-related view.

Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.

#### What are the advantages of using component-based architecture?
The software system is decomposed into reusable, cohesive, and encapsulated component units.

Each component has its own interface that specifies required ports and provided ports; each component hides its detailed implementation.

A component should be extended without the need to make internal code or design modifications to the existing parts of the component.

Depend on abstractions component do not depend on other concrete components, which increase difficulty in expendability.

Connectors connected components, specifying and ruling the interaction among components. The interaction type is specified by the interfaces of the components.

Components interaction can take the form of method invocations, asynchronous invocations, broadcasting, message driven interactions, data stream communications, and other protocol specific interactions.

For a server class, specialized interfaces should be created to serve major categories of clients. Only those operations that are relevant to a particular category of clients should be specified in the interface.

A component can extend to other components and still offer its own extension points. It is the concept of plug-in based architecture. This allows a plugin to offer another plugin API.

Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

#### What is “props” short for?
property

#### How are props used in React?
to deploy a component

#### What is the flow of props?
 React’s data flow between components is uni-directional (from parent to child only).

