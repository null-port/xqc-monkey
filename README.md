# 🐒 xQc's Infinite Monkey Theorem 

In this experiment, I attempted to recreate the works of **William Shakespeare** using only messages from **xQc's Twitch chat**.

Yes, you read that right.

👉 [Watch the video here!](https://youtu.be/rv05dpjJ7zo)

## 📜 What’s Inside?
This project contains several Python scripts that attempt to rewrite Shakespeare's plays using Twitch chat logs from the streamer xQc. The idea is loosely inspired by the [**Infinite Monkey Theorem**](https://en.wikipedia.org/wiki/Infinite_monkey_theorem), where monkeys hitting random keys on a typewriter will eventually type out the complete works of Shakespeare. Except here, the monkeys are terminally online Twitch chatters.

## 📁 Folder Structure:
- **`full files (completed stories)`** – The final generated versions of Shakespeare’s stories, built entirely from xQc’s chat logs.
- **`grep files (unique words)`** – Contains the Shakespeare stories with only the first appearance of each unique word preserved. Repetitions are removed so that every word appears just once, in the order it originally occurred.
- **`missing words`** – Lists every word from the original text that never had a corresponding match in xQc's Twitch chat. These are the "gaps" that chat failed to fill.
- **`og files`** – The original Shakespeare texts used as input/reference for the transformations.
- **`singeline files`** – Contains the original Shakespeare texts with each word placed on its own line. No content is altered—this is simply a formatting transformation to support parsing and processing.

## 📦 Data Source
All Twitch chat logs were downloaded using [**justlog**](https://github.com/gempir/justlog), an open-source Twitch chat archive tool.
