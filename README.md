# random-novel
This project is aiming to write a random Novel.
The process is simple, a very basic algorithm will be "writing" a novel.
The algorithm will determined the completion of the novel based on the average length of a novel (between 70,000 to 120,000 words, [source](https://jerichowriters.com/average-novel-wordcount/#:~:text=Average%20Word%20Count%20For%20A,sit%20between%2070%2C000%2D120%2C000%20words)).

For the random part, it will be in the choosing of words with a random pick from a encyclopedia (TODO: choose which API). From there, a translation from french will be done into english of the selected word. The translation will be randomly selected from the proposition done by the Deepl API. From the translated word, a *retranslation* will be done to get back a french word which corresponds approximately.
This random process of translation back and forth will have to be done 3 times for each word. The limit of 500,000 characters per month for [free](https://www.deepl.com/en/docs-api#:~:text=You%20can%20access%20the%20DeepL,characters%20per%20month%20for%20free.) of the [Deepl API](https://www.deepl.com/docs-api) will be our limit. Thus, extending the duration of writing of the novel, just as a writer is taking a lot of time to pick correctly the words composing the novel.
The 500,000 characters limit will be disctributed along the month based on the number of days minus some days to rest (just as a real human) set as 7 days per month of rest.
On the working days, we have to establish a schedule also. The random has again to play it's part here to establish if the algorithm wants to write the novel at that time or not, based on this table:
| Time  | Want to work (%) |
| ----- | ---------------- |
| 08:00 | 90               |
| 09:00 | 75               |
| 10:00 | 75               |
| 11:00 | 60               |
| 12:00 | 60               |
| 14:00 | 50               |
| 15:00 | 50               |
| 16:00 | 50               |
| 17:00 | 50               |
| 18:00 | 50               |
| 19:00 | 50               |
| 20:00 | 50               |
| 21:00 | 50               |
| 22:00 | 50               |
| 23:00 | 100              |
| 23:00 | 100              |
| 00:00 | 30               |
| 01:00 | 30               |
| 02:00 | 15               |
To keep in mind: there is a quota of characters to write per day which means that each days between 23:00 and 23:59 the "want to work" percentage is more a rush of what is left to write.
9
