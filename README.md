# AlgorithmExErcises

Repository for following along the book *Introduction to Algorithms Third Edition*

## Installation

```bash
git clone git@github.com:phereford/algorithm_ex_ercises.git
cd algorithm_ex_ercises
mix deps.get
```

## Goals 
The *Introduction to Algorithms* book is an amazingly detailed book with
algorithms and data structures. Every week, we will be reading about one 
algorithm and implementing it in Elixir. We are not doing code golf, or looking
to compete/optimize our solutions against one another. We are working through
each algorithm systematically and running performance benchamrks against each of
our implementations.  
  
## Structure
Every module created for your algorithm or data structure will need documentation
to show an understanding of Big-O notation and the time/space requirements for
the algorithm. For all of us that are partaking in this adventure, let's follow
this format for naming conventions:  
```elixir
defmodule AlgorithmExErcises.Phereford.InsertionSort do
end
```  
Let's utilize our github username for namespacing each of our implementations. 
As a note, we do not have to merge back into this master repository if you don't
want to. The idea here is by issuing a PR and merging back into this, we can see
all of the different paths to implementing a specific type of algorithm and work
towards understanding the nuances of each solution.  
  
### Performance Testing
In addition, we should include benchee performance tests to keep track of performance
of every implementation and every algorithm.  
  
### Unit Testing
I love unit testing. If you have the time to unit test, by all means go for it.
The purposes of the book club is not to create production ready algorithms. The
intent is to create a working knowledge of algorithms, their time space constraints
and how they perform in comparison to one another. If you want to unit test, go
for it but it is by no means mandatory.
