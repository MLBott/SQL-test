# SQL Simple Database 

Author: Michael Bottom

## Summary:


The database stores video clips efficiently and is meant to support a neural network that recognizes certain actions occurring in the video (i.e. running, jumping, standing, waving) and recognizes certain objects appearing in the video (i.e. cats, dogs, cars, water, trees).

To arrange the data quickly and efficiently each item needs to have a primary key. Entities would be classifyed as  action/object, tags for action/object, relevant start time, relevant stop time, video resolution, and frame reference clarity. The foreign key would be the site that the video clip was pulled from.

> Primary Key: Vid_ID <br/>
> Entity Keys: Action/Object, Tag_ID, Start_SEQ, Stop_SEQ, Vid_RES, Frame_CLR <br/>
> Foreign Key: Source_ID

## File List

```
Database Creation.sql
Database ERD Creation.docx
Database Normalization.vsd
README.md
SQL Queries 1.sql
