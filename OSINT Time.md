# Challenge Name: OSINT time

##Category: OSINT / Forensics

##Difficulty: Easy

##Challenge Description
Paste the original challenge text about Leo refusing to share his vacation location and posting a sloth photo.


##Approach



1. Saw the sloth image and immediately started researching where sloths are commonly found geographically, trying to identify the location visually — without fully reading the challenge description first

2. After that didn't lead anywhere conclusive, went back and read the full challenge text which hinted the flag was stored with "other image details"

3. Recognized this as a clue pointing to other image data. Googled what that could mean. Which took me to exifdata.com

4. Downloaded the sloth image from the challenge

5. Extracted the EXIF metadata using an online EXIF viewer (EXIFdata.com)

6. Found the flag hidden in the Image Description and User Comment fields


##Lesson Learned

Always read the full challenge description before diving in! A simple misread sent me down a rabbit hole of sloth geography before the answer was hiding in the metadata all along.

<details>
<summary>Hint</summary>

Check the image metadata!

</details>

<details>
<summary>Flag (spoiler!)</summary>

MetaCTF{bienvenidos_a_costa_rica}

</details>
