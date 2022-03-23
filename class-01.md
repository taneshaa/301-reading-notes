# Readings: Introduction to React and Components

## Reading
[Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

1. What is a “component”? 
  A component is a modular, portable, replaceable and reusable set of functionality that encapsulates its function and exporting it as a higher-level interface. It's a software object which is suppose to interact with other components encapsulating functionality or a set of functionalities. It has a defined interface and conforms to behavior common to all components within an architecture. Software component can be thought of as a unit of composition with a specified interface and context dependencies. It can be deployed independently and is subject to the composition by third parties. 
2. What are the characteristics of a component?
  * Reusability - designed to be reused in different situations in different applications. 
  * Replaceable - may be freely substituted with other similar components 
  * Not-Context-Specific - Designed to operate in different environments and contexts
  * Extensible - Can be extended from existing components to provide new behavior
  * Encapsulated - Depicts the interfaces, allow the caller to use its functionality but doesn't expose details of the internal variables or state
  * Independent - Designed to have minimal dependencies on other components 
3. What are the advantages of using component-based architecture? 
  * Ease of deployment - As new compatible versions become available, easier to replace existing versions with no impact on other components or the system
  * Reduce Cost - the use of third party components allows you to spread the cost of development and maintenance 
  * Ease of development - Components implement well-known interfaces to provide defined functionality, allowing development without impact on other parts or system
  * Reusable - Can be used to spread development and maint cost across several applications or systems
  * Modification of Technical Complexity - Component modifies the complexity through the use of a component container and its services 
  * Reliability - Overall system reliability increases since each reliability of each individual component enhances reliability of the whole system via reuse. 
  * System Maintenance and Evolution - Easy to change and update the implementation without affecting the rest of the system 
  * Independent - independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development. 

[What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)

1. What is “props” short for: properties which are returned as an object
2. How are props used in React: for passing data from one component to another
3. What is the flow of props: data with props are being passed in a uni-directional flow (one way from parent to child) and is read-only, cannot be changed by child.


