# engineering-topics

## Programming
	Clean code
		Meaningful naming
		Functions done right
		Comment only what code can't say
		Error handling
		Boundaries
		SOLID
		Domain-specific types vs primitive types
		Don't fall for convenience
	Interfaces
		Make 'em easy to use right, hard to use wrong
		Postel's law
	Null references: The billion dollar mistake
	Floating point numbers aren't real (BigDecimal vs double)
	Reusability: Composition over inheritance

## Functional programming
	Immutability
	Pure functions & referential transparency
	Higher order functions
	Partially applied functions & Currying
	Functors & monads as control flow
	External vs internal iteration

## Concurrency
	Threads
	Fibers
	Actor model

## IO
	Non-blocking
		Reactive programming
			Reactive extensions (RxJava | Vert.x | Reactor)

## Design
	Patterns
		Factory method
		Abstract factory
		Adapter
		Bridge
		Chain of responsibility
		Command
		Iterator
		Mediator
		Builder
		Prototype
		Composite
		Decorator
		Memento
		Observer
		State (FSM)
		Strategy
		Singleton
		Facade
		Flyweight
		Template method
		Visitor
		Proxy
	System decomposition
		DDD
			Domain modeling
				Entities vs Value-Objects
				Aggregates
				Domain events (Event storming)
			Modules: Vertical slicing
			Bounded contexts
				Shared Kernel
				Anti-corruption layers
			
## Integration Patterns
	Remote procedure call
		HTTP
			REST + HATEOAS
			SSE
			WebSockets
		RPC + Serialization + IDL
			Avro
			Thrift
			gRPC + Protocol buffers
		RPC + Serialization
			JSON-RPC
	Messaging
		Channels
			Point-to-point
			Publish-Subscribe
			Dead letter channel
			Delivery guarantees
				Idempotence
			Message bridge
			Message bus
		Messages
			Types
				Command
				Event
				Document
			Properties
				Correlation identifier
				Message sequence
				Message expiration
				Format indicator
		Routing
			Splitter
			Aggregator
			Scatter-Gather
		Transformation
			Envelope wrapper
			Enricher
			Filter
			Normalizer
		Reactive systems
			Flow-control (back-pressure)
	File transfer
		Storage format
			Row-oriented
				Avro
			Column-oriented
				Parquet
				OCR

## Distributed Systems
	Replication
		Topologies
			Leader-Follower
			Multi-leader
			Leaderless
		Challenges
			Replication lag
			Write conflicts
			Leader election + consensus
		Extension
			CRDT (conflict-free replicated data type)
			CQRS + Event-sourcing
	Partitioning
		Challenges
			Secondary indexes
			Rebalancing
			Request routing
	Consistency
		Transactions
			ACID	
				Isolation levels
				Serializability
			Distributed transactions & consensus
			Sagas
				Orchestration vs Choreography
		Linearizability
		Ordering guarantees
	Challenges
		Faults and partial failures
		Unreliable networks
		Unreliable clocks
		Own knowledge vs Common knowledge

## Data processing
	Event time vs processing time
	Batch vs Stream
	Windows
	Watermarks
	Triggers
	Accumulation

## Architecture
	Reliability
	Scalability
		Ahmdahl's law
		Load
		Performance
	Maintainability
		Operability
		Simplicity
		Evolvability
	Security
