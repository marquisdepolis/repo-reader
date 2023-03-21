# repo-reader
For Python: analyses the files in a directory, finds the filenames and function calls, and uses GPT to create an explanation of what they do.

Right now the repo reads files in a folder, analyses it and gets a full summary of what it's about via GPT. It calls callgpt, a separate library, to run "ScholarGPT" to make this work. You can also ask followup questions.

It can also read from github repos directly via url, but I haven't uncommented and tested that capability yet.
