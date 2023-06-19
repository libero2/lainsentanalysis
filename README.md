# Sentiment Analysis in Serial Experiments Lain PSX
This is a Jupyter Notebooks project I did as a final for a class on computational linguistics.
As part of getting comfortable with text preprocessing, extraction, and sentiment analysis,
I used a script from a famously-heavy visual novel with a cult following, Serial Experiments Lain for PSX.

## Text Resources Used
All resources were pulled from the laingame WebGL implementation of the game in English, available [here](https://laingame.net/index.html).
<br>
More specifically, I used [ain's translation](https://ain-and-lain.tumblr.com/post/54679085486/lda-installment-three) of Lain's diary from the game.

## Python Resources Used
- For text extraction from the available PDF files, I used PyPDF.
- For sentence tokenization and sentiment analysis, [NLTK's](https://www.nltk.org/) [VADER](https://www.nltk.org/api/nltk.sentiment.vader.html) and [Punkt](https://www.nltk.org/api/nltk.tokenize.punkt.html) libraries were used.
- To work with my data and make graphics, the [Pandas](https://pandas.pydata.org/) libary was used.
<br>
<br>

## Results, Misc.
Finally, I [presented](https://docs.google.com/presentation/d/1lXN7WQ-J_2sR2mdwwvU_qVib1cha8OVnhMNSXQzVZPw/edit?usp=drive_link) my results.
<br>
<br>
At submission time I ran into some issues with proper sentence splitting with the Punkt tokenizer out of the box,
so an addition to this project was made using PunktTrainer to more properly split lines.
<br>
<br>
A huge thank you to my professor for this course, who always supported my interest in getting back into coding as a way to pursue NLP!
