This project is an attempt made by me to understand text summarization. I implemented two papers which used supervised method to extract the summary of given paper. The basic idea of these papers was to create a graph associated with text where the vertices represent the entity to be ranked and the edges indicate some relationship(which can be syntactic or semantic) between vertices, and then PageRank algorithm is used to rank these vertices.

The two papers that I explored were: LexRank: www.cs.cmu.edu/afs/cs/project/jair/pub/volume22/erkan04a-html/erkan04a.html TextRank: https://web.eecs.umich.edu/~mihalcea/papers/mihalcea.emnlp04.pdf

Scripts: testRankWord.py : implements textRank algorithm for keyword extraction. testRankSent.py : implements textRank algorithm for sentence summarizaton. lexRank.py : implements lexrank algorithm for sentence summarization.

usage: script_name number_of_top_entities document_containing_text example - ./lexrank.py 3 data.txt

Dependency: Nltk, numpy