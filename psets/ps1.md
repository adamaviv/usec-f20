# Problem Set 1

** Due via Github classroom on <u>Sept. 15</u>**

## Problem 1 (35 points)

Github Classroom Link: [https://classroom.github.com/a/xi9p2K1_](https://classroom.github.com/a/xi9p2K1_)

In light of the "Why Johnny Can't Encrypt" paper, you will perform an expert evaluation of a current encryption tool. Pick a tool from [Wikipedia's list](https://en.wikipedia.org/wiki/Encryption_software) of encryption tools. In particular, consider tools listed at the bottom of that page under the "disk encryption," "email clients," and "OTR" messaging categories. Download and install (or, if applicable, simply enable) the tool you chose. Inspired by the Johnny paper, perform an expert evaluation of the tool.

You should turn in four paragraphs describing:

* Paragraph 1: State what tool you chose and describe the steps you took in your expert evaluation. Essentially, we want you to explain your methodology.
* Paragraph 2: What usability flaws identified in the Johnny paper still persist 15 years later in this tool? Describe them.
* Paragraph 3: What usability flaws does this tool have beyond those previously identified in the Johnny paper? Describe them.
* Paragraph 4: What usability flaws identified in the Johnny paper have been addressed to your satisfaction? How were they addressed?

If you believe any of those paragraphs is not applicable (e.g., the tool has no usability flaws not described in the Johnny paper), instead briefly explain why you believe it is not applicable.

In the github classroom assignment, create a document called `evaluation.md` and write your report using markdown formatting. 

## Problem 2 (15 points) 

Github Classroom Link: https://classroom.github.com/a/9C2r5DG5

In class, we watched excerpts of the [12-minute video](https://vimeo.com/56881481) Edward Snowden made for Glenn Greenwald. We laughed; we cried. Can you do better? 

In three paragraphs or less, try to explain everything a journalist needs to know about using whatever encryption tool you examined in Problem 1. Do your best! 

In addition to the paragraph you write, write one or two sentences reflecting on this experience. (For example, Have you communicated everything the journalist needs to know? If not, what's missing?)

In the github classroom assignement, create a document called `advice.md` and `refelections.md` to write your report using markdown formatting. 

## Problem 3 (35 points)
Github Classroom Link: https://classroom.github.com/a/dWaF_lCS

In this assignment, you will complete a journal/diary study (on your self) attempting to send me an encrypted email, and me then sending an encrypted email back to you. **Note that you should complete this by Monday Sept. 14th to ensure that I may properly contact you in return with the /secret message/.**

### Step 0: prepare

This is a journaling/diary study exercise so you should prepare for that first. You should record the following information as part of your quest to complete this problem. You should have sections in your diary entry for each of the following information.

1. Any google/search queries you perform, with a brief description of your thought process when searching
2. Any websites you opened, the url with a brief explanation
3. Any tools you installed/uninstalled and the context for selecting that tool 
4. Your exploration of using that tools, the correct and incorrect comands you tried and the context of those commands
5. Any confusions or questions you had while using the tool
6. The steps you took in completing the task?
7. Finally, provide 3-to-4 paragraphs (with multiple sentences per-paragraph!) that is a full narrative, from start to end, in completing this task, as if you were relaying the story to someone in a documentary movie entitled "I sent an encrypted email."

Essentially, try and record yourself as you do this and describe your entire process so that someone else can review your process and understand your thought process. 

Submit a file in the git repo called `diary.md` that contains your diary of this task. 

### Step 1: send

Investigate an email client that will enable you to do PGP/SMIME email. Install it and generate a PGP public/private key. I have already done this and my public/private key pair for PGP email. My PGP public key is below

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

mQENBF9HrmwBCADdk2m9BKY9L74073E07y4xAV1Y3965er4XbZyqOReqoqIxYLCN
AiwwBweLGuZ9tA5BOSYPEe04g1AL5klVfU+2PoE7pQXWpreU1HxypI+fg3dsGriB
SKV2eU0avOADly3NsQjr8/OUHe24oblBF4h00uZX0WGd++L/9ec4YS8MajaeLB5N
kDunVV192XhnnhJyD0ZsgnB1D9WuxedwzfQ5vnJuccfuPw4vJjHOlYHLuUtyv25x
SVogyGEz0pmskiwbI9tVC6EgRBftsdQ2mEqvCI6EgfTfEJ6Lh6G0s3oYUuFHnMaT
VNd5AO3acQh/LIXoeWUNBh0hBct8bgRA9BPdABEBAAG0GUFkYW0gQXZpdiA8YWF2
aXZAZ3d1LmVkdT6JAVQEEwEIAD4WIQRXWMj+cK8qfGD0OPGjep+lgSdyQwUCX0eu
bAIbAwUJA8JnAAULCQgHAgYVCgkICwIEFgIDAQIeAQIXgAAKCRCjep+lgSdyQ8De
B/9q9L6CA44ycRLA65pwrBkHYS4W7wtQ8Js1uPw8jFf+wqz6S6OhqRRY48y7zxkN
l5cp+2HTZbmxz6Ua9192ijul18FZqZbuAZ0IbqatP+j8XVvOToO+lmsfz/T+2s9Y
nyzE+sOFR96L7kVObv3Q61H/RbcifIVs09Q2ikhNJT6gW+ja8eehnDGXHvkYN2j2
SntjNZZRaICp+Eb71iZhi8FPvIfpby0ED8fDTxxPPPoYa1d/XVn+5VkFMAQKloyP
oG7/iCxFem9ivbplT0DJlbBrsLeNR/88arwxwVh8gb5uqN7DYdA+Cn03hLZ7q02e
Q3vSVYY/KrInOUi5piaZ7gwbuQENBF9HrmwBCACib+AYjyDwjXoc/6WyigleVu1Q
S5zJfLN9FWajiu/z1Adzz474zm0g8NwSzlcpl8L1/AQXAJ4AkHJUx/EzbmUf/OWb
R2sj7J+QO7X3bNm35dSq2b2BPEgcc79kI8kuUs2AW2YwtGFcvN5R0wxzRhxl27yx
i05sVXJ8LHk7x51BSFUNreIUYE8q3GGOktD+c3ibS+ddVbIrZSaG2dRAg1TovJjh
6JfbIW04GKnrRCnrNyTmQn4ao4EvZmV7iKTC8KkId8mi7kFmPdhqea4rOLok/fLu
VSg7ynH5cwVqDVxYnksdLF+9JG33fDmO7R1oRMJSRzwBfg5ojpIs0Qspp7VTABEB
AAGJATwEGAEIACYWIQRXWMj+cK8qfGD0OPGjep+lgSdyQwUCX0eubAIbDAUJA8Jn
AAAKCRCjep+lgSdyQ03oCACJqPheHpFeNYseB1ZeJb2SW6XWYfCeaMLSbpOFowx+
Uofv10LvmT7iwizCriqF4D5IfWJFfX2ti2s3R1guREg0cbdk7d3JcnpVEKyc4MEH
W4n+FOMXv7kOdBk+q6WVsldawwKXlSwenlrX8f8CJO9jqTu1k34qLLl2HVXtOi1+
EWu4Shu6VxT1oA2npUQ1my8U23hTjtirc99SHYm0B3+z+GTyRRbVcf2RrROuKaHK
kkpExDO+nI9VTpzoc4SFPrZwoF+Hr/6Zq6BC2s3LBrbsvZ8WVsmgFlQdQ7ytoYap
k0kisJt5VLP4pir3wCn7xgIrO1cXRtz0/73flwUAwCw/
=FYBY
-----END PGP PUBLIC KEY BLOCK-----
```

Send me an encrypted message that contains the answers to the following questions:

1. What is the name of the secure email client you used to complete this task
2. How many secure email clients did you try first?
3. Was this easy or hard? Explain.

This email should be sent `aaviv@gwu.edu` and it should ALSO be signed by your public key.  Use the following subject line

```
csci6907: ps1: <your name>
```

Note that I may reply in the clear if you do not properly encrypt and/or sign your message. 

#### Step 2: receive

As part of the email you send in Step 1, or as a new email, send me your public key for your GWU email address (or another email address of your choosing). I will then send you an encrypted message containing a secret message. The message should be both encrypted and signed by the public key above. Put that secret message in a file called `secret.md` as part of your submission.

#### Step 3: reflect

Compete your diary/narrative of this experience. It should be about 1-to-2 pages long (8-9 paragraphs), so please reflect on the entire experience. We will use these diaries as part of the next assignment to practice qualitative coding.


## Problem 4 (10 points, and you MUST complete this to pass this class)

Github Classroom Link: https://classroom.github.com/a/fzUTpED4

Complete the online Human Subjects Protection Training Requirement by following the instructions at the [GW Office of Human Research](https://humanresearch.gwu.edu/citi-courses-accounts-info). You should complete the **Social & Behavioral Research** course. Whence complete, include a copy of your certificate in your submission call `certificate.pdf`

**Note that you do not have to pay for this course if you follow the instructions at the link above. GW pays for a school wide license.**

## Problem 5 (5 points, and you are strongly recommended to complete this)

Github Classroom Link: https://classroom.github.com/a/A12K6vfx

Request access to the Qualtrics Site License for SEAS. Information can be found on the [GW SEAS Computing Facility help page](https://seascf.seas.gwu.edu/qualtrics).

Then create a simple survey with the following questions, and then publish the survey and take it yourself. The questions are:

* What topics in this course most excite you?

* What topic in this course least excites you?

* Describe your earliest experience with using a computer? 

To prove you've done the task, include a link to the published survey in your submission in a file called `survey.md` as well as a pdf of the results as presented by Qualtrics called `results.pdf`. 



