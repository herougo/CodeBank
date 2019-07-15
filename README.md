# CodeBank
A library of machine learning functionality.

### Why

- aggregate ML code in one place so that it's easy to find and reuse
- unified interface for various functionality (ie data loaders, preprocessing) for easy integration
- reduce the amount of time coding from scratch
- allow people to try out projects they would've had time to set up on their own

### Current Goals

- collect as much ML code as possible
- standardizing the interfaces of data loaders, environments, trainers, loss functions, metrics, models, etc
- including more people with the interfacing goal
- collect state-of-the-art implementations of popular ML problems

### How to contribute:

- **submit existing unrefactored, reusable code (one-time 1-10 min)**: you can submit unrefactored code to the "unsorted" folder and no refactoring is necessary (see the unsorted folder README for more details).
- **View the [list of problems](https://github.com/herougo/CodeBank/wiki/List-of-Problems) and add links to implementations (one-time 5-20 min)**: you can post code links and/or import paths (e.g. torch.data.DataLoader) for recommended implementations
- **Adapt to the [recommended standardized interfaces](https://github.com/herougo/CodeBank/wiki) (one time 5-10 min reading)**: these interfaces are designed to be easy to use and integrate with other interfaces.
- **submit properly formatted code (ongoing)** submit the following kinds of ML code formatted with the Code Bank standard interfaces (see the wiki)
  - data loaders for datasets
  - loss functions
  - metrics
  - NN models: pytorch, tensorflow, keras
  - baselines (and/or state-of-the-art) for a wide range of ML problems
  - preprocessing functions
  - utility functions

### Future Goals

[*More Details for Future Goals*](https://github.com/herougo/CodeBank/wiki/Future-Directions)

- expand to more users
- serve as a guideline for recommended ML code style
- extending interfaces to wrap around externally defined interfaces (e.g. for dataset, consider each datareader implemented in allennlp and be able to convert it into an instance of the standardized Code Bank interface)
- maintaining a large ML repo (like allennlp) with its own internal implementations of vectorizers and other modules
  - maybe when we have 10+ people actively contributing code
- creating a search engine for code
  - considered once the code collection is large enough and there is reasonable demand
