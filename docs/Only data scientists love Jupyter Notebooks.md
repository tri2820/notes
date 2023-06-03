# Only data scientists love Jupyter Notebooks
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

## A Hot Mess It Is
Set aside the lack of features like autocomplete, the fundamental problem is using the same tools for multiple (inseparable) tasks

- For education (researching papers, books, etc)
- For exploring datasets and ideas
- For software development: [Netflix replaces bash script with notebooks](https://www.linkedin.com/pulse/inside-netflixs-notebook-driven-architecture-jesus-rodriguez/)

These tasks deceptively start the same: with writing some code. Yet, the code subtly serve different purposes.

- Educational code are pseudo code and highlights (code taken out of context). They are not meant to be run.
  
- Exploratory code contain hacks because they care not about reproducibility. Hacks that are both personal and systematic (sharing kernels). I would also consider executing code out-of-order a hack.
  
- SE code have to be modularized (into `load_data.py, model.py, requirements.txt, main.py`) to be testable (a must when you have new interns coming in)

Code from one task takes a lot of time (something impossible) to transfer to another. All of these different types of code cramped into a same text-code-plot format makes it so damn confusing.

## What now?
TODO