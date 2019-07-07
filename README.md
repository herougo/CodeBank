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
- collect state-of-the-art implementations of popular ML problems

### How to contribute:

- (one-time 1-20 min): submit existing reusable code
  - **to the "unsorted" folder**: no refactoring necessary (the folder is meant to simply gather as much code as possible so that it can be refactored later)
  - **to the codebank project**: refactoring may be necessary (see the wiki)
- (one-time 5-20 min): view the [list of problems](https://docs.google.com/spreadsheets/d/1hSExH0DRMA_tz8XtvAW6JTcq0eSSwdB7ALaiVUtYAis) missing implementations and post links and/or import paths (e.g. torch.data.DataLoader) for recommended implementations
- (one time 5-10 min reading) adapt to the [recommended standardized interfaces](https://github.com/herougo/CodeBank/wiki) designed to be easy to use and integrate with other interfaces.
- (ongoing) submit the following kinds of ML code (formatted with the Code Bank standard interfaces)
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
