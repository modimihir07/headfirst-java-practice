# Capstone Project Plan: QuizHub

## Description

QuizHub is a modest client-server study tool designed to reinforce core Java concepts learned throughout Head First Java. A central multi-threaded server loads quiz questions from serialized data files or plain text, accepts TCP socket connections from terminal or lightweight GUI clients, presents questions, records participant answers, and computes results. The project remains scoped for completion within three to four weeks alongside regular academic coursework.

## Features

- Multi-threaded TCP socket server managing concurrent client connections
- Object serialization and file I/O for saving and loading question banks and attempt logs
- Java Collections and Streams for shuffling questions, validating submissions, and ranking scores
- Strict exception handling covering client disconnections, invalid input, and I/O errors
- Optional Swing desktop client alongside a terminal-based interface

## Chapters Referenced

- Chapters 3 & 4: Object state, methods, and reference mechanics
- Chapter 6: Java API packages and ArrayList usage
- Chapters 7 & 8: Class inheritance, abstract classes, and polymorphic interfaces
- Chapter 11: Collections framework and generics
- Chapter 12: Lambdas and Streams for data processing
- Chapter 13: Exception handling and resource management
- Chapters 14 & 15: Swing GUI components and event listeners
- Chapter 16: File streams and object serialization
- Chapters 17 & 18: Networking, multithreading, and synchronization

## Location

Once started, this project will live in a top-level directory named `quiz-hub/`, positioned as a sibling to the chapter directories. The folder is not created in advance; it will be created when development begins.
