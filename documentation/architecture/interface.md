# Interface: Template

* **Name:** Interface Name (Replace "Template" above)
* **Reference Number:** Optional, reference ID
* **Version**: Version number

## Resources

* The heart of the interface documentation is the set of resources it provides
* Resources are typically operations, but can be messaging endpoints, shared memory or data streams
* For each resource, provide the syntax, semantics and error handling
* The syntax is the signature of the resource
* The semantics is a description of what happens when the resource is used, along with pre- and post-conditions and usage restrictions
* Error handling lists exceptions and error codes that can occur when the operation is executed

## Data Types and Constants

* Describe new data types created for the data passed to or returned by resources in the interface
* Describe also any constants defined in the interface to hold commonly-used values that make programming against the interface more convenient.
* The following data types are created for the data passed to or returned by resources in the interface:
* `int`: A signed integer value.
* `float`: A floating-point number.
* `string`: A sequence of characters.
* `bool`: A boolean value.
The following constants are defined in the interface:
* `MAX_INT`: The maximum value for an `int`.
* `MIN_INT`: The minimum value for an `int`.
* `MAX_FLOAT`: The maximum value for a `float`.
* `MIN_FLOAT`: The minimum value for a `float`.
* `MAX_STRING_LENGTH`: The maximum length for a `string`.
These data types and constants are used to make programming against the interface more convenient.

## Error Handling

* Describe error conditions that can be raised by the resources on the interface
* This section has the error handling description that is common to two or more resources
* Error handling is also described in the Resources section separately for each resource.

## Variability

* If the interface allows the element to be configured in any way, then these configuration parameters and how they affect the semantics of the interactions in the interface must be documented here

## Quality Attribute Characteristics

* Document what quality attribute characteristics, such as performance or reliability, the interface makes known to its users.

## Rationale

* Record the reasons behind the design of the interface

## Issues

* Are there any issues that need to be resolved?

## Usage Guide

* Describe step-by-step one or more examples of using the interface
