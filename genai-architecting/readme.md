# Architectural Considerations

## Functional Requirements

The system must be able to handle between 150 and 400 students at a time.

## Non-functional Requirements

The system must perform with very little latency, and needs to be scalable as
the school is expected to grow to accomodate more than 400 students.

# Business Condiserations

## Complexity

Using an LLM will require approximately 5 more parts to the system. Depending on
the setup, this value can be reduced.

## Lock-in

It is best to use an open source model to prevent a vendor from having control
over whether the system can continue and/or experience unmanageable cost increases.

## Essential Components

We will likely need guardrails, mainly to prevent student data and other
personally identifiable data from leaving the system.
