# Only data scientists love their Jupyter Notebooks
Bar of entry for notebooks is low because it looks like a research paper.

- Markdown comment
- Code
- Plot

Other mediums vowed to replace it, but would have a hard time explaining what they are:

- [Postman Flows](https://blog.postman.com/postman-flows-the-next-generation-of-software-development/)
- [VizierDB](https://vizierdb.info)

## Praise
Make code more tangible (output is directly under)

## Criticism
Check [I Don't Like Notebooks](https://docs.google.com/presentation/d/1n2RlMdmv1p25Xy5thJUhkKGvjtV-dkAIsUXP-AL4ffI).

- Hidden state
- Requirement management is bad
- Hard-coded path & constants everywhere

Why don't we just use code?

- No inline plot
- Sharing is hard
- Reading is usually not top-down

## Conclusion
Set aside the lack of features like autocomplete, the fundamental problem is using the same tools for multiple (inseparable) tasks

- For education (researching papers, books, etc)
- For exploring datasets and ideas
- For software development: [Netflix replaces bash script with notebooks](https://www.linkedin.com/pulse/inside-netflixs-notebook-driven-architecture-jesus-rodriguez/)

These tasks always start the same with writing some code. Yet eventually, these code serves different purpose:

- Educational code evolves to pseudo code and highlights (code that are taken out of context)
- Exploratory code is used only once, hence begin ran out-of-order and irreproducible, and contain hacks that are both personal and systematic (sharing kernels)
- SE code is modularized (into `load_data.py, model.py, requirements.txt, main.py`) to be testable (given when you have new interns coming in)

All of these different types of code cramped into a same text-code-plot format makes it so confusing.