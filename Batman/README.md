# Batman Challenge — BRK-CYS 2026

## Challenge Information

* **Category:** Osint
* **Difficulty:** Medium
* **Author:** Suzan Alsabbah
* **Event:** BRK-CYS 2026
Step 1 — Initial Observation

The challenge begins with a single image shared by a friend, showing a semi-desert environment with a mysterious box placed in the area.

At first glance, the image does not contain explicit metadata or location tags, suggesting that the solution must rely on visual analysis and hidden clues.

The flag format is:

BRKCYS{Ans1,Ans2,Ans3,Ans4}
Step 2 — Visual Investigation
___

The image was carefully examined for:

Landmarks
Terrain patterns
Hidden text or steganographic data
Shadows and environmental clues

No obvious EXIF data was found, which suggests that the challenge relies on deeper OSINT techniques rather than surface metadata.
___
Step 3 — Hidden Data Extraction

Since many OSINT challenges embed information inside images, the file was processed using a steganography tool.

This revealed a hidden string:

Jam Go
___

Step 4 — Name Reconstruction

The extracted fragments were analyzed:

“Jam” → could relate to James
“Go” → could relate to George

By combining common real-world naming patterns, the most likely full name is:

James George

___
Step 5 — Social Media Investigation

The name was searched across:

Facebook
Instagram
LinkedIn

Eventually, a suspicious account was found:

James.george92

This account contained a post featuring:

The same geographical environment as the challenge image
A group trip photo matching the scene
Step 6 — Data Extraction from Post

From the identified post, the following information was extracted:

📍 Location: Ajloun
📅 Date: 2/9/2018
👥 Number of people: 4
___
Further confirmation came from visual matching between the OSINT image and the post.


Question	Answer
Place	Ajloun
Person	James George
Date	2/9/2018
People	4
Final Flag
BRKCYS{Ajloun,James George,2/9/2018,4}
