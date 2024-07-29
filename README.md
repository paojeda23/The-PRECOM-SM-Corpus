# Corpus PRECOM

## Introduction
Collection of native spanish texts of PRECOM project where several pathological gambling topics are included.

## Description
In first place, a quick explanation of each group of texts made for de corpus:
- **Betting**: in this class, betting chats gathered from the popular messaging app 'Telegram' are included, where discussions about loosing, winning and betting money between teenager users have place. Primarily, sport is the scope where youngsters are more interested in gamble money.
- **Gambling**: this set includes text extracted from the streaming platform 'Twitch', heavely famous among young users. In these broadcasts, streamers gamble over online slot, roulette, blackjack, poker and other games of chance platforms. Users discuss in the stream chat about what is happening on screen and their own experiences in gambling.
- **Lootboxes**: this collection gathers text from 'Twitch' and the worldwide known online forum 'Reddit'. As for 'Twitch' texts, these compile live videos where streamers open lootboxes from different videogames in front of dozens of viewers. The users speak among them in the chat about the retransmission and their experience in buying this type of products. Texts from 'Reddit' are more focused on telling an addiction experience that worries (or worried) the maker of the thread and other forum participants answer, trying to encourage him/her and give some advice on how to overcome the addiction they are goign through.
- **Trading**: this group is made of 'Telegram' chats where users discuss about investing and speculation on financial instruments in order to obtain some benefit. It is tradicionally associated to stock market but after the cryptocurrency fever youngsters lately prefer to gamble their money in cryptocoins with the uncertainty of wether or not they will earn more income than they invested.
- **Videogames**: finally, this set is made of 'Reddit' threads again, where users expose their  addiction to certain videogames, specially online. As in lootboxes collection, teens answer to the creator of the thread and chat with him/her about their problem and possible solutions.

## Organization
After the analysis of the information and the conclusions obtained from it, it was decided to organize the text corpus over the frequency of interaction of the users participating on it, due to the close relation the number of interactions have with users' emotions and some other metrics measured.
The corpus is organized in .CSV files as DataFrames where information is organized in several columns (user column is anonymized):
- **Date**: the timestamp of the message in format: *dd/mm/yyyy hh:mm:ss*
- **User**: the user that wrote the message.
- **Message**: the message that one concrete user send.
- **Platform**: the platform where the message belongs.
- **InteracFrequency**: this tag can get two values: MF (most frequent) and LF (least frequent) depending on the interaction frequency of the user who wrote the message.

## Interaction frequency
A series of files based on the interaction frequency of each user are included in this section of the corpus. For each gambling group, information about the number of interactions of each user every day, week and month is contained in these documents. The users are anonymized for this purpose as well.
