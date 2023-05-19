# SQL Simple Database: Video Content Classifier

Created by: Michael Bottom

## Overview:

Welcome to my repository containing a simple SQL database designed to support a neural network that classifies video content. The database stores video clips efficiently, with an emphasis on recognizing specific actions (i.e., running, jumping, standing, waving) and identifying objects (i.e., cats, dogs, cars, water, trees) in the video.

This database is designed for quick data retrieval and efficient organization, relying on primary and foreign keys for each data item. Entities include characteristics such as action/object type, associated tags, relevant time frames, video resolution, and frame clarity reference. 

## Schema:

**Primary Key**: `Vid_ID` - A unique identifier for each video.

**Entity Keys**: 

* `Action/Object` - Classification of the main action or object in the video.
* `Tag_ID` - Tags associated with the action or object.
* `Start_SEQ` and `Stop_SEQ` - Time sequence markers for the action or object's appearance.
* `Vid_RES` - Video resolution.
* `Frame_CLR` - Clarity of the frame reference.

**Foreign Key**: `Source_ID` - Identifier for the site from which the video clip was sourced.

## File Structure:

The repository consists of the following key files:

* `Database Creation.sql` - SQL script for creating the database.
* `Database ERD Creation.docx` - Document detailing the Entity Relationship Diagram (ERD) of the database.
* `Database Normalization.vsd` - Diagram demonstrating the normalization process of the database.
* `README.md` - This file, providing a high-level overview of the repository.
* `SQL Queries 1.sql` - Example SQL queries demonstrating interaction with the database.

Feel free to explore, learn, and provide feedback on this SQL database design project!
