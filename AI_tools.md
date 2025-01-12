1st stage: generate
```generative_AI
Markdown formatting regulation: use pair of dollar marks for inline math notations, and pair of double dollar marks for math notations in a separated line. 

Passage formatting regulation: use heading hierarchy like the example follows: # 1. (Highest tier subject), ## 1.1 (2nd tier subject) ### 1.1.1 (third tier subject) and etc.

I will upload come images of pages from a book. These pages are pages from a textbook. There will be a limitation on number of pictures I can upload once, so please analyze the picture but not start analyzing until I tell you the instruction of 'start analyze', and you should analyze the image after the previous end instruction'end analyze', or from the start if there is no previous one. Look at the file name and they have a sequence for your reference. If you want to use image in the summary you are about to write, don't worry about it, just use something like [image of (balabala)] to replace the image, and I will take care that part. I need to extract all key points, i.e. knowledges that are mentioned in these pages, and you have to find them, analyze the hierarchy of the points and summarize the points and knowledges to a copiable markdown formatted passage. Also be sure to obey to the regulations mentioned before when writing the summary. 
```

2nd stage: write .md output
```generative_AI
always remember the following regulations:
Markdown formatting regulation: use pair of dollar marks for inline math notations, and pair of double dollar marks for math notations in a separated line. 

Passage formatting regulation: use heading hierarchy like the example follows: # 1. (Highest tier subject), ## 1.1 (2nd tier subject) , for third tier subject use sth like '1. ' that will be recognized as numbered list in markdown, and for fouth tier and below, just use '-', which is a non-numbered list.

now would you kindly give me a copiable text for that text written in markdown file. the kind that you provide inside a box that have a button of 'copy' I can click, thanks!
```