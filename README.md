# Presentation-Original
The original PowerPoint, before I used AI to reformat it. The content and structure are mine; in the final version AI handled layout and cut the slide text down so the audience listens instead of reading ahead.

 ---
# Whats Here
original.pptx: my deck before reformatting
final.pptx: the version I presented
change_log.docx: before/after text for every slide, with word counts and layout notes

---
# Setup
I made the PowerPoint and compiled all the images and content in detail.
I then ran through the presentation 5x and dictated it to my phone and had Claude create a word doc for each run
I uploaded my version of the PowerPoint along with the last 3 transcribes of the run and prompted as follows:

 ---
# Prompts
In a fresh Claude instance:

 ---
Me: i am presenting this project for a job interview tomorrow. currently the presentations content and images are good but there are too many words on the slide, i ran through the presentation a few times and am uploading them here. what i want you to do is to simplify the wording without changing the content, voice, or assets per slide and reformat the slides to look better in a presentation environment. the main thing is i don't want the audience to be reading ahead i want them to be listening to me present. attached is the transcripts. do not change the order of the slides or bullet points, don't add any numbers from the transcripts as i plan on saying those (unless a vague reminder for me to remember to say the number but no specific number from transcripts on the slide.) Preserve technical terms exactly, including their qualifiers. For example "3.7 V nominal" not "3.7 V", ‘tryptophan synthase’ not "synthesis" the modifiers are not filler. The main goal is to reduce wordcount so the audience isn't reading ahead. Output the new PowerPoint file and a word file of all changes you made. if the transcripts differ and you have to make a choice about witch one to follow, prefer "Xcimer_RunThrough3_AsSpoken.docx" if anything is unclear ask questions before starting to work on the project.

 ---
Claude: I’ll read the deck and the three run-through transcripts first, then decide whether anything needs clarifying before I edit.
Your slides already contain some numbers (e.g. ~$200K, 34 LEDs, 250/800/1000 C, 1,747 m^2/g, 1.5mm OD → 4mm, 60 C, 17 rings/256 slices). I won't add any from the transcripts — but should the ones already on the slides stay?

---
Me: if a number is already on a slide, leave it. The ones not to add are the ones that only appear in the transcripts.

---
Claude: How far should the visual reformat go? Either way, every image stays in the corner you point to in your talk ('top right', 'bottom right', and so on)

---
Me: i prefer a darker style, you have freedom with the scale and alignment of images to make the slides look better but keep assets with its respective slide don't add any assets only reformat

---
Claude: Should I put your Run-Through 3 wording in each slide's speaker notes? Only you see notes, in presenter view, so the numbers you plan to say would be there as a backup.

---
Me: No leave speaker notes empty

---
Claude: I’ve made the new deck and the Word change log. Every slide now has fewer words (2,015 down to 1,352, about a third fewer) and a dark style. Slide order, bullet order, the images on each slide and every number that was already on a slide are unchanged, and the speaker notes are empty.

What changed:

Wording: I cut filler phrasing, not content. Technical terms kept their qualifiers. I checked every slide against the original and found no missing terms and no new numbers.
Layout: each project or section name is now the headline, with “Presentation options” or “Passion project” as a small label above it. “Issue” and “Solution” are colored labels instead of bullets. The six capstone steps on slide 7 are a grid of short panels.
Images: they’re resized and aligned, and none of them overlap text any more. I used Run-Through 3 to keep each image in the spot you point to while you talk (“top right,” “bottom right,” “the image on the right”). On slide 15, the middle photo used to hang off the bottom of the slide; it now fits.

Check before tomorrow:

Slide 3 reminders: I added two small gray cues, “(trim %)” and “(cost per transition)”, as prompts to say those figures. They contain no numbers, and you can delete them if you’d rather not have them.
Slide 16: “(3.7v)” now reads “(3.7 V nominal)”, following your example.
Small fixes: “fiber nylon” is now “carbon fiber nylon”, and the title typo “from factor” is now “form factor”. Units are written consistently (for example “250 °C” instead of “250 C”). The change log lists every one of these.
Slide 20: it still says the original deck and prompts are on your GitHub as “Presentation-Original”. Make sure that’s uploaded before the interview.

The change log has a before/after table for every slide, the word counts, and the layout notes. I checked the layout in a preview rather than in PowerPoint itself, so flip through it once before you present. The fonts are all Arial, so it should look the same on any computer.
