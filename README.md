# random-novel
This project is aiming to write a random Novel.
The process is simple, a very basic algorithm will be "writing" a novel.
The algorithm will determined the completion of the novel based on the average length of a novel (between 70,000 to 120,000 words, [source](https://jerichowriters.com/average-novel-wordcount/#:~:text=Average%20Word%20Count%20For%20A,sit%20between%2070%2C000%2D120%2C000%20words)).
For the random part, it will be in the choosing of words with a random pick from a encyclopedia (TODO: choose which API). From there, a translation from french will be done into english of the selected word. The translation will be randomly selected from the proposition done by the Deepl API. From the translated word, a *retranslation* will be done to get back a french word which corresponds approximately.
This random process of translation back and forth will have to be done 3 times for each word. The limit of 500,000 characters per month for free of the Deepl API will be our limit. Thus, extending the duration of writing of the novel, just as a writer is taking a lot of time to pick correctly the words composing the novel.
