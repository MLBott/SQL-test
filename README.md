SQL Database Creation 1
=======================

Author: Michael Bottom
Date: 3/19/2018

Summary:
--------

This database would be created to store video clips efficiently and allow for training of a neural network whose job it would be to recognize certain actions occurring in the video (i.e. running, jumping, standing, waving) and recognize certain objects occurring in the video (i.e. cats, dogs, cars, water, trees).

To arrange the data quickly and efficiently each item needs to have a primary key. Entities would be classifyed as  action/object, tags for action/object, relevant start time, relevant stop time, video resolution, and frame reference clarity. The foreign key would be the site that the video clip was pulled from.
Primary Key: Vid_ID
Entity Keys: Action/Object, Tag_ID, Start_SEQ, Stop_SEQ, Vid_RES, Frame_CLR.
Foreign Key: Source_ID

File List
---------
```
Database Creation.sql
Database ERD Creation.docx
Database Normalization.vsd
README.md
SQL Queries 1.sql
