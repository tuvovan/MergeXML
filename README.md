# Merge XML

## Content
The idea of this file is that:
Thinking about you are doing a object detection project and you have to label many object by yourself.
The job is then divided to many people, one has responsibility for one object.

In the final, you have a folder (say Eye_drop) as shown below, inside is many videos which have been decompsed to frames.
And inside those folder, there are images, and x folders corresponding to x objects that you want to label.

This file help you to merge those xml file. Lets say, in folder "2000..." below, there is 1 image that have 2 objects.
However, these object are labeled by 2 different persons so they are in different folders.

Use this file and BOOM, they are merged.

### Prerequisites
- Python
- xml

## How to run
Place the file outside of the root folder as follow,

Run: 
    ```
    python merge_xml.py -f "Folder-you-want-to-run-on"
    ```
## Usage
python merge_xml.py     [-h] 
                        [--folder]
```